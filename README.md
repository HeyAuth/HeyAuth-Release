# HeyAuth Community

这里是 HeyAuth 的社区。即便您没有购买 HeyAuth, 您也可以在这里了解到 HeyAuth 的相关信息，
和社区里的伙伴们一起交流与学习。

`CHANGELOG.md` 中包含了 HeyAuth 的更新日志，会有比较大的延迟。
如果您是正版用户，可以查看 [HeyAuth 蓝图](https://github.com/orgs/HeyAuth/projects/1) 来查看实时计划。

如果您有什么疑惑，可联系 [admin@yuxiaoqiu.cn](mailto:admin@yuxiaoqiu.cn) 以咨询。

如果您发现 HeyAuth 有什么问题，或者是新功能请求，可以 [发起issue](https://github.com/HeyAuth/HeyAuth-Release/issues/new/choose)
来咨询。无论是正版还是盗版用户，我们都会尽可能耐心地回答您。
~~除非您是盗版而且我们忍不住或是实在太抽象的正版用户~~

### HeyAuth 立项

HeyAuth 从 `2024-07-28 15:31:46` 开始开发，距今已过

<div id="box1"></div>
  <script>
    function timingTime(){
      let start = '2024-07-28 15:31:46'
      let startTime = new Date(start).getTime()
      let currentTime = new Date().getTime()
      let difference = currentTime - startTime
      let m =  Math.floor(difference / (1000))
      let mm = m % 60  // 秒
      let f = Math.floor(m / 60)
      let ff = f % 60 // 分钟
      let s = Math.floor(f/ 60) // 小时
      let ss = s % 24
      let day = Math.floor(s  / 24 ) // 天数
      return day + "天" + ss + "时" + ff + "分" + mm +'秒'
    }
    setInterval(()=>{
      document.getElementById('box1').innerHTML = timingTime()
    },1000)
  </script><br>

  如果加载不出来是因为禁止了Javascript `(xwx`