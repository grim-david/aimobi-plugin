# aimobi 플러그인

Claude Code에서 `/아이루`로 회사 시스템의 코드와 운영 DB(읽기 전용)를 확인하며 대화합니다. 윈도우·맥 모두 별도 프로그램 없이 동작합니다.

## 설치

1. 관리자에게 개인 토큰을 받습니다.
2. 터미널(또는 Claude Code 안에서 `/plugin` 대신 아래 명령):

```
claude plugin marketplace add grim-david/aimobi-plugin
claude plugin install aimobi@aimobi --config token=<받은 토큰>
```

Claude Code 대화창에서는 `/plugin install aimobi --marketplace grim-david/aimobi-plugin` 으로 설치하고, 토큰 칸에 받은 토큰을 넣습니다.

3. 새 대화에서 `/아이루 <질문>`.

서버는 평일 09~19시에만 켜집니다.
