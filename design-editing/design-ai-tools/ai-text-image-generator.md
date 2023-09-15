> AI图像生成
>
> TEXT TO IMAGE

## Stable Diffusion

Stable Diffusion是一个文转图的模型，其使用了CLIP ViT-L/14文本编码器，基于Latent Diffusion Model（LDM）, 能够通过文本提示调整模型。它在运行时将成像过程分离成“扩散 （diffusion）”的过程——从有噪声的情况开始，逐渐改善图像，直到完全没有噪声，逐步接近所提供的文本描述。  已权重开源。

Github：https://github.com/CompVis/stable-diffusion

Github UI： https://github.com/AUTOMATIC1111/stable-diffusion-webui

Stable Diffusion Prompt Book: https://openart.ai/promptbook

操作步骤：

1. Github搜索table diffusion Colab，找到大佬的地址， 比如： https://github.com/woctezuma/stable-diffusion-colab， 点击 Open In Colab,
   
2. 运行项目
   第一段代码安装依赖。
   第二段代码，显示输入tokens
   
   可下载ipynb在自己电脑上运行，https://colab.research.google.com/github/woctezuma/stable-diffusion-colab/blob/main/stable_diffusion.ipynb
   
3. 在这个网站注册https://huggingface.co/， 并新建tokens
    在这个地址取得许可 https://huggingface.co/CompVis/stable-diffusion-v1-4
    然后复制tokens到Colab 

4. 运行代码第三段下载权重。

5. 运行代码第四段输入相关文字得到图像。

6. 使用Stable Diffusion秋叶整合包

**参考视频：**

AI 文字生成图片（Stable Diffusion）22.8

https://www.bilibili.com/video/BV1Hd4y197hF/

**参考网站：**

在线作画(Google账号登录， 每天免费一次)：https://chilloutai.com/ 、 https://chilloutai.xyz/

**模型网站：**

civitai : https://civitai.com/

https://models.paomiantv.cn / http://www.liandange.com

**模型：**

LORA：https://chilloutai.com/guofeng

- 墨心 MoXin：https://models.paomiantv.cn/models/Detail?id=12597&modelVersionId=14856 

  https://civitai.com/models/12597/moxin?modelVersionId=14856（需要构图Lora，推荐基础模型为ChilloutMix、国风3.2）

## Stable Diffusion Online

Disco Diffusion：可在Google的corlab上直接部署

https://stablediffusionweb.com/

https://huggingface.co/spaces/stabilityai/stable-diffusion

https://replicate.com/stability-ai/stable-diffusion

Graviti Diffus: https://www.diffus.graviti.com/

## Stable Diffusion Like

https://stability.ai/ (测试地址：https://beta.dreamstudio.ai/home, 大图只支持1024; 展示地址：https://clipdrop.co/tools)

Lexica: 基于Stable Diffusion的在线插画生成, https://lexica.art/

Scribble Diffusion：https://scribblediffusion.com/, 手绘草图转换

Stable Doodle: https://clipdrop.co/stable-doodle, 手绘草图转换

## Midjourney

Midjourney能够根据用户的提示生成图像。善于适应实际的艺术风格，创造出用户想要的任何效果组合的图像。擅长环境效果，特别是幻想和科幻场景，比如就像游戏的艺术效果, 需下载注册Discord。

> Midjourney is an independent research lab exploring new mediums of thought and expanding the imaginative powers of the human species.

官网: https://www.midjourney.com/

- Once your trial has ended, become a paid membership with /subscribe or go to https://www.midjourney.com/account
- For detailed information and how-to go to  https://docs.midjourney.com/
- To see your creations sign in at: https://midjourney.com/

网站状态：https://status.midjourney.com/

最新版本：Midjourney5，每个新账号免费次数为25,3.31更新， 均要付费

常用指令：

> /setting

Midjourney 学习导航：https://learningprompt.wiki/docs/midjourney-learning-path / http://www.sucaijishi.com/articles-51-435-1.html

MJ Prompt Tool: https://promptfolder.com/midjourney-prompt-helper/

Midjourney 图片示例：https://chilloutai.com/midjourney

## DALL·E 2

OpenAI旗下的一个图片生成软件， 基于CLIP神经网络，注册需海外手机号。

> DALL·E 2 is an AI system that can create realistic images and art from a description in natural language.

官网：https://openai.com/dall-e-2/

扩展知识：How does DALL-E 2 actually work? （https://www.youtube.com/watch?v=F1X4fHzF4mQ）

> 输入的文本被转化为使用神经网络的CLIP文本嵌入。
>
> 使用主成分分析（Principal Component Analysis）或PCA降低文本嵌入的维度。
>
> 使用文本嵌入创建图像嵌入。
>
> 进入Decoder步骤后，扩散模型被用来将图像嵌入转化为图像。
>
> 图像被从64×64放大到256×256，最后使用卷积神经网络放大到1024×1024。

Generrated:  基于DALL·E 2的图片生成指令语句

https://generrated.com/

## Deepai

官网：https://deepai.org/machine-learning-model/text2img

## AI绘画工具

AI绘画搜索：https://www.enterpix.app/

![只需要输入一段文字描述、或者是上传一张图片，AI绘画软件就能为你快速生成一张绘画，水墨风，赛博朋克风，平面插画风，油画风，素描，工笔，漫画，末世废土风，抽象的，写意的、高写实的](https://i0.hdslb.com/bfs/article/5a16068d9e4780ab874fbc9ad80993c7d1685072.png)

1. Photosonic： Writesonic推出的AI艺术插画生成工具， https://writesonic.com/photosonic-ai-art-generator

2. Dream AI：https://dream.ai/create （基于 AI 生成不同风格的绘画类作品，无需登陆，免费试用，但只有一幅图）

   Are you team Barbie or Oppenheimer?：https://dream.ai/barbie

3. NightCafe Creator： https://creator.nightcafe.studio/

   能ai绘画软件， 有软件版

4. Deep Dream Generator：https://deepdreamgenerator.com/，

   描述同上

5. StarryAI： https://starryai.com/

   Generate art 🎨 simply by describing what you want to see
   and our Artificial Intelligence transforms your words into art.

   支持安卓和IOS

6. getimg.ai：在线AI图像和插画创作工具， https://getimg.ai/

7. Astria：可定制的人工智能图像生成，https://www.astria.ai/

8. Runaway： https://runwayml.com/

   支持Gen-2 Gen-1 Text to Image Image to Image
   Infinite Image Inpainting Frame Interpolation Custom AI Training

9. Pisco：官网：https://picso.ai/， 偏黑暗、赛博朋克、末世废土风格更强烈一些

10. NUWA: 微软出品的AI绘画工具，暂不开放使用

   https://nuwa-infinity.microsoft.com/#/NUWAInfinity

   Bing Image Creator:  https://cn.bing.com/create

11. Nijijourney: 绘制任何二次元风格的绘画！这是一个由 Spellbrush 与 Midjourney 所共同设计开发的魔法般工具。无论您是在寻找可爱的Q版角色还是充满动感的动作场景，niji・journey 都能将您的想象变为现实

    https://nijijourney.com/zh/

12. 文心一格: 百度推出的AI艺术和创意辅助平台

    https://yige.baidu.com/

13. 6pen art: 国内团队出品，输出各种绘画风格

    API: https://fromston.6pen.art/

14. 即时设计AI作画，https://js.design/AI-gallery

15. 目前Fotor, Canva等也支持AI生成， 详情写相关页面

Craiyon: 在线文本到图像生成, https://www.craiyon.com/

万兴爱画: 万兴科技推出的AI生成高品质艺术画工具, https://aigc.wondershare.cn/

Tiamat：国内团队推出的AI艺术画生成工具，https://www.tiamat.world/

Wepik AI: Freepik推出的AI文本到图像的在线生成工具, https://wepik.com/ai-presentations / https://www.freepik.com/ai/image-generator

Vega AI：在线免费AI插画创作平台，支持文生图，图生图，条件生图等多种绘画模式， https://rightbrain.art/

PixCap 3D 工具: https://pixcap.com/

AI Tagging: https://www.pixyle.ai/

> Automatic Tagging of Product Data
> With Rich Fashion Attributes

Artbreeder：创建令人惊叹的插画和艺术，https://www.artbreeder.com/

dreamlike.art：免费在线插画生成工具，https://dreamlike.art/

言之画: AI图像内容创作平台，由出门问问推出, https://paint.mobvoi.com/?ref=ai-bot.cn

无限画千库网: https://588ku.com/ai/wuxianhua/Home

Waifu Labs： 在线AI生成二次元动漫头像，https://waifulabs.com/

BlueWillow：AI图像艺术画生成工具，https://www.bluewillow.ai/

Deep Dream Generator:生成梦幻般的插画图片, https://deepdreamgenerator.com/

Skybox AI: AI生成和合成360°全景图像插画, https://skybox.blockadelabs.com/

行者AI美术:AI图片生成和美术创作工具箱, https://xingzheai.cn/#create

天工巧绘SkyPaint:  免费的AI插画绘制工具，由昆仑万维与奇点智源合作推出,https://sky-paint.singularity-ai.com/index.html#/

Stockimg AI: https://stockimg.ai/

画宇宙: 人工智能AI作画网站, https://creator.nolibox.com/?utm_source=ai-bot.cn

Adobe Firefly:  https://www.adobe.com/sensei/generative-ai/firefly.html

通义万相:  阿里, https://wanxiang.aliyun.com/

网易AI创意工坊: 网易云课堂推出的AI作画平台, https://ke.study.163.com/artWorks/painting

堆友AI反应堆:  阿里旗下堆友推出的多风格AI绘画生成器, https://d.design/ai

秘塔捉捉猫: 秘塔写作猫推出的AI文字到图像生成工具, https://drawdraw.com/?s=aigj

WHEE:  https://www.whee.com/

简单AI: 搜狐最新推出的AI图片生成平台,  https://ai.sohu.com/search

美图AI文生图:  https://design.meitu.com/aigc/text-to-image

造梦日记:  AI一下，妙笔生画,  https://www.printidea.art/

创客贴AI画匠:  https://aiart.chuangkit.com/landingpage

Leonardo.ai: 游戏插画, https://leonardo.ai/

Pix AI: https://pixai.art/

https://pixlr.com/

https://pixilio.ai/

https://convert.leiapix.com/

https://pixia.ai/

https://replicate.com/pixray/text2image

Segement Anything Gui