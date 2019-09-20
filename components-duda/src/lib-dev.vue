<script>
import { ComponentsDudaSample } from './entry';
export default {
    name:  'ComponentsDudaLibDev', // vue library dev component
    components: {
        ComponentsDudaSample,
    },
}
</script>

<template>
    <div class="components-duda-lib-dev">
        <components-duda-sample></components-duda-sample>
    </div>
</template>

<style scoped>
    .components-duda-lib-dev {
        display: block;
        width: 400px;
        margin: 25px auto;
    }
</style>
