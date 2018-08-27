<template>
    <header>
        <img src="../assets/logo-marley-reads.jpeg" alt="logo">
        <h1>Marley Reads</h1>
    </header>    
</template>

<script>
export default {
    name: 'Header'
}
</script>

<style>
header {
    display: flex;
    flex-direction: row;
    justify-content: center;
    align-content: space-between;
    
}

header img {
    grid-row: 1/3;
    grid-column: 1/2;
    height: 100px;
    width: auto;
}

header h1 {
    grid-row: 1/2;
    grid-column: 2/3;
    margin: 0;
    color: chocolate;
    font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
}

</style>
