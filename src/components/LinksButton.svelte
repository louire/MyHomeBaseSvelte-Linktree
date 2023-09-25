<script>
	export let url;
	export let text;
	export let iconButton;
</script>


<style>
    a.button {
	background-color: #E5C3A6;
	border: none;
	color: black;
	padding: 15px 32px;
	line-height: 24px;
	display: inline-block;
	font-size: 16px;
	font-weight: bolder;
	width: 80%;
	margin-top: 20px;
	border-radius: 10px;
	
}
</style>


<div class="LinksButtons">
	<a href={url} target="_blank" class="button">{iconButton} {text}</a>
</div>
