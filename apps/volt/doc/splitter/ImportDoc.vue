<template>
    <DocSectionText v-bind="$attrs" />
    <DocSectionCode :code="code" lang="script" />
</template>

<script setup>
import { ref } from 'vue';

const code = ref(`import Splitter from '@/volt/splitter';
import SplitterPanel from 'primevue/splitterpanel';
`);
</script>
