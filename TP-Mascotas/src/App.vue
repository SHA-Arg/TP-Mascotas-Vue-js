<script setup>
const name = "Vue dinamico";
const styleColor = "color: red";
</script>

<template>
	<h1>Hola {{ name }}</h1>
	<h2 :style="styleColor">Soy Rojo</h2>
</template>

<style>
h1 {
	color: blue;
}
</style>
