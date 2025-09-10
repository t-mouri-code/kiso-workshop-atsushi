<!DOCTYPE html>
<html lang="ja">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>もうthank youだけで終わらせない - 大人のための英語ワークショップ</title>
    <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@fortawesome/fontawesome-free@6.4.0/css/all.min.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Noto+Sans+JP:wght@300;400;500;700&display=swap" rel="stylesheet">
    <style>
        * {
            font-family: 'Noto Sans JP', sans-serif;
        }
        
        :root {
            --primary-color: #6B46C1;
            --secondary-color: #EC4899;
            --accent-color: #F3E8FF;
            --text-dark: #374151;
            --text-light: #6B7280;
        }
        
        .gradient-bg {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
        }
        
        .hero-gradient {
            background: linear-gradient(135deg, rgba(139, 92, 246, 0.9) 0%, rgba(219, 39, 119, 0.8) 100%);
        }
        
        .card-shadow {
            box-shadow: 0 10px 25px rgba(0, 0, 0, 0.1);
        }
        
        .section-padding {
            padding: 4rem 0;
        }
        
        .text-gradient {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
        }
        
        .hover-scale {
            transition: transform 0.3s ease;
        }
        
        .hover-scale:hover {
            transform: scale(1.05);
        }
        
        .floating {
            animation: float 3s ease-in-out infinite;
        }
        
        @keyframes float {
            0%, 100% { transform: translateY(0px); }
            50% { transform: translateY(-10px); }
        }
        
        .testimonial-card {
            background: linear-gradient(145deg, #ffffff 0%, #fdf2f8 100%);
            border: 1px solid #f3e8ff;
        }
        
        .cta-button {
            background: linear-gradient(135deg, #ec4899 0%, #be185d 100%);
            transition: all 0.3s ease;
        }
        
        .cta-button:hover {
            background: linear-gradient(135deg, #be185d 0%, #9d174d 100%);
            transform: translateY(-2px);
            box-shadow: 0 10px 20px rgba(236, 72, 153, 0.3);
        }
        
        .problem-icon {
            background: linear-gradient(135deg, #fef3c7 0%, #fde68a 100%);
        }
        
        .benefit-icon {
            background: linear-gradient(135deg, #dbeafe 0%, #bfdbfe 100%);
        }
        
        .carousel-btn {
            z-index: 10;
        }
        
        .carousel-dot.active {
            background-color: #8B5CF6 !important;
        }
        
        @media (max-width: 768px) {
            .carousel-btn {
                display: none;
            }
        }
        
        /* スマホ向け最適化 */
        @media (max-width: 414px) {
            .section-padding {
                padding: 2rem 0;
            }
            
            h1 {
                line-height: 1.3;
                font-size: 2rem;
            }
            
            h2 {
                line-height: 1.4;
                font-size: 1.75rem;
            }
            
            h3, h4 {
                line-height: 1.5;
                font-size: 1.25rem;
            }
            
            p {
                line-height: 1.7;
                font-size: 1rem;
            }
            
            .text-4xl {
                font-size: 2rem;
            }
            
            .text-3xl {
                font-size: 1.75rem;
            }
            
            .text-2xl {
                font-size: 1.25rem;
            }
            
            .text-xl {
                font-size: 1.125rem;
            }
            
            .text-base {
                font-size: 1rem;
            }
            
            .px-4 {
                padding-left: 1rem;
                padding-right: 1rem;
            }
            
            /* セクション内でのフォント統一 */
            .testimonial-card p {
                font-size: 1rem;
            }
            
            .card-shadow p {
                font-size: 1rem;
            }
        }
    </style>
</head>
<body class="bg-gray-50">
    <!-- Hero Section -->
    <section class="relative min-h-screen flex items-center justify-center overflow-hidden">
        <div class="absolute inset-0 hero-gradient"></div>
        <div class="absolute inset-0 opacity-20">
            <img src="https://cdn1.genspark.ai/user-upload-image/gemini_generated/556df105-fd32-4d29-bfad-e8f7e297051a" alt="笑顔の50歳女性" class="w-full h-full object-cover">
        </div>
        
        <div class="relative z-10 text-center text-white px-4 max-w-4xl mx-auto">
            <div class="floating mb-8">
                <h1 class="text-4xl md:text-7xl font-bold mb-6 leading-tight">
                    もう<br><span class="text-yellow-300">thank you</span><br>だけで終わらせない
                </h1>
            </div>
            
            <p class="text-lg md:text-2xl mb-8 font-light">
                ──海外旅行も、趣味も、<br class="md:hidden">人生100年時代のこれからも。
            </p>
            
            <div class="bg-white bg-opacity-20 backdrop-blur-sm rounded-2xl p-6 mb-6 border border-white border-opacity-20">
                <p class="text-xl md:text-3xl font-semibold">
                    そんな【大人のための】<br class="md:hidden">英語ワークショップ
                </p>
            </div>
            
            <button class="cta-button text-white px-12 py-4 rounded-full text-xl font-semibold inline-flex items-center space-x-3 mt-8">
                <i class="fas fa-play"></i>
                <span>無料で体験する</span>
            </button>
        </div>
    </section>

    <!-- Problems Section -->
    <section class="section-padding bg-white">
        <div class="max-w-6xl mx-auto px-4">
            <div class="text-center mb-16">
                <h2 class="text-3xl md:text-5xl font-bold text-gradient mb-6">
                    こんな気持ち、<br class="md:hidden">ありませんか？
                </h2>
                <div class="w-24 h-1 bg-gradient-to-r from-purple-500 to-pink-500 mx-auto rounded-full"></div>
            </div>
            
            <div class="grid md:grid-cols-2 gap-8">
                <div class="card-shadow rounded-2xl p-8" style="background: linear-gradient(135deg, #fffbeb 0%, #fefce8 100%); border: 1px solid #fef3c7;">
                    <div class="flex items-start space-x-4 mb-6">
                        <div class="problem-icon w-16 h-16 rounded-full flex items-center justify-center flex-shrink-0">
                            <i class="fas fa-plane text-2xl text-yellow-600"></i>
                        </div>
                        <div>
                            <h3 class="text-xl md:text-2xl font-bold text-gray-800 mb-3">旅行のたびに<br class="md:hidden">ちょっと後悔</h3>
                        </div>
                    </div>
                    <div class="mb-6">
                        <img src="https://cdn1.genspark.ai/user-upload-image/gemini_generated/43ef40ee-9840-45e4-b731-e9a0608cf14b" alt="スーツケースを持つ女性（後悔している表情）" class="w-full h-48 object-cover rounded-xl">
                    </div>
                    <p class="text-gray-600 leading-relaxed text-base md:text-lg">
                        ホテルやレストランで<br>「thank you」しか出てこず、<br>もっと言えたら<br>楽しかったのに…と思う。<br><br>帰国後に少し勉強するけど、<br>すぐやめてしまう。
                    </p>
                </div>
                
                <div class="card-shadow rounded-2xl p-8" style="background: linear-gradient(135deg, #f0fdfa 0%, #ecfdf5 100%); border: 1px solid #d1fae5;">
                    <div class="flex items-start space-x-4 mb-6">
                        <div class="problem-icon w-16 h-16 rounded-full flex items-center justify-center flex-shrink-0">
                            <i class="fas fa-heart text-2xl text-yellow-600"></i>
                        </div>
                        <div>
                            <h3 class="text-xl md:text-2xl font-bold text-gray-800 mb-3">子ども優先で<br class="md:hidden">過ごしてきた</h3>
                        </div>
                    </div>
                    <div class="mb-6">
                        <img src="https://stp-magazine.entrenet.jp/wp-content/uploads/2023/10/%E5%AD%90%E8%82%B2%E3%81%A6%E7%B5%82%E4%BA%86-%E7%AC%AC%E4%BA%8C%E3%81%AE%E4%BA%BA%E7%94%9F-01.jpg" alt="子育て終了後の女性" class="w-full h-48 object-cover rounded-xl">
                    </div>
                    <p class="text-gray-600 leading-relaxed text-base md:text-lg">
                        これまで家族に時間もお金も<br>注いできた。<br><br>でも、そろそろ「自分のため」に<br>学んでもいいのでは？<br>と考えるようになった。
                    </p>
                </div>
                
                <div class="card-shadow rounded-2xl p-8 bg-gradient-to-br from-blue-50 to-indigo-50 border border-blue-100">
                    <div class="flex items-start space-x-4 mb-6">
                        <div class="problem-icon w-16 h-16 rounded-full flex items-center justify-center flex-shrink-0">
                            <i class="fas fa-book text-2xl text-yellow-600"></i>
                        </div>
                        <div>
                            <h3 class="text-xl md:text-2xl font-bold text-gray-800 mb-4 mt-2">英語がずっと<br>心残り</h3>
                        </div>
                    </div>
                    <div class="mb-6">
                        <img src="https://cdn1.genspark.ai/user-upload-image/gemini_generated/8a569d44-d646-466f-bd9a-14c3ead9e1a0" alt="英語学習に挫折を感じる女性" class="w-full h-48 object-cover rounded-xl">
                    </div>
                    <p class="text-gray-600 leading-relaxed text-base md:text-lg">
                        英会話教室に通ったり教材を買ったりしたけど、成果を感じられない。<br><br>だからこそ、<br>もう一度挑戦してみたい。
                    </p>
                </div>
                
                <div class="card-shadow rounded-2xl p-8 bg-gradient-to-br from-green-50 to-emerald-50 border border-green-100">
                    <div class="flex items-start space-x-4 mb-6">
                        <div class="problem-icon w-16 h-16 rounded-full flex items-center justify-center flex-shrink-0">
                            <i class="fas fa-level-up-alt text-2xl text-yellow-600"></i>
                        </div>
                        <div>
                            <h3 class="text-xl md:text-2xl font-bold text-gray-800 mb-3">最近なんだか<br class="md:hidden">停滞気味</h3>
                        </div>
                    </div>
                    <div class="mb-6">
                        <img src="https://halmek.co.jp/media/article/image/20f58cf937162964e6d5407a42edd914.jpg" alt="50代女性の英会話学習" class="w-full h-48 object-cover rounded-xl">
                    </div>
                    <p class="text-gray-600 leading-relaxed text-lg">
                        最初はなんでも学びだった。でも最近は<br>ネイティブの音についていけなかったり<br><br>パッと言いたいことが<br>出てこなかったり...
                    </p>
                </div>
            </div>
        </div>
    </section>

    <!-- Workshop Description -->
    <section class="section-padding bg-gradient-to-br from-purple-50 to-pink-50">
        <div class="max-w-6xl mx-auto px-4">
            <div class="text-center mb-16">
                <h2 class="text-3xl md:text-5xl font-bold text-gradient mb-6">
                    大人の英語<br>ワークショップとは？
                </h2>
                <p class="text-lg md:text-xl text-gray-600 max-w-3xl mx-auto leading-relaxed">
                    このワークショップは、<br>知っているのに言えない・聞き取れない<br>そんな壁を一歩越える体験会です。
                </p>
            </div>
            
            <div class="bg-white rounded-3xl card-shadow p-8 md:p-12 mb-12">
                <div class="flex items-center justify-center mb-8">
                    <img src="https://cdn1.genspark.ai/user-upload-image/gemini_generated/0d3ac02f-b7a1-4b5c-8a0a-ba9b7bf36b58" alt="40〜60代女性の英語ワークショップ" class="w-full max-w-2xl h-80 object-cover rounded-2xl">
                </div>
                
                <div class="text-center mb-12">
                    <h3 class="text-3xl font-bold text-gray-800 mb-4">内容（60分）</h3>
                </div>
                
                <div class="grid md:grid-cols-3 gap-8">
                    <div class="text-center">
                        <div class="benefit-icon w-20 h-20 rounded-full flex items-center justify-center mx-auto mb-6">
                            <i class="fas fa-volume-up text-3xl text-blue-600"></i>
                        </div>
                        <h4 class="text-2xl font-bold text-gray-800 mb-4">聞こえるようになるための<br>発音矯正</h4>
                        <div class="mb-6">
                            <img src="https://page.gensparksite.com/v1/base64_upload/632ded8fc85b2348f170bb1b3db5f4ec" alt="オンライン発音練習を楽しむ40代日本人女性" class="w-full h-48 object-cover rounded-xl mx-auto">
                        </div>
                        <p class="text-gray-600 leading-relaxed text-base">
                            日本人が苦手な音の違いを体感練習。<br>ただのリンキングや脱落ではなく、<br>本当の発音矯正をお伝えします。<br>"音を知れば聞こえる"を<br>ぜひ実感してください。
                        </p>
                    </div>
                    
                    <div class="text-center">
                        <div class="benefit-icon w-20 h-20 rounded-full flex items-center justify-center mx-auto mb-6">
                            <i class="fas fa-puzzle-piece text-3xl text-blue-600"></i>
                        </div>
                        <h4 class="text-2xl font-bold text-gray-800 mb-4">中学英語で<br>2〜3文の文章を<br class="md:hidden">作る方法</h4>
                        <div class="mb-6">
                            <img src="https://images.unsplash.com/photo-1434030216411-0b793f4b4173?w=400&h=192&fit=crop" alt="シンプルな英語学習ノート" class="w-full h-48 object-cover rounded-xl mx-auto">
                        </div>
                        <p class="text-gray-600 leading-relaxed text-base">
                            複雑な文法は不要！<br>中学レベルの基礎を使って、<br>簡単な単語や型で<br>正確なニュアンスを伝えられる<br>英文の組み立て方をお教えします。
                        </p>
                    </div>
                    
                    <div class="text-center">
                        <div class="benefit-icon w-20 h-20 rounded-full flex items-center justify-center mx-auto mb-6">
                            <i class="fas fa-tachometer-alt text-3xl text-blue-600"></i>
                        </div>
                        <h4 class="text-2xl font-bold text-gray-800 mb-4">ネイティブの話す英語が<br>遅く聞こえるトレーニング</h4>
                        <div class="mb-6">
                            <img src="https://cdn1.genspark.ai/user-upload-image/gemini_generated/1b5593f2-840b-45bb-8dd2-f650b8412053" alt="リスニングスピードトレーニング" class="w-full h-48 object-cover rounded-xl mx-auto">
                        </div>
                        <p class="text-gray-600 leading-relaxed text-base">
                            音の変化パターンを理解し、<br>英語のリズムに慣れる<br>特別トレーニング。<br>「速すぎてついていけない」から<br>「あれ？聞こえる！」への変化を<br>60分で体験していただきます。
                        </p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Instructor Introduction Section -->
    <section class="section-padding bg-white">
        <div class="max-w-4xl mx-auto px-4">
            <div class="text-center mb-16">
                <h2 class="text-3xl md:text-5xl font-bold text-gradient mb-6">
                    講師紹介
                </h2>
                <div class="w-24 h-1 bg-gradient-to-r from-purple-500 to-pink-500 mx-auto rounded-full"></div>
            </div>
            
            <div class="bg-gradient-to-br from-purple-50 to-pink-50 rounded-3xl p-8 md:p-12 card-shadow">
                <!-- Instructor Profile -->
                <div class="flex flex-col md:flex-row items-center md:items-start mb-12">
                    <div class="mb-8 md:mb-0 md:mr-12 flex-shrink-0">
                        <img src="https://page.gensparksite.com/v1/base64_upload/812806d35d92b9eebdd6a7288427b214" alt="講師 喜早佑輔" class="w-48 h-48 rounded-2xl object-cover card-shadow">
                    </div>
                    <div class="text-center md:text-left">
                        <h3 class="text-2xl md:text-3xl font-bold text-gray-800 mb-4">【講師】</h3>
                        <p class="text-xl md:text-2xl font-semibold text-gray-800 mb-4">
                            喜早佑輔（きそうゆうすけ）、25歳。
                        </p>
                        <p class="text-lg text-gray-600 leading-relaxed">
                            工学院大学在学時から、現在1500名が<br>
                            受講した日常英会話向け英語コーチング<br>
                            「ENGLISH CAMP」創業に携わる。<br><br>
                            40〜60代の方、1000名以上の<br>
                            サポート実績。
                        </p>
                    </div>
                </div>
                
                <!-- Greeting Message -->
                <div class="bg-white rounded-2xl p-8 md:p-10 card-shadow">
                    <h3 class="text-2xl md:text-3xl font-bold text-gradient mb-6 text-center">【あいさつ】</h3>
                    
                    <div class="space-y-6 text-lg text-gray-700 leading-relaxed">
                        <p class="font-semibold text-xl text-center">
                            初めまして！喜早と申します！
                        </p>
                        
                        <p>
                            私は普段、20〜60代の<br>
                            大人の方々の<br>
                            "学び直し"としての英語学習を<br>
                            サポートしています。
                        </p>
                        
                        <p>これまで多くの方が、最初は</p>
                        
                        <div class="bg-gray-50 rounded-xl p-6 border-l-4 border-purple-500">
                            <ul class="space-y-2 text-gray-600">
                                <li>「リスニングって<br>やっぱり難しい…」</li>
                                <li>「いつまでもパッと英語が出せない」</li>
                                <li>「もう年齢的に<br>無理かも」</li>
                                <li>「私には才能が<br>ないから」</li>
                            </ul>
                        </div>
                        
                        <p>そんなふうに、半分<br>諦めかけていました。</p>
                        
                        <p class="font-semibold text-purple-700">
                            でも実際には、<br>
                            今からでも遅くありません。<br>
                            英語は大人になってからでも、確実に上達していきます。
                        </p>
                        
                        <p class="font-semibold text-blue-700">
                            特にリスニングは、<br>
                            正しい方法で取り組めば<br>
                            わずか10分でも聞こえる感覚を<br>
                            味わえるのです。
                        </p>
                        
                        <div class="bg-yellow-50 rounded-xl p-6 border-l-4 border-yellow-500">
                            <p class="text-gray-600">
                                「そんなうまい話<br>
                                あるわけないでしょ？」<br><br>
                                「本当に<br>
                                効果があるの？」<br><br>
                                と、最初は<br>
                                誰もが半信半疑。
                            </p>
                        </div>
                        
                        <p class="font-semibold">
                            だからこそ、まずは<br>
                            体験していただきたいのです。
                        </p>
                        
                        <p class="text-xl font-semibold text-gradient text-center mb-6">
                            今回の<br>
                            大人の英語ワークショップは<br><br>
                            あなたの英語への<br>
                            苦手意識をやわらげ、<br><br>
                            もう一度、学び直せる手応えを<br>
                            実感していただけます。
                        </p>
                        
                        <p class="text-xl font-bold text-center text-pink-600">
                            あなたのご参加<br>
                            心よりお待ちしております！！
                        </p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- 3 STEP Booking Section -->
    <section class="section-padding bg-gradient-to-br from-sky-100 to-blue-200">
        <div class="max-w-6xl mx-auto px-4">
            <!-- Header Text -->
            <div class="text-center mb-16">
                <h2 class="text-3xl md:text-5xl font-bold text-gradient mb-6">
                    簡単3ステップで<br>今すぐ予約
                </h2>
                <p class="text-xl text-gray-600 max-w-3xl mx-auto leading-relaxed">
                    わずか3分で完了！<br>まずはお気軽にお申し込みください
                </p>
            </div>
            
            <!-- Steps -->
            <div class="grid lg:grid-cols-3 gap-12">
                <!-- Step 1 -->
                <div class="bg-white rounded-3xl p-8 card-shadow text-center relative">
                    <div class="absolute -top-6 left-1/2 transform -translate-x-1/2">
                        <div class="bg-gradient-to-r from-blue-500 to-purple-600 text-white w-12 h-12 rounded-full flex items-center justify-center text-xl font-bold">
                            01
                        </div>
                    </div>
                    <div class="pt-8">
                        <img src="images/step1-calendar-new.jpg" alt="日程選択画面" class="w-full max-w-xs mx-auto rounded-2xl mb-6 card-shadow">
                        <h3 class="text-2xl font-bold text-gray-800 mb-4">STEP 1</h3>
                        <p class="text-lg text-gray-600 leading-relaxed">
                            ご都合が良い日程を<br>ワンタップで選べます
                        </p>
                        <div class="mt-4 text-sm text-blue-600 font-semibold">
                            平日・土日祝 9:00-21:00受付中！
                        </div>
                    </div>
                </div>
                
                <!-- Step 2 -->
                <div class="bg-white rounded-3xl p-8 card-shadow text-center relative">
                    <div class="absolute -top-6 left-1/2 transform -translate-x-1/2">
                        <div class="bg-gradient-to-r from-blue-500 to-purple-600 text-white w-12 h-12 rounded-full flex items-center justify-center text-xl font-bold">
                            02
                        </div>
                    </div>
                    <div class="pt-8">
                        <img src="images/step2-form-new.jpg" alt="質問フォーム画面" class="w-full max-w-xs mx-auto rounded-2xl mb-6 card-shadow">
                        <h3 class="text-2xl font-bold text-gray-800 mb-4">STEP 2</h3>
                        <p class="text-lg text-gray-600 leading-relaxed">
                            30秒で終わる<br>４つの質問に答える
                        </p>
                        <div class="mt-4 text-sm text-green-600 font-semibold">
                            お名前・年齢・目的など簡単入力
                        </div>
                    </div>
                </div>
                
                <!-- Step 3 -->
                <div class="bg-white rounded-3xl p-8 card-shadow text-center relative">
                    <div class="absolute -top-6 left-1/2 transform -translate-x-1/2">
                        <div class="bg-gradient-to-r from-blue-500 to-purple-600 text-white w-12 h-12 rounded-full flex items-center justify-center text-xl font-bold">
                            03
                        </div>
                    </div>
                    <div class="pt-8">
                        <img src="images/step3-contact.jpg" alt="コーチからの返信画面" class="w-full max-w-xs mx-auto rounded-2xl mb-6 card-shadow">
                        <h3 class="text-2xl font-bold text-gray-800 mb-4">STEP 3</h3>
                        <p class="text-lg text-gray-600 leading-relaxed">
                            担当コーチから返信
                        </p>
                        <div class="mt-4 text-sm text-purple-600 font-semibold">
                            ZoomのURLをお送りします
                        </div>
                    </div>
                </div>
            </div>
            
            <!-- CTA Button -->
            <div class="text-center mt-16">
                <button class="cta-button text-white px-16 py-6 rounded-full text-2xl font-bold inline-flex items-center space-x-4 hover-scale">
                    <i class="fas fa-calendar-alt text-2xl"></i>
                    <span>無料で予約する</span>
                </button>
                <p class="text-gray-600 mt-4">※予約は3分で完了します</p>
            </div>
        </div>
    </section>

    <!-- Why Free Section -->
    <section class="section-padding bg-white">
        <div class="max-w-4xl mx-auto px-4 text-center">
            <h2 class="text-4xl md:text-5xl font-bold text-gradient mb-8">
                なぜ無料なの？
            </h2>
            
            <div class="bg-gradient-to-br from-amber-50 to-yellow-50 rounded-3xl p-8 md:p-12 card-shadow border border-amber-100">
                <p class="text-lg md:text-xl text-gray-600 leading-relaxed mb-8">
                    このワークショップは、<br>第二言語習得論に基づいた学習法を<br>実際に体験していただきながら、<br>今後のプログラム改善のために<br>データを取らせていただいています。<br>そのため費用はいただいていません。
                </p>
                
                <div class="grid md:grid-cols-2 gap-6">
                    <div class="flex items-center space-x-4 bg-white rounded-xl p-6">
                        <i class="fas fa-shield-alt text-3xl text-green-500"></i>
                        <span class="text-lg font-semibold text-gray-800">無理な勧誘は一切なし</span>
                    </div>
                    <div class="flex items-center space-x-4 bg-white rounded-xl p-6">
                        <i class="fas fa-check-circle text-3xl text-blue-500"></i>
                        <span class="text-lg font-semibold text-gray-800">実際に試して、自分に合うかどうかを確認できる</span>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Testimonials Section -->
    <section class="section-padding bg-gradient-to-br from-indigo-50 to-purple-50">
        <div class="max-w-6xl mx-auto px-4">
            <div class="text-center mb-16">
                <h2 class="text-3xl md:text-5xl font-bold text-gradient mb-6">
                    参加者の声<br>（40〜60代の方々から）
                </h2>
            </div>
            
            <!-- Carousel Container -->
            <div class="relative">
                <div class="testimonial-carousel overflow-hidden">
                    <div class="testimonial-track flex transition-transform duration-500 ease-in-out" id="testimonialTrack">
                        <!-- Testimonial 1 -->
                        <div class="testimonial-slide min-w-full px-4">
                            <div class="testimonial-card rounded-2xl p-8 card-shadow max-w-2xl mx-auto">
                                <div class="flex items-center mb-6 justify-center">
                                    <img src="https://cdn1.genspark.ai/user-upload-image/gemini_generated/a11bcd9d-a907-4a21-a278-14675bf6286c" alt="55歳主婦参加者" class="w-20 h-20 rounded-full object-cover mr-6">
                                    <div>
                                        <h4 class="font-bold text-gray-800 text-xl">55歳・主婦</h4>
                                    </div>
                                </div>
                                <div class="mb-6 text-center">
                                    <div class="flex text-yellow-400 text-2xl mb-4 justify-center">
                                        <i class="fas fa-star"></i>
                                        <i class="fas fa-star"></i>
                                        <i class="fas fa-star"></i>
                                        <i class="fas fa-star"></i>
                                        <i class="fas fa-star"></i>
                                    </div>
                                </div>
                                <p class="text-gray-600 leading-relaxed text-xl text-center">
                                    「旅行で"thank you"以外を言えたのが嬉しかった！前回のハワイ旅行では、レストランで"This looks delicious!"と言えて、店員さんが笑顔で応えてくれました。」
                                </p>
                            </div>
                        </div>
                        
                        <!-- Testimonial 2 -->
                        <div class="testimonial-slide min-w-full px-4">
                            <div class="testimonial-card rounded-2xl p-8 card-shadow max-w-2xl mx-auto">
                                <div class="flex items-center mb-6 justify-center">
                                    <img src="https://illust.download/wp-content/uploads/2023/04/ai-create244_4lbqa.jpg" alt="62歳会社員参加者" class="w-20 h-20 rounded-full object-cover mr-6">
                                    <div>
                                        <h4 class="font-bold text-gray-800 text-xl">62歳・会社員</h4>
                                    </div>
                                </div>
                                <div class="mb-6 text-center">
                                    <div class="flex text-yellow-400 text-2xl mb-4 justify-center">
                                        <i class="fas fa-star"></i>
                                        <i class="fas fa-star"></i>
                                        <i class="fas fa-star"></i>
                                        <i class="fas fa-star"></i>
                                        <i class="fas fa-star"></i>
                                    </div>
                                </div>
                                <p class="text-gray-600 leading-relaxed text-xl text-center">
                                    「ずっと苦手意識があったけど、"私でもできるかも"と思えました。特に音のまとまりで聞く練習が目からウロコでした。」
                                </p>
                            </div>
                        </div>
                        
                        <!-- Testimonial 3 -->
                        <div class="testimonial-slide min-w-full px-4">
                            <div class="testimonial-card rounded-2xl p-8 card-shadow max-w-2xl mx-auto">
                                <div class="flex items-center mb-6 justify-center">
                                    <img src="https://cdn1.genspark.ai/user-upload-image/gemini_generated/fd313f50-6f58-4cad-bd43-39e74d4c19ad" alt="48歳主婦参加者" class="w-20 h-20 rounded-full object-cover mr-6">
                                    <div>
                                        <h4 class="font-bold text-gray-800 text-xl">48歳・主婦</h4>
                                    </div>
                                </div>
                                <div class="mb-6 text-center">
                                    <div class="flex text-yellow-400 text-2xl mb-4 justify-center">
                                        <i class="fas fa-star"></i>
                                        <i class="fas fa-star"></i>
                                        <i class="fas fa-star"></i>
                                        <i class="fas fa-star"></i>
                                        <i class="fas fa-star"></i>
                                    </div>
                                </div>
                                <p class="text-gray-600 leading-relaxed text-xl text-center">
                                    「子どもが巣立って時間ができた今、やっと自分のための学びに踏み出せました。1時間があっという間で、もっと続けたいと思いました。」
                                </p>
                            </div>
                        </div>
                        
                        <!-- Testimonial 4 -->
                        <div class="testimonial-slide min-w-full px-4">
                            <div class="testimonial-card rounded-2xl p-8 card-shadow max-w-2xl mx-auto">
                                <div class="flex items-center mb-6 justify-center">
                                    <img src="https://cdn1.genspark.ai/user-upload-image/gemini_generated/d5ea9198-425d-4ad3-88a8-66a8977fdd55" alt="42歳会社員参加者" class="w-20 h-20 rounded-full object-cover mr-6">
                                    <div>
                                        <h4 class="font-bold text-gray-800 text-xl">42歳・会社員</h4>
                                    </div>
                                </div>
                                <div class="mb-6 text-center">
                                    <div class="flex text-yellow-400 text-2xl mb-4 justify-center">
                                        <i class="fas fa-star"></i>
                                        <i class="fas fa-star"></i>
                                        <i class="fas fa-star"></i>
                                        <i class="fas fa-star"></i>
                                        <i class="fas fa-star"></i>
                                    </div>
                                </div>
                                <p class="text-gray-600 leading-relaxed text-xl text-center">
                                    「仕事で忙しいけど、たった1時間で変化を感じられたのが驚きでした。個人に合わせてくれるので、効率的に学べました。」
                                </p>
                            </div>
                        </div>
                        
                        <!-- Testimonial 5 -->
                        <div class="testimonial-slide min-w-full px-4">
                            <div class="testimonial-card rounded-2xl p-8 card-shadow max-w-2xl mx-auto">
                                <div class="flex items-center mb-6 justify-center">
                                    <img src="https://cdn1.genspark.ai/user-upload-image/gemini_generated/284d609f-0b41-4f06-9478-88f46fb6d0b2" alt="58歳パート参加者" class="w-20 h-20 rounded-full object-cover mr-6">
                                    <div>
                                        <h4 class="font-bold text-gray-800 text-xl">58歳・パート</h4>
                                    </div>
                                </div>
                                <div class="mb-6 text-center">
                                    <div class="flex text-yellow-400 text-2xl mb-4 justify-center">
                                        <i class="fas fa-star"></i>
                                        <i class="fas fa-star"></i>
                                        <i class="fas fa-star"></i>
                                        <i class="fas fa-star"></i>
                                        <i class="fas fa-star"></i>
                                    </div>
                                </div>
                                <p class="text-gray-600 leading-relaxed text-xl text-center">
                                    「今まで何度も挫折してきましたが、この方法なら続けられそうです。年齢を理由に諦めなくて良かった！」
                                </p>
                            </div>
                        </div>
                    </div>
                </div>
                
                <!-- Navigation Buttons -->
                <button class="carousel-btn carousel-prev absolute left-0 top-1/2 transform -translate-y-1/2 bg-white rounded-full p-3 shadow-lg hover:bg-gray-50 transition-colors duration-200" onclick="prevTestimonial()">
                    <i class="fas fa-chevron-left text-purple-600 text-xl"></i>
                </button>
                
                <button class="carousel-btn carousel-next absolute right-0 top-1/2 transform -translate-y-1/2 bg-white rounded-full p-3 shadow-lg hover:bg-gray-50 transition-colors duration-200" onclick="nextTestimonial()">
                    <i class="fas fa-chevron-right text-purple-600 text-xl"></i>
                </button>
                
                <!-- Dots Indicator -->
                <div class="flex justify-center mt-8">
                    <div class="flex space-x-2">
                        <button class="carousel-dot w-3 h-3 rounded-full bg-purple-300 transition-colors duration-200" onclick="goToSlide(0)"></button>
                        <button class="carousel-dot w-3 h-3 rounded-full bg-purple-300 transition-colors duration-200" onclick="goToSlide(1)"></button>
                        <button class="carousel-dot w-3 h-3 rounded-full bg-purple-300 transition-colors duration-200" onclick="goToSlide(2)"></button>
                        <button class="carousel-dot w-3 h-3 rounded-full bg-purple-300 transition-colors duration-200" onclick="goToSlide(3)"></button>
                        <button class="carousel-dot w-3 h-3 rounded-full bg-purple-300 transition-colors duration-200" onclick="goToSlide(4)"></button>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Target Audience -->
    <section class="section-padding bg-white">
        <div class="max-w-4xl mx-auto px-4">
            <div class="text-center mb-16">
                <h2 class="text-4xl md:text-5xl font-bold text-gradient mb-6">
                    こんな方におすすめです
                </h2>
            </div>
            
            <div class="grid md:grid-cols-2 gap-6">
                <div class="flex items-center space-x-4 bg-gradient-to-r from-pink-50 to-rose-50 rounded-xl p-6 border border-pink-100">
                    <i class="fas fa-globe-americas text-3xl text-pink-500"></i>
                    <span class="text-lg font-semibold text-gray-800">旅行で<br>「ありがとう」以上を伝えたい</span>
                </div>
                
                <div class="flex items-center space-x-4 bg-gradient-to-r from-purple-50 to-violet-50 rounded-xl p-6 border border-purple-100">
                    <i class="fas fa-clock text-3xl text-purple-500"></i>
                    <span class="text-lg font-semibold text-gray-800">子育てが落ち着き、<br>自分の時間を使いたい</span>
                </div>
                
                <div class="flex items-center space-x-4 bg-gradient-to-r from-blue-50 to-indigo-50 rounded-xl p-6 border border-blue-100">
                    <i class="fas fa-redo-alt text-3xl text-blue-500"></i>
                    <span class="text-lg font-semibold text-gray-800">英語に挑戦してきたけど<br>成果を感じられなかった</span>
                </div>
                
                <div class="flex items-center space-x-4 bg-gradient-to-r from-green-50 to-emerald-50 rounded-xl p-6 border border-green-100">
                    <i class="fas fa-chart-line text-3xl text-green-500"></i>
                    <span class="text-lg font-semibold text-gray-800">初級〜中級の間で<br>伸び悩んでいる</span>
                </div>
            </div>
        </div>
    </section>

    <!-- FAQ Section -->
    <section class="section-padding bg-gradient-to-br from-gray-50 to-blue-50">
        <div class="max-w-4xl mx-auto px-4">
            <div class="text-center mb-16">
                <h2 class="text-4xl md:text-5xl font-bold text-gradient mb-6">
                    よくある質問
                </h2>
                <div class="w-24 h-1 bg-gradient-to-r from-purple-500 to-pink-500 mx-auto rounded-full"></div>
            </div>
            
            <div class="space-y-6">
                <!-- FAQ Item 1 -->
                <div class="bg-white rounded-3xl card-shadow p-8 border border-gray-100">
                    <div class="flex items-start space-x-4 mb-4">
                        <div class="w-8 h-8 bg-gradient-to-r from-purple-500 to-pink-500 rounded-full flex items-center justify-center flex-shrink-0">
                            <span class="text-white font-bold text-sm">Q</span>
                        </div>
                        <h3 class="text-xl md:text-2xl font-bold text-gray-800">
                            英語初心者でも参加できますか？
                        </h3>
                    </div>
                    <div class="ml-12">
                        <p class="text-gray-600 leading-relaxed text-lg">
                            はい。英語初級者の方〜中上級者の方まで効果を実感していただけますので、ぜひご参加ください。
                        </p>
                    </div>
                </div>

                <!-- FAQ Item 2 -->
                <div class="bg-white rounded-3xl card-shadow p-8 border border-gray-100">
                    <div class="flex items-start space-x-4 mb-4">
                        <div class="w-8 h-8 bg-gradient-to-r from-purple-500 to-pink-500 rounded-full flex items-center justify-center flex-shrink-0">
                            <span class="text-white font-bold text-sm">Q</span>
                        </div>
                        <h3 class="text-xl md:text-2xl font-bold text-gray-800">
                            正直半信半疑ですが参加しても大丈夫ですか？
                        </h3>
                    </div>
                    <div class="ml-12">
                        <p class="text-gray-600 leading-relaxed text-lg mb-4">
                            はい。大丈夫です。英語耳ワークショップは完全無料ですのでぜひお気軽にご参加ください。
                        </p>
                        <p class="text-gray-600 leading-relaxed text-lg">
                            効果を体験していただけたら私たちも嬉しいです。
                        </p>
                    </div>
                </div>

                <!-- FAQ Item 3 -->
                <div class="bg-white rounded-3xl card-shadow p-8 border border-gray-100">
                    <div class="flex items-start space-x-4 mb-4">
                        <div class="w-8 h-8 bg-gradient-to-r from-purple-500 to-pink-500 rounded-full flex items-center justify-center flex-shrink-0">
                            <span class="text-white font-bold text-sm">Q</span>
                        </div>
                        <h3 class="text-xl md:text-2xl font-bold text-gray-800">
                            ワークショップはどのような形で実施されますか？
                        </h3>
                    </div>
                    <div class="ml-12">
                        <p class="text-gray-600 leading-relaxed text-lg mb-4">
                            zoomアプリを使ってオンラインでマンツーマンで実施します。
                        </p>
                        <p class="text-gray-600 leading-relaxed text-lg mb-4">
                            所要時間は30分〜1時間程度を予定しております。
                        </p>
                        <p class="text-gray-600 leading-relaxed text-lg">
                            無料延長もできますので追加のご質問などがありましたらお気軽にお伝えください。
                        </p>
                    </div>
                </div>

                <!-- FAQ Item 4 -->
                <div class="bg-white rounded-3xl card-shadow p-8 border border-gray-100">
                    <div class="flex items-start space-x-4 mb-4">
                        <div class="w-8 h-8 bg-gradient-to-r from-purple-500 to-pink-500 rounded-full flex items-center justify-center flex-shrink-0">
                            <span class="text-white font-bold text-sm">Q</span>
                        </div>
                        <h3 class="text-xl md:text-2xl font-bold text-gray-800">
                            本当に無料ですか？ 料金は発生しませんか？
                        </h3>
                    </div>
                    <div class="ml-12">
                        <p class="text-gray-600 leading-relaxed text-lg mb-4">
                            英語耳ワークショップは完全無料でリスニング上達体験をしていただきます。
                        </p>
                        <p class="text-gray-600 leading-relaxed text-lg">
                            後から費用が発生することなどは一切ございません。
                        </p>
                    </div>
                </div>

                <!-- FAQ Item 5 -->
                <div class="bg-white rounded-3xl card-shadow p-8 border border-gray-100">
                    <div class="flex items-start space-x-4 mb-4">
                        <div class="w-8 h-8 bg-gradient-to-r from-purple-500 to-pink-500 rounded-full flex items-center justify-center flex-shrink-0">
                            <span class="text-white font-bold text-sm">Q</span>
                        </div>
                        <h3 class="text-xl md:text-2xl font-bold text-gray-800">
                            しつこい勧誘などはありますか？
                        </h3>
                    </div>
                    <div class="ml-12">
                        <p class="text-gray-600 leading-relaxed text-lg mb-4">
                            希望者の方には運営母体の日常英会話向け英語コーチングENGLISH CAMPのご案内をさせていただく場合がございます。
                        </p>
                        <p class="text-gray-600 leading-relaxed text-lg">
                            ただし、あくまで希望者のみの実施でしつこい勧誘、営業活動は行いませんのでご安心ください。
                        </p>
                    </div>
                </div>

                <!-- FAQ Item 6 -->
                <div class="bg-white rounded-3xl card-shadow p-8 border border-gray-100">
                    <div class="flex items-start space-x-4 mb-4">
                        <div class="w-8 h-8 bg-gradient-to-r from-purple-500 to-pink-500 rounded-full flex items-center justify-center flex-shrink-0">
                            <span class="text-white font-bold text-sm">Q</span>
                        </div>
                        <h3 class="text-xl md:text-2xl font-bold text-gray-800">
                            予約後にキャンセルはできますか？
                        </h3>
                    </div>
                    <div class="ml-12">
                        <p class="text-gray-600 leading-relaxed text-lg mb-4">
                            はい。日程変更などもお気軽にお伝えください。
                        </p>
                        <p class="text-gray-600 leading-relaxed text-lg">
                            もちろん予約後の辞退も可能です。
                        </p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Second STEP Section -->
    <section class="section-padding bg-gradient-to-br from-purple-100 to-pink-100">
        <div class="max-w-6xl mx-auto px-4">
            <div class="text-center mb-16">
                <h2 class="text-3xl md:text-5xl font-bold text-gradient mb-6">
                    簡単3ステップで<br>今すぐ予約
                </h2>
                <p class="text-xl text-gray-600 max-w-3xl mx-auto leading-relaxed">
                    わずか3分で完了！<br>まずはお気軽にお申し込みください
                </p>
            </div>
            
            <!-- Steps -->
            <div class="grid lg:grid-cols-3 gap-12">
                <!-- Step 1 -->
                <div class="bg-white rounded-3xl p-8 card-shadow text-center relative">
                    <div class="absolute -top-6 left-1/2 transform -translate-x-1/2">
                        <div class="bg-gradient-to-r from-purple-500 to-pink-500 text-white w-12 h-12 rounded-full flex items-center justify-center text-xl font-bold">
                            01
                        </div>
                    </div>
                    <div class="pt-8">
                        <img src="images/step1-calendar-new.jpg" alt="日程選択画面" class="w-full max-w-xs mx-auto rounded-2xl mb-6 card-shadow">
                        <h3 class="text-2xl font-bold text-gray-800 mb-4">STEP 1</h3>
                        <p class="text-lg text-gray-600 leading-relaxed">
                            ご都合が良い日程を<br>ワンタップで選べます
                        </p>
                        <div class="mt-4 text-sm text-blue-600 font-semibold">
                            平日・土日祝 9:00-21:00受付中！
                        </div>
                    </div>
                </div>
                
                <!-- Step 2 -->
                <div class="bg-white rounded-3xl p-8 card-shadow text-center relative">
                    <div class="absolute -top-6 left-1/2 transform -translate-x-1/2">
                        <div class="bg-gradient-to-r from-purple-500 to-pink-500 text-white w-12 h-12 rounded-full flex items-center justify-center text-xl font-bold">
                            02
                        </div>
                    </div>
                    <div class="pt-8">
                        <img src="images/step2-form-new.jpg" alt="質問フォーム画面" class="w-full max-w-xs mx-auto rounded-2xl mb-6 card-shadow">
                        <h3 class="text-2xl font-bold text-gray-800 mb-4">STEP 2</h3>
                        <p class="text-lg text-gray-600 leading-relaxed">
                            30秒で終わる<br>４つの質問に答える
                        </p>
                        <div class="mt-4 text-sm text-green-600 font-semibold">
                            お名前・年齢・目的など簡単入力
                        </div>
                    </div>
                </div>
                
                <!-- Step 3 -->
                <div class="bg-white rounded-3xl p-8 card-shadow text-center relative">
                    <div class="absolute -top-6 left-1/2 transform -translate-x-1/2">
                        <div class="bg-gradient-to-r from-purple-500 to-pink-500 text-white w-12 h-12 rounded-full flex items-center justify-center text-xl font-bold">
                            03
                        </div>
                    </div>
                    <div class="pt-8">
                        <img src="images/step3-contact.jpg" alt="コーチからの返信画面" class="w-full max-w-xs mx-auto rounded-2xl mb-6 card-shadow">
                        <h3 class="text-2xl font-bold text-gray-800 mb-4">STEP 3</h3>
                        <p class="text-lg text-gray-600 leading-relaxed">
                            担当コーチから返信
                        </p>
                        <div class="mt-4 text-sm text-purple-600 font-semibold">
                            ZoomのURLをお送りします
                        </div>
                    </div>
                </div>
            </div>
            
            <!-- CTA Button -->
            <div class="text-center mt-16">
                <button class="cta-button text-white px-16 py-6 rounded-full text-2xl font-bold inline-flex items-center space-x-4 hover-scale">
                    <i class="fas fa-calendar-plus text-2xl"></i>
                    <span>無料で予約する</span>
                </button>
                <p class="text-gray-600 mt-4">※完全無料・無理な勧誘なし・予約は3分で完了</p>
            </div>
        </div>
    </section>

    <!-- Final CTA Section -->
    <section class="section-padding gradient-bg">
        <div class="max-w-4xl mx-auto px-4 text-center text-white">
            <h2 class="text-4xl md:text-5xl font-bold mb-8">
                まずはお気軽に<br>ご参加ください
            </h2>
            
            <div class="bg-white bg-opacity-20 backdrop-blur-sm rounded-3xl p-8 md:p-12 mb-12 border border-white border-opacity-20">
                <p class="text-2xl md:text-3xl font-light mb-6">
                    大人のための英語学び直し。
                </p>
                <p class="text-xl md:text-2xl">
                    1時間で「聞こえる」「言える」を<br>１つ増やす体験をしてみませんか？
                </p>
            </div>
            
            <button class="cta-button text-white px-16 py-6 rounded-full text-2xl font-bold inline-flex items-center space-x-4 hover-scale">
                <i class="fas fa-rocket text-2xl"></i>
                <span>無料で体験する</span>
            </button>
            
            <div class="mt-8 text-sm opacity-80">
                <p>※無理な勧誘は一切ございません</p>
            </div>
        </div>
    </section>

    <!-- Testimonial Carousel JavaScript -->
    <script>
        let currentSlide = 0;
        const totalSlides = 5;
        
        function showSlide(index) {
            const track = document.getElementById('testimonialTrack');
            const dots = document.querySelectorAll('.carousel-dot');
            
            // Update slide position
            track.style.transform = `translateX(-${index * 100}%)`;
            
            // Update dots
            dots.forEach((dot, i) => {
                if (i === index) {
                    dot.classList.add('active');
                } else {
                    dot.classList.remove('active');
                }
            });
            
            currentSlide = index;
        }
        
        function nextTestimonial() {
            const nextIndex = (currentSlide + 1) % totalSlides;
            showSlide(nextIndex);
        }
        
        function prevTestimonial() {
            const prevIndex = (currentSlide - 1 + totalSlides) % totalSlides;
            showSlide(prevIndex);
        }
        
        function goToSlide(index) {
            showSlide(index);
        }
        
        // Auto-play carousel (optional)
        setInterval(() => {
            nextTestimonial();
        }, 5000); // Change slide every 5 seconds
        
        // Initialize first slide
        document.addEventListener('DOMContentLoaded', function() {
            showSlide(0);
        });
        
        // Touch/swipe support for mobile
        let startX = 0;
        let endX = 0;
        
        const carousel = document.querySelector('.testimonial-carousel');
        
        carousel.addEventListener('touchstart', function(e) {
            startX = e.touches[0].clientX;
        });
        
        carousel.addEventListener('touchend', function(e) {
            endX = e.changedTouches[0].clientX;
            handleSwipe();
        });
        
        function handleSwipe() {
            const swipeThreshold = 50;
            const diff = startX - endX;
            
            if (Math.abs(diff) > swipeThreshold) {
                if (diff > 0) {
                    nextTestimonial();
                } else {
                    prevTestimonial();
                }
            }
        }
    </script>

    <!-- Footer -->
    <footer class="bg-gray-800 text-white py-8">
        <div class="max-w-6xl mx-auto px-4 text-center">
            <p class="text-gray-400">
                © 2024 大人のための英語ワークショップ.<br>All rights reserved.
            </p>
        </div>
    </footer>
</body>
</html>
