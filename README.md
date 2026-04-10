# examinee.github.io

Reverse Engineering & Malware Analysis 기술 블로그

## 로컬 셋업

```bash
# 1. Hugo 설치 (Windows - Chocolatey)
choco install hugo-extended

# 또는 Hugo 설치 (Windows - Scoop)
scoop install hugo-extended

# 2. 리포 클론
git clone --recursive https://github.com/examinee/examinee.github.io.git
cd examinee.github.io

# 3. 테마 서브모듈 초기화 (이미 클론 시 --recursive 했으면 생략)
git submodule update --init --recursive

# 4. 로컬 서버 실행
hugo server -D

# 5. http://localhost:1313 에서 확인
```

## 새 글 작성

```bash
# 새 포스트 생성
hugo new posts/my-new-post.md

# draft: false 로 바꾸면 배포됨
```

## 배포

`main` 브랜치에 push하면 GitHub Actions가 자동으로 빌드 및 배포합니다.
