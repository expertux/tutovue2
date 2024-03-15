<template>
<h3>{{ counterop }} </h3>
<button @click="addCounter">IncrementarOption</button>
</template>

<script lang="ts">
    import {defineComponent} from "vue";
    export default defineComponent({
    name: 'CounterOption',
    data() {
        let counterop = 0;
        return{counterop}
    },
    methods:{
        addCounter(){
            this.counterop++
        }
    }
})

</script>
 
<style>

</style>