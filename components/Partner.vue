<template>
    <section id="partner_section">
        <h1 id="partner_title">Our Partner</h1>
        <div class="partner_container">
            <img src="../assets/sonali_bank.jpeg" alt="">
            <img src="../assets/metronet.png" alt="">
            <img src="../assets/shurjopay.png" alt="">
            <img src="../assets/mobishastra.jpeg" alt="">
        </div>
    </section>
</template>

<script>
export default {

}
</script>

<style scoped>

#partner_title {
    text-align: center;
    margin: 30px;
    font-size: 24px;
    background: #121FCF;
    background: linear-gradient(to right, #121FCF 44%, #CF1512 100%);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;

}

.partner_container {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    width: 60%;
    margin: 20px auto;
    gap: 20px;
}

.partner_container img {
    width: 200px;
}
</style>