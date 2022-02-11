<template>
  <!--
  Tailwind UI components require Tailwind CSS v1.8 and the @tailwindcss/ui plugin.
  Read the documentation to get started: https://tailwindui.com/documentation
-->
  <!-- This example requires Tailwind CSS v1.4.0+ -->
  <div></div>
</template>

<script>
export default {
  data() {
    return {
      menuOpen: false,
    }
  },

  methods: {
    toggleMenu() {
      this.menuOpen = !this.menuOpen
    },
  },
}
</script>

<style scoped></style>
