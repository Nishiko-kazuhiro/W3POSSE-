<!DOCTYPE html>
<html lang="ja">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>メンバー紹介カード</title>
  <!-- Tailwind CSS CDN -->
  <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-slate-100 text-slate-800 min-h-screen flex items-center">

  <!-- ページ全体の中央寄せコンテナ（max-w-* と mx-auto） -->
  <main class="max-w-5xl mx-auto px-6 py-12 w-full">
    
    <!-- 見出しエリア -->
    <header class="text-center mb-10">
      <h1 class="text-3xl font-bold text-slate-900 mb-2">自己紹介</h1>
      <p class="text-slate-600">メンバーの紹介です。</p>
    </header>

    <!-- 3枚のカードを並べるFlexboxコンテナ -->
    <!-- スマホ幅では縦並び(flex-col)、sm(640px)以上で横並び(sm:flex-row) -->
    <div class="flex flex-col sm:flex-row justify-between items-stretch gap-6">

      <!-- カード1 -->
      <article class="flex-1 bg-white rounded-2xl shadow-md p-6 border border-slate-200 flex flex-col items-center text-center transition duration-300 hover:-translate-y-1 hover:shadow-xl">
        <span class="text-5xl mb-4" role="img" aria-label="ノートパソコン">💻
        </span>
        <h2 class="text-xl font-bold text-slate-900 mb-2">佐藤 健太</h2>
        <p class="text-sm text-slate-600 leading-relaxed">
          得意科目は体育です。野球部に所属しています。
        </p>
      </article>

      <!-- カード2 -->
      <article class="flex-1 bg-white rounded-2xl shadow-md p-6 border border-slate-200 flex flex-col items-center text-center transition duration-300 hover:-translate-y-1 hover:shadow-xl">
        <span class="text-5xl mb-4" role="img" aria-label="パレット">🎨</span>
        <h2 class="text-xl font-bold text-slate-900 mb-2">鈴木 花子</h2>
        <p class="text-sm text-slate-600 leading-relaxed">
          得意科目は国語です。読書が好きでよく図書館に行きます。
        </p>
      </article>

      <!-- カード3 -->
      <article class="flex-1 bg-white rounded-2xl shadow-md p-6 border border-slate-200 flex flex-col items-center text-center transition duration-300 hover:-translate-y-1 hover:shadow-xl">
        <span class="text-5xl mb-4" role="img" aria-label="ロケット">🚀</span>
        <h2 class="text-xl font-bold text-slate-900 mb-2">田中 太郎</h2>
        <p class="text-sm text-slate-600 leading-relaxed">
          得意科目は数学です。問題を解くのが好きで、勉強熱心です。
        </p>
      </article>

    </div>
  </main>

</body>
</html>