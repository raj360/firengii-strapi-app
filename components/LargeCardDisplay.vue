<template>
  <div class="container">
    <h4>{{cardsSection.title}}</h4>

    <div class="snippet">
      {{cardsSection.snippet}}
    </div>

    <div class="cards-container">

    </div>
  </div>
</template>

<script>
export default {
  props:['cardsSection']
};
</script>

<style  scoped>
.container {
    margin-top: 20rem;
}
    .header {
        font-weight: 700;
        font-size: 1.5rem;
    }
    .snippet {
        color: grey;
        margin-bottom: 1.5rem;
    }
    .cards-container {
        display: flex;
        justify-content: space-between;
    }
</style>
