<template>
  <div class="note-container">
    <div class="note-selectors">
      <div class="note-selector active">
        <p class="note-selector-title">First note...</p>
        <p class="note-selector-timestamp">Timestamp here...</p>
      </div>
      <div class="note-selector">
        <p class="note-selector-title">Second note...</p>
        <p class="note-selector-timestamp">Timestamp here...</p>
      </div>
      <div class="note-selector">
        <p class="note-selector-title">Third note...</p>
        <p class="note-selector-timestamp">Timestamp here...</p>
      </div>
    </div>
  </div>
</template>

<script>
import NoteSelectors from "./NoteSelectors";

export default {
  components: {
    NoteSelectors,
  },
};
</script>
