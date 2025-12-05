<script lang="ts">
	import Card from '../components/Card.svelte';
</script>

<span class="text-white text-3xl">Domenic Muentes</span>

<br />
<br />

<div>
	<span class="text-white">Information about me:</span>
	<p class="text-white">- I am a programmer</p>

    <br />

	<span class="text-white">My personal projects:</span>

    <br />
    <br />

	<div class="flex flex-row flex-wrap gap-3 max-w-fit bg-red-500">
		<Card>
			<span>Project 1</span>
		</Card>

		<Card>
			<span>Project 2</span>
		</Card>

		<Card>
			<span>Project 3</span>
		</Card>

		<Card>
			<span>Project 4</span>
		</Card>

		<Card>
			<span>Project 5</span>
		</Card>
	</div>
</div>
