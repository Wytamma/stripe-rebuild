<template>
    <div class="flex flex-col bg-white rounded shadow-md pt-4">
        <div class=" font-medium pb-4 px-6 ">
            Analytics
        </div>
        <div class="flex justify-between text-sm font-medium pb-4 px-6 ">
            <div class="flex">
                <div class="flex bg-white items-center text-grey-dark text-sm hover:text-black hover:shadow-md rounded shadow border border-grey-light py-1 px-2 mr-2">
                <div class=" mr-2">
                    1<span class="text-xs">W</span>
                </div>
                <svg class="fill-current inline-block h-3 w-3" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 320 512">
                    <path d="M143 256.3L7 120.3c-9.4-9.4-9.4-24.6 0-33.9l22.6-22.6c9.4-9.4 24.6-9.4 33.9 0l96.4 96.4 96.4-96.4c9.4-9.4 24.6-9.4 33.9 0L313 86.3c9.4 9.4 9.4 24.6 0 33.9l-136 136c-9.4 9.5-24.6 9.5-34 .1zm34 192l136-136c9.4-9.4 9.4-24.6 0-33.9l-22.6-22.6c-9.4-9.4-24.6-9.4-33.9 0L160 352.1l-96.4-96.4c-9.4-9.4-24.6-9.4-33.9 0L7 278.3c-9.4 9.4-9.4 24.6 0 33.9l136 136c9.4 9.5 24.6 9.5 34 .1z"></path>
                </svg>
            </div>
            <div class="flex bg-white items-center text-grey-dark text-sm rounded shadow border border-grey-light py-1 px-2 mr-2">
                <div>
                    Nov 29, 2018 &rarr; Dec 5, 2018
                </div>
            </div>
            <div class="flex bg-white items-center text-grey-dark text-sm hover:text-black hover:shadow-md rounded shadow border border-grey-light py-1 px-2">
                <div class=" mr-2">
                    Hourly
                </div>
                <svg class="fill-current inline-block h-3 w-3" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 320 512">
                    <path d="M143 256.3L7 120.3c-9.4-9.4-9.4-24.6 0-33.9l22.6-22.6c9.4-9.4 24.6-9.4 33.9 0l96.4 96.4 96.4-96.4c9.4-9.4 24.6-9.4 33.9 0L313 86.3c9.4 9.4 9.4 24.6 0 33.9l-136 136c-9.4 9.5-24.6 9.5-34 .1zm34 192l136-136c9.4-9.4 9.4-24.6 0-33.9l-22.6-22.6c-9.4-9.4-24.6-9.4-33.9 0L160 352.1l-96.4-96.4c-9.4-9.4-24.6-9.4-33.9 0L7 278.3c-9.4 9.4-9.4 24.6 0 33.9l136 136c9.4 9.5 24.6 9.5 34 .1z"></path>
                </svg>
            </div>
            </div>
            <div>
            <div class="flex bg-white items-center text-grey-dark text-sm hover:text-black hover:shadow-md rounded shadow border border-grey-light py-1 px-2">
                <svg class="mr-2 fill-current inline-block h-3 w-3" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16">
                <path d="M6.74 15.901l-.227-2.432a5.632 5.632 0 0 1-1.329-.55l-1.88 1.558a8.046 8.046 0 0 1-1.781-1.78l1.558-1.881a5.632 5.632 0 0 1-.55-1.329L.099 9.26a8.06 8.06 0 0 1 0-2.518l2.432-.228c.127-.47.313-.916.55-1.329l-1.558-1.88a8.046 8.046 0 0 1 1.78-1.781L5.185 3.08a5.632 5.632 0 0 1 1.329-.55L6.74.099a8.06 8.06 0 0 1 2.518 0l.228 2.432c.47.127.916.313 1.329.55l1.88-1.558a8.046 8.046 0 0 1 1.781 1.78L12.92 5.185c.237.413.423.859.55 1.329l2.432.228a8.06 8.06 0 0 1 0 2.518l-2.432.228c-.127.47-.313.916-.55 1.329l1.558 1.88a8.046 8.046 0 0 1-1.78 1.781l-1.881-1.558a5.632 5.632 0 0 1-1.329.55l-.228 2.432a8.06 8.06 0 0 1-2.518 0zM8 11a3 3 0 1 0 0-6 3 3 0 0 0 0 6z" fill-rule="evenodd"></path>
                </svg>
                <div >
                    Customize
                </div>
            </div>
            </div>
            </div>
            <div class="border-t border-grey-light bg-grey-lightest pb-4 ">
            <div class="flex items-center justify-between px-6 pt-4">
                <div class="flex flex-col">
                <div class="text-sm text-grey-darker pb-1">
                    Gross Volume
                </div>
                <div class="text-indigo text-lg font-semibold">
                    $0.00
                </div>
                </div>  
                <div class="">
                <div class="flex h-8 border-b-2 border-indigo">
                    <div class="w-10 border-r border-l border-grey-light">
                    </div>
                    <div v-for="n in 6" :key="n" class="w-10 border-r border-grey-light">
                    </div>
                </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
  name: 'AnalyticsCard'
}
</script>
