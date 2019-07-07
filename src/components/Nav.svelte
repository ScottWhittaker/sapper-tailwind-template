<script>
	export let segment;
</script>

<nav class="text-sm">
	<a class='mr-2 hover:text-red-600  {segment === undefined ? "underline" : ""}' href='.'>home</a>
	<a class='hover:text-red-600 {segment === "about" ? "underline" : ""}' href='about'>about</a>
</nav>