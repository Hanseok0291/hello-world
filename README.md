191218

웹폰트 사용시 권장 적용 순서.

@font-face {
  font-family: 'Nanum Gothic';
  font-style: normal;
  font-weight: 400;
  src:  url(./NanumGothic-Regular.eot);
  src:  url(./NanumGothic-Regular.eot?#iefix) format('embedded-opentype'),
        url(./NanumGothic-Regular.woff2) format('woff2'),
        url(./NanumGothic-Regular.woff) format('woff'),
        url(./NanumGothic-Regular.ttf) format('truetype');        
}

@font-face {
  font-family: 'Nanum Gothic';
  font-style: bold;
  font-weight: 700;
  src:  url(./NanumGothic-Bold.eot);
  src:  url(./NanumGothic-Bold.eot?#iefix) format('embedded-opentype'),
        url(./NanumGothic-Bold.woff2) format('woff2'),
        url(./NanumGothic-Bold.woff) format('woff'),
        url(./NanumGothic-Bold.ttf) format('truetype');
}