<script>
export default {}
</script>

<template>
  <section id="how" class="why mt-20 mx-auto mb-20 sm:mb-40">
    <div class="container-gravy">
      <div class="flex flex-col justify-center items-center">
        <h2 class="head header__title text-primary text-3xl lg:text-4xl font-bold mb-4">
          How <span class="text-secondary">Rewind</span> Works
        </h2>
        <p class="sf why__subtitle font-light tracking-wide text-center text-opacity-80 text-lg mb-10">
          Get started with Rewind in these easy steps
        </p>
        <div class="steps flex flex-col w-full mt-12">
          <div class="flex flex-col md:flex-row justify-between relative">
            <div class="steps-desc flex flex-col md:mt-20 mb-10 md:mb-0">
              <h3 class="font-semibold text-3xl text-black mb-6">
                Step 1 - Create A Refund Link
              </h3>
              <p class="steps-desc">
                After signing up your business on Rewind, create a refund link and send to your customer. Soon as your customer is done initiating the refund, you will be notified on your mail.
              </p>
            </div>
            <img src="@/assets/images/refund-img.png" alt="step one image">
            <img src="@/assets/icons/left-dir.svg" alt="left arrow" class="hidden md:block absolute -bottom-20 right-72">
          </div>
          <div class="flex flex-col-reverse md:flex-row justify-between relative mt-10 md:mt-20">
            <img src="@/assets/images/confirm-img.png" alt="step one image">
            <div class="steps-desc flex flex-col md:mt-32">
              <h3 class="font-semibold text-3xl text-black mb-6">
                Step 2 - Confirm Refund
              </h3>
              <p class="steps-desc">
                Confirm the refund initiated and assign approval to a person of higher authority if need be.
              </p>
            </div>
            <img src="@/assets/icons/right-dir.svg" alt="right arrow" class="hidden md:block absolute -bottom-20 left-72">
          </div>
          <div class="flex flex-col md:flex-row justify-between">
            <div class="steps-desc flex flex-col md:mt-48">
              <h3 class="font-semibold text-3xl text-black mb-6">
                Step 3 - Approve Refund
              </h3>
              <p class="steps-desc">
                After confirmation through the customer's reference code, Approval can now be initiated;
              </p>
            </div>
            <img src="@/assets/images/success.png" alt="step one image">
          </div>
        </div>
        <div class="mt-20 lines md:mt-40 bg-black rounded-xl flex flex-col items-center justify-center py-20 w-full">
          <h1 class="cta__title text-white text-center font-bold text-3xl md:text-4xl lg:leading-snug mb-6">
            Are You Ready To Start Refunding The Easy Way?
          </h1>
          <a href="https://splish.notion.site/REWIND-FAQ-a4b30fcde63d43cd9185ff9edb3a4c1f" data-type="button" class="btn bg-secondary rounded-full text-black px-20 font-semibold py-4 btn-primary" target="_blank">
            Coming this Fall
          </a>
        </div>
      </div>
    </div>
  </section>
</template>

<style lang="scss" scoped>
.lines {
  background-image: url('@/assets/images/cta_lines.png');
  background-size: cover;
  background-repeat: no-repeat;
  background-position: center;
}
.why {
  .steps {
    &-desc {
      width: 100%;
      max-width: 500px;
    }
  }
  .cta__title {
    width: 100%;
    max-width: 520px;
  }
  &__subtitle {
    width: 100%;
    max-width: 570px;
  }
  &-btn {
    border-radius: 53px;
    padding: 16px 36px;
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
