<template>
<!-- Topbar  START-->
    <nav class="navbar navbar-expand navbar-light bg-white topbar mb-4 static-top shadow">

        <!-- ToogleSearch START -->
        <ToogleSearch></ToogleSearch>
        <!-- ToogleSearch END -->


        <!-- TopNavbar START -->
        <TopNavbar></TopNavbar>
        <!-- TopNavbar END -->
    </nav>
<!-- Topbar  END-->
</template>

<script>
import ToogleSearch from "./ToogleSearch.vue";
import TopNavbar from "./TopNavbar.vue";
    export default{
    name: "MainContent",
    components: { ToogleSearch, TopNavbar }
}
</script>