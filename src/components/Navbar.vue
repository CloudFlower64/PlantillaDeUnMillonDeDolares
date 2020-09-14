<template>
    <div class="navbar">
        <header>
            <img src="../assets/logo.png" alt="logo-colegio">
            <h2>Colegio El Arrayan</h2>
        </header>
        <div class="navlinks">
            <ul>
                <li><a href="">Material</a></li>
                <li><a href="Profesores.vue">Funcionarios</a></li>
                <li><a href="">Multimedia</a></li>
            </ul>
        </div>
    </div>
</template>

<script>
export default {
  name: 'NavBar',
  props: {
    msg: String
  }
}
</script>

<style scoped>
    .navbar {
        display: flex;
        justify-content: space-between;
        align-items: center;
        background: gold;
    }

    .navbar header {
        display: flex;
        align-items: center;
    }

    .navbar header img {
        width: 60px;
        height: 50px;
    }

    .navbar header h2 {
        color: white;
    }

    .navlinks ul li {
        font-family: Helvetica, sans-serif;
        display: inline-flex;
        list-style: none;
    }

    .navlinks ul li a {
        color: white;
        text-decoration: none;
        margin: 5px;
    }
</style>