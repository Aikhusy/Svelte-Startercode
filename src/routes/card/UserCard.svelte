<!-- UserCard.svelte -->
<script>
    // Logic komponen
    export let name;
    export let email;
    let isEditing = false;
</script>

<!-- Template/UI -->
<div class="card">
    <h2>{name}</h2>
    <p>{email}</p>
</div>

<style>
    /* Scoped styling */
    .card {
        padding: 1rem;
        border: 1px solid #ddd;
    }
</style>