<div class="mx-auto w-full text-white text-center h-full">

    <!-- bg -->
    <div class="relative isolate bg-gradient-to-t from-[#B5BAE4] to-[#FFFFFF] h-screen">

        <!-- หัวด้านบน -->
        <div class="bg-[#B5BAE4] h-[70px] md:h-[100px] w-full flex items-center justify-between px-4">
            <!-- Logo ด้านซ้าย -->
            <div class="flex-shrink-0">
                <button>
                    <h1 class="font-mitr font-regular text-[#2C2C2C] text-lg md:text-2xl bg-[#FFE3DE] flex items-center justify-center rounded-3xl px-3 py-1 md:px-4 md:py-2">
                        <svg xmlns="http://www.w3.org/2000/svg" width="1.43em" height="1em" viewBox="0 0 256 180" class="mr-2">
                            <path fill="#f00"
                                d="M250.346 28.075A32.18 32.18 0 0 0 227.69 5.418C207.824 0 127.87 0 127.87 0S47.912.164 28.046 5.582A32.18 32.18 0 0 0 5.39 28.24c-6.009 35.298-8.34 89.084.165 122.97a32.18 32.18 0 0 0 22.656 22.657c19.866 5.418 99.822 5.418 99.822 5.418s79.955 0 99.82-5.418a32.18 32.18 0 0 0 22.657-22.657c6.338-35.348 8.291-89.1-.164-123.134"/>
                            <path fill="#fff" d="m102.421 128.06l66.328-38.418l-66.328-38.418z"/>
                        </svg>
                        <a href="/Homepage">YouTubePreAcc</a>
                    </h1>
                </button>
            </div>

            <!-- เมนูด้านขวา -->
            <div class="flex items-center space-x-4 md:space-x-6 lg:space-x-8">
                <button>
                    <a href="/product">
                        <h1 class="font-mitr font-regular text-sm md:text-lg lg:text-xl text-[#2C2C2C]">Products</h1>
                    </a>
                </button>

                <button>
                    <a href="/history">
                        <h1 class="font-mitr font-regular text-sm md:text-lg lg:text-xl text-[#2C2C2C]">History</h1>
                    </a>
                </button>

                <button>
                    <a href="/topup">
                        <h1 class="font-mitr font-regular text-sm md:text-lg lg:text-xl text-[#2C2C2C]">Top-up</h1>
                    </a>
                </button>

                <!-- โปรไฟล์ผู้ใช้ -->
                <button>
                    <a href="/profile" class="flex items-center">
                        <svg xmlns="http://www.w3.org/2000/svg" width="1em" height="1em"
                            viewBox="0 0 24 24"
                            class="h-[30px] w-[30px] md:h-[40px] md:w-[40px] lg:h-[50px] lg:w-[50px]">
                            <g fill="none" stroke="#ffe3de" stroke-width="1.5">
                                <path stroke-linecap="round"
                                    d="M7 18v-1a5 5 0 0 1 5-5v0a5 5 0 0 1 5 5v1"/>
                                <path stroke-linecap="round" stroke-linejoin="round"
                                    d="M12 12a3 3 0 1 0 0-6a3 3 0 0 0 0 6"/>
                                <circle cx="12" cy="12" r="10"/>
                            </g>
                        </svg>
                        <span class="font-mitr font-regular text-sm md:text-lg lg:text-xl text-[#2C2C2C] ml-2">username</span>
                    </a>
                </button>

                <!-- Coin -->
                <button class="flex items-center">
                    <a href="/topup" class="flex items-center">
                        <img src="../src/lib/images/Diamond.png" alt="coin"
                            class="h-[20px] w-[20px] md:h-[30px] md:w-[30px] lg:h-[40px] lg:w-[40px]">
                        <h1 class="font-mitr font-regular text-sm md:text-lg lg:text-xl text-[#2C2C2C] ml-1 md:ml-2">0</h1>
                    </a>
                </button>
            </div>
        </div>
        
        <!-- Center Content -->
        <div class="flex flex-col md:flex-row items-center justify-center py-10 md:py-20">

            <!-- Product 1 -->
            <div class="mb-10 md:mb-0">
                <button class="flex flex-col items-center justify-center bg-[#FFE3DE] rounded-3xl shadow-md p-6 w-[300px] h-[400px] md:w-[400px] md:h-[500px] mx-4">
                    <a href="/product-detail-1">

                        <h1 class="font-mitr font-regular text-3xl text-[#2C2C2C] mb-4">12 MONTH</h1> 
                
                        <svg xmlns="http://www.w3.org/2000/svg" width="1.43em" height="1em" viewBox="0 0 256 180" class="w-[200px] h-[200px] mb-4">
                            <path fill="#f00" d="M250.346 28.075A32.18 32.18 0 0 0 227.69 5.418C207.824 0 127.87 0 127.87 0S47.912.164 28.046 5.582A32.18 32.18 0 0 0 5.39 28.24c-6.009 35.298-8.34 89.084.165 122.97a32.18 32.18 0 0 0 22.656 22.657c19.866 5.418 99.822 5.418 99.822 5.418s79.955 0 99.82-5.418a32.18 32.18 0 0 0 22.657-22.657c6.338-35.348 8.291-89.1-.164-123.134"/>
                            <path fill="#fff" d="m102.421 128.06l66.328-38.418l-66.328-38.418z"/>
                        </svg>

                        <h1 class="font-mitr font-regular text-3xl text-[#2C2C2C]">IN STOCK 20</h1> 
                    </a>
                </button>
            </div>

            <div class="flex flex-col items-center w-full md:w-auto">
                <h2 class="font-mitr font-regular text-2xl text-[#2C2C2C] mb-4">YouTube Premium 365 Day</h2>

                <!-- Quantity Buttons -->
                <div class="flex items-center space-x-4 mb-4">
                    <p1 class="bg-[#FFFFFF] w-[80px] text-center text-black font-semibold border border-gray-300 rounded-lg py-2 px-20">1</p1>
                </div>

                <div class="flex flex-col md:flex-row justify-end items-center mt-5 md:mt-10 space-y-4 md:space-y-0">

                    <div class="flex items-center">
                        <p class="font-mitr font-regular text-2xl md:text-3xl text-[#2C2C2C] flex items-center">
                            <span id="total-price" class="mr-2">540</span>
                            <img src="../src/lib/images/Diamond.png" alt="coin" class="h-[30px] w-[30px] md:h-[40px] md:w-[40px]">
                        </p>
                    </div>
                    
                    <button class="font-mitr font-regular bg-white text-lg ml-5 md:text-2xl text-[#2C2C2C] px-4 py-2 border border-gray-300 rounded-3xl hover:bg-gray-100 drop-shadow-md">
                        Order now</button>
                </div>
                           
                
            </div>

        </div>

    </div>
</div>

