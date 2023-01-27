<script lang="ts">
	export let color: string = "bg-white";
	export let title: string;
	export let url: string | null;
</script>

<a href={url} rel="noreferrer" target="_blank" class={`flex gap-4 bg-opacity-30 p-4 rounded-md hover:scale-105 transform ease-in-out duration-300 ${color} cursor-pointer`}>
	<slot class="w-6" />
	<h3>{title}</h3>
</a>