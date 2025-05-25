<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>데이터 압축 테스트</title>
</head>
<body>
    <h1>데이터 압축 테스트</h1>
    <input type="number" id="size" value="1000">
    <button onclick="test()">실행</button>
    <div id="result"></div>

    <script>
        function test() {
            const size = parseInt(document.getElementById('size').value);
            const result = document.getElementById('result');
            result.innerHTML = `크기: ${size} bytes`;
        }
    </script>
</body>
</html>
