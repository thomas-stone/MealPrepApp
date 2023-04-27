<h1>Welcome to MealPrepApp</h1>
<p>A work in progress for all of your meal prep plans!</p>

<p>Included below is a button to click while you wait.</p>

<div>
    <button on:click={handleClick}>Click Me!</button>
    <p>clicked {count} {count == 1 ? 'time' : 'times'}</p>
</div>


<script>
	let count = 0;

	function handleClick() {
		count += 1;
	}
</script>