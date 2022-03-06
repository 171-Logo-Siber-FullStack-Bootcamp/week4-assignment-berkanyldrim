<template>
 <!-- Content Wrapper START -->
    <div id="content-wrapper" class="d-flex flex-column">
        <MainContent></MainContent>
    </div>
 <!-- Content Wrapper END -->
</template>

<script>
import MainContent from "./fullWrapper/MainContent.vue";
export default{
    name: "WrapperTop",
    components: { MainContent }
}
</script>