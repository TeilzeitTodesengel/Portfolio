<h1>Welcome to SvelteKit</h1>
<div class="cards">
    <div class="card"></div>
    <div class="card"></div>
    <div class="card"></div>
    <div class="card"></div>
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

.cards {
    display: flex;
    flex-wrap: wrap;
    flex-direction: row;
    justify-content: center;
    align-self: center;
    gap: 0.5rem;
    width: 90%;
    padding: 2rem;
    --yPos: 100px;
    --xPox: 100px;
    .card{
        width: 20rem;
        height: 15rem;
        background: radial-gradient(
            100rem circle at var(--xPox) var(--yPos),
            rgba(#4411bb, 0.6),
            transparent 10%
        );
        border-radius: 0.5rem;
    }
}
</style>