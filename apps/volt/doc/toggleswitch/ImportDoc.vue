<template>
    <DocSectionText v-bind="$attrs" />
    <DocSectionCode :code="code" lang="script" />
</template>

<script>
export default {
    data() {
        return {
            code: `import ToggleSwitch from '@/volt/toggleswitch';
`
        };
    }
};
</script>
