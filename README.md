# 골드문 업로드 안내

이 폴더 안의 파일을 GitHub 저장소 최상단에 올리면 됩니다. 폴더째 넣지 말고 `index.html`, `functions` 폴더, `README.md`가 바로 보이게 올리세요.

## Cloudflare Pages 설정

- Framework preset: `None`
- Build command: `exit 0`
- Build output directory: `/`
- Root directory: 비워두기

## 관리자 기능 설정

Cloudflare Pages 프로젝트에서 다음 값을 설정해야 저장 기능이 동작합니다.

1. Settings > Variables and Secrets
   - `ADMIN_PASSWORD`: 관리자 비밀번호
   - `SESSION_SECRET`: 길고 랜덤한 문자열

2. Settings > Bindings
   - KV namespace binding
   - Variable name: `GOLDMOON_KV`
   - KV namespace: 새로 만든 골드문용 KV

관리자 열기: 홈페이지에서 `DIABLO IV PRICE BOARD` 배지를 1.4초 길게 누르거나 `Ctrl + Alt + A`를 누릅니다.
