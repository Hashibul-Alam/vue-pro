<template>
  <header className="bg-gray-900 text-white p-4 font-Primary ">
  <div className="flex justify-between items-center">
    <div>
    <h1 className=" flex text-[#00a63e] font-semibold ">
       <NoteSeacrh/>Wallet Tracker
    </h1>
    <p className="text-gray-400 text-sm">Tag, track and analyze multiple wallets</p>
   </div>
    <div className="flex space-x-4 text-sm items-center">
        <button className="px-3 py-1 rounded flex items-center">
            <SettingsIcon/>
        </button>
      <button className="bg-gray-800 hover:opacity-75  text-gray-400 flex items-center ps-3 py-1 rounded cursor-pointer ">
         <PowerBuy/>  BUY <span className=" bg-gray-900 px-3 mr-1 py-1 rounded ml-3">40$</span>
      </button>
      <button className="bg-gray-800 px-3 py-2 rounded cursor-pointer ">Add Wallet +</button>
      <button className="bg-gray-800 px-3 py-2 rounded cursor-pointer ">Import/Export Wallet</button>
    </div>
  </div>
  </header>
</template>

<script setup lang="ts">
import SettingsIcon from "@/components/icons/SettingsIcon.vue";
import PowerBuy from "@/components/icons/PowerBuy.vue";
import NoteSeacrh from "@/components/icons/NoteSeacrh.vue";
</script>
