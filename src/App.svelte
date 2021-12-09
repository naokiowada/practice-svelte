<script>
 let count = 0;
 
 function incrementButton () {
	count += 1; 
 }
 function decrementButton () {
	 count -= 1;
 }
　
</script>
<div>
</div>

<main>
	<div style={count < 0 ? "background-color:red;" : ""}>
		{count}
	</div>
 <button on:click={incrementButton}>+</button>
 <button on:click={decrementButton}>-</button>	
</main>

<style>

</style>