<template>
    <section>
        <Navbar/>
        <div>
            <slot/>
        </div>
        <Footer/>
    </section>
</template>

<style>
    body{
        padding: 0;
        margin: 0;
        box-sizing: border-box;
    }
    p{
        margin: 0;
    }
</style>