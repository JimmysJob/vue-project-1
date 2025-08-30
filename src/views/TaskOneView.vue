<!-- 需求功能描述 -->
<!-- 請嘗試將「商品列表」、「購物車」、「通知」拆分成 3 個元件 -->
<!-- 請使用 props 將商品資料傳遞至「商品列表」元件 -->
<!-- 「購物車」元件的刪除功能，請使用 emit 傳遞事件 -->
<!-- 使用 provide, inject 完成通知功能 -->
<script setup>
import ProductList from '../components/ProductList.vue';
import ProductCart from '../components/ProductCart.vue';
import ProductNotification from '../components/ProductNotification.vue';
</script>

<template>
  <div id="app" class="container py-5">
    <div class="row">
      <!-- 商品列表區 -->
      <ProductList />

      <!-- 購物車區 -->
      <ProductCart />
    </div>

    <!-- 通知元件 -->
    <ProductNotification />
  </div>
</template>
