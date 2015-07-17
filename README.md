# user_api 
<hr>

## 使用方法  ##
主要功能為四大項，網址上輸入下方網址就可以路由到對應的功能上。             


                           http://renhao1.goodideascampus.com/(function) 
                       
                       
                       
                       

#### create:

                           http://renhao1.goodideas-campus.com/user/add
          
使用$['post'] name,account,email對應到相應的欄位可以對user資料表進行新增。

#### read:


                           http://renhao1.goodideas-campus.com/users
使用該項路由可將全部的資料以json格式顯現出來。

                           http://renhao1.goodideas-campus.com/users/:id
如果要找單一筆資料，只需要在get後方，輸入id編號，即可呼叫該筆資料

#### update:
                           http://renhao1.goodideas-campus.com/user/update
使用$['post'] id,name,account,email對應到相應的欄位可以對user資料表進行修改。

#### delete:
                           http://renhao1.goodideas-campus.com/user/:id
在id位置輸入主鍵號碼即可對user資料表進行刪除。

****************************************************************************************************************
###### 使用平台:Web

###### 使用語言:PHP

###### 使用套件:Slim,idiorm
**********************************************************************


###### 作者:renhao
