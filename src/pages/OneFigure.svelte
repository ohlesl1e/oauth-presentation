<script>
    export let title = "";
    export let image = "";
</script>

<div
    class="flex flex-col flex-wrap justify-evenly mx-auto max-w-22/24 pt-20 items-center text-center"
>
    <div class="w-22/24">
        {#if title}
            <h1
                class="font-sans font-black text-neutral-900 text-7xl mt-5 tracking-tight"
            >
                {title}
            </h1>
        {/if}
        <img class="w-4/6 mx-auto my-8" src={image} alt="figure-1" />
    </div>
</div>
