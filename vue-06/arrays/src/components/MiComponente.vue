<template>
    <div>
        <div v-for="(color, index) in colores2" :key="index">
            Nombre {{color.nombre}} <br>
            Nombre2 {{color.nombreIngles}} <br>
            <p>---------------------</p>
        </div>

        {{colores}}
        {{colores[0]}}

        <ul>
            <li> {{colores[0]}} </li>
            <li> {{colores[1]}} </li>
            <li> {{colores[2]}} </li>
        </ul>
        <h1>foor loop</h1>
        <ul>
            <li v-for="(color, index) in colores" :key="index"> {{color}} </li>
        </ul>
    </div>
</template>

<script>
export default {
    name: 'MiComponente',
    data() {
        return {
            colores: [
                'rojo',
                'verde',
                'amarillo',
                'azul'
            ],
            colores2: [
                {nombre: 'rojo', nombreIngles: 'red'},
                {nombre: 'verde', nombreIngles: 'green'},
                {nombre: 'amarillo', nombreIngles: 'yellow'},
                {nombre: 'azul', nombreIngles: 'blue'}
            ]
        }
    },
}
</script>

<style>
</style>