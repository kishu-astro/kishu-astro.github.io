<template>
  <div>
    <h3>ガイド紹介</h3>
    <div v-for="guide in guides">
      <!-- <image src={`/img/guides/${guide.fileName}`} /> -->
      <div>
        <h3>{{guide.name}}</h3>
        <p>{{guide.text}}</p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'price',
  data: () => ({
    guides: [
      {
        fileName: '001.JPG',
        name: '角田夏樹',
        text: 'やるき！元気！夏樹！',
      },
      {
        fileName: '001.JPG',
        name: '角田夏樹',
        text: 'やるき！元気！夏樹！',
      },
    ],
  }),
}
</script>

<style>
</style>
