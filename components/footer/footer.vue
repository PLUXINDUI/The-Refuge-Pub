<template>
    <footer class="footer">
        <div class="footer__copyright"> {{copyrightText }}</div>
    </footer>
</template>

<script>
export default {
    computed: {
        copyrightText(){
            const currentYear = new Date().getFullYear();
            return  `2023 - ${currentYear}, The Refuge Pub`
        }
    }
}
</script>

<style lang="scss">
.footer {
    background: linear-gradient(#b8e356, #a5cc52)
}
</style>