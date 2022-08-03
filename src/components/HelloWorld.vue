<template>
<div class="container">
    <div class="container-one">
        <div class="profile">
            <img src="" alt="">
            <h3>Abbi Engel</h3>
            <p>Software Developer</p>
        </div>
        <div class="social-links">
                <div class="link">
                    <a href="">
                    <img src="" alt="">
                    <h2>Github</h2></a>
                </div>
                <div class="link">
                    <a href="">
                    <img src="" alt="">
                    <h2>LinkedIn</h2>
                    </a>
                </div>
                <div class="link">
                    <a href="">
                    <img src="" alt="">
                    <h2>Resume</h2></a>
                </div>
        </div>
    </div>
    <div class="container-two">
        <div class="about-me">
            <h1>Something</h1>
            <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Accusantium sunt quae ut doloribus nostrum cupiditate necessitatibus temporibus voluptates, quo corporis, beatae qui deleniti. Veritatis, quae laudantium? Fuga numquam aut asperiores!</p>
        </div>
        <div class="skills">
            <h1>Tech Skills</h1>
            <img src="" alt="">
            <img src="" alt="">
            <img src="" alt="">
        </div>
    </div>
</div>
</template>

<script>
export default {
  name: 'HelloWorld',
}
</script>

<style scoped>
    link {
        height: 25%;
    }

.container {
    display: flex;
    flex-direction: row;
    background-color: #cecece;
}

.container-one {
    background-color: #ffb0b0;
    padding: 2.5%;
    width: 30%;
}

.container-two {
    background-color: #cdc0fc;
    width: 60%;
}

.link a{
    text-decoration: none;
    color: black;
    font-size: 10px;
}

</style>
