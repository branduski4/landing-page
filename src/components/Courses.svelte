<script>
const courses = [
    {
        name:"Javascript",
        image:"https://static.platzi.com/media/achievements/badge-basicojs-e2ead888-428e-4f55-962c-8894aeaeacda.png"
    },
    {
        name:"JS práctico",
        image:"https://static.platzi.com/media/achievements/practico-javascript_badge-fb533fa5-73c8-4f75-9d81-0294d9013ab5.png"
    },
    {
        name:"JS Async",
        image:"https://static.platzi.com/media/achievements/badge-asincro-js-9f17b092-47d0-4c8a-a59d-67714aa18db3.png"
    },
    {
        name:"Closures",
        image:"https://static.platzi.com/media/achievements/badge-piezas-clousures-scope-javascript-af54a63d-00d6-42e3-96c3-731028480418.png"
    },
    {
        name:"Github",
        image:"https://static.platzi.com/media/achievements/badge-github-0b729570-934d-47d8-ba6b-610d7f15e0ec.png"
    },
    {
        name:"Engineering",
        image:"https://static.platzi.com/media/achievements/badge-eng-management-8aa3f5cb-e16d-4ef6-8ef0-ff244a6ab746.png"
    },
    {
        name:"PM",
        image:"https://static.platzi.com/media/achievements/piezas-fundamentos-project-management_badge-68790674-1bff-4798-afab-5f9f83645eeb.png"
    },
    {
        name:"PM Práctico",
        image:"https://static.platzi.com/media/achievements/piezas-practico-project-management_badge-1c63bdbf-cdac-4d64-855b-4ad48752d6c2.png"
    },
    {
        name:"PM Planning",
        image:"https://static.platzi.com/media/achievements/badges-categoria-negocios-emprendimiento-bb3945da-c29f-4624-8548-0589d51346ea.png"
    },
    {
        name:"Learn Online",
        image:"https://static.platzi.com/media/achievements/piezas-estrategias-aprender-en-linea_badge-761628f5-6760-4c6a-a279-d4447022f8e7.png"
    },
    {
        name:"Time",
        image:"https://static.platzi.com/media/achievements/badge-gestion-tiempo-5368aa24-4418-4e10-b6c3-c8775b849bf9.png"
    },
    {
        name:"Notion",
        image:"https://static.platzi.com/media/achievements/badge-notion-nuevo-3d72225d-944c-48f2-88ff-85afe9903ce1.png"
    },
    {
        name:"English",
        image:"https://static.platzi.com/media/achievements/piezas-taller-ingles-principiantes_badge-1-56da5912-2828-48f3-9879-0ab93c1c3d3d.png"
    },
    {
        name:"Front end",
        image:"https://static.platzi.com/media/achievements/badge-curso-practico-frontend-developer-d28c2eb0-cd3e-4951-bb96-5f1bcab2add5.png"
    },
    {
        name:"AWS",
        image:"https://static.platzi.com/media/achievements/badge-aws-fundamentos-2-copy-1b5df21d-5bb7-4412-add1-fff42e6fc3a1.png"
    },

]
</script>
<section id="skills">
    <h1 class="skill__title">Skills & Certifications</h1>
        <div class="courses__container contenedor">
            {#each courses as course }
            <div class="course__card">
                <img class="course__img" src="{course.image}" alt="">
                <p class="course__title">{course.name}</p>
            </div>
            {/each}
        </div>

</section>

<style>
     :root{
    --primary-color:#332FD0;
    --secondary-color:#FB2576;
    --third-color:#fff;
    }
.skill__title{
    color: var(--secondary-color);
    text-align: center;
    padding-top: 4rem;
    font-size: 5rem;
}
@media screen and (min-width:768px){
    .skill__title{
        font-size: 8rem;
    }
}
.courses__container{
    display: grid;
    justify-items: center;
    grid-template-columns: repeat(3,1fr);
    gap: 2rem;
    grid-auto-rows: auto;
    margin-top: 4rem;
}
@media screen and (min-width:992px){
    .courses__container{
        grid-template-columns: repeat(4,1fr);
        width: 60%;
    }   
}
.course__card{
    display: flex;
    flex-direction: column;
    align-items: center;
}
.course__img{
    width: 6.2rem;
}
@media screen and (min-width:992px){
    .course__img{
        width: 12rem;
    }
}
.course__title{
    font-size: 1.5rem;
    font-weight: bold;
}

</style>