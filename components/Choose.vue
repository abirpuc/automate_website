<template>
    <section id="choose_section">
        <div class="overlay">
            <h1 class="heading">Why Choose Us</h1>
            <div class="card_container">
                <div class="title_card">
                    <h1 class="title">Expertise in Automation</h1>
                    <p>Automate IT Limited specializes in automation solutions. We have a proven track record of streamlining processes, reducing manual work, and increasing efficiency through automation.</p>
                </div>
                <div class="title_card">
                    <h1 class="title">Cost Savings</h1>
                    <p>Automation often leads to cost savings in the long run. By choosing Automate IT Limited, you may be able to reduce labor costs and minimize errors in your processes</p>
                </div>
                <div class="title_card">
                    <h1 class="title">Customized Solutions</h1>
                    <p>They understand that every business is unique. Automate IT Limited can provide tailored automation solutions to fit your specific requirements and objectives.</p>
                </div>
                <div class="title_card">
                    <h1 class="title">Support and Maintenance</h1>
                    <p>Ongoing support and maintenance are critical for the success of automation initiatives. Automate IT Limited likely offers such services to keep your systems running smoothly.</p>
                </div>
                <div class="title_card">
                    <h1 class="title">ROI</h1>
                    <p>Evaluate the potential return on investment (ROI) that their automation solutions can offer. Automate IT Limited should be able to provide you with a clear picture of the financial benefits.</p>
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
#choose_section {
    background-image: url('../assets/choose.jpg');
    background-size: cover;
    background-position: center;
    background-repeat: no-repeat;
    width: 100%;
    height: 850px;
}

.overlay{
    width: 100%;
    height: 850px;
    background-color: rgba(0, 35, 87, 0.7);
    position: absolute;
    z-index: 999; 
}

#choose_section .heading {
    font-size: 24px;
    text-align: center;
    color: white;
}

.card_container{
    width: 90%;
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    margin: 50px auto;
    gap: 20px;
}

.title_card {
    width: 300px;
    height: 300px;
    padding: 20px;
    border-radius: 10px;
    background-color: rgba(255, 255, 255, 0.507);
    box-shadow: 5px 4px 30px rgba(0, 0, 0, 0.4);
}

.title_card .title {
    text-align: center;
    font-size: 20px;
    font-family: 'open sans' sans-serif;
    color: black;
}

.title_card p {
    margin: 0 auto;
    line-height: 20px;
    text-align: justify;
}
</style>