<template>
  <div class="result">
    <cite role="textbox">
      https://googlegoalsandmissions.com
    </cite>
    <div class="resultTitle">
      <h3>Google goals and missions explained by Gabrielle Geroudet</h3>
    </div>
    <div class="resultText">
      <p>
        Google wants "to provide access to the world's information in one click". It is true since Google is first known
        for its search engine service, its most popular product. This product enables people to easily access
        information from around the world. Everyone should have access to each information you could find on the
        internet and Google understood this well since its creation.<br><br>
        Google also wants "to organize the world’s information and make it universally accessible and useful".
        Ever since its beginnings, the company has focused on developing its algorithms to maximize
        effectiveness and allow people accessing more relevant information for what they searched. Google continues to
        focus on ensuring that people access the information they need.
      </p>
    </div>
  </div>
</template>

<script>
export default {
  name: "Goals"
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
}

.resultTitle h3:hover {
  text-decoration: underline;
}

.resultText p {
  color: #4d5156;
  line-height: 1.58;
  font-size: 14px;
  font-weight: normal;
}

.result {
  width: 600px;
}
</style>