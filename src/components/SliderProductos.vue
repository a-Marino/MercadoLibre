<template>
    <div class="flex flex-col overflow-hidden">
        <!-- Titulo -->
        <div class="flex flex-row items-end space-x-4">
            <h1 class="text-2xl text-gray-600 font-light">{{title}}</h1>
            <a href="#" class="text-md text-blue-500 hover:text-blue-600">Ver historial</a>
        </div>
        <!-- Productos -->
        <div class="flex flex-row min-w-full carousell space-x-5">
            <!-- Contenedor producto -->
            <div class="product-container rounded-md shadow-sm hover:shadow-xl mt-5 flex flex-col">
                <!-- Imagen Producto -->
                <div class="product-img overflow-hidden border-b">
                    <img src="https://http2.mlstatic.com/D_Q_NP_787221-MLA48007684849_102021-AB.webp" alt="product-img">
                </div>
                <!-- Data Producto -->
                <div class="product-data flex flex-col ml-4 mt-3">
                    <!-- Precio / Descuento -->
                    <div class="flex flex-col">
                        <span class="text-sm text-gray-400 precio-descuento line-through mt-2 overflow-hidden">$ 90.999</span>
                        <div class="flex flex-row items-end space-x-3">
                            <span class="text-2xl font-semibold">$ 77.999</span>
                            <span class="verde text-sm">14% OFF</span>
                        </div>
                    </div>
                    <!-- Cuotas / Envio -->
                    <div class="flex flex-col mt-1">
                        <span class="text-sm overflow-hidden">12x $ 6.500 sin interes</span>
                        <div class="flex flex-row space-x-1 mt-1">
                            <span class="text-sm verde overflow-hidden font-medium">Envio gratis</span>
                        </div>
                    </div>
                    <!-- Descripcion -->
                    <div class="overflow-hidden mt-2 mb-3 descripcion">
                        <p class="text-sm text-gray-400">
                            Smart TV Samsung Series 7 UN50AU7000GCZB LED 4K
                        </p>
                    </div>
                </div>
            </div>
            <!-- Contenedor producto -->
            <div class="product-container rounded-md shadow-sm hover:shadow-xl mt-5 flex flex-col">
                <!-- Imagen Producto -->
                <div class="product-img overflow-hidden border-b">
                    <img src="https://http2.mlstatic.com/D_Q_NP_763952-MLA48732838004_012022-AB.webp" alt="product-img">
                </div>
                <!-- Data Producto -->
                <div class="product-data flex flex-col ml-4 mt-3">
                    <!-- Precio / Descuento -->
                    <div class="flex flex-col">
                        <span class="text-sm text-gray-400 precio-descuento line-through mt-2 overflow-hidden">$ 117.800</span>
                        <div class="flex flex-row items-end space-x-3">
                            <span class="text-2xl font-semibold">$ 69.199</span>
                            <span class="verde text-sm">41% OFF</span>
                        </div>
                    </div>
                    <!-- Cuotas / Envio -->
                    <div class="flex flex-col mt-1">
                        <span class="text-sm overflow-hidden">12x $ 5.767 sin interes</span>
                        <div class="flex flex-row space-x-1 mt-1">
                            <span class="text-sm verde overflow-hidden font-medium">Envio gratis</span>
                        </div>
                    </div>
                    <!-- Descripcion -->
                    <div class="overflow-hidden mt-2 mb-3 descripcion">
                        <p class="text-sm text-gray-400">
                            Aire acondicionado BGH split frio/calor 3000 frigorias blanco
                        </p>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'SliderProductos',
    props: {
        title: {
            type: String,
            required: true,
        },
    }
}
</script>

<style scoped>
    .carousell {
        height: 450px;
    }

    .product-container .descripcion {
        display: none;
    }

    .product-container .precio-descuento {
        display: none;
    }

    .product-container:hover {
        transition: .25s ease-in-out;
        height: auto;
        min-height: 330px;
        max-height: 392px;
    }

    .product-container:hover .precio-descuento {
        display: block;
    }

    .product-container:hover .descripcion {
        display: block;
    }

    .product-container {
        background-color: #fff;
        height: 330px;
        width: 224px;
        overflow: hidden;
        cursor: pointer;
    }
</style>