<template>
	<div class=" relative px-1 py-6 sm:px-6 sm:py-10">
		<div class="relative bg-white w-3/4 py-6 px-8 m-auto shadow-2xl rounded-xl">
			<div>
				<img
					loading="lazy"
					width="400"
					height="400"
					class="profile-img mx-auto drop-shadow-2xl"
					src="../../assets/myimg3.jpeg"
				/>
				<h1 class="text-blue-500 text-xl font-bold text-center p-1 m-1">
					Muhammad Usama
				</h1>
			</div>

			<ul class="flex justify-around text-sm sm:text-base">
				<li>Developer</li>
				<li>Designer</li>
				<li>Gamer</li>
			</ul>
		</div>
	</div>
</template>

<script>
export default {
	name: "AppProfileCard"
};
</script>

<style scoped>
.profile-img {
	width: 6rem;
	border-radius: 100%;
	box-shadow: -1px 3px 17px 0px rgba(0, 0, 0, 0.75);
	-webkit-box-shadow: -1px 3px 17px 0px rgba(0, 0, 0, 0.75);
	-moz-box-shadow: -1px 3px 17px 0px rgba(0, 0, 0, 0.75);
}
</style>