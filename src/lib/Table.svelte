<script lang="ts">
	async function main() {
		fetch("results-min.json").then(res => res.json()).then(console.log);
	}

	main();
</script>

<p>Table.</p>
