<script>
	export let url;

	const changeProfilePicture = (isFormal) =>{
		if(!isFormal){
			document.querySelector("#profilePicture").src = "https://i.imgur.com/9bxvv1N.jpeg";
		}else{
			document.querySelector("#profilePicture").src = url;
		}
	}
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
	<img src={url} 
		on:mouseenter={() => changeProfilePicture(false)} 
		on:mouseleave={() => changeProfilePicture(true)}
		id="profilePicture" 
		alt="ProfilePicture, yeah its me :D" 
		class="profile-picture"
	>
</div>
