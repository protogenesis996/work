<template>
    <section class="Appmain-container">
        <transition name="fade-transform" mode="out-in">
            <router-view />
        </transition>
    </section>
</template>

<script>
export default {
  name: 'Appmain'
}
</script>
<style scoped lang="scss">

</style>
