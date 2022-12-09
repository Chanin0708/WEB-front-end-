<template>
<div>
  <b-card no-body class="text-center">
    <div class="bg-secondary text-light">
      This is some content without the default <samp>&lt;b-card-body&gt;</samp> section. Notice the
      lack of padding between the card's border and this gray <samp>&lt;div&gt;</samp>.
    </div>
  </b-card>
</div>
    </template>
    
    <script>
    export default {
      name: 'Footer',
      props: {
        msg: String
      }
    }
    </script>
    