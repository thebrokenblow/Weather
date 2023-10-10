<template>
  <section class="section-bottom">
    <div class="block-bottom">
      <div class="block-bottom-inner">
        <div class="block-bottom-pic pic-humidity"></div>
        <div class="block-bottom-texts">
          <div class="block-bottom-text-block">
            <div class="block-bottom-text-block-title">
              Humidity: {{ this.humidity }} %
            </div>
            <div class="block-bottom-text-block-desc">
              Humidity is the concentration of water vapor present in the air.
              Water vapor, the gaseous state of water, is generally invisible to
              the human eye.
              <br /><br />
              The same amount of water vapor results in higher relative humidity
              in cool air than warm air.
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  props: {
    humidity: {
      type: Number,
      required: true,
    },
  },
};
</script>
