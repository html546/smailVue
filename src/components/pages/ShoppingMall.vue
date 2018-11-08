<template>
    <div class="search-bar">
        <van-row>
            <van-col span="3">icon</van-col>
            <van-col span="16">search-input</van-col>
            <van-col span="5">button</van-col>
        </van-row>
    </div>
</template>

<script>
export default {
    name: '',
    data() {
        return {
            msg:'Shopping Mall'
        }
    }
}
</script>

<style lang="" scoped>
.search-bar{
    height: 2.2rem;
    background-color: #e5017d;
    line-height: 2.2rem;
}
</style>