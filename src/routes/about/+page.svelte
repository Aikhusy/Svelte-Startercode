<h1>abouts</h1>
<p>
    component dari 
    
</p>
<UserCard email="aikhusy@gmail.com" name="aikhusy" />

<Counter/>

<script module>

    import UserCard from '../../routes/card/UserCard.svelte';
    import Counter from '../../routes/components/Counter.svelte';
	let total = 0;
    
</script>

<script>
	total += 1;
	console.log(`instantiated ${total} times`);
</script>

<style>
	p {
		/* this will only affect <p> elements in this component */
		color: burlywood;
	}
</style>