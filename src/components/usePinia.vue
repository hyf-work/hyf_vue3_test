<template>
    
</template>
<script lang="ts" setup>
import {ref} from 'vue';
import { useUserStore } from '@/store/user';
const userStore  = useUserStore();
 userStore.updateName('李四')
const msg = ref(1)
</script>
<style lang="scss" scoped>

</style>