# SEVEN WRITING Cursor Rules - MDC Version

세븐 라이팅은 하나의 콘텐츠 아이디어를 바탕으로, 다음 7가지 형식의 콘텐츠를 AI를 활용해 자동 또는 반자동으로 생성하는 전략적 콘텐츠 생성 방법입니다.

1. 블로그 게시글
2. X 및 Thread SNS 게시글
3. 이메일 뉴스레터
4. 쇼츠(Shorts) 영상 대본
5. 프레젠테이션 슬라이드용 지시문
6. 팟캐스트 또는 라디오 스크립트
7. 유튜브 영상 대본

## Claude Code Max 플랜 사용자인 경우
AI를 무제한으로 활용 가능하므로 콘텐츠를 대량으로 한번에 생성할 수 있습니다. 
반복작업 없이 프롬프트만 잘 설계하면 블로그, SNS글, 영상대본 등을 자동으로 연속 생성할 수 있습니다. 이 세븐 라이팅 전략을 기반으로 하면 콘텐츠 대량생산에 효율적입니다.

## IDE - AI연동 지원되는 IDE나 Editor 사용
- Cursor

## Cursor Rules 폴더
```bash
📁 seven-writing-cursor_rules
    ├── .cursor/rules
    │   ├── image_prompts_blog.mdc
    │   ├── image_prompts_short_movie.mdc
    │   ├── image_prompts_youtube.mdc
    │   └── workflow_guide.mdc
```

## 콘텐츠 포멧별 하위폴더 구성
```bash
01_writing/
  ├── 001_memo/
  │   ├── 01_active/
  │   └── 02_close/
  ├── 100_blog/
  │   ├── 01_draft/
  │   └── 02_commit/
  ├── 200_x•threads/
  │   ├── 01_draft/
  │   └── 02_commit/
  ├── 300_mail-magazine/
  │   ├── 01_draft/
  │   └── 02_commit/
  ├── 400_razio/
  │   ├── 01_draft/
  │   └── 02_commit/
  ├── 500_short-movie/
  │   ├── 01_draft/
  │   └── 02_commit/
  ├── 600_presen/
  │   ├── 01_draft/
  │   └── 02_commit/
  └── 700_youtube/
      ├── 01_draft/
      └── 02_commit/
```

## 사용법
1. memo 폴더에 리서치 정보난 기사 리소스의 파일을 넣음
2. AI에 지시하기 (Claude Code)
3. "워크 플로 파일을 따라 실행하십시오." 지시문 실행
4. AI사 출력을 말하시면 10분 내외로 각 준비된 폴더에 출력 생성


## 유지보수

```
다음과 같은 측면에서 워크플로를 수정합니다.
- 블로그는 후크가 효과적인 리드 문장을 작성하는 방법
- Youtube는 10분의 척도로 하는 것
```
## 사용자 정의

`.cursor/rules/` 디렉토리의 MDC 파일을 편집하여 AI 동작과 템플릿을 사용자 정의할 수 있습니다.

## 사용법
1. memo 폴더에 리서치 정보나 기사 리소스 파일을 넣습니다.
2. Claude Code에서 지시합니다.
```
워크플로우 파일 절차에 맞춰 실행해 주세요.
```
3. AI가 출력을 생성하며 10~20분정도 미리 준비한 각 폴더별로 출력물이 생성됩니다.

## 유지보수 방법
지시문을 수정하고 싶을 경우의 방법을 설명합니다.
아래와 같이 Claude Code에게 아래와 같이 지시하면 됩니다.
```
워크플로우 수정 사항
1. 블로그: 후킹(관심 끌기) 효과 있는 리드문 작성
2. 유튜브: 영상 길이 10분으로 제한
```
위와 같은 지시문으로 프롬프트가 업데이트됩니다.
즉, 실제로 사용하면서 자신만의 워크플로우 프롬프트로 업데이트하는 것을 추천합니다.

이 기능을 활용하여 확장하면 워드프레스에 글등록을 하거나 Notion, Obsidian과 연동하여 확장도 고려해볼 수 있습니다.

## 작성자
김 재 우 (JAEWOO, Kim)
email: gaebalai.official@gmail.com

## 라이센스

MIT 라이센스하에 게시됩니다. 자세한 내용은 [LICENSE](LICENSE) 파일을 참조하십시오.