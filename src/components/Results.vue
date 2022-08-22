<script setup>
import Grid from "@/components/Grid.vue";
</script>

<template>
  <div class="flex items-center justify-center w-full">
    <div class="bg-white max-w-md lg:max-w-5xl w-full p-12  h-auto rounded-2xl shadow-lg">
      <Grid>
        <div>
          <h2 class="text-[14px] font-bold text-gray-400">IP ADDRESS</h2>
        </div>
        <div>
          <h2 class="text-[14px] font-bold text-gray-400">LOCATION</h2>
        </div>
        <div>
          <h2 class="text-[14px] font-bold text-gray-400">TIME ZONE</h2>
        </div>
        <div>
          <h2 class="text-[14px] font-bold text-gray-400">ISP</h2>
        </div>
      </Grid>
    </div>
  </div>
</template>
