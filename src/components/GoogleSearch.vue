<template>
  <div class="GoogleSearch">
    <div id="searchBar">
      <div class="search">
        <div class="icon"></div>
        <p>Gabrielle Geroudet|</p>
        <button id="voiceSearchBtn" title="Vocal search"></button>
      </div>
      <div class="answer" @click="$emit('scrollto', 'goals')">
        <div class="icon"></div>
        <p><span class="bold">Google goals and missions explained by </span> Gabrielle Geroudet</p>
      </div>
      <div class="answer" @click="$emit('scrollto', 'hire')">
        <div class="icon"></div>
        <p><span class="bold">why should Google hire</span> Gabrielle Geroudet</p>
      </div>
      <div class="answer" @click="$emit('scrollto', 'work')">
        <div class="icon"></div>
        <p><span class="bold">why does</span> Gabrielle Geroudet <span class="bold">want to work for Google</span></p>
      </div>
      <div id="btnSearch">
        <button>Google Search</button>
        <button>I'm feeling lucky</button>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'GoogleSearch',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.GoogleSearch {
  display: flex;
  justify-content: center;
}

.search {
  display: flex;
  margin: 10px 5px;
}

#searchBar {
  box-shadow: 0 1px 6px 0 rgb(183 183 183);
  width: 560px;
  text-align: left;
  border-radius: 20px;
}

.icon {
  -webkit-mask-image: url(../assets/search.svg);
  -webkit-mask-position: center;
  -webkit-mask-repeat: no-repeat;
  -webkit-mask-size: 20px;
  background-color: rgb(124 127 131);
  background-position: center center;
  background-repeat: no-repeat;
  background-size: 16px;
  height: 24px;
  width: 24px;
  padding-left: 10px;
}

#searchBar p, #icon {
  margin: auto 0;
}

#searchBar p {
  padding-left: 15px;
}

.bold {
  font-weight: bold;
}

.answer:hover {
  background: #eee;
}

.answer {
  display: flex;
  padding: 10px 5px;
}

#btnSearch {
  text-align: center;
}

#btnSearch button {
  background-color: #f8f9fa;
  border: 1px solid #f8f9fa;
  border-radius: 4px;
  color: #3c4043;
  font-family: arial,sans-serif;
  font-size: 14px;
  margin: 11px 4px;
  padding: 0 16px;
  line-height: 27px;
  height: 36px;
  min-width: 54px;
  text-align: center;
  cursor: pointer;
  user-select: none;
}

#btnSearch button:hover {
  box-shadow: 0 1px 1px rgb(0 0 0 / 10%);
  background-color: #f8f9fa;
  border: 1px solid #dadce0;
  color: #202124;
}

#voiceSearchBtn {
  background: url(../assets/googlemic.svg) no-repeat center;
  background-size: 21px 21px;
  border: none;
  border-radius: 2px;
  cursor: pointer;
  height: 100%;
  outline: none;
  padding: 0;
  pointer-events: auto;
  width: 26px;
}
</style>
