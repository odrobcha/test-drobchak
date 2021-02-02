<template>
    <div>

        <the-test-navigation></the-test-navigation>
        <router-view></router-view>
         <!--place where selected routed componets should be load -->
    </div>


</template>
<script>
    import TheTestNavigation from "./components/TheTestNavigation";

export default {
  name: 'App',
    components: {
      TheTestNavigation,
    },


    methods: {
    },
    data() {
        return {
        };
    },

};

</script>

<style>
    @import './assets/scss/style.scss';

</style>

