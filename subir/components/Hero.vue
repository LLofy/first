<template>
    <div class="Hero container">
        <div class="text-container">        
            <h1 class="header">Find your Fire Extinguisher</h1>
            <p class="snippet">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Iste iusto illum quidem asperiores, cum nisi aperiam eius ipsa sapiente odit!</p> 
            <button class="button btn">Start Looking</button>
        </div>
        <img src="~assets/svg/fire-extinguisher.svg" alt="" class="img">

    </div>
</template>

<script>
    export default {
        
    }
</script>
<style scoped>
    .Hero {
        height: 550px;
        position: relative;
        top:1px;
        display: flex;
        padding: 20px 0;
        align-items: flex-start;
        justify-content: space-between;
    }

    .text-container {
        margin-top: 80px;
    }

    .header {
        font-weight: 900;
        font-size: 70px;
    }

    .snippet {
        color: grey;
        font-size: 1.25rem;
    }

    .image {
        width: 27.5rem;
        margin-top: 2rem;
    }

    .overlay {
        background: rgba(0, 0, 0, 0);
        position: absolute;
        width: 100%;
        height: 100%;
        top: 0;
    }

    .button {
        padding: 1rem 4rem;
        border-radius: 100rem;
        background-color: rgb(231, 81, 43);
        color: white;
        width: 20rem;
        font-weight: 700;
        transition: 0.5s;
    }

    .button:hover {
        width: 21.5rem;
    }

    @media (max-width: 500px) {
        .Hero {
            height: 40vh;

        }
    }
</style>