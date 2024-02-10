<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>cVS 영화 무인 예매</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
            text-align: center;
        }

        h1 {
            color: #333;
        }

        button {
            padding: 10px;
            background-color: #4CAF50;
            color: #fff;
            border: none;
            cursor: pointer;
        }

        #confirmationMessage {
            color: #4CAF50;
            display: none;
        }
    </style>
</head>
<body>
    <h1>cVS 영화 무인 예매</h1>
    
    <button onclick="reserveTicket()">예매 하기</button>
    
    <p id="confirmationMessage">예매가 완료되었습니다!</p>

    <script>
        function reserveTicket() {
            // 여기에서 실제로 서버에 예매 정보를 전송하는 로직을 추가할 수 있습니다.
            
            // 간단하게 버튼을 클릭하면 예매 완료 메시지를 보여주는 예시 코드
            document.getElementById('confirmationMessage').style.display = 'block';
        }
    </script>
</body>
</html>
