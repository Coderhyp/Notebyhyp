# Vue生命周期

* 从new 一个 Vue实例到这个实例销毁的过程 就是生命周期 从开始创建 初始化数据 编译模板 挂载DOM渲染 更新-渲染 卸载等一系列过程 
* Vue内部能够让我们在在生命周期不同的阶段 调用相应的回调函数（钩子函数）进行相应操作  
* 我们可以使用的有 beforeCreate created  beforeMount mounted beforeUpdate Updated beforeDestory destoryed 
* 第一次的页面加载会触发的钩子是beforeCreate created  beforeMount mounted
* 异步请求可以在created中或者mounted中调用  mounted主要是在DOM渲染的阶段

