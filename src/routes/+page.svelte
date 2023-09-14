<script>
    import Card from "$lib//Card.svelte";
</script>

<h1>Welcome to SvelteKit</h1>
<div class="cards">
    <Card><p class="card-content">About Me</p></Card>
    <Card><p class="card-content">About my Projects</p></Card>
    <Card><p class="card-content">Some Jokes</p></Card>
    <Card><p class="card-content">Legal Stuff</p></Card>
</div>
<p>Visit <a href="/about">the About Page</a> to read about me</p>
<p>Visit <a href="/projects">the Projects Page</a> to read about my projects</p>
<p>Visit <a href="/jokes">the Jokes Page</a> to read some (veeeery) bad jokes</p>
<p>Visit <a href="/index">the About Page</a> to read about index</p>

<style lang="scss">
    :global(body) {
    background-color: #232533;
}
a {
    text-decoration: none;
    color: #41bd4c;
}
p {
    color: #41bd4c;
}

.card-content {
    display: flex;
    flex-wrap: wrap;
    flex-direction: row;
    justify-content: center;
    align-self: center;
    text-align: center;
}

.cards {
    display: flex;
    flex-wrap: wrap;
    flex-direction: row;
    justify-content: center;
    align-self: center;
    gap: 0.5rem;
    width: 90%;
    padding: 2rem;
}
</style>