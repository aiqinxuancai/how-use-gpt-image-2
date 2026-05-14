# 教你使用gpt-image-2

## 常用转发站地址

**请按喜好自行挑选，充值不要充多，够用就行，密钥请在对应的转发站控制台中生成**

[鹅站](https://cubence.com/)：（0.1/次）**已验证可用**

```html
API地址：https://api-dmit.cubence.com/v1/
```

[right](https://right.codes/)：（0.04/次 1k 、0.13/次 4k）**已验证可用** 

```html
API地址：https://right.codes/draw/
```

[老农](https://www.packyapi.com/)：（0.04/次） **已验证可用 可以4K 推荐！**

```html
API地址：https://www.packyapi.com/   **在gpt-image-playground配置中要开base64**
```

[鸡站](https://api.ikuncode.cc/)：（0.06/次） **已验证可用（不稳定）**

```html
API地址：https://api.ikuncode.cc/
```

## 方式1，使用专为gpt-image-2设计的页面

访问 [https://gpt-image-playground.cooksleep.dev/](https://gpt-image-playground.cooksleep.dev/) ，该项目的key都存储在前端，不存在丢失key风险

进入后按照上面提供的转发站API地址填写API URL

<img width="794" height="637" alt="image" src="https://github.com/user-attachments/assets/09b0f886-d7c4-4322-8174-9df62a34ee16" />

填写完成后直接在下面输入提示词生成图片

<img width="1275" height="911" alt="image" src="https://github.com/user-attachments/assets/4da2e201-1743-4cae-9027-afa167b8084f" />

也可查看生成详情并进行编辑

<img width="926" height="652" alt="image" src="https://github.com/user-attachments/assets/dff59ef3-1f90-4b84-a8f1-514c6d5f2a31" />

---

## 方式2：使用Cherry Studio

有明显缺点，更新慢，不支持4k设置

下载Cherry Studio，并安装：[https://www.cherry-ai.com/download](https://www.cherry-ai.com/download)

在设置中找到NewAPI，或者点击“添加”按钮，供应商类型选择NewAPI来新建

![image.png](image%203.png)

在模型的地方点击**加号**添加一个新模型

![image.png](image%204.png)

模型id写**gpt-image-2**，端点类型选**图像生成（OprnAI）**即可。

![image.png](image%205.png)

回到Cherry，点击加号，打开绘画

![image.png](image%206.png)

选择New API或刚才新建的提供商，以及刚才添加的模型gpt-image-2，就可以使用了

![image.png](image%207.png)
