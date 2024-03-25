# Rainyun_AutoSignIn
[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2FIcyBlue17%2FRainyun_AutoSignIn.svg?type=shield)](https://app.fossa.com/projects/git%2Bgithub.com%2FIcyBlue17%2FRainyun_AutoSignIn?ref=badge_shield)  [![每日签到](https://github.com/IcyBlue17/Rainyun_AutoSignIn/actions/workflows/main.yml/badge.svg)](https://github.com/IcyBlue17/Rainyun_AutoSignIn/actions/workflows/main.yml) 
[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2FIcyBlue17%2FRainyun_AutoSignIn.svg?type=shield&issueType=security)](https://app.fossa.com/projects/git%2Bgithub.com%2FIcyBlue17%2FRainyun_AutoSignIn?ref=badge_shield&issueType=security)

自动签到脚本for雨云 ，提供shell文件/Github Action两种方式

## 运行Shell文件自动签到（不推荐，好久没更新了）

```shell
curl -s https://raw.githubusercontent.com/IcyBlue17/Rainyun_AutoSignIn/main/AutoSignin.sh | sh
```
## 使用Github Action自动签到（推荐）  
1. Fork此仓库
2. 在你自己fork的仓库的Settings - Secrets and variables - Actions - Repository secrets中创建一个名为RAINYUN_API_KEY的Repository secret，值为你获取的雨云apikey。
3. 为这个仓库启用Github Actions。然后运行一次测试。如果返回"未达成条件"，或者"任务成功"为正确配置。此后这个workflow将定时执行。如果返回需要登录，请检查你的api密钥是否填写在了正确的位置，你是否正确填写apikey。



# 许可  

[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2FIcyBlue17%2FRainyun_AutoSignIn.svg?type=large&issueType=license)](https://app.fossa.com/projects/git%2Bgithub.com%2FIcyBlue17%2FRainyun_AutoSignIn?ref=badge_large&issueType=license)  

  
## 待办  
- 一键配置时间
  
- 随机时间
  
- 一键卸载
  
# 注意:因本人问题目前这个脚本不带卸载功能，如果你需要卸载请手动删除计划任务和计划脚本。我将很快更新。😭


