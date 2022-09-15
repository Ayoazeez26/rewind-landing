<script>
export default {
  data: () => ({
    blogs: [
      {
        title: 'Saves Time',
        desc: 'Saves time and eliminates hours of manual work with automated payment refunds.',
        image: 'saves-time'
      },
      {
        title: 'Customer Satisfaction',
        desc: 'The swiftness of each refund guarantees customer satisfaction.',
        image: 'customer'
      },
      {
        title: 'Expand Digital Financial Services',
        desc: 'Manage existing bank accounts in one dashboard.',
        image: 'accounts'
      },
      {
        title: 'Control Over Refunds',
        desc: 'Visibility, Permissions and control over refunds in real-time.',
        image: 'control'
      },
      {
        title: 'Maximize Productivity',
        desc: 'Rewind helps people focus on other aspects of their business',
        image: 'productivity'
      },
      {
        title: 'Versatility',
        desc: 'Any business that accepts payment can adopt Rewind into their payment system. Be it Fintech, E-commerce, etc.',
        image: 'versatility'
      }
    ]
  }),
  methods: {
    getImage (pic) {
      return require(`@/assets/icons/${pic}.svg`)
    }
  }
}
</script>

<template>
  <section class="why mt-20 mx-auto mb-20 sm:mb-40">
    <div class="container-gravy">
      <div class="flex flex-col justify-center items-center">
        <h2 class="head header__title text-primary text-3xl lg:text-4xl font-bold mb-4">
          Why Choose <span class="text-secondary">Rewind</span>?
        </h2>
        <p class="sf header__subtitle text-white font-light tracking-wide text-opacity-80 text-xl md:text-2xl mt-5 mb-12">
          Rewind gives businesses the credit they need to issue instant refunds to customers. Here are some reasons why you should choose Rewind
        </p>
        <div class="blogs flex space-y-6 sm:space-y-0 sm:space-x-6 flex-wrap mb-16">
          <div v-for="(blog, index) in blogs" :key="index" class="blog p-8">
            <div class="blog-icon bg-secondary rounded-xl flex items-center justify-center w-12 h-12">
              <img :src="getImage(blog.image)" :alt="blog.image">
            </div>
            <h5 class="text-primary text-2xl font-bold mt-4">
              {{ blog.title }}
            </h5>
            <p class="high-tracking mt-1 font-light tracking-wide">
              {{ blog.desc }}
            </p>
          </div>
        </div>
        <div class="mt-10 w-5/6 h-px bg-primary mx-auto" />
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
    .high-tracking {
      line-height: 180%;
    }
  }
  &__subtitle {
    width: 100%;
    max-width: 644px;
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
