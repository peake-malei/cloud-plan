<template>
    <div>
        披克云计划
        <el-steps :active="1" style="margin-top:100px">
            <el-step title="步骤 1" description="这是一段很长很长很长的描述性文字"></el-step>
            <el-step title="步骤 2" description="这是一段很长很长很长的描述性文字"></el-step>
            <el-step title="步骤 3" description="这段就没那么长了"></el-step>
        </el-steps>
    </div>
</template>

<script>
    export default {
        name: "CloudPlan"

    }
</script>

<style scoped>

</style>