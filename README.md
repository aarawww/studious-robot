!DOCTYPE html>
<html lang="ja">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>OW2学生鯖</title>
    <!-- Tailwind CSS CDNを読み込み -->
    <script s<rc="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700;800&display=swap" rel="stylesheet">
    <style>
        /* Interフォントを全体に適用 */
        body {
            font-family: 'Inter', sans-serif;
            background-color: #0d1117; /* GitHub Dark Modeのような背景色 */
            color: #f0f6fc;
        }
        /* ボタンのアニメーション */
        .btn-primary {
            transition: transform 0.2s, box-shadow 0.2s;
            background: linear-gradient(90deg, #6366f1 0%, #a855f7 100%); /* 紫〜インディゴのグラデーション */
        }
        .btn-primary:hover {
            transform: translateY(-2px);
            box-shadow: 0 10px 20px rgba(168, 85, 247, 0.4);
        }
        /* Overwatchのテーマに合わせた紫系のアクセントカラー */
        .accent-text {
            color: #a855f7;
        }
        .card-bg {
            background-color: #161b22; /* カードの背景色 */
        }
    </style>
</head>
<body class="min-h-screen">

    <!-- ヘッダーナビゲーション -->
    <header class="shadow-lg sticky top-0 z-10 bg-opacity-95 bg-[#0d1117] backdrop-blur-sm">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-4 flex justify-between items-center">
            <!-- ロゴ/タイトル -->
            <h1 class="text-2xl font-extrabold tracking-tight text-white flex items-center">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 mr-2 accent-text" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
                  <path stroke-linecap="round" stroke-linejoin="round" d="M12 6.253v13m0-13C10.832 5.477 9.246 5 7.5 5S4.168 5.477 3 6.253v13C4.168 18.477 5.754 18 7.5 18s3.332.477 4.5 1.253m0-13C13.168 5.477 14.754 5 16.5 5s3.332.477 4.5 1.253v13C19.832 18.477 18.246 18 16.5 18s-3.332.477-4.5 1.253" />
                </svg>
                <span class="accent-text">OW2</span>学鯖
            </h1>
            <!-- ナビゲーションリンク (モバイルでは非表示) -->
            <nav class="hidden md:flex space-x-6 text-sm font-semibold">
                <a href="#about" class="hover:text-gray-400">コミュニティ紹介</a>
                <a href="#features" class="hover:text-gray-400">活動内容</a>
                <a href="#join" class="hover:text-gray-400">参加方法</a>
            </nav>
        </div>
    </header>

    <!-- メインコンテンツ -->
    <main>
        <!-- ヒーローセクション -->
        <section class="text-center py-20 md:py-32 relative overflow-hidden">
            <!-- 背景のグラデーション/エフェクト -->
            <div class="absolute inset-0 opacity-10" style="background: radial-gradient(circle at 50% 10%, #a855f7, transparent 60%);"></div>
            
            <div class="relative max-w-4xl mx-auto px-4">
                <p class="text-lg font-semibold mb-3 accent-text uppercase tracking-wider">学生限定 & 全プラットフォーム対応</p>
                <h2 class="text-5xl sm:text-6xl md:text-7xl font-extrabold mb-6 leading-tight">
                    <span class="block">最高の仲間と</span>
                    <span class="block text-transparent bg-clip-text bg-gradient-to-r from-indigo-400 to-purple-500">戦場を支配せよ。</span>
                </h2>
                <p class="text-xl text-gray-400 mb-8 max-w-2xl mx-auto">
                    同じ学校、同じ年代の仲間とチームアップ。カジュアルからランクマッチ、大会出場まで、学生生活をもっと熱くする最高のOverwatch 2コミュニティへようこそ！
                </p>
                <a href="#join" class="btn-primary inline-block py-3 px-8 rounded-full text-lg font-bold shadow-2xl hover:scale-105 transform">
                    Discordサーバーに参加する！
                </a>
            </div>
        </section>

        <!-- コミュニティ紹介セクション -->
        <section id="about" class="py-16 md:py-24 bg-[#161b22]">
            <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
                <div class="text-center mb-12">
                    <h3 class="text-4xl font-bold mb-3">
                        <span class="accent-text">「OW2学鯖」</span>とは？
                    </h3>
                    <p class="text-gray-400">安心・安全な学生限定のゲーム環境を提供します。</p>
                </div>

                <div class="grid md:grid-cols-3 gap-8">
                    <!-- カード 1 -->
                    <div class="card-bg p-6 rounded-xl shadow-xl hover:shadow-2xl transition duration-300 border border-gray-700/50">
                        <div class="text-3xl mb-3 accent-text font-extrabold">1</div>
                        <h4 class="text-xl font-bold mb-3">安心の学生限定サーバー</h4>
                        <p class="text-gray-400">荒らしや迷惑行為の心配なく、安心してゲームを楽しめる環境を維持しています。</p>
                    </div>
                    <!-- カード 2 -->
                    <div class="card-bg p-6 rounded-xl shadow-xl hover:shadow-2xl transition duration-300 border border-gray-700/50">
                        <div class="text-3xl mb-3 accent-text font-extrabold">2</div>
                        <h4 class="text-xl font-bold mb-3">ランクの壁なし</h4>
                        <p class="text-gray-400">ブロンズからトップ500まで、すべてのランク帯のメンバーが在籍。実力に関係なく、気軽に一緒にプレイできる相手が見つかります。</p>
                    </div>
                    <!-- カード 3 -->
                    <div class="card-bg p-6 rounded-xl shadow-xl hover:shadow-2xl transition duration-300 border border-gray-700/50">
                        <div class="text-3xl mb-3 accent-text font-extrabold">3</div>
                        <h4 class="text-xl font-bold mb-3">カスタム＆イベント</h4>
                        <p class="text-gray-400">定期的なカスタムマッチ、コーチングセッション、コミュニティ内トーナメントなど、楽しい企画が盛りだくさん！</p>
                    </div>
                </div>
            </div>
        </section>

        <!-- 活動内容/特徴セクション -->
        <section id="features" class="py-16 md:py-24">
            <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
                <h3 class="text-center text-4xl font-bold mb-12">主な<span class="accent-text">活動内容</span></h3>
                
                <div class="grid md:grid-cols-2 lg:grid-cols-4 gap-6">
                    <!-- Feature Item 1: 即席チームアップ -->
                    <div class="p-5 card-bg rounded-lg shadow-lg text-center border border-indigo-500/30">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-10 w-10 mx-auto accent-text mb-3" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
                          <path stroke-linecap="round" stroke-linejoin="round" d="M13 10V3L4 14h7v7l9-11h-7z" />
                        </svg>
                        <h5 class="font-bold text-lg mb-1">即席チームアップ</h5>
                        <p class="text-sm text-gray-400">「@（ランク）」コマンドで、すぐにランク/カジュアルの仲間を見つけられます。</p>
                    </div>
                    
                    <!-- Feature Item 2: チーム・クランメンバー募集 -->
                    <div class="p-5 card-bg rounded-lg shadow-lg text-center border border-indigo-500/30">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-10 w-10 mx-auto accent-text mb-3" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
                            <!-- Users icon path -->
                            <path stroke-linecap="round" stroke-linejoin="round" d="M17 20v-2a4 4 0 00-4-4H5a4 4 0 00-4 4v2m16-16a4 4 0 11-8 0 4 4 0 018 0zM7 8a4 4 0 100-8 4 4 0 000 8z" />
                        </svg>
                        <h5 class="font-bold text-lg mb-1">チーム・クランメンバー募集</h5>
                        <p class="text-sm text-gray-400">固定チームや大会参加を目的としたクランメンバーをいつでも募集・結成できます。</p>
                    </div>
                    
                    <!-- Feature Item 3: 勉強会/コーチング -->
                    <div class="p-5 card-bg rounded-lg shadow-lg text-center border border-indigo-500/30">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-10 w-10 mx-auto accent-text mb-3" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
                          <path stroke-linecap="round" stroke-linejoin="round" d="M12 8c1.657 0 3 .895 3 2s-1.343 2-3 2h-1l-2 2v-4h3z" />
                          <path stroke-linecap="round" stroke-linejoin="round" d="M21 12a9 9 0 11-18 0 9 9 0 0118 0z" />
                        </svg>
                        <h5 class="font-bold text-lg mb-1">勉強会/コーチング</h5>
                        <p class="text-sm text-gray-400">上手い人のリプレイ添削や、プロによるコーチング企画を実施！</p>
                    </div>
                    <!-- Feature Item 4: オフゲーム交流 -->
                    <div class="p-5 card-bg rounded-lg shadow-lg text-center border border-indigo-500/30">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-10 w-10 mx-auto accent-text mb-3" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
                          <path stroke-linecap="round" stroke-linejoin="round" d="M8 7v8a2 2 0 002 2h6M8 7V5a2 2 0 012-2h4.586a1 1 0 01.707.293l4.414 4.414a1 1 0 01.293.707V19a2 2 0 01-2 2h-2.5" />
                        </svg>
                        <h5 class="font-bold text-lg mb-1">オフゲーム交流</h5>
                        <p class="text-sm text-gray-400">趣味や学校生活の話題、雑談チャンネルでゲーム外でも友達作り。</p>
                    </div>
                </div>
            </div>
        </section>

        <!-- 参加方法セクション -->
        <section id="join" class="py-16 md:py-24 bg-[#161b22]">
            <div class="max-w-4xl mx-auto px-4 sm:px-6 lg:px-8 text-center">
                <h3 class="text-4xl font-bold mb-10">今すぐ<span class="accent-text">参加</span>しよう！</h3>
                
                <!-- 参加ステップ -->
                <div class="grid md:grid-cols-3 gap-6 mb-10">
                    <div class="card-bg p-6 rounded-lg border border-purple-500/50">
                        <p class="text-5xl font-extrabold accent-text mb-2">1</p>
                        <h4 class="text-xl font-bold mb-2">Discordに参加</h4>
                        <p class="text-gray-400 text-sm">下記のボタンから公式Discordサーバーに参加してください。</p>
                    </div>
                    <!-- 変更されたステップ 2 -->
                    <div class="card-bg p-6 rounded-lg border border-purple-500/50">
                        <p class="text-5xl font-extrabold accent-text mb-2">2</p>
                        <h4 class="text-xl font-bold mb-2">メンバー認証（プライバシー配慮）</h4>
                        <p class="text-gray-400 text-sm">自分の今の学生区分を入力しサーバーに参加。</p>
                    </div>
                    <!-- ステップ 3 -->
                    <div class="card-bg p-6 rounded-lg border border-purple-500/50">
                        <p class="text-5xl font-extrabold accent-text mb-2">3</p>
                        <h4 class="text-xl font-bold mb-2">チームアップ開始！</h4>
                        <p class="text-gray-400 text-sm">認証完了後、すべてのチャンネルが開放され、自由に活動できます！</p>
                    </div>
                </div>
                
                <!-- CTAボタン (Discord招待リンク) -->
                <a href="https://discord.gg/Q6T3QdNSPy" target="_blank" rel="noopener noreferrer" class="btn-primary w-full md:w-auto inline-block py-4 px-12 rounded-full text-xl font-bold shadow-2xl hover:scale-[1.02] transform transition">
                    Discordサーバーに参加する (招待リンク)
                </a>
                <p class="text-sm text-gray-500 mt-4">製作者ああら 運営 なす・ならか</p>
            </div>
        </section>

    </main>
    
    <!-- サイト共有セクションの追加 -->
    <section class="py-8 bg-[#161b22] border-t border-gray-800">
        <div class="max-w-4xl mx-auto px-4 sm:px-6 lg:px-8 text-center">
            <h4 class="text-xl font-bold mb-4">このサイトをシェアする</h4>
            <button onclick="copySiteLink()" class="py-3 px-8 rounded-full text-lg font-bold bg-gray-600 hover:bg-gray-700 transition duration-200 shadow-lg flex items-center justify-center mx-auto">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6 mr-2" fill="none" viewBox="0 0 24 24" stroke="currentColor" stroke-width="2">
                  <path stroke-linecap="round" stroke-linejoin="round" d="M8 5H6a2 2 0 00-2 2v12a2 2 0 002 2h10a2 2 0 002-2v-1M8 5a2 2 0 002 2h2a2 2 0 002-2M8 5a2 2 0 012-2h2a2 2 0 012 2m0 0h2a2 2 0 012 2v2M8 7h12" />
                </svg>
                サイトURLをクリップボードにコピー
            </button>
        </div>
    </section>

    <!-- フッター -->
    <footer class="bg-[#0d1117] border-t border-gray-800 py-8">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 text-center">
            <!-- リンクを削除しました -->
            <p class="text-gray-500 text-sm">&copy; 2025 OW2学生コミュニティ. All Rights Reserved.</p>
        </div>
    </footer>

    <!-- カスタムメッセージボックス (alert()の代替) -->
    <div id="messageBox" class="fixed inset-0 bg-black bg-opacity-70 hidden items-center justify-center z-50">
        <div class="bg-[#161b22] p-6 rounded-xl shadow-2xl max-w-sm w-full transform transition-all duration-300 scale-95 opacity-0" id="messageContent">
            <h5 id="messageTitle" class="text-xl font-bold mb-3 text-white">通知</h5>
            <p id="messageText" class="text-gray-300 mb-4">メッセージ内容</p>
            <button onclick="hideMessageBox()" class="w-full py-2 bg-purple-600 hover:bg-purple-700 rounded-lg font-semibold transition duration-200">閉じる</button>
        </div>
    </div>

    <!-- JavaScript for Message Box -->
    <script>
        // カスタムメッセージボックスの表示ロジック
        function showMessageBox(message, type = 'info') {
            const box = document.getElementById('messageBox');
            const content = document.getElementById('messageContent');
            const title = document.getElementById('messageTitle');
            const text = document.getElementById('messageText');

            // タイトルとメッセージを設定
            let titleText = '通知';
            if (type === 'error') {
                titleText = 'エラー';
                title.classList.add('text-red-400');
            } else if (type === 'success') {
                titleText = '成功';
                title.classList.add('text-green-400');
            } else {
                title.classList.remove('text-red-400', 'text-green-400');
            }

            title.textContent = titleText;
            text.textContent = message;

            // 表示処理
            box.classList.remove('hidden');
            box.classList.add('flex');
            setTimeout(() => {
                content.classList.remove('opacity-0', 'scale-95');
                content.classList.add('opacity-100', 'scale-100');
            }, 50);
        }

        function hideMessageBox() {
            const box = document.getElementById('messageBox');
            const content = document.getElementById('messageContent');
            
            // 非表示処理
            content.classList.remove('opacity-100', 'scale-100');
            content.classList.add('opacity-0', 'scale-95');
            
            setTimeout(() => {
                box.classList.add('hidden');
                box.classList.remove('flex');
            }, 300); // アニメーション時間に合わせて遅延
        }
        
        // サイトリンクをコピーする関数
        function copySiteLink() {
            // この環境でこのページの実際のURLを取得することはできないため、架空のURLを使用します。
            const dummyUrl = 'https://ow2-gakusei-server.com/';
            
            const tempInput = document.createElement('input');
            tempInput.value = dummyUrl;
            document.body.appendChild(tempInput);
            
            // iOS/一部環境でのexecCommandのための選択処理
            if (navigator.userAgent.match(/ipad|ipod|iphone/i)) {
                tempInput.selectionStart = 0;
                tempInput.selectionEnd = tempInput.value.length;
            }
            
            tempInput.select();
            
            try {
                // クリップボードにコピー
                document.execCommand('copy');
                showMessageBox('サイトURLをコピーしました！', 'success');
            } catch (err) {
                // コピー失敗時のフォールバック
                showMessageBox('URLのコピーに失敗しました。お手数ですが、手動でコピーしてください: ' + dummyUrl, 'error');
            }
            
            document.body.removeChild(tempInput);
        }
    </script>
</body>
</html>
# studious-robot
