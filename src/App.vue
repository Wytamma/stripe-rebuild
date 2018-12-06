<template>
  <div id="app" class="bg-grey-light font-sans leading-tight text-black">
    <div class="min-h-screen px-4 mx-auto max-w-1410px min-w-1024px bg-grey-light">
      <div class="flex pt-6">
        <div class="mr-4 xl:pr-12">
          <AccountSelect/>
          <Navbar/>
        </div>
        <div class="flex flex-col flex-grow">
            <div class="flex justify-between pb-4">
              <SearchBar/>
              <div class="flex items-baseline">
                <div class="mr-4">
                  <svg class="fill-current text-grey-darker inline-block h-4 w-4" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 576 512">
                    <path d="M542.22 32.05c-54.8 3.11-163.72 14.43-230.96 55.59-4.64 2.84-7.27 7.89-7.27 13.17v363.87c0 11.55 12.63 18.85 23.28 13.49 69.18-34.82 169.23-44.32 218.7-46.92 16.89-.89 30.02-14.43 30.02-30.66V62.75c.01-17.71-15.35-31.74-33.77-30.7zM264.73 87.64C197.5 46.48 88.58 35.17 33.78 32.05 15.36 31.01 0 45.04 0 62.75V400.6c0 16.24 13.13 29.78 30.02 30.66 49.49 2.6 149.59 12.11 218.77 46.95 10.62 5.35 23.21-1.94 23.21-13.46V100.63c0-5.29-2.62-10.14-7.27-12.99z"></path>
                  </svg>
                </div>
                <div class="mr-4">
                  <svg class="fill-current text-grey inline-block h-4 w-4" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 448 512">
                    <path d="M224 512c35.32 0 63.97-28.65 63.97-64H160.03c0 35.35 28.65 64 63.97 64zm215.39-149.71c-19.32-20.76-55.47-51.99-55.47-154.29 0-77.7-54.48-139.9-127.94-155.16V32c0-17.67-14.32-32-31.98-32s-31.98 14.33-31.98 32v20.84C118.56 68.1 64.08 130.3 64.08 208c0 102.3-36.15 133.53-55.47 154.29-6 6.45-8.66 14.16-8.61 21.71.11 16.4 12.98 32 32.1 32h383.8c19.12 0 32-15.6 32.1-32 .05-7.55-2.61-15.27-8.61-21.71z"></path>
                  </svg>
                </div>
                <div class="flex items-center bg-white rounded-full shadow"> 
                  <svg class="fill-current text-grey inline-block h-4 w-4 m-1.5" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16">
                    <path d="M8 11a5.698 5.698 0 0 0 3.9-1.537l1.76.66A3.608 3.608 0 0 1 16 13.5V15a1 1 0 0 1-1 1H1a1 1 0 0 1-1-1v-1.5c0-1.504.933-2.85 2.34-3.378l1.76-.66A5.698 5.698 0 0 0 8 11zM7.804 0h.392a3.5 3.5 0 0 1 3.488 3.79l-.164 1.971a3.532 3.532 0 0 1-7.04 0l-.164-1.97A3.5 3.5 0 0 1 7.804 0z" fill-rule="evenodd"></path>
                  </svg>
                </div>
              </div>
            </div>
            <div class="mb-4">
              <Chart/>
            </div>
            <div>
              <AnalyticsCard/>
            </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import Navbar from "./components/NavBar.vue";
import AccountSelect from "./components/AccountSelect.vue";
import SearchBar from "./components/SearchBar.vue";
import Chart from "./components/Chart.vue";
import AnalyticsCard from "./components/AnalyticsCard.vue";

export default {
  name: "app",
  components: {
    Navbar,
    AccountSelect,
    SearchBar,
    Chart,
    AnalyticsCard
  }
};
</script>

<style>
@tailwind preflight;
@tailwind components;
@tailwind utilities;

.col {
  background-attachment: #6073e0;
}
</style>
