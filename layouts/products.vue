<template>
  <div>
    <header>
      <div>
        <NuxtLink to="/products">Nuxt Dojo Merch</NuxtLink>
      </div>
    </header>

    <!-- output the page content -->
    <div>
      <slot />
    </div>
    <footer>
      <ul>
        <li><NuxtLink to="/">Home</NuxtLink></li>
        <li><NuxtLink to="/about">About</NuxtLink></li>
        <li><NuxtLink to="/products">Products</NuxtLink></li>
      </ul>
    </footer>
  </div>
</template>

<style>
.router-link-exact-active {
  color: #12b488;
}
</style>
