# hover得用法

## 用法1

光标悬停在该元素上，使该元素的样式改变

<style>
    h1:hover {
        color: pink;
}
<style>
<body>
    <h1>用法1<h1>
<body>

 ## 用法2

通过hover控制其它块的样式

### 1.控制子元素样式

<style>
    h1:hover p{
        color: pink;
}
<style>
<body>
    <h1>用法
    	<p>控制子元素样式<p>
    <h1>
<body>





