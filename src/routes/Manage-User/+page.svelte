<div class="mx-auto w-full text-white text-center h-full">
    <!-- bg -->
    <div class="relative isolate bg-gradient-to-t from-[#B5BAE4] to-[#FFFFFF] h-full">

        <!-- หัวด้านบน -->
        <div class="bg-[#B5BAE4] h-[70px] sm:h-[90px] md:h-[100px] w-screen flex items-center justify-center">
            <div class="absolute left-5 sm:left-8 md:left-10">
                <button>
                    <h1 class="text-[#2C2C2C] font-semibold text-base sm:text-lg md:text-2xl bg-[#FFE3DE] flex items-center justify-center rounded-3xl px-2 py-1 sm:px-3 sm:py-2 md:px-4 md:py-2">
                        <svg xmlns="http://www.w3.org/2000/svg" width="1.43em" height="1em" viewBox="0 0 256 180" class="mr-2">
                            <path fill="#f00" d="M250.346 28.075A32.18 32.18 0 0 0 227.69 5.418C207.824 0 127.87 0 127.87 0S47.912.164 28.046 5.582A32.18 32.18 0 0 0 5.39 28.24c-6.009 35.298-8.34 89.084.165 122.97a32.18 32.18 0 0 0 22.656 22.657c19.866 5.418 99.822 5.418 99.822 5.418s79.955 0 99.82-5.418a32.18 32.18 0 0 0 22.657-22.657c6.338-35.348 8.291-89.1-.164-123.134"/>
                            <path fill="#fff" d="m102.421 128.06l66.328-38.418l-66.328-38.418z"/>
                        </svg>
                        <a href="/Homepage-Admin">YouTubePreAcc-Admin</a>
                    </h1>
                </button>
            </div>

            <div class="absolute right-5 sm:right-8 md:right-10 flex items-center space-x-3 sm:space-x-4 md:space-x-5 lg:space-x-10">

                <button>
                    <a href="/Backoffice-Homepage" class="bg-white text-[#2C2C2C] text-xs sm:text-sm md:text-lg lg:text-xl font-semibold px-3 py-1 sm:px-4 sm:py-2 border border-gray-300 rounded-3xl hover:bg-gray-100 drop-shadow-md">Back to User</a>
                </button>

                <!-- Button History -->
                <button>
                    <a href="/Manage-Products">
                        <h1 class="text-xs sm:text-sm md:text-lg lg:text-xl font-semibold text-[#2C2C2C]">Manage-Products</h1>
                    </a>
                </button>

                <!-- Button Top-up -->
                <button>
                    <a href="/Manage-User">
                        <h1 class="underline text-xs sm:text-sm md:text-lg lg:text-xl font-semibold text-[#2C2C2C]">Manage-User</h1>
                    </a>
                </button>

                <!-- Profile Icon -->
                <button>
                    <a href="/profile">
                        <svg xmlns="http://www.w3.org/2000/svg" width="1em" height="1em" viewBox="0 0 24 24" class="h-[30px] sm:h-[40px] md:h-[50px] lg:h-[80px] w-[30px] sm:w-[40px] md:w-[50px] lg:w-[80px]">
                            <path fill="#ffe3de" d="M12 2A10 10 0 0 0 2 12a10 10 0 0 0 10 10a10 10 0 0 0 10-10A10 10 0 0 0 12 2"/>
                        </svg>
                    </a>
                </button>

            </div>
        </div>
        
        <!-- ข้อความตรงกลาง -->

        <div class="py-[50px] absolute right-5 md:right-10 flex space-x-4 md:space-x-10 lg:space-x-20">
            <button class="bg-[#98BC79] text-[#FFFFFF] px-4 py-1 rounded mr-2">Add Product</button>
        </div>

        <div class="flex flex-col items-center h-screen text-center py-[100px]">
            <table class="table-auto border-collapse border border-slate-500 w-full max-w-full overflow-x-auto">
                <thead>
                    <tr>
                        <th class="border border-slate-600 text-[#2C2C2C] bg-[#FFE3DE] p-3">NUMBER</th>
                        <th class="border border-slate-600 text-[#2C2C2C] bg-[#FFE3DE] p-3">Username</th>
                        <th class="border border-slate-600 text-[#2C2C2C] bg-[#FFE3DE] p-3">Email</th>
                        <th class="border border-slate-600 text-[#2C2C2C] bg-[#FFE3DE] p-3">Role</th>
                        <th class="border border-slate-600 text-[#2C2C2C] bg-[#FFE3DE] p-3">Manage</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td class="border border-slate-600 text-[#2C2C2C] bg-[#FFFFFF] p-3">001</td>
                        <td class="border border-slate-600 text-[#2C2C2C] bg-[#FFFFFF] p-3">Book</td>
                        <td class="border border-slate-600 text-[#2C2C2C] bg-[#FFFFFF] p-3">Book</td>
                        <td class="border border-slate-600 text-[#2C2C2C] bg-[#FFFFFF] p-3">Admin</td>
                        <td class="border border-slate-600 text-[#2C2C2C] bg-[#FFFFFF] p-3">
                            <button class="bg-[#6CAAF0] text-white px-4 py-1 rounded mr-2">Manage</button>
                            <button class="bg-[#BD4C52] text-white px-4 py-1 rounded">Delete</button>
                            <button class="bg-[#98BC79] text-[#FFFFFF] px-4 py-1 rounded mr-2">Change Password</button>
                        </td>
                    </tr>
                    <tr>
                        <td class="border border-slate-600 text-[#2C2C2C] bg-[#FFFFFF] p-3">002</td>
                        <td class="border border-slate-600 text-[#2C2C2C] bg-[#FFFFFF] p-3">Pui</td>
                        <td class="border border-slate-600 text-[#2C2C2C] bg-[#FFFFFF] p-3">Pui</td>
                        <td class="border border-slate-600 text-[#2C2C2C] bg-[#FFFFFF] p-3">User</td>
                        <td class="border border-slate-600 text-[#2C2C2C] bg-[#FFFFFF] p-3">
                            <button class="bg-[#6CAAF0] text-white px-4 py-1 rounded mr-2">Manage</button>
                            <button class="bg-[#BD4C52] text-white px-4 py-1 rounded">Delete</button>
                            <button class="bg-[#98BC79] text-[#FFFFFF] px-4 py-1 rounded mr-2">Change Password</button>
                        </td>
                    </tr>
                </tbody>
            </table>
        </div>
        
    </div>
</div>
