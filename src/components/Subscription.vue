<template>
    <div class="subscription relative -top-4  h-full">
        <div class="w-full">
            <p class="text-center text-[28px] md:text-[42px] lg:text-5xl font-bold pt-20 pb-10 text-white">Fork Subscription Pricing</p>
            <div class="grid grid-cols-1 gap-x-3 gap-y-3 items-center justify-center md:h-[1120px] lg:h-[560px] px-[30px] md:px-[109px] lg:px-[133px] md:grid-cols-2 lg:grid-cols-4">
                <div class="text-white w-full flex flex-col items-center h-fit hover:h-[560px] group transform transition-all  duration-500">
                    <div class="bg-white bg-opacity-[0.06] duration-500 w-full group-hover:transition-all group-hover:bg-black group-hover:bg-opacity-[0.11]">
                        <p class=" text-2xl text-center uppercase py-8">Student</p>
                    </div>
                    <div class="bg-white w-full flex flex-col items-center justify-center pt-8 bg-opacity-[0.11]  duration-500 group-hover:bg-[#463048] group-hover:transition-all group-hover:bg-opacity-[0.84]">
                        <p class="font-bold text-6xl group-hover:text-8xl group-hover:transition-all  duration-500 ease-out"><span class="font-normal">$</span>29</p>
                        <p class="uppercase pt-5">per month</p>
                        <hr class="w-12 my-7 border-[rgb(141,129,172)] border-2">
                        <p class=" h-11 px-5 text-center">Personal License</p>
                        <p class="bg-white bg-opacity-[0.15] py-4 px-9 rounded-full mt-9 mb-8  duration-500  group-hover:transition-all group-hover:mt-20">Purchase</p>
                    </div>
                </div>
                <div class="text-white flex flex-col items-center h-fit hover:h-[560px] transform transition-all  duration-500 group">
                    <div class="bg-white bg-opacity-[0.06] w-full group-hover:transition-all group-hover:bg-black group-hover:bg-opacity-[0.11]">
                        <p class=" text-2xl text-center uppercase py-8">Professional</p>
                    </div>
                    <div class="bg-white w-full flex flex-col items-center justify-center pt-8 bg-opacity-[0.11] group-hover:bg-[#463048] group-hover:transition-all group-hover:bg-opacity-[0.84]">
                        <p class="font-bold text-6xl group-hover:text-8xl group-hover:transition-all"><span class="font-normal">$</span>59</p>
                        <p class="uppercase pt-5">per month</p>
                        <hr class="w-12 my-7 border-[#8D81AC] border-2">
                        <p class=" h-11 px-6 text-center">Professional License Email Support</p>
                        <p class="bg-white bg-opacity-[0.15] py-4 px-9 rounded-full mt-9 mb-8 group-hover:transition-all group-hover:mt-20">Purchase</p>
                    </div>
                </div>
                <div class="text-white flex flex-col items-center h-fit hover:h-[560px] transform transition-all  duration-500 group">
                    <div class="bg-white bg-opacity-[0.06] w-full group-hover:transition-all group-hover:bg-black group-hover:bg-opacity-[0.11]">
                        <p class=" text-2xl text-center uppercase py-8">Agency</p>
                    </div>
                    <div class="bg-white w-full flex flex-col items-center justify-center pt-8 bg-opacity-[0.11] group-hover:bg-[#463048] group-hover:transition-all group-hover:bg-opacity-[0.84]">
                        <p class="font-bold text-6xl group-hover:text-8xl group-hover:transition-all"><span class="font-normal">$</span>99</p>
                        <p class="uppercase pt-5">per month</p>
                        <hr class="w-12 my-7 border-[#8D81AC] border-2">
                        <p class=" h-11 px-5 text-center">1-12 Team Members Phone Support</p>
                        <p class="bg-white bg-opacity-[0.15] py-4 px-9 rounded-full mt-9 mb-8 group-hover:transition-all group-hover:mt-20">Purchase</p>
                    </div>
                </div>
                <div class="text-white flex flex-col items-center h-fit hover:h-[560px] transform transition-all  duration-500 group">
                    <div class="bg-white bg-opacity-[0.06] w-full group-hover:transition-all group-hover:bg-black group-hover:bg-opacity-[0.11]">
                        <p class=" text-2xl text-center uppercase py-8">Enterprise</p>
                    </div>
                    <div class="bg-white w-full flex flex-col items-center justify-center pt-8 bg-opacity-[0.11] group-hover:bg-[#463048] group-hover:transition-all group-hover:bg-opacity-[0.84]">
                        <p class="font-bold text-6xl group-hover:text-8xl group-hover:transition-all"><span class="font-normal">$</span>159</p>
                        <p class="uppercase pt-5">per month</p>
                        <hr class="w-12 my-7 border-[#8D81AC] border-2">
                        <p class=" h-11 px-3 text-center">Unlimited Team Members 24/7 Phone Support</p>
                        <p class="bg-white bg-opacity-[0.15] py-4 px-9 rounded-full mt-9 mb-8 group-hover:transition-all group-hover:mt-20">Purchase</p>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>

export default{
    name:"Subscription",

}
</script>