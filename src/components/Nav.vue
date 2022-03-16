<template>
    <nav class="flex flex-col">
        <!-- Nav primario -->
        <div class="flex flex-row justify-around items-center py-2">
            <a href="/" class="nav-logo"></a>
            <!-- Searchbar -->
            <input type="text" name="search" id="search" class="search-bar" placeholder="Buscar productos, marcas y mas..." autocomplete="off">
            <!-- lvl 6 meli -->
            <img src="https://http2.mlstatic.com/D_NQ_877425-MLA47306668299_082021-OO.webp" alt="Nivel 6" class="lvl6 cursor-pointer">
        </div>
        <!-- Nav secundario -->
        <div class="flex flex-row justify-around items-center mt-5 pb-2">
            <!-- Envio a direccion de usuario -->
            <div class="flex flex-row space-x-1">
                <img src="@/assets/svg/marcador.svg" alt="ubicacion" class="w-6">
                <div class="flex flex-col send-user text-center -space-y-1">
                    <p class="font-light text-sm">Enviar a Usuario</p>
                    <p class="text-base font-normal">Direccion</p>
                </div>
            </div>
            <!-- Categorias -->
            <ul class="flex flex-row categories space-x-3 text-sm">
                <a href="#"><li>Categorias ⌵</li></a>
                <a href="#"><li>Ofertas</li></a>
                <a href="#"><li>Historial</li></a>
                <a href="#"><li>Supermercado</li></a>
                <a href="#"><li>Moda</li></a>
                <a href="#"><li>Vender</li></a>
                <a href="#"><li>Ayuda</li></a>
            </ul>
            <!-- Opciones Perfil -->
            <div class="flex flex-row text-sm space-x-5">
                <a href='#' class="flex items-center space-x-1">
                    <img src="@/assets/svg/usuario.svg" alt="Usuario" class="w-4">
                    <span>Usuario ⌵</span>
                </a>
                <a href="#">Mis compras</a>
                <a href="#">Favoritos ⌵</a>
                <a href="#"><img src="@/assets/svg/campana.svg" alt="Campana" class="w-5"></a>
                <a href="#"><img src="@/assets/svg/carrito-de-compras.svg" alt="Carrito" class="w-5"></a>
            </div>
        </div>
    </nav>
</template>

<script>
export default {
    name: 'Nav'
}
</script>

<style scoped>
    nav {
        background-color: var(--amarillo-meli);
        color: #333;
    }

    .nav-logo {
        background-image: url('https://http2.mlstatic.com/frontend-assets/ui-navigation/5.18.9/mercadolibre/logo__large_plus.png');
        height: 34px;
        width: 134px;
        color: transparent;
    }

    .lvl6 {
        width: 340px;
        height: 39px;
    }

    .search-bar {
        width: 35rem;
        height: 2.4rem;
        outline: none;
        padding: 1rem;
        color: #333;
        border-radius: 2px;
        box-shadow: rgba(0, 0, 0, 0.24) 0px 3px 8px;
    }

    .send-user p:first-child {
        color: #333;
    }

    .categories {
        color: rgba(51,51,51,.6);
    }

    a:hover {
        color: black;
    }

</style>