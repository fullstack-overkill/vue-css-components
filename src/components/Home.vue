<template>
  <div class="home">
    <div class="paper-shadow">
      <div class="paper">
        <div class="group-comp">
          <div class="group-title">Buttons</div>
          <hr class="group-divider" />
          <div class="btn-group row">
            <button class="buttonA">BUTTON</button>
            <button class="buttonA-OUTILINED">BUTTON</button>
            <button class="buttonA-TEXT">BUTTON</button>
          </div>
          <div class="btn-group row">
            <button class="buttonB">BUTTON</button>
            <button class="buttonB-OUTILINED">BUTTON</button>
            <button class="buttonB-TEXT">BUTTON</button>
          </div>
          <div class="btn-group row">
            <button class="buttonC">BUTTON</button>
            <button class="buttonC-OUTILINED">BUTTON</button>
            <button class="buttonC-TEXT">BUTTON</button>
          </div>
          <div class="btn-group row">
            <button class="buttonD">+</button>
            <button class="buttonD-OUTILINED">+</button>
            <button class="buttonD-TEXT">+</button>
          </div>
        </div>
        <div class="group-comp">
          <div class="group-title">Dialog</div>
          <hr class="group-divider" />
          <div class="btn-group">
            <div class="screen-modal">
              <div class="modal-container">
                <div class="modal-shadow">
                  <div class="modal">
                    <div class="modal-header">Dialog header</div>
                    <div class="modal-desc">Dialog body text</div>
                    <div class="modal-actions">
                      <button class="buttonC-TEXT">ACTION 1</button>
                      <button class="buttonC-TEXT">ACTION 2</button>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="group-comp">
          <div class="group-title">Paper</div>
          <hr class="group-divider" />
          <div class="btn-group">
            <div class="paper-comp-shadow">
              <div class="paper-comp">
                <div class="paper-title">
                  Home
                </div>
              </div>
            </div>
            <div class="paper-comp-shadow sub-paper">
              <div class="paper-comp"></div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="stylus">
@import '../assets/stylus/main.styl';
@import './home.styl';

h3 {
  margin: 40px 0 0;
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  display: inline-block;
  margin: 0 10px;
}

a {
  color: #42b983;
}
</style>
