<template>
  <body class="bg-primary font-mostserrat overflow-hidden">
    <div class="bg-primary h-screen max-w-screen-xl flex m-auto">
      <SideLeft />
      <SideRight />
    </div>
  </body>
</template>

<script>
export default {}
</script>

<style>
::-webkit-scrollbar {
  width: 8px;
}

/* Track */
::-webkit-scrollbar-track {
  background: #ffffff20; 
  opacity: 0.5;
}

/* Handle */
::-webkit-scrollbar-thumb {
  background: #1e1e287f;
  border-radius: 5px;
}

/* Handle on hover */
::-webkit-scrollbar-thumb:hover {
  background: rgba(255, 255, 255, 0.3);
}
</style>
