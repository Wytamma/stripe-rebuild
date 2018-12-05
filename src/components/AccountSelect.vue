<template>
<div class="flex items-center pb-6">
    <div class="flex items-center bg-white rounded-full shadow mr-2">
        <svg class="fill-current text-grey inline-block h-4 w-4 m-1.5" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16">
            <path d="M3 7.5V12h10V7.5c.718 0 1.398-.168 2-.468V15a1 1 0 0 1-1 1H2a1 1 0 0 1-1-1V7.032c.602.3 1.282.468 2 .468zM0 3L1.703.445A1 1 0 0 1 2.535 0h10.93a1 1 0 0 1 .832.445L16 3a3 3 0 0 1-5.5 1.659C9.963 5.467 9.043 6 8 6s-1.963-.533-2.5-1.341A3 3 0 0 1 0 3z" fill-rule="evenodd"></path>
        </svg>
    </div>
    <div class="mr-2">
        <div class="text-base font-medium">
        Unnamed account
        </div>
        <div class="text-indigo text-sm font-medium hover:text-black">
        <div class="flex  items-center">
            <div class="m-1">
            <svg class="fill-current inline-block h-3 w-3" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16">
                <path d="M15.194 4.28L11.72.805l.087-.087a2.456 2.456 0 1 1 3.473 3.473zm-1.415 1.414l-9.264 9.264L0 16l1.042-4.515 9.264-9.264z" fill-rule="evenodd"></path>
            </svg>
            </div>
            <div>
            Add a name
            </div>
        </div>
        </div>
    </div>
    <button class="py-2 focus:outline-none">
        <svg class="fill-current text-grey-dark inline-block h-3 w-3" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16">
            <path d="M13.591 5.293a1 1 0 0 1 1.416 1.416l-6.3 6.3a1 1 0 0 1-1.414 0l-6.3-6.3A1 1 0 0 1 2.41 5.293L8 10.884z" fill-rule="evenodd"></path>
        </svg>
    </button>
</div>
</template>

<script>
export default {
  name: 'AccountSelect'
}
</script>
