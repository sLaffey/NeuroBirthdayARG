# 线索整理

## 生日会回放

取名太麻烦了叫你 themoon1/m1 吧。

以 b 站 4K 缓存片源下载后分时段提取的所有帧为准，重新整理一下线索。

由于此前依 Web 端解析下载的 1080p 片源整理过，对清晰度要求不高的地方不会更新图源，仅更新帧位置。

### 5:00-6:30

#### 440 帧

![alt text](./images/frame_0221.png)

有二维码，手绘重建后扫描结果为 `themoon`。

![alt text](./images/qrcode1-1.png)

但是除了微信好像别的扫不太出来不知道为什么。

右下角的密文

```
bmfy'x wjfq
bmfy'x kfpj
```

凯撒密码，解密得到 `what's real what's fake`

#### 666 帧

![alt text](./images/frame_0334.png)

有密文，处理一下。

![alt text](./images/frame_0334-1.png)

提取后得到 `4oCc5bey57uP5b6I5pma5LqG77yMYWlyaXPjgILigJ0K4oCc5ZOl5ZOl77yM5ZOl5ZOl77yM5YaN57uZYWlyaXPorrLkuKrmlYXkuovlkKfjgILigJ0K4oCc5aW95ZCn5aW95ZCn77yM5pyA5ZCO5LiA5Liq5ZOm44CC6L+Z5Liq5pWF5LqL55qE5Li76KeS5Lmf5Y+rYWlyaXPvvIzot5/kvaDkuIDmoLflkaLigKbigKbigJ0=`

base64 解码结果：

```
“已经很晚了，airis。”
“哥哥，哥哥，再给airis讲个故事吧。”
“好吧好吧，最后一个哦。这个故事的主角也叫airis，跟你一样呢……”
```

#### 698 帧

![alt text](./images/frame_0349.png)

后面的数字通过之后的画面可以看出是 5、7、9，作为后续三次凯撒密码解密的密钥。

#### 854 帧

![alt text](./images/frame_0428.png)

![alt text](./images/frame_0428-1.png)

背景文字为 `ZVTLAPTLZ H ZVUN APASL PZ TVYL PTWVYAHUA AOHU PAZ SFYPJZ`，凯撒密码破解得到 `SOMETIMES A SONG TITLE IS MORE IMPORTANT THAN ITS LYRICS`。可能是提示我们注意作品名 `themoon`。

#### 886 帧

![alt text](./images/frame_0444.png)

![alt text](./images/frame_0444-1.png)

```
jTX+iZRM08
hYS6Lb7v3Jcwy
YL2cobfHVrITtyja
mDuvqL7Scd35Nf4
H8T1rdYTBMhRZgQm
ST1PF/zmTyE0eNNzcV
nG95h5/sBgN8XRY4ihPP
4chhoFKqkGum0460qwKyoAV8d
EiE9PBrcjeLMaCQD6G7RxuzWr2dLXtC
OGvyNi09J4ZINbfckJDmc0OC7kMWmgsW2xdl7e
Gq/5ozd/lteBIG/748+pGEMvYlMHtULHrIfnthz3AJB/1Oi8hPXFxd
z8OBe0aQP4suMRBGtAYyzIQs3Hk4j2ob5BJxZDBYNVTa+9Ucky+sx
NY0LtAR7HxUTY5rwb+1crYq65OGC9NoN9Zir1UEsZh1WRr/i5yGVBE=
```

暂不清楚解密方法。

#### 892 帧

![alt text](./images/frame_0447.png)

![alt text](./images/frame_0447-1.png)

提取文本 `RO HXD MXW'C DWMNABCJWM BXVN XO CQN ADUN, RC VNJWB HXD FXW'C WNNM RC OXA WXF.`，也是凯撒密码，解密得到 `IF YOU DON'T UNDERSTAND SOME OF THE RULE, IT MEANS YOU WON'T NEED IT FOR NOW.`

#### 1224-1251 帧

闪过了许多密文，推测是同一文本的内容，所以放在一起了。

![alt text](./images/frame_0613.png)

![alt text](./images/frame_0615.png)

![alt text](./images/frame_0617.png)

![alt text](./images/frame_0619.png)

![alt text](./images/frame_0621.png)

![alt text](./images/frame_0623.png)

![alt text](./images/frame_0625.png)

一起处理一下。

![alt text](./images/frame_0613-1.png)

![alt text](./images/frame_0615-1.png)

![alt text](./images/frame_0617-1.png)

![alt text](./images/frame_0619-1.png)

![alt text](./images/frame_0621-1.png)

![alt text](./images/frame_0623-1.png)

![alt text](./images/frame_0625-1.png)

分别提取文本。

- `mANGeI6gaNboS0nCDPvNd4FvxLWeTGiZq2mbbWpMbh hW57Y+iOcyrB1ey7WHgM3Hm28ivlKpcQP0XptpjIA`
- `dwH5fqh5kLeDzgpQTCTyiTO1L9L1kx56hDCuVFHyB bIY5flaUQbJXtBgzoA8SSXhbkiZYXjCCB8rjMo2Il`
- `sYblwpfBbPzVrW1VN4hI/KH86lpZUgSqTUWhgbxwz vMolR3YQqhPSCIUlnVLqzgepFvH01FX+WWlLV5ZJk`
- `WV6vOA9O+PxGJa/IEF48H8WwjZ65gGhE514VxAO2M rRgRw2iu4tDEptQdDmyjm4rb83svitiaTpSqgXbnR`
- `dLLymnsRodt/mt/7UEt1jEFnaL229r7VQO/jg6VNA gizoDa3tFKEDNjGW9VwIRpb/b19aKuKEwJW5wSwe2`
- `4fkehDRGK8L4Z+bVcXrRcl0OgOyZ++cUkbuFK72W6 ljq5E+lRVA8P3ueg5zJBQafdimsrNvPdJao3S6QBX`
- `g2WgNuSXL7EDsx8ntcjvahKGHMurIwGa4Cp1mYZKd hEk7ZoxPT7JQKF+fdgLkU92WYkSCqLqPnTWMedawD`

暂不清楚解密方法。

#### 1252 帧

![alt text](./images/frame_0627.png)

不清楚遮挡的字代表什么。

#### 1454 帧

![alt text](./images/frame_0728.png)

![alt text](./images/frame_0728-1.png)

```
22yxwFV853+9JyqiNU7Hv+HQ7xMPqFvhQ9y7wm54Lc579S8vWYnPnPNXhBv24
MrC9bVL9x5TxpwtYbBzEX23i2pjumCP8Ke57Yx3XuFYxrKhH96QejheeV61rLkvvbe6K
XzxSVKxrCT1SgKMMsiVJksPKYsrYXdLYW4DorNbXETeaQipTYKp6JXy1SiMc1WUAdLS3
Zrn442dozxqpitidUeagikQHGhkaCA7Lefq3HwcPBALghxeRXzwme3evJTKBU1fp2H
nMc2Db5sQQvjASRAUFvwJL17F8PKW3DuSEh3UGxGgPhQdjjWi7rLMdDUjxZr7neF7
tfLLMYqQJkDQbcDiDoYu7CBqi7FCpyucPGVqj6GU+CEoQBEjrpsmVxaTRvPy891cdbxq
BJQoxK2opukAnKNgSdfFv+2gwtdByKQp3YGt5KBZALZLK4jGvsDttFpLwoTHhdTa
5T6xJKpRJwiUGqpcGrLuFhYPotVNDDPzFTWCVPnCNPGMLqJoSESdqFWLoPNjN44ai
```

暂不清楚解密方法。

#### 1535 帧

![alt text](./images/frame_0767.png)

`Vigenère`，指维吉尼亚密码。

`The key is that the same suffix, with different prefixes, will bring different results.`，与密钥有关。

#### 1729 帧

![alt text](./images/frame_1729.png)

![alt text](./images/frame_1729-1.png)

为什么要用得意黑！！！

```
5P7+NY+YOM9NWsDNy4RWk+dqrER8UTre/d15VSDOXXmud+IRytAbF4UalzWWsWJoSQpKgkOjxmcPCR3Te9SkpuQtpaU3GP84Wcu7a//XTg
Qc12A4F8yPE6vzTBx23h3nIKU2jAlrPQiS+QoFDggig0okkaOQ1TSOtRrrc6YJIFP0Z0ZEKhPtPZ67mLVcQR2xtHTMimSEbL6UoiIqcOSusL83ZOUPg
wyEHvE/jUCEk1j6BXmZotguENfBVzXpY4Hq9V7gKFoKdMmiPQ7Y/itxXq0vwpdunJaNkPIXr6hhuk9QhcJWuTAaRhGjDhrGg1gfh03TeDRvtrpnpFR
bldgPQTVFRQHXsRAh7IDtLt78nWfXPGIviUlok21/GJb7WDJfa49swe3iL8c0YyaAYIjVv7QXWIOscFAZnkIO3ruCYzP23+70j1pWja9M3TrCkYMcqa+
kfzWZJc+DEYZHJOvW+pmc1gfU8UDsPZ6VJnWF3ZXHMlc+L7QMzd9/IjTJ2hHbxvCwYGVD2NGOXzN7FwkqsCo1UvjEX4aJu4oQNnimqPfTpWNh49
udeHIp7/KPToeUYyF6oQBvaHRt2/Ebb7q6PmOOjIkvXjC9jsOvmgqTSuKX00r1hW9rwtt9X3t261qtX6LgK3YwuP/Rp/qtCzoQL2CsypETqL7cfP
VeFNIcaN+gyKJxvFJpLecNJBfL4Jn1tf9PlBrUDznwGBPCu3pk6Ucg4jAL5ExHYvp/4C11yTw3gUaSu2knFfuAFhqpN691pgLvA6+kokBBau7cFgWF
jbQ0gvQ7lDcXK2avzDdsA+CcHUtz5jGCSZPTMwurPNN46eX44SAtbVV5yLHY00r/k91KdRWgYRxwslZDEUqcHOX5BHMX+BK/byls9OQ7deMn
```

#### 1822 帧

![alt text](./images/frame_1822.png)

左上角人物暗示维吉尼亚密码，电脑屏幕中左上浏览器应为 `about:blank` 空白画面，左下浏览器页面为 `app.netlify.com` 的加载页面，有明显的 Netlify 图标。电脑旁有红蓝配色的线条，不清楚进一步含义。

#### 1879 帧

![alt text](./images/frame_0940.png)

`Pvydd ksm fnpm qk kalfs tzx dc oedx?`

电脑中的画面为 CyberChef。

通过前面对密钥的暗示得到密钥是 `thesamesuffixwithdifferentprefixeswillbringdifferentresults`，解密得到 `Would you like to check out my blog?`

#### 1932 帧

![alt text](./images/frame_1932.png)

也有红蓝配色的线穿过，推测暗示是 study 制作了 Neurosama。

#### 1961 帧

![alt text](./images/frame_1961.png)

`Bm cgu grvywxbxjl fl, wpjs cfy jbac fj iypw pw qtou ul howl.`

同样，解密得到 `If you understand me, then you will be able to find my blog.`

结合最后 Neuro 画面的 url 编码，推测部分解密目标是找到博客网站。再结合 Netlify 图标的线索可以推测该网站部署于 Netlify 上，域名应当为 `*.netlify.app`。

#### 1976-1983 帧

闪过两段加密文本，推测为同一段。

![alt text](./images/frame_0989.png)

![alt text](./images/frame_0991.png)

![alt text](./images/frame_0989-1.png)

```plaintext
r+8I/jrbPUwKulV89gQ4d9kaBuOw+Af9ngfBAU0Aw37/HF+OYq9G30xJmq35emmCRiIiIudV4gvea589iq
nS35BozQ3qY00IQINCbwMm1V+BDFH97IjjFZ4N3mtAT9YIwnMbYVGm5zRi96MTRZvh2eDFT6Rwb0
l5reQRRxGguNOla8iIFMwT9wgIFCv4uXkASmfrErlxjHdLmA1im2VNvufpILELdx1S5ELMKTOQlYvPpjS
WP5tZysxnnkmyizSDep7g/KmS95Lo2cDvlNoSYSRiEvoipQDicJPU+0LbIs607ma5OmFzZKvbgGg8boqr
```

![alt text](./images/frame_0991-1.png)

```plaintext
EOenTf/4jPhpka7c2ATOQZCwKc2L9tYteNs+yFjmoIumUWLJJRaLXcW/U93HOvF1+XWaFERtYkhX3G
8u8XZ1lGRQpB4EEDymCv1IMKaQ5koyYdUiOcs6WutQLOtId+JW0tXUuS70t6/TuxMirbNdxRD49l6/
w2glUqx779pjAchu+RPiLIlju7nnHsRbfLuv/0D0YATzssr2zFXmuueq+Hpt0cD9KsTv70TxoTil9IVagpMr0L
YkbMWQUDz7QNa47HxubnSon5D8yBJLVFVkccIcVleuqhBq0EU5EBdX+Inla9hyAL2eMjMU0E3EbZ9P
```

#### 1984 帧

![alt text](./images/frame_0993.png)

主要是右侧两个图片的提示。

上方的图片数字两两分割后得到 `themoon` 在英文字母表中的顺序，`00` 代表空格。

由此猜测下方的图片应按照空格对应 `00`，`a` 对应 `01`，`j` 对应 `10`，`k` 对应 `11` 解读，但进一步如何解密尚不明确。

#### 2135 帧

![alt text](./images/frame_1068.png)

![alt text](./images/00a081476cef427b28d343e9e0b68ace_720.png)

古文字码，原文以 UTF-8 编码格式存储后由 GBK 格式读取获得，空白部分可能为空格字符或者未定义区域字符，其它地方可直接还原，结合一部分猜测可完整还原原文。

红色乱码原文为 `红色药丸代表揭示真相，接受残酷的现实`，蓝色乱码原文为 `蓝色药丸则意味着回到原先的生活并保持对世界的错觉`。

此处两句话出自电影《黑客帝国》的经典台词，结合附近画面可以知道 study 选择了蓝色药丸，尚不明确进一步的含义。

#### 2136 帧

![alt text](./images/frame_1069.png)

![alt text](./images/c29f5f17ccee1367c052950d8e999d53_720.png)

同上。解密结果为：

```plaintext
因此，"蓝色药丸"通常被用来比喻一个人选择逃避现实
选择保持自己的错觉和舒适区
```

推测与剧情有关，尚需更多剧情线索。

#### 2145&2155 帧

![alt text](./images/frame_2145.png)

![alt text](./images/frame_2155.png)

在更换为 4K 片源后可以辨认出文字，两帧图片内文字相同。

![alt text](./images/7f41818964bda5fa205da115a7d314e5.png)

```plaintext
&#x4E00;&#x7CFB;&#x5217;&#x610F;&#x8BC6;&#x6D3B;&#x52A8;&#x8FC7;
&#x540E;&#xFF0C;Phil&#x5E26;&#x7740;&#x8D85;&#x8131;&#x548C;
&#x4E0D;&#x65ED;&#x4FEL;&#x5FF5;&#x611F;&#x7684;&#x5B64;&#x72EC;
&#x56DE;&#x5230;&#x73B0;&#x5B9F;&#x3002;&#x4F5C;&#x8005;&#x51DD;
&#x89C6;&#x6708;&#x4EAF;&#xFF0C;&#x865A;&#x5984;&#x5730;&#x5E7B;
&#x60F3;&#x6709;&#x6240;&#x6539;&#x53D8;&#xFF0C;&#x5374;&#x53D1;
&#x73B0;&#x6708;&#x4EAF;&#x4E5F;&#x6B63;&#x51DD;&#x89C6;&#x7740;
&#x4ED6;&#x3002;&#x6708;&#x5149;&#x4E0B;&#xFF0C;&#x53EA;&#x6709;
&#x81EA;&#x5DF1;&#x7684;&#x53CC;&#x811A;&#x6E05;&#x6670;&#x53EF;
&#x89C1;&#x3002;
```

为 HTML 实体编码，解码得到：

```
一系列意识活动过
后，Phil带着超脱和
不无信念感的孤独
回到现实。作者凝
视月亮，虚妄地幻
想有所改变，却发
现月亮也正凝视着
他。月光下，只有
自己的双脚清晰可
见。
```

Phil 为该手书所用歌曲 The Moon 的主唱，全名 Phil Elvrum，乐队名称为 The Microphones，在 2004 年更名为 Mount Eerie。该段文字出自豆瓣关于《The Moon》的乐评。

#### 2185 帧

![alt text](./images/frame_1092.png)

![alt text](./images/c40c3f188361a22773342950781d7b0e_720.png)

古文字码。同样手段解读得到 `令人厌恶的自我沦陷和对沦陷本身的迷恋`。该段文字同样出自豆瓣。

#### 2285 帧

![alt text](./images/frame_1143.png)

同上。原文如下：

```plaintext
我发誓听见了你的声音
微光（“the glow”）是遥远的、虚无缥缈的
```

The Glow 可能是 The Moon 所在专辑 The Glow, Pt. 2 中的一首歌，歌名同样为 The Glow, Pt. 2。

该句可能暗示后面的杂音，同时在[豆瓣乐评](https://music.douban.com/review/15486909/)可以找到原句出处。

![alt text](./images/ff255ae9409181e0fd6564cb7e687bbc.png)

5:37-5:38 处有细微杂音，查看频谱图发现单词 `exhausted`，尚不清楚进一步含义。

#### 2296 帧

![alt text](./images/frame_1151.png)

图片中间藏有信息。经多张图片混合，可得到文字。

![alt text](./images/cb0b250d0badd6fc8d8f588698f57d40.png)

`I do not exist`

已知这句话是另外一个与 Neuro 相关的民间 ARG 视频标题，该 ARG 似乎尚未告破，不清楚二者之间是否有进一步的联系。

#### 2306-4265 帧

画面中有不同位置的加密文本，由于视频后期处理效果有些画面难以辨识，尽量挑选出最清晰的一帧。

![alt text](./images/frame_2400.png) 
![alt text](./images/frame_2400-1.png)

```
91eUET19D2WHoRc2C9PZbHQw
KL3TrJCBv7Ej475v496nbmQb3H
```

![alt text](./images/frame_2520.png) 
![alt text](./images/frame_2520-1.png) 

```
DRUHNjicyAjuHWKbhUvRw8sK3Xj
p4r2icfr8dxj62Jh61SSJPkthwFErW
```

![alt text](./images/frame_2650.png) 

```
yUx5EZn8GhskTkfpmTg4uPouWvp
dETw2PgLDnQCDF4BkPxqMWbvnu
```

![alt text](./images/frame_2802.png) 
![alt text](./images/frame_2802-1.png) 

```
pg8AkW9ROFldqgisYQZVu08p/mHK0
+FVqVfN/LfM4KjWnLVu178q+YJC22G
```

![alt text](./images/frame_2894.png) 
![alt text](./images/frame_2894-1.png) 

```
fQctPT9SUObPBp+lo7MArHj6/oHW8N
gv7SH1SlRHTQIl2U79CIMZe0B5UDY
```

![alt text](./images/frame_2970.png) 
![alt text](./images/frame_2970-1.png) 

```
uaVe37asuOJN/D
gxe1V8OHzLR1V2x
C4iBCB7LIRCjMShd
JBHUHHs6hjR0bZ
```

这一帧在之后有闪回。

![alt text](./images/frame_3090.png) 
![alt text](./images/frame_3090-1.png) 

```
ohazfhzIlsCYBXVo0D8j5ZS/GkXOJsMB79hGY7ogogBgE5QWflTzj7bAqo=
```

![alt text](./images/frame_3122.png) 
![alt text](./images/frame_3122-1.png) 

```
Z1BNTDB1T09jd1Z4WGp1
OWJtQmlnK0kyS29UYzF
mYUZzVVBJQlVRcmdjc0Rw
QjlwY3B3WGtKaHNBa1h
```

![alt text](./images/frame_3160.png) 

与上一帧相同。

![alt text](./images/frame_3224.png) 
![alt text](./images/frame_3224-1.png) 

```
UMjdqWEV0d2x2NFkvZU5PNjRkcHdIaGliQURHQ0V
idVgxuDhDMzE5OVlRZk5wVmJZUm5sc1JLZ2J3eW
```

![alt text](./images/frame_3226.png) 

与上一帧相同。

![alt text](./images/frame_3290.png) 

该画面由于文字隐藏在噪声中且和底色重叠，比较难以提取。通过在 PS 中将同一画面的所有帧压入堆栈，取堆栈标准差/范围值，调高亮度得到相对较为容易辨识的图片。

![alt text](./images/res.png)

```
9vOEVTbGE1bUxXamd1bXZHK2xMNm9XK1JoVXV6U
OhaNZhkM3NvUjNsMlKjJkxsNvtuUXpxYWw0Q3pm8
```

![alt text](./images/frame_3418.png) 
![alt text](./images/frame_3418-1.png) 

```
HFObjJmMnJZUnRtWHIzbXJ0TEoVRGTkc3ZWQW1
CZEQreno5eElKzJrZU93VnFhNjF6UjhobEJ3cs0=
```

![alt text](./images/frame_3508.png) 

这里可以看出左上角数字 `0418`，可能对应 ARG 视频 Study 的 04:18，该时间点在简介出现过。

处理一下比较明显。

![alt text](./images/3500-1.png)

![alt text](./images/frame_3590.png) 

![alt text](./images/frame_3590-1.png) 

这一张识读比较困难。

```
KIsUkoyKdhETIQKaYUoR2BCljkBTk?qJqd3jcwPWEG
+M2C1kvSlMNDcdPeQCWjuheoZ6y76Wk0SlY8Jr77kl
lYUmWwvJVhTNO0L7MkTGeNvczMHGaS9SAVHWJ
lCcKt1CZccwJK3QlDnC+ALdDBibiuieMUcWewv+Z
```

后面图片中的背景文字可能发生了变化，更加难以识别。

![alt text](./images/frame_3750.png)
![alt text](./images/frame_4016.png)
![alt text](./images/frame_4037.png)
![alt text](./images/frame_4140.png)
![alt text](./images/frame_4147.png)

中间闪过的画面可能暗示这一段密文的解密方式，右下角的数字为同一字体，可能是编号一类。第一张左上角字体为 Bradley Hand ITC，因此文本为 `//003200`，第二张左上角为 `000500 -> AES -> ???`。

![alt text](./images/frame_4230.png)

![alt text](./images/40a5b7602a686934b746bc7188c4a8eb.png)

```
BeBMk6qgH9Qh8kHpMT+yEswlYtNbmaxPHQ
KMUfn1zTsW+cgO9M1RogNPVGc+OAQm8QQT
69D7mBPNrZwWtzeUGAjYu2t/5s33cp5Rf10dt
VqDHKy8eDmrco89lC/57VJMNGcjOcD9Dr8J49
6VMFxIS2lZ/gbgaTJL1a4fGIgM2pY8qlyPJctv
CmfHiFJ6NnxDr6qYJHG6Tnwek8z/NYPI8Q6pa
0w8YZs+kd3MvlVtLqKSkEIGfzQ25qV/JV2eW7X
FIbVmx35LjMCxxgxTeRtEIjer2EXCGCUDzyxc=
```

中间插入的画面可能是暗示这一段密文的解密方式。

#### 4483 帧

![alt text](./images/frame_2242.png)

Unicode 编码，转写结果为 `有一个地方，跟地面上的世界不一样。那里充满奇幻、神秘和危险。`

原句出自《爱丽丝梦游仙境》，旁边兔子和树洞的意象也与此相符。

4324-4701 帧画面应该出自 Meaning of Life，蜡烛出自 Candles，暂未发现其他线索。

此外画面中白色方块整体符合月亮升落轨迹，不清楚是否为进一步线索。

#### 4926 帧

![alt text](./images/frame_2497.png)

`I%20have%20a%20song%20that%20I%20never%20tire%20of%20listening%20to`

`%20` 为 url 编码的空格，尚不清楚是否有额外含义。

此外结尾的 Neuro 发饰为红蓝配色，可能暗示红蓝药丸的意象。

#### 5130 帧

![alt text](./images/frame_2566.png)

可能是指 ARG 视频 hello, world。

#### 字幕收集

Study

Fallen down

> 在 ARG 视频《Study》的简介出现过，对应的时间为 04:18 和 21:48。在简介的 13:27 和 30:39 出现过倒置的版本。

I'm not like other girls

> 在同一视频的简介中出现，对应时间点为 13:58。在 Fallen Down 的歌词中也出现了。

I'm fine...

> 在同一视频的简介中出现，对应时间点为 31:10。在 I Don't Want to Be an Engineer 和 Fallen Down 的歌词中均出现了。

I want to be \<???\>

> 未找到来源。

I think I saw a ghost

> 在同一视频的简介中出现，对应时间点为 07:43 和 25:14。同时也在 I Think I Saw a Ghost 的歌词中出现。

I've been losing touch

> 在 I Think I Saw a Ghost 的歌词中出现了，大概在原视频的 08:01 - 08:03。

Got myself another test

> 在 Fallen Down 的歌词中出现了，且不止一次。

Why are you crying?

> 这句话出现在 ARG 视频《Public Static Void》里。原文是日语，不过这句话和官方英文翻译一致，大约位于该视频的 00:26。

THE MOON

（后接 The Moon 歌词）

### 14:30-

此处暂时仍采用 1080p 的旧片源。

#### 1096 帧

![alt text](./images/frame_1096.png)

![alt text](./images/frame_1096-1.png)

```
V2FpdCwgd2FpdCwg
dW50aWwgdGhpbmdz
IGNoYW5nZSB3aXRo
IHRpbWUu
```

base64 解码结果为 `Wait, wait, until things change with time.`

#### 1598 帧

![alt text](./images/frame_1598.png)

![alt text](./images/frame_1598-1.png)

`RXZlcnkgd29yZCBoZXJlIGlzIHNvIGltcG9ydGFudC4=`

由于图片严重失真，识别结果不准确，通过部分识读和猜测得到原句

`Every word here is so important.`

## 单品投稿

取名太麻烦了叫你 themoon2/m2 吧。

所有帧均相同，取第一帧。

![alt text](./images/frame_0001.png)

![alt text](./images/frame_0001-1.png)

识别结果 `+>>>++++++++++[->+++++++++++>++++++++++>++++++++++++>++++++++++++>+++>>++++++++++++>++++++++++>+++++++++++>++++++++++>+<<<<<<<<<<<]>>+>>---->++>>---->+++++>->+[[<]<[<]<<<[->+>+<<]+>[-<+>]>[->>[.>]<[<]<]>>[>]>[.>]<]`

执行结果

![alt text](./images/5520aee7557fae7e7ced2911bdcf09af.png)

## 完整单品投稿

取名太麻烦了叫你 themoon3/m3 吧。

这次手书总体看起来像是 m1 的不同视角。

片源采用 b 站 1080p 60 帧缓存。

### 视频简介

```plaintext
ZGVmIGVuY3J5cHRfYWxsKHBsYWludGV4dCk6DQogICAgcmVzdWx0ID0gW10NCiAgICANCiAgICByZXN1bHQuYXBwZW5kKGVuY3J5cHQocGxhaW50ZXh0WzBdLCAwKSkNCiAgICANCiAgICBmb3IgaSBpbiByYW5nZSgxLCBsZW4ocGxhaW50ZXh0KSk6DQogICAgICAgIHByZXYgPSBwbGFpbnRleHRbaS0xXQ0KICAgICAgICByZXN1bHQuYXBwZW5kKGVuY3J5cHQocGxhaW50ZXh0W2ldLCBwcmV2KSkNCiAgICANCiAgICByZXR1cm4gcmVzdWx0
```

解密得到一段 Python 代码：

```python
def encrypt_all(plaintext):
    result = []
    
    result.append(encrypt(plaintext[0], 0))
    
    for i in range(1, len(plaintext)):
        prev = plaintext[i-1]
        result.append(encrypt(plaintext[i], prev))
    
    return result
```

### 145-159 帧

![alt text](./images/m3_frame0159.png)

![alt text](./images/m3_frame0159-1.png)

```plaintext
Vm10amVFMUhWblJVYmtwclVrWndXRmxzWkc5Vk1WSldW
bGhrYkZKc2JEVlVWbFpyWVRGYVZWWnNhRnBOUjJoMldW
VmtSMk14U2xsYVJscFhVbFZ3VEZaR1dtRlZNVTVYVTJ4V
1ZHRjZiSEJWTUZaS1pERmFXRTFZWkZkaGVrWllXV3RhYT
FWc1drWmpSbHBXVmtVMVZGa3hXbE5qYkZaelZHeE9VMkV
4Y0RSV2JUQXhZVEZzVjFkWWNGcE5NbWhaVm01d1IyVldV
bFpXVkVaWFlsWmFTbGxWV2xkaVIwcEpVV3M1Vm1Wck5UT
ldSM040VjBaT1dWcEdWbWxYUmtwUlZtMTRiMkl5VVhoal
JWcFdZa2RTYzFadGMzaE5NV3gxWTBWa2FHSlZWalpXVnp
WaFZsZEZlRk5zVWxaaE1YQkhXa1JHVjJNeFRuUmpSMnhZ
VWpKbmVsWnJZekZrTWtWNVZGaHNVMkpHV2xoWldIQkhZM
FpaZDFkcmRFNWlSbkJIV1ZWV1QxUnNXbkpOVkZaV1RXcF
djbGRXVlhoWFIxSkZWMnh3YUUxdGFGbFdWRW8wVmpGT1J
rNVdiR2xTYkVwd1ZXMTBkbVZXWkZWVFZFWlVUVlZ3V1ZV
eGFIZFZiRnBHVjJ4YVZtSnVRbnBhVmxwaFVteFdjazlY
Y0ZkaVZHdDZWMWQwVjJReFZsZFdiRlpPVWtkek9RPT0=
```

嵌套了七层 Base64，解密得到一小段话：

```plaintext
课堂喧嚣、人际疏远、日常于迷思中沉没。
勾勒涂鸦遍布笔记角落。
```

对应前一个画面的场景。

### 374-388 帧

![alt text](./images/m3_frame0388.png)

![alt text](./images/m3_frame0388-1.png)

```plaintext
&#106;&#88;&#75;&#112;&#87;&#114
;&#47;&#57;&#71;&#89;&#89;&#76;
&#90;&#54;&#81;&#85;&#83;&#49;&#1
19;&#76;&#86;&sol;&#67;&#77;&#50
;&#68;&#115;&#53;&#100;&#109;&#6
9;&#67;&#101;&#70;&#69;&#119;&#1
16;&#110;&#57;&#87;&#70;&#77;&#8
1;&#102;&#72;&#115;&#48;&#53;&#1
10;&#88;&#66;&#75;&#76;&#79;&#11
0;&#99;&#55;&#55;&#84;&#83;&#82;
&#69;&#122;&#98;&#90;&#54;&#67;&
#76;&#97;&#54;&#109;&#74;&#56;&#
104;&#51;&#65;&#116;&#88;&#121;&
#66;&#118;&#112;&#86;&#106;&#83;
&#48;&#53;&#71;&#106;&#86;&#53;&
#78;&#51;&#105;&#73;&#86;&#74;&#
87;&#119;&#108;&#66;&#115;&#113;
&#77;&#107;&#104;&#78;&#52;&#78;
&#109;&#103;&#51;&#56;&#107;&#69
;&#85;&#51;&#87;&#112;&#104;&#82
;&sol;&#50;&#77;&#70;&#87;&#88;&
#86;&#111;&#81;&#73;&#87;&#90;&#
112;&#65;&#48;&#70;&#71;&#56;&#6
7;&#88;&#107;&#113;&#118;&#81;&#
105;&#83;&#107;&#76;&#75;&#85;&#
103;&#108;&#110;&sol;&#122;&#90;
&#66;&#102;&#119;&#86;&#100;&#71
;&#110;&#110;&#75;&#97;&#115;&#1
11;&#112;&#107;&#84;&#75;&#90;&#
68;&#102;&#89;&#119;&#57;&#116;&
#80;&#66;&#113;&#53;&#74;&#102;&
#99;&plus;&#84;&plus;&#119;&#51;
```

删去换行符：

```plaintext
&#106;&#88;&#75;&#112;&#87;&#114;&#47;&#57;&#71;&#89;&#89;&#76;&#90;&#54;&#81;&#85;&#83;&#49;&#119;&#76;&#86;&sol;&#67;&#77;&#50;&#68;&#115;&#53;&#100;&#109;&#69;&#67;&#101;&#70;&#69;&#119;&#116;&#110;&#57;&#87;&#70;&#77;&#81;&#102;&#72;&#115;&#48;&#53;&#110;&#88;&#66;&#75;&#76;&#79;&#110;&#99;&#55;&#55;&#84;&#83;&#82;&#69;&#122;&#98;&#90;&#54;&#67;&#76;&#97;&#54;&#109;&#74;&#56;&#104;&#51;&#65;&#116;&#88;&#121;&#66;&#118;&#112;&#86;&#106;&#83;&#48;&#53;&#71;&#106;&#86;&#53;&#78;&#51;&#105;&#73;&#86;&#74;&#87;&#119;&#108;&#66;&#115;&#113;&#77;&#107;&#104;&#78;&#52;&#78;&#109;&#103;&#51;&#56;&#107;&#69;&#85;&#51;&#87;&#112;&#104;&#82;&sol;&#50;&#77;&#70;&#87;&#88;&#86;&#111;&#81;&#73;&#87;&#90;&#112;&#65;&#48;&#70;&#71;&#56;&#67;&#88;&#107;&#113;&#118;&#81;&#105;&#83;&#107;&#76;&#75;&#85;&#103;&#108;&#110;&sol;&#122;&#90;&#66;&#102;&#119;&#86;&#100;&#71;&#110;&#110;&#75;&#97;&#115;&#111;&#112;&#107;&#84;&#75;&#90;&#68;&#102;&#89;&#119;&#57;&#116;&#80;&#66;&#113;&#53;&#74;&#102;&#99;&plus;&#84;&plus;&#119;&#51;
```

为 HTML 实体编码，解码得到：

```plaintext
jXKpWr/9GYYLZ6QUS1wLV/CM2Ds5dmECeFEwtn9WFMQfHs05nXBKLOnc77TSREzbZ6CLa6mJ8h3AtXyBvpVjS05GjV5N3iIVJWwlBsqMkhN4Nmg38kEU3WphR/2MFWXVoQIWZpA0FG8CXkqvQiSkLKUgln/zZBfwVdGnnKasopkTKZDfYw9tPBq5Jfc+T+w3
```

可能经 AES 加密，需要进一步线索。

### 569-577 帧

![alt text](./images/m3_frame0577.png)

右侧 `rot9+10`。

### 580-627 帧

![alt text](./images/m3_frame0601.png)

![alt text](./images/m3_frame0601-1.png)

```plaintext
NGuBY2jV2jTe7r3Ey/Pbtbwd1kLlXewhMyP9km7FvO5xo5py
PXaaFmLwFWIqlP1RIGjbsuyBAC5qo9OCbZ9IUMcYFzNAAXpr
UV3cNxly5/nEqgZb3Hl/zXKNtm0FMmhaNqERRKeXT+4CWWi3
+ZJdjCYLS7ccQ9egakwQSG0XT2ifCtLibzu90kYCaUqFldvt
```

无法直接解密。同样可能经 AES 加密，需要进一步线索。

### 677-751 帧

![alt text](./images/m3_frame0750.png)

`Find it down in hell.`

此处对应 m1 的 `Would you like to check out my blog?`。

~~没偷摸骂我两句吧~~

### 804-873 帧

![alt text](./images/m3_frame0854.png)

对应 m1 的 1984 帧处，此处右侧为空白，可以印证确认 m1 对应处为解密有关提示。

### 964-

后面人声部分基本和 m1 的场景是对应的。联合起来看的话，似乎讲述了 Study 去往了一些地方，最后到 Meaning of Life 的场景和她的工作室内，将自己与 Neurosama 连接。结合最后的 `hello, world` 来看的话，或许讲述了类似于 NeuroARG 的剧情。不过以上都只是猜测。

另外值得注意的是，此处除了出现 The Moon 的歌词外，还出现了 In Hell We Live, Lament 的歌词。尚不清楚含义。

此外，在 m1 中出现的闪回在此处也有出现，不过内容似乎并无差异，因此不再单独列出。

密文部分单独列出。

### 1394-1426 帧

![alt text](./images/m3_frame1426.png)

```plaintext
······
濂圭殑瑙
嗚□鐮寸□璺
宠穬锛□_
涓€鍒囧瓨
鍦凵兘绐佸厐
鑰岃垂瑙○紝
...
```

原文为：

```
······
她的视觉破碎跳跃，
一切存在都突兀而费解，
...
```

值得注意的是该原文转成乱码后少了一个 `_`，考虑到可能是打印提示符，应该影响不大。

### 1944-1971 帧

![alt text](./images/m3_frame1953.png)

可以看到有密文，但似乎并不全。反色后发现右侧和下方被色块遮挡，有些可疑。

![alt text](./images/m3_frame1953-1.png)

```plaintext
W50aWwgdGhpbmdzIGNodCwg
d2FpdCwgdV2FpdCwgd2FpdCe?
CBoZXJlIGrid2UgbGlh82QdjcIHR
4=nkgd2ZSBpbiBoZWxs29yZCun
BoZty0LCB5ZXQgd2UgbpdCwg?
W50aWimV2ZXIgbGFtZwgdGyd?
FudC4==3iW50Lg==u2avUiv8wr
mdzIGNoYW5nW50ZSB3aXRoIH
dCwgdW5tcG9HNvlGltcGyudC4=
```

可以明显地看到中间有部分加粗。截取这一部分文本得到 

```plaintext
d2UgbGl2ZSBpbiBoZWxsLCB5ZXQgd2UgbmV2ZXIgbGFtZW50Lg==
```

解密得到

```plaintext
we live in hell, yet we never lament.
```

那其它部分有没有用呢？不清楚，只知道如果凑一凑对齐的话，可以翻译出零散的词句，可能出现 `Until things cht, wait, wait, wait` `gs chang` `with w` `so impl®t.` 等等意味不明的片段。个人倾向于可能没什么用处。