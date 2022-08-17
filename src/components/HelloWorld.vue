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
                    <a href="https://github.com/abbi36">
                    <img src="../assets/github.png" alt="">
                    <h2>Github</h2>
                    </a>
                </div>
                <div class="link">
                    <a href="https://www.linkedin.com/in/abbigail-engel-1a81171a2/">
                    <img src="../assets/linkedin.png" alt="">
                    <h2>LinkedIn</h2>
                    </a>
                </div>
                <div class="link">
                    <a href="../files/Abbi.pdf">
                    <img src="../assets/resume.png" alt="">
                    <h2>Resume</h2>
                    </a>
                </div>
                <div class="link">
                    <a href="mailto: abbi.engel33@gmail.com">
                    <img src="../assets/email.png" alt="">
                    <h2>Email</h2>
                    </a>
                </div>
        </div>
    </div>
    <div class="container-two">
        <div class="about-me">
            <h1>Hello World</h1>
            <p>Welcome to my Portfolio!</p>
        </div>
        <div class="skills">
            <h1>Tech Skills</h1>
            <div class="logos">
            <img src="../assets/javascript.png" alt="">
            <img src="../assets/html.png" alt="">
            <img src="../assets/css.png" alt="">
            <img src="../assets/vue.png" alt="">
            <img src="../assets/react.png" alt="">
            </div>
        </div>
    </div>
</div>
</template>

<script scoped>
export default {
  name: 'HelloWorld',
}
</script>

<style scoped>

.profile {
    font-size: medium;
  }

    .img {
        height: 25%;
    }

    .link img{
        height: 3rem;
    }

.container {
    display: flex;
    flex-direction: row;
    background-color: #b5c99a;
    border-radius: 25px;
    width: 70%;
    align-items: center;
    margin-left: auto;
    margin-right: auto;
}

.container-one {
    background-color: #70e000;
    padding: 3%;
    width: 30%;
    border-radius: 25px;
    align-items: center;

}

.container-two {
    display: flex;
    flex-direction: column;
    border-radius: 25px;
    gap: 5em;
    background-color: #b5c99a;
    margin-top: -20%;
    align-items: center;
    margin-top: 5%;
    width: 70%;
}

.link a{
    text-decoration: none;
    color: black;
    font-size: 12px;
}

.about-me {
    align-items: center;
}

.logos img{
    height: 5rem;
}


</style>
