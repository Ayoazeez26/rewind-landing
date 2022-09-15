<script>
export default {
}
</script>

<template>
  <section class="w-full h-screen bg-black mb-5">
    <div class="container-gravy h-full">
      <div id="hero" class="header h-full relative flex flex-col justify-end items-center text-center rounded-lg pt-12 md:pt-44">
        <h1 class="header__title text-white font-bold text-4xl md:text-6xl lg:text-7xl lg:leading-snug">
          Refund Your Customers In <span class="text-secondary">Minutes</span>
        </h1>
        <p class="sf header__subtitle text-white font-light tracking-wide text-opacity-80 text-xl md:text-2xl mt-5 mb-12">
          Rewind makes refunds faster and easier, to boost customer satisfaction.
        </p>
        <a href="#footer" data-type="button" class="btn bg-secondary rounded-full text-black px-20 font-semibold py-4 btn-primary">
          Join waiting List
        </a>
        <a href="#why" class="mt-28 mb-8">
          <div id="why" />
          <img src="@/assets/images/scroll.png" alt="scroll image">
        </a>
      </div>
    </div>
  </section>
</template>

<style lang="scss" scoped>
.header {
  // margin-top: 151px;
  // margin-left: -10px;
  // margin-right: -10px;
  &__title {
    width: 100%;
    max-width: 901px;
  }
  &__subtitle {
    width: 100%;
    max-width: 580px;
  }
  &__bg {
    width: 652px;
    @media screen and (min-width: 768px) and (max-width: 1280px) {
      display: none;
    }
  }
  @media screen and (max-width: 640px) {
    margin-top: 80px;
    margin-left: 0;
    margin-right: 0;
  }
}
</style>
