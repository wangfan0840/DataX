#BUG

##Could not resolve dependencies for project com.alibaba.datax:otsstreamreader 
打开otsstreamreader项目，将快照改为1.0.0即可
##Could not find artifact org.pentaho:pentaho-aggdesigner-algorithm:jar:5.1.5-jhyde
请手动下载Jar包pentaho-aggdesigner-algorithm-5.1.5-jhyde.jar下载地址：https://public.nexus.pentaho.org/content/groups/omni/org/pentaho/pentaho-aggdesigner-algorithm/5.1.5-jhyde/
将Jar包放置在本地Maven仓库org/pentaho/pentaho-aggdesigner-algorithm/5.1.5-jhyde路径下，之后进行重新打包。

