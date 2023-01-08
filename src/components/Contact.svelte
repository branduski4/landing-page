<script>

</script>

<footer id="footer">
    <h3 class="footer__title" >Contact me at</h3>
    <div class="contact__container">
        <a target="_blank" href="https://github.com/branduski4"><img class="contact__img" src="./github.svg" alt=""></a>
        <a target="_blank" href="https://www.linkedin.com/in/brandon-ruben-vizcarra-tirado-aa7989162/"><img class="contact__img" src="./linkedin.svg" alt=""></a>
        <a target="_blank" href="https://www.facebook.com/iDivinitty"><img class="contact__img" src="./facebook.svg" alt=""></a>
    </div>
</footer>
<style scoped>
     :root{
    --primary-color:#332FD0;
    --secondary-color:#FB2576;
    --third-color:#fff;
    }
    #footer{
        background-color:var(--secondary-color);
        margin-top: 10rem;
    }
    .footer__title{
        padding: 2rem 0;
        text-align: center;
        color: var(--third-color);
    }
    .contact__container{
        justify-items: center;
        width: 100%;
        display: grid;
        grid-template-columns: repeat(3,1fr);
        padding: 5rem 0;
    }
    a{
        width: 40px;
    }
    
</style>