<template>
<div>
  <h1>Profesores</h1>
    <div class="areas">
      <a href="" class="artes"><h2>Área de Artes</h2></a>
      <a href="" class="ciencias"><h2>Área de Ciencias</h2></a>
      <a href="" class="humanidades"><h2>Área de Humanidades</h2></a>
    </div>
    <h1>Funcionarios</h1>
    <div class="funcionarios">
      <a href="" class="artes"><h2>Aseo</h2></a>
      <a href="" class="artes"><h2>Directiva</h2></a>
      <a href="" class="artes"><h2>Paradocentes</h2></a>
    </div>
</div>
</template>

<style scoped>

.areas {
  display: flex;
  justify-content: space-around;
}

.areas a  {  
  align-items: center;
  color: white;
  display: flex;
  justify-content: center;
  text-decoration: none;
}

.artes {
  background: chartreuse;
  width: 30%;
  height: 20vh;
}

.ciencias {
  background: gold;
  width: 30%;
}

.humanidades {
  background: firebrick;
  width: 30%;
}

 .funcionarios {
   display: flex;
   justify-content: space-around;
 }

.funcionarios a  {
  align-items: center;
  color: white;
  display: flex;
  justify-content: center;
  text-decoration: none;
}

</style>