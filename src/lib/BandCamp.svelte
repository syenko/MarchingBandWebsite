<script>
	import { base } from '$app/paths';
</script>

<div class="flex flex-col items-center justify-center p-12">
	<div class="font-header text-4xl">Get ready for Band Camp!</div>
	<div class="grid grid-cols-3 mt-5 text-lg text-center gap-5">
		<div>
			<div class="font-bold">Where?</div>
			<div>Room 803 (the band room) at the front of Los Altos High School!</div>
			<div class="p-3 w-full flex flex-col items-center">
				<a href="{base}/BandRoomMap.pdf" target="_blank">
					<img
						class="h-full max-h-64 object-cover"
						src="{base}/images/wherebandroom.png"
						alt="Map of LAHS with Band Room circled"
					/>
					<div class="text-gray-500 text-sm">Click for full map</div>
				</a>
			</div>
		</div>
		<div>
			<div class="font-bold">When?</div>
			<div>9:00 AM - 4:00 PM from Monday, August 4th to Saturday, August 9th</div>
			<div class="pt-3">12:00 PM - 4:00 PM on Saturday will be the family showcase and picnic!</div>
		</div>
		<div>
			<div class="font-bold">What do I bring?</div>
			<ul>
				<li>Comfortable athletic wear</li>
				<li>Water bottle (large!)</li>
				<li>Lunch</li>
				<li>Music binder and pencil</li>
				<li>Sunscreen</li>
				<li>Instrument</li>
				<li>Yourself! (and a friend?)</li>
			</ul>
		</div>
	</div>
</div>
