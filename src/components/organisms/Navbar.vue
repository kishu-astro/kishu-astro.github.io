<template>
  <ul>
    <li v-for="item in navItems">
      {{ item.text }}
    </li>
  </ul>
</template>

<script>
export default {
  name: 'Navbar',
  data: () => ({
    navItems: [
      { key: 'top', text: 'TOP' },
      { key: 'price', text: '料金' },
      { key: 'guides', text: 'ガイド紹介' },
      { key: 'photos', text: '写真' },
      { key: 'wether', text: '天気' },
      { key: 'contact', text: 'お問い合わせ' },
    ],
  }),
}
</script>

<style>
</style>
