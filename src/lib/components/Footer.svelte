<script>
    import { IconBrandInstagramFilled, IconBrandTwitterFilled, IconBrandYoutubeFilled, IconDiamond, IconRings } from "@tabler/icons-svelte";
</script>

<footer class="w-full px-4 pt-8 pb-2 gap-6 flex flex-col bg-gray-300">
    <div class="w-full px-8 flex justify-around">
        <IconBrandTwitterFilled size="32" color="#334155" />
        <a href="https://www.instagram.com/usecorpovivo?utm_source=ig_web_button_share_sheet&igsh=ZDNlZDc0MzIxNw==">
            <IconBrandInstagramFilled size="32" color="#334155" />
        </a>
        <IconBrandYoutubeFilled size="32" color="#334155" />
    </div>
    <div class="w-2/5 self-center flex items-center justify-center gap-2">
        <div class="w-20 border-b border-b-slate-500 border-solid"></div>
        <IconDiamond />
        <div class="w-20 border-b border-b-slate-500 border-solid"></div>
    </div>
    <div class="flex flex-col text-center">
        <a class="text-slate-700 text-lg" href="http://api.whatsapp.com/send?1=pt_BR&phone=5581996200989">
           Consultor: (81) 99620-0989</a
        >
        <span class="text-slate-700 text-lg">
            08:00 - 17:00 de Segunda à Sexta
        </span>
    </div>
    <div class="w-2/5 self-center flex items-center justify-center gap-2">
        <div class="w-20 border-b border-b-slate-500 border-solid"></div>
        <IconRings />
        <div class="w-20 border-b border-b-slate-500 border-solid"></div>
    </div>
    <nav class="flex justify-around text-lg px-4">
        <a href="/">Sobre</a>
        <a href="/">Contato</a>
        <a href="/">Blog</a>
    </nav>
    <div class="flex flex-col items-center text-slate-500 text-sm">
        <span>Copyright© usecorpovivo</span>
        <span>Todos os Direitos Reservados.</span>
    </div>
</footer>