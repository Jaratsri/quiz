<template>
  <div>
    <b-button v-b-modal.modal-1>Score</b-button>

    <b-modal id="modal-1" title="Score">
      <p class="my-4">{{ numCorrect }}/{{ numTotal }}</p>
    </b-modal>
  </div>
</template>

<script>
export default {
  props: ["numCorrect", "numTotal"]
};
</script>