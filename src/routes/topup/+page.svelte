<div class="mx-auto w-full text-white text-center h-full">

    <!-- bg -->
    <div class="relative isolate bg-gradient-to-t from-[#B5BAE4] to-[#FFFFFF] h-full">
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
                        <h1 class="underline font-mitr font-regular text-sm md:text-lg lg:text-xl text-[#2C2C2C]">Top-up</h1>
                    </a>
                </button>

                <!-- โปรไฟล์ผู้ใช้ -->
                <button>
                    <a href="/profile" class="flex items-center">
                        <svg xmlns="http://www.w3.org/2000/svg" width="1em" height="1em" viewBox="0 0 24 24" class="h-[30px] w-[30px] md:h-[40px] md:w-[40px] lg:h-[50px] lg:w-[50px]">
                            <path fill="#ffe3de" fill-rule="evenodd" d="M7.5 6a4.5 4.5 0 1 1 9 0a4.5 4.5 0 0 1-9 0M3.751 20.105a8.25 8.25 0 0 1 16.498 0a.75.75 0 0 1-.437.695A18.7 18.7 0 0 1 12 22.5c-2.786 0-5.433-.608-7.812-1.7a.75.75 0 0 1-.437-.695" clip-rule="evenodd"/>
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
        
        <!-- ข้อความตรงกลาง -->
        <div class="min-h-screen flex flex-col items-center text-white py-[40px]">
            
            <!-- Header section -->
            <div class="bg-[#B5BAE4] p-5 w-full max-w-md rounded-t-lg flex items-center">
                <img src="../src/lib/images/twg.png" class="h-16 w-16 rounded-lg" alt="TrueWallet Logo">
                <div class="ml-4">
                    <h1 class="font-mitr font-regular text-xl text-[#2C2C2C]">TrueWallet Voucher</h1>
                    <p class="font-mitr font-regular text-sm text-[#2C2C2C]">ทรูวอลเล็ท ซองอั่งเปา</p>
                </div>
            </div>
        
            <!-- Body section -->
            <div class="bg-[#B5BAE4]/70 p-5 w-full max-w-md rounded-b-lg">
                <div class="mb-5 flex flex-col items-center">
                    <!-- Step 1 -->
                    <div>
                        <img src="../src/lib/images/tw-gift2.png" alt="Step 1" class="border rounded-lg mb-2">
                    </div>
                </div>
        
                <!-- Input and Button -->
                <div class="mb-5">
                    <label for="voucher-link" class="font-mitr font-regular block mb-2 text-left text-[#2C2C2C]">TrueWallet Voucher</label>
                    <input id="voucher-link" type="text" class="w-full p-2 rounded-md bg-[#FFFFFF] text-[#2C2C2C] border border-gray-500" placeholder="https://gift.truemoney.com/campaign/?v=">
                </div>
        
                <button class="font-mitr font-regular w-full py-3 text-[#2C2C2C] bg-[#FFE3DE] rounded-lg font-bold">Top up</button>
            </div>
        </div>

    </div>
</div>
