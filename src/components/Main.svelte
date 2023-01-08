<script>
    const proyects = [
        {
            name:"Anestesys",
            image:"https://biossmann.com/images/svg-pegado-532026x137.svg?crc=378443864",
            description:"Anestesys es un sistema flexible que se adapta a cualquier máquina de anestesia utilizada por la institución médica u hospital público o privado que lo solicite. Su diseño cumple con lo requerido por las normas NOM-004-SSA3-2012 expediente clínico, NOM-024-SSA3-2019 expediente clínico electrónico y NOM-006- SSA3-2011 para la práctica de la Anestesiología."
        },
        {
            name:"Annexio",
            image:"https://biossmann.com/images/logo_annexio.svg?crc=528302455",
            description:"Annexio es un sistema de gestión de información del área quirúrgica, que a través de sus diferentes módulos y la interconexión operativa con otras plataformas propias de Biossmann [Anestesys – Interfaz - Folio tracker] permite la retroalimentación y distribución de datos de todo lo que refiere a los procedimientos quirúrgicos"
        },
        {
            name:"Interfaz",
            image:"https://www.biossmann.com/images/svg-pegado-1087614x302.svg?crc=4225963642",
            description:"lafdkljasdhjfasldjfhaslkdjfhalskjdh"
        },
        ]
</script>
<section id="portfolio">

    <h1 class="container__title">Projects</h1>
    <div class="card__container ">
        {#each proyects as proyect}
                
                <div class="card__proyect">
                    <img class="card__img"loading="lazy" src="{proyect.image}" alt="">
                    <!-- <h3 class="card__title">{proyect.name}</h3> -->
    
                </div>
        {/each}
    
    </div>
</section>

<style scoped>
 :root{
    --primary-color:#332FD0;
    --secondary-color:#FB2576;
    --third-color:#fff;
    }
.card__container{
    margin-top: 4rem;
    display: grid;
    grid-template-columns: 1fr;
    grid-auto-rows: 15rem;
}

.container__title{
    color:var(--secondary-color);
    text-align: center;
    padding-top: 5rem;
    font-size: 5rem;
}
@media screen and (min-width:768px){
    .container__title{
        font-size: 8rem;
    }   
}

.card__proyect{
    display: flex;
    justify-content: center;
    margin-bottom: 3rem;
}

.card__img{
  object-fit: contain;
  border-radius: 10px;
  box-shadow: -1px 9px 25px -5px rgba(107,107,107,0.75);
  background-color: transparent;
  filter: grayscale(1);
  padding: 1.5rem;
  width: 90%;
  transition: transform 0.3s ease-in-out;
}
@media screen and (min-width:992px){
    .card__img{
        width: 60%;
    }   
}
.card__img:hover{
    transform: scale(1.05);
    filter: grayscale(0);
    cursor: pointer;
}
</style>