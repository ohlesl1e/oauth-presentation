<script>
    export let title = "";
    export let image = "";
</script>

<div class="flex flex-col justify-center text-center h-screen">
    {#if title}
        <div>
            <h1
                class="font-sans font-black text-neutral-900 text-7xl tracking-tight"
            >
                {title}
            </h1>
        </div>
    {/if}
    <img class="w-auto max-h-4/6 mx-auto my-8" src={image} alt="figure-1" />
</div>
