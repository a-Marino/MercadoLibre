<template>
    <div class="container flex flex-row m-auto my-10 shadow-sm rounded-md">
        <div class="flex flex-row py-5 justify-around flex-1 overflow-hidden items-center">
            <!-- Tarjeta cretido -->
            <div class="flex flex-row space-x-3">
                <div>
                    <a href="#"><img src="https://http2.mlstatic.com/resources/frontend/homes-korriban/assets/images/payments/credit-card.svg" alt="tarjeta credito" decoding='async'></a>
                </div>
                <div class="flex flex-col">
                    <span class="text-lg">Tarjeta de Credito</span>
                    <a href='#' class="text-sm text-blue-500 hover:text-blue-600">Ver promociones bancarias</a>
                </div>
            </div>
            <!-- Tarjeta debito -->
            <div class="sm:flex flex-row hidden space-x-3">
                <div>
                    <a href="#"><img src="https://http2.mlstatic.com/resources/frontend/homes-korriban/assets/images/payments/debit-card.svg" alt="tarjeta debito" decoding='async'></a>
                </div>
                <div class="flex flex-col">
                    <span class="text-lg">Tarjeta de Debito</span>
                    <a href="#" class="text-sm text-blue-500 hover:text-blue-600">Ver mas</a>
                </div>
            </div>
            <!-- Cuotas -->
            <div class="md:flex flex-row hidden space-x-3">
                <div>
                    <a href="#"><img src="https://http2.mlstatic.com/resources/frontend/homes-korriban/assets/images/payments/mercado-creditsv2.svg" alt="cuotas" decoding='async'></a>
                </div>
                <div class="flex flex-col">
                    <span class="text-lg">Cuotas sin interes</span>
                    <a href="#" class="text-sm text-blue-500 hover:text-blue-600">Conoce Mercado Credito</a>
                </div>
            </div>
            <!-- Efectivo -->
            <div class="lg:flex flex-row hidden space-x-3">
                <div>
                    <a href="#"><img src="https://http2.mlstatic.com/resources/frontend/homes-korriban/assets/images/payments/payment-agreement.svg" alt="efectivo" decoding='async'></a>
                </div>
                <div class="flex flex-col">
                    <span class="text-lg">Efectivo</span>
                    <a href="#" class="text-blue-500 text-sm hover:text-blue-600">Ver mas</a>
                </div>
            </div>
        </div>
        <div class="py-5 px-6 w-auto border-l">
            <!-- btn Mas -->
            <div>
                <a href="#"><img src="https://http2.mlstatic.com/resources/frontend/homes-korriban/assets/images/payments/view-more.svg" alt="btn-mas"></a>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'MetodosPago',
}
</script>

<style scoped>
    .container {
        background-color: #fff;
    }
</style>