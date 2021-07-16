# Git CLI Backup

## 용어정리

* Local Repositoty: 지역 저장소

* Remote Repository: 원격 저장소

* `push`: `Local Repositoty `__->__`Remote Repository`

  __<->__ ` pull`



## 저장소(Reposity) 생성

> [git hub](https://github.com/) 접속 -> 우측 상단의 `+`클릭->`new repository`
>
> ->`repository name`에 repositroy이름 입력->`Description`작성 자유롭게
>
> ->`public`은 오픈소스 프로젝트, `private`은 나와 등록한 동료들만 확인 가능(유료)
>
> ->`create depository`



## 저장소(Repository) 연결

* `git bash`에서  `git log`통해 지역저장소 확인 가능

>  ___Git bash에서..___
>
>  * 원격 저장소 연결하기
>   * `git remote add` `원격저장소의 별명`(일반적으로 origin을 쓴다.)`원격저장소의 주소`(깃허브에서 __HTTPS__로 되어 있는 것 선택)
>  * 원격저장소 주소 보기
>   * `git remote -v` 입력



## push 해보기(저장하고 버전만든 후)

*  `git bash`에 `git push`입력 시 마지막 줄에 `git push --set--upstream origin master`출력된다.
*  그대로 복붙해서 다시 입력해주면 `origin(아까 설정했던 원격저장소의 별명)`에 `master라는 브랜치`로 업로드 된다.
*  git hub의 아이디와 비밀번호 입력하기
*  업로드 끝



## clone 해보기(backup한 것을 복원)

* `git clone` `주소` `디렉토리`
* `cd` `만들어진 디렉토리`
* `ls -al` 해보면 원격저장소에서 복제하여 지역저장소가 만들어진 것 확인 가능



