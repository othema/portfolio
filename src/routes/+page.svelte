<script>
	import Project from "../components/Project.svelte";

</script>
<nav>
	djvgeorge.me
</nav>

<div class="max-w-3xl px-8 mt-24 mx-auto">
	<section>
		<h1 class="font-bold text-3xl">Daniel George</h1>
		<p class="w-[80%] mt-4">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Delectus, ipsa architecto incidunt nesciunt obcaecati at inventore fugiat eum.</p>
		<img class="h-11 mt-4" src="https://skillicons.dev/icons?perline=30&i=js,ts,html,css,nodejs,react,tailwind,svelte,sass,py,c,unity&theme=dark" alt="My skills" />
	</section>

	<hr class="my-8 border-gray-400 dark:border-gray-500"/>

	<section>
		<h2 class="font-bold text-2xl">Notable Projects</h2>

		<ul class="mt-3">
			<Project title="StockX" date="Mar 2021" color="bg-red-500"/>
			<Project title="StockX" date="Mar 2021" color="bg-purple-500" />
			<Project title="StockX" date="Mar 2021" color="bg-green-500" />
		</ul>
	</section>
</div>