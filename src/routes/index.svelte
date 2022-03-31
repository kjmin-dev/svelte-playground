<script>
    let currentTime = new Date();
    setInterval(() => {
        currentTime = new Date();
    }, 1000);
</script>

<h1>Welcome to SvelteKit</h1>
<p>Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation</p>
<p>The current time is: {currentTime}</p>
