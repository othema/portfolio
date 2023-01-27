<script lang="ts">
	export let color: string = "bg-white";
	export let title: string;
</script>

<div class={`flex gap-4 bg-opacity-30 p-4 rounded-md hover:scale-105 transform ease-in-out duration-300 ${color}`}>
	<slot class="w-6" />
	<h3>{title}</h3>
</div>