<!--All needs to be responsive-->
<script>
  import { each } from "svelte/internal";
	import LinksButton from "./components/LinksButton.svelte";
	import ProfilePicture from "./components/ProfilePicture.svelte";

	let links= [
		{text : "medium", url : "https://medium.com/@louirecio"},
		{text : "Twitter / X", url : "https://twitter.com/louireciok"},
		{text : "LinkedIn", url : "https://www.linkedin.com/in/louirecio/"},
		{text : "GitHub", url : "https://github.com/louire/"}
	];
	let imgLink = {url : "https://avatars.githubusercontent.com/u/71304021?v=4"};
</script>

<style>

.containerCentre {
	text-align: center;
}

</style>

<div class="containerCentre">
	<ProfilePicture {...imgLink} />
	<p>
		@louire
		<br>
		Loui Recio Izaguirre
	</p>
	{#each links as link}
		<LinksButton {...link} />
	{/each}

</div>


