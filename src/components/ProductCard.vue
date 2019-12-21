<template>
    <div class="card">
        <span class="card-title">Lorem</span>
        <p class="card-content">But I must explain to you how all this mistaken idea of denouncing 
            pleasure and praising pain was born and I will give you a complete account of the system, 
            and expound the actual teachings of the great explorer of the truth, the master-builder 
            of human happiness. No one rejects, dislikes, or avoids pleasure itself, because it is pleasure, 
            but because those who do not know how to pursue pleasure rationally encounter consequences that 
            are extremely painful. Nor again is there anyone who loves or pursues or desires to obtain pain of 
            itself, because it is pain, but because occasionally circumstances occur in which toil and pain can 
            procure him some great pleasure. To take a trivial example, which of us ever undertakes laborious 
            physical exercise, except to obtain some advantage from it? But who has any right to find fault with 
            a man who chooses to enjoy a pleasure that has no annoying consequences, or one who avoids a pain 
            that produces no resultant pleasure?
        </p>
    </div>
</template>
<script>
    export default {
        name: 'ProductCard'
    }
</script>
<style scoped>
    .card-title {
        font-size: 2rem;
        width: 100%;
        text-align: center;
    }
    .card {
        width: 100%;
        height: 100%;
        padding: 3rem 2rem;
        -webkit-box-shadow: 0px 21px 38px -12px rgba(0,0,0,0.75);
        -moz-box-shadow: 0px 21px 38px -12px rgba(0,0,0,0.75);
        box-shadow: 0px 21px 38px -12px rgba(0,0,0,0.75);
    }
    .card-content {
        text-align: center;
        font-size: .8rem;
        opacity: .6;
    }
</style>