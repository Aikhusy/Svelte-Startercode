<h1>abouts</h1>
<p>
    component dari 
    
</p>
<UserCard email="aikhusy@gmail.com" name="aikhusy" />

<Counter/>

<div class="card" id="card">

    <button type="button" onclick={createNewButton}>click gw</button>
    
</div>

<script module>

    import UserCard from '../../routes/card/UserCard.svelte';
    import Counter from '../../routes/components/Counter.svelte';
	let total = 0;
    function createNewButton()
    {
        const card = document.getElementById('card');
        if (card) {
        // Create a new instance of the Counter component
            
        }
    }

</script>

<script>

	total += 1;
	console.log(`instantiated ${total} times`);
    console.log(`instantiated jalan bro`);
    
</script>

<style>

	p {
		/* this will only affect <p> elements in this component */
		color: burlywood;
	}

</style>