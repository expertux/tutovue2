<template>
    <h3>{{ countersmall }}</h3>
    <button @click="addCounter"> IncrementarSmall</button>
</template>
    
    <script lang="ts" setup>
        import { Ref, ref} from "vue"
        let countersmall:Ref = ref(0)
        const addCounter = ():void => {
                    countersmall.value++
                }
    </script>
    
    