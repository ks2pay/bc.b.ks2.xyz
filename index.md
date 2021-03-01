##BC群组服务器使用本插件子服配置教程

###比如您购买了一个授权给主服：【play.ks2.xyz 】
###但是您现在还有以下几个子服：
>####1：[bc1.ks2.xyz]

>####2：[bc2.ks2.xyz]

>####3：......

###【本教程实现原理】：将每个BC子服看作是多个不同的服务器

设置教程：

####1：从 http://buy.oa5.xyz/ 再购买两个(多个)授权，授权的ip分别为
###[bc1.ks2.xyz]和[bc2.ks2.xyz]

####2：在bc1子服的插件配置文件设置ip为bc1.ks2.xyz

####在bc2子服的插件配置文件设置ip为bc2.ks2.xyz

####[如有多个子服，请以此类推......]

####3：在云商城里设置商品下单后提交到不同的服务器

####比如bc1服设置的url就是：
`http://api.ks2.xyz/?ip=bc1.ks2.xyz&send=plugins&key=xxx&command=xxx`

####那么bc2服设置的url就是：

`http://api.ks2.xyz/?ip=bc2.ks2.xyz&send=plugins&key=xxx&command=xxx`
