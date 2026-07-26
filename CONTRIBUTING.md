# Contributing

이 프로젝트에 기여해 주셔서 감사합니다.

이 저장소는 GitHub의 Fork, Branch, Commit, Push, Pull Request 과정을 실습하기 위한 오픈소스 학습용 저장소입니다.
기여자는 자신의 자기소개 Markdown 파일을 추가하는 방식으로 참여할 수 있습니다.

## 기여 방법

### 1. 저장소 Fork

이 저장소를 자신의 GitHub 계정으로 Fork합니다.

### 2. Fork한 저장소 Clone

```bash
git clone https://github.com/<username>/github-practice.git
cd github-practice
```

### 3. 작업 브랜치 생성

브랜치 이름은 다음 규칙을 사용합니다.

```text
docs/<username>
```

### 4. 자기소개 파일 작성

`participants` 디렉터리에 자신의 GitHub 사용자 이름으로 Markdown 파일을 추가합니다. 세부 내용은 `template.md`를 참고합니다.

```text
participants/<username>.md
```

다른 참여자의 파일은 수정하지 않습니다.

### 5. 변경 사항 확인

```bash
git status
git diff
```

Pull Request에는 자신의 자기소개 Markdown 파일 1개만 포함되어야 합니다.

### 6. Commit

변경한 파일을 Staging Area에 추가합니다.

```bash
git add participants/<username>.md
```

Commit 메시지는 다음 형식을 사용합니다.

```text
docs: <변경 내용>
```

이 저장소에서는 문서 파일만 추가하므로 `docs` 태그만 사용합니다.

### 7. Push

작업 브랜치를 자신의 Fork 저장소에 Push합니다.

```bash
git push -u origin docs/<username>
```

### 8. Pull Request 생성

다음 방향으로 Pull Request를 생성합니다.

```text
<내 Fork>:docs/<username> → <원본 저장소>:main
```
