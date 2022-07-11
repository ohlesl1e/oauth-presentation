<script>
    export let title = "";
    export let image = "";
</script>

<div
    class="flex flex-wrap justify-evenly mx-auto max-w-22/24 pt-20 items-center text-center"
>
    <div class="w-22/24">
        {#if title}
            <h1
                class="font-sans font-black text-neutral-900 text-7xl mt-5 tracking-tight"
            >
                {title}
            </h1>
        {/if}
        <img class="h-5/6 w-auto mx-auto mt-8" src={image} alt="figure-1" />
    </div>
</div>
