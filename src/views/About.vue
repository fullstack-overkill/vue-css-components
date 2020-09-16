<template>
  <div class="home">
    <router-link :to="{ name: 'Home' }">
      <button class="page-change">
        <span class="material-icons">arrow_back_ios</span>
      </button>
    </router-link>
    <div class="paper-shadow">
      <div class="paper">
        <div class="group-comp">
          <div class="group-title">UI</div>
          <hr class="group-divider" />
          <div class="group-comp">
            <div class="container-test">
              <div class="app-phone">
                <div class="page-analytics">
                  <div class="analytics-header">
                    <div class="header-menu">
                      <button class="menu-opp">
                        <span class="material-icons">menu</span>
                      </button>
                      <div class="menu-text">Analytics</div>
                    </div>
                    <div class="menu-opp-secondary">
                      <button class="menu-search">
                        <span class="material-icons">search</span>
                      </button>
                      <button class="menu-more">
                        <span class="material-icons">more_vert</span>
                      </button>
                    </div>
                  </div>
                  <div class="analytics-body">
                    <div class="card-paper">
                      <div class="card-paper-title">Marketing</div>
                      <div class="card-paper-value">23.4 M</div>
                    </div>
                    <div class="card-paper">
                      <div class="card-paper-title">Marketing</div>
                      <div class="card-paper-value">23.4 M</div>
                    </div>
                    <div class="card-paper">
                      <div class="card-paper-title">Marketing</div>
                      <div class="card-paper-value">23.4 M</div>
                    </div>
                    <div class="card-paper">
                      <div class="card-paper-title">Marketing</div>
                      <div class="card-paper-value">23.4 M</div>
                    </div>
                    <div class="card-paper">
                      <div class="card-paper-title">Marketing</div>
                      <div class="card-paper-value">23.4 M</div>
                    </div>
                    <div class="card-paper">
                      <div class="card-paper-title">Marketing</div>
                      <div class="card-paper-value">23.4 M</div>
                    </div>
                    <div class="card-paper">
                      <div class="card-paper-title">Marketing</div>
                      <div class="card-paper-value">23.4 M</div>
                    </div>
                    <div class="card-paper">
                      <div class="card-paper-title">Marketing</div>
                      <div class="card-paper-value">23.4 M</div>
                    </div>
                  </div>
                  <button class="add-btn">
                    <span class="material-icons">add</span>
                  </button>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>


<script>
export default {
  name: "Home",
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="stylus">
@import '../assets/stylus/main.styl';
@import './about.styl';
</style>
