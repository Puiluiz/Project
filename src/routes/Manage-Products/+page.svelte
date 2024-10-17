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
                        <a href="/Homepage-Admin">YouTubePreAcc-Admin</a>
                    </h1>
                </button>
            </div>

            <!-- เมนูด้านขวา -->
            <div class="flex items-center space-x-4 md:space-x-6 lg:space-x-8">
                <!-- Button Manage -->
                <button>
                    <a href="/Homepage" class="font-mitr font-regular bg-white text-[#2C2C2C] text-xs sm:text-sm md:text-lg lg:text-xl px-3 py-1 sm:px-4 sm:py-2 border border-gray-300 rounded-3xl hover:bg-gray-100 drop-shadow-md">Back-User</a>
                </button>

                <button>
                    <a href="/Manage-Products">
                        <h1 class="underline font-mitr font-regular text-sm md:text-lg lg:text-xl text-[#2C2C2C]">Manage-Products</h1>
                    </a>
                </button>

                <button>
                    <a href="/Manage-User">
                        <h1 class="font-mitr font-regular text-sm md:text-lg lg:text-xl text-[#2C2C2C]">Manage-User</h1>
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
            </div>
        </div>
        
        <!-- ข้อความตรงกลาง -->

        <div class="py-[50px] absolute right-5 md:right-10 flex space-x-4 md:space-x-10 lg:space-x-20">
            <button class="font-mitr font-regular bg-[#98BC79] text-[#FFFFFF] px-4 py-1 rounded mr-2">Add Product</button>
        </div>

        <div class="flex flex-col items-center h-screen text-center py-[100px]">
            <table class="table-auto border-collapse border border-slate-500 w-full max-w-full overflow-x-auto">
                <thead>
                    <tr>
                        <th class="font-mitr font-regular border border-slate-600 text-[#2C2C2C] bg-[#FFE3DE] p-3">NUMBER</th>
                        <th class="font-mitr font-regular border border-slate-600 text-[#2C2C2C] bg-[#FFE3DE] p-3">ID PRODUCT</th>
                        <th class="font-mitr font-regular border border-slate-600 text-[#2C2C2C] bg-[#FFE3DE] p-3">LIST</th>
                        <th class="font-mitr font-regular border border-slate-600 text-[#2C2C2C] bg-[#FFE3DE] p-3">AMOUNT</th>
                        <th class="font-mitr font-regular border border-slate-600 text-[#2C2C2C] bg-[#FFE3DE] p-3">PRICE</th>
                        <th class="font-mitr font-regular border border-slate-600 text-[#2C2C2C] bg-[#FFE3DE] p-3">Manage</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td class="font-mitr font-regular border border-slate-600 text-[#2C2C2C] bg-[#FFFFFF] p-3">001</td>
                        <td class="font-mitr font-regular border border-slate-600 text-[#2C2C2C] bg-[#FFFFFF] p-3">P001</td>
                        <td class="font-mitr font-regular border border-slate-600 text-[#2C2C2C] bg-[#FFFFFF] p-3">1 MONTH</td>
                        <td class="font-mitr font-regular border border-slate-600 text-[#2C2C2C] bg-[#FFFFFF] p-3">1</td>
                        <td class="font-mitr font-regular border border-slate-600 text-[#2C2C2C] bg-[#FFFFFF] p-3">45</td>
                        <td class="font-mitr font-regular border border-slate-600 text-[#2C2C2C] bg-[#FFFFFF] p-3">
                            <button class="font-mitr font-regular bg-[#6CAAF0] text-white px-4 py-1 rounded mr-2">Manage</button>
                            <button class="font-mitr font-regular bg-[#BD4C52] text-white px-4 py-1 rounded">Delete</button>
                        </td>
                    </tr>
                    <tr>
                        <td class="font-mitr font-regular border border-slate-600 text-[#2C2C2C] bg-[#FFFFFF] p-3">002</td>
                        <td class="font-mitr font-regular border border-slate-600 text-[#2C2C2C] bg-[#FFFFFF] p-3">P002</td>
                        <td class="font-mitr font-regular border border-slate-600 text-[#2C2C2C] bg-[#FFFFFF] p-3">12 MONTH</td>
                        <td class="font-mitr font-regular border border-slate-600 text-[#2C2C2C] bg-[#FFFFFF] p-3">1</td>
                        <td class="font-mitr font-regular border border-slate-600 text-[#2C2C2C] bg-[#FFFFFF] p-3">540</td>
                        <td class="font-mitr font-regular border border-slate-600 text-[#2C2C2C] bg-[#FFFFFF] p-3">
                            <button class="font-mitr font-regular bg-[#6CAAF0] text-white px-4 py-1 rounded mr-2">Manage</button>
                            <button class="font-mitr font-regular bg-[#BD4C52] text-white px-4 py-1 rounded">Delete</button>
                        </td>
                    </tr>
                    <tr>
                        <td class="font-mitr font-regular border border-slate-600 text-[#2C2C2C] bg-[#FFFFFF] p-3">003</td>
                        <td class="font-mitr font-regular border border-slate-600 text-[#2C2C2C] bg-[#FFFFFF] p-3">C000</td>
                        <td class="font-mitr font-regular border border-slate-600 text-[#2C2C2C] bg-[#FFFFFF] p-3">TOP-UP</td>
                        <td class="font-mitr font-regular border border-slate-600 text-[#2C2C2C] bg-[#FFFFFF] p-3">20</td>
                        <td class="font-mitr font-regular border border-slate-600 text-[#2C2C2C] bg-[#FFFFFF] p-3">20</td>
                        <td class="font-mitr font-regular border border-slate-600 text-[#2C2C2C] bg-[#FFFFFF] p-3">
                            <button class="font-mitr font-regular bg-[#6CAAF0] text-white px-4 py-1 rounded mr-2">Manage</button>
                            <button class="font-mitr font-regular bg-[#BD4C52] text-white px-4 py-1 rounded">Delete</button>
                        </td>
                    </tr>
                </tbody>
            </table>
        </div>
        
    </div>
</div>
