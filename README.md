# autogpt-
全网最全最简单，无需运行虚拟机，无需编码无需部署本地，小白也能使用autogpt

## 保姆级的演示过程，一步一步教你完成autogpt的安装使用

安装前准备：
一个能够使用的chatgpt账号

1.点击访问[autogpt-stable](https://github.com/OnebugIS/Auto-GPT/tree/stable)

2.把浏览器中的 `github.com` 改为 `gitpod.io/#`，注册gitpod

<img width="1275" alt="image" src="https://user-images.githubusercontent.com/31435789/234505278-fe7aead2-d9a4-4d31-9547-9c5caef74912.png">

出现这个页面后

<img width="647" alt="image" src="https://user-images.githubusercontent.com/31435789/234502273-1cdb1c1c-44be-46ae-9ed1-34f9fc807482.png">

<img width="734" alt="image" src="https://user-images.githubusercontent.com/31435789/234505736-ec44f6e9-3130-4e57-8b5e-be7554abe045.png">

3.这个时候会自动安装运行程序

<img width="1564" alt="image" src="https://user-images.githubusercontent.com/31435789/234506199-4409b80e-134e-476a-9b97-50d06f1e1fea.png">

4.点击`master`切换 `stable`分支

<img width="1211" alt="image" src="https://user-images.githubusercontent.com/31435789/234507161-d283ec0c-6437-46d7-9914-55cccebbd5e5.png">

5.找到`.env.template`文件，改名为`.env`

![image](https://user-images.githubusercontent.com/31435789/234507681-dd16d832-2eb4-452e-a946-ecb543d683bb.png)

6.点击链接 [获取chat-gpt的api-key](https://platform.openai.com/account/api-keys)，并将获取到的key复制到OPENAI_API_KEY

![image](https://user-images.githubusercontent.com/31435789/234507892-44203f0d-dcf3-4a35-8908-3b336f924c32.png)

7.点击链接申请 [pinecone api-key](https://app.pinecone.io/organizations/-NTEv1ONYkoH6k5ZbBYj/projects/asia-northeast1-gcp:f0113ff/keys)，并将获取的key复制到

  ![image](https://user-images.githubusercontent.com/31435789/234510537-67ecc9da-3326-4f1f-b29d-1c746b20c4bf.png)

8.如果你想要autogpt自动进行网络搜索还需要配置谷歌浏览器的api，[点击链接申请账户](https://console.cloud.google.com/welcome?project=trans-envoy-384906)

![image](https://user-images.githubusercontent.com/31435789/234516871-69cabc35-1924-472f-9381-5cced308cf53.png)


9.[点击申请谷歌浏览器的api](https://console.cloud.google.com/apis/dashboard)

![image](https://user-images.githubusercontent.com/31435789/234516985-14b155a7-6ba3-4026-8f9f-4ef9759d1aa7.png)

点击试用api

![image](https://user-images.githubusercontent.com/31435789/234517186-1002a4f3-5801-492e-b366-135fe49c5694.png)

10.[点击创建凭据](https://console.cloud.google.com/apis/credentials?project=trans-envoy-384906)
把生成的api密钥放到

![image](https://user-images.githubusercontent.com/31435789/234519185-bb69e102-4634-46e4-8958-7840aa6082d0.png)
记得把前面的#去掉

11.[点击链接获取搜索引擎id](https://programmablesearchengine.google.com/controlpanel/all)

![image](https://user-images.githubusercontent.com/31435789/234519789-9fb0531c-ab8b-462b-9f67-a3787f432f2d.png)

把搜索引擎id复制到 CUSTOM_SEARCH_ENGINE_ID

![image](https://user-images.githubusercontent.com/31435789/234519970-092874d9-fa83-4fb1-9619-e77050139c29.png)


12.保存文件，直接把`sun.sh`文件拖到终端，回车

![image](https://user-images.githubusercontent.com/31435789/234520904-985aaecf-2f7f-458e-8887-168654bbf1c4.png)

13.当出现以下内容，表示autogpt安装完成

![image](https://user-images.githubusercontent.com/31435789/234521087-ffd0a90d-8d7f-4cee-9074-2d6ac5db664a.png)

