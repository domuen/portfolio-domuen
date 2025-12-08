<script lang="ts">
	let { preview, url } = $props();
</script>

<div class="rounded-xl cursor:pointer hover:scale-1.25">
	<img src={preview} alt="" />

	<text>{url}</text>
</div>
