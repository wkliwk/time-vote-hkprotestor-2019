# TIME's Person of the Year for 2019 : Hong Kong Protestors

## 大家幫手投 Hong Kong Protestors 做 TIME's Person of the Year for 2019，由於跟正常程序咁投會比較麻煩又要register又要係咁refresh先揀到，所以寫左條script仔，幫大家快速直接投 `Hong Kong Protestors` 一票 
（唔敢保證100%無問題，如果時間多想穩陣啲就最好跟返正常flow去投)

<img src="https://scontent-hkg3-2.xx.fbcdn.net/v/t1.0-9/75550426_953433055025315_8466231089969496064_o.jpg?_nc_cat=1&_nc_oc=AQnLhPyAc8EGRoh1KyZzFnhg3kEFbz9rCZGZioMAwtxw2m31daFZe8MgFIpnxCqFF_o&_nc_ht=scontent-hkg3-2.xx&oh=faed1cee0e37e9251785c22bf902626b&oe=5E860DD2" width="200">

1. Bookmark 呢條
<a href="javascript: (function () {    const t = new XMLHttpRequest;    t.open(&quot;POST&quot;, &quot;https://time-magazine-production.herokuapp.com/api/vote&quot;), t.setRequestHeader(&quot;Content-Type&quot;, &quot;application/json&quot;), t.onload = function () {        200 === t.status ? alert(&quot;%E6%88%90%E5%8A%9F\n%E5%85%89%E5%BE%A9%E9%A6%99%E6%B8%AF%EF%BC%8C%E6%99%82%E4%BB%A3%E9%9D%A9%E5%91%BD&quot;) : alert(&quot;%E9%8C%AF%E8%AA%A4&quot;)    }, t.send(JSON.stringify({        person_id: &quot;54&quot;,        result: !0,        fingerprint: (t => {            const e = `; ${document.cookie}`.split(`; ${t}=`);            if (2 === e.length) return e.pop().split(&quot;;&quot;).shift()        })(&quot;fingerprint&quot;),        email: &quot;false&quot;    }))}());" add_date="1530821604">LINK</a> （或者就咁拉去bookmark條toolbar到）

2. 去TIME投票頁 (一定要經呢條 [https://time-magazine-production.herokuapp.com/](https://time-magazine-production.herokuapp.com) )去

3. Click 頭先個 Bookmark

4. 成功會有個alert box彈出黎

---
完

香港人加油！！ 🇭🇰