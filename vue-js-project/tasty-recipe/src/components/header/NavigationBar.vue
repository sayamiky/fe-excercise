<template>
    <div class="header__navbar row
    justify-content-between align-items-center"
    style="width:450px"
    >
    <search-menu></search-menu>
    <SignupMenu/>
    </div>
</template>
<script setup>
import SearchMenu from './SearchMenu.vue';
import SignupMenu from './SignupMenu.vue';

</script>