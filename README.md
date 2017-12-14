# SYPopGesture
一键解决pop手势问题

## 优势
1.支持自定义leftButtonItem造成的pop手势不可用
2.支持VC中包含UIScrollView相关view造成的pop手势不可用
## UIScrollView UICollectionView UIPageViewController MapView UISlider等
3.支持侧滑和全屏返回手势
4.支持不同vc的使用不同的手势操作

## 使用方式
* 将UIViewController+SYPopGesture.h 拖入工程即可实现
* 设置为全屏pop手势
 self.sy_isFullPopGesture = YES;
* 设置手势不可用
  self.sy_interactivePopDisabled = YES;
  


