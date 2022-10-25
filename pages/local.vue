<template>
  <div class="content">
    <div class="container">
      <div class="mapouter">
        <div class="gmap_canvas">
          <iframe
            class="gmap_iframe"
            width="100%"
            frameborder="0"
            scrolling="no"
            marginheight="0"
            marginwidth="0"
            src="https://maps.google.com/maps?width=650&amp;height=400&amp;hl=en&amp;q=Unimetrocamp campinas&amp;t=&amp;z=14&amp;ie=UTF8&amp;iwloc=B&amp;output=embed"
          ></iframe
          ><a href="https://mcpenation.com/">MCPE Nation</a>
        </div>
      </div>
    </div>
    <br />
    <br />
    <br />
    <br />
    <br />
  </div>
</template>

<script>
export default {}
</script>

<style>
.mapouter {
  position: relative;
  text-align: right;
  width: 100%;
  height: 700px;
}

.gmap_canvas {
  overflow: hidden;
  background: none !important;
  width: 100%;
  height: 700px;
}

.gmap_iframe {
  height: 700px !important;
} /*# sourceMappingURL=local.css.map */
</style>