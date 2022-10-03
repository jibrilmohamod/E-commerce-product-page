<template>
 <div
  class="w-10/12 m-auto h-[10vh] border border-red-600 flex items-center justify-between"
 >
  <nav>
   <ul class="flex">
    <li>
     <router-link to="/"><h1 class="text-2xl">Sneakers</h1></router-link>
    </li>
    <li>
     <router-link to="/about">Collections</router-link>
    </li>
    <li>
     <router-link to="/about">Men</router-link>
    </li>
    <li>
     <router-link to="/about"> About </router-link>
    </li>
    <li>
     <router-link to="/about"> Contact </router-link>
    </li>
   </ul>
  </nav>
  <div>
   <!-- cart -->
   <nav>
    <ul class="flex">
     <li>
      <router-link to="/cart">Cart</router-link>
     </li>
     <!-- profile image -->
     <li>
      <router-link to="/profile"
       ><img class="w-10 border h-12 rounded-full" src="" alt=""
      /></router-link>
     </li>
    </ul>
   </nav>
  </div>
 </div>
</template>

<script setup></script>

<style lang="scss" scoped></style>
