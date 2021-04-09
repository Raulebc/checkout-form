<template>
    <div class="flex h-screen bg-gray-100 justify-center items-center">
        <div class="flex flex-row border w-2/3 h-2/5 shadow-2xl rounded-2xl bg-white">
            <div class="flex flex-col w-1/3 h-full items-center">
                <div class="flex w-full h-4/5 border-b border-gray-200 justify-center">
                    <div class="flex flex-col w-2/3 pt-4 justify-center items-start gap-4">
                        <div class="flex flex-col justify-items-start">
                            <p class="uppercase text-xs font-semibold">order Number</p>
                            <p class="text-blue-800 font-semibold">789457934</p>
                        </div>
                        <div class="flex flex-col justify-items-start">
                            <p class="uppercase text-xs font-semibold">Amount</p>
                            <p class="text-blue-800 font-semibold">$ 376,90</p>
                        </div>
                    </div>
                </div>

                <div class="flex items-center font-bold text-blue-800 h-1/6 w-full justify-start pl-3 text-xs gap-3">
                    <span>
                        <svg xmlns="http://www.w3.org/2000/svg" class="w-3 stroke-current stroke-2 text-indigo-800" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                            <path strokeLinecap="round" strokeLinejoin="round" strokeWidth={2} d="M15 19l-7-7 7-7" />
                        </svg>
                    </span>
                    <p class="uppercase">previous step</p>
                </div>
            </div>
            <div class="flex flex-col w-2/3 shadow-2xl bg-gradient-to-b from-blue-900 to-blue-700 rounded-r-2xl text-white">
                <div class="flex flex-row items-center  border-white border-b border-opacity-30 px-4 py-4 uppercase">
                    <p class="font-semibold text-white text-opacity-30 text-xs px-4 py-2">Master card</p> 
                    <span>
                        <svg xmlns="http://www.w3.org/2000/svg" class="w-3 text-white opacity-30 stroke-current stroke-2" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                            <path strokeLinecap="round" strokeLinejoin="round" strokeWidth={2} d="M9 5l7 7-7 7" />
                        </svg>
                    </span>
                </div>
                <div class="flex justify-ceniter h-4/5 px-4 py-4">
                    <div class="flex flex-col w-11/12 justify-center gap-5">
                        <input type="text" placeholder="Nombre que aparece en la tarjeta" class="text-xs pl-3 outline-none focus:border-gray-200 h-8 bg-transparent focus:placeholder-opacity-30 border placeholder-gray-200 placeholder-opacity-50 pla border-gray-200 rounded"/>
                        <input type="text" class="text-xs pl-3 outline-none focus:border-gray-200 h-8 bg-transparent focus:placeholder-opacity-30 border placeholder-gray-200 placeholder-opacity-50 pla border-gray-300 rounded" placeholder="XXX XXX XXX"/>
                        <div class="flex flex-row justify-between">
                            <input type="text" placeholder="XX/XX" class="h-8 w-40 text-xs pl-3 outline-none focus:border-gray-200 bg-transparent focus:placeholder-opacity-30 border placeholder-gray-200 placeholder-opacity-50 pla border-gray-300 rounded">
                            <input type="text" placeholder="XXX" class="h-8 w-20 text-xs pl-3 outline-none focus:border-gray-200 bg-transparent focus:placeholder-opacity-30 border placeholder-gray-200 placeholder-opacity-50 pla border-gray-300 rounded">
                        </div>
                    </div>
                </div>
                <div class="flex items-center border-t border-white border-opacity-30 pl-4 py-4">
                    <div class="flex flex-row justify-between w-11/12">
                        <p class="font-bold pl-3 text-white text-opacity-50 text-xs uppercase">proceed to checkout</p> 
                        <svg xmlns="http://www.w3.org/2000/svg" class="w-3 text-white opacity-60 stroke-current stroke-2" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                            <path strokeLinecap="round" strokeLinejoin="round" strokeWidth={2} d="M9 5l7 7-7 7" />
                        </svg>
                    </div>
                </div>
            </div>
        </div>
    </div>



    <!-- <div>
        <div class="leading-loose flex justify-center">
            <form class="max-w-xl m-4 p-10 bg-white rounded shadow-xl">
                <p class="text-gray-800 font-medium">Customer information</p>
                <div class="">
                <label class="block text-sm text-gray-00" for="cus_name">Name</label>
                <input class="w-full px-5 py-1 text-gray-700 bg-gray-200 rounded" id="cus_name" name="cus_name" type="text" required="" placeholder="Your Name" aria-label="Name">
                </div>
                <div class="mt-2">
                <label class="block text-sm text-gray-600" for="cus_email">Email</label>
                <input class="w-full px-5  py-4 text-gray-700 bg-gray-200 rounded" id="cus_email" name="cus_email" type="text" required="" placeholder="Your Email" aria-label="Email">
                </div>
                <div class="mt-2">
                <label class=" block text-sm text-gray-600" for="cus_email">Address</label>
                <input class="w-full px-2 py-2 text-gray-700 bg-gray-200 rounded" id="cus_email" name="cus_email" type="text" required="" placeholder="Street" aria-label="Email">
                </div>
                <div class="mt-2">
                <label class="hidden text-sm block text-gray-600" for="cus_email">City</label>
                <input class="w-full px-2 py-2 text-gray-700 bg-gray-200 rounded" id="cus_email" name="cus_email" type="text" required="" placeholder="City" aria-label="Email">
                </div>
                <div class="inline-block mt-2 w-1/2 pr-1">
                <label class="hidden block text-sm text-gray-600" for="cus_email">Country</label>
                <input class="w-full px-2 py-2 text-gray-700 bg-gray-200 rounded" id="cus_email" name="cus_email" type="text" required="" placeholder="Country" aria-label="Email">
                </div>
                <div class="inline-block mt-2 -mx-1 pl-1 w-1/2">
                <label class="hidden block text-sm text-gray-600" for="cus_email">Zip</label>
                <input class="w-full px-2 py-2 text-gray-700 bg-gray-200 rounded" id="cus_email"  name="cus_email" type="text" required="" placeholder="Zip" aria-label="Email">
                </div>
                <p class="mt-4 text-gray-800 font-medium">Payment information</p>
                <div class="">
                <label class="block text-sm text-gray-600" for="cus_name">Card</label>
                <input class="w-full px-2 py-2 text-gray-700 bg-gray-200 rounded" id="cus_name" name="cus_name" type="text" required="" placeholder="Card Number MM/YY CVC" aria-label="Name">
                </div>
                <div class="mt-4">
                <button class="px-4 py-1 text-white font-light tracking-wider bg-gray-900 rounded" type="submit">$3.00</button>
                </div>
            </form>
        </div>
    </div> -->
</template>

<script>
    var sharedSource = {};
</script>

<style></style>
