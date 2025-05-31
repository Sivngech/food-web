<template>
    <div class="fixed inset-0 z-50 md:flex items-center justify-center  bg-opacity-50 max-w-[1139px] w-full mx-auto">
        <div class="bg-white rounded shadow-md w-full max-w-5xl mx-4 md:mx-auto md:flex md:gap-5 p-5">
            <div class="hidden md:block w-full max-w-sm mx-auto">
                <img src="public/images/picture2.png" alt="">
            </div>
            <div class="relative w-full max-w-xl mx-auto flex flex-col gap-4 md:overflow-hidden">
                <div class="absolute top-0 right-0 mt-2 mr-2 overflow-hidden">
                    <img src="public/images/Eremove2.png" alt="eremove" class="w-8 h-8 cursor-pointer">
                </div>
                <h1 class="text-2xl md:text-3xl font-semibold md:overflow-hidden">Login</h1>
                <p class="text-base md:text-lg text-gray-600">Enter your email to log in.</p>
                <div style="background-color: #F3F4F6;" class="bg-gray-100 rounded-full px-4 py-2">
                    <input type="text" placeholder="Enter your email"  class="w-full bg-transparent outline-none">
                </div>
                <div style="background-color: #F96540; color:white;" class="text-white rounded-full text-center mt-2">
                    <button class="w-full py-2">
                        Continue
                    </button>
                </div>
                <div class="flex items-center gap-2 mt-4">
                    <div class="flex-grow border-t border-gray-300"> <img src="public/images/Line2.png" alt=""></div>
                    <p class="text-xs text-gray-500">OR</p>

                    <div class="flex-grow border-t border-gray-300"> <img src="public/images/Line2.png" alt=""></div>
                </div>


                <div class="text-center text-xs text-gray-500 px-4">By continuing, you agree to the updated Terms of
                    Sale, Terms of Service, and Privacy Policy.</div>

                <div class="space-y-3">
          <button class="w-full flex items-center justify-center gap-2 bg-[#F1F4FE] rounded-full py-2">
            <img src="/images/Google.png" alt="Google" class="w-5 h-5" />
            <span class="text-sm text-[#EA4336]">Continue with Google</span>
          </button>

          <button class="w-full flex items-center justify-center gap-2 bg-[#F1F4FE] rounded-full py-2">
            <img src="public/images/Logo-fb-simple.png" alt="Facebook" class="w-5 h-5" />
            <span class="text-sm text-[#3F5893]">Continue with Facebook</span>
          </button>

          <button class="w-full flex items-center justify-center gap-2 bg-[#F1F4FE] rounded-full py-2">
            <img src="public/images/Apple.png" alt="Apple" class="w-5 h-5" />
            <span class="text-sm text-black">Continue with Apple</span>
          </button>
        </div>


            </div>


        </div>



    </div>
</template>