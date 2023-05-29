<template>
    <Html>
        <Title>Track</Title>
    </Html>
    <body class="bg-[#fff] hidden lg:block">
        <div class="bgTrack">
            <Nav/>
            <HeroSection/>
        </div>
        <FooterSection/>
    </body>
</template>

<style>
    @import url('https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@300;400;500;600;700&display=swap');
    html{
        height:100%;
    }
    body{
        min-height: 100vh;
        font-family: 'Plus Jakarta Sans', sans-serif;
    }
    body::-webkit-scrollbar{
        width: 4px;
        padding-right:5px;
    }
    body::-webkit-scrollbar-thumb{
        width: 4px;
        background: #dfe79c;
        border-radius: 10px;
        padding-right: 5px;
        border: 2px solid #DBF301;
    }
    .bgTrack{
        background: url('/image/bgTrack.png');
        background-repeat: no-repeat;
        background-position: cover;
        background-size: 100%;
    }
</style>