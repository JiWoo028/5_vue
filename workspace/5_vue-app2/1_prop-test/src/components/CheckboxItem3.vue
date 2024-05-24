<template lang="">
    <input type='checkbox' :checked='checked'>{{number}} {{name}}
    <br>
</template>
<script>
    export default {
        name : 'checkboxItem',
        props : {
            number : [Number, String],
            name : {
                type : String,
                requied : true
            },
            checked : {
                type : Boolean,
                required : true
            }
        }
    }
</script>
<style lang="">
    
</style>