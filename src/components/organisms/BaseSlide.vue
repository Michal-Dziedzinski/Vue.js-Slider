<template>
	<ArrowButton />
	<BaseImage />
	<ArrowButton />
</template>

<script>
import BaseImage from '@/components/molecules/BaseImage.vue';
import ArrowButton from '@/components/atoms/ArrowButton.vue';

export default {
	name: 'BaseSlide',
	components: {
		BaseImage,
		ArrowButton,
	},
};
</script>

<style lang="scss" scoped></style>
