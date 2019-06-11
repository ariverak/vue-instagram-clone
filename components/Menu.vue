<template>
    <div class="menu">
        <touchable-opacity @onClick="onClick">
            <Icon name="regular/compass" scale="1.5" />
        </touchable-opacity>
        <touchable-opacity @onClick="onClick">
            <Icon name="regular/heart" scale="1.5" />
        </touchable-opacity>
        <touchable-opacity @onClick="onClick">
            <Icon name="regular/user" scale="1.5" />
        </touchable-opacity>
    </div>
</template>
<script>
export default {
    methods : {
        onClick(){
            console.log("jiji")
        }
    }
}
</script>
<style scoped>
.menu {
    display: inline-flex;
    width : 200px;
    justify-content: space-around;
}
</style>


