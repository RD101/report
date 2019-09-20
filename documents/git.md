# git install

CentOS7.6 에서 사용되는 git 버전은 1.8.x 입니다.
버전이 낮아서 `http://`, `https://` 프로토콜로 git push 할 수 없습니다.
CentOS7.6 설치후 git 버전을 올려주세요.

git-2.23.0.tar.gz 파일을 아래 링크에서 다운로드 합니다.

다운로드: https://mirrors.edge.kernel.org/pub/software/scm/git/

```
# yum install gcc
# yum install curl-devel
# yum install zlib
# ./configure --with-curl --with-expat
# make
# make install
```

### 참고사항
- [gcc](https://gcc.gnu.org): GNU C Compiler
- [curl-devel](https://curl.haxx.se): URL로 데이터를 전송하기 위한 라이브러리
- [zlib](https://github.com/madler/zlib): 데이터를 압축하기 위한 압축 알고리즘 라이브러리
- [expat](https://github.com/libexpat/libexpat): Stream-oriented XML 1.0 파싱 라이브러리

