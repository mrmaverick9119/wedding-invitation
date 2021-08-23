<template>
	<div id="profile">
		<div>
			<h1 class="uk-heading-line uk-text-center uk-h1 uk-padding-small title" uk-scrollspy="cls:uk-animation-slide-top-small"><span>Our Profile</span></h1>
			<div>
				<div class="uk-column-1-2@l uk-padding-large">
					<div uk-scrollspy="cls:uk-animation-slide-left-medium" class="uk-padding-large uk-padding-remove-horizontal uk-padding-remove-top">
						<img src="../assets/images/KC-16-5.jpg" :alt="wanita.nama" class="uk-border-circle uk-width-medium@l uk-width-large uk-box-shadow-large ">
						<div class="uk-padding-small uk-padding-remove-bottom">
							<h2 class="uk-h2">{{ wanita.nama }}</h2>
							<p class="text-deskripsi uk-responsive-width uk-margin-auto uk-margin-auto-vertical uk-padding-medium">{{ wanita.deskripsi }}</p>
						</div>
					</div>
					<div uk-scrollspy="cls:uk-animation-slide-right-medium" class="uk-padding-large uk-padding-remove-horizontal uk-padding-remove-top">
						<img src="../assets/images/KC-3.jpg" :alt="pria.nama" class="uk-border-circle uk-width-medium@l uk-width-large uk-box-shadow-large">
						<div class="uk-padding-small uk-padding-remove-bottom">
							<h2 class="uk-h2 uk-responsive-width uk-margin-auto uk-margin-auto-vertical uk-padding-medium">{{ pria.nama }}</h2>
							<p class="text-deskripsi uk-responsive-width uk-margin-auto uk-margin-auto-vertical uk-padding-medium">{{ pria.deskripsi }}</p>
						</div>
					</div>
				</div>
			</div>
		</div>
	</div>
</template>

<script>
export default {
  name: 'Profile',

  data () {
    return { pria: { nama: 'Chaithra', deskripsi: '' }, wanita: { nama: 'Kishan', deskripsi: '' } }
  }
}
</script>

<style lang="css" scoped>
	#profile {
		padding-top: 1px;
        background-color: #c1ebf7;
	}
	
    .text-deskripsi {
    	color: #666666 !important;
    }

	@media screen and (max-width: 1024px) {
		
	}
</style>