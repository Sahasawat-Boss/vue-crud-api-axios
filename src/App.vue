<template>
  <div>
    <nav class="p-4 bg-teal-100 font-semibold ">
      <RouterLink to="/" class="mr-4" active-class="text-blue-400">Home</RouterLink>
      <RouterLink to="/about" active-class="text-blue-400">About</RouterLink>
    </nav>
    <div class="p-6">
      <RouterView />
    </div>
  </div>
</template>
