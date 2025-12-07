<script lang="ts">
	import ProjectCard from '../components/ProjectCard.svelte';
</script>

<!-- TODO: investigate this flex direction responsiveness bug -->
<div class="flex lg:flex-col items-center p-4 gap-4">
	<div class="flex lg:flex-row flex-col w-6xl gap-4 overflow-hidden">
		<div class="flex flex-col lg:w-1/3 w-full p-6 gap-4 bg-gray-900 rounded-4xl">
			<div class="flex gap-4">
				<div class="w-20 h-20 bg-blue-500 rounded-full"></div>
				<div>
					<h2>Domenic Muentes</h2>
					<h4>Software Engineer</h4>
				</div>
			</div>

			<div class="lg:hidden flex gap-4">
				<button class="text-white px-4 py-2 bg-gray-800 rounded-xl hover:bg-gray-700"
					>View Resume</button
				>
				<button class="text-white px-4 py-2 bg-gray-800 rounded-xl hover:bg-gray-700"
					>Contact</button
				>
			</div>
		</div>

		<!-- <div class="h-px mx-6 bg-gray-500 rounded-full"></div> -->

		<div class="flex flex-col lg:w-2/3 w-full p-6 gap-4 bg-gray-900 rounded-4xl">
			<h2>My Personal Projects</h2>

			<div class="flex lg:flex-row flex-col flex-wrap gap-3 max-w-fit">
				<ProjectCard preview="" url="" />
				<ProjectCard preview="" url="" />
				<ProjectCard preview="" url="" />
				<ProjectCard preview="" url="" />
				<ProjectCard preview="" url="" />
				<ProjectCard preview="" url="" />
			</div>
		</div>
	</div>

	<div class="lg:flex hidden lg:flex-row flex-col w-6xl gap-4 overflow-hidden">
		<div class="flex flex-col lg:w-1/3 w-full p-6 gap-4 bg-gray-900 rounded-4xl">
			<h2>Contact</h2>

			<div class="h-px bg-gray-500 rounded-full"></div>

			<div>
				<p>domenicmuentes@example.com</p>
				<p>(555) 555-5683</p>
			</div>
		</div>

		<div class="lg:w-2/3 w-full"></div>
	</div>
</div>
