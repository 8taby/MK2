# MK2
![무제_1_](https://user-images.githubusercontent.com/97948617/193410877-c9b1a223-8acc-4671-a823-58ea414a1a56.svg)

**MK2** 스킨은 Material Kit 2를 Tistory에 적용한 반응형 스킨입니다. 다국어 타이포그래피와 머티리얼 디자인, 시각적 통일성을 목표로 하고 있습니다.

> **Material Kit**는 Google의 머티리얼 디자인에 영감을 받은 신선한 무료 Bootstrap 5 UI입니다. 저희는 여러분의 무수한 요청에 이것을 만들었습니다. 사용하기 간편하고 아름다운 구성 요소들로 여러분께 머티리얼 컨셉을 전할 수 있어서 영광입니다. Bootstrap 요소를 재구성하면서 세 가지 완성된 예시 페이지를 통해 여러분의 다음 프로젝트에서 디자인하는 데 도움이 되기를 바랍니다.
> 
> **Material Kit**는 빛, 면, 그리고 동작을 이용합니다. 다양한 색상, 선명한 이미지, 대축척 타이포그래피에 특화되어 있습니다. 일반 레이아웃에서는 마치 여러 장의 종이를 겹쳐 놓은 듯한 모습으로 다양한 레이어를 배치해 깊이와 순서가 명확히 보이도록 합니다. 네비게이션이 왼쪽에 자리잡고, 모든 상호작용은 오른쪽 공간에서 이루어집니다.
> 
> 이 새로운 디자인은 잉크와 종이, 그리고 일상생활에서 객체와 재료가 상호작용하는 방식에 대한 연구의 결과물입니다. 그 결과로 다음 프로젝트에서도 사용할 수 있는 아름답고 일관된 요소 세트가 만들어집니다. **Material Kit**는 웹에 접속할 수 있는 Android 애플리케이션이 시각적으로 유사한 인상을 남기면서 일관성을 유지해야 하는 경우 훌륭한 도구입니다. 또한 **Material Kit**는 세련된 웹 페이지를 만드는 데 도움이 되는 매력적인 도구입니다.
>
> [Creative Tim의 Material Kit 2 소개 중](https://github.com/creativetimofficial/material-kit#readme)

## Example

![image](https://user-images.githubusercontent.com/97948617/193433972-bd9c1fb8-65ec-473f-96d9-49889b54b28f.png)
v0.2.3 [자세히 알아보기](README.md#v023)

![image](https://user-images.githubusercontent.com/97948617/193627687-0644c52a-544d-4318-b9cf-76f4e5898bd1.png)
v0.3.0 [자세히 알아보기](README.md#v030)

![image](https://user-images.githubusercontent.com/97948617/194706805-3f4cd069-8718-48bd-b9ad-32c8e3491dfa.png)
v0.3.3 [자세히 알아보기](README.md#v033)

![image](https://user-images.githubusercontent.com/97948617/194732989-ef5df541-8aa4-4005-b5cc-5c07d7cce5d0.png)
v0.3.5 [자세히 알아보기](README.md#v035)

[Acta non Verba by A-NV](https://acta-non-verba.tistory.com/)에서 적용된 모습을 확인하실 수 있습니다.

## Structure

    SKIN ┬ index.xml
         ├ skin.html
         ├ style.css
         ├ preview.gif
         ├ preview256.jpg
         ├ preview560.jpg
         ├ preview1600.jpg
         └ images ┬ script.js
                  ├ bootstrap.bundle.min.js
                  ├ background.jpg
                  ├ background.jpg
                  └ background.jpg

### index.xml

스킨 정보 파일로 자세한 내용은 '스킨 정보 파일' 장에서 다룹니다.

### skin.html

스킨의 메인 템플릿 파일로 치환자를 사용해 각 url에 해당하는 HTML 결과물로 치환됩니다.

### style.css

css 분리를 위한 파일이며 skin.html과 마찬가지로 스킨에디터에서 편집할 수 있습니다.

### preview

티스토리 각 영역에서 미리보기를 표시하기 위한 파일압니다.

  preview.gif : 미리보기 기본 파일로 아래 파일이 없는 경우에 사용 (112x84)
  preview256.jpg : 사용 중인 스킨 미리보기 (256x192)
  preview560.jpg : 스킨 목록 미리보기 (560x420)
  preview1600.jpg : 스킨 상세보기 미리보기 (1600x1200)

### images

필수요소가 아닌 파일은 모두 images 아래에 위치하게 됩니다. image, script, css 등을 업로드하여 스킨에서 사용합니다.

### 🔜 더 자세한 내용은 [여기](https://tistory.github.io/document-tistory-skin/common/files.html)를 참고하시기 바랍니다.

## Download

### [최신 버전 다운로드하기](https://github.com/8taby/MK2/releases/latest)

## Details

### Font

MK2에서는 Apple 기기에서의 시스템 설정과 비슷한 사용자 경험을 모든 이용자에게 제공하기 위해 [Pretendard Variable](https://github.com/orioncactus/pretendard) 폰트를 사용하고 있습니다. `style.css` 파일에서 `font-family`를 변경하실 수 있습니다

한자를 표시할 때 `Pretendard` 폰트가 적용되지 않는 경우가 있음을 고려해 [Pretendard JP Variable](https://github.com/orioncactus/pretendard/tree/main/packages/pretendard-jp) 폰트를 추가로 지원합니다.

## License

MK2 스킨은 라이선스 및 저작권을 고지하며 사용, 복제, 변경, 통합, 발행, 배포, 재실시, 판매에 대한 제약을 포함한 어떠한 제약 없이 취급할 수 있습니다. 자세한 법률적 사항은 [Wikipedia/MIT 허가서](https://ko.wikipedia.org/wiki/MIT_%ED%97%88%EA%B0%80%EC%84%9C)를 참고하시기 바랍니다.

> 라이선스 모두 보기
[MK2](https://github.com/8taby/MK2/blob/main/LICENSE) | [Material Kit 2 by Creative Tim](https://github.com/creativetimofficial/material-kit/blob/master/LICENSE.md) | [Pretendard/Pretendard Variable](https://github.com/orioncactus/pretendard/blob/main/LICENSE)

## Version

### v0.0.1

**30 Sep 2022**

- 개발 계획을 수립했습니다.

### v0.1.0

**30 Sep 2022**

- [Material Kit 2 by Creative Tim](https://github.com/creativetimofficial/material-kit)을 티스토리 스킨 형식에 맞게 수정했습니다.
- 일부 링크를 수정했습니다.
- font-family [Pretendard](https://github.com/orioncactus/pretendard)로 변경했습니다.

### v0.1.1

**30 Sep 2022**

    ❗ 이 버전은 Release되어 있지 않습니다.

- footer와 body의 section이 제대로 분리되지 않는 문제를 수정했습니다.

### v0.2.0

**1 Oct 2022**

- **Tistory의 공통치환자를 적용했습니다.**
- Creative Tim으로 연결되는 일부 링크를 수정했습니다.
- Tistory의 css 용량 제한 문제를 해결했습니다.

    🤔 [이곳](https://www.websiteplanet.com/ko/webtools/jscssminifier/)에서 용량을 줄일 수 있습니다.

- 구독 버튼을 생성했습니다.(네비게이션 바 오른쪽)
- Tistory 기본 홈 버튼과 구독 버튼을 삭제했습니다.

### v0.2.1

**1 Oct 2022**

- preview.png 파일 세트를 업로드했습니다.

### v0.2.2

**2 Oct 2022**

- preview.jpg 파일 세트였습니다. 앞으로는 확장자를 잘 보도록 하겠습니다.
- .js 파일의 저장 위치를 `./assets/js/...`에서 `./images/...`로 변경했습니다.
- 네비게이션 바에 Tistory 메뉴바의 기능을 일부 적용했습니다.
    - 티스토리 홈으로 돌아가기
    - 티스토리 스토리 페이지로 가기
    - 티스토리 포럼으로 가기
    - 티스토리 매니저 페이지로 가기
- 네비게이션 바의 깃허브 버튼에 호버링할 때 타이틀 문구가 바뀌었습니다.

### v0.2.3

**2 Oct 2022**

- 일부 이미지 파일의 경로가 `./images...`로 되어 있는 것을 `./images/...`로 수정했습니다.
- 홈 화면의 본문 섹션 내에 글을 작성할 수 있는 공간을 만들었습니다.

### v0.2.4

**3 Oct 2022**

- 스크롤 바를 삭제했습니다.
- 카테고리 미리보기로 사용할 수 있는 공간을 탑재했습니다.

### v0.2.5

**3 Oct 2022**

- url로 티스토리 게시물에 접근 시 발생할 수 있는 Google Adsense의 작동 방해를 방지할 수 있는 js 코드를 삽입했습니다.

### v0.3.0

**4 Oct 2022**

    ❗ 이 버전은 Release되어 있지 않습니다.

- 본문 카드 영역 위에 작은 카드 영역을 삽입했습니다.
- 브레드크럼을 사용할 수 있습니다.
- 검색 기능을 사용할 수 있는 `<s_search>` 태그를 작동할 수 있게 만들었습니다.

### v0.3.1

**6 Oct 2022**

- 브레드크럼을 삭제했습니다. 브레드크럼은 추후 추가될 예정입니다.
- 본문과 제목, 카테고리가 출력됩니다.
- 콘텐츠 태그를 모두 작성해 두었습니다. 하지만 적당한 태그 내에 들어가 있지 않는 문제로 일부 태그는 출력되지 않거나 비정상적으로 출력됩니다.

### v0.3.2

**8 Oct 2022**

- 스크롤바를 환원했습니다. 오버레이 스크롤바를 적용할 줄 아시는 분은 연락 바랍니다.
- Footer 부분의 링크를 블로그 운영자로 변경했습니다.
- 글 제목과 글 본문 카드를 분리했습니다.
- 글 본문을 그리드에 맞춰 정렬했습니다.

### v0.3.3

**8 Oct 2022**

- 시간을 표시할 때 고정폭 숫자를 사용하도록 설정했습니다.
- 시간을 표시할 때 가운데에 맞춘 쌍점을 사용하도록 설정했습니다.
- 스크롤바를 없애는 것을 기본 방침으로 하겠습니다. 아래로 내리기는 불편하지만 분명 이렇게 하는 게 콘텐츠에 집중하는 데 도움이 되겠지요. 오락가락 하는 것 같아 보여도 어느 방법이 가장 완벽할지를 찾는 과정이랍니다.
- 검색 결과를 표시하는 카드에서 작성 일시와 게시물 제목 사이에 수직선 `|`을 추가했습니다.
- footer 영역의 모든 아이콘 링크를 바꾸었습니다.
- footer 영역에 블로그 이름과 블로그 대표 이미지가 출력되도록 하였습니다.

### v0.3.4

**8 Oct 2022**

- 관리 권한이 있을 때 보이는 온클릭 이벤트 탭을 추가했습니다.
- 검색 카드에서 검색 버튼의 크기를 개선했습니다.
- 검색 결과 카드를 수정했습니다.
- 방문자 수 카드를 추가했습니다.
- 하단 footer의 링크를 linktree로 변경했습니다.

### v0.3.5

**9 Oct 2022**

- 한자를 표시할 때 `Pretendard Variable` 폰트가 적용되지 않는 문제를 해결했습니다.
- `Pretendard JP Variable` 폰트를 기본으로 사용하고, 한국 한자를 표현할 필요가 있을 경우에만 스타일시트 `ss05`를 사용할 수 있도록 설정했습니다.
- `0.3.4` 버전에서 사용된 `color-primary` 클래스를 삭제했습니다.(`text-primary`와 중복)

## Contributer

MK2 스킨 개발에 기여해 주실 분을 찾습니다.

### Roadmap

#### v0.1.0
    0. Material Kit 2를 Tistory에 이식
        0-1. <s_t3> 태그 적용
#### v0.2.0
        0-2. 공통치환자 적용
        0-3. 필수 파일, 리소스 파일 경로 수정
#### v0.3.0
    1. 검색 결과 리스트
    2. 검색 결과 댓글 리스트
#### v0.4.0
    3. 위치 로그
    4. 태그 클라우드
#### v0.5.0
    5. 방명록
        5-1. 방명록 글쓰기
        5-2. 방명록 리스트
    6. 공지사항 글
    7. 보호 글
#### v0.6.0
    8. 글
        8-1. 글 제목 | 카테고리 | 작성일 | 글 관리
        8-2. 글
        8-3. 글 관련 태그
        8-4. 트랙백 | 댓글
        8-5. 트랙백
        8-6. 댓글
            8-6-1. 댓글 리스트
            8-6-2. 댓글 쓰기
    9. 페이지
#### v0.7.0 - 0.9.0
    자잘한 오류 수정
#### v1.0.0
    v1 Release

### TODO

- [x] font-family `"Pretendard Variable"`로 변경
- [ ] 스킨 세부 지정
    - [x]  홈
    - [x]  글
    - [ ]  카테고리
    - [ ]  태그
    - [ ]  위치로그
    - [ ]  방명록
- [x] 모바일에서 사용자 경험이 저하되는 문제
- [ ] 검색 결과 페이지에서 검색어 입력 칸에 문자가 겹쳐 표시되는 문제
- [x] 모든 링크 수정
- [ ] 이미지 파일 변경
- [x] 저작권 표시 수정
- [ ] HTML 문서와 CSS 파일 재개발
- [ ] Material Kit 2 Pro로 업그레이드
- [ ] Category별 badge 색상 변경
- [ ] 홈 화면 정비

## Next

**MK2** 스킨의 _v1 Release_ 개발을 완료한 뒤에는 [Soft UI Design System](https://www.creative-tim.com/product/soft-ui-design-system)을 이용한 티스토리 스킨을 만들어 볼 예정입니다.
