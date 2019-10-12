<template>
    <div id="photo-collage" class="flex-container">
        <div>
            <img src = "../assets/bridal-bouquet.jpg" alt="Bridal Bouquets on Stairs" height="250" width="375">
        </div>
        <div>
            <img src = "../assets/dog-boy.jpg" alt="Boy with Dog" height="250" width="375">
        </div>
        <div>
            <img src = "../assets/dog-girl.jpg" alt="Dog and Girl" height="250" width="375">
        </div>
        <div>
            <img src = "../assets/flower-hand.jpg" alt="Flower and Hand" height="250" width="375">
        </div>
        <div>
            <img src = "../assets/groom.jpg" alt="Wedding Groom Picture" height="250" width="375">
        </div>
        <div>
            <img src = "../assets/kids-circle.jpg" alt="Kids sitting in a circle" height="250" width="375">
        </div>
        <div>
            <img src = "../assets/leaves.jpg" alt="Leaves on a plant" height="250" width="375">
        </div>
        <div>
            <img src = "../assets/morning-primrose.jpg" alt="Morning Primrose" height="250" width="375">
        </div>
        <div>
            <img src = "../assets/rain-window.jpg" alt="Rain on Window" height="250" width="375">
        </div>
        <div>
            <img src = "../assets/rose.jpg" alt="Rose Picture" height="250" width="375">
        </div>
        <div>
            <img src = "../assets/salt.jpg" alt="Salt Crystal" height="250" width="375">
        </div>

    </div>
</template>

<script>
    export default {
        name: 'PhotoCollage',
    }
</script>

<style scoped>
    .flex-container {
        display: flex;
        flex-wrap: wrap;
    }

    .flex-container > div {
        margin: auto;
        text-align: center;
    }
</style>