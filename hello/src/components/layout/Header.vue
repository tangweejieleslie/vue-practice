<template>
    <div class="head">
        <h2>This is the header</h2>
        <ul>
            <li>Item 1</li>
            <li>Item 2</li>
        </ul>
    </div>
</template>

<script>
export default {
    name:'Head'
}
</script>

<style scoped>
.head {
    background: #4f4f4f;
    color: #fafafa;
    font-size: 1.3em;
    padding: 20px;
    margin-bottom: 10px;
    text-transform: capitalize;
}

ul {
    list-style: none;
    text-align: center;
}

li {
    display: inline;
    margin: 5px;
    font-size: 0.8em;
    text-transform: uppercase;
}


</style>
