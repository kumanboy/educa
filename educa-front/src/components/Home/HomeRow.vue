<template>
    <section id="home">
        <h2>Enhance YOur Future with Technologies</h2>
        <p>Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a
            galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but
            also the leap into electronic typesetting, remaining essentially unchanged.</p>
        <div class="btn">
            <a class="blue" href="#">Learn More </a>
            <a class="yellow" href="#">Visit Courses</a>
        </div>
    </section>
</template>

<script>
export default {
    name: "HomeRow"
}
</script>

<style scoped>
#home{
    background-image: linear-gradient(rgba(9,5,54,0.3), rgba(5,4,46,0.7)), url("@/images/back.jpg");
    width: 100%;
    height: 100vh;
    background-size: cover;
    background-position: center;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    text-align: center;
    padding-top: 40px;
}
#home h2{
    color: #fff;
    font-size: 2.2rem;
    letter-spacing: 1px;
}
#home p{
    width: 50%;
    color: #fff;
    font-size: 0.9rem;
    line-height: 25px;
}

#home .btn{
    margin-top: 30px;
}

#home a{
    text-decoration: none;
    font-size: 0.9rem;
    padding: 13px 35px;
    color: #ffffff;
    font-weight: 600;
    border-radius: 5px;
}

#home a.blue{
    color: #ffffff;
    background-color: rgb(21,21,100);
    transition: 0.3s ease;
}

#home a.blue:hover{
    background-color: #ffffff ;
    color: rgb(21,21,100);
}

#home a.yellow{
    color: #ffffff;
    background-color: #FDC93B;
    transition: 0.3s ease;
}

#home a.yellow:hover{
    color: rgb(21,21,100);
    background-color: #ffffff;
}
</style>