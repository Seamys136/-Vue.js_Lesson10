<template>
    <header class="header">
      <div class="title-logo">
        <img class="logo" alt="logo" src="../assets/LogoO.png">Interno
        <ul class="menu-list">
          <li class="menu-list-link">
            <a class="link" href="#">Домой</a>
          </li>
          <li class="menu-list-link">
            <a class="link" href="#">Проект</a>
          </li>
          <li class="menu-list-link">
          <a class="link" href="#">Блог</a>
        </li>
      </ul>
    </div>
  </header>
</template>
  
  <script>
  export default {
    name: 'CompHeader',
    
  }
  </script>
  
  <!-- Add "scoped" attribute to limit CSS to this component only -->
  <style scoped>

.header {
  padding: 20px 120px 0px 180px;
  width: 98%;
  line-height: 35px;
   
}

.title-logo {
  font-size: 40px;
  
}

.logo {
  width: 30px;
}

.link {
    color: #292f36; 
    font-family: 'Akrobat', Helvetica, sans-serif;
    text-decoration: none;
    font-size: 20px;
  }

.menu-list-link {
    display: inline-block;
    margin-right: 25px;
    margin-left: 25px;
}

.menu-list {
    text-align: right;
    margin: 0;
    margin-top: -35px;
}
</style>
  