<template>
    <footer>
        <div class="footer_content">
            <div class="footer_card">
                <h1 class="footer_title">company</h1>
                <div class="footer_card_content">
                    <ul>
                        <li><a href="#">About Us</a></li>
                        <li><a href="#">Portfolio</a></li>
                        <li><a href="#">Our Clients</a></li>
                        <li><a href="#">Contact Us</a></li>
                    </ul>
                </div>
            </div>
            <div class="footer_card">
                <h1 class="footer_title">CLOUD CAMPUS MODULES</h1>
                <div class="footer_card_content">
                    <ul>
                        <li><a href="#">Dynamic Website (DW)</a></li>
                        <li><a href="#">Student Information & Collection System</a></li>
                        <li><a href="#">Result Management System</a></li>
                        <li><a href="#">Attendance Notification System</a></li>
                        <li><a href="#">Short Message Service (SMS)</a></li>
                        <li><a href="#">Parents Portal (PP)</a></li>
                        <li><a href="#">Fast Accounts Management System</a></li>
                        <li><a href="#">Human Resource Management</a></li>
                        <li><a href="#">Payroll Management System</a></li>
                        <li><a href="#">Class Routine Management System (CRMS)</a></li>
                    </ul>
                </div>
            </div>
            <div class="footer_card">
                <h1 class="footer_title">Membership</h1>
                <div class="footer_card_content">
                    <ul>
                        <li><a href="#">
                            <img src="../assets/basis.jpg" alt="">
                        </a></li>
                        <li><a href="#">
                            <img src="../assets/bcs.png" alt="">
                        </a></li>
                    </ul>
                </div>
            </div>
        </div>
        <div class="footer_nav">
            <p>&copy;Desh Universal Private Limited. All Rights Reserved.</p>
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">Cloud Campus</a></li>
                <li><a href="#">About Us</a></li>
                <li><a href="#">Contact</a></li>
            </ul>
        </div>
    </footer>
</template>

<script>
export default {

}
</script>

<style scoped>
footer {
    background-color: #e7e4e493;
}

.footer_content {
    width: 90%;
    margin: 60px auto;
    padding: 60px 0;
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 10px;
}

.footer_title {
    font-size: 22px;
    font-weight: 100;
    letter-spacing: 4px;
    text-transform: uppercase;
    line-height: 22px;
}

.footer_card_content {
    margin-top: 20px;
    text-align: left;
}

.footer_card_content ul li {
    line-height: 25px;
}

.footer_card_content ul li:hover>a {
    color: #C52D2F;
    transition: ease-in-out .3s
}

.footer_nav{
    background-color: #007099;
    height: 78px;
    border-top: 5px solid #0292c7;
    padding: 0 100px;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.footer_nav p{
    color: white;
    transition: ease-in-out .3s;
}

.footer_nav ul{
    display: flex;
}

.footer_nav ul li{
    margin-left: 20px;
}
.footer_nav ul li a{
    color: white;
    transition: ease-in-out .3s;
}

.footer_nav p:hover, .footer_nav a:hover{
    color:#C52D2F;
}
</style>