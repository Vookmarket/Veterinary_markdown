# Veterinary_markdown

## 目的

獣医学情報をmarkdown形式にまとめていきます。

## 構成

このフォルダのカテゴリ構成です

- 徴候(symptom)
- 疾病(disease)
- 検査(examination)
- 薬剤(drag)
- 処置(treatment)

## 更新法

- まずは情報源の情報(new_informationディレクトリ)を参照し、定義、概念、事実、数値、その他データ、考察(考察者)、参考文献に関する情報を列挙する。
- 列挙された情報が関連するカテゴリをdisease, drag, examination, symptom似たいしてタグづけ(複数可)し校正したものを、new_informationディレクトリ内に更新前に抽出した情報を「proofread.md」としてまとめる(校正はしても要約は可能な限りしない)。
- diseaseディレクトリを内のファイル構成を確認し、列挙された情報が関連するファイル名を列挙する。
- ディレクトリ内にあるtemplateディレクトリの.mdを確認し、ファイルの内部構成を確認する。
- 関連性の高いファイルが存在しない場合は、新たにファイルを作成する。
- 列挙されたファイルを順に開き、情報をtemplateとproofed_text.mdに従って更新する。
- カテゴリディレクトリのREADMEやindexを�