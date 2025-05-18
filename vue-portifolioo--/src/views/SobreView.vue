<template>
  <div class="min-h-screen bg-pink-100 text-pink-900 p-6">
    <div class="max-w-6xl mx-auto space-y-10">
      <header class="text-center">
        <h1 class="text-5xl font-bold mb-2">Sobre Mim</h1>
        <p class="text-lg">Minha trajetória na tecnologia.</p>
      </header>

      <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-6">
        

        <section class="bg-pink-200 rounded-xl shadow-md p-6">
          <h2 class="text-3xl font-semibold mb-3">Habilidades</h2>
          <ul class="list-disc list-inside text-lg space-y-1">
            <li>HTML, CSS, Tailwind, JavaScript</li>
            <li>Vue.js, Vite, Git e GitHub</li>
            <li>Consumo de APIs e integração com backend</li>
          </ul>
        </section>

        <section class="bg-pink-200 rounded-xl shadow-md p-6">
          <h2 class="text-3xl font-semibold mb-3">Oque Estudo?</h2>
          <p class="text-lg">
           Estudando de tudo um pouco, mas gostando de estudar e trabalhar com back-end.
          </p>
        </section>

        <section class="bg-pink-200 rounded-xl shadow-md p-6">
          <h2 class="text-3xl font-semibold mb-3">Como Comecei?</h2>
          <p class="text-lg">
           Estudando programação desde 2021, com curso tecnico na etec com ensino medio e me aprofundando na faculdade para entrar na área.
          </p>
        </section>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'SobreView',
};
</script>

<style scoped>
</style>





