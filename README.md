# 🎮 TETRIS — Play & Compete

> 누구나 플레이하고 점수를 등록해 경쟁할 수 있는 테트리스

**[▶ PLAY NOW](https://your-username.github.io/tetris)**

---

## 기능

- 🎮 클래식 테트리스 (NES 점수 방식)
- 👻 고스트 피스 / 홀드 / 다음 피스 미리보기
- 🏆 점수 리더보드 (상위 100명)
- 📱 모바일 터치 컨트롤 지원
- ⚡ 설치 불필요 — 단일 HTML 파일

## 조작법

| 키 | 동작 |
|---|---|
| ← → | 이동 |
| ↑ / Z | 회전 |
| ↓ | 소프트 드롭 |
| Space | 하드 드롭 |
| C | 홀드 |
| P / Esc | 일시정지 |

## GitHub Pages 배포

```bash
# 1. 레포 생성 (이름: tetris)
# 2. 파일 업로드
git init
git add .
git commit -m "init tetris"
git remote add origin https://github.com/YOUR_NAME/tetris.git
git push -u origin main

# 3. Settings → Pages → Branch: main → Save
# 4. https://YOUR_NAME.github.io/tetris 접속
```

## 점수 저장 방식

localStorage 기반 — 같은 기기/브라우저에서 점수가 유지됩니다.
전 세계 공유 리더보드가 필요하면 Supabase 연동을 추가하세요.
