<script>
	import { base } from '$app/paths';

	import DATA from '$lib/data.js';
	import Header from '$lib/Header.svelte';
	import JoinUs from '$lib/JoinUs.svelte';
	import About from '$lib/About.svelte';
	import Carousel from '$lib/Carousel.svelte';
	import News from '$lib/News.svelte';
	import Footer from '$lib/Footer.svelte';
	import StaffPage from '$lib/StaffPage.svelte';
	import ParentVolunteers from '$lib/ParentVolunteers.svelte';
	import UpcomingSeason from '$lib/UpcomingSeason.svelte';
	import FAQ from '$lib/FAQ.svelte';
	import Schedule from '$lib/Schedule.svelte';
	import BandCamp from '$lib/BandCamp.svelte';
</script>

<Header links={DATA.NAV_DATA.LINKS} />
<BandCamp />
<UpcomingSeason />
<JoinUs />
<About />
<Schedule events={DATA.EVENTS_DATA} />
<Carousel images={DATA.IMAGE_DATA} />
<ParentVolunteers />
<News articles={DATA.NEWS_STORIES} />
<StaffPage staff={DATA.STAFF_DATA} />
<FAQ questions={DATA.QUESTIONS_DATA} />
<Footer />
