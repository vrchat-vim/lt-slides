---
marp: true
theme: uncover
class:
    - invert

size: 16:9
paginate: true

---

# Vim(Neovim)プラグイン今昔物語
yank.nvim
2023/07/30
![bg brightness:0.7](https://raw.githubusercontent.com/vrchat-vim/lt-slides/main/vim-plugins-old-and-new/bg.png)

---

# 自己紹介
- VRChat.vim管理者
- Neovim使い
- Python, Rustなどを触っている

---

# 昨今のプラグイン事情
- 今までプラグインはVimScriptで書かれることがほとんどだった
- しかしNeovimの登場により、より高速で自由度の高いLuaでプラグインが書けるように
- さらにdenops.vimなどの登場により、Vimのプラグインにも世代交代が訪れている

---

# 有名プラグインの今と昔

---

## ファイラー
- 昔: NERDTree ([preservim/nerdtree](https://github.com/preservim/nerdtree))
    - 今でもVimといえばこれ！と言っても過言ではないプラグイン
    - シンプルかつ使いやすい
- 今: fern.vim ([lambdalisue/fern.vim](https://github.com/lambdalisue/fern.vim))
    - VimScript製、Vim/Neovim両対応のファイラー
    - 複数の表示モードやパフォーマンスの向上など、かゆいところに手が届くような進化を着実にしている

---

## プラグインマネージャー
- 昔: vim-plug ([junegunn/vim-plug](https://github.com/junegunn/vim-plug))
    - 昔からあるVim用パッケージマネージャ
    - 最低限の機能がついている
- 今: lazy.nvim ([folke/lazy.nvim](https://github.com/folke/lazy.nvim))
    - **控えめに言ってやばい**
    - きれいなUI、非常に扱いやすい遅延ロード、起動時間表示など大量の機能がついているNeovim用パッケージマネージャー

---

## ステータスライン
- 昔: vim-airline ([vim-airline/vim-airline](https://github.com/vim-airline/vim-airline))
    - 今でもVim用のステータスラインなら一番手
    - Vimのステータスラインをファンシーにする
- 今: lualine.nvim ([nvim-lualine/lualine.nvim](https://github.com/nvim-lualine/lualine.nvim))
    - Lua製のステータスライン
    - パフォーマンスの向上やテーマ・コンポーネント機能、設定がよりしやすくなるなど扱いやすくなっている

---

## 補完
- 昔: neocomplete.vim ([Shougo/neocomplete.vim](https://github.com/Shougo/neocomplete.vim))
    - みんな大好きShougoWare
    - この時代からShougoWareの片鱗が見える設定のしやすさ
- 今: ddc.vim([Shougo/ddc.vim](https://github.com/Shougo/ddc.vim))
    - **ShougoWareは進化するよどこまでも**
    - denops.vimを使うことによりVim/Neovim双方で高いパフォーマンスを実現
    - 設定がより細分化されさらにカスタマイズしやすく

---

# 結論
- Neovimの登場によりプラグインのLua化が進み、より高速化や設定の細分化が行われている
- 一昔前のVimしか触ったことがない人はぜひ最新のプラグインを触ってみてほしい

