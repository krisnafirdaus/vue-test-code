<script setup>
defineProps({
  desc: {
    type: String,
    required: true
  }
})
</script>

<template>
	<div class="card">
		<div>{{ desc }}</div>
	</div>
</template>