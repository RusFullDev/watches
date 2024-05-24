<script >
export default{
data(){
  return{
  watches:[
    {
    name:'Apple',
    describe:'Apple is one of the most famous smart watches providing company.',
    img:'/apple-watch-series7-black-myshop-pk-1-removebg-preview 1.png'
  },
  {
    name:'Xiaomi',
    describe:'Xiaomi smart watches are produced by MI company.',
    img:'/xiaomi_redmi_watch_2_lite_azul_01_l-removebg-preview 1.png'
  },
  {
    name:'FitBit',
    describe:'FitBit smart watches are best for there health and fitness features.',
    img:'/FitBit.png'
  },
  ]
  }
}
}
</script>


<template>
  <div class="bg-[#383638] h-[877px]">
    <div class="container mx-auto">
      <header class="h-[70px] flex justify-between text-[Poppins]">
        <div class="flex items-center gap-2">
          <img src="../public/Apple Watch.png" alt="">
          <p class="text-[#FFFFFF] font-medium text-base">Mohid</p>
        </div>
        <div class="flex items-center gap-7">
          <a href="#"><p class="text-[#8B8E99] font-medium text-base">Home</p></a>
          <div class="flex gap-1 items-center">
            <a href="#"><p class="text-[#8B8E99] font-medium text-base">Brands</p></a>
            <img src="../public/chevron-down.png" alt="">
          </div>
          <a href="#"><p class="text-[#8B8E99] font-medium text-base">Recent Products</p></a>
          <a href="#"><p class="text-[#8B8E99] font-medium text-base">Contact</p></a>
         <a href="#"><p class="text-[#8B8E99] font-medium text-base">About</p></a>
        </div>
        <div class="flex items-center gap-4">
          <img src="../public/Search.png" alt="">
          <img src="../public/Person.png" alt="">
          <div class="flex items-center ">
            <img src="../public/Shopping Cart.png" alt="">
          <img src="../public/1.png" alt="" class="pb-5">
          </div>
        </div>
      </header>
  <div class="text-[Poppins] flex gap-[183px] items-center">
    <div class="pt-[200px]">
    <h1 class="text-white text-[64px] leading-[80.32px] font-bold text-[Poppins] w-[457px]">Discover Most Suitable Watches</h1>
    <p class="text-[#8B8E99] font-medium text-base text-[Poppins] w-[456px] pb-[47px] pt-5">Find the best, reliable, and cheap smart watches here. We focus on product quality. Here you can find smart watches of almost all brands. So why you are waiting? Just order now!</p>
  <div class="flex items-center relative">
    <div class="absolute z-10 left-2"><img src="/searchwwwwwwwwwwwwwwwww2.png" alt="" ></div>
    <input type="text" name="" id="" class="h-[60px] w-[443px] rounded-2xl">
   <div class="absolute z-10 left-80"> <button class=" h-[45px] w-[112px] rounded-xl bg-[#3858D6] text-white font-semibold text-lg leading-[23px]">Search</button></div>
  </div>
</div>
<div>
  <img src="/watch.png" alt="">
</div>
  </div>
</div>
  </div>
  
  <div class="grid grid-cols-3 gap-5 mt-[73px] pb-[135px]">
    <div v-for="item,index in watches":key="index" class="w-354px h-239px bg-[#F6F6F6] rounded-[22px] gap-[26px] ">
<div class="text-[Inter] flex gap-8 pl-10 py-10 w-[354px]">
  <img :src="item.img" alt="">
  <div class="w-[173px]">
<h3 class="text-[#1E1D1D] font-bold text-4xl">{{ item.name }}</h3>
<p class="text-[#8B8E99] text-base font-medium">{{ item.describe }}</p>
</div>
</div>
    </div>
  </div>
  
</template>





<style scoped>

</style>
