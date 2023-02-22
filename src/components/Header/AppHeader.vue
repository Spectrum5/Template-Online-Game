<script>
import SocialHeader from "../../components/Header/SocialHeader.vue"
import NavHeader from "../../components/Header/NavHeader.vue"
import JumbotronHeader from "../../components/Header/JumbotronHeader.vue"
export default {
    data() {
        return {
            SocialHeader,
            NavHeader,
            JumbotronHeader,
        }
    }
}
</script>

<template>
    <!-- creazione template html -->
    <SocialHeader />
    <NavHeader />
    <JumbotronHeader />

</template>