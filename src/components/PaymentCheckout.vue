<template>
  <div>
    <a href="https://www.ideal.nl/demo/en/?screens=dskweb&bank=bunq&type=dsk"><img src="https://is5-ssl.mzstatic.com/image/thumb/Purple124/v4/e9/67/69/e967697d-b166-0cbf-3d3b-e356509459cf/AppIcon-1x_U007emarketing-0-8-0-0-85-220.png/1200x630wa.png" alt="" style="width: 70px; height: 50px;"></a>
  </div>
</template>

<script>
export default {
  name: "PaymentCheckout",
  data() {
    return {
        paid: Boolean
    }
  },
  methods: {
    getImage(imageUrl) {
      require(imageUrl);
    },
  },
};
</script>
