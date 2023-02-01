<template>
    <div>
        <h2>学生姓名:{{name}}</h2>
        <h2>学生年龄:{{age}}</h2>
        <button @click="showName">点我提示姓名</button>
    </div>
</template> 

<script>
export default {
    name:'Student',
    data() {
        return {
            name:'许佳乐',
            age:22
        }
    },
    methods: {
        showName(){
            alert(this.name)
        }
    },
}
</script>