<template>
 <div
  class="w-10/12 m-auto h-[10vh] border border-red-600 flex items-center justify-between"
 >
  <nav class="border h-full">
   <ul class="flex items-center h-full">
    <li class="mr-14">
     <router-link to="/"
      ><h1 class="text-4xl font-bold">sneakers</h1></router-link
     >
    </li>
    <li class="mr-14">
     <router-link to="/about"
      ><h2 class="text-gray-400">Collections</h2></router-link
     >
    </li>
    <li class="mr-14">
     <router-link to="/about"><h2 class="text-gray-400">Men</h2></router-link>
    </li>
    <li class="mr-14">
     <router-link to="/about">
      <h2 class="text-gray-400">Women</h2>
     </router-link>
    </li>
    <li class="mr-14">
     <router-link to="/about"
      ><h2 class="text-gray-400">About</h2>
     </router-link>
    </li>
    <li class="mr-14">
     <router-link to="/about"
      ><h2 class="text-gray-400">Contacts</h2>
     </router-link>
    </li>
   </ul>
  </nav>
  <div>
   <!-- cart -->
   <nav>
    <ul class="flex">
     <li>
      <router-link to="/cart"><i class="fas fa-cart-shopping"></i></router-link>
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
