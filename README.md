/* 全体のスタイル */
body {
    background-color: #f8f9fa; /* 背景色 */
    font-family: sans-serif;
    display: flex;
    justify-content: center;
    padding: 40px 20px;
    margin: 0;
}

.container {
    width: 100%;
    max-width: 400px; /* スマホで見やすい幅 */
    text-align: center;
}

/* プロフィール画像 */
.profile-img {
    width: 100px;
    height: 100px;
    border-radius: 50%; /* 丸くする */
    object-fit: cover;
    margin-bottom: 20px;
}

/* テキストスタイル */
h1 { font-size: 1.5rem; margin-bottom: 10px; color: #333; }
.bio { font-size: 0.9rem; color: #666; margin-bottom: 30px; }

/* ボタンのスタイル */
.links { display: flex; flex-direction: column; gap: 15px; }

.link-btn {
    background-color: #ffffff; /* ボタンの色 */
    color: #333;
    padding: 15px;
    text-decoration: none;
    border-radius: 8px;
    border: 1px solid #ddd;
    transition: 0.3s;
    font-weight: bold;
}

/* ホバー（マウスを乗せた時）の動き */
.link-btn:hover {
    background-color: #1a73e8;
    color: #ffffff;
    border-color: #1a73e8;
}
