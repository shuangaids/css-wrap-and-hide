# css-wrap-and-hide

既折行又隐藏的 css样式 （展示两行，多余的文字用三个点替代）

.css {

  display: -webkit-box;
  
  /*! autoprefixer: off */
  
  -webkit-box-orient: vertical;
  
  /*! autoprefixer: on */
  
  -webkit-line-clamp: 2;
  
  overflow: hidden;
  
  word-break:break-all;//这句话是用于避免英文单词不折行现象
  
  max-width: 150px;//如果不加这句话 上面的代码将没有效果
  
}
