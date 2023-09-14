<script lang="ts">
    let xPos = 100;
    let yPos = 100;
</script>

<div class="card">
    <slot></slot>
</div>

<style lang='scss'>
    .card {
        width: 20rem;
        height: 15rem;
        background: radial-gradient(
            100rem circle at 100px 100px,
            rgba(#4411bb, 0.6),
            transparent 10%
        );
        border-radius: 0.5rem;
        border-color: #117dbb;
        border-width: 5px;
    }
</style>