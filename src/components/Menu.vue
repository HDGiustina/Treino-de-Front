<template>
    <div class="menu">
        <div class="logo py-3">
            <img src="https://portalsuperingresso.s3.amazonaws.com/eleventickets180x127.png" alt="logo" class="w-28">
        </div>
        <nav class="">
            <li class="menu-nav px-10">
                <a href="">Dashboard</a>
            </li>
            <li class="menu-nav px-10"><a href="">Relatórios</a></li>
            <li class="menu-nav px-10"><a href="">Conteúdos</a></li>
            <li class="menu-nav px-10"><a href="">Layout</a></li>
            <li class="menu-nav px-10"><a href="">Traduções</a></li>
            <li class="menu-nav px-10"><a href="">Clientes</a></li>
            <li class="menu-nav px-10"><a href="">Configurações</a></li>
        </nav>
        <div>
            svg
            <h1></h1>
            <p></p>
            <button></button>
        </div>
    </div>
</template>

<script>
    export default {
        name: "Menu",
    }
</script>

<style scoped>
    .menu {
        height: 100vh;
        background-color: #262D35;
    }

    li{
        color: #ABAFB0;
        font-size: 18px;
    }
    .logo {
        display: flex;
        justify-content: center;
        background-color: #1A1A1A;
    }
    
    .menu-nav:hover, a:hover{
        background-color: #505050;
    }
</style>