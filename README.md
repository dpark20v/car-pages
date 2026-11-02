# Jarvis

브라우저에서 바로 돌아가는 개인 AI 비서예요. Claude API를 사용하고, 서버 없이 정적 HTML 하나로 동작해요.

## 사용법

1. `index.html`을 GitHub Pages 같은 정적 호스팅에 올리거나 브라우저로 직접 열어요.
2. 처음 열면 나오는 설정 창에 [Anthropic API 키](https://console.anthropic.com/settings/keys)를 입력해요.
3. 대화를 시작하면 돼요.

## 기능

- 답변이 실시간으로 표시돼요(스트리밍).
- 모델을 고를 수 있어요(기본값은 Claude Opus 5.5).
- 대화 기록이 브라우저에 저장되고, 새 대화를 만들거나 지울 수 있어요.
- 설정에서 Jarvis의 성격(시스템 프롬프트)을 바꿀 수 있어요.
- 모바일 화면도 지원해요.

## 보안 참고

API 키는 브라우저의 localStorage에만 저장되고 `api.anthropic.com`으로만 전송돼요. 키가 브라우저 안에 있기 때문에 공용 컴퓨터에서는 쓰지 마세요. 사이트를 다른 사람과 공유해도 각자 자기 키를 입력해야 해요.

## 자료실

- `porsche-911-992.html`: 포르쉐 911 (992) 소개 페이지
- `car-parts-encyclopedia.html`: 자동차 부품 백과사전
