# 用户体验 Cheatsheet
> 更新时间：2016年11月3日

|属性|内容|
|:---|:---|
|需求|<input type="text" style="width:10rem;height:1.2rem;" placeholder=" 需求名称">|
|平台|<form action=""><input type="radio" name="platform" value="ios">&nbsp;iOS<div style="margin:-1.5rem;">&nbsp;</div><br><input type="radio" name="platform" value="android">&nbsp;Android<div style="margin:-1.5rem;">&nbsp;</div><br><input type="radio" name="platform" value="h5">&nbsp;H5<br><span style="font-size:0.8rem;color:#999999;">具体版本号测试跟进</span></form>|
|当前阶段|<form><select id = "ux_process"><option value = "design">设计中</option><option value = "implementation">研发自测</option><option value = "walk_through" selected="selected">设计走查</option><option value = "test_verification">测试验证</option></select></form>|
|负责人|<input type="text" placeholder="" style="width:6rem;height:1.2rem;">|

<br>


## 1. 信息流程

|条件|场景1|
|:---|:---|
|信息布局<p style="color:#666666;font-size:0.8rem;margin-top:0;max-width:200px;word-wrap:break-word;">整体的信息布局是否满足需求，是否表达了轻重</p>|<input type="checkbox" name="content" value="info_architecture">&nbsp;满足需求<br><div style="margin:-0.6rem;">&nbsp;</div><textarea name="textarea" style="border-color:#cccccc;border-radius:2px;" rows="6" cols="40" placeholder="如有问题请说明"></textarea>|
|文案内容<p style="color:#666666;font-size:0.8rem;margin-top:0;max-width:200px;word-wrap:break-word;">文案是否准确，运营是否确认文案</p>|<input type="checkbox" name="content" value="info_architecture">&nbsp;满足需求<br><div style="margin:-0.6rem;">&nbsp;</div><textarea name="textarea" style="border-color:#cccccc;border-radius:2px;" rows="6" cols="40" placeholder="如有问题请说明"></textarea>|
|入口操作<p style="color:#666666;font-size:0.8rem;margin-top:0;max-width:200px;word-wrap:break-word;">点击后的跳转目标是否正确</p>|<input type="checkbox" name="actions" value="entry_point">&nbsp;满足需求<br><div style="margin:-0.6rem;">&nbsp;</div><textarea name="textarea" style="border-color:#cccccc;border-radius:2px;" rows="6" cols="40"  placeholder="如有问题请说明"></textarea>|
|信息导航<p style="color:#666666;font-size:0.8rem;margin-top:0;max-width:200px;word-wrap:break-word;">页面的路径是否理解，回退是否正确，头部标题是否易于理解和定位</p>|<input type="checkbox" name="nav" value="navigation">&nbsp;满足需求<br><div style="margin:-0.6rem;">&nbsp;</div><textarea name="textarea" style="border-color:#cccccc;border-radius:2px;" rows="6" cols="40"  placeholder="如有问题请说明"></textarea>|
|页面切换<p style="color:#666666;font-size:0.8rem;margin-top:0;margin-top:0;max-width:200px;word-wrap:break-word;">切换转场是否流畅且合理</p>|<input type="checkbox" name="trans" value="transition">&nbsp;满足需求<br><div style="margin:-0.6rem;">&nbsp;</div><textarea name="textarea" style="border-color:#cccccc;border-radius:2px;" rows="6" cols="40"  placeholder="如有问题请说明"></textarea>|
|不同用户的场景<p style="color:#666666;font-size:0.8rem;margin-top:0;margin-top:0;max-width:200px;word-wrap:break-word;">新老用户的不同情况是否有考虑</p>|<input type="checkbox" name="contexts" value="senario">&nbsp;满足需求<br><div style="margin:-0.6rem;">&nbsp;</div><textarea name="textarea" style="border-color:#cccccc;border-radius:2px;" rows="6" cols="40"  placeholder="如有问题请说明"></textarea>|
|引导说明<p style="color:#666666;font-size:0.8rem;margin-top:0;margin-top:0;max-width:200px;word-wrap:break-word;">是否做好了相应的引导提示</p>|<input type="checkbox" name="guide" value="guidance">&nbsp;满足需求<br><div style="margin:-0.6rem;">&nbsp;</div><textarea name="textarea" style="border-color:#cccccc;border-radius:2px;" rows="6" cols="40"  placeholder="如有问题请说明"></textarea>|
|表单设计<p style="color:#666666;font-size:0.8rem;margin-top:0;margin-top:0;max-width:200px;word-wrap:break-word;">是否设计好了各种状态（等待\加载\错误提醒\引导etc），是否考虑了不同极限情况</p>|<input type="checkbox" name="form" value="form_design">&nbsp;满足需求<br><div style="margin:-0.6rem;">&nbsp;</div><textarea name="textarea" style="border-color:#cccccc;border-radius:2px;" rows="6" cols="40"  placeholder="如有问题请说明"></textarea>|

## 2. 操作体验和动效

|条件|场景1|
|:---|:---|
|可点击区域<p style="color:#666666;font-size:0.8rem;margin-top:0;max-width:200px;word-wrap:break-word;">点击区域的大小是否满足规范</p>|<input type="checkbox" name="tappable" value="size_tap_area">&nbsp;满足需求<br><div style="margin:-0.6rem;">&nbsp;</div><textarea name="textarea" style="border-color:#cccccc;border-radius:2px;" rows="6" cols="40"  placeholder="如有问题请说明"></textarea>|
|滑动\滚动流畅度<p style="color:#666666;font-size:0.8rem;margin-top:0;max-width:200px;word-wrap:break-word;">是否有弹性，是否自然，有否卡顿</p>|<input type="checkbox" name="scroll" value="scroll_effect">&nbsp;满足需求<br><div style="margin:-0.6rem;">&nbsp;</div><textarea name="textarea" style="border-color:#cccccc;border-radius:2px;" rows="6" cols="40"  placeholder="如有问题请说明"></textarea>|
|动效部分<p style="color:#666666;font-size:0.8rem;margin-top:0;max-width:200px;word-wrap:break-word;">是否流畅，有否拖沓，是否有意义</p>|<input type="checkbox" name="motion" value="meaningful_motion_design">&nbsp;满足需求<br><div style="margin:-0.6rem;">&nbsp;</div><textarea name="textarea" style="border-color:#cccccc;border-radius:2px;" rows="6" cols="40"  placeholder="如有问题请说明"></textarea>|

## 3. 视觉实现

|条件|场景1|
|:---|:---|
|布局<p style="color:#666666;font-size:0.8rem;margin-top:0;max-width:200px;word-wrap:break-word;">整体内容布局是否实现正确</p>|<input type="checkbox" name="visual" value="layout">&nbsp;满足需求<br><div style="margin:-0.6rem;">&nbsp;</div><textarea name="textarea" style="border-color:#cccccc;border-radius:2px;" rows="6" cols="40"  placeholder="如有问题请说明"></textarea>|
|间距<p style="color:#666666;font-size:0.8rem;margin-top:0;max-width:200px;word-wrap:break-word;">上下间距和左右间距</p>|<input type="checkbox" name="visual" value="spacing">&nbsp;满足需求<br><div style="margin:-0.6rem;">&nbsp;</div><textarea name="textarea" style="border-color:#cccccc;border-radius:2px;" rows="6" cols="40"  placeholder="如有问题请说明"></textarea>|
|对齐<p style="color:#666666;font-size:0.8rem;margin-top:0;max-width:200px;word-wrap:break-word;">各元素的对齐，icon\图片\文字\按钮\页面</p>|<input type="checkbox" name="visual" value="alignment">&nbsp;满足需求<br><div style="margin:-0.6rem;">&nbsp;</div><textarea name="textarea" style="border-color:#cccccc;border-radius:2px;" rows="6" cols="40"  placeholder="如有问题请说明"></textarea>|
|字体<p style="color:#666666;font-size:0.8rem;margin-top:0;max-width:200px;word-wrap:break-word;">字体\字号\颜色\字间距\行间距\段间距</p>|<input type="checkbox" name="visual" value="fonts">&nbsp;满足需求<br><div style="margin:-0.6rem;">&nbsp;</div><textarea name="textarea" style="border-color:#cccccc;border-radius:2px;" rows="6" cols="40"  placeholder="如有问题请说明"></textarea>|
|颜色<p style="color:#666666;font-size:0.8rem;margin-top:0;max-width:200px;word-wrap:break-word;">是否和视觉稿或规范一致</p>|<input type="checkbox" name="visual" value="color">&nbsp;满足需求<br><div style="margin:-0.6rem;">&nbsp;</div><textarea name="textarea" style="border-color:#cccccc;border-radius:2px;" rows="6" cols="40"  placeholder="如有问题请说明"></textarea>|
|图形元素<p style="color:#666666;font-size:0.8rem;margin-top:0;max-width:200px;word-wrap:break-word;">icon\图片等尺寸、位置、颜色、失真、占位符</p>|<input type="checkbox" name="visual" value="image">&nbsp;满足需求<br><div style="margin:-0.6rem;">&nbsp;</div><textarea name="textarea" style="border-color:#cccccc;border-radius:2px;" rows="6" cols="40"  placeholder="如有问题请说明"></textarea>|
|控件一致性<p style="color:#666666;font-size:0.8rem;margin-top:0;max-width:200px;word-wrap:break-word;">需求设计和平台内的整体保持统一Consistency</p>|<input type="checkbox" name="visual" value="image">&nbsp;满足需求<br><div style="margin:-0.6rem;">&nbsp;</div><textarea name="textarea" style="border-color:#cccccc;border-radius:2px;" rows="6" cols="40"  placeholder="如有问题请说明"></textarea>|
|空置页面<p style="color:#666666;font-size:0.8rem;margin-top:0;max-width:200px;word-wrap:break-word;">即用户在页面中没有生成任何内容，如何说明并引导</p>|<input type="checkbox" name="visual" value="blank_page">&nbsp;满足需求<br><div style="margin:-0.6rem;">&nbsp;</div><textarea name="textarea" style="border-color:#cccccc;border-radius:2px;" rows="6" cols="40"  placeholder="如有问题请说明"></textarea>|
|极端 Edgy Cases<p style="color:#666666;font-size:0.8rem;margin-top:0;max-width:200px;word-wrap:break-word;">页面内容是否做好了极端情况的承载，为不同分辨率设置好极值</p>|<input type="checkbox" name="visual" value="edgy_case">&nbsp;满足需求<br><div style="margin:-0.6rem;">&nbsp;</div><textarea name="textarea" style="border-color:#cccccc;border-radius:2px;" rows="6" cols="40"  placeholder="如有问题请说明"></textarea>|

## 4. 特殊情况

- 加载 Loading 
- 错误/失败 Error
- 空白 Empty
- 部分展示 Partial
- 弱网 Poor Network

|状态|条件|场景1|
|:---|:---|:---|
|加载|加载刷新机制<p><ul style="color:#666666;font-size:0.8rem;margin-top:-0.5rem;max-width:200px;word-wrap:break-word;"><li >前端机制：自动刷新加载，用户手动刷新加载；</li><li>交互和展示：下拉加载顶部loading还是toast展示；</li><li>场景：有缓存和无缓存</li></ul></p>|<input type="checkbox" name="cases" value="loading">&nbsp;满足需求<br><div style="margin:-0.6rem;">&nbsp;</div><textarea name="textarea" style="border-color:#cccccc;border-radius:2px;" rows="6" cols="40"  placeholder="如有问题请说明"></textarea>|
|加载|加载顺序<p style="color:#666666;font-size:0.8rem;margin-top:0;max-width:200px;word-wrap:break-word;">页面的加载顺序，包括在有缓存和无缓存情况下的加载顺序</p>|<input type="checkbox" name="loading" value="loading_order">&nbsp;满足需求<br><div style="margin:-0.6rem;">&nbsp;</div><textarea name="textarea" style="border-color:#cccccc;border-radius:2px;" rows="6" cols="40"  placeholder="如有问题请说明"></textarea>|
|加载/部分展示|占位符<p style="color:#666666;font-size:0.8rem;margin-top:0;max-width:200px;word-wrap:break-word;">包括数据无法加载时的展示和加载中的中间状态占位符</p>|<input type="checkbox" name="loading" value="placeholder">&nbsp;满足需求<br><div style="margin:-0.6rem;">&nbsp;</div><textarea name="textarea" style="border-color:#cccccc;border-radius:2px;" rows="6" cols="40"  placeholder="如有问题请说明"></textarea>|
|加载|列表加载<p style="color:#666666;font-size:0.8rem;margin-top:0;max-width:200px;word-wrap:break-word;">包括数据的缓存\列表加载的不同状态（成功、失败、中间）\部分数据接口异常</p>|<input type="checkbox" name="loading" value="list_loading">&nbsp;满足需求<br><div style="margin:-0.6rem;">&nbsp;</div><textarea name="textarea" style="border-color:#cccccc;border-radius:2px;" rows="6" cols="40"  placeholder="如有问题请说明"></textarea>|
|弱网|有缓存时<p style="color:#666666;font-size:0.8rem;margin-top:0;max-width:200px;word-wrap:break-word;">整体如何提示告知</p>|<input type="checkbox" name="poor_network" value="with_cache">&nbsp;满足需求<br><div style="margin:-0.6rem;">&nbsp;</div><textarea name="textarea" style="border-color:#cccccc;border-radius:2px;" rows="6" cols="40"  placeholder="如有问题请说明"></textarea>|
|弱网|无缓存时<p style="color:#666666;font-size:0.8rem;margin-top:0;max-width:200px;word-wrap:break-word;">整体如何提示告知</p>|<input type="checkbox" name="poor_network" value="no-cache">&nbsp;满足需求<br><div style="margin:-0.6rem;">&nbsp;</div><textarea name="textarea" style="border-color:#cccccc;border-radius:2px;" rows="6" cols="40"  placeholder="如有问题请说明"></textarea>|
|错误/失败|有缓存时<p style="color:#666666;font-size:0.8rem;margin-top:0;max-width:200px;word-wrap:break-word;">如何展示的，是否统一</p>|<input type="checkbox" name="error" value="with_cache">&nbsp;满足需求<br><div style="margin:-0.6rem;">&nbsp;</div><textarea name="textarea" style="border-color:#cccccc;border-radius:2px;" rows="6" cols="40"  placeholder="如有问题请说明"></textarea>|
|错误/失败|无缓存时<p style="color:#666666;font-size:0.8rem;margin-top:0;max-width:200px;word-wrap:break-word;">如何展示的，是否统一</p>|<input type="checkbox" name="error" value="no_cache">&nbsp;满足需求<br><div style="margin:-0.6rem;">&nbsp;</div><textarea name="textarea" style="border-color:#cccccc;border-radius:2px;" rows="6" cols="40"  placeholder="如有问题请说明"></textarea>|
|错误/失败|部分接口异常<p style="color:#666666;font-size:0.8rem;margin-top:0;max-width:200px;word-wrap:break-word;">如何展示的，是否统一</p>|<input type="checkbox" name="error" value="api_fail">&nbsp;满足需求<br><div style="margin:-0.6rem;">&nbsp;</div><textarea name="textarea" style="border-color:#cccccc;border-radius:2px;" rows="6" cols="40"  placeholder="如有问题请说明"></textarea>|
|错误/失败|404<p style="color:#666666;font-size:0.8rem;margin-top:0;max-width:200px;word-wrap:break-word;">前端错误（服务器找不到页面）</p>|<input type="checkbox" name="error" value="web_404">&nbsp;满足需求<br><div style="margin:-0.6rem;">&nbsp;</div><textarea name="textarea" style="border-color:#cccccc;border-radius:2px;" rows="6" cols="40"  placeholder="如有问题请说明"></textarea>|
|<svg xmlns="http://www.w3.org/2000/svg" width="8" height="8" viewBox="0 0 8 8"><circle cx="4" cy="4" r="4" fill="#D72929" fill-rule="evenodd"/></svg>&nbsp;错误/失败|500<p style="color:#666666;font-size:0.8rem;margin-top:0;max-width:200px;word-wrap:break-word;">前端错误（服务器内部错误）</p>|<input type="checkbox" name="erro" value="web_500">&nbsp;满足需求<br><div style="margin:-0.6rem;">&nbsp;</div><textarea name="textarea" style="border-color:#cccccc;border-radius:2px;" rows="6" cols="40"  placeholder="如有问题请说明"></textarea>|
|错误/失败|502<p style="color:#666666;font-size:0.8rem;margin-top:0;max-width:200px;word-wrap:break-word;">前端错误（服务器暂不可用）</p>|<input type="checkbox" name="error" value="web_502">&nbsp;满足需求<br><div style="margin:-0.6rem;">&nbsp;</div><textarea name="textarea" style="border-color:#cccccc;border-radius:2px;" rows="6" cols="40"  placeholder="如有问题请说明"></textarea>|
|错误/失败|操作错误<p style="color:#666666;font-size:0.8rem;margin-top:0;max-width:200px;word-wrap:break-word;">点击进行操作错误时的报错机制</p>|<input type="checkbox" name="error" value="control_mistake">&nbsp;满足需求<br><div style="margin:-0.6rem;">&nbsp;</div><textarea name="textarea" style="border-color:#cccccc;border-radius:2px;" rows="6" cols="40"  placeholder="如有问题请说明"></textarea>|
|空白|数据为空<p style="color:#666666;font-size:0.8rem;margin-top:0;max-width:200px;word-wrap:break-word;">当前页面的接口无法拉取任何数据，页面展示为空时候的显示方式</p>|<input type="checkbox" name="empty" value="api_empty">&nbsp;满足需求<br><div style="margin:-0.6rem;">&nbsp;</div><textarea name="textarea" style="border-color:#cccccc;border-radius:2px;" rows="6" cols="40"  placeholder="如有问题请说明"></textarea>|


