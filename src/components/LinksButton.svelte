<script>
	export let url;
	export let text;
</script>


<style>
    a.button {
	background-color: #4CAF50;
	border: none;
	color: white;
	padding: 15px 32px;
	line-height: 24px;
	display: inline-block;
	font-size: 16px;
	width: 80%;
	margin-top: 20px;
	border-radius: 10px;
}
</style>


<div class="LinksButtons">
	<a href={url} target="_blank" class="button">{text}</a>

</div>