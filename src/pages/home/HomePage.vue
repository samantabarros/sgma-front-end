<template>
  <div class="row flex justify-center items-center menu-cards">
    <div class="q-pa-md">
      <router-link to="/alunos" style="text-decoration: none">
        <div
          class="bg-blue-6 row justify-center items-center card-aluno"
          style="width: 400px; height: 300px"
        >
          <div class="column items-center">
            <q-icon name="groups" size="100px" color="white" />
            <p class="text-white" style="font-size: 30px">Alunos</p>
          </div>
        </div>
      </router-link>
    </div>
    <div class="q-pa-md">
      <router-link to="/modulos" style="text-decoration: none">
        <div
          class="bg-deep-purple-6 row justify-center items-center card-aluno"
          style="width: 400px; height: 300px"
        >
          <div class="column items-center">
            <q-icon name="auto_stories" size="100px" color="white" />
            <p class="text-white" style="font-size: 30px">Módulos</p>
          </div>
        </div>
      </router-link>
    </div>
  </div>
</template>

<script setup></script>
<style scoped>
.card-aluno:hover {
  transform: scale(1.05);
}

.card-aluno{
  transition: transform .4s;
}

.menu-cards {
  min-height: calc(100vh - 50px - 42px);
}
</style>
