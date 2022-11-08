# v2.vuejs.org

> Important: This repository is for Vue 1.x and 2.x only. Issues and pull requests related to 3.x are managed in the [v3 doc repo](https://github.com/vuejs/docs-next).

This site is built with [hexo](http://hexo.io/). Site content is written in Markdown format located in `src`. Pull requests welcome!

## 기여 가이드

1. [ssafy-vue/kr.vuejs.org issue](https://github.com/ssafy-vue/kr.vuejs.org/issues)에서 번역 or 개선할 파일에 대한 이슈를 발행합니다.
2. 변경 내용 추적을 위해, 가급적 `Pull Request`전 `Draft`를 등록하고 리뷰 준비가 완료되면 `Pull Request`로 변환하여 리뷰 요청을 합니다.
3. 코드 리뷰가 끝나면 [ssafy-vue/kr.vuejs.org](https://github.com/ssafy-vue/kr.vuejs.org)에 `merge` 되고, 자동으로 사이트에 배포됩니다.

### Issue 양식

#### Title
작업에 대한 간략한 설명을 작성합니다.

> 메뉴 순서 변경

#### Label
작업 내용에 따라 라벨을 적절히 선택합니다.

- 번역 개선
- 번역 추가
- 성능 개선
- 레이아웃 개선

#### Comment
중복 작업을 방지하기 위해 작업 과정에서 변경이 예상되는 파일 목록을 작성합니다.


### Pull Request 양식

Title과 Label은 Issue와 동일하게 작성합니다.

#### Comment
작업 동기와 변경된 파일 목록을 작성합니다.

- example
``` text
### 동기
UI 접근성 향상을 위해 메뉴 순서를 변경

### 결과
Add : /src/v2/foo.md
Update : /src/v2/index.md
Delete : /src/v1/**
```

## Development

### 최초 클론시 1회 실행
``` bash
npm install
```

### 개발용 서버 시작

``` bash
npm run dev
```
* 서버 주소 : http://localhost:4000/ 
* 서버 종료 : 실행시킨 shell 에서 Ctrl + C 를 입력하여 종료합니다.

## On Translations

Translations for this documentation project are currently maintained in separate repositories forked from this original one.

### Arabic

Arabic translation is maintained by [Interstellar Club](https://github.com/InterstellarClub)

* Translation Repo - [/interstellarClub/ar.vuejs.org](https://github.com/interstellarClub/ar.vuejs.org)
* Primary Maintainers :
    * [Ilyes Chouia](https://github.com/celyes)
    * [Ahmed Aissaoui](https://github.com/Aissaoui-Ahmed)

### French

French translation is maintained by Vuejs-FR.
* Translation Repo - [/vuejs-fr/vuejs.org](https://github.com/vuejs-fr/vuejs.org)

### Italian

* Translation Repo - [/vuejs/it.vuejs.org](https://github.com/vuejs/it.vuejs.org)

### Japanese

Japanese translation is maintained by [Vue.js japan user group](https://github.com/vuejs-jp)

* Translation Repo - [/vuejs/jp.vuejs.org](https://github.com/vuejs/jp.vuejs.org)
* Primary maintainer - [kazupon](https://github.com/kazupon)
* Secondary Maintainers:
    * [re-fort](https://github.com/re-fort)
    * [potato4d](https://github.com/potato4d)
    * [oohira](https://github.com/oohira)

### Korean

Korean translation is maintained by [Vue.js Korean User group](https://github.com/vuejs-kr).

* Translation Repo - [/vuejs-kr/kr.vuejs.org](https://github.com/vuejs-kr/kr.vuejs.org)
* Translation Repo with SSAFY - [/Bogyie/kr.vuejs.org](https://github.com/Bogyie/kr.vuejs.org)
* Primary maintainer - [ChangJoo Park](https://github.com/ChangJoo-Park)

### Mandarin

* Translation Repo - [/vuejs/cn.vuejs.org](https://github.com/vuejs/cn.vuejs.org)

### Persian (Farsi)

Persian translation is maintained by VueJS-fa.

* Translation Repo - [/vuejs-fa/fa.vuejs.org](https://github.com/vuejs-fa/fa.vuejs.org)
* Primary maintainer - [Pooya Parsa](https://github.com/pi0)

### Português-Br

Português-Br translation is maintained by [Vuejs-Br](https://github.com/vuejs-br).

* Translation Repo - [/vuejs-br/br.vuejs.org](https://github.com/vuejs-br/br.vuejs.org)

### Russian

Russian translation is maintained by Translation Gang.

* Translation Repo - [/translation-gang/ru.vuejs.org](https://github.com/translation-gang/ru.vuejs.org)
* Primary maintainer - [Grigoriy Beziuk](https://gbezyuk.github.io)

### Spanish

* Translation Repo - [/1950Labs/vuejs.org](https://github.com/1950Labs/vuejs.org)
* Spanish translation is maintained by:

[1950Labs](https://1950labs.com) & [Vue.js Montevideo](https://www.meetup.com/Montevideo-Vue-JS-Meetup/):

- [Leonel More](https://github.com/leonelmore) | [Twitter](https://twitter.com/leonelmore)
- [Sebastián Camacho](https://github.com/sxcamacho) | [Twitter](https://twitter.com/sxcamacho)
- [Diana Rodríguez](https://github.com/alphacentauri82) | [Twitter](https://twitter.com/cotufa82)
- [Alejandro Parada](https://github.com/alejandro8605)
- [José Javier Señaris](https://github.com/pepesenaris) | [Twitter](https://twitter.com/pepesenaris)
- [Federico Kauffman](https://github.com/fedekau) | [Twitter](https://twitter.com/fedekauffman)
- [Fabián Larrañaga](https://github.com/FLarra) | [Twitter](https://twitter.com/FLarraa)
- [Pablo Marcano](https://github.com/Pablosky12) | [Twitter](https://twitter.com/stiv_ml)
- [Nicolás Tinte](https://github.com/Tintef) | [Twitter](https://twitter.com/NicoTinte)
- [Diego Barreiro](https://github.com/faliure)
- [Matías Verdier](https://github.com/MatiasVerdier) | [Twitter](https://twitter.com/matiasvj)
- [Pablo Kz](https://github.com/pabloKz)
- [Leonardo Fagundez](https://github.com/lfgdzdev) | [Twitter](https://twitter.com/Lfgdz)


### Vietnamese

Vietnamese translation is maintained by [Vue.js Vietnam User group](https://github.com/vuejs-vn/).

* Translation Repo: [/vuejs-vn/vuejs.org](https://github.com/vuejs-vn/vuejs.org)
* Primary maintainer - [phanan](https://github.com/phanan)

### Bahasa Indonesia

Bahasa Indonesia translation is maintained by [Vue.js Indonesia](https://github.com/vuejs-id/).

* Translation Repo: [/vuejs-id/docs](https://github.com/vuejs-id/docs)

### Want to help with the translation?

If you feel okay with translating quite alone, you can fork the repo, post a comment on the [Community Translation Announcements](https://github.com/vuejs/v2.vuejs.org/issues/2015) issue page to inform others that you're doing the translation and go for it.

If you are more of a team player, Translation Gang might be for you. Let us know somehow that you're ready to join this international open-source translators community. Feel free to contact [Grigoriy Beziuk](https://gbezyuk.github.io) or anybody else from [the team](https://github.com/orgs/translation-gang/people).

And thank you in advance ;)
