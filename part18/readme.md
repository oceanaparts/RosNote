# 18.通讯机制比较
<div align=center><img src="https://s2.loli.net/2022/02/03/rY87NeWpjZ39wKq.png"></div>
* 话题通讯异步的含义是:当一个msg发过来后，可能还没处理，后续的msg就有发过来了，也就是不用等待当前的msg处理完，在接受下一个msg，这样可能会错失消息，对应的处理办法就是设置缓存区，将没来得及处理的消息放置在缓存区