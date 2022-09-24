<template>
  <div class="page-success">
    <div class="columns multiline">
      <div class="column is-12">
        <h1 class="title">Success</h1>

        <p>Your order will be processed within 48 hours</p>
      </div>
    </div>
  </div>
</template>

<script>
    export default{
        name:'success',
        components: {},
        mounted() {
            document.title = 'Success | Django Store'
        }
    }
</script>