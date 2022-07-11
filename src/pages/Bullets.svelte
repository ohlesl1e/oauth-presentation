<script>
    export let title;
    export let bullets = [];
    export let animated = false;
</script>

<div class="flex flex-wrap justify-evenly mx-auto max-w-22/24 pt-20">
    <div class="w-22/24">
        <h1
            class="font-sans font-black text-neutral-900 text-8xl text-left tracking-tight"
        >
            {title}
        </h1>
        <ul
            class="font-sans font-semibold text-neutral-900 text-5xl tracking-normal leading-none"
        >
            {#each bullets as value, i}
                {#if animated}
                    <li
                        class="list-disc w-23/24 py-3 animate__animated mt-3 op0 start-{i +
                            1}:op100 start-{i + 1}:animate__fadeInUp"
                    >
                        {value}
                    </li>
                {:else}
                    <li class="list-disc w-23/24 py-3 mt-3 op100">
                        {value}
                    </li>
                {/if}
            {/each}
        </ul>
    </div>
</div>
