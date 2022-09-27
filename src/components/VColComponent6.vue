<template>
  <div class="container">
    <div class="row">
        <div class="col-md-4 card">
            row 1 col 1
        </div>
        <div class="col-md-4 card">
            row 1 col 2
        </div>
    </div>
  </div>
</template>

<script>
export default {
    name: 'VColComponent6',
}
</script>

<style scoped>

.container .row {
    width: 100% !important;
    display: flex !important;
    justify-content: space-between !important;
    align-items: center !important;
    border: solid 2px red !important;
}

</style>