<script>

    import banner from '$img/looks/look2.webp';
    import { scrollToSection } from '$src/utils/scrollToSection.js';
    export let objectPosition = '15% 70%';
   
</script>
<div id="banner" class="w-full flex flex-col items-center">
    <a
        href="#servicos"
        class="absolute top-15 left-1/2 transform -translate-x-1/2 w-[90%] px-6 py-2 rounded-full text-white text-sm text-center bg-gray-700 bg-clip-padding backdrop-filter backdrop-blur-xl bg-opacity-0" on:click={(event) => { event.preventDefault(); scrollToSection('servicos'); }}
        >VISTA-SE PARA IMPRESSIONAR</a
    >

    <img src={banner} alt="Banner" class="banner-img" style="object-position: {objectPosition};" />

    <a
        href="#servicos"
        class="relative bottom-16 px-6 py-2 rounded-full text-white text-mg bg-gray-700 bg-clip-padding backdrop-filter backdrop-blur-xl bg-opacity-0" on:click={(event) => { event.preventDefault(); scrollToSection('servicos'); }}
        >VEM PARA A CORPO VIVO</a
    >
</div>
<style scoped>
.banner-img {
    width: 100%;
    height: 41rem;
    object-fit: cover;
    object-position: center 72%;
}
</style>