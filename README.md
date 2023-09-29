# Next LangChain Vector DataBase Sample

## 開発環境

### 開発言語

- [TypeScript](https://typescriptbook.jp/)

### フロントエンドフレームワーク

- [Next js (App router)](https://nextjs.org/docs)

### CSSフレームワーク

- [Tailwind CSS](https://tailwindcss.com/)

### データベース

- [Supabase](https://supabase.com/)

### OpenAI関連

- [OpenAI](https://platform.openai.com/)
- [LangChain](https://js.langchain.com/docs/get_started/introduction/)

## 簡単な流れ

1. PDFを読み込み
2. 読み込んだデータを分割
3. 分割したデータをembeddingsしてベクトルデータに変換してデータベースに保存
4. データベースに保存したベクトルデータと質問から回答を得る

## 環境変数

- `.env.local.example`を`.env.local`に変更
- `OPENAI_API_KEY`にOpenAI APIのAPIキーを指定
- `SUPABASE_PRIVATE_KEY`にSupabaseのPRIVATEキーを指定
- `SUPABASE_URL`にSupabaseのURLを指定

## node_modulesをインストール

```bash
npm install
```

## 簡易サーバー起動

```bash
npm run dev
```

## 読み込むPDF

ディレクトリ`data`に`pg.pdf`を用意
