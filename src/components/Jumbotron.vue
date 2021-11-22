<template>
    <section class="jumbotron">
        <div class="text">
            <h2>Vue Cli</h2>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Dicta sapiente quis exercitationem non optio aut tempora minima officia placeat. Officiis ipsam at sequi ut? Sequi quibusdam in necessitatibus adipisci repudiandae! Lorem ipsum, dolor sit amet consectetur adipisicing elit. Perspiciatis commodi quibusdam autem adipisci! Magni, culpa quidem. Fugiat labore pariatur maxime animi sint nulla! Laboriosam tempore iste magnam, reprehenderit minima rerum?</p>
        </div>
    </section>
</template>

<script>
export default {
    name: 'Jumbotron',
}
</script>

<style>
    .jumbotron {
        height: 70vh;
        background-image: url('../assets/jumbotron background.jpg');
        background-size: cover;
        background-position-y: bottom;
        padding: 50px;
        display: flex;
        justify-content: center;
        align-items: center;
    }

    .text {
        width: 50%;
        padding: 50px 70px;
        background-color: rgba(255, 255, 255, 0.7);
    }

    h2 {
        margin: 20px 0;
    }
</style>