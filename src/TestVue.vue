<template>   
    <div>
    <ul class="list">
        <li>First</li>
        <li>Second</li>
        <li>Third</li>
        <li>Fourth</li>
    </ul>

    <PictureVue />
    </div>

</template>


<script>
import PictureVue from './PictureVue.vue';

    export default {
        name: 'TestVue',
        components: {
            PictureVue
        }
    }
</script>