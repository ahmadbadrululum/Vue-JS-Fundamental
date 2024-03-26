<template>
    <div>
        <input type="checkbox">
        <span>{{ task.name  }}</span>
    </div>
</template>

<script>
export default {
    name: 'ItemTugas',
    props:['task']
}
</script>