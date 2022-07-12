<script>
    export let items = [];
    export let images = [];
</script>

<div
    class="flex flex-wrap justify-evenly mx-auto max-w-22/24 py-10 text-center content-center h-screen"
>
    <div class="lg:w-11/24 w-22/24">
        <h1
            class="font-sans font-black text-neutral-900 text-7xl mt-5 tracking-tight"
        >
            {items[0]}
        </h1>
        <img class="w-4/6 h-auto mx-auto mt-8" src={images[0]} alt="figure-1" />
    </div>
    <div
        class="lg:w-11/24 w-22/24 animate__animated op0 start-1:op100 start-1:animate__fadeInRight"
    >
        <h1
            class="font-sans font-black text-neutral-900 text-7xl mt-5 tracking-tight"
        >
            {items[1]}
        </h1>
        <img class="w-4/6 h-auto mx-auto mt-8" src={images[1]} alt="figure-2" />
    </div>
</div>
