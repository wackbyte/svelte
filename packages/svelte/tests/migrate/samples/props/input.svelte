<script>
	/** @type {Record<string, { href: string; title: string; }[]>} */
	export let readonly;
	export let optional = 'foo';
	export let binding;
	export let bindingOptional = 'bar';
</script>

{readonly}
{optional}
<input bind:value={binding} />
<input bind:value={bindingOptional} />
