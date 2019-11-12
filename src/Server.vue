<template>
  <div>
    <ul class="list-group">
      <li class="list-group-item" v-bind:key="index" v-for="index in array">Sunucu {{ index }}</li>
    </ul>
  </div>
</template>

<script>
export default {
  data: function() {
    return {
      array: [
          '#1',
          '#2',
          '#3', 
          '#4',
          '#5',
        ]
    };
  }
};
</script>


 