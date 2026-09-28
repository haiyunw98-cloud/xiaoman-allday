# 小满全天记｜产品界面

[下载 Android APK](https://github.com/haiyunw98-cloud/xiaoman-allday/releases/download/v0.1.2-public/xiaoman-allday-0.1.2-public.apk) · [返回产品介绍](README.md)

本图集展示 v0.1.2-public 的首页、使用偏好及 AI 服务配置。图片由当前版本 Android 控件在测试环境中渲染，非手机实拍；展示首次安装状态，不含私人记录或虚构业务数据。

## 首页与外观

首页集中提供录音控制、日期浏览和内容分类，底部搜索支持历史检索与小满问答。提供奶白薄荷、深蓝夜色两种外观，配置入口统一位于右上角。

<p><img src="assets/ui-v0.1.2/01-home-light.png" alt="浅色首页" width="46%"> <img src="assets/ui-v0.1.2/08-home-navy.png" alt="深蓝首页" width="46%"></p>

## 设置与关注重点

进入右上角齿轮 →「关注重点与使用习惯」，可填写身份背景和用逗号分隔的关注领域，例如项目进度、需求变更、学习笔记。保存后在下一次整理生效，不改写旧记录和已经确认的待办。定时停止默认关闭，开启后可选择停止时间；只自动停止，不会自动开启麦克风。

<p><img src="assets/ui-v0.1.2/05-settings.png" alt="右上角齿轮打开的设置目录" width="46%"> <img src="assets/ui-v0.1.2/06-preferences.png" alt="身份与关注领域设置" width="46%"></p>

## AI 服务配置

选择阿里云百炼、DeepSeek、硅基流动或 OpenAI 预设，填写自己的 API Key 和可调用模型，测试后保存。自定义服务还需填写 HTTPS API 地址，且兼容 OpenAI Chat Completions 接口及所需结构化输出。Key 默认空白；测试会产生少量用量，模型权限、额度和费用由所选平台决定。

<p><img src="assets/ui-v0.1.2/07-api.png" alt="API 配置页面，密钥为空" width="46%"> <img src="assets/ui-v0.1.2/10-api-platforms.png" alt="支持的平台列表" width="46%"></p>

## 日记、提醒与待办

日记风格可选工作生活综合、工作复盘或生活记录，篇幅可选详细或简洁。默认 21:00 根据已整理信息生成，按今日概览、主题回顾、见闻和后续关注组织；有转写积压时等待处理。授权且存在可写日历时，日记全文写入当天的一条全天日程。

重点自动收录，无需确认。候选待办在 12:30、18:00 重点合并后生成，提供「忽略」「编辑」「加入待办」；确认后可以延期或完成。每日未完成待办汇总默认 09:00 提醒，可调整或关闭。系统后台调度可能延后。图中待办页是尚无候选的首次使用状态，不是生成结果演示。

<p><img src="assets/ui-v0.1.2/09-diary-preferences.png" alt="日记风格与待办偏好" width="46%"> <img src="assets/ui-v0.1.2/04-tasks.png" alt="待办页首次使用状态" width="46%"></p>
