# 나랏말

> 한글코딩 및 플랫폼 관련된 문제로 인하여 영어로 포팅하였습니다. 이 저장소는 앞으로 관리되지 않을 예정이며 한글 코딩을 해보고 싶으신 분들은 가져다 사용하셔도 좋습니다.
>
> 이 저장소의 코드를 가져다 사용함으로써 발생하는 문제는 책임지지 않습니다.
>
> 가급적 영어 및 .Net Standard 2.0 기반으로 포팅한 [Naramal](https://github.com/steamb23/Naramal) 을 이용해주시기 바랍니다.

C#에서의 유연한 한글처리를 위해 만들어진 라이브러리입니다. 유니코드2.0부터
정립된 Hangul Syllables 기반으로 동작하여 한글의 자소를 분리하고 다시 이를
합칠 수 있습니다. 이 라이브러리를 사용하면 한글을 보다 유연하게 처리할 수
있습니다.

## 사용 방법
위키에 서술 예정입니다.

## 왜 대부분 한글로 코딩되어 있나요?

한글을 다루는 라이브러리인 만큼 클래스, 함수, 변수의 이름을 한글로 하는 것도
좋을 것 같았습니다. 또한 라이브러리의 구성요소를 한글로 작성함으로써 타
라이브러리와 구분성을 높일 수 있다고 생각합니다. 다만 부분적으로 .Net BCL에
의존해야 하는 부분은 어쩔 수 없이 영문으로 작성하였습니다.

분명 한글로 코딩된 것에 대해 거부감을 느끼시는 분들도 있습니다. 제가 작성한
코드는 대부분 MIT 라이센스로 배포하고 있기 때문에 필요하시다면 라이센스 조건
하에 마음대로 바꾸어 쓰셔도 좋습니다.

## License
MIT License

Copyright (c) 2020 SteamB23

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
