<template>
    <section id="section">
        <div class="overlay">
            <div class="card_container">
                <div class="title_card">
                    <h1>Your Automation Partner</h1>
                    <p>Your Automation Partner" is more than just a motto; it's our promise to you. We're here to simplify
                        and enhance your automation journey. Let's work together to achieve efficiency, productivity, and
                        success.</p>
                </div>
                <div class="title_card">
                    <h1>Education-Centric Automation</h1>
                    <p>We specialize in crafting automation solutions specifically designed for the education industry. From
                        student enrollment and grading to administrative workflows, we understand the nuances of educational
                        processes and tailor our solutions to meet these demands.</p>
                </div>
                <div class="title_card">
                    <h1>Empowering Educators</h1>
                    <p>Our solutions are designed not to replace educators, but to elevate them. By automating repetitive
                        tasks, we give educators more time to connect with students, develop innovative curriculum, and
                        foster a nurturing learning environment.</p>
                </div>
                <div class="title_card">
                    <h1>Data-Driven Insights</h1>
                    <p>We provide educators and administrators with valuable insights by harnessing the power of data. Our
                        solutions help you make informed decisions that lead to improved student engagement, retention, and
                        academic success.</p>
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
#section {
    height: 600px;
    background-image: url('../assets/meeting.jpg');
    background-size: cover;
    background-position: center;
    position: relative;
}

.overlay {
    height: 600px;
    width: 100%;
    background-color: rgba(0, 35, 82, 0.7);
    position: absolute;
    top: 0;
    left: 0;
    z-index: 1;
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
    padding: 20px;
    border-radius: 10px;
    color:white;
    background-color: rgba(36, 92, 117, 0.712);
    box-shadow: 5px 4px 30px rgba(0, 0, 0, 0.4);
}

.title_card h1 {
    text-align: center;
    font-size: 20px;
    font-family: 'open sans' sans-serif;
}

.title_card p {
    margin: 0 auto;
    line-height: 20px;
    text-align: justify;
}
</style>