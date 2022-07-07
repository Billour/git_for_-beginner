# git_for_beginner

    
*重點: 2020年 Github 把 branch "master" 預設改為 "main" ，這樣造成 git  在你的本機電腦上的branch是 "master"，兩者名稱不同，會造成衝突。  
*一個全新的 git 一定要有檔案才有辨法上傳至 github 這是規定。  
<br/> 
Git 常用指令  
Bath  
初始化「資料夾內」所有的檔案  
```  
git init  
```  
--------  
 
新增「資料夾內」的「所有檔案」至git  
```  
git add .  
```  
請記得 是 git (空白) add (空白) .     最後一個是 "."= 點  
--------  
<br/>  

建立版本備註commit 備註。
```  
git commit -m "first commit"  
```    
--------  
<br/>  
  
  
提交資料  至「本機端 git 」(local git) -u   
*如果有版本衝突時會提醒  
```  
git push -u origin master  
```    
--------  
<br/>    
  
提交資料  至「本機端 git 」(local git) -f  
*如果有版本衝突時「不會」提醒  
```  
git push -f origin master  
```   
--------  
<br/>  

下載資料
```  
git pull origin master  
```  
--------  
<br/>  

換host 位置  
```  
git pull --rebase origin master  
```  
--------  
<br/>  

查詢現在正在那個分支
```  
git branch --list  
```  
--------  
<br/>  
