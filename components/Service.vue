<template>
    <section id="service_section">
        <h1>Our Service</h1>
        <div class="container">
            <div class="service_card">
                <img src="../assets/logo_1.jpeg" alt="">
                <h1>Academy-Institute Management System </h1>
            </div>
            <div class="service_card">
                <img src="../assets/logo_2.png" alt="">
                <h1>SmartKit-School Accessories</h1>
            </div>
            <div class="service_card">
                <img src="../assets/logo_2.png" alt="">
                <h1>SmartKit-School Accessories</h1>
            </div>
        </div>
    </section>
</template>

<style>
#service_section {
    padding: 30px 100px;
}

#service_section h1 {
    font-size: 30px;
    text-align: center;
    font-family: sans-serif;
    background: #121FCF;
    background: linear-gradient(to right, #121FCF 44%, #CF1512 100%);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;

}

.container {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 20px;
    margin: 0 auto;
    width: 90%;
}

.service_card {
    text-align: center;
    padding: 20px;
    border-radius: 10px;
    border: 1px solid gray;
    box-shadow: 6px 8px 20px rgba(0, 0, 0, 0.4);
}

.service_card img {
    width: 200px;
    height: 200px;
    border-radius: 50%;
}

.service_card h1 {
    font-size: 18px;
    font-weight: 300;
}</style>