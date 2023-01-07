
<div class="header__info contenedor">
    <h3 class="header__name">Brandon Vizcarra Tirado</h3>
    <h1 class="header__position">Project Lead <span>&</span> Product Enthusiast</h1>
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
            align-items: flex-end;
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
        }
    }
    .header__position span{
        color: white;
    }
</style>