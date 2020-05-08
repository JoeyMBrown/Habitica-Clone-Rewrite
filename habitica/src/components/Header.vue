<template>
  <div>
    <ul>
        <li><a href="#"><b>Filter</b></a></li>    <!-- Don't really see the need for a filter option may be removed -->
        <li id="test"><b>Nothing for Now</b></li> <!-- Will eventually display the current list being viewed -->
        <li><a href="#"><b>Plus Icon</b></a></li> <!-- Will eventually link to a modal -->
    </ul>
  </div>
</template>

<script>
import { Component, Prop, Vue } from 'vue-property-decorator';

@Component
export default class Header extends Vue {
}

</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
ul {
    display: flex;
    flex-direction: row;
    justify-content: space-between;

    list-style-type: none;
    border: 1px solid black;
    background-color: #DB2763;

    width: 100%;
    padding: 0px;
    margin: 0px;
}

li {
    padding: 6px;
    margin: 10px;
    color: white;
}

li a {
    text-decoration: none;
    color: white;
}
</style>