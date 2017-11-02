# CleanCache
iOS 清除缓存，包括SDWebImage 缓存的图片

使用：
  在使用时直接调用类方法即可

举个栗子：
显示缓存大小：CGFloat cacheSize = [FileService folderSizeAtPath:cachePath];
清除缓存：[FileService clearCache:cachePath];
