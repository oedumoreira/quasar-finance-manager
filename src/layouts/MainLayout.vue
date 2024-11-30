<template>
  <q-layout view="lHh Lpr lFf">
    <q-header elevated class="bg-gradient-to-tl from-purple-600 to-indigo-400 text-white">
      <q-toolbar>
        <q-toolbar-title class="font-bold">
          Finanças Pessoais e Investimentos
        </q-toolbar-title>

        <div class="relative inline-block">
          <img class="inline-block size-[35px] rounded-full"
            src="https://images.unsplash.com/photo-1568602471122-7832951cc4c5?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=facearea&facepad=2&w=300&h=300&q=80"
            alt="Avatar">
          <span
            class="absolute top-0 end-0 block size-2 rounded-full ring-2 ring-white bg-teal-400 dark:ring-neutral-900"></span>
        </div>
      </q-toolbar>
    </q-header>
    <q-page-container>
      <router-view />
    </q-page-container>
  </q-layout>
</template>

<script setup>
import { ref } from 'vue'

defineOptions({
  name: 'MainLayout'
})

</script>
