<script>
export default {}
</script>

<template>
  <section class="why mt-20 mx-auto mb-20 sm:mb-40">
    <div class="container-gravy">
      <div class="flex flex-col justify-center items-center">
        <h2 class="head header__title text-primary text-3xl lg:text-4xl font-bold mb-4">
          How <span class="text-secondary">Rewind</span> Works
        </h2>
        <p class="sf why__subtitle font-light tracking-wide text-center text-opacity-80 text-lg mb-10">
          Get started with Rewind in these easy steps
        </p>
        <div class="steps flex flex-col">
          <div class="flex justify-between">
            <div class="desc flex flex-col">
              <h3 class="font-semibold text-3xl">Step 1 - Create A Refund Link</h3>
              <p class="steps-desc">After signing up your business on Rewind, create a refund link and send to your customer. Soon as your customer is done initiating the refund, you will be notified on your mail.</p>
            </div>
            <img src="@/assets/images/refund-img.png" alt="step one image">
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<style lang="scss" scoped>
.why {
  .blog {
    width: 100%;
    border-radius: 20px;
    max-width: 375px;
    &-icon {
      box-shadow: 0px 8px 12px rgba(71, 61, 46, 0.1);
    }
    &:hover {
      box-shadow: 0px 4px 15px rgba(137, 137, 136, 0.15);
    }
    .high-tracking {
      line-height: 180%;
    }
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
