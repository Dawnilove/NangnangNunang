# 면책 조항 (Disclaimer)

**바탕화면 고양이** · Copyright (c) 2026 Dawnilove

이 문서는 프로그램을 쓰기 전에 알아 둬야 할 위험과 책임의 범위를 정리한 거예요.
프로그램을 설치하거나 실행하면 이 내용에 동의한 것으로 봐요.
라이선스 전문은 [LICENSE](LICENSE)에 있어요.

---

## 1. 있는 그대로 제공해요

- 이 프로그램은 개인이 취미로 만든 것이고, **"있는 그대로(AS IS)"** 제공해요.
- 잘 동작한다는 것, 특정 목적에 맞는다는 것, 오류나 중단이 없다는 것, 다른 권리를 침해하지 않는다는 것을 **보증하지 않아요**.
- 업데이트, 오류 수정, 기술 지원을 해 줄 의무도 없어요.

## 2. 바탕화면 아이콘을 실제로 움직여요

- 고양이는 장난을 칠 때 **바탕화면 아이콘의 위치를 실제로 바꿔요.** 파일 자체는 건드리지 않아요.
- 켤 때 아이콘 자리를 저장해 두고 **우클릭 → 아이콘 돌려놓기**로 되돌릴 수 있지만, 아이콘이 추가·삭제되거나 Windows가 배치를 바꾸면 완전히 되돌리지 못할 수 있어요.
- 아이콘 배치가 중요하다면 **설정 → 아이콘 장난치기**를 꺼 두세요.

## 3. Claude 질문 기능

- 답은 AI가 만든 거라 **틀리거나 오래된 내용이 있을 수 있어요.** 중요한 결정(건강·법률·돈 등)에는 그대로 믿지 말고 꼭 확인하세요.
- 질문은 사용자가 고른 방식으로 Anthropic에 보내져요.
  - **Claude Code 구독**: 이 PC의 Claude Code를 실행해 답을 받아요. 사용량은 사용자의 구독 한도에 포함돼요.
  - **API 키**: `api.anthropic.com`에 직접 보내요. 요금은 사용자의 Anthropic 계정에 청구돼요.
- Claude 이용에는 **Anthropic의 이용 약관과 사용 정책**이 적용돼요. 이를 지키는 건 사용자의 책임이에요.
- 비밀번호, 주민등록번호, 회사 기밀 같은 **민감한 정보는 질문에 넣지 마세요.**

## 4. API 키와 보안

- API 키는 Windows DPAPI로 암호화해 이 PC에만 저장해요. 그래도 **PC가 악성 프로그램에 감염되거나 다른 사람이 같은 Windows 계정에 접근하면 키가 새어 나갈 수 있어요.**
- 키가 유출됐다고 의심되면 바로 [Anthropic Console](https://console.anthropic.com)에서 키를 폐기하고 새로 만드세요.
- 키 유출, 무단 사용, 그로 인한 요금에 대해 저작권자는 책임지지 않아요.

### 지켜 주세요

- 프로그램은 **공식 배포 위치에서만** 받으세요. 다른 곳에서 받은 파일은 바꿔치기됐을 수 있어요.
- 받은 파일은 함께 올린 `.sha256` 값과 비교해 확인하세요.
  ```powershell
  Get-FileHash .\DesktopCat-Portable-1.0.0.exe -Algorithm SHA256
  ```
- 쓰지 않는 API 키는 지우고, 키에는 꼭 필요한 만큼의 사용 한도를 걸어 두세요.
- Windows와 백신을 최신 상태로 유지하세요.

## 5. 서명하지 않은 프로그램이에요

- 실행 파일에 코드 서명이 없어서, Windows가 **"PC 보호"** 경고를 띄우거나 백신이 의심 파일로 볼 수 있어요.
- **Smart App Control**이 켜진 Windows 11에서는 서명 없는 실행 파일이 **아예 실행되지 않아요.** 그 기능을 끄는 건 보안 수준을 낮추는 일이고 되돌릴 수 없으니, 저작권자는 끄라고 권하지 않아요.
- PyInstaller로 만든 프로그램에서 흔히 생기는 일이에요. 불안하면 받은 파일의 `.sha256` 값을 확인하고, 공식 배포 위치(Releases)에서만 받으세요.

## 6. 책임의 범위

법이 허락하는 한, 저작권자는 다음에 대해 **책임지지 않아요.**

- 프로그램을 쓰거나 쓰지 못해서 생긴 직접·간접·우연·특별·결과적 손해
- 데이터 손실, 바탕화면 배치 변화, 업무 중단, 이익 손실
- AI 답변 내용, 또는 그것을 믿고 한 행동의 결과
- API 키·계정 유출, 악성 프로그램, 무단 접근 같은 보안 사고
- 공식 배포 위치가 아닌 곳에서 받았거나 다른 사람이 고친 프로그램으로 생긴 문제
- Anthropic, Microsoft 등 다른 회사 서비스의 장애·변경·요금

다만 저작권자의 고의나 중대한 과실로 생긴 손해처럼, 법상 책임을 없앨 수 없는 경우는 예외예요.

## 7. 상표와 관계

- "Claude"와 "Anthropic"은 Anthropic PBC의 상표예요.
- 이 프로그램은 **Anthropic의 공식 제품이 아니며**, Anthropic과 제휴·후원·보증 관계가 없어요.
- Windows는 Microsoft Corporation의 상표예요.

## 8. 문제를 발견하면

보안 문제를 발견하면 공개된 곳에 자세히 쓰지 말고 저작권자(Dawnilove)에게 먼저 알려 주세요.

---

*English summary: Desktop Cat is a personal hobby project provided "AS IS" without any warranty. It really moves your desktop icons (not files). AI answers may be wrong. Your use of Claude is subject to Anthropic's terms, and API usage is billed to your account. Keep your API key safe; the author is not liable for key leaks, malware, data loss, or any damages to the extent permitted by law. Not affiliated with or endorsed by Anthropic.*
