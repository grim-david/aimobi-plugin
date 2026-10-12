# aimobi 플러그인

Claude Code에서 `/아이루`로 회사 시스템의 코드와 운영 DB(읽기 전용)를 확인하며 대화합니다. 윈도우·맥 모두 따로 설치할 프로그램이 없습니다.

## 설치

먼저 관리자에게 **개인 토큰**(`aimobi_`로 시작)을 받습니다. 그다음 둘 중 편한 쪽으로 설치합니다.

**Claude Code 대화창에서**

```
/plugin install aimobi --marketplace grim-david/aimobi-plugin
```

설치 중 토큰을 묻는 칸에 받은 토큰을 붙여 넣습니다.

**터미널에서**

```
claude plugin marketplace add grim-david/aimobi-plugin
claude plugin install aimobi@aimobi --config token=받은토큰
```

## 업데이트

새 버전이 나오면 터미널에서:

```
claude plugin marketplace update aimobi
claude plugin update aimobi@aimobi
```

또는 Claude Code의 `/plugin` → Marketplaces → aimobi에서 업데이트합니다. 여기서 자동 업데이트를 켜 두면 시작할 때마다 알아서 받습니다. 업데이트 뒤 앱을 재시작합니다. 토큰은 다시 넣지 않아도 됩니다.

## 사용

새 대화를 열고 `/아이루 <질문>`. 예: `/아이루 통합배반 차량 목록은 어떤 예약 상태를 빼?`

- 서버는 평일 09~19시에만 켜집니다.
- 토큰은 다른 사람에게 주지 마세요. 잃어버렸으면 관리자에게 새로 받으면 됩니다.
