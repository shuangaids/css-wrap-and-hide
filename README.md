# css-wrap-and-hide
既折行又隐藏的 css样式 （展示两行，多余的文字用三个点替代）
.css {
  display: -webkit-box;
  /* autoprefixer: ignore next */(避免编译丢失的情况)
  -webkit-box-orient: vertical;
  -webkit-line-clamp: 2;
  overflow: hidden;
}
