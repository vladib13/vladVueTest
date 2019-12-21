<template>
    <div class="section">
        <span class="title">Productos</span>
        <b-row>
            <b-col>
                <ProductCard/>
            </b-col>
            <b-col>
                <ProductCard/>
            </b-col>
            <b-col>
                <ProductCard/>
            </b-col>
        </b-row>
    </div>
</template>
<script>
import ProductCard from './ProductCard.vue'
    export default {
        name: 'BodySection',
        components: {
            ProductCard
        }
    }
</script>
<style scoped>
    .title {
        font-size: 3.5rem;
        width: 100%;
        display: flex;
        justify-content: center;
    }
    @media (max-width: 612px) {
        .col {
            margin-top: 1rem;
        }
    }
    .section {
        padding: 1rem 2rem;
        width: 100%;
    }
</style>