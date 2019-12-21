<template>
    <section class="section mt-2">
        <h4>"Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut..."</h4>
        <div>
            <small>In a free hour, when our power of choice is untrammelled and when nothing prevents our being able
                 to do what we like best, every pleasure is to be welcomed and every pain avoided.
            </small>
        </div>
    </section>
</template>
<script>
    export default {
        name: 'EndSection'
    }
</script>
<style scoped>
    h4 {
        font-weight: bold;
        text-align: center;
    }
    div{
        display: flex;
        justify-content: center;
        width: 100%;
    }
    small{
        font-weight: bold;
        font-size: .6rem;
        text-align: center;
    }
    .section{
        background-color: rgb(230, 225, 167);
        width: 100%;
        padding: 2rem 1rem;
    }
</style>