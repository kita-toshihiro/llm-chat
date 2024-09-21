### LLM（大規模言語モデル）とは

[LLM（大規模言語モデル）](https://ja.wikipedia.org/wiki/%E5%A4%A7%E8%A6%8F%E6%A8%A1%E8%A8%80%E8%AA%9E%E3%83%A2%E3%83%87%E3%83%AB) 
とは、人工知能（AI）の一種であり、コンピュータが人間の言語を理解し、自然な文章を生成するための技術。LLMは与えられたキーワードや質問に対して適切な回答を生成したり、ある言語から別の言語への翻訳を行ったり、特定のテーマに基づいた創作文章を生成したりすることができる。LLMを用いると、ユーザーの意図を理解し、文脈に応じた自然な対話が可能となる。教育、医療、ビジネスなど、様々な分野で応用が進められている。
[ハルシネーション](https://ja.wikipedia.org/wiki/%E3%83%8F%E3%83%AB%E3%82%B7%E3%83%8D%E3%83%BC%E3%82%B7%E3%83%A7%E3%83%B3_(%E4%BA%BA%E5%B7%A5%E7%9F%A5%E8%83%BD))（もっともらしいウソを教えてくること）には注意が必要。

[Transformer](https://ja.wikipedia.org/wiki/Transformer_(%E6%A9%9F%E6%A2%B0%E5%AD%A6%E7%BF%92%E3%83%A2%E3%83%87%E3%83%AB))（GPTやGeminiで採用されている計算方法）の図式的説明（[デモサイト](https://poloclub.github.io/transformer-explainer/)）

[The Full Story of Large Language Models and RLHF](https://www.assemblyai.com/blog/the-full-story-of-large-language-models-and-rlhf/)   
（[日本語での記事](https://gigazine.net/news/20230623-rlhf-llm/)）

<br>

### まずはChatGPTやGeminiを標準のチャット画面で利用してみる

プロンプト（入力文字）に「〇〇についての４択問題を２問作成してください。」と書いて送信したら、クイズ問題２問が作成されましたか。

何度も同じプロンプトを送信してみると、問題の内容が毎回変わり、問題文の書式も一定でなく変化することがわかります。自分が望む形式で出力してほしい場合は、例示を含めるなど、プロンプトの書き方を工夫する必要があります。

**演習：** 小テスト問題を生成するときに各問題の**解説**も出力するようなプロンプトを入力して、実際に生成してみてください。

<br>

### APIを使ってGPT, Gemini の機能を利用する

ChatGPTのウェブサイトやスマートフォンアプリでGPTを使ったり、Geminiのウェブサイトやスマートフォンアプリで Geminiを使ったりすることでも、十分に便利さを享受できますが、API（プログラムから呼び出して処理結果を受け取る仕組み）を使ってそれらの機能を使うことができると、自分が作ったプログラム、アプリなどからGPTやGeminiを呼び出して利用することができ、更に様々な用途の可能性が広がります。

ChatGPT APIの料金を全て紹介！GPT3.5とGPT4-Turbo、最新のGPT-4oについても！（AITech）  
（なお GPT3.5 は、今は
[GPT-4o-mini](https://openai.com/index/gpt-4o-mini-advancing-cost-efficient-intelligence/) に取って代わられています）  
[https://aitechworld.info/chatgpt-api-price/](https://aitechworld.info/chatgpt-api-price/)  

Google AI Studio & Vertex AI Studio：Gemini API 利用方法の違い（クラウドエース）  
（無料で使える枠もあるようですが、その場合、入力データがモデル学習に使われることに注意です）
[https://zenn.dev/cloud_ace/articles/e5c13b4fdaeb42](https://zenn.dev/cloud_ace/articles/e5c13b4fdaeb42)

**APIの利用料**は、頻繁に変更されるので、都度、以下でチェックをしておくのが良いです：  
Pricing (OpenAI) [https://openai.com/api/pricing/](https://openai.com/api/pricing/)  
Gemini API Pricing (Google) [https://ai.google.dev/pricing](https://ai.google.dev/pricing)

<br>

### 本日の講座参加者のためのデモサイト

[https://jula1.rcis.jp:6677/](
https://jula1.rcis.jp:6677/)

