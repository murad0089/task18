<template>
    <div class="relative">
        
        <div class="bg-[#27262A] md:bg-[#27262A] lg:bg-black bg-opacity-100 absolute top-0 flex flex-wrap
         md:justify-center items-center lg:justify-between text-[#8D81AC] py-5 w-full">
            <div class="flex justify-between items-center w-full">
                 <div class="flex w-1/3 px-5 md:w-1/3 md:px-12 md:py-3 items-center">
                    <img src="../assets/Logo/Logo 1.png" alt="">
                    <p class="font-bold px-6 text-xl hidden md:inline-block hover:text-white transition ">FORKIO</p>
                </div>
                <div class="w-3/6 justify-around hidden lg:flex items-center font-bold py-3 pr-4 ">
                    <a class="hover:text-white transition " href="">Overview</a>
                    <a class="hover:text-white transition " href="">About Fork</a>
                    <a class="hover:text-white transition " href="">Buying Options</a>
                    <a class="hover:text-white transition " href="">Support</a>
                </div>
                <div v-show="show==false" class="absolute m-auto left-0 right-0 space-y-8 z-10 w-11/12 top-20 text-white font-normal bg-[#333333] justify-center flex flex-col">
                    <a class="text-[26px] py-8 px-10 hover:text-[#8D81AC] transition" href="">Overview</a>
                    <a class="text-[26px] py-8 px-10 hover:text-[#8D81AC] transition" href="">About Fork</a>
                    <a class="text-[26px] py-8 px-10 hover:text-[#8D81AC] transition" href="">Buying Options</a>
                    <a class="text-[26px] py-8 px-10 hover:text-[#8D81AC] transition" href="">Support</a>
                </div>
                <button class="bg-[#8D81AC] w-1/3 h-2/3 md:w-auto py-2 px-3  lg:px-9 md:px-6 md:py-1 md:mr-6 text-base text-white rounded-full hover:text-[#8D81AC] hover:bg-white transition ">Buy now</button>
                <i class="fa fa-bars w-1/3  md:hidden text-center" @click="show=!show" v-show="show==true" aria-hidden="true"></i>
                <i class="fa fa-times w-1/3 md:hidden text-center" @click="show=!show" v-show="show==false" aria-hidden="true"></i>
            </div>
           
            <div class="w-full gap-7 justify-center hidden lg:hidden font-bold md:flex">
                <a class="hover:text-white transition " href="">Overview</a>
                <a class="hover:text-white transition " href="">About Fork</a>
                <a class="hover:text-white transition " href="">Buying Options</a>
                <a class="hover:text-white transition " href="">Support</a>
            </div>
        </div>
            <div class="flex flex-col absolute top-40 justify-center items-center w-full bg-opacity-100 text-center">  
                <div class="space-y-4">
                    <p class="font-bold text-white text-5xl md:text-7xl lg:text-[82px]">Fork App</p>
                    <p class="text-[#8D81AC]  text-lg md:text-2xl lg:text-[30px] ">A real gamechanger in the world of web development</p>
                    <p class="text-[#848E97] text-[16px] ">v. 2.8 For Mac and Windows</p>
                </div>
            </div>
        <div class="flex absolute -bottom-7 justify-center w-full">
            <button class="bg-[#8D81AC] rounded-full text-white px-7 md:px-14 py-4 font-bold text-base md:text-[21px] hover:text-[#8D81AC] hover:bg-white transition border-2 border-[#8D81AC]">Download For Free Now</button>
        </div>
        <img class="-z-10 md:w-full object-cover top-0 h-[718px] md:h-[800px]" src="../assets/Bg-images/img 1.png" alt="">
        
    </div>
</template>

<script>

export default{
    name:'Header',
    data(){
        return{
            show:true,
        }
    }
}
</script>