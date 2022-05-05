<template>
  <div class="p-8">
    <h1 class="text-4xl">Contact Me</h1>
    <p class="py-2" v-for="paragraph in $store.state.contact" :key="paragraph">
      {{ paragraph }}
    </p>
    <p class="py-2 text-2xl font-bold">Phone: <small>09-13-83-33-34</small></p>
  </div>
</template>
