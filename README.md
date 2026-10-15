# 🤝 팀 협업 안내

아래 내용은 팀원 Git/GitHub 작업 방법입니다.

## 1. 시작하기 전에

### 저장소 받기

```bash
git clone https://github.com/zzengmo/18_kdt_01.git
cd 18_kdt_01
```

### Git 사용자 정보 등록

```bash
git config --global user.name "내이름"
git config --global user.email "내깃허브이메일"
```

---

## 2. 매일 작업 순서

```bash
# 1. 작업 시작 전 최신 내용 받기
git pull

# 2. 코딩 작업

# 3. 변경 파일 추가
git add .

# 4. 커밋
git commit -m "작업 내용 설명"

# 5. GitHub 업로드
git push
```

> ⚠️ 작업 시작 전 `git pull`을 먼저 실행하면 충돌을 줄일 수 있습니다.

---

## 3. 자주 쓰는 Git 명령어

| 명령어 | 설명 |
|---|---|
| `git pull` | 원격 저장소 최신 내용 받기 |
| `git add .` | 변경 파일 전체 추가 |
| `git commit -m "설명"` | 변경 내용 저장 |
| `git push` | GitHub에 업로드 |
| `git status` | 현재 변경 상태 확인 |
| `git log` | 커밋 기록 확인 |

---

## 4. 충돌이 발생했을 때

- 같은 파일을 여러 명이 동시에 수정하면 충돌이 발생할 수 있습니다.
- 각자 담당 파일을 중심으로 작업합니다.
- 공통 파일 수정 전 팀원에게 공유합니다.
- 충돌 발생 시 변경 내용을 확인한 뒤 함께 해결합니다.

---

