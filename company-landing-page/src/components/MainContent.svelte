<script lang="ts">
	export let CTA_Name: string = "Click Here";
</script>

<main>
	<div>
		<h1>Landing page</h1>
		<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ac dui iaculis, condimentum sapien ac, interdum libero. </p>

		<button>{CTA_Name}</button>
	</div>
	<div class="right_side">
		<img src="" width="100%"  alt=""/>
	</div>
</main>

<style>
    
	main {
		display: flex;
		flex-direction: row;
		color: #FCC603;
	}

	div {
		padding: 2rem;
		flex: 1;
		background-color: #5D9BFD;
	}

	.right_side {
		background-color: #FFF3C2;
	}

	img {
		box-shadow: 0px 4px 10px #333;
	}

	button {
		margin-top: 2rem;
		min-width: 200px;
		border-radius: 2rem;
		background-color: #FCC603;
		color: #023047;
		font-weight: bold;
		font-size: 1.2rem;
		border: 0px;
		box-shadow: 2px 4px 5px black;
	}
</style>