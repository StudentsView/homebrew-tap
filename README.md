# HanX Homebrew tap

로컬 AI 에이전트가 엑셀 파일을 읽고 수정하고 수식을 계산하도록 HanX CLI를 설치합니다. macOS 13 이상에서 Apple Silicon과 Intel을 지원합니다. Node.js는 필요하지 않습니다.

## Homebrew 설치

Homebrew가 설치된 Mac에서 실행합니다.

```sh
brew install StudentsView/tap/hanx
```

## 설치 확인

```sh
hanx --version
hanx capabilities --pretty
```

## 업데이트

```sh
brew update
brew upgrade StudentsView/tap/hanx
```

## npm으로 설치

Homebrew 대신 npm을 사용할 수도 있습니다. Node.js 18 이상이 필요합니다. 두 방법 모두 실행 명령은 `hanx`입니다.

```sh
npm install -g @juyoungsuh/hanx
```

[공개 npm 패키지](https://www.npmjs.com/package/@juyoungsuh/hanx)에서 버전을 확인하세요.

## 사용 안내

[CLI 안내](https://github.com/StudentsView/HanX/blob/main/docs/cli/README.md)에 엑셀 수식과 파일 편집 및 MCP 연결 방법이 있습니다.

원본 배포 파일은 [HanX Releases](https://github.com/StudentsView/HanX/releases)에서 가져오며 SHA256을 확인합니다. 네이티브 실행 파일과 JSON/MCP 문서 도구만 설치합니다. GUI 앱은 원본 저장소의 pkg를 이용하세요.

본 제품은 한컴의 HWP 문서 파일(.hwp) 공개 문서를 참고하여 개발하였습니다.
