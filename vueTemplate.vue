<template lang="html">
    <div class="">

    </div>
</template>

<script>

  export default {
    // 组件名称
    name: 'clubcreate',
    // 用于注册引入的组件
    components: {},
    // 组件数据 （ 只接受 function ）
    data () {
      return {

      }
    },
    // 组件方法 ( 事件处理器 )
    methods: {

    },
    // 生命周期钩子函数 ( 组件实例刚刚被创建，组件属性计算之前，如data属性等 )
    // 在这加loading事件
    beforeCreate () {
      let that = this;

    },
    // 生命周期钩子函数 ( 组件实例创建完成，属性已绑定，但DOM未生成，$el属性还不存在 )
    // 在这结束loading, 做一些初始化， 实现函数自执行
    created () {
      let that = this;

    },
    // 生命周期钩子函数 ( 模板编译/挂载之后 不保证组件全部挂载 )
    // 在这发起请求，拿回数据，配合路由钩子做一些事情
    mounted () {
      let that = this;
      // 如果你希望等到整个视图都渲染完毕，可以用 vm.$nextTick 替换掉 mounted
      that.$nextTick(function () {

      })
    }
  }
</script>

<style media="screen"  lang="less" scoped>

</style>
