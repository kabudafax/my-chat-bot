* react-textarea-autosize 这个插件可以使得text-area组件自适应文本长度
* 安装插件 @tailwindcss/forms 来美化输入框,他是一个tailwindcss插件，需要在tailwindcss.config.ts中的plugins中进行配置。
 ` plugins: [require("tailwindcss-animate"), require("@tailwindcss/forms")],`
  * 配置完成后会自动应用来美化输入框
* 实现结果的流式返回
  * 使用nextjs的api来返回结果
  * 使用react-query来简化loading和
  * `pnpm i @tanstack/react-query`
* `nanoid` 随机生成unique id 
* 使用zod进行表单的类型验证`pnpm i zod`
* `eventsource-parser`用来处理readablestream,接收chunks，并且在接受完完整信息后，触发parsed data
* `react-hot-toast` 一个流行的toast库
* 使用upstash的redis服务，来为路由添加保护
  * 安装两个库`@upstash/redis @upstash/ratelimit`

### warmup
* e.preventDefault() 是一个方法，用于阻止浏览器执行与事件相关的默认动作。例如，当你在一个表单的提交按钮上点击时，浏览器默认会重新加载页面。如果你希望在点击按钮时执行一些自定义的 JavaScript 逻辑，而不是让浏览器重新加载页面，就可以使用 e.preventDefault() 来阻止这种默认行为
* 一些常见的使用场景：
  * 表单提交：不重新加载页面
  * 链接点击：不导航到新页面
  * 右键菜单：阻止默认的浏览器右键菜单