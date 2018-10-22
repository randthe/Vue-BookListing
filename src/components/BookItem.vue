<template>
    <li>{{book.title}} : {{book.author}}</li>
</template>
<script>
export default {
    name: 'BookItem',
    data() {
        return { name: 'All Books', 
                 props: ['book']
               };
    }
}
</script>
<style>
    li{
        display: block;
        margin: 0 10px
    }
</style>
