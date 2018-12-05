<template>
    <div class="flex flex-col bg-indigo rounded shadow-md px-6 pb-3">
        <div class="flex justify-center">
            <div class="bg-orange rounded-b text-white text-2xs font-bold px-2">
            TEST DATA
            </div>
        </div>
        <div class="flex justify-between mb-2">
            <div class="flex">
            <div class="text-white text-lg mr-4">
                Today
            </div>
            <div class="text-white text-lg font-semibold">
                $0.00
            </div>
            </div>
            <div class="flex bg-white items-center text-grey-darker text-sm hover:text-black hover:shadow-md rounded shadow py-1 px-2">
                <div class=" mr-12">
                    Gross volume
                </div>
                <svg class="fill-current inline-block h-3 w-3" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 320 512">
                    <path d="M143 256.3L7 120.3c-9.4-9.4-9.4-24.6 0-33.9l22.6-22.6c9.4-9.4 24.6-9.4 33.9 0l96.4 96.4 96.4-96.4c9.4-9.4 24.6-9.4 33.9 0L313 86.3c9.4 9.4 9.4 24.6 0 33.9l-136 136c-9.4 9.5-24.6 9.5-34 .1zm34 192l136-136c9.4-9.4 9.4-24.6 0-33.9l-22.6-22.6c-9.4-9.4-24.6-9.4-33.9 0L160 352.1l-96.4-96.4c-9.4-9.4-24.6-9.4-33.9 0L7 278.3c-9.4 9.4-9.4 24.6 0 33.9l136 136c9.4 9.5 24.6 9.5 34 .1z"></path>
                </svg>
            </div>
        </div>
        <div class="flex justify-between mb-4">
            <div class="flex text-white items-center text-sm">
            <div class=" mr-10">
                Yesterday
            </div>
            <div class="">
                <svg class="fill-current inline-block h-2 w-2 mr-4" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16">
                    <path d="M13.591 5.293a1 1 0 0 1 1.416 1.416l-6.3 6.3a1 1 0 0 1-1.414 0l-6.3-6.3A1 1 0 0 1 2.41 5.293L8 10.884z" fill-rule="evenodd"></path>
                </svg>
            </div>
            <div class="text-grey-light">
                $0.00
            </div>
            </div>
            <div>
                <svg class="fill-current text-white inline-block h-3 w-3" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512">
                <path fill="currentColor" d="M496 384H64V80c0-8.84-7.16-16-16-16H16C7.16 64 0 71.16 0 80v336c0 17.67 14.33 32 32 32h464c8.84 0 16-7.16 16-16v-32c0-8.84-7.16-16-16-16zM464 96H345.94c-21.38 0-32.09 25.85-16.97 40.97l32.4 32.4L288 242.75l-73.37-73.37c-12.5-12.5-32.76-12.5-45.25 0l-68.69 68.69c-6.25 6.25-6.25 16.38 0 22.63l22.62 22.62c6.25 6.25 16.38 6.25 22.63 0L192 237.25l73.37 73.37c12.5 12.5 32.76 12.5 45.25 0l96-96 32.4 32.4c15.12 15.12 40.97 4.41 40.97-16.97V112c.01-8.84-7.15-16-15.99-16z"></path>
                </svg>
            </div>
        </div>
        <div class="flex justify-between h-20">
            <div v-for="n in 25" :key="n" class="border-r border-indigo-light">
            </div>
            
        </div>
        <div class="flex items-center -mt-3">
            <div class="w-3/4 border-white border-t-2 mt-1"></div>
            <div >
            <svg class="stroke-current fill-current text-white inline-block h-2 w-2" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 512 512">
                <path d="M256 8C119 8 8 119 8 256s111 248 248 248 248-111 248-248S393 8 256 8zm0 448c-110.5 0-200-89.5-200-200S145.5 56 256 56s200 89.5 200 200-89.5 200-200 200z"></path>
            </svg>
            </div>
            <div class="w-1/4 border-white border-t mt-1"></div>
        </div>
        <div class="flex text-white text-xs">
            <div class="flex justify-between w-3/4">
            <div>
                12:00 AM
            </div>
            <div class="flex -mr-10">
                <div class="mr-1">
                <svg class="stroke-current fill-current text-white inline-block h-2 w-2" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 320 512">
                    <path fill="currentColor" d="M296 160H180.6l42.6-129.8C227.2 15 215.7 0 200 0H56C44 0 33.8 8.9 32.2 20.8l-32 240C-1.7 275.2 9.5 288 24 288h118.7L96.6 482.5c-3.6 15.2 8 29.5 23.3 29.5 8.4 0 16.4-4.4 20.8-12l176-304c9.3-15.9-2.2-36-20.7-36z"></path>
                </svg>
                </div>
                <div>
                Now, 5:34 PM
                </div>
            </div>
            </div>
            <div class="flex justify-end w-1/4 ">
            <div>
                11:59 PM
            </div>
            </div>
        </div>
    </div>
</template>
<script>
export default {
  name: 'Chart',
}
</script>
