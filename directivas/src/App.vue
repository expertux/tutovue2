<template>
  <p>...</p>
   <ExampleSelective />
    <CounterOption/>
    <p> aca inicia por composition</p>
    <CounterComposition/>
    <p>aca inicia por composition pero menos lienas codigo  resumido</p>
    <CounterCompositionSmall />
</template>

<script lang="ts" setup>
import ExampleSelective from './components/ExampleSelective.vue'
import CounterOption from './components/CounterOption.vue'
import CounterComposition from './components/CounterComposition.vue'
import CounterCompositionSmall from './components/CounterCompositionSmall.vue'
</script>

<style>
h1 {
  color: green;
}
</style>
