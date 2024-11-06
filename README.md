<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Lời tỏ tình</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background-color: #f0f8ff;
            flex-direction: column;
            text-align: center;
        }
        h1 {
            color: #ff69b4;
        }
        button {
            margin: 10px;
            padding: 10px 20px;
            font-size: 16px;
            cursor: pointer;
            border: none;
            border-radius: 5px;
        }
        #agreeBtn {
            background-color: #32cd32;
            color: white;
        }
        #rejectBtn {
            background-color: #ff6347;
            color: white;
            position: relative;
        }
    </style>
</head>
<body>
    <h1>Chào em!</h1>
    <p>Anh/chị muốn nói rằng anh/chị rất thích em. Em có muốn đồng ý làm bạn với anh/chị không?</p>
    <button id="agreeBtn" onclick="agree()">Đồng ý</button>
    <button id="rejectBtn" onclick="reject()">Từ chối</button>

    <script>
        function agree() {
            alert("Cảm ơn em đã đồng ý! Anh/chị rất vui!");
        }

        function reject() {
            // Di chuyển nút "Từ chối" đến vị trí khác khi bị nhấn vào
            var rejectBtn = document.getElementById("rejectBtn");
            var x = Math.random() * (window.innerWidth - rejectBtn.offsetWidth);
            var y = Math.random() * (window.innerHeight - rejectBtn.offsetHeight);
            rejectBtn.style.position = "absolute";
            rejectBtn.style.left = x + "px";
            rejectBtn.style.top = y + "px";
        }
    </script>
</body>
</html>


AnnDuong086/AnnDuong086 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
