<template>

<VApp>
  <SideBar @selectOption="onSelectOption"/>
  <VMain>
    <ImageGallery :isWithColor="isWithColor"/>
  </VMain>
</VApp>

</template>

<script setup>
import ImageGallery from "./components/ImageGallery.vue";
import SideBar from "./components/SideBar"
import {ref} from "vue"

const isWithColor = ref(true)

const onSelectOption = (isColor) => {
  isWithColor.value = isColor
}
 </script>






