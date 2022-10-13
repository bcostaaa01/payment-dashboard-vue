<template>
  <div id="order-summary">
    <div id="order-list">
      <li v-for="(item, index) in items" :key="index">
        <img :src="item.imageUrl" alt="" style="height: 75px; width: 75px" />
        {{ item.title }} - {{ item.price }}
      </li>
    </div>
    <div id="order-total">
        <h3>Totaal te betalen</h3>
        <h5>4.48€</h5>
    </div>
  </div>
</template>

<script>
export default {
  name: "OrderSummary",
  data() {
    return {
      items: [
        {
          title: "Kaas",
          imageUrl:
            "https://static.ah.nl/dam/product/AHI_43545239363538303439?revLabel=2&rendition=800x800_JPG_Q90&fileType=binary",
          price: '1.99€',
        },
        {
          title: "Aardbei",
          imageUrl:
            "https://www.ah-boodschappen.nl/storage/product-image/poster/2765.jpg",
          price: '2.49€',
        },
      ]
    };
  }
};
</script>
