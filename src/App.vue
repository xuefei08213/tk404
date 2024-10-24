<template>
  <div class="min-h-screen bg-gray-100">
    <header class="bg-white shadow">
      <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
        <h1 class="text-xl font-semibold py-3">我的博客</h1>
        <nav class="mt-4">
          <router-link to="/" class="mr-4">首页</router-link>
          <router-link to="/about" class="mr-4">关于</router-link>
          <router-link to="/contact">联系</router-link>
        </nav>
      </div>
    </header>
    <main class="py-6 flex-grow">
      <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
        <router-view></router-view>
      </div>
    </main>
    <footer class="bg-gray-800 text-white py-6">
      <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
        <p>&copy; 2024 我的博客. 版权所有.</p>
      </div>
    </footer>
  </div>
</template>

<script>
export default {
  name: 'App'
};
</script>