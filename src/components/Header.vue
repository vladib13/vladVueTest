<template>
    <div>
        <b-navbar toggleable="lg" type="light" variant="faded">
            <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>
            <b-collapse id="nav-collapse" is-nav>
                <b-navbar-nav>
                    <b-nav-item href="#">INICIO</b-nav-item>
                    <b-nav-item href="#">NOSOTROS</b-nav-item>
                    <b-nav-item-dropdown text="INDUSTRIA" right>
                        <b-dropdown-item href="#">VISION</b-dropdown-item>
                        <b-dropdown-item href="#">MISION</b-dropdown-item>
                        <b-dropdown-item href="#">EMPLEOS</b-dropdown-item>
                    </b-nav-item-dropdown>
                    <b-nav-item-dropdown text="PRODUCTOS" right>
                        <b-dropdown-item href="#">LAPTOPS</b-dropdown-item>
                        <b-dropdown-item href="#">DESKTOPS</b-dropdown-item>
                    </b-nav-item-dropdown>
                    <b-nav-item-dropdown text="MEDIA" right>
                        <b-dropdown-item href="#">FOTOS</b-dropdown-item>
                        <b-dropdown-item href="#">VIDEOS</b-dropdown-item>
                        <b-dropdown-item href="#">MUSICA</b-dropdown-item>
                    </b-nav-item-dropdown>
                    <b-nav-item href="#">CONTACTENOS</b-nav-item>
                </b-navbar-nav>
                <b-navbar-nav class="ml-auto right">
                    <b-link href="#foo">Ingresar</b-link>
                    <span class="mx-2">|</span>
                    <b-link href="#foo">Buscar Oficina</b-link>
                </b-navbar-nav>
            </b-collapse>
        </b-navbar>
    </div>
</template>
<script>
    export default {
        name: 'Header'
    }
</script>
<style scoped>
    ul.right a{
        color: black;
        font-weight: bold;
    }
</style>