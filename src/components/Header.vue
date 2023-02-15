<template>
<header>
    <h1>{{ title }}</h1>
    <ButtonItem text="Add item" color="green"/>
    <ButtonItem text="Another item" color="blue"/>
    <ButtonItem text="A item" color="red"/>
    <ButtonItem text="okay" color="blue"/>

</header>
</template>


<script>


import ButtonItem from './Button.vue'

export default{
    name: 'HeaderTag',
    props:{
        title:String,
    },
  
    components:{
       ButtonItem,

    }
    

}

</script>


<style scoped>

header{
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin-bottom: 20px;
}


</style>