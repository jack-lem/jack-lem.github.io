# 在MyEclipse里ArrayList总是出现警告，下面提示是什么意思啊？  
### ArrayList下面的警告是说ArrayList没有进行对象实例化（也就是说没指知定ArrayList存放的类型是什么）。  
### 解释：“List list = new ArrayList();”会出现安全警告的原道因是list和Arrylist都是object对象，没有进行实例化回，导致警告的。  
### 解决办法：将上面的代码写成“List<Object> list = new ArrayList<Object>();”这种情况下就不会出现警告了答。  
***
