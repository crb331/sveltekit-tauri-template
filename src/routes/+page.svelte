<script>
    let count = 0;
    function aumentar() {
        count++;
    }
</script>

<h1>Welcome to SvelteKit</h1>
<h1>{count}</h1>

<button on:click={aumentar}>Aumentar </button>

<h1 class="text-3xl font-bold">
    Hello world!
</h1>