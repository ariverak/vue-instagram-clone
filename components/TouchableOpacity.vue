<template>
    <div v-on:click="handleClick" class="root" :class="{touchable : touchableEffect}">
        <slot />
    </div>
</template>
<script>
export default {
    data : ()=>({
        touchableEffect : false
    }),
    methods : {
        handleClick(){
            this.touchableEffect = true;
            setTimeout(()=>{
                 this.touchableEffect = false;
            },200);
            this.$emit('onClick');
        }
    }
}
</script>
<style scoped>
    .root {
        cursor : pointer;
    }
    .touchable {
        opacity: 0.4;
    }
</style>


