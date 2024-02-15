<script setup lang="ts">
</script>

<template>
  <form>
    <div>
      <label
        id="scancodeLabel"
        for="scancode">
        Scancode
      </label>
      <input
        id="scancode"
        name="scancode"
        type="text"
        aria-labelledby="scancodeLabel"
        aria-describedby="scancodeDesc"
      />
      <span id="scancodeDesc">abc1234</span>
    </div>
  </form>
</template>