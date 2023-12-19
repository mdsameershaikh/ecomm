<template>
    <div class="head">
        <div class="brand-name">Jaden</div>
        <div class="nav-items">
            <div>Home</div>
            <div>Products</div>
            <div>About</div>
            <div>Contact</div>
        </div>
    </div>
</template>
<style scoped>
.head {
    background: brown;
    position: fixed;
    top: 0px;
    color: yellow;
    width: 100%;
    left: 0px;
    height: 50px;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.brand-name {
    margin-left: 1%;
}

.nav-items {
    display: flex;
    justify-content: space-evenly;
    width: 35%;
}
</style>
<script>

export default {
    name: 'page-head',
    components: {

    }
}
</script>