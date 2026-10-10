# STRUCTURE · sisunstudio-sample

```
sisunstudio-sample/
├─ index.html                   단일 파일 (CSS·JS 인라인)
├─ wrangler.toml                name = sisunstudio-sample → sisunstudio-sample.lgt3232.workers.dev
├─ .assetsignore                img/·문서·index_*.html·ss-mood2.webp 배포 제외
├─ ss-serif-display(-italic).woff2   영문 제목 (Source Serif 4 Display · opsz 60)
├─ ss-serif-text.woff2          작은 영문 라벨·버튼 (Source Serif 4 Text · opsz 16)
├─ ss-pretendard.woff2          한글·본문 (사용 글자만 → 글자 추가 시 재생성)
├─ ss-hero.webp                 히어로 (흰 액자)
├─ ss-mood.webp                 Brow 섹션 무드 사진 (흰 장미)
├─ ss-g-01~32.webp              갤러리
├─ og-sisun.jpg                 공유 썸네일 1200×630
├─ img/                         다올 제공 원본 (배포 제외)
└─ CHANGELOG.md / STRUCTURE.md
```

## 섹션 순서
헤더 → 히어로 → `#philosophy`(흰) → `#lash`(sand) → `#brow`(stone) → `#gallery`(라이트박스 `#lb`) → `#guide`(sand · 토글 5) → `#visit`(링크 8칸 `.links`) → 푸터.

## 가격 수정
`.list dl` 안 `<div class="row"><dt>영문<small>한글</small></dt><dd>금액<small>원</small></dd></div>` 한 줄 = 한 항목. BEST 표시는 `<span class="best">Best</span>`.
