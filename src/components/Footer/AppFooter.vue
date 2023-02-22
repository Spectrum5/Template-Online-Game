<script>
import TestimonialsFooter from "../../components/Footer/TestimonialsFooter.vue"
import ContactsFooter from "../../components/Footer/ContactsFooter.vue"
import SocialNewsletterFooter from "../../components/Footer/SocialNewsletterFooter.vue"
import FirmFooter from "../../components/Footer/FirmFooter.vue"

export default {
    data() {
        return {
            TestimonialsFooter,
            ContactsFooter,
            SocialNewsletterFooter,
            FirmFooter
        }
    }
}
</script>

<template>
    <!-- creazione template html -->
    <TestimonialsFooter />
    <ContactsFooter />
    <SocialNewsletterFooter />
    <FirmFooter />
</template>

<style scoped lang="scss">
/* aggiunta stile css */
</style>