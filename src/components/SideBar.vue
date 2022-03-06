<template>
    <!-- Sidebar Start -->
        <ul class="navbar-nav bg-gradient-primary sidebar sidebar-dark accordion" id="accordionSidebar">
            <!-- SidebarBrand START-->
            <SideBarBrand></SideBarBrand> 
            <!-- SidebarBrand END -->


            <!-- NavItemHeading START-->
            <NavItemHeading></NavItemHeading>
            <!-- NavItemHeading END-->


            <!-- NavItemCollapse START-->
            <NavItemCollapse></NavItemCollapse>
            <!-- NavItemCollapse END-->


            <!-- SideBarCardsTables START -->
            <SideBarCardsTables></SideBarCardsTables>
            <!-- SideBarCardsTables END -->

            <!-- SideBarFooter END -->
            <SideBarFooter></SideBarFooter>
            <!-- SideBarFooter END -->
        </ul>
    <!-- Sidebar End -->

    
</template>

<script>

import SideBarBrand from "./fullSideBar/SideBarBrand.vue";
import NavItemHeading from "./fullSideBar/NavItemHeading.vue";
import NavItemCollapse from "./fullSideBar/NavItemCollapse.vue";
import SideBarCardsTables from "./fullSideBar/SideBarCardsTables.vue";
import SideBarFooter from "./fullSideBar/SideBarFooter.vue";

export  default{
    name:"SideBar",
    components:{
    SideBarBrand,
    NavItemHeading,
    NavItemCollapse,
    SideBarCardsTables,
    SideBarFooter
}
}
</script>