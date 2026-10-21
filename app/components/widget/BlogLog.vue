<script setup lang="ts">
const blogLog = [
	{ label: '2026-10-19', value: '使用 midnightcrowing.site 域名' },
]
</script>

<template>
<BlogWidget card title="更新日志">
	<ZDlGroup size="large" :items="blogLog" />
</BlogWidget>
</template>
