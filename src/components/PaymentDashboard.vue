<template>
    <div>
        <h1>Overzicht van de bestelling</h1>
        <OrderSummary />
        <PaymentCheckout />
    </div>
</template>

<script>
import OrderSummary from './OrderSummary.vue'
import PaymentCheckout from './PaymentCheckout.vue';

export default {
    name: 'PaymentDashboard',
    components: {
    OrderSummary,
    PaymentCheckout
}
}
</script>