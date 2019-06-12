    <template>
  <div class="root">
    <div class="logoSection">
     <span class="glyphsSpriteApp_instagram__outline__24__grey_9 u-__7" aria-label="Instagram"></span>
      <div class="divider">|</div>
      <span class="glyphsSpriteMobile_nav_type_logo u-__7" aria-label="Instagram"></span>
     
    </div>
    <SearchBar/>
    <Menu/>
  </div>
</template>
<script scoped>
import SearchBar from "./SearchBar";
import Menu from "./Menu";
export default {
  components: {
    SearchBar,
    Menu
  }
};
</script>

<style scoped>
.root {
  height: 76px;
  flex: 1;
  width: 100%;
  align-items: center;
  display: inline-flex;
  justify-content: space-around;
  border-bottom: 1px solid lightgray;
}
.logoSection {
  display: flex;
  align-items: center;
}
.divider {
  display: flex;
  align-items: flex-start;
  font-size: 30px;
  height: 48px;
  margin: 0 15px;
}
.logo {
  margin-top: 5px;
  width: 103px;
  height: 45px;
}
.glyphsSpriteApp_instagram__outline__24__grey_9 {
    background-repeat: no-repeat;
    background-position: -52px -234px;
    height: 24px;
    width: 24px;
}
.glyphsSpriteMobile_nav_type_logo {
    background-repeat: no-repeat;
    background-position: -94px -72px;
    height: 29px;
    width: 103px;
}
.u-__7 {
    display: block;
}
</style>


