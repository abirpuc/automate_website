<template>
    <section id="contact_section">
        <div class="heading">
            <h1 class="title">LET'S TALK</h1>
            <p class="details">Contact us to discuss your ideas and concept, and we would love to give you a no obligation
                free quote for bringing your need to reality.</p>
        </div>
        <div class="contact_container">
            <div class="contact_card">
                <div class="contact_info">
                    <div class="icon">
                        icon
                    </div>
                </div>
                <h2>GIVE US A CALL</h2>
                <div class="contact_info_item">
                    <p>Helpline</p>
                    <p>09643224488</p>
                </div>
            </div>
            <div class="contact_card">
                <div class="contact_info">
                    <div class="icon">
                        icon
                    </div>
                </div>
                <h2>CHAT US</h2>
                <div class="contact_info_item">
                    <p>WhatsApp</p>
                    <p>09643224488</p>
                </div>
            </div>
            <div class="contact_card">
                <div class="contact_info">
                    <div class="icon">
                        icon
                    </div>
                </div>
                <h2>Write To Us</h2>
                <div class="contact_info_item">
                    <p>sales@deshuniversal.com</p>
                </div>
            </div>
            <div class="contact_card">
                <div class="contact_info">
                    <div class="icon">
                        icon
                    </div>
                </div>
                <h2>
                    DEMO/QUOTE REQUEST</h2>
                <div class="contact_info_item">
                    <p><a href="#">Fill a Quick Form</a></p>

                </div>
            </div>
        </div>
    </section>
</template>

<style>
a {
    text-decoration: none;
    color: #787878;
    font-weight: 400;
}

#contact_section {
    border-top: 4px solid skyblue;
}

.contact_container {
    width: 92%;
    margin: 20px auto;
    gap: 10px;
    display: grid;
    grid-template-columns: repeat(4, 1fr);
}

.heading {
    width: 90%;
    margin: 30px auto;
    text-align: center;
}

.heading .title {
    font-size: 24px;
    margin-bottom: 20px;
    background: #121FCF;
    background: linear-gradient(to right, #121FCF 44%, #CF1512 100%);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;

}

.contact_container {
    width: 90%;
    margin: 20px auto;
    gap: 10px;
}

.contact_card {
    text-align: center;
    /* border: 2px solid black; */
}

.contact_info {
    display: flex;
    justify-content: center;
    align-items: center;
    margin: 0 auto;
    width: 100px;
    height: 100px;
    color: #C52D2F;
    border-radius: 50%;
    border: 3px solid rgba(201, 198, 198, 0.521);
}

.contact_info .icon {
    font-size: 25px;
    text-transform: uppercase;
    font-weight: 700;
    transition: .3s ease-in-out;
}

.contact_info:hover {
    background-color: #C52D2F;
    border: 3px solid #C52D2F;
    color: white;
}

.contact_card h2 {
    font-size: 22px;
    line-height: 22px;
    color: #787878;
    font-weight: 300;
}

.contact_card p {
    font-size: 20px;
    line-height: 20px;
    color: #787878;
    font-weight: 300;
    margin-bottom: 8px;
}
</style>