# URECEIPT

## ToDo List

- [ ] ユニバーサル参照を使用した関数テンプレートでラムダ式のコンセプト制約
- [ ] OPENFILENAME 構造体を入力用と出力用の2つ用意する
- [ ] シーン移行を排除して統合
- [ ] 出力時に細かい仕様の追加(元のreceiptsからの削除や組み合わせの追加出力等)

## In Progress

## Completed

- [x] 文字が対象の文字と等しいかどうかを確認する非型テンプレート関数の追加(MyCommon)
- [x] inputkeyの改善(std::expectedを使用)
- [x] FileProcessor.ixxの見直し(ファイル読み込み時点で一行目のチェックを実行し、不適なら再入力など)
- [x] receiptsとconfigをmyDataに統合

## Cancelled
- std::vector receiptsをflat_multimapに変更
- これを引数に持つ関数をテンプレートにしてコンセプトで制約
(<flat_map>がVisualStudioに未対応のため)
- これらをgitのブランチマージで行う(新しくブランチを作る意味がなかったため)