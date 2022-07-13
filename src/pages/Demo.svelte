<script>
    export let src
</script>

<div flex flex-col items-center justify-center h-screen>
    <div class="">
        <h1
            class="h-2/12 font-sans font-black text-neutral-900 text-7xl tracking-tight"
        >
            Demo
        </h1>
    </div>
    <iframe
        {src}
        class="w-3/4 h-10/12"
        title="demo"
        referrerpolicy="unsafe-url"
        sandbox="allow-top-navigation allow-scripts allow-forms allow-popups allow-same-origin"
    />
</div>
