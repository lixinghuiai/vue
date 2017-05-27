<template>
    <div id="me">
        <myname name="xinghui"></myname>
        <myage age="age"></myage>
    </div>
</template>
<script>
    import Name from './myname.vue';
    import Age from './myage.vue';
    export default{
        components:{"myname":Name, "myage":Age}
    }
</script>