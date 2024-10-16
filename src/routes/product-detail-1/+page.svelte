<div class="mx-auto w-full text-white text-center h-full">

    <!-- bg -->
    <div class="relative isolate bg-gradient-to-t from-[#B5BAE4] to-[#FFFFFF] h-screen">

        <!-- หัวด้านบน -->
        <div class="bg-[#B5BAE4] h-[70px] md:h-[100px] w-full flex items-center justify-between px-4">
            <div class="absolute left-5 md:left-10">
                <button>
                    <h1 class="text-[#2C2C2C] font-semibold text-lg md:text-2xl bg-[#FFE3DE] flex items-center justify-center rounded-3xl px-2 py-1 md:px-4 md:py-2">
                        <svg xmlns="http://www.w3.org/2000/svg" width="1.43em" height="1em" viewBox="0 0 256 180" class="mr-2">
                            <path fill="#f00" d="M250.346 28.075A32.18 32.18 0 0 0 227.69 5.418C207.824 0 127.87 0 127.87 0S47.912.164 28.046 5.582A32.18 32.18 0 0 0 5.39 28.24c-6.009 35.298-8.34 89.084.165 122.97a32.18 32.18 0 0 0 22.656 22.657c19.866 5.418 99.822 5.418 99.822 5.418s79.955 0 99.82-5.418a32.18 32.18 0 0 0 22.657-22.657c6.338-35.348 8.291-89.1-.164-123.134"/>
                            <path fill="#fff" d="m102.421 128.06l66.328-38.418l-66.328-38.418z"/>
                        </svg>
                        <a href="/Homepage">YouTubePreAcc</a>
                    </h1>
                </button>
            </div>

            <div class="absolute right-5 md:right-10 flex items-center space-x-4 md:space-x-10 lg:space-x-20">
                <button>
                    <a href="/product">
                        <h1 class="text-sm md:text-lg lg:text-xl font-semibold text-[#2C2C2C]">Products</h1>
                    </a>
                </button>

                <button>
                    <a href="/history">
                        <h1 class="text-sm md:text-lg lg:text-xl font-semibold text-[#2C2C2C]">History</h1>
                    </a>
                </button>

                <button>
                    <a href="/topup">
                        <h1 class="text-sm md:text-lg lg:text-xl font-semibold text-[#2C2C2C]">Top-up</h1>
                    </a>
                </button>

                <button>
                    <a href="/profile">
                        <svg xmlns="http://www.w3.org/2000/svg" width="1em" height="1em" viewBox="0 0 24 24" class="h-[40px] w-[40px] md:h-[60px] md:w-[60px] lg:h-[80px] lg:w-[80px]">
                            <path fill="#ffe3de" d="M12 2A10 10 0 0 0 2 12a10 10 0 0 0 10 10a10 10 0 0 0 10-10A10 10 0 0 0 12 2"/>
                        </svg>
                    </a>
                </button>

                <button class="flex items-center">
                    <a href="/topup" class="flex items-center">
                        <img src="../src/lib/images/Diamond.png" alt="coin" class="h-[20px] w-[20px] md:h-[30px] md:w-[30px] lg:h-[40px] lg:w-[40px]">
                        <h1 class="text-sm md:text-lg lg:text-xl font-semibold text-[#2C2C2C] ml-1 md:ml-2">0</h1> 
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

                        <h1 class="text-3xl font-semibold text-[#2C2C2C] mb-4">1 MONTH</h1> 
                
                        <svg xmlns="http://www.w3.org/2000/svg" width="1.43em" height="1em" viewBox="0 0 256 180" class="w-[200px] h-[200px] mb-4">
                            <path fill="#f00" d="M250.346 28.075A32.18 32.18 0 0 0 227.69 5.418C207.824 0 127.87 0 127.87 0S47.912.164 28.046 5.582A32.18 32.18 0 0 0 5.39 28.24c-6.009 35.298-8.34 89.084.165 122.97a32.18 32.18 0 0 0 22.656 22.657c19.866 5.418 99.822 5.418 99.822 5.418s79.955 0 99.82-5.418a32.18 32.18 0 0 0 22.657-22.657c6.338-35.348 8.291-89.1-.164-123.134"/>
                            <path fill="#fff" d="m102.421 128.06l66.328-38.418l-66.328-38.418z"/>
                        </svg>

                        <h1 class="text-3xl font-semibold text-[#2C2C2C]">IN STOCK 20</h1> 
                    </a>
                </button>
            </div>

            <div class="flex flex-col items-center w-full md:w-auto">
                <h2 class="text-2xl text-[#2C2C2C] font-semibold mb-4">YouTube Premium 30 Day</h2>

                <!-- Quantity Buttons -->
                <div class="flex items-center space-x-4 mb-4">
                    <button class="bg-[#FFFFFF] text-black font-bold px-4 py-2 rounded-lg" on:click={decreaseQuantity}>-</button>
                    <input id="quantity" type="text" value="1" class="bg-[#FFFFFF] w-[80px] text-center text-black font-semibold border border-gray-300 rounded-lg py-2 focus:outline-none" readonly />
                    <button class="bg-[#FFFFFF] text-black font-bold px-4 py-2 rounded-lg" on:click={increaseQuantity}>+</button>
                </div>

                <div class="flex flex-col md:flex-row justify-end items-center mt-5 md:mt-10 space-y-4 md:space-y-0">

                    <div class="flex items-center">
                        <p class="text-2xl md:text-3xl font-semibold text-[#2C2C2C] flex items-center">
                            <span id="total-price" class="mr-2">45</span>
                            <img src="../src/lib/images/Diamond.png" alt="coin" class="h-[30px] w-[30px] md:h-[40px] md:w-[40px]">
                        </p>
                    </div>
                    
                    <button>
                        <a href="/login" class="bg-white text-lg ml-5 md:text-2xl text-[#2C2C2C] px-4 py-2 border border-gray-300 rounded-3xl hover:bg-gray-100 drop-shadow-md">Order now</a>
                    </button>
                </div>
                           
                
            </div>

        </div>

    </div>
</div>

<script>
    const pricePerItem = 45;

    function increaseQuantity() {
        let quantityInput = document.getElementById('quantity');
        if (quantityInput instanceof HTMLInputElement) {
            let quantity = parseInt(quantityInput.value);
            quantityInput.value = (quantity + 1).toString();
        }
        updateprice();
    }

    function decreaseQuantity() {
        let quantityInput = document.getElementById('quantity');
        if (quantityInput instanceof HTMLInputElement) {
            let quantity = parseInt(quantityInput.value);
            if (quantity > 1) {
                quantityInput.value = (quantity - 1).toString();
            }
        }
        updateprice();
    }

    function updateprice() {
        let quantityInput = document.getElementById('quantity');
        let totalPriceElement = document.getElementById('total-price');

        if (quantityInput instanceof HTMLInputElement && totalPriceElement) {
            let quantity = parseInt(quantityInput.value);
            let totalPrice = quantity * pricePerItem;
            totalPriceElement.innerText = totalPrice.toString();
        }
    }
</script>
