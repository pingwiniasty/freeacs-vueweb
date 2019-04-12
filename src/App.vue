<template>
  <div id="app">
    <top-nav></top-nav>
    <b-container fluid>
      <b-row>
          <left-nav></left-nav>
        <b-col md="10" tag="main" class="ml-auto">
          <router-view></router-view>
        </b-col>
      </b-row>
    </b-container>
  </div>
</template>

<script>

import TopNav from "./components/Core/TopNav";
import LeftNav from "./components/Core/LeftNav";
export default {
  name: 'app',
  components: {LeftNav, TopNav},
}
</script>

<style>

</style>
