<template>
  <div class="question1-container">
    <span class="question1-text heading3">{{ Question }}</span>
    <span class="bodySmall">{{ Answer }}</span>
  </div>
</template>

<script>
export default {
  name: 'Question1',
  props: {
    Question: {
      type: String,
      default: 'What types of cars do you sell?',
    },
    Answer: {
      type: String,
      default:
        'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed non volutpat turpis. Mauris luctus rutrum mi ut rhoncus.',
    },
  },
}
</script>

<style scoped>
.question1-container {
  gap: var(--dl-space-space-unit);
  flex: 1;
  width: auto;
  height: auto;
  display: flex;
  position: relative;
  align-items: flex-start;
  flex-direction: column;
}
.question1-text {
  font-weight: 700;
}
</style>
