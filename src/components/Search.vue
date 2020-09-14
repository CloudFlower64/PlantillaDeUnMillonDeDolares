<template>
    <div class="search">
        <h2 class="title">¿Qué estas buscando?</h2>
        <input class="input" type="input" placeholder="Buscar..." name="Search" id="">
    </div>
</template>

<style scoped>

.title {
    color: white;
    font-size: 25px;
}

.input {
    background-color: rgba(255, 255, 255, 0.1);
    border: 2px solid white;
    border-radius: 25px;
    color: white;
    font-size: 16px;
    height: 50px;
    outline: none;
    padding: 0px 20px;
    width: 75%;
}

::placeholder {
    color: white;
}

</style>