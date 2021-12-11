<template>
  <div class="result">
    <cite role="textbox">
      https://workingforgoogle.com
    </cite>
    <div class="resultTitle">
      <h3>Why does Gabrielle Geroudet want to work for Google ?</h3>
    </div>
    <div class="resultText">
      <p>
        Working at Google would be an achievement. I think that Google kind of helped
        creating the Internet, thanks to their search engine that helps you find any website
        you want. I also live with a lot of connected objects from Google like ChromeCast or
        Google Home because I enjoy their products. In a day, I have at least one interaction
        with a Google product or service, and I would love to be a part of it too. And since it
        is so hard to join Google, it would be the Holy Grail to work for them.<br>
        For example, Google's website is coded in different Javascript frameworks. I would
        love to gain experience in these because I think that it is the future of front end
        developing. I would like to gain skills in pair programming too. Google must have a
        dev team. I think that it is important to learn coding a project with other devs. I can
        learn different coding techniques and I would have to deal with problems when
        several people are coding at the same time. Thanks to that experience, I would gain
        knowledge in code that is important to web development.
      </p>
    </div>
  </div>
</template>

<script>
export default {
  name: "Work"
}
</script>

<style>

.resultTitle h3 {
  font-size: 20px;
  line-height: 1.3;
  margin-bottom: 3px;
  font-weight: normal;
  color: #1a0dab;
  cursor: pointer;
  margin-top: 5px;
}

.result cite {
  padding-top: 20px;
  font-size: 14px;
  line-height: 1.3;
  color: #202124;
  font-style: normal;
}

.resultTitle h3:hover {
  text-decoration: underline;
}

.resultText p {
  color: #4d5156;
  line-height: 1.58;
  font-size: 14px;
  font-weight: normal;
  margin: 0;
}

.result {
  width: 600px;
}
</style>