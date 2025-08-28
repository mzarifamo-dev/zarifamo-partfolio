<script setup lang="ts">

</script>

<template>
  <section class="dark:bg-gray-800 bg-[#F9F9F9]">
    <div class="max-w-[556px] px-4 py-10 mx-auto  flex flex-col ">
      <div class="w-full flex flex-col gap-5">
        <div class="flex gap-9">
          <label class="flex items-center gap-4"><input type="radio" class="w-7 h-7  accent-[#b9ff66]"><span class="justify-start dark:text-white text-black text-base sm:text-lg font-normal ">Say Hi</span></label><label class="flex items-center gap-4"><input type="radio" class="w-7 h-7  accent-[#b9ff66]"><span class="justify-start dark:text-white text-black text-base sm:text-lg font-normal ">Get a Quote</span></label>
        </div>
        <div class="w-full flex flex-col justify-start items-start gap-6">
          <div class="w-full">
            <label class=" dark:text-white text-black text-base font-normal  leading-7">Name*</label><input placeholder="Name" type="text" class="mt-2 w-full px-5 py-2 bg-white rounded-xl outline outline-1 outline-offset-[-1px] outline-black  overflow-hidden  text-[#898989] text-lg font-normal ">
          </div>
          <div class="w-full">
            <label class="dark:text-white text-black text-base font-normal  leading-7">Email*</label><input placeholder="Email" type="email" class="mt-2 w-full px-5 py-2 bg-white rounded-xl outline outline-1 outline-offset-[-1px] outline-black  overflow-hidden  text-[#898989] text-lg font-normal ">
          </div>
          <div class="w-full">
            <label class="dark:text-white text-black text-base font-normal  leading-7">Message*</label><textarea class="mt-2 w-full resize-none px-5 py-2 bg-white rounded-xl outline outline-1 outline-offset-[-1px] outline-black  overflow-hidden  text-[#898989] text-lg font-normal " placeholder="Message" cols="40" rows="10"></textarea>
          </div>
        </div>
        <button class=" px-9 py-5 bg-[#191a23] rounded-2xl  dark:bg-white text-center dark:text-[#191a23]  text-white text-xl font-normal  leading-7">Send Message</button>
      </div>
    </div>
  </section>
</template>

<style scoped>

</style>