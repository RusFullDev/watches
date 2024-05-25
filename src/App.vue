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
  ],
  watch_product:[
{
  img:'/public/MKUQ3_VW_34FR+watch-45-alum-midnight-nc-7s_VW_34FR_WF_CO-removebg-preview (1) 1.png',
  name:'Apple Smart I',
  level:'/public/Frame 5.png',
  oldPrice:'$300.00',
  newPrice:'$255.00',
  like:'/public/Wish List.png',
  addCard:'/public/Add To Cart.png'
},
{
  img:'/public/MKUQ3_VW_34FR+watch-45-alum-midnight-nc-7s_VW_34FR_WF_CO-removebg-preview (1) 1 (1).png',
  name:'Apple Smart II',
  level:'/public/Frame 5.png',
  oldPrice:'$300.00',
  newPrice:'$255.00',
  like:'/public/Wish List.png',
  addCard:'/public/Add To Cart.png'
},{
  img:'/public/MKUQ3_VW_34FR+watch-45-alum-midnight-nc-7s_VW_34FR_WF_CO-removebg-preview (1) 1 (2).png',
  name:'Apple Smart III',
  level:'/public/Frame 5.png',
  oldPrice:'$300.00',
  newPrice:'$255.00',
  like:'/public/Wish List.png',
  addCard:'/public/Add To Cart.png'
}
  ],
  watch_products:[
{
  img:'/public/3.png',
  name:'Apple Smart IV',
  level:'/public/Frame 5.png',
  oldPrice:'$450.00',
  newPrice:'$399.00',
  like:'/public/Wish List.png',
  addCard:'/public/Add To Cart.png'
},
{
  img:'/public/4.png',
  name:'Samsung Watch Pro',
  level:'/public/Frame 5.png',
  oldPrice:'$300.00',
  newPrice:'$255.00',
  like:'/public/Wish List.png',
  addCard:'/public/Add To Cart.png'
},{
  img:'/public/5.png',
  name:'Fitbit Max 1',
  level:'/public/Frame 5.png',
  oldPrice:'',
  newPrice:'$255.00',
  like:'/public/Wish List.png',
  addCard:'/public/Add To Cart.png'
}
  ],
people:[
  {
    img:'/public/person-1.png',
    name:'Hamza Faizi',
    describe:'Don’t waste time, just order! This is the best website to puschase smart watches.',
    level:'/public/Frame 5.png',
  },
  {
    img:'/public/person-2.png',
    name:'Hafiz Huzaifa',
    describe:'I’ve been purchasing smart watches of Mohid for a long time. All the products are good quality.',
    level:'/public/Frame 5.png',
  }
]

  }
}
}
</script>


<template>
  <!-- Header -->
  <div class="bg-[#383638] h-[877px]">
    <div class="container mx-auto">
      <header class="h-[70px] flex justify-between">
        <!-- Logo Mohid -->
        <div class="flex items-center gap-2">
          <img src="../public/Apple Watch.png" alt="">
          <p class="text-[#FFFFFF] font-medium text-base">Mohid</p>
        </div>
      
        <!-- Menu -->
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


      <div class=" md:hidden items-center">
        <img src="../public/Person.png" alt="">
      </div>

      <!-- Search,contact corzina -->
        <div class="flex items-center gap-4 ">
          <img src="../public/Search.png" alt="">
          <img src="../public/Person.png" alt="">
          <div class="flex items-center ">
            <img src="../public/Shopping Cart.png" alt="">
          <img src="../public/1.png" alt="" class="pb-5">
          </div>
        </div>
      </header>
    
      <!-- Navbar -->
  <nav class="flex justify-between items-center">
    <div>
    <h1 class="text-white text-[64px] leading-[80px] font-bold w-[457px] h-[265px] left-[-2px]">Discover Most Suitable Watches</h1>
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
</nav>
</div>
  </div>
  

   <!-- section-1-->
  <div class="container mx-auto">
  <div class="grid grid-cols-3 gap-5 mt-[73px] pb-[135px] text-center">
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
  </div>
  
  <!-- section-2 -->
  <div class="container mx-auto">
    <div class="text-center pb-[65px]">
      <p class="text-base font-medium text-[#3858D6]">Find your favourite smart watch.</p>
      <h2 class="text-[#1E1D1D] text-4xl font-bold">Our Latest Products</h2>
    </div>
  <!-- section-2 -->
<div>
  <div class=" grid grid-cols-3 gap-[50px] pb-16">
    <div v-for="item,index in watch_product":key='index' class="w-[335px] h-[440px]">
    <div class="bg-[#F6F6F6] w-[334px] h-[337px]">
        <img :src="item.img" alt="" class="pl-[41px] pr-[43px] py-[29px]">
      </div>
      <div class="pt-[11px] text-center text-[#1E1D1D] font-semibold text-2xl">
      <h3 class="pb-2">{{ item.name}}</h3>
     <div class="flex justify-center pb-2 "> <img :src="item.level" alt=""></div>
      <div class="flex gap-2 justify-center">
        <p class="text-[#8B8E99] text-txl font-medium line-through">{{ item.oldPrice }}</p>
        <p>{{ item.newPrice }}</p>
      </div>
    </div>
</div>
  </div>
 
  <div class=" grid grid-cols-3 gap-[50px] pb-16">
    <div v-for="item,index in watch_products":key='index' class="w-[335px] h-[440px]">
    <div class="bg-[#F6F6F6] w-[334px] h-[337px]">
        <img :src="item.img" alt="" class="pl-[41px] pr-[43px] py-[29px]">
      </div>
      <div class="pt-[11px] text-center text-[#1E1D1D] font-semibold text-2xl">
      <h3 class="pb-2">{{ item.name}}</h3>
     <div class="flex justify-center pb-2 "> <img :src="item.level" alt=""></div>
      <div class="flex gap-2 justify-center">
        <p class="text-[#8B8E99] text-txl font-medium line-through">{{ item.oldPrice }}</p>
        <p>{{ item.newPrice }}</p>
      </div>
    </div>
</div>
  </div>
  <div class="mb-[145px] flex items-center justify-center">
    <button class="bg-[#3858D6] text-white text-lg font-semibold h-[46px] w-[196px] rounded-3xl ">View More</button>
  </div>
</div>
</div>

<!-- section-3 -->
<div>
  <div class="container mx-auto">
    <div class="text-center pb-[55px]">
      <p class="text-base font-medium text-[#3858D6]">Here are our some of the best clients.</p>
      <h2 class="text-[#1E1D1D] text-4xl font-bold">What People Say About Us</h2>
    </div>

    <div class="flex justify-around mb-[135px]">
    <div v-for="item,index in people":key='index' >
<div class="w-[524px] h-[239px] rounded-3xl bg-[#F6F6F6] flex items-center gap-7">
   <img :src="item.img" alt="" class="pl-8">
    <div>
      <h3 class="text-[#1E1D1D] font-bold text-3xl">{{ item.name }}</h3>
      <p class="w-[255px] text-[#8B8E99] font-medium text-base py-2">{{ item.describe }}</p>
      <img :src="item.level" alt="">    
    </div>
  </div>
</div>

</div>




  </div>
</div>

<!-- section-4 -->
<div class=" ">
  <div class="container mx-auto">
    <div class="flex items-center bg-[#F6F6F6] h-[377px] rounded-3xl  mb-[91px] justify-around">
    <div>
    <h2 class="text-[#1E1D1D] text-4xl font-bold ">Subscribe To Newsletter</h2>
    <p class="text-[#8B8E99] font-medium text-base py-3">Get free guide about smart watches daily.</p>
  <div class="flex items-center relative">
    <input type="text" name="" id="" class="h-[60px] w-[443px] rounded-2xl" placeholder="  Enter Email Address">
   <div class="absolute z-10 left-80"> 
    <button class=" h-[45px] w-[112px] rounded-xl bg-[#3858D6] text-white font-semibold text-lg leading-[23px]" >Subscribe</button></div>
  </div>
</div>
<div>
  <img src="/public/6426000_sd-removebg-preview 1.png" alt="">
</div>
</div>
  </div>
</div>

<footer>
  <div class="bg-[#0B0B0B] h-[65px] flex justify-center items-center text-base font-medium text-white">
    <div>
      <p>Copyright @ 2022 | Mohid</p>
    </div>

  </div>
</footer>

</template>





<style scoped>

</style>
