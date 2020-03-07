<template>
    <div class="pt_container">
        <Point />
    </div>
</template>

<script>
import Point from "~/components/Point.vue"

export default {
    name : "Editor",
    components : {
        Point
    }
}
</script>

<style>

.pt_container {
    width : 500px;
    height: 500px;
    border : 1px solid black;
}

</style>>

