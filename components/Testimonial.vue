<template>
    <section id="testimonial">
        <h1 id="title">Our Client Says About US</h1>
        <div class="testimonial_container">
            <div class="testimonial_card">
                <div class="person">
                    <img src="../assets/profile.jpeg" alt="">
                </div>
                <div class="details">
                    <div class="info">
                        <h2>Name: Luis Enrique</h2>
                        <p>Designation: Professor</p>
                    </div>
                    <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Tempora aliquid fuga excepturi maxime natus
                        similique! Consectetur voluptates ratione a omnis perspiciatis, excepturi tenetur pariatur earum,
                        sit doloremque ad dolor dignissimos sequi. Amet esse consectetur error sequi sapiente temporibus
                        officia dolore dolorum delectus ipsum doloremque labore ad quia iure a eum odit sunt aspernatur,
                        deleniti quos vero provident architecto eligendi? Ratione?</p>
                </div>
            </div>
            <div class="testimonial_card">
                <div class="person">
                    <img src="../assets/profile.jpeg" alt="">
                </div>
                <div class="details">
                    <div class="info">
                        <h2>Name: Luis Enrique</h2>
                        <p>Designation: Professor</p>
                    </div>
                    <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Tempora aliquid fuga excepturi maxime natus
                        similique! Consectetur voluptates ratione a omnis perspiciatis, excepturi tenetur pariatur earum,
                        sit doloremque ad dolor dignissimos sequi. Amet esse consectetur error sequi sapiente temporibus
                        officia dolore dolorum delectus ipsum doloremque labore ad quia iure a eum odit sunt aspernatur,
                        deleniti quos vero provident architecto eligendi? Ratione?</p>
                </div>
            </div>
            <div class="testimonial_card">
                <div class="person">
                    <img src="../assets/profile.jpeg" alt="">
                </div>
                <div class="details">
                    <div class="info">
                        <h2>Name: Luis Enrique</h2>
                        <p>Designation: Professor</p>
                    </div>
                    <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Tempora aliquid fuga excepturi maxime natus
                        similique! Consectetur voluptates ratione a omnis perspiciatis, excepturi tenetur pariatur earum,
                        sit doloremque ad dolor dignissimos sequi. Amet esse consectetur error sequi sapiente temporibus
                        officia dolore dolorum delectus ipsum doloremque labore ad quia iure a eum odit sunt aspernatur,
                        deleniti quos vero provident architecto eligendi? Ratione?</p>
                </div>
            </div>
        </div>
    </section>
</template>

<style>
#testimonial #title {
    text-align: center;
    margin: 30px;
    font-size: 24px;
    background: #121FCF;
    background: linear-gradient(to right, #121FCF 44%, #CF1512 100%);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;

}

.testimonial_container {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    width: 94%;
    margin: 60px auto;
    gap: 10px;
}

.testimonial_card {
    position: relative;
    background: white;
    box-shadow: 5px 6px 10px rgba(0, 0, 0, 0.4);
    padding: 10px;
    border-radius: 10px;
    text-align: center;
}

.testimonial_card img {
    width: 100px;
    height: 100px;
    border-radius: 50%;
    position: absolute;
    border: 2px solid gray;
    top: -50px;
    left: 40%;
}

.testimonial_card .details {
    margin-top: 50px;
    text-align: left;
}

.info {
    margin-bottom: 20px;
}

.details .info h2 {
    margin: 0;
}
</style>