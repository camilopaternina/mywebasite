<template>
    <div>
        <NavbarComponentVue nav1="nav-link active" nav2="nav-link" nav3="nav-link"/>
        
        <!-- Container -->
        <div class="container">

        </div>
    </div>
</template>

<script>
import NavbarComponentVue from '@/components/NavbarComponent.vue'
export default {
    components:{
        NavbarComponentVue
    },
    created(){
        document.title = "Camilo Paternina - Inicio";
    }
}
</script>