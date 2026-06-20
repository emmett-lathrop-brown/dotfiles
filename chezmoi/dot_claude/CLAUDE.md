# CLAUDE.md — global house core (`~/.claude/CLAUDE.md`)

正本 = dotfiles の `chezmoi/dot_claude/CLAUDE.md`（`chezmoi apply` で `~/.claude/CLAUDE.md` に展開）。
全プロジェクトで**常に読まれる**「横断 house 挙動の核」。編集は dotfiles 側で行う。

> **1ルール = 1ホーム（二重管理ゼロ）**: cross-repo の規約・methodology・progress-tracking は
> dotagent の `house` plugin / superpowers が正本（CI・clone 先にも効く）。ここには重複させず、
> **「この Mac の自分の Claude セッションで常に効かせたいローカル挙動」だけ**を書く。

## House behavior

- 個人 repo の `main` は意図的に **branch protection を付けない**（force-push 運用・履歴 scrub のため）。
  GitHub の「Your main branch isn't protected」バナーは**無視**し、保護を有効化しない。
