<template>
    <div class="label-conteiner">
       <div class="label-title">{{title}}</div>
       <div class="label-numb">{{numbers}}</div>
    </div>
</template>

<script>
    export default {
        name : 'LabelComp',
        props: {
            title: {
                type: String,
                default: 'no title'
            },
            numbers: {
                type: Number,
                default: 1
            }
        }
    }
</script>

<style lang="css">
.label-conteiner {
    width: 100px;
    display: inline-flex;
}
.label-numb {
    width: 20px;
    background-color: black;
    text-align: center;
}
.label-title {
    background-color: white;
}
</style>