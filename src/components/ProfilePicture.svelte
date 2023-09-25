<script>
	export let url;
</script>

<style>
    .profile-picture {
		
	width: 200px;
	margin-top: 35px;
	border-radius: 50%;
	object-fit: cover;
}
	
</style>


<div class="ProfilePicture">
	<img src={url} alt="ProfilePicture, yeah its me :D" class="profile-picture">
    
</div>