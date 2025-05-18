<template>
  <div class="min-h-screen bg-pink-100 text-pink-900 flex items-center justify-center p-6">
    <div class="bg-pink-200 rounded-xl shadow-md p-6 max-w-md w-full text-center space-y-4">

      <!-- Imagem de perfil -->
      <div class="w-32 h-32 mx-auto rounded-full overflow-hidden">
        <img :src="fotoPerfil" alt="Foto de perfil" class="w-full h-full object-cover">
      </div>

      <!-- Título e apresentação -->
      <h1 class="text-3xl font-bold">Bem-vindo(a)!</h1>
      <p class="text-base">
        Olá, me chamo <strong>Barbara</strong>, uma estudante de Analise e Desenvolvimento de sistemas pela UNIMAR.
        Conheça um pouco dos meus trabalhos.
      </p>
    </div>
  </div>
</template>

<script>
import foto from '@/assets/img/barbara.jpeg';

export default {
  name: 'HomeView',
  data() {
    return {
      fotoPerfil: foto
    };
  }
};
</script>










