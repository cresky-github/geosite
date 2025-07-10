# geosite

direct 指定用国内DNS解析

proxy 指定用国外DNS解析

这两个表之外的域名，国内/国外DNS解析均可。

    可以用 msodsn / sing-box 的逻辑判断，返回 realip / fakeip。  
    国内/国外DNS解析，匹配cnip，直接返回。  
            推荐用国内，防止未知是国外，优先返回。
            基本逻辑：用国内DNS解析，返回cnip，就一定是国内域名，其它情况不确保
    否则，就返回fakeip，或者realip。取决实际需要。
  
当然，这是动态的。
