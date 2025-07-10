# geosite

direct.dset 指定用国内DNS解析

proxy.dset 指定用国外DNS解析

这两个表之外的域名，国内/国外DNS解析均可。

    可以用msodsn / sing-box  的逻辑判断，返回 realip / fakeip。  
    先用国内DNS解析，匹配cnip，直接返回。  
    否则，就返回fakeip
  
