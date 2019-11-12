<template>
  <div class="row">
    <div class="col-xs-12 col-sm-6">
        <Server></Server>
    </div>
    <div class="col-xs-12 col-sm-6">
      <p>{{serverStatus}}</p>
    </div>
  </div>
</template>

<script>
import Server from "./Server";
export default {
    data: function() {
        return {
            serverStatus : "Sunucu Bilgisi güncel değil!!"
        }
    },
    components: {
      Server
    }
}
</script>

<style scoped>
    p {
        border: 1px solid #ddd;
        padding: 10px 15px;
        border-radius: 4px;
        background: #ffe0e0;
        text-shadow: 1px 1px #fff;
    }
</style>