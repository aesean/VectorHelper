# VectorHelper
这几天读到一篇介绍Vector兼容性的文章
(参考：http://www.jianshu.com/p/e3614e7abc03),
然后尝试替换了一些资源文件，效果还不错，但是App里有一些Vector需要根据主题不同切换颜色，如果还是按照文章所说的使用属性动画框架去设置其实也能实现，不过就过于劳师动众了，属性动画无非也是反射，既然属性动画能做那自己通过反射肯定也是可以实现的。通过AnimatedVectorDrawable源码，一步步反射回去，写了一个简单的封装类。

详细介绍可以参考这里：http://www.jianshu.com/p/2db6a5ce871b
