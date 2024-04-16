<template>
 <fwb-navbar>
  <template #logo> Swiff </template>
  <template #default="{ isShowMenu }">
   <fwb-navbar-collapse :is-show-menu="isShowMenu">
    <fwb-navbar-link is-active link="#"> Home </fwb-navbar-link>
    <fwb-navbar-link link="#"> Products </fwb-navbar-link>
    <fwb-navbar-link link="#"> Pricing </fwb-navbar-link>
    <fwb-navbar-link link="#"> Contact </fwb-navbar-link>
   </fwb-navbar-collapse>
  </template>
 </fwb-navbar>
</template>

<script setup>
import { FwbNavbar, FwbNavbarCollapse, FwbNavbarLink } from "flowbite-vue";
</script>
