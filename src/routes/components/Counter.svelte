<!-- UserCard.svelte -->
<script>
    // Logic komponen
    let counter = 0;

    function incrementNumber()
    {
        counter ++;
    }
</script>

<!-- Template/UI -->
<div class="card">
    <button type="button" on:click={incrementNumber}>
        {counter} {counter === 1 ? 'time':"times"}
    </button>
</div>

<style>
    /* Scoped styling */
    .card {
        padding: 1rem;
        border: 1px solid #ddd;
    }
</style>