<template>
    <footer class="footer">
        <div class="footer-wrapper">
            <div class="footer-info">
                <div class="contact-info">
                    <img class="logo" alt="logo" src="./assets/LogoO.png">Interno
                </div>    
            </div>
            <div class="wrapper">   
            <div>
                <img class="logo-footer" alt="twitter" src="./assets/tw.png">
            </div>
            <div>
                <img class="logo-footer" alt="in" src="./assets/in.png">
            </div>
        </div>
        </div>   
        <div> 
        <div class="content">
            <div>
            <ul class="list">Страницы
                <p class="menu-list-link">
                    <a class="link" href="#">Домой</a>
                </p>
                <p class="menu-list-link">
                    <a class="link" href="#">Проект</a>
                </p>
                <p class="menu-list-link">
                    <a class="link" href="#">Блог</a>
                </p>
            </ul>
            </div>
            <div>
                <ul class="list">Контакты
                    <p class="contact" >55 East Birchwood Ave. Brooklyn, New York 11201</p>
                    <p class="contact">contact@interno.com</p>
                    <p class="contact">(123) 456 - 7890</p>
                </ul>
            </div>
        </div>
    </div>

    </footer>
</template>
  
  <script>
  export default {
    name: 'CompFooter',
    
  }
  </script>
  
  <!-- Add "scoped" attribute to limit CSS to this component only -->
 <style scoped>

.footer {
        margin-top: 250px;
        display: flex;
        justify-content: space-between
    }

    .content, .contact-info, .wrapper {
        display: flex;
    }

    .logo-footer {
        margin: 30px 35px 0 0;
    }

    .list {
        margin: 0;
        font-family: 'Akrobat', Helvetica, sans-serif;
        font-size: 20px;
        padding-left: 130px

    }

    .link, .contact {
        color: #4d5053; 
        font-family: 'Akrobat', Helvetica, sans-serif;
        text-decoration: none;
        font-size: 13px;
        margin-top: 40px
    }
</style>
  