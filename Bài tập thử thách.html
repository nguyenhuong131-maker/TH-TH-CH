<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Play games with HTM</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap');

        body {
            font-family: 'Roboto', Arial, sans-serif;
            margin: 0;
            padding: 0;
            background: linear-gradient(to bottom, #f0faff, #ffffff); /* Nền trang xanh cực nhạt */
            color: #333;
        }

        /* --- ĐÂY LÀ PHẦN SỬA MÀU NỀN DÒNG ĐẦU TIÊN --- */
        header {
            background: linear-gradient(135deg, #e0f2f1, #b2ebf2); /* Màu xanh nhạt nhẹ nhàng */
            padding: 40px 0;
            text-align: center;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.05);
            border-bottom: 2px solid #80deea;
        }

        header h1 {
            margin: 0;
            color: #006064; /* Chữ xanh đậm để nổi bật trên nền nhạt */
            font-size: 42px;
            font-weight: 700;
            text-transform: uppercase;
            letter-spacing: 2px;
            text-shadow: 1px 1px 2px rgba(255,255,255,0.8);
        }

        header p {
            margin-top: 10px;
            color: #00838f;
            font-size: 20px;
            font-style: italic;
            font-weight: bold;
        }
        /* ------------------------------------------- */

        .container {
            background-color: #ffffff;
            padding: 40px;
            border-radius: 16px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.08);
            text-align: center;
            width: 90%;
            max-width: 700px;
            margin: 30px auto;
        }

        h1 {
            margin-bottom: 20px;
            font-size: 28px;
            color: #00796b;
            font-weight: bold;
        }

        textarea {
            width: 100%;
            height: 140px;
            margin: 20px 0;
            padding: 15px;
            border: 2px solid #80deea;
            border-radius: 12px;
            font-size: 16px;
            font-family: 'Courier New', Courier, monospace;
            resize: none;
            background-color: #fafafa;
        }

        button {
            padding: 14px 35px;
            font-size: 16px;
            color: #fff;
            background: linear-gradient(135deg, #00acc1, #00838f);
            border: none;
            border-radius: 30px;
            cursor: pointer;
            transition: all 0.3s ease;
            font-weight: bold;
            text-transform: uppercase;
            box-shadow: 0 4px 15px rgba(0, 131, 143, 0.3);
        }

        button:hover {
            transform: translateY(-2px);
            box-shadow: 0 6px 20px rgba(0, 131, 143, 0.4);
        }

        #result {
            margin-top: 25px;
            font-size: 18px;
            font-weight: bold;
            min-height: 24px;
        }

        footer {
            background: #f1f8e9;
            color: #555;
            text-align: center;
            padding: 25px 0;
            margin-top: 50px;
            border-top: 1px solid #dcedc8;
        }

        footer a { color: #00796b; text-decoration: none; font-weight: bold; }
    </style>
</head>
<body>
    <header>
        <h1>Play games with HTM</h1>
        <p>Chinh phục thử thách - Khám phá đam mê!</p>
    </header>
    <div class="container">
        <h1 id="level-title">Nhiệm vụ Level 1</h1>
        <p id="level-desc">Viết một thẻ tiêu đề &lt;h1&gt; Chào mừng các bạn đến với khóa học HTML</p>
        <textarea id="codeInput" placeholder="Nhập mã HTML của bạn ở đây..."></textarea>
        <button onclick="checkAnswer()">Kiểm tra</button>
        <div id="result"></div>
        <div id="score">Điểm: 0 | Cúp: 0</div>
    </div>
    <footer>
        &copy; 2025 HTML Learning Game. <a href="#">Điều khoản sử dụng</a> | <a href="#">Chính sách bảo mật</a>
    </footer>
    <script>
        let levels = [
            { desc: "Viết một thẻ tiêu đề <h1> với nội dung: Chào mừng các bạn đến với khóa học HTML", answer: "<h1>Chào mừng các bạn đến với khóa học HTML</h1>" },
            { desc: "Thêm hình ảnh có đường dẫn 'image.jpg'", answer: "<img src='image.jpg'>" },
            { desc: "Tạo danh sách có thứ tự với các mục: Toán, Lý, Hóa", answer: "<ol><li>Toán</li><li>Lý</li><li>Hóa</li></ol>" },
            { desc: "Tạo bảng với 2 hàng và 2 cột", answer: "<table><tr><td>1</td><td>2</td></tr><tr><td>3</td><td>4</td></tr></table>" },
            { desc: "Thêm liên kết với nội dung 'Google' và đường dẫn 'https://google.com'", answer: "<a href='https://google.com'>Google</a>" },
            { desc: "Tạo liên kết mở trong tab mới với nội dung 'Facebook' và đường dẫn 'https://facebook.com'", answer: "<a href='https://facebook.com' target='_blank'>Facebook</a>" },
            { desc: "Tạo bảng với 3 hàng và 3 cột, điền dữ liệu từ 1 đến 9", answer: "<table><tr><td>1</td><td>2</td><td>3</td></tr><tr><td>4</td><td>5</td><td>6</td></tr><tr><td>7</td><td>8</td><td>9</td></tr></table>" },
            { desc: "Chèn video với đường dẫn 'video.mp4' và thêm thuộc tính tự động phát", answer: "<video src='video.mp4' autoplay></video>" },
            { desc: "Thêm hình ảnh với đường dẫn 'avatar.jpg' và thuộc tính thay thế là 'Ảnh đại diện'", answer: "<img src='avatar.jpg' alt='Ảnh đại diện'>" },
            { desc: "Tạo liên kết email với nội dung 'Liên hệ tôi' và địa chỉ email 'example@gmail.com'", answer: "<a href='mailto:example@gmail.com'>Liên hệ tôi</a>" }
        ];

        let currentLevel = 0;
        let score = 0;
        let attempts = {};

        function loadLevel() {
            document.getElementById("level-title").innerText = `Nhiệm vụ Level ${currentLevel + 1}`;
            document.getElementById("level-desc").innerText = levels[currentLevel].desc;
            document.getElementById("codeInput").value = "";
            document.getElementById("score").innerText = `Điểm: ${score} | Cúp: ${Math.floor(score / 10)}`;
        }

        function normalizeString(str) {
            return str.replace(/\s+/g, '').toLowerCase();
        }

        function checkAnswer() {
            let userCode = normalizeString(document.getElementById("codeInput").value.trim());
            let correctAnswer = normalizeString(levels[currentLevel].answer);

            attempts[currentLevel] = (attempts[currentLevel] || 0) + 1;

            if (userCode === correctAnswer) {
                if (attempts[currentLevel] === 1) {
                    score += 10;
                } else {
                    score += 5;
                }
                document.getElementById("result").innerHTML = "🎉 Đúng rồi! Bạn đã mở khóa Level tiếp theo!";
                currentLevel++;
                if (currentLevel < levels.length) {
                    loadLevel();
                } else {
                    document.getElementById("result").innerHTML += " 🏆 Bạn đã hoàn thành khóa học!";
                }
            } else {
                document.getElementById("result").innerHTML = "❌ Sai! Hãy thử lại!";
                document.getElementById("result").style.color = "#dc3545";
            }
            document.getElementById("score").innerText = `Điểm: ${score} | Cúp: ${Math.floor(score / 10)}`;
        }

        window.onload = loadLevel;
    </script>
</body>
</html>