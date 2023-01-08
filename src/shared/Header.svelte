<script>

</script>
<div class="container">
    <header class="header contenedor">
        <nav class="header__nav">
            <h2 class="header__logo">Branduski</h2>
            <ul class="nav__ul">
                <li class="nav__li">
                    <a href="#" class="nav__link">About Me</a>
                    <a href="#" class="nav__link">Portfolio</a>
                    <a href="#" class="nav__link">Skills</a>
                    <a href="#" class="nav__link">Contact</a>
                </li>
            </ul>
        </nav>
        <div class="header__info">
                <h3 class="header__name">Brandon Vizcarra Tirado</h3>
                <h1 class="header__position">Project Lead <span>&</span> Product Enthusiast</h1>
            <div class="header__links">
                <a href="/src/Cv_Brandon.pdf" target="_blank" class="header__cv">
                    Download my CV
                </a>
                <a href="https://www.linkedin.com/in/brandon-ruben-vizcarra-tirado-aa7989162/" target="_blank" class="header__cv header__linkedin">
                    LinkedIn Profile
                </a>
                
            </div>
        </div>
    </header>
</div>

<style scoped>
    :root{
    --primary-color:#332FD0;
    --secondary-color:#FB2576;
    --third-color:#fff;
    }
    .container{
        background-image: url('../assets/pexels-tuesday-temptation-3780104.webp');
        background-size: cover;
        width: 100%;
        height: 100vh;
    }
    .header__nav{
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
        
    }
    @media screen and (min-width:992px){
       .header__nav{
        flex-direction: row;
        justify-content: space-between;
        align-items: center;
       }
    }
    .header__logo{
        color:var(--third-color);
        font-style:italic;
        padding: 1.5rem 0;
    }
    .nav__ul{
        padding: 0;
    }
    .nav__li{
        display: flex;
        flex-direction: column;
        list-style: none;
    }
    @media screen and (min-width:992px){
        .nav__li{
            flex-direction: row;
            gap: 1rem;
        }
    }
    .nav__link{
        color: white;
        text-decoration: none;
        font-size: 1.8rem;
        transition: color 0.3s ease-in-out;
        margin-bottom: 1.4rem;
        text-align: center;
    }
    .nav__link:hover{
        color: #FB2576;
    }
    .header__info{
        margin-top: 5rem;
        display: flex;
        flex-direction: column;
        align-items:center;
        line-height: 1.5;
        min-height: 50rem;
    }
    @media screen and (min-width:992px){
        .header__info{
            align-items: flex-start;
            height: 70rem;
            justify-content: center;
        }
    }
    .header__name{
        color: white;
        font-size: 3rem;
        text-align: center;
        margin: 0;
    }
    @media screen and (min-width:1024px){
        .header__name{
            font-size: 7rem;
            text-align: left;
        }
    }
    .header__position{
        color: var(--secondary-color);
        text-align: center;
        font-size:5.5rem;
    }
    @media screen and (min-width:1024px){
        .header__position{
            font-size: 11rem;
            text-align: left;
        }
    }
    .header__position span{
        color: white;
    }
    .header__cv{
        padding: 1.4rem 2rem;
        color: var(--third-color);
        text-decoration: none;
        font-size: 1.8rem;
        background-color:var(--secondary-color);
        border-radius: 5px;
        margin-top: 1.5rem;
        transition-property: color background-color;
        transition-duration: 0.3s;
        transition-timing-function: ease-in-out;
        box-shadow: 5px 6px 59px -1px rgba(138,138,138,0.77);
    }
    .header__cv:hover{
        color: var(--third-color);
        background-color:#d50052;
        
    }
    .header__links{
        display: flex;
        flex-direction: column;
    }
    @media screen and (min-width:768px){
        .header__links{
            flex-direction: row;
        }
    }
    
    @media screen and (min-width:768px){
        .header__linkedin{
           display: block;
           margin-left: 2rem;
        }
    }
    .header__linkedin{
        background-color: transparent;
        border: 1px solid var(--secondary-color);
    }
    .header__linkedin:hover{
        background-color: rgba(26, 26, 26, 0.848);
        color: var(--secondary-color);
    }
</style>