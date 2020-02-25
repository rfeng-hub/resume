<template>
    <div class="cell">
        <h3>项目经历</h3>
        <h4 class="row">
            <span>外勤通-审批工单管理</span>
            <span>2019.12-至今</span>
        </h4>
        <ul>
            <li>- 负责审批工单管理的设计与开发，包括模板管理、数据导出、自定义打印、数据统计可视化等九个页面；同步输出设计文档.</li>
            <li>- 主要使用了 HTML+CSS+JS 完成基本功能的实现，借助 Layui、Echarts 等框架和库完成部分功能.</li>
        </ul>
        <h4 class="row">
            <span>校友卡管理平台</span>
            <span>2019.10-2019.11</span>
        </h4>
        <ul>
            <li>- 基于项目原型开发校友卡管理平台第一版，完成接口对接与调试；参与原型调整讨论会议，实现原型调整后的第二版.</li>
            <li>- 开发技术主要是 Vue+Layui，传统的管理系统布局，iframe 作为主体内容显示区域.</li>
        </ul>
        <h4 class="row">
            <span>电商后台管理系统</span>
            <span>2020.01-2020.02</span>
        </h4>
        <ul>
            <li>- 一个简易的电商后台管理系统，实现对用户、权限、商品、订单的管理，整理出开发文档.</li>
            <li>- 前端技术栈包括 Vue、Vue-router、Element-UI、Axios、Echarts，后端技术栈包括 Node.js、Express、Jwt、Mysql、Sequelize.</li>
            <li>- 网址：<a href="http://123.57.5.190/">http://123.57.5.190/</a> 账号：admin 密码：123456.</li>
        </ul>
        <h4 class="row">
            <span>基于网络爬虫的电影票比价系统</span>
            <span>2019.01-2019.05</span>
        </h4>
        <ul>
            <li>- 使用 Python 编写网络爬虫，从猫眼、淘票票、糯米、时光网上获取全国所有城市的所有电影院里正在
上映的电影的排片信息，制作成一个基于上述四家购票平台的电影票比价系统，编写前端页面进行展
示，帮助用户购买到更优惠的电影票.</li>
        </ul>
        <h4 class="row">
            <span>基于深度学习的短文本数据挖掘模型与展示</span>
            <span>2018.01-2018.07</span>
        </h4>
        <ul>
            <li>- 针对互联网上的用户对产品的评论，根据情感倾向对数据加以分类，分别通过深度学习当中的卷积神经
网络(CNN)和循环神经网络(RNN)技术建立两种产品的数据挖掘模型并予以展示，通过对比两种模型的
性能，借鉴并不断改进。可供用户清晰的掌握互联网用户对产品的印象，使得用户对某种产品能够有更
加清晰的认识和评价，同时让产品的制造商获得大众的反馈以对自己的产品进行合理的改进.</li>
        </ul>
        <h4 class="row">
            <span>小样本物体识别系统</span>
            <span>2018.04-2018.06</span>
        </h4>
        <ul>
            <li>- 基于 Omniglot 数据集，用卷积神经网络设计模型。 给定一张图片，能够实时输出预测类型。系统能够
备份训练好的模型参数，并且能够载入已有的模型参数.</li>
        </ul>
    </div>
</template>

<script>
export default {};
</script>

<style lang="stylus" scoped>
.row {
    display: flex;
    justify-content: space-between;
}
</style>
