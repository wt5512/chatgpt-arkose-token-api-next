# chatgpt-arkose-token-api-next
chatgpt-arkose-token-api-next
发送GPT-4对话需要Arkose Token作为参数，本接口专门提供Arkose Token获取


## 2024-02-02更新： 
### 步骤

第一步：**打开页面 https://app.westpaas.com/loginByQr/  获取api权限**

第二步：**调用下面接口**

```
curl --location --request POST 'https://app.westpaas.com/BaseService/api/Gpt/UseGptArkoseBatch?count=1' \
--header 'Authorization: Bearer [第一步获取的token]'
```

如果需要帮助请联系wt5512@163.com




