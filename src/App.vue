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

      <IsiKiri type="kiri">Kamu Terlalu baik</IsiKiri>
      <IsiKiri type="kanan">Kita temenan aja</IsiKiri>
      <IsiKiri type="kiri">Okay</IsiKiri>
      <IsiKiri type="kanan">Maaf Yah</IsiKiri>
      <IsiKiri type="kiri">Gapapa</IsiKiri>
      <IsiKiri type="kanan">Sip</IsiKiri>
      <IsiKiri type="kanan">See you</IsiKiri>

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
