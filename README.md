## Marp 란?
- markdown으로 PPT를 작성할 수 있는 도구입니다.
- markdown을 사용함으로써 작성이 편리하며, version control도 Git을 통해 기존 보다 효율적일 것입니다.

## Marp 사용 법

1. VSCode Extension - Marp for VS Code 설치
   
   https://marketplace.visualstudio.com/items?itemName=marp-team.marp-vscode

2. theme를 사용하기 위해서는 vscode settings.json 설정이 필요합니다.

   예시는 .vscode/settings.json입니다.
   반드시 css 파일을 다운로드 하지 않고, github raw link로 연결해도 됩니다.

3. 기본적으로 markdown 문법을 사용하며, html 구문도 사용이 가능합니다.
   
   슬라이드 구분은 "---"으로 가능합니다.
   
   자세한 내용은 sample.md를 참조하여 작성합니다.

4. Export는 vscode extension을 통해 가능 합니다. (파일 탭 우측 marp icon 클릭 -> Export slide deck)
     - export 가능한 확장자 : ppt, pdf, png...

- 이 테마는 아직 완성되지 않았습니다. 지속적인 디자인 피드백 또는 css 잘 다루는 분이 개선해주시면 좋겠습니다.

이 테마, sample 파일은 marp 공식 테마인 gaia와 ttyskg/marp-themes(https://github.com/ttyskg/marp-themes) default+, sample.md를 참조하여 만들어졌습니다. (MIT License)