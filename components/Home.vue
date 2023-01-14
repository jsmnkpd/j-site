<template>
    <div>
        <div id="nav">
            <h1 id="header">潔明</h1>
            <ul>
                <li><a href="#">home</a></li>
                <li><NuxtLink to="about">about</NuxtLink></li>
                <li><NuxtLink to="read">read</NuxtLink></li>
                <li><NuxtLink to="watch">watch</NuxtLink></li>
                <li><NuxtLink to="press">press</NuxtLink></li>
                <li><NuxtLink to="contact">contact</NuxtLink></li>
            </ul>
        </div>
        <h1 id="h3ader">jasmine kapadia</h1>
        <img src=" /picofme.png" alt="jasmine standing in a courtyard" width="700px" class="center"/>
        
    </div>
</template>

<style>
p{
    font-family:Garamond; font-size: large;}

body{
    background-color: #FFFFF0; }

.center {
  display: block;
  margin-left: auto;
  margin-right: auto;
  width: 50%;
}

#header{
    
    font-size: xx-large;
    color: #3d2042;
    opacity: 85%;
    margin-bottom: 50px;
}

#nav ul{
    display: flex;
    flex-direction: column;
    justify-content: space-around;
}

#nav ul li{
    margin-bottom: 85px;
    font-size:x-large;
}

#nav{
    position: fixed;
    top: 30px;
    left: 150px;
}

#h3ader{
    position: fixed;
    bottom: 30px;
    right: 60px;
    font-size: xx-large;
    color: #3d2042;
    opacity: 85%;
}

ul {
  list-style-type: none;
  margin: 0;
  padding: 0;
}

</style>