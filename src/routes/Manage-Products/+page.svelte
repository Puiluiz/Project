<div class="mx-auto w-full text-white text-center h-full">
    <!-- bg -->
    <div class="relative isolate bg-gradient-to-t from-[#B5BAE4] to-[#FFFFFF] h-full">

        <!-- หัวด้านบน -->
       <div class="bg-[#B5BAE4] h-[60px] md:h-[80px] lg:h-[100px] w-full flex items-center justify-between px-4">
        <!-- Logo ด้านซ้าย -->
        <div class="flex-shrink-0">
            <button>
                <h1 class="font-mitr font-regular text-[#2C2C2C] text-sm md:text-lg lg:text-2xl bg-[#FFE3DE] flex items-center justify-center rounded-3xl px-2 md:px-3 lg:px-4 py-1 md:py-2">
                    <svg xmlns="http://www.w3.org/2000/svg" width="1.43em" height="1em" viewBox="0 0 256 180" class="mr-2">
                        <path fill="#f00" d="M250.346 28.075A32.18 32.18 0 0 0 227.69 5.418C207.824 0 127.87 0 127.87 0S47.912.164 28.046 5.582A32.18 32.18 0 0 0 5.39 28.24c-6.009 35.298-8.34 89.084.165 122.97a32.18 32.18 0 0 0 22.656 22.657c19.866 5.418 99.822 5.418 99.822 5.418s79.955 0 99.82-5.418a32.18 32.18 0 0 0 22.657-22.657c6.338-35.348 8.291-89.1-.164-123.134"/>
                        <path fill="#fff" d="m102.421 128.06l66.328-38.418l-66.328-38.418z"/>
                    </svg>
                    <a href="/Homepage-Admin">YouTubePreAcc-Admin</a>
                </h1>
            </button>
        </div>

        <!-- เมนูด้านขวา -->
        <div class="flex items-center space-x-2 sm:space-x-4 lg:space-x-8">
            <!-- Button Manage -->
            <button>
                <a href="/Homepage" class="font-mitr font-regular bg-white text-[#2C2C2C] text-xs sm:text-sm md:text-lg px-2 md:px-4 py-1 border border-gray-300 rounded-3xl hover:bg-gray-100 drop-shadow-md">BackUser</a>
            </button>

            <button>
                <a href="/Manage-Products" class="underline font-mitr font-regular text-xs sm:text-sm md:text-lg text-[#2C2C2C]">Manage-Products</a>
            </button>

            <button>
                <a href="/Manage-User" class="font-mitr font-regular text-xs sm:text-sm md:text-lg text-[#2C2C2C]">Manage-User</a>
            </button>

            <button>
                <a href="/Log-Product" class="font-mitr font-regular text-xs sm:text-sm md:text-lg text-[#2C2C2C]">Log</a>
            </button>

            <!-- โปรไฟล์ผู้ใช้ -->
            <button>
                <a href="/profile" class="flex items-center">
                    <svg xmlns="http://www.w3.org/2000/svg" width="1em" height="1em" viewBox="0 0 24 24" class="h-[20px] md:h-[30px] lg:h-[40px] w-[20px] md:w-[30px] lg:w-[40px]">
                        <path fill="#ffe3de" fill-rule="evenodd" d="M7.5 6a4.5 4.5 0 1 1 9 0a4.5 4.5 0 0 1-9 0M3.751 20.105a8.25 8.25 0 0 1 16.498 0a.75.75 0 0 1-.437.695A18.7 18.7 0 0 1 12 22.5c-2.786 0-5.433-.608-7.812-1.7a.75.75 0 0 1-.437-.695" clip-rule="evenodd"/>
                    </svg>
                    <span class="font-mitr font-regular text-xs md:text-lg text-[#2C2C2C] ml-2">username</span>
                </a>
            </button>
        </div>
    </div>
        
        <!-- Center Message & Button -->
         
        <div class="py-[50px] absolute right-5 md:right-10 flex space-x-4 md:space-x-10 lg:space-x-20">
            <button class="font-mitr font-regular bg-[#98BC79] text-[#FFFFFF] px-4 py-1 rounded mr-2">Add Product</button>
        </div>

        <!-- Table Section -->
        <div class="flex flex-col items-center h-screen text-center py-[100px]">
            
            <!-- ช่องค้นหา -->
            <div class="mb-4">
                <input type="text" placeholder="Search.." class="font-mitr font-regular text-[#2C2C2C] p-2 border border-gray-300 rounded-l-3xl" />
                <button class="font-mitr font-regular bg-[#98BC79] text-white px-4 py-2 rounded-r-3xl">Search</button>
            </div>

            <!-- 1 Month Products -->
            <div class="mt-8 w-full max-w-5xl px-4">
                <h1 class="font-mitr font-regular text-2xl md:text-4xl mb-4 text-[#2C2C2C]">Products for 1 Month</h1>
                <div class="overflow-x-auto">
                    <table class="table-auto border-collapse border border-slate-500 w-full ">
                        <thead>
                            <tr>
                                <th class="font-mitr font-regular border border-slate-600 text-[#2C2C2C] bg-[#FFE3DE] p-3">ID</th>
                                <th class="font-mitr font-regular border border-slate-600 text-[#2C2C2C] bg-[#FFE3DE] p-3">Email</th>
                                <th class="font-mitr font-regular border border-slate-600 text-[#2C2C2C] bg-[#FFE3DE] p-3">Password</th>
                                <th class="font-mitr font-regular border border-slate-600 text-[#2C2C2C] bg-[#FFE3DE] p-3">Price</th>
                                <th class="font-mitr font-regular border border-slate-600 text-[#2C2C2C] bg-[#FFE3DE] p-3">Expire</th>
                                <th class="font-mitr font-regular border border-slate-600 text-[#2C2C2C] bg-[#FFE3DE] p-3">Manage</th>
                            </tr>
                        </thead>
                        <tbody>
                            <tr>
                                <td class="font-mitr font-regular border border-slate-600 text-[#2C2C2C] bg-[#FFFFFF] p-3">001</td>
                                <td class="font-mitr font-regular border border-slate-600 text-[#2C2C2C] bg-[#FFFFFF] p-3">Test@gmail.com</td>
                                <td class="font-mitr font-regular border border-slate-600 text-[#2C2C2C] bg-[#FFFFFF] p-3">1234</td>
                                <td class="font-mitr font-regular border border-slate-600 text-[#2C2C2C] bg-[#FFFFFF] p-3">45</td>
                                <td class="font-mitr font-regular border border-slate-600 text-[#2C2C2C] bg-[#FFFFFF] p-3">45</td>
                                <td class="font-mitr font-regular border border-slate-600 text-[#2C2C2C] bg-[#FFFFFF] p-3">
                                    <button class="font-mitr font-regular bg-[#6CAAF0] text-white px-4 py-1 rounded mr-2">Manage</button>
                                    <button class="font-mitr font-regular bg-[#BD4C52] text-white px-4 py-1 rounded">Delete</button>
                                </td>
                            </tr>
                        </tbody>
                    </table>
                </div>
                <div class="flex justify-between mt-4 text-gray-600">
                    <span>Previous</span>
                    <span>Next</span>
                </div>
            </div>

            <!-- 12 Months Products -->
            <div class="mt-8 w-full max-w-5xl px-4">
                <h1 class="font-mitr font-regular text-2xl md:text-4xl mb-4 text-[#2C2C2C]">Products for 12 Months</h1>
                <div class="overflow-x-auto">
                    <table class="table-auto border-collapse border border-slate-500 w-full">
                        <thead>
                            <tr>
                                <th class="font-mitr font-regular border border-slate-600 text-[#2C2C2C] bg-[#FFE3DE] p-3">ID</th>
                                <th class="font-mitr font-regular border border-slate-600 text-[#2C2C2C] bg-[#FFE3DE] p-3">Email</th>
                                <th class="font-mitr font-regular border border-slate-600 text-[#2C2C2C] bg-[#FFE3DE] p-3">Password</th>
                                <th class="font-mitr font-regular border border-slate-600 text-[#2C2C2C] bg-[#FFE3DE] p-3">Price</th>
                                <th class="font-mitr font-regular border border-slate-600 text-[#2C2C2C] bg-[#FFE3DE] p-3">Expire</th>
                                <th class="font-mitr font-regular border border-slate-600 text-[#2C2C2C] bg-[#FFE3DE] p-3">Manage</th>
                            </tr>
                        </thead>
                        <tbody>
                            <tr>
                                <td class="font-mitr font-regular border border-slate-600 text-[#2C2C2C] bg-[#FFFFFF] p-3">001</td>
                                <td class="font-mitr font-regular border border-slate-600 text-[#2C2C2C] bg-[#FFFFFF] p-3">Test@gmail.com</td>
                                <td class="font-mitr font-regular border border-slate-600 text-[#2C2C2C] bg-[#FFFFFF] p-3">1234</td>
                                <td class="font-mitr font-regular border border-slate-600 text-[#2C2C2C] bg-[#FFFFFF] p-3">45</td>
                                <td class="font-mitr font-regular border border-slate-600 text-[#2C2C2C] bg-[#FFFFFF] p-3">45</td>
                                <td class="font-mitr font-regular border border-slate-600 text-[#2C2C2C] bg-[#FFFFFF] p-3">
                                    <button class="font-mitr font-regular bg-[#6CAAF0] text-white px-4 py-1 rounded mr-2">Manage</button>
                                    <button class="font-mitr font-regular bg-[#BD4C52] text-white px-4 py-1 rounded">Delete</button>
                                </td>
                            </tr>
                        </tbody>
                    </table>
                </div>
                <div class="flex justify-between mt-4 text-gray-600">
                    <span>Previous</span>
                    <span>Next</span>
                </div>
            </div>
        </div>
    </div>
</div>
