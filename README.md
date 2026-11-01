# HanX Homebrew tap

로컬 AI 에이전트가 엑셀 파일을 읽고 수정하고 수식을 계산하도록 HanX CLI를 설치합니다. macOS 13 이상에서 Apple Silicon과 Intel, Linux에서는 Ubuntu 22.04 이상 x64를 지원합니다. 설정 실행기에 Node.js를 사용하며 Homebrew가 함께 준비합니다.

## Homebrew 설치

Homebrew가 설치된 macOS 또는 Linux에서 실행합니다.

```sh
brew install StudentsView/tap/hanx
hanx setup
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
hanx setup
```

[공개 npm 패키지](https://www.npmjs.com/package/@juyoungsuh/hanx)에서 버전을 확인하세요.

## 사용 안내

[CLI 안내](https://github.com/StudentsView/HanX/blob/main/docs/cli/README.md)에 엑셀 수식과 파일 편집 및 MCP 연결 방법이 있습니다.

원본 배포 파일은 [HanX Releases](https://github.com/StudentsView/HanX/releases)에서 가져오며 SHA256을 확인합니다. 설치 후 방향키와 Enter로 GUI만, CLI만, 둘 다를 선택합니다. 자동 설치에는 `hanx setup --components all --yes`를 사용하세요. GUI만 선택해도 작은 설정 실행기는 유지하며 앱은 내부 문서 엔진을 사용합니다. Windows에서는 npm 또는 원본 저장소의 Setup.exe를 사용하세요.
