<template>
  <div>
     OLA
  </div>  
</template>

<script> 

export default {  
  mounted() {
    this.openPdf()
  },
  methods: {
    openPdf() {
      const file = this.$route.params.file
      const pdfUrl = '/a_arte_de_alcancar_uma_vida_plena' + file + '.pdf'
      // window.open(pdfUrl, '_blank')
    }
  }
}
</script>
