### 参考サイト
[Vim Cheat Sheet](https://vim.rtorr.com/lang/ja)<br>
[Vim幼稚園からVim小学校へ](https://qiita.com/hachi8833/items/7beeee825c11f7437f54)

## 移動
### 全体・段落
| キー | 説明 |
:---:|:---: 
| gg | ファイルの先頭に移動 |
| G | ファイルの末尾に移動 |
| ctrl + u | 半画面分上に移動 |
| ctrl + d | 半画面分下に移動 |
| H | 画面上部に移動 |
| L | 画面下部に移動 |
| alt (option) + k | 前の段落の先頭に移動 |
| alt (option) + j | 次の段落の先頭に移動 |

### 単語・かっこ
| キー | 説明 |
:---:|:---: 
| b	| 単語の先頭に進む |
| w |	単語の先頭に戻る |
| e | 単語の末尾に進む |
| ge | 単語の末尾に戻る |
| % |	対となる括弧へ移動 |

## 検索

### 全体
| キー | 説明 |
:---:|:---: 
| / | 順方向に文字列検索 |
| ? | 逆方向に文字列検索 |
| n | 順方向に繰り返し検索 |
| N | 逆方向に繰り返し検索 |

### 一行
| キー | 説明 |
:---:|:---: 
| f | その行の順方向に一文字検索 | 
| F | その行の逆方向に一文字検索 | 
| t | その行の順方向に一文字検索(カーソルは文字の手前) | 
| T | その行の逆方向に一文字検索(カーソルは文字の手前) | 
| ; |	順方向に繰り返し検索 |
| , |	逆方向に繰り返し検索 |

## 選択（ビジュアルモード）
| キー | 説明 |
:---:|:---: 
| v | ビジュアルモード開始
| V | 行単位のビジュアルモード
| o | 選択範囲の反対側に移動
| Ctrl + v | 矩形ビジュアル
| O | 矩形の反対側の角に移動
| aw | 単語を選択
| ab | () のブロックを選択
| aB | {} のブロックを選択
| at | <> タグのブロックを選択
| ib | () ブロックの括弧を除いた内側を選択
| iB | {} ブロックの括弧を除いた内側を選択

## エディタ
| キー | 説明 |
:---:|:---: 
| gh | 前のタブに切り替え |
| gl | 次のタブに切り替え |
