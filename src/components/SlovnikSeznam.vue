<template>
    <div class="container">
        <span> Перевести слово {{slovo}} на Seznamu</span>
        <button @click="openSlovnikSeznam" >Preloz</button> 
    </div>
    
</template>


<script>
export default {
    data(){
        return {
            slovo:"S-L-O-V-aO"
        }
    },
    methods: {
        openSlovnikSeznam(){
           this.slovo ="otkrito"
        }
    }
}
</script>


<style scoped>
.container{
    margin: 0px 10px 15px 10px;
    border: 1px solid black;
    padding: 3px 5px;
    background:#999;
    display: flex;
}
</style>