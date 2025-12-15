<template>
    <footer>
    <div class="social-links">
      <a href="https://www.instagram.com" target="_blank">
        <img src="@/assets/instagram.png" alt="Logo Instagram" />
      </a>
      <a href="https://github.com/jarod65-61" target="_blank">
        <img src="@/assets/github.png" alt="Logo GitHub" />
      </a>
      <a href="https://mail.google.com/mail/" target="_blank">
        <img src="@/assets/mail.png" alt="Logo Google Mail" />
      </a>
    </div>
     <small>
      Dernière mise à jour :
      <time>{{ lastUpdate }}</time>
    </small>
  </footer>
</template>

<script>
export default {
  data() {
    return {
      lastUpdate: ""
    };
  },

  mounted() {
    const date = new Date(document.lastModified);
    this.lastUpdate = date.toLocaleDateString("fr-FR");
  }
};
</script>

<style scoped>

footer {
  background-color: #e9835b; 
  color: #ffec8b;          
  padding: 1.5rem 0;        
  text-align: center;
  border-radius: 20px;      
  display: flex;
  flex-direction: column;
  align-items: center;
  gap: 0.75rem;            
  margin: 1rem;
}

.social-links {
  display: flex;
  justify-content: center;
  gap: 1rem;
}

.social-links img {
  width: 32px;
  height: 32px;
  border-radius: 50%;
  transition: transform 0.3s ease;
}

.social-links img:hover {
  transform: scale(1.2);
}

</style>
