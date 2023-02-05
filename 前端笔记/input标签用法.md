# 表单提交

　为了能够让input的数据表单内容成功提交到指定的url中，需要在input的外面套一层<form action="#"> </form>
　其中，action后面填写的值为目的url。

# 原有的type属性值

- button

- checkbox，复选框，也可做为一种属性单独使用

- file，添加mutiple属性后一次能上传多个文件

- hidden

- image，用src将一张图片放置在页面上，将提交鼠标点击该图片的坐标位置。当src资源缺失，则显示alt属性值

- password

- radio，单选框，配合name属性分组单选框

- reset，重置当前表单数据，配合forn标签使用

- submit，提交当前标签数据，配合form标签使用

- text，文本框

## CODE展示

  <form action="">
          <!-- 复选框，配合label使用 -->
          <!-- id值和for值一样 -->
          兴趣：
          <input type="checkbox" name="" id="阅读" value="兴趣">
          <!-- value里的值要上传到服务器 -->
          <label for="阅读">阅读</label>
          <input type="checkbox" name="" id="玩游戏" value="兴趣">
          <label for="玩游戏">玩游戏</label>
          <input type="checkbox" name="" id="编程" value="兴趣">
          <label for="编程">编程</label>
          <br>
          通关的游戏：
          <input type="checkbox" name="" id="生化危机8" value="游戏" checked>
          <label for="生化危机8">生化危机8</label>
          <input type="checkbox" name="" id="生化危机7" value="游戏">
          <label for="生化危机7">生化危机7</label>
          <input type="checkbox" name="" id="双人成行" value="游戏">
          <label for="双人成行">双人成行</label>
          <br>
          <!-- 单选框 -->
          <!-- 配合name分组 -->
          性别：
          <input type="radio" name="性别" id="man" checked>
          <label for="man">男</label>
          <input type="radio" name="性别" id="woman">
          <label for="woman">女</label>
          <input type="radio" name="性别" id="secret">
          <label for="secret">未知</label>
          <br>
          登录页面：
          <br>
          账号：<input type="text">
          密码：<input type="password" name="" id="">
          <input type="submit" value="提交">
          <br>
          <!-- 配合form标签使用 -->
          <input type="reset" value="重置">
          上传文件：
          <!-- 添加mutiple属性后一次能上传多个文件 -->
          <input type="file" name="" id="" multiple>
          <br>
          <input type="image" src="./pic.png" alt="牛马">
  </form>
# 新增type属性值

