<script>
	let html = $state('<p>Write some text!</p>');
</script>

<div contenteditable></div>

<pre>{html}</pre>

<style>
	[contenteditable] {
		padding: 0.5em;
		border: 1px solid #eee;
		border-radius: 4px;
	}
</style>
