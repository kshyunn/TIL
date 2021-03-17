## gitignore

.gitignore 파일에 git으로 추적하지 않을 파일을 관리한다.

```hxml
data.csv # 특정 파일
secret_folder/
*.zip # 특정 확장자
```

* 일반적으로 개발 소스코드와 관련 없는 개발 환경 속에서 생성되는 파일들을 필수적으로 넣는다.
  * os - mac/windows/linux, IDE (통합개발환경) /text editor(Eclipse, Intellij, Pycharm, VS Code) 특정 언어 환경
  * https://gitignore.io
    * 위의 사이트에서 내 환경을 입력하여 우선 적용을 해보고, 차차 원하는 파일들을 골라보자.

![image-20210317095256197](gitignore/image-20210317095256197.png)