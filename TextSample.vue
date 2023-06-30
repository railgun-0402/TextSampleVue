<template>
    <div class="container">
        <div class="row mt-3">
            <input type="test" v-model="text" class="form-control-inline col-6" />
            <div class="col-5">
                <button @click="show()" class="btn btn-primary">show</button>
                <button @click="change()" class="btn btn-primary">change</button>
            </div>
            <div class="alert alert-info mt-3">{{ text }}</div>
        </div>
    </div>
</template>

<script>
export default {
    data: function() {
        return {
            text: "",
        };
    },
}
</script>