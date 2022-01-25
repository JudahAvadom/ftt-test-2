<template>
    <div class="navbar">
        <div class="nav">
            <h1>Welcome</h1>
            <nav>
                <ul>
                    <li>Home</li>
                    <li>Photos</li>
                    <li>Videos</li>
                </ul>
            </nav>
        </div>
        <div class="nav-content">
            <h1>The new experience</h1>
            <h2>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Aliquam praesentium expedita quos illum itaque numquam voluptatum maxime mollitia perferendis iusto.</h2>
        </div>
    </div>
</template>

<style>
    .navbar {
        background-image: url("../img/forest.jpg");
        background-size: cover;
    }
    .navbar .nav{
        padding: 20px;
        display: flex;
        justify-content: space-between;
    }
    .navbar .nav ul {
        display: flex;
    }
    .navbar .nav ul li {
        padding-right: 10px;
    }
    .nav-content {
        padding: 8% 19%;
    }
    .nav-content h2 {
        -webkit-text-stroke: .5px #fff;
        color: #000; 
        font-size: 25px;
    }
</style>

<script>
export default {
    name:"Navbar"
}
</script>