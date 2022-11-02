<template>
 <section>
    <div id="section">
    <nav>
        <div class="first">
        <img src="../assets/logo.svg" alt="">
        <div class="router-links">
            <a href="" class="router-link">Product</a>
            <a href="" class="router-link">Company</a>
            <a href="" class="router-link">Connect</a>
        </div>
        </div>
        <div class="second">
            <button>Login</button>
            <button>Sign Up</button>
        </div>
    </nav>


    <div class="container">
        <h1>A modern publishing platform</h1>
        <p>Grow your audience and build your online brand</p>
        <div class="hero-btn">
   <button id="primary">Start for Free</button>
   <button id="secondary">Learn More</button>
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
section{
    height: 90vh;
    width: 100%;
    background: var(--white);
}
    #section{
        background: url(../assets/bg-pattern-intro-desktop.svg), linear-gradient(180deg, hsl(353, 100%, 62%), hsl(13, 100%, 72%));
        background-size:240%;
        width: 100%;
        height: 80vh;
        background-position: 28%;
        border-bottom-left-radius: 200px;
        display: flex;
        align-items: center;
        justify-content: flex-start;
        flex-direction: column;
    }
nav{
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    align-items: center;
    width: 80%;
    background: transparent;
    padding-top: 3rem;
}
.first{
    display: flex;
    align-items: center;
    column-gap: 3rem;
}
.router-links{
    display: flex;
    column-gap: 1.5rem;
    font-family: 'Ubuntu', sans-serif;
    font-weight: 500;
    font-size: 1.1rem;
}
.router-link{
    color: inherit;
    text-decoration: none;
    transition: .1s ease-in-out all;
    color: var(--ftext);
}
.router-link:hover{
    text-decoration: underline 2px;
    color: var(--text);

}
.second{
    display: flex;
    column-gap: 2rem;
}
.second button{
    border: none;
    outline: none;
    background: none;
    font-family: 'Ubuntu', sans-serif;
    color: var(--ftext);
    font-weight: 500;
    font-size: 1.1rem;
}
.second button:nth-child(2){
    color: transparent;
    background: var(--text);
    color: #ff6462;
    padding-block: .6rem;
    padding-inline: 1.8rem;
    border-radius: 26px;

}
.container{
display: flex;
flex-direction: column;
align-items: center;
justify-content: center;
width: 100%;
height: 80%;
}
.container h1{
font-size: 4rem;
font-family: 'Overpass', sans-serif;
color: var(--text);
}
.container p{
color: var(--ftext);
font-family: 'Overpass', sans-serif;
font-size: 1.1rem;
}
.hero-btn{
    display: flex;
    column-gap: 1.5rem;
    margin-top: 2.5rem;
} 
.hero-btn button{
    background: none;
    outline: none;
    border: none;
     font-family: 'Ubuntu', sans-serif;
    color: var(--text);
    font-weight: 500;
    font-size: 1.1rem;
}
.hero-btn button:nth-child(1){
    background: var(--text);
    color: #ff6462;
    padding-block: .6rem;
    padding-inline: 1.2rem;
    border-radius: 26px;
}
.hero-btn button:nth-child(2){
    padding-block: .6rem;
    padding-inline: 1.6rem;
    border-radius: 26px;
    border: 1px solid var(--text);
}
</style>