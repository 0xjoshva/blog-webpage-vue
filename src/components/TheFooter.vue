<template>
    <section>
        <footer>
            <div class="footer-links">
            <img src="../assets/logo.svg" alt="">
            <div class="links">
                <h6>Product</h6>
                <p>Overview</p>
                <p>Pricing</p>
                <p>Marketplace</p>
                <p>Features</p>
                <p>Integrations</p>
            </div>
            <div class="links">
                <h6>Company</h6>
                <p>About</p>
                <p>Team</p>
                <p>Blog</p>
                <p>Careers</p>
               
            </div>
            <div class="links">
                <h6>Connect</h6>
                <p>Contact</p>
                <p>Newsletter</p>
                <p>Linkedin</p>
            </div>
            </div>
        </footer>
    </section>
</template>
<script>
export default {
    
}
</script>
<style scoped>
    section{
        width: 100%;
        height: 50vh;
        display: flex;
        justify-content: end;
        align-items: end;
    }
    footer{
        background: var(--footerbg);
        height: 40vh;
        width: 100%;
        border-top-right-radius: 150px;
padding-top: 6rem;
display: flex;
justify-content: center;
    }
    .footer-links{
        width: 80%;
                display: flex;
        justify-content: left;
        align-items: flex-start;
        column-gap: 15rem;
    }
    .links{
        display: flex;
        flex-direction: column;
        row-gap: .5rem;
    }
.links h6{
font-size: 1.3rem;
color: var(--text);
font-family: 'Overpass', sans-serif;
padding-bottom: 1.5rem;
margin-top: .5rem;

}
.links p{
    color: var(--ftext);
font-family: 'Overpass', sans-serif;
font-size: 1.1rem;
}
</style>