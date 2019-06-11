    <template>
    <div class="root">
            <div class="logoSection">
                <Icon name="brands/instagram" scale="1.5"/>
                <div class="divider">|</div>
                <img class="logo" alt="instagram" src="~/static/insta.png" />
            </div>
            <SearchBar />
            <Menu />
    </div>
</template>
<script scoped>
import SearchBar from './SearchBar'
import Menu from './Menu'
export default {
    components : {
        SearchBar,
        Menu
    }
}
</script>

<style scoped>
.root {
    height : 76px;
    flex : 1;
    width: 100%;
    align-items: center;
    display: inline-flex;
    justify-content: space-around;
    border-bottom: 1px solid lightgray
}
.logoSection {
    display : flex;
    align-items: center;
}
.divider {
    display: flex;
    align-items: flex-start;
    font-size : 30px;
    height : 48px;
    margin: 0 15px;
}
.logo {
    margin-top : 5px;
    width : 103px;
    height : 45px;
}
</style>


