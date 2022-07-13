<div class="flex flex-col h-screen items-center flow-bg">
    <ul class="mt-15">
        {#each Array(5) as _, i}
            {#if i < 2}
                <li>
                    <img
                        class="my-15 animate__animated op0 start-{i +
                            1}:op100 start-{i + 1}:animate__fadeInUp"
                        src="flow{i + 1}.png"
                        alt="{i + 1} step"
                    />
                </li>
            {:else}
            <li>
                <img
                    class="my-15 animate__animated op0 start-{i +
                        1}:op100 start-{i + 1}:animate__fadeInUp"
                    src="imflow{i + 1}.png"
                    alt="{i + 1} step"
                />
            </li>
            {/if}
        {/each}
    </ul>
</div>

<style>
    .flow-bg {
        background-image: url("im-flow-background.png");
    }
</style>
