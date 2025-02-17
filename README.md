<!DOCTYPE html>
<html>
<head>
    <title>ระบบยืมหนังสือแบบพิเศษ</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
            padding: 20px;
            background-color: #e3f2fd;
        }
        .container {
            max-width: 450px;
            margin: auto;
            background: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 15px rgba(0, 0, 0, 0.2);
        }
        label {
            font-weight: bold;
        }
        input, button {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
        }
        button {
            background-color: #ff7043;
            color: white;
            border: none;
            cursor: pointer;
        }
        button:hover {
            background-color: #d84315;
        }
    </style>
</head>
<body>
    <div class="container">
        <h2>ระบบยืมหนังสือแบบพิเศษ</h2>
        <form>
            <label for="name">ชื่อผู้ยืม:</label>
            <input type="text" id="name" name="name" placeholder="กรอกชื่อของคุณ" required>
            
            <label for="book">ชื่อหนังสือ:</label>
            <input type="text" id="book" name="book" placeholder="กรอกชื่อหนังสือ" required>
            
            <label for="date">วันที่ต้องการยืม:</label>
            <input type="date" id="date" name="date" required>
            
            <label for="duration">ระยะเวลาการยืม (วัน):</label>
            <input type="number" id="duration" name="duration" min="1" max="30" required>
            
            <button type="submit">ยืมหนังสือ</button>
        </form>
    </div>
</body>
</html>

