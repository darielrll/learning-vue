<template>
    <div>
        <p>{{mostrarBoton}}</p>
        <hr>
        <div v-if="mostrarBoton == 'clave'">
            Usuario autenticado <button> Boton Secreto </button>
        </div>
        <div v-else-if="mostrarBoton">
            El valor fue encontrado pero incorrecto
        </div>
        <div v-else>
            Valor no encontrado, ingrese un valor
        </div>
        ------ show -------
        <!-- El show solo oculta con estilo el componente, lo mantiene en el DOM -->
        <div v-show="mostrarBoton == 'clave'">
            Usuario autenticado <button> Boton Secreto </button>
        </div>
    </div>
</template>

<script>
export default {
    name: 'MiComponente',
    data() {
        return {
            mostrarBoton: "clave"
        };
    }
}
</script>

<style lang="">
    
</style>