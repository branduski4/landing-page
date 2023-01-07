<script>

</script>

<header class="header contenedor">
    <nav class="header__nav">
        <h2 class="header__logo">Branduski!</h2>
        <ul class="nav__ul">
            <li class="nav__li">
                <a href="#" class="nav__link">About Me</a>
                <a href="#" class="nav__link">Portfolio</a>
                <a href="#" class="nav__link">Skills</a>
                <a href="#" class="nav__link">Contact</a>
            </li>
        </ul>
    </nav>
</header>

<style scoped>
    :root{
    --primary-color:#332FD0;
    --secondary-color:#FB2576;
    --third-color:#fff;
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
</style>