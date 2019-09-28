@ECHO OFF&PUSHD %~DP0 &TITLE 再见云课堂 by MBRjun
mode con cols=50 lines=30
color 1F

:Lis
@ echo.        最终用户许可条款            最后更新时间：
@ echo.      ━━━━━━━━━━━━━━━━━            2019/9/28
@ echo.   Ending User License Terms
@ echo. 
@ echo.
@ echo. 这是一份法律性资料。
@ echo.
@ echo. 这是一款开源软件，源码发布在GitHub
@ echo. 上，任何人可以直接商用，但是必须注
@ echo. 明原作者为：MBRjun。如果不注明，保
@ echo. 留起诉权力。
@ echo.
@ echo. 本软件完全免费，软件无内购，如果你花
@ echo. 钱购买了该软件，表示你被骗了，请联系
@ echo. 作者。
@ echo.
@ echo.
@ echo. 作者QQ:3469077282
@ echo. 作者B站:411515003（数码尝鲜MBR）
@ echo.
@ echo.
@ echo.
@ echo.
@ echo.
@ echo.
@ echo.
@ echo.
@ echo.
@ echo.
set /p tk= 我不接受(E)                  我接受(N)
if /i "%tk%"=="N" Goto Menu
if /i "%tk%"=="E" Goto E
goto Lis
:E
exit
goto Lis
:Menu
Cls
color 1F
@ echo.
@ echo.　　　　　　 ┢ 主菜单 ┦
@ echo.      ━━━━━━━━━━━━━━━━━
@ echo.     ┃再见云课堂！按1
@ echo.      ━━━━━━━━━━━━━━━━━
@ echo.     ┃给作者B站充电 按2       
@ echo.      ━━━━━━━━━━━━━━━━━
@ echo.
@ echo.
@ echo.      MBRjun 版权所有
@ echo.
@ echo.
set /p xj= 敲数，回车：
if /i "%xj%"=="1" Goto yun
if /i "%xj%"=="2" Goto bili
:error
cls
color 4f
echo.
echo. =  //
echo.     =
echo. =  \\
echo. 遇到一个致命错误，
echo. 正在自动修复。
echo.
echo. 按下 Control-C 退出自动修复
echo.
echo.
echo.
echo.
echo.
echo.
echo.
echo.
echo.
echo.
echo.
echo.
echo.
echo.
echo.
echo.
echo.
echo.
echo.
echo.
systeminfo > bugreport.txt
goto menu
:yun
echo.
echo.
echo 正在检查环境，请等待10秒钟
systeminfo
ping www.baidu.com -i 1
cls
echo.
echo 已经成功获得控制权!
echo.请保持此窗口最小化即可继续
echo.出现错误属于正常现象！
echo.
echo.
:l
taskkill -f /im ClassManagerApp.exe
taskkill -f /im ClassManagerCmd.exe
taskkill -f /im RJCStuAppcmd.exe
taskkill -f /im shutdown.exe
cls
echo.
echo 已经成功获得控制权!
echo.请保持此窗口最小化即可继续
echo.出现错误属于正常现象！
echo.
echo.
goto l
:bili
explorer "https://space.bilibili.com/411515003"
goto menu
pause
goto menu
