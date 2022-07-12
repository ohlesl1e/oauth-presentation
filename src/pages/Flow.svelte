<div class="flex flex-col min-h-screen justify-center items-center flow-bg">
    <ul class=''>
        {#each Array(7) as _, i}
            <li>
                <img 
                class='my-15 animate_animated op0 start-{i+1}:op100 start{i+1}:animate_fadeInUp'
                src="flow{i + 1}.png" 
                alt="{i + 1} step" 
                />
            </li>
        {/each}
    </ul>
</div>

<style>
    .flow-bg {
        background-image: url('flow-background.png');
    }
</style>