## 职业制作不易，如果觉得不错可以打赏作者，精神支持亦可
<details>
<summary>叽付宝二维码</summary>  
	
![87dcc65ee628ac8963c01c977330726b](https://github.com/iderfl/mm-bx/assets/90140812/fc855b87-7474-4a6b-8f25-38ef055ced79)
	
</details>  


## 可以找作者定制九宫格翻牌监控，效果如下
<details>
<summary>点击查看</summary> 

* 效果预览  
![image](https://github.com/iderfl/mm-bx/assets/90140812/c9208e0f-c7ca-40bb-94da-9ab40e191965)
![QQ2024511-224135 -original-original](https://github.com/iderfl/mm-bx/assets/90140812/832907a5-0b0c-477e-baa3-7a4e7691fabb)  

	可以是释放技能把黑色翻成图片（释放技能后显示图）  
	也可以图片翻成黑色（释放技能后显示黑色）
  
* 以下是支持的图片  
  ![image](https://github.com/iderfl/mm-bx/assets/90140812/f4819353-cb9b-4c19-9ebb-1dea265f5f61)

</details>  

# 教程链接
*  [点击查看花间教程](https://github.com/iderfl/-cw-/blob/main/%E8%8A%B1%E9%97%B4%E6%95%99%E7%A8%8B.md)

# 更新日志
## 更新日志没说需要重新取色/换宏/换监控就是不需要，如果需要会写在更新日志里面

## [雾海寻龙]花间紫武bate5更新，2024年5月15日
* 优化开腰坠的条件  
	旧：芙蓉前，开水月时腰坠  
	新：开水月腰坠

* 【不换监控】【不改宏】【不用重新取色】 

---------------------------------------
<details>
<summary>[雾海寻龙]橙武宏更新，2024年5月8日</summary>  

	/fcast [bufftime:璃光浮远>0] 水月无间
	/fcast [bufftime:璃光浮远>0] 玉石俱焚
	/cast [tnobuff:兰摧玉折&nobuff:璃光浮远] 兰摧玉折
	/cast [tbuff:兰摧玉折] 快雪时晴 
* 修复橙武宏不打兰摧
* 正确的橙武循环应该是 ___玉石-玉石-玉石-玉石-兰摧-快雪-（墨海）-（芙蓉）-玉石___


</details> 
<details>
<summary>[雾海寻龙]橙武花间bate4更新，2024年5月7日</summary>  
 
* 普通循环，如果五豆及以上，会替换钟林打【临源】
* 普通循环，如果墨海已经调息12s，那么会替换钟林打【墨海】
* 芙蓉循环，如果墨海已经调息12s，那么没5豆也打【墨海】

</details> 

<details>
<summary>[雾海寻龙]紫武花间bate4更新，2024年5月7日</summary>  
 
* 普通循环，如果当前八豆，会替换钟林打【临源】
* 普通循环，如果墨海已经调息12s，那么会替换钟林打【墨海】

</details> 

<details>
<summary>[雾海寻龙]橙武花间bate3更新，2024年4月29日</summary>  
 
* 修复一部分8豆没打墨海，导致豆溢出的bug
* ___即便如此，还是会有阴间的橙武特效触发在已经5豆，但是还没打墨海之前，导致豆溢出___

</details>  
<details>
<summary>[雾海寻龙]紫武花间bate3更新，2024年4月29日</summary>  

* 新增了5豆和8豆的取图，你需要重新取图才能继续使用
* 修复停手/乱循环导致墨海没打出去，导致豆溢出（修橙武循环bug想到的）
* ___即便如此，如果出现频繁停手，还是有可能导致豆溢出，五一回来再修吧，改动比较多___  

</details>  
<details>
<summary>花间橙武宏更新，2024年4月28日</summary>  
修复二段加速特效期间多打玉石导致下一循环错误问题  

	/fcast [bufftime:璃光浮远>0] 水月无间  
	/cast [tnobuff:兰摧玉折&nobuff:璃光浮远|nobuff:钟灵] 兰摧玉折  
	/fcast [bufftime:璃光浮远>0] 玉石俱焚  
	/cast 快雪时晴  
</details>   
<details>
<summary>橙武bate2更新日志，2024年4月27日</summary>

	1.删除了墨海2层的取图
	2.新增墨海0层取图  
* 以上修改解决了上线后墨海图标不显示层数的问题，你需要对墨海0层图标进行取图才能正常使用  
* 以下是操作步骤：  
  		1.进入茗伊监控列表，将墨海监控勾选上`隐藏消失的`  
  		2.打2次墨海技能，使墨海图标的层数数字消失；取图框选图标内`右下角1/4`
</details> 
<details>
<summary>紫武bate2更新日志，2024年4月27日</summary>
	
	1.删除了墨海2层的取图
	2.新增墨海0层取图  
* 以上修改解决了上线后墨海图标不显示层数的问题，你需要对墨海0层图标进行取图才能正常使用  
* 以下是操作步骤：  
  		1.进入茗伊监控列表，将墨海监控勾选上`隐藏消失的`  
  		2.打2次墨海技能，使墨海图标的层数数字消失；取图框选图标内`右下角1/4`
</details>
<details>
<summary>橙武bate1更新日志，2024年4月26日</summary>
	
	1.修复玉石后切宏卡一个GCD的问题  
	2.修复橙武特效结束后玉石会打断快雪  
	3.修复特效期间会打墨海的问题（特效期间只打玉石收益最高）   
	4.更新橙武宏  

</details> 
<details>
<summary>紫武bate1更新日志，2024年4月26日</summary>
	
	1.修复玉石后切宏卡一个GCD  
	2.修复乱洒循环打2个墨海  
</details>




 
 
