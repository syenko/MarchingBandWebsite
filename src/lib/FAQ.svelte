<script>
	import Heading from './Heading.svelte';
	import Question from './Question.svelte';
	/**
	 * @type {any[]}
	 */
	export let questions = [];
	export let id = 'faq';
</script>

<div class="mb-8"><Heading {id}>FAQ</Heading></div>
<div class="w-full px-5 flex flex-col items-center justify-center">
	{#each questions as question}
		<Question {...question} />
	{/each}
</div>
