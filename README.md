# xlua-framework-
界面生成脚本 自动生成MVC界面 已经config的界面


说明:
1.工具在Tools/GameUITool 或者Shit+q 可以打开界面

2.UIName   例如 UIMain   会生成对应的脚本名
  FileName 例如 UIMain   会生成对应的文件名

3.选择UILayers 会做为config 的层级

4.只写入Config  不会生成脚本或者文件夹  只修改config中的数据

5.CreateUILuaData 会生成所有数据
  提示
  在UIConfig.lua中 添加--AppendCode  
  local UIModule = {
	-- 模块 = 模块配置表
	UILogin = require "UI.UILogin.UILoginConfig",
	--AppendCode  
} 
  在UIWindowNames.lua中 添加--AppendCode  
  local UIWindowNames = {
  -- 登陆模块
	UILogin = "UILogin",
	UILoginServer = "UILoginServer",
	--AppendCode  
  
6.创建WrapItem时候 文件夹名一定要填写的 例如UIMain
   
  
  
