<template>
    <section id="client_section">
        <div class="overlay">
            <h1 id="client_title">Our Client</h1>
            <div class="client_container">
                <div class="client_card">
                    <img src="../assets/cosic.png" alt="">
                </div>
                <div class="client_card">
                    <img src="../assets/bay_development.png" alt="">
                </div>
                <div class="client_card">
                    <img src="../assets/cocsol.png" alt="">
                </div>
            </div>
        </div>
    </section>
</template>

<script>
export default {

}
</script>

<style scoped>
#client_section{
    background-image: url('../assets/business-partner.webp');
    height: 500px;
    background-size: cover;
    background-position:center;
}
.overlay {
    height: 500px;
    width: 100%;
    background-color: rgba(0, 35, 82, 0.7);
    position: absolute;
    z-index: 999;
}
#client_title {
    text-align: center;
    font-size: 28px;
    color: white;
}

.client_container {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    width: 60%;
    margin: 20px auto;
    gap: 20px;
}

.client_container img {
    width: 200px;
}
</style>