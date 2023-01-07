
<div class="header__info contenedor">
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


<style>
    :root{
    --primary-color:#332FD0;
    --secondary-color:#FB2576;
    --third-color:#fff;
    }
    .header__info{
       
        margin-top: 3rem;
        min-height: 40rem;
        display: flex;
        flex-direction: column;
        align-items: center;
    }
    @media screen and (min-width:992px){
        .header__info{
            align-items: flex-start;
            margin-top: 9rem;
        }
    }
    .header__name{
        color: white;
        font-size: 3rem;
        text-align: center;
        margin: 0;
    }
    @media screen and (min-width:992px){
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
    @media screen and (min-width:992px){
        .header__position{
            font-size: 10rem;
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
    .header__cv:active, .header__linkedin{
        transform: scale(1.1);
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
    .header__linkedin{
        background-color: transparent;
        border: 1px solid var(--secondary-color);
        color: white;
        transition-property: color background-color;
        margin-top: 1.2rem;
    }
    @media screen and (min-width:768px){
        .header__linkedin{
           display: block;
           margin-left: 2rem;
        }
    }
    .header__linkedin:hover{
        background-color: rgba(255, 255, 255, 0.848);
        color: var(--secondary-color);
    }
</style>