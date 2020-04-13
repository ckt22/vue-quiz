<template>
<div class="question-box-container">
  <b-jumbotron header="BootstrapVue" lead="Bootstrap v4 Components for Vue.js 2">

    <template v-slot:lead>
        Some question here?
    </template>

    <hr class="my-4">

    <p>
        List of answers
    </p>

    <b-button variant="primary" href="#">Submit</b-button>
    <b-button variant="success" href="#">Next</b-button>
  </b-jumbotron>
</div>
</template>