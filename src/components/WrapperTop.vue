<template>
 <!-- Content Wrapper START -->
    <div id="content-wrapper" class="d-flex flex-column">
        <!-- Main Content START -->
        <MainContent></MainContent>
        <!-- Main Content END -->


        <!-- Page Content START -->
        <PageContent></PageContent>
        <!-- Page Content END -->
    </div>
 <!-- Content Wrapper END -->
</template>

<script>
import MainContent from "./fullWrapper/MainContent.vue";
import PageContent from "./PageContent.vue";
export default{
    name: "WrapperTop",
    components: { MainContent, PageContent }
}
</script>