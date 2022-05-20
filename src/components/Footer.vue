<template>
  <div class="footer">
    <div class="socials">
      <div><a href="#" target="_blanck"></a><i class="fa-brands fa-facebook-square"></i></div>
      <div><a href="#" target="_blanck"></a><i class="fa-brands fa-twitter"></i></div>
      <div><a href="#" target="_blanck"></a><i class="fa-brands fa-instagram"></i></div>
    </div>

    <div class="tel"><p>TEL: 08034459549</p></div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
      .footer{
            width: 30%;
            margin: auto auto;
            padding-bottom: 40px;
      }

      .socials{
            display: flex;
            justify-content: space-around;
      }
      .tel{
            padding-top: 30px;
            text-align: center;
            font-size: 20px;
            font-weight: 900 !important;
            font-style: italic;
      }
</style>