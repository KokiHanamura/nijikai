# CLAUDE.md

<!-- 50〜100 行以内を目安に。共通ワークフローは .claude/rules/harness.md（claude-harness 管理）にある。 -->

# nijikai

結婚式二次会の案内ページ（友人有志による非公式ページ）。GitHub Pages で公開: https://kokihanamura.github.io/nijikai/

## Commands

| Command | Description |
|---------|-------------|
| `python3 -m http.server 8000` | ローカル確認 → http://localhost:8000/ |

## Architecture

- `index.html` 1 枚に HTML・CSS・JS をまとめている。写真（`shop-*.jpg` など）と `qr.png` は同じ階層
- `main` に push すると Pages に自動で反映される

## Gotchas

- 公開ページなので、参加者の個人情報（氏名一覧・連絡先など）は載せない
- 写真を追加するときはスマホ表示を前提にサイズを抑える
