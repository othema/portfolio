<script lang="ts">
	export let title: string;
	export let date: string;
	export let description: string = "Lorem ipsum dolor sit amet consectetur adipisicing elit. Sapiente molestiae unde quae quis quasi? Error!";
	export let image: string = "https://via.placeholder.com/48"
	export let color: string = "white";
</script>

<article class={`flex items-center gap-4 bg-opacity-30 p-4 my-3 rounded-md hover:scale-105 transform ease-in-out duration-300 ${color}`}>
	<img class="rounded-md h-12 w-12" src={image} alt="Project">
	<div>
		<h3 class="font-bold text-lg flex items-center">{title} <span class="font-normal text-sm ml-4">[{date}]</span></h3>
		<p class="text-sm">{description}</p>
	</div>
</article>