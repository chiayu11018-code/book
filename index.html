<!DOCTYPE html>
<html lang="zh-TW">
<head>
    <meta charset="UTF-8">
    <title>語音魔法書遊戲</title>
    <style>
        body { 
            background-color: #2c3e50; 
            display: flex; 
            flex-direction: column;
            align-items: center; 
            justify-content: center; 
            height: 100vh; 
            margin: 0;
            color: white;
            font-family: Arial, sans-serif;
        }
        #book-container {
            width: 300px;
            height: 400px;
            cursor: pointer;
            transition: transform 0.5s;
        }
        .book-img { width: 100%; height: auto; }
        #status { margin-top: 20px; font-size: 1.2rem; color: #f1c40f; }
        .hidden { display: none; }
        
        /* 簡單的動畫效果 */
        .open-animation { transform: scale(1.1) rotate(-5deg); }
    </style>
</head>
<body>

    <h1>🎙️ 說出「Open」來開啟魔法書</h1>
    
    <div id="book-container">
        <img id="book-image" src="https://img.icons8.com/plasticine/400/book.png" alt="Closed Book" class="book-img">
        <img id="surprise-image" src="https://img.icons8.com/color/200/unicorn.png" class="book-img hidden" alt="Surprise">
    </div>

    <div id="status">等待語音指令...</div>

    <script>
        const bookImage = document.getElementById('book-image');
        const surpriseImage = document.getElementById('surprise-image');
        const statusText = document.getElementById('status');

        // 初始化語音辨識
        const SpeechRecognition = window.SpeechRecognition || window.webkitSpeechRecognition;
        
        if (!SpeechRecognition) {
            statusText.innerText = "您的瀏覽器不支援語音辨識，請使用 Chrome。";
        } else {
            const recognition = new SpeechRecognition();
            recognition.lang = 'en-US'; // 也可以設為 'zh-TW'
            recognition.continuous = true;
            recognition.interimResults = false;

            recognition.onstart = () => {
                statusText.innerText = "魔咒監聽中... (請說 Open)";
            };

            recognition.onresult = (event) => {
                const transcript = event.results[event.results.length - 1][0].transcript.trim().toLowerCase();
                console.log("聽到的內容:", transcript);

                if (transcript.includes("open") || transcript.includes("開啟")) {
                    openMagicBook();
                }
            };

            recognition.onerror = (event) => {
                statusText.innerText = "錯誤: " + event.error;
            };

            // 點擊畫面開始監聽（瀏覽器安全限制需要使用者互動）
            document.body.onclick = () => {
                recognition.start();
                statusText.innerText = "魔法感應啟動...";
            };
        }

        function openMagicBook() {
            statusText.innerText = "魔法已解開！";
            // 替換圖片（這裡可以換成你準備好的書本開啟圖）
            bookImage.src = "https://img.icons8.com/plasticine/400/open-book.png";
            
            setTimeout(() => {
                surpriseImage.classList.remove('hidden');
                document.getElementById('book-container').classList.add('open-animation');
            }, 500);
        }
    </script>
</body>
</html>
