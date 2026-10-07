# 2026-form-validation

CodeGridの記事「フォームのバリデーションは、ブラウザにどこまで任せられるか」（全3回）のデモです。

- 記事: https://www.codegrid.net/series/2026-form-validation/
- デモ: https://codegrid.github.io/2026-form-validation/

## デモ一覧

### 第1回 ブラウザに任せるフォームバリデーションの基本

| ファイル | 内容 |
|---|---|
| [1/basic.html](https://codegrid.github.io/2026-form-validation/1/basic.html) | required属性とtype="email"だけでバリデーションするフォーム |
| [1/required-choice.html](https://codegrid.github.io/2026-form-validation/1/required-choice.html) | ラジオボタンとセレクトボックスを必須にする |
| [1/inputmode.html](https://codegrid.github.io/2026-form-validation/1/inputmode.html) | inputmode属性で数字用のキーボードを出す郵便番号の入力欄 |
| [1/range.html](https://codegrid.github.io/2026-form-validation/1/range.html) | min属性・max属性で人数と予約日の範囲を指定する |
| [1/step.html](https://codegrid.github.io/2026-form-validation/1/step.html) | step属性で小数を受け付ける（指定なしとの比較） |
| [1/minlength.html](https://codegrid.github.io/2026-form-validation/1/minlength.html) | minlength属性とrequired属性で3文字以上の入力を必須にする |
| [1/maxlength.html](https://codegrid.github.io/2026-form-validation/1/maxlength.html) | maxlength属性で貼り付けた値が切り捨てられる |

### 第2回 pattern属性と、ブラウザに任せきれないこと

| ファイル | 内容 |
|---|---|
| [2/pattern.html](https://codegrid.github.io/2026-form-validation/2/pattern.html) | pattern属性で郵便番号の書式を判定する |
| [2/pattern-tel-id.html](https://codegrid.github.io/2026-form-validation/2/pattern-tel-id.html) | 電話番号と会員IDの書式を指定する |
| [2/pattern-required.html](https://codegrid.github.io/2026-form-validation/2/pattern-required.html) | pattern属性は空欄を判定しない（required属性との比較） |
| [2/pattern-hyphen.html](https://codegrid.github.io/2026-form-validation/2/pattern-hyphen.html) | 文字クラスの中のハイフンはエスケープする（`[0-9-]`と`[0-9\-]`の比較） |
| [2/pattern-password.html](https://codegrid.github.io/2026-form-validation/2/pattern-password.html) | 英大文字・英小文字・数字を含む8文字以上のパスワード |
| [2/user-invalid.html](https://codegrid.github.io/2026-form-validation/2/user-invalid.html) | :invalidと:user-invalidの違い |

### 第3回 novalidate属性で、エラーの表示を自前で行う

| ファイル | 内容 |
|---|---|
| [3/novalidate.html](https://codegrid.github.io/2026-form-validation/3/novalidate.html) | novalidate属性を付けると、エラーがあっても送信される |
| [3/custom-error.html](https://codegrid.github.io/2026-form-validation/3/custom-error.html) | 判定はブラウザ、表示は自前で行うフォーム |

`sent.html`は、各デモのフォームを送信したときに表示するページです。
