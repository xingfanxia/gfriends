# 女友头像仓库
![TotalNumber](https://img.shields.io/badge/TotalNum-2.86w-Blue.svg)  ![AutoUpdate](https://img.shields.io/badge/AutoUpdate-2020--6--12-green.svg)<br>
媒体服务器演员头像仓库<br>推荐搭配任一刮削整理项目 [JAVSDT](https://github.com/junerain123/javsdt "JAVSDT")、[JAVOneStop](https://github.com/ddd354/JAVOneStop "JAVOneStop")、[AVDC](https://github.com/yoshiko2/AV_Data_Capture "AV Data Capture")([GUI](https://github.com/moyy996/AVDC "AVDC GUI"))、[JavScraper](https://github.com/JavScraper/Emby.Plugins.JavScraper "JavScraper") 及 Emby、Jellyfin、Plex 等媒体服务器使用。

## 快速开始
对于一般用户来说，可以通过这些工具方便的导入头像。

### Emby / Jellyfin



无需下载本仓库的女友头像，仅需下载 [Gfriends Inputer 一键导入工具](https://github.com/xinxin8816/gfriends/releases)，编辑 `Config.ini`文件并运行程序。<br>该工具将自动从本仓库搜索头像并导入你的服务器。



<details>
<summary>或者试试安装插件导入？</summary>
<p>由 JavScraper 提供<p>

无需下载本仓库的女友头像，仅需为你的 Emby / Jellyfin 服务器安装 [JavScraper](https://github.com/JavScraper/Emby.Plugins.JavScraper) 插件。<br>该插件将自动从本仓库搜索头像并导入你的服务器，亦提供了元数据刮削功能。

</details>

### Plex
由 ddd354 提供

无需下载本仓库的女友头像，仅需为你的 Plex 服务器安装 [JAVnfoMoviesImporter](https://github.com/ddd354/JAVnfoMoviesImporter.bundle) 插件。<br>该插件将自动从本仓库搜索头像并导入你的服务器，亦提供了元数据刮削功能。

## 进阶说明
本项目以抓取官方高质量大图为主要目标，头像图片为自动化抓取，部分人工筛选。

`Filetree.json` 为已按质量排序的文件树，可供程序调用搜索。女友仓库不能保证 AI 优化的图片完美无瑕，若您不想获取这些经 AI 优化的图片，只需删除文件树中的 `AI-Fix-` 前缀即可。

### 上传新的演员图片
欢迎提交优质的演员头像图片或写真。不过首先，优质头像应 **尽可能** 满足：

1. 以女友为主体的特写或近景，且足够养眼。
2. 接近 3:2 的长宽比，宽度宜在 300px 以上。

如果您的图片符合上述要求，则可以：

1. 移步至仓库的 [人工存储 HandStorage](https://github.com/xinxin8816/gfriends/tree/master/Content/0-Hand-Storage) 目录，该目录拥有最高优先级，能保证上传的图片被优先使用。
2. 轻击 “Upload files” 按钮，然后上传图片到仓库。在上传等待过程中，随便写一点 “Commit Changes” 说明，比如上传了哪些女友的图片。
3. 轻击 “Commit” 提交然后 “Pull Requests”。在经过审核后，您的美图就可以和大家分享了。

此外，如果您有大量的图片想要上传，则最好使用 Git 命令，也可以提交一个 issue 求助。

### 提交来源网站

首先，该优质网站上的图片除了满足上述要求，还应尽可能满足：每位女友只有一张或少量的图片，以避免二次人工筛选。

如果您有这样的来源网站，那就太完美了~ 您只需提交一个 issue 告诉我地址即可。

### 更新计划
✔ 自动定期抓取新入职女友头像至仓库（仅后述标注 🌟）<br>
✔ 匹配简体中文 / 繁体中文 / 日文姓名<br>
✔ 高斯模糊处理以匹配 Emby 的特殊尺寸（需使用 Gfriends Inputer 导入）<br>
✔ AI 算法放大并优化低分辨率头像（仅后述标注 ➡）

## 图片来源
排序不分前后<br>
标注🌟的图片为原生高质量大图，标注➡的图片为经过 AI 算法放大优化的图片。

### 第三方内容商
| 品牌 | 尺寸 |女友数量|简介|备注|
| :----: | :----: | :----: | :----: | :----: |
| [GRAPHIS](http://graphis.ne.jp/ "GRAPHIS") | 360×508 | 600+ | 著名的美女摄影写真机构 | 🌟 |
| [Juicy Honey](http://juicy-honey.com/ "Juicy Honey") | 640×960 | 30+ | X-City 旗下的写真分支 | 🌟 |
| [LovePop](https://lovepop.net/ "Lovepop") | 384×576 | 70+ | 美少女写真摄影机构 | 🌟 |
| [FANZA](http://dmm.co.jp/ "FANZA") | *inconsistent* | 1.5W+ | DMM官方，仅作为补充 | ➡ *New Add!* |

### 品牌官方
| 品牌 | 尺寸 |女友数量|旗下知名小姐姐|备注|
| :----: | :----: | :----: | :----: | :----: |
| [S1 No. 1 Style](https://www.s1s1s1.com/ "S1 No. 1 Style") | 470×600 |300+|三上悠亜、羽咲みはる、桜羽のどか、架乃ゆら|🌟<br>人气与美形著称|
| [MUTEKI](https://www.mutekimuteki.com/ "MUTEKI") | 640×906|50+|深山あすか、水瀬ちあき、松本菜奈実、夢川エマ|🌟|
| [FaleNO](https://faleno.jp/ "FaleNO") | 1500×2125 |10+|桥本有菜、吉高寧々、美乃すずめ、佐藤ゆか|🌟 <br> U-next 旗下公司|
| [Attackers](https://www.attackers.net/ "Attackers") | 216×270|1000+|明里つむぎ、岬ななみ、二宮ひかり、結城のの|➡432×540|
| [Moodyz](https://www.moodyz.com/ "MOODYZ") | 230×300 |1100+|高桥しょう子、西宫このみ、伊东ちなみ、千早希|➡460×600|
| [Premium](http://www.premium-beauty.com/ "Premium") | 208×276 |100+|樱木凛、星野美优、冬月枫、二宫沙树|➡416×552|
| [Idea Pocket](https://www.ideapocket.com/ "Idea Pocket") | 300×300 |100+|天海つばさ、相沢みなみ、桃乃木かな、希崎ジェシカ|➡600×600|
| [KM Produce](https://www.km-produce.com/ "KM Produce") | 330×330|10+|川上优、麻生岬、麻仓忧、神咲诗织|➡660×660|
| [kawaii*](https://www.kawaiikawaii.jp/ "kawaii*") | 640×896|300+|ひなみちゃん、伊藤舞雪、宇佐木あいか、有栖るる|🌟|
| [Prestige<br>蚊香社](https://www.prestige-av.com/ "Prestige<br>蚊香社") | 119×170|200+|永瀬みなも、有村のぞみ、園田みおん、藤江史帆|绝对美少女制造商<br>➡476×680|
| [未満](http://www.miman.jp/ "未満") |290×390|100+|あやみ旬果、さくらゆら、高岡美鈴、高梨ゆあ|➡580×780|
| [无垢](http://www.muku.tv/ "无垢") |110×70|300+|河南実里、高杉麻里、本橋実来、大島美緒|➡440×280|
| [桃太郎映像](http://www.indies-av.co.jp/ "桃太郎映像") |451×600 | 200+ |宝生リリー、泉りおん、入江愛美、阿部乃みく|🌟<br>专业企划制造商|
| [えむっ娘ラボ](http://www.mko-labo.net/ "えむっ娘ラボ") | 168×191 |200+|有坂深雪、有村のぞみ、笹倉杏、上原亜衣|➡336×382|
| [OPPAI](http://www.oppai-av.com/ "OPPAI") | 312×364 |100+|浜崎真緒、成海さやか、美緒みくる、柊るい|➡624×728|
| [E-BODY](http://www.av-e-body.com/ "E-BODY") | 312×400|500+|Julia、红城まゆ、羽野理沙、蒂亚|➡624×800|
| [Wanz Factory](https://www.wanz-factory.com/ "Wanz Factory") | 280×280 |200+|椎名そら、つぼみ、水野朝陽、浅井ルリ子|➡560×560|
| [Honnaka<br>本中](https://www.honnaka.jp/ "Honnaka<br>本中") | 335×375 |300+|さわきりほ、さくらみゆき、つくしみか、あいだ飛鳥|➡670×750|
| [kira☆kira](https://www.kirakira-av.com/ "kira☆kira") |180×180|10+|加瀬エリナ、水谷心音、霧嶋りお、有村リア|➡360×360|
| [BeFree](https://www.befreebe.com/ "BeFree") | 215×215|100+|つぼみ、浜崎真緒、安藤美奈子、坂口れな|➡430×430|
| [痴女天堂](https://www.bi-av.com/ "痴女天堂") | 300×300|300+|大槻ひびき、沖田杏梨、大浦真奈美、渚みつき|➡600×600|
| [Fitch](https://www.fitch-av.com/ "Fitch") | 300×392|500+|春菜はな、美園和花、月森ゆの、河北はるな|➡600×786|
| [Madonna](https://www.madonna-av.com/ "Madonna") | 230×300|30+|美森けい、谷花紗耶、桜井ゆみ、今井ひまり|➡792×800|
| [溜池ゴロー](http://www.tameikegoro.jp/ "溜池ゴロー") |100×100|500+|めぐり、本田岬、かすみ果穂、さとう遥希|MOODYZ 旗下公司<br>➡400×400|
| [Das!](http://www.dasdas.jp/ "Das!") |280×280|300+|あべみかこ、冴月りん、跡美しゅり、一ノ瀬梓|➡560×560|
| [ラグジュTV](https://seesaawiki.jp/av_neme/d/%A5%E9%A5%B0%A5%B8%A5%E5TV/ "ラグジュTV") |116×236|900+|藤本ゆうり、美園和花、浜崎真緒、あやみ旬果|➡332×472|

## 免责声明
1. 本项目作者旨在学习 Python 后端，提高编程水平。
2. 项目仅用于技术、学术交流，严禁用于商业和其他盈利目的。
3. 请自觉遵守当地法律法规，产生的一切后果由用户自行承担。
4. 头像图片版权归相应网站及演员所属经纪公司所有。
5. 作者保留最终决定权和最终解释权。

若您不同意上述任一条款，请勿直接或间接使用本项目。
