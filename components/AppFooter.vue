<script>
export default {
}
</script>

<template>
  <footer id="footer" class="bg-black mx-auto mt-5">
    <div class="container-gravy flex flex-col-reverse md:flex-row justify-between items-center footer relative mx-auto rounded-lg px-10 py-7">
      <p class="text-xs copy text-white">
        © 2022 Rewind Inc. All rights reserved.
      </p>
      <a href="https://splish.notion.site/REWIND-FAQ-a4b30fcde63d43cd9185ff9edb3a4c1f" target="_blank" class="text-white mb-3 md:mb-0">
        FAQs
      </a>
      <div class="flex justify-between items-center max-w-min">
        <a href="https://www.facebook.com" target="_blank" class="item w-10 h-10 flex items-center justify-center">
          <img src="@/assets/icons/facebook.svg" alt="Facebook Icon" class="">
        </a>
        <a href="https://twitter.com/getrewindnow?s=21&t=VFLsWllT1hJNA6fDp2CAMQ" target="_blank" class="item w-10 h-10 flex items-center justify-center ml-2">
          <img src="@/assets/icons/twitter.svg" alt="Twitter Icon" class="">
        </a>
        <a href="https://instagram.com/getrewind?igshid=MTA0ZTI1NzA=" target="_blank" class="item w-10 h-10 flex items-center justify-center ml-2">
          <img src="@/assets/icons/instagram.svg" alt="Instagram Icon" class="">
        </a>
        <a href="https://www.linkedin.com/company/getrewind/?viewAsMember=true" target="_blank" class="item w-10 h-10 flex items-center justify-center ml-2">
          <img src="@/assets/icons/linkedin.svg" alt="LinkedIn Icon" class="">
        </a>
      </div>
    </div>
  </footer>
</template>

<style lang="scss" scoped>
.footer {
  @media screen and (max-width: 768px) {
    margin-left: 0;
    margin-right: 0;
  }
}
</style>
