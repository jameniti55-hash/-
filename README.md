<html lang="th">
<head>
    <meta charset="UTF-8">
    <title>Quest for My Future | เกมค้นหาตัวเอง</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="game-container">
        <div id="start-screen">
            <h1>🧭 Quest for My Future</h1>
            <p>ร่วมออกเดินทางค้นหา "คณะที่ใช่" ใน 1 นาที</p>
            <button onclick="startGame()">เริ่มการเดินทาง</button>
        </div>

        <div id="quiz-screen" class="hidden">
            <div class="progress-bar"><div id="progress"></div></div>
            <h2 id="question-text">คำถามจะปรากฏที่นี่</h2>
            <div id="options-container">
                </div>
        </div>

        <div id="result-screen" class="hidden">
            <h2>✨ การเดินทางสิ้นสุดลงแล้ว!</h2>
            <p>บุคลิกภาพเด่นของคุณคือ: <strong id="personality-type">-</strong></p>
            <div class="recommendation">
                <h3>คณะที่แนะนำสำหรับคุณ:</h3>
                <ul id="faculty-list"></ul>
            </div>
            <button onclick="location.reload()">ทำแบบทดสอบใหม่</button>
        </div>
    </div>
    <script src="script.js"></script>
</body>
</html>
