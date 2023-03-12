<template>
    <div>

        <footer>
        <h2 class="feedback">Связаться со мной</h2>
        <div class="social">
           <img src="" alt=""> 
           <img src="" alt="">
           <img src="" alt="">
           <img src="" alt="">
           <img src="" alt="">
        </div>
    </footer>

    </div>
</template>

<script>
    export default {
        
    }
</script>

<style>


footer {
    background: #000000;
    padding-top: 46px;
    padding-bottom: 62px;
    flex-wrap: wrap;
}

.feedback {
    font-weight: 400;
    font-size: 40px;
    line-height: 49px;
    color: #FFFFFF;
    text-align: center;
}

.social {
    display: flex;
    justify-content: center;
    gap: 200px;
    margin-top: 34px;
    flex-wrap: wrap;
}


.social img {
    transition: transform 500ms;
}

.social img:hover {
    transform: rotate(360deg);
}

.left img {
    width: 100%;
}


</style>