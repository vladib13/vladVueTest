<template>
    <section class="section">
        <b-row>
            <b-col>
                <h6>Nosotros</h6>
                <div class="link">
                    <a href="#">Inicio</a>
                </div>
                <div class="link">
                    <a href="#">Quiénes Somos</a>
                </div>
            </b-col>
            <b-col>
                <h6>Nuestra Empresa</h6>
                <div class="link">
                    <a href="#">Nosotros</a>
                </div>
                <div class="link">
                    <a href="#">Partners</a>
                </div>
            </b-col>
            <b-col>
                <h6>Support</h6>
                <div class="link">
                    <a href="#">Apoyo Técnico</a>
                </div>
                <div class="link">
                    <a href="#">Aplicación de Turnos</a>
                </div>
            </b-col>
        </b-row>
    </section>
</template>
<script>
    export default {
        name: 'Footer'
    }
</script>
<style scoped>
    h6 {
        font-weight:600;
    }
    .link {
        width: 100%;
        display: flex;
        justify-content: center;
    }
    a, h6 {
        color: white;
        text-align: center;
    }
    a {
        opacity: .8;
    }
    .section {
        padding: 1rem 2rem;
        width: 100%;
        background-color: rgba(42, 42, 42, 0.856);
    }
</style>