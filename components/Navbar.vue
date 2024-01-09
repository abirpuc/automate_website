<template>
    <nav class="navbar">
        <div>
            <p class="logo">Logo</p>
        </div>
        <div class="menu-item">
            <ul class="menu-list">
                <li><a href="#"><span>Home</span></a></li>
                <li><a href="#"><span>Pages</span></a>
                    <ul class="inner-item">
                        <li><a href="#"><span>About</span></a></li>
                        <li><a href="#"><span>Service</span></a></li>
                        <li><a href="#"><span>Contact</span></a></li>
                        <li><a href="#"><span>Team</span></a></li>
                    </ul>
                </li>
                <li><a href="#"><span>About</span></a></li>
                <li><a href="#"><span>Service</span></a></li>

            </ul>
            <div>
                <p>menu</p>
            </div>
        </div>
    </nav>
</template>

<style>
.logo {
    font-size: 24px;
    font-weight: 800;
}

li {
    list-style-type: none;
}

a {
    text-decoration: none;
}

.navbar {
    height: 100px;
    padding: 0 100px;
    box-shadow: 10px 10px 80px rgba(0, 0, 0, 0.4);
}

.navbar {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.menu-item {
    display: flex;
    justify-content: start;
    align-items: center;
    gap: 40px;
}

.menu-list {
    display: block;
}

.menu-list li {
    display: inline-block;
    margin-left: 30px;
    font-size: 17px;
    font-family: sans-serif;
    letter-spacing: 5px;
}

.menu-list li a span {
    display: block;
    color: black;
}

.menu-list li:hover > span {
    color: red;
}

.inner-item {
    position: absolute;
    top: 150px;
    background: white;
    width: 200px;
    text-align: left;
    visibility: none;
    opacity: 0;
    box-shadow: 10px 10px 30px rgba(0, 0, 0, 0.4);
    transition: .5s linear;
    padding: 0;
    z-index: 99999;
}

.inner-item li {
    display: inline-block;
    padding: 10px;
    z-index: 99999;
}

.menu-item li:hover>ul {
    top: 100px;
    visibility: visible;
    opacity: 1;
}</style>