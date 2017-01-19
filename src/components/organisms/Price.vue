<template>
  <div>
    <h3>料金</h3>
    <div>
      <table>
        <thead>
          <tr>
            <th v-for="col in cols">
              {{col}}
            </th>
          </tr>
        </thead>
        <tbody>
          <tr v-for="row in rows">
            <td>{{row.kind}}</td>
            <td>{{row.price}}</td>
          </tr>
        </tbody>
      </table>
    </div>
  </div>
</template>

<script>
export default {
  name: 'price',
  data: () => ({
    cols: ['種別', '料金'],
    rows: [
      { kind: '大人', price: '2,900円' },
      { kind: '中・高生', price: '1,000円' },
      { kind: '小学生', price: '500円' },
    ],
  }),
}
</script>

<style>
</style>
