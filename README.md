# gurii-gabreh.github.io

GitHub Pagesのユーザーサイト用リポジトリ。`https://gurii-gabreh.github.io/` 直下に `robots.txt` を置き、このドメイン配下で公開している全アプリ(`gurii-gabreh.github.io/<アプリ名>/`)について、AI学習への利用を拒否する意思表示を行うためだけに作成した(2026-11-21)。

- robots.txtはドメイン直下に置いたものだけが有効(RFC 9309)。各アプリのリポジトリ内に置いても効かないため、このリポジトリを作成した。
- 内容: IETF草案の共通トークン `__usage_ai-training` と、各社の学習用クローラー/制御トークン(GPTBot・ClaudeBot・Google-Extended・Applebot-Extended・CCBot・meta-externalagent)を拒否。検索エンジンのクロールは止めない。
- 経緯: ユーザー指示「作成したアプリで相手側の学習に使われるタイミングがあったら、禁止してほしい」(範囲: AI Lab+GitHub Pages、内容: 共通合図+名前指定)。進捗はprogress-tracker-dashboardで管理。
- 注意: 強制力は無く、守るかどうかは各社の任意。GitHub上のソースコード自体はこのファイルでは守れない。
