# Deutsch Sprint · 德语冲刺 🇩🇪

为零基础中文学习者设计的德语 A1 起步学习 App，加入德国日常生活和 Ausbildung（双元制学徒）场景。

## 在线使用
GitHub Pages（启用后）：https://qifangming2018-eng.github.io/deutsch-sprint-a1/

## 学习内容
- 24 个主题、148 条核心德语表达
- 先听说、再认读、逐步过渡到拼写
- 德语系统朗读（点击喇叭），可调播放速度
- 听力选择、阅读、口语自测、简短写作
- 根据记忆难度安排复习；本地进度记录及导入/导出

## 发布方法（只需一次）
1. GitHub 仓库 → **Settings** → **Pages**
2. **Build and deployment** → **Source**：选择 `Deploy from a branch`
3. **Branch**：选择 `main` 和 `/(root)`，点击 **Save**
4. 等待 GitHub Pages 构建完成，打开上面的在线网址
5. 在 Android Chrome 浏览器右上角菜单中选择 **添加到主屏幕** 或 **安装应用**

静态网页托管无需付费服务器。本仓库根目录 `index.html` 已集成全部 HTML/CSS/JavaScript，无需构建。

## 重要限制
- 发音基于浏览器/Web Speech API，设备没有可用德语发音人时可能无法播放；首次请在 Chrome 上测试。
- 语音识别只判断系统识别到的文字，不是专业发音评分。写作和口语专项练习中的自评也不代表通过考试。
- 学习记录存在当前浏览器的本地存储，换设备、清除浏览数据可能丢失。建议定期导出 JSON 备份，**不要把个人进度备份提交到公开 GitHub 仓库**。
- 此版本是入门 MVP，完成 24 个单元不等于通过官方德语 A1；还需要更丰富的听力、口语和写作训练，并结合歌德 A1 模拟考试评估。

## 技术
原生 HTML/CSS/JavaScript + Web Speech API + localStorage + Service Worker，支持 HTTPS 下的离线缓存。安装体验及离线语音是否可用取决于浏览器和设备支持。
