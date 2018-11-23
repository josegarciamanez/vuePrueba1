<template>
    <div>
        <h1>{{ titulo }}</h1>
        <h5>{{ autor }}</h5>
    </div>
</template>

<script>
export default {
    name: 'Titulo',
    props: {
        titulo: String,
        autor: String,
    },
    data() {
        return {};
    },
};
</script>
