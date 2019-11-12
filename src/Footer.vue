<template>
  <div class="row">
      <div class="col-xs-12">
        <footer>
          <p>{{copyright}} <a :href="link">{{ link.replace(this.link, "videosinif.com") }}</a></p>
        </footer>
      </div>
    </div>
</template>

<script>
export default {
    data: function() {
        return {
            copyright : "Tüm Hakları Saklıdır | ",
            link : "http://videosinif.com"
        }
    }
}
</script>

 