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
    margin: .5em;
    
}

header h1 {
    display: flex;
    align-content: center;
    margin: .5em;
    color: rgb(231, 106, 17);
    font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
    font-size: 2em;
}

</style>
