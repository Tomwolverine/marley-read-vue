<template>

    <div class="home">
        <Header />
        <img class="book" src="../assets/logo.png" alt="">
        <h2>Authors</h2>
        <img class="person" src="../assets/logo.png" alt="">
        <h2>Books</h2>
    </div>
</template>

<script>
import Header from './Header'
export default {
    name: 'Home',
    components: {
        Header
    }
    
}
</script>

<style>
.home {
    display: flex;
    flex-direction: row;
    justify-content: space-between;
}
</style>
