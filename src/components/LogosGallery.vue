<template>
    <div class="logos-wrappper">
        <h2 class="title-header">
            Example Logos Component
        </h2>
        <div class="item-logos">
            <img class="logo-baru" alt="Vue logo" src="../assets/logo.png">
        </div>
        <div class="item-logos">
            <img class="logo-baru" alt="Vue logo" src="../assets/logo.png">
        </div>
        <div class="item-logos">
            <img class="logo-baru" alt="Vue logo" src="../assets/logo.png">
        </div>
        <div class="item-logos">
            <img class="logo-baru" alt="Vue logo" src="../assets/logo.png">
        </div>
        <div class="item-logos">
            <img class="logo-baru" alt="Vue logo" src="../assets/logo.png">
        </div>
        <div class="item-logos">
            <img class="logo-baru" alt="Vue logo" src="../assets/logo.png">
        </div>
        <div class="item-logos">
            <img class="logo-baru" alt="Vue logo" src="../assets/logo.png">
        </div>
    </div>
</template>

<script>
export default {
  name: 'LogosGallery'
}
</script>

<style scoped>
.title-header {
    text-align: left;
    margin-bottom: 20px;
}

.logos-wrappper {
    width: 80%;
    overflow: hidden;
    margin: 0 auto;
}

.item-logos{
    float: left;
    background: rgb(196, 224, 33);
    width: 100px;
    height: 100px;
    margin: 10px;
    border-radius: 20%;
}

.item-logos .logo-baru{
    width: 100%;
    height: 100%;
    object-fit: cover;
    border-radius: 20%;
}
</style>
