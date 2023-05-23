# cheetah

シフト管理するWebアプリケーションです

## 構想

### 必須

- DBに事前にシステム管理者（店長など）が登録したユーザーのみログイン可能にする。（IDとパスワードを事前に教えておくなど）
- ユーザーはHomeからシフトの登録、変更、確認などが出来る。
- シフト登録時には日時と自分が出来るポジションを登録する。
- バックエンド側で各時間帯の出勤者のポジションを確認、程よく振り分ける。

### 可能であれば

- シフト提出期日などを設定できるようにする？
- 管理者画面を作成、全ユーザー単位のシフト提出状況や合計勤務時間、過去のシフト等を確認できるようにする？

## 使用言語とフレームワーク

- Java(SpringBoot)
- HTML/CSS+JavaScript(余裕があればReact, Vue.jpなど)

## データベース

- MySQL

## データベース設計

- 未定
