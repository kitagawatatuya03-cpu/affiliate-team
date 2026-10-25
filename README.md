# affiliate-team

Claude Code で動かすアフィリエイト運用チームです。ルールは `CLAUDE.md` にまとめています。

## 使い方（このフォルダで `claude` を起動して話しかける）
1. 「researcher で〇〇ジャンルの案件を調べて」
2. 「strategist で今月の戦略案を作って」 → **あなたが承認①**
3. 「writer-adult で〇〇の X 投稿を作って、compliance でチェックして」
4. `review/` を見て **あなたが承認②** → 「この案を approved に移して」
5. 投稿は自分で行う（予約投稿ツールでも可）
6. 週1回 CSV を `data/` に置いて「analyst で週次レポートを作って」

## 最初にやること
- `rules/brand-voice.md` を記入する
- 使うASPと、その規約のURLを researcher に伝える
