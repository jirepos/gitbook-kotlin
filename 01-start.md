# 시작하기

* VS Code에서 익스텐션 설치
  * Kotlin Language 익스텐션 설치
  * Code Runner 설치 
* [Github](https://github.com/JetBrains/kotlin/releases/tag/v1.7.21)에서 kotlin-최신버전.zip 다운로드 
* Windows 환경변수 path에 "코틀린 설치 디렉토리/bin" 설정  


```kotlin
fun main() {
    println("Hello World!")
    println("안녕하세요!")
}
```

* 한글 출력 시 output 창에 한글 깨짐
  * Java를 Code Runner 로 실행하면 한글 인코딩 에러가 발생한다.
  * -Dfile.encoding=utf8 작동 안함 
* Code Runner 실행 시 HelloWorld.kt가 있는 디렉토리에 HelloWorld.jar가 생성됨 
