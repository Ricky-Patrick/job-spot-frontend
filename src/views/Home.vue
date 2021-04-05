<template>
<div>
    <Navbar/>
    <Footer/>
</div>
</template>
<style>
.foter{
	background-color: green
}
</style>
<script>
// @ is an alias to /src
import Navbar from '@/components/Navbar.vue'
import Footer from '@/components/Footer.vue'
export default {
name: 'navbar',
components: {
    Navbar, Footer
},

}
</script>
