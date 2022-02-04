<template>
    <div class="flex min-h-screen items-center justify-center">
        <div class="relative m-auto w-[350px] h-[712px] bg-black rounded-[60px] 
        overflow-hidden border-8 border-black">
            <img class="absolute h-full w-full object-cover" src="@/static/background.jpeg" >
            <div class="absolute top-0 inset-x-0 mx-auto bg-black w-[130px] h-[23px] rounded-b-lg" />
            <div class="relative">
                <div class="mt-16 flex flex-col items-center">
                    <svg xmlns="http://www.w3.org/2000/svg" class="h-8 w-8 text-white" viewBox="0 0 20 20" fill="currentColor">
                    <path d="M10 2a5 5 0 00-5 5v2a2 2 0 00-2 2v5a2 2 0 002 2h10a2 2 0 002-2v-5a2 2 0 00-2-2H7V7a3 3 0 015.905-.75 1 1 0 001.937-.5A5.002 5.002 0 0010 2z" />
                    </svg>
                    <p class="mt-3 text-white text-6xl font-extralight">11:19</p>
                    <p class="mt-1 text-white text-lg font-light">Friday, Feb 4</p>
                </div>
                <div class="flex flex-col p-4">
                    <div class="bg-white/50 w-full h-[300px] rounded-3xl p-4">
                        <div class="flex justify-between ">
                            <div>
                                <p class="font-bold text-sm">9:30 AM</p>
                                <div class="text-lg font-bold">Your morning summary </div>
                            </div>
                            <span class="bg-gray-500 h-8 w-8 rounded-full text-white flex items-center justify-center">11</span>

                        </div>
                        <div class="mt-2 flex justify-between space-x-4"> 
                            <div>
                                <img class=" rounded h-24 w-full object-cover" src="https://media.bleacherreport.com/image/upload/v1625368217/ilertc3nqs53klcp9xvx.jpg" > 
                                <h3 class="pt-2 text-sm font-bold leading-tight"> NBA Finals Are Here!</h3>
                                <p class="pt-1 text-xs "> Bucks vs Suns is shaping up to be a very intriguing series! </p>
                            </div>
                            <div>
                                <img class=" rounded h-24 w-full object-cover" src="https://media.bleacherreport.com/f_auto,w_1280,q_auto,c_fill/br-cms/b2/cf/5f/7c/dfa6/488d/87a3/f67fbb636a7b/crop_exact_GettyImages-1236758703.jpeg" > 
                                <h3 class="pt-2 text-sm font-bold leading-tight"> NBA Finals Are Here!</h3>
                                <p class="pt-1 text-xs "> Bucks vs Suns is shaping up to be a very intriguing series! </p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>