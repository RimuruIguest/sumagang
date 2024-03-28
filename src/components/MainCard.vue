<template>
    <div class="wrapper">
        <div class="main-container">
            <div class="container-one">
                <div class="profile">
                    <img src="../assets/profilepic.jpg" alt="">
                    <h3>John Mark Sumagang</h3>
                    <p>SOFTWARE DEVELOPER EYY</p>
                </div>
                <div class="social-link">
                    <div class="link">
                        <a href="https://github.com/RimuruIguest/TheGentlemen" target="blank">
                            <img src="../assets/github.jpg" alt="">
                            <h2>GITHUB</h2>
                        </a>
                    </div>
                    <div class="link">
                        <a href="https://www.facebook.com/jan.sumagang.9" target="blank"> 
                            <img src="../assets/facebook.jpg" alt="">
                            <h2>FACEBOOK</h2>
                        </a>
                    </div>
                    <div class="link">
                        <a href="https://www.instagram.com/windjayjo/" target="blank">
                            <img src="../assets/instagram.jpg" alt="">
                            <h2>INSTAGRAM</h2>
                        </a>
                    </div>
                    <div class="link">
                        <a href="https://twitter.com/NotASlime24" target="blank">
                            <img src="../assets/twitter.jpg" alt="">
                            <h2>TWITTER</h2>
                        </a>
                    </div>
                </div>
            </div>
            <div class="container-two">
                <div class="about me ">
                    <h1>About Me</h1>
                    <p>John Mark Sumagang, an 18-year-old resident of Bangbang, Cordova, aspires to become a millionaire.</p>
                    <div class="Language-Section">
                        <h1>Language Studied</h1>
                        <div class="logos">
                            <img src="../assets/japan.jpg" alt="">
                            <img src="../assets/english.jpg" alt="">
                            <img src="../assets/bisaya.jpg" alt="">
                            <div class="button-container">
                                <div class="project-button">
                                    <a href="">Contact Number : 0909090909</a>
                                </div>
                                <div class="project-button">
                                    <a href="">EMAIL: rimuruiguest24@gmail.com</a>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {

}
</script>


<style scoped>
.wrapper {
    display: flex;
    justify-content: center;
}

img {
    height: 40px;
}

.main-container {
    display: flex;
    flex-direction: center; /* Change flex-direction to column for smaller screens */
    background-color: rgb(199, 227, 218);
    border-radius: 30px;
    width: 90%; /* Adjust width for smaller screens */
    max-width: 500px; /* Add max-width to prevent container from stretching too wide */
    margin: 5px ; /* Center the container */
    background-color: rgb(93, 240, 164);
    box-shadow: 0px 3px 8px rgba(0, 0, 0, 0.5);
    padding: 10px; /* Add padding */
}

.container-one {
    background-color: rgb(206, 239, 178);
    width: 70%; /* Take full width */
    padding: 10px; /* Add padding */
    border-radius: 35px;
    margin-bottom: 20px; /* Add margin-bottom for spacing */
    box-shadow: 0px 3px 8px rgba(0, 0, 0, 0.5);
}

.profile img {
    height: 80px; /* Adjust height for profile image */
    border-radius: 50%; /* Make the profile image circular */
    box-shadow: 0px 3px 8px rgba(0, 0, 0, 0.5);
}

.link a {
    text-decoration: none;
    color: #2c3e50;
    font-size: 14px; /* Increase font size for links */
    margin-bottom: 10px; /* Add margin bottom for spacing */
    display: block; /* Display links as block elements */
}

.link img {
    height: 50px; /* Adjust height for social media icons */
}

.container-two {
    background-color: rgb(206, 239, 178);
    margin: 2%;
    width: 100%; 
    height: 95%;
    padding: 5px; 
    border-radius: 30px;
    box-shadow: 0px 3px 8px rgba(0, 0, 0, 0.5);
}

.about-me {
    text-align: center; /* Center align the text */
    margin-bottom: 20px; /* Add margin bottom for spacing */
}

.logos img {
    height: 50px; /* Adjust height for language logos */
    margin-right: 10px; /* Add margin-right for spacing between logos */
    border-radius: 50%; /* Make the logos circular */
}

.button-container {
    display: flex;
    flex-wrap: wrap;
    justify-content: center; 
}

.project-button {
    background-color: #3fe19b;
    border-radius: 25px;
    padding: 10px 20px; 
    margin: 50px; 
    box-shadow: 0px 3px 8px rgba(0, 0, 0, 0.5);
}

.project-button a {
    text-decoration: none;
    color: #000407;
    font-size: 20x;
}

@media only screen and (min-width: 880px) {
    .main-container {
        width: 80%; 
    }
}
</style>
