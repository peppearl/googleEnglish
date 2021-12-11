<template>
  <header id="header">
    <div id="headerLinks">
      <div id="links">
        <div class="divService">
          <a href="/" class="googleService">Gmail</a>
        </div>
        <div class="divService">
          <a href="/" class="googleService">Images</a>
        </div>
      </div>
      <div id="buttons">
        <div id="svg_a">
          <div id="svg_b">
            <div id="svg_c">
              <a id="menuLink" href="/">
                <svg id="googleMenu" focusable="false" viewBox="0 0 24 24">
                  <path
                      d="M6,8c1.1,0 2,-0.9 2,-2s-0.9,-2 -2,-2 -2,0.9 -2,2 0.9,2 2,2zM12,20c1.1,0 2,-0.9 2,-2s-0.9,-2 -2,-2 -2,0.9 -2,2 0.9,2 2,2zM6,20c1.1,0 2,-0.9 2,-2s-0.9,-2 -2,-2 -2,0.9 -2,2 0.9,2 2,2zM6,14c1.1,0 2,-0.9 2,-2s-0.9,-2 -2,-2 -2,0.9 -2,2 0.9,2 2,2zM12,14c1.1,0 2,-0.9 2,-2s-0.9,-2 -2,-2 -2,0.9 -2,2 0.9,2 2,2zM16,6c0,1.1 0.9,2 2,2s2,-0.9 2,-2 -0.9,-2 -2,-2 -2,0.9 -2,2zM12,8c1.1,0 2,-0.9 2,-2s-0.9,-2 -2,-2 -2,0.9 -2,2 0.9,2 2,2zM18,14c1.1,0 2,-0.9 2,-2s-0.9,-2 -2,-2 -2,0.9 -2,2 0.9,2 2,2zM18,20c1.1,0 2,-0.9 2,-2s-0.9,-2 -2,-2 -2,0.9 -2,2 0.9,2 2,2z"></path>
                </svg>
              </a>
            </div>
          </div>
        </div>
        <div>
          <a id="signIn" href="/">Sign in</a>
        </div>
      </div>
    </div>
  </header>
</template>

<script>
export default {
  name: 'Header'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
#googleMenu {
  color: #5f6368;
  cursor: pointer;
  height: 24px;
  width: 24px;
}

.divService {
  display: inline-block;
  padding-top: 13px;
}

#headerLinks {
  display: flex;
  -webkit-box-sizing: border-box;
  box-sizing: border-box;
  height: 48px;
  line-height: normal;
  padding-left: 30px;
  -webkit-flex: 0 0 auto;
  flex: 0 0 auto;
  -webkit-justify-content: flex-end;
  justify-content: flex-end;
}

#links {
  padding-right: 15px;
}

.googleService {
  display: inline-block;
  padding-left: 15px;
  line-height: 24px;
  vertical-align: middle;
  color: rgba(0, 0, 0, 0.87);
  text-decoration: none;
  font-size: 13px;
}

.googleService:hover {
  text-decoration: underline;
}

#buttons {
  display: flex;
}

#svg_a {
  display: inline;
}

#svg_b {
  padding: 4px;
  display: inline-block;
  vertical-align: middle;
}

#svg_c {
  position: relative;
}

#menuLink {
  padding: 8px;
  background-position: -64px -29px;
  display: inline-block;
  outline: none;
  vertical-align: middle;
  -webkit-border-radius: 2px;
  border-radius: 2px;
  -webkit-box-sizing: border-box;
  box-sizing: border-box;
  height: 40px;
  width: 40px;
  color: #000;
  cursor: pointer;
  text-decoration: none;
}

#menuLink:hover {
  background-color: rgba(60, 64, 67, 0.08);
  border-radius: 50%;
}

#signIn {
  color: #fff;
  cursor: pointer;
  margin: 6px 8px 0 8px;
  text-decoration: none;
  background: #1a73e8;
  border: 1px solid transparent;
  font-family: Google Sans, Roboto, RobotoDraft, Helvetica, Arial, sans-serif;
  font-weight: 500;
  font-size: 14px;
  letter-spacing: 0.25px;
  line-height: 16px;
  min-width: 96px;
  padding: 9px 23px;
  text-align: center;
  vertical-align: middle;
  -webkit-border-radius: 4px;
  border-radius: 4px;
  -webkit-box-sizing: border-box;
  box-sizing: border-box;
  display: inline-block;
}

#signIn:hover {
  background: #2b7de9;
  -webkit-box-shadow: 0 1px 2px 0 rgb(66 133 244 / 30%), 0 1px 3px 1px rgb(66 133 244 / 15%);
  box-shadow: 0 1px 2px 0 rgb(66 133 244 / 30%), 0 1px 3px 1px rgb(66 133 244 / 15%);
}

#signIn:active {
  background: #63a0ef;
  -webkit-box-shadow: 0 1px 2px 0 rgb(66 133 244 / 30%), 0 1px 3px 1px rgb(66 133 244 / 15%);
  box-shadow: 0 1px 2px 0 rgb(66 133 244 / 30%), 0 1px 3px 1px rgb(66 133 244 / 15%);
}

#signIn:focus {
  background: #63a0ef;
  -webkit-box-shadow: 0 1px 2px 0 rgb(66 133 244 / 30%), 0 1px 3px 1px rgb(66 133 244 / 15%);
  box-shadow: 0 1px 2px 0 rgb(66 133 244 / 30%), 0 1px 3px 1px rgb(66 133 244 / 15%);
}
</style>
