<template>
    <header>
        <img src="../assets/logo-marley-reads.jpeg" alt="logo">
        <h1>Galvanize Reads</h1>
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
    display: flex;
    
}

header h1 {
    display: flex;
    align-items: center;
    margin: 0;
    color: chocolate;
    font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
}

</style>
