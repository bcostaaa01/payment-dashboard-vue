<template>
  <div>
    <a href="https://www.ideal.nl/demo/en/?screens=dskweb&bank=bunq&type=dsk"><img src="https://is5-ssl.mzstatic.com/image/thumb/Purple124/v4/e9/67/69/e967697d-b166-0cbf-3d3b-e356509459cf/AppIcon-1x_U007emarketing-0-8-0-0-85-220.png/1200x630wa.png" alt="" style="width: 70px; height: 50px;"></a>
    <a href="https://www.sandbox.paypal.com/checkoutnow?sessionID=uid_ddd564cdd3_mtg6mty6nta&buttonSessionID=uid_bc36c4460d_mtg6mtc6mji&stickinessID=uid_02d478d488_mtg6mty6nte&inlinexo=false&smokeHash=&token=455563423W970953D&fundingSource=paypal&buyerCountry=US&locale.x=en_US&commit=true&enableFunding.0=paylater&clientID=ATssuyeiKXrkPP1TfoIcMXMoLBIO7ps9B2HN34eiAuhIuktEMTX0m_IVahzN3Ep3OXA8L33o0LxkkhiN&env=sandbox&sdkMeta=eyJ1cmwiOiJodHRwczovL3d3dy5wYXlwYWwuY29tL3Nkay9qcz9jbGllbnQtaWQ9QVRzc3V5ZWlLWHJrUFAxVGZvSWNNWE1vTEJJTzdwczlCMkhOMzRlaUF1aEl1a3RFTVRYMG1fSVZhaHpOM0VwM09YQThMMzNvMEx4a2toaU4mY3VycmVuY3k9VVNEJmRpc2FibGUtZnVuZGluZz1jYXJkJmVuYWJsZS1mdW5kaW5nPXBheWxhdGVyJmJ1eWVyLWNvdW50cnk9VVMmbG9jYWxlPWVuX1VTJmNvbXBvbmVudHM9bWVzc2FnZXMsYnV0dG9ucyIsImF0dHJzIjp7ImRhdGEtdWlkIjoidWlkX2JmdnJocGxlaWtlZGh2aGlzYXVnZWJqdWlvbWJqayJ9fQ&xcomponent=1&version=5.0.335"><img src="https://cdn.pixabay.com/photo/2018/05/08/21/29/paypal-3384015_1280.png" alt="" style="width: 70px; height: 50px;"></a>
    <a href="https://www.klarna.com/demo/us/en-US/one/checkout"><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/4/40/Klarna_Payment_Badge.svg/1280px-Klarna_Payment_Badge.svg.png" alt="" style="width: 80px; height: 50px;"></a>
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
