<template>
  <div class="min-h-screen bg-gray-50">
    <nav class="bg-white shadow-sm">
      <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
        <div class="flex justify-between h-16">
          <div class="flex items-center">
            <router-link to="/" class="text-xl font-bold text-blue-600">
              CloudTix
            </router-link>
          </div>
          <div class="flex items-center space-x-4">
            <router-link to="/" class="text-gray-700 hover:text-blue-600 px-3 py-2 rounded-md text-sm font-medium">
              首页
            </router-link>
            <router-link to="/contact" class="text-gray-700 hover:text-blue-600 px-3 py-2 rounded-md text-sm font-medium">
              联系我们
            </router-link>
            <router-link to="/terms" class="text-gray-700 hover:text-blue-600 px-3 py-2 rounded-md text-sm font-medium">
              用户协议
            </router-link>
            <router-link to="/privacy" class="text-gray-700 hover:text-blue-600 px-3 py-2 rounded-md text-sm font-medium">
              隐私协议
            </router-link>
          </div>
        </div>
      </div>
    </nav>

    <main>
      <router-view />
    </main>

    <footer class="bg-gray-800 text-white mt-auto">
      <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-8">
        <div class="flex justify-between items-center">
          <div>
            <p class="text-sm">&copy; 2025 CloudTix. All rights reserved.</p>
          </div>
          <div class="flex space-x-6">
            <router-link to="/contact" class="text-sm text-gray-300 hover:text-white">
              联系我们
            </router-link>
            <router-link to="/terms" class="text-sm text-gray-300 hover:text-white">
              用户协议
            </router-link>
            <router-link to="/privacy" class="text-sm text-gray-300 hover:text-white">
              隐私协议
            </router-link>
          </div>
        </div>
      </div>
    </footer>
  </div>
</template>

<script setup>
</script>
