<script>
    import { IconArrowRight } from "@tabler/icons-svelte";
    import { scrollToSection } from '$src/utils/scrollToSection.js';
    import ProdutoLanding from './ProdutoLanding.svelte';
    import product1 from '$img/img/photo2.webp';
    import product2 from '$img/looks/look3.webp';
    import product3 from '$img/looks/look4.webp';
    import product4 from '$img/looks/look1.webp';


</script>
<div id="produtos" class="w-full pb-4 flex flex-col gap-6 items-center">
    <h2 class="text-2xl tracking-widest">LOOKS</h2>
    <div class="w-full flex overflow-x-auto items-center justify-start gap-4 pl-[0%] py-4">
        <ProdutoLanding image={product1} title='Conjunto camisa rosa - calça sarja preta' price='__,__'/>
        <ProdutoLanding image={product2} title='Conjunto camisa branca praiana - calça sarja' price='__,__'/>
        <ProdutoLanding image={product3} title='Conjunto camisa branca - calça sarja' price='__,__'/>
        <ProdutoLanding image={product4} title='Conjunto camisa vinho - calça preta' price='__,__'/>
    </div>
    <a href="/" class="flex items-center" on:click={(event) => { event.preventDefault(); scrollToSection('produtos'); }}>Explore mais <IconArrowRight/></a>
</div>