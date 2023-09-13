<script setup>
import ProfileWa from "./components/ProfileWa.vue";
import IsiKiri from "./components/IsiKiri.vue";
</script>

<template>
  <div
    class="min-h-screen flex items-center justify-center bg-gray-300 rounded-lg"
  >
    <div class="bg-slate-200 shadow-lg rounded-lg h-full w-96">
      <ProfileWa />

      <IsiKiri />
      <div class="p-4 flex justify-end">
        <div class="w-[120px] px-2 rounded-xl bg-white gap-4 flex items-center">
          <span class="text-sm"> Oh ok:) </span>
          <span class="text-[10px]">13:39</span>
        </div>
      </div>
      <div class="p-4 flex justify-start">
        <div class="w-[165px] px-2 rounded-xl bg-white gap-4 flex items-center">
          <span class="text-sm"> Kita temenan aja ya... </span>
          <span class="text-[10px]">13:40</span>
        </div>
      </div>
      <div class="p-4 flex justify-end">
        <div class="w-[120px] px-2 rounded-xl bg-white gap-4 flex items-center">
          <span class="text-sm"> Gitu ya okei lah:) </span>
          <span class="text-[10px]">13:41</span>
        </div>
      </div>
      <div class="p-4 flex justify-start">
        <div class="w-[165px] px-2 rounded-xl bg-white gap-4 flex items-center">
          <span class="text-sm"> Lagian aku udah anggep kamu, </span>
          <span class="text-[10px]">13:42</span>
        </div>
      </div>
      <div class="p-4 flex justify-start">
        <div class="w-[165px] px-2 rounded-xl bg-white gap-4 flex items-center">
          <span class="text-sm"> Seperti kakaku sendiri. </span>
          <span class="text-[10px]">13:42</span>
        </div>
      </div>
      <div class="p-4 flex justify-end">
        <div class="w-[70px] px-2 rounded-xl bg-white gap-4 flex items-center">
          <span class="text-sm"> :) </span>
          <span class="text-[10px]">13:43</span>
        </div>
      </div>
      <div class="p-4 flex justify-start">
        <div class="w-[120px] px-2 rounded-xl bg-white gap-4 flex items-center">
          <span class="text-sm"> Maaf ya. </span>
          <span class="text-[10px]">13:45</span>
        </div>
      </div>

      <div class="flex items-center p-2">
        <input
          type="text"
          class="flex-grow rounded-full border border-gray-300 px-3 py-2 outline-none focus:ring focus:ring-blue-200"
          placeholder="Ketik pesan..."
        />
        <button
          class="bg-blue-500 text-white rounded-full px-2 py-2 ml-2 hover:bg-blue-600 focus:outline-none focus:ring focus:ring-blue-200 flex items-center justify-center"
        >
          <svg
            xmlns="http://www.w3.org/2000/svg"
            class="icon icon-tabler icon-tabler-send"
            width="22"
            height="22"
            viewBox="0 0 24 24"
            stroke-width="2"
            stroke="currentColor"
            fill="none"
            stroke-linecap="round"
            stroke-linejoin="round"
          >
            <path stroke="none" d="M0 0h24v24H0z" fill="none"></path>
            <path d="M10 14l11 -11"></path>
            <path
              d="M21 3l-6.5 18a.55 .55 0 0 1 -1 0l-3.5 -7l-7 -3.5a.55 .55 0 0 1 0 -1l18 -6.5"
            ></path>
          </svg>
        </button>
      </div>
    </div>
  </div>
</template>
