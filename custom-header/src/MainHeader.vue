<template>
    <div style="border: solid; border-color: red; width: 700px">
        <h1>Custom Header</h1>
    </div>
</template>
  
<script>
export default {
    name: 'MainHeader',
    props: {
        msg: String
    }
}
</script>
  
<style scoped>
h3 {
    margin: 40px 0 0;
}

ul {
    list-style-type: none;
    padding: 0;
}

li {
    display: inline-block;
    margin: 0 10px;
}

a {
    color: #42b983;
}</style>
  