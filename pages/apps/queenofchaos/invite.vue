<template>
  <div>
    <p class="text-white font-semibold text-center text-4xl animate-pulse">Redirecting you to Discord...</p>
  </div>
</template>

<script>
export default {
  head() {
    return {
      title: 'Redirecting...',
    }
  },
  mounted() {
    setTimeout(function () {
      window.location.href =
        'https://discord.com/api/oauth2/authorize?client_id=679741957047582725&permissions=274878228544&scope=bot%20applications.commands'
    }, 3000)
  },
}
</script>