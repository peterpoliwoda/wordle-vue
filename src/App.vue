<script setup></script>

<template>
  <div class="row">Hello Wordle!</div>
</template>

<style scoped>
.row {
  display: flex;
  justify-content: center;
}

.cell {
  width: 60px;
  height: 60px;
  border: 1px solid black;
  margin: 5px;
  font-size: 50px;
  text-align: center;
  text-transform: uppercase;
}

.backgroundGrey {
  background: #d4d4d4;
}

.backgroundGreen {
  background: #b3faa8;
}

.backgroundYellow {
  background: #ffe788;
}
</style>
