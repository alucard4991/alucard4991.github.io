<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>헬로 월드 버튼</title>
    <style>
        /* 버튼 스타일 */
        button {
            padding: 10px 20px;
            font-size: 16px;
            color: white;
            background-color: #007BFF;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        button:hover {
            background-color: #0056b3;
        }
    </style>
</head>
<body>

    <button id="myButton">클릭하세요!</button>

    <script>
        // 버튼 클릭 시 "헬로 월드!" 메시지 표시
        document.getElementById("myButton").onclick = function() {
            alert("헬로 월드!");
        };
    </script>

</body>
</html>
