<script>
import GameCollectionMain from "../../components/Main/GameCollectionMain.vue"
import ProfessionalTeamMain from "../../components/Main/ProfessionalTeamMain.vue"
import AllMatchesMain from "../../components/Main/AllMatchesMain.vue"
import UpcomingMatchesMain from "../../components/Main/UpcomingMatchesMain.vue"
import TeamPlayersMain from "../../components/Main/TeamPlayersMain.vue"
import PlayTogetherMain from "../../components/Main/PlayTogetherMain.vue"
import StreamingMain from "../../components/Main/StreamingMain.vue"
import ProductsMain from "../../components/Main/ProductsMain.vue"
import PartnerMain from "../../components/Main/PartnerMain.vue"
import BlogPostsMain from "../../components/Main/BlogPostsMain.vue"



export default {
    data() {
        return {
            GameCollectionMain,
            ProfessionalTeamMain,
            AllMatchesMain,
            UpcomingMatchesMain,
            TeamPlayersMain,
            PlayTogetherMain,
            StreamingMain,
            ProductsMain,
            PartnerMain,
            BlogPostsMain,
        }
    }
}
</script>

<template>
    <!-- creazione template html -->
    <GameCollectionMain />
    <ProfessionalTeamMain />
    <AllMatchesMain />
    <UpcomingMatchesMain />
    <TeamPlayersMain />
    <PlayTogetherMain />
    <StreamingMain />
    <ProductsMain />
    <PartnerMain />
    <BlogPostsMain />

</template>

<style scoped lang="scss">
/* aggiunta stile css */
</style>