<script>
	import Heading from './Heading.svelte';
	import StaffCard from './StaffCard.svelte';

	/**
	 * @type {any[]}
	 */
	export let staff = [];
	export let id = 'staff';
</script>

<div class="my-16">
	<Heading {id}>Meet the staff</Heading>
	<div class="flex justify-center items-center">
		{#each staff as staffMember}
			<StaffCard {...staffMember} />
		{/each}
	</div>
</div>
