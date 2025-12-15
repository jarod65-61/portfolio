<template>
  <header class="site-header">
    <a href="#home" class="logo"> 
      <img src="@/assets/home.png" alt="Logo" />
    </a>

    <nav class="nav-menu">
      <a href="#presentation">Présentation</a>
      <a href="#creations">Créations</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>
</template>

<style scoped>

.site-header {
  position: fixed;
  top: 0;
  left: 0;
  right: 0;
  display: flex;
  justify-content: space-between;
  align-items: center;
  background-color: #ff7f4c; 
  padding: 1rem 2rem;
  border-radius: 20px;
}
.logo img {
  width: 50px;
  height: 50px;
}
.nav-menu a {
  color: #ffffff;
  text-decoration: none;
  font-weight: bold;
  margin-left: 1.5rem;
  transition: color 0.3s ease;
}
.nav-menu a:hover {
  color: #ffe4e1;
}

main {
  padding-top: 80px; 
}
</style>