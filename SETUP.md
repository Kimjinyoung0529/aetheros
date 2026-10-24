# aetheros · 내도메인.한국 → GitHub Pages 연결

도메인: `aetheros.o-r.kr`  
Pages 대상: `Kimjinyoung0529.github.io` (이 레포)

## 1. 내도메인.한국에서 (필수)

1. [내도메인.한국](https://www.xn--i40bx54a9qb.kr/) 로그인
2. `aetheros.o-r.kr` **수정** 화면 열기
3. **고급설정 / Advanced** → **별칭 (CNAME)** 선택
4. 값에 정확히 입력:
   ```
   Kimjinyoung0529.github.io
   ```
5. 보안코드(캡차) 입력 → **수정하기**
6. A 레코드/IP는 비워 두세요 (CNAME만)

DNS 전파는 보통 수 분~수십 분 걸려요.

## 2. GitHub Pages (이미 준비됨)

- 레포: https://github.com/Kimjinyoung0529/aetheros
- Source: `main` 브랜치 / 루트 (`/`)
- CNAME 파일 내용: `aetheros.o-r.kr`

설정 확인: https://github.com/Kimjinyoung0529/aetheros/settings/pages

## 3. HTTPS

DNS가 잡히고 GitHub가 인증서를 발급하면 Pages 설정에서 **Enforce HTTPS**를 켜세요.

## 참고

- 무료 `.o-r.kr` 는 **주기적 갱신**(대략 3개월)이 필요해요. 만료되면 사이트가 끊깁니다.
- 모회사: https://aetherion.o-r.kr/
