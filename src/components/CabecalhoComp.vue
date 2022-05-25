<script>
export default {};
</script>
<template>
  <header id="header">
    <div class="logo">
      <img id="imglogo" width="90" height="90" src="@/assets/logoo.png" />
    </div>
    <nav class="menu link">
      <a>   </a>
      <RouterLink to ="/home">HOME</RouterLink>
      <a>   </a>
      <RouterLink to ="/animais">ANIMAIS</RouterLink>
      <a>   </a>
      <RouterLink to ="/doacoes">DOAÇÕES</RouterLink>
      <a>   </a>
      <RouterLink to ="/login">LOGIN</RouterLink>
    </nav>
  </header>
</template>
<style>
.menu {
  display: flex;
  margin-top: 30px;
  color: #beaee2;
  font-size: 1.2em;
  font-family: "Times New Roman", Times, serif;
}

.menu > a {
  padding-left: 20px;
}

.menu > a:hover {
  font-size: 1.25em;
}
</style>
