<template>
    <div class="menu">
        <touchable-opacity @onClick="onClick">
             <span class="glyphsSpriteSafari__outline__24__grey_9 u-__7" aria-label="Buscar personas"></span>
        </touchable-opacity>
        <touchable-opacity @onClick="onClick">
            <span class="glyphsSpriteHeart__outline__24__grey_9 u-__7" aria-label="Feed de actividades"></span>
        </touchable-opacity>
        <touchable-opacity @onClick="onClick">
           <span class="glyphsSpriteUser__outline__24__grey_9 u-__7" aria-label="Perfil"></span>
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
    
    justify-content: space-around;
}
.glyphsSpriteSafari__outline__24__grey_9, .glyphsSpriteSave__filled__24__grey_9 {
    background-repeat: no-repeat;
    background-position: -130px -286px;
    height: 24px;
    width: 24px;
}
.glyphsSpriteHeart__filled__24__red_5, .glyphsSpriteHeart__outline__24__grey_9 {
    background-repeat: no-repeat;
    background-position: -26px -260px;
    height: 24px;
    width: 24px;
}
.glyphsSpriteHeart__outline__24__grey_9 {
    background-position: -52px -260px;
}
.glyphsSpriteUser__filled__24__grey_9, .glyphsSpriteUser__outline__24__grey_9 {
    background-repeat: no-repeat;
    background-position: -271px -208px;
    height: 24px;
    width: 24px;
}
.glyphsSpriteUser__outline__24__grey_9 {
    background-position: -271px -182px;
}
.u-__7 {
    display: block;
}
</style>


