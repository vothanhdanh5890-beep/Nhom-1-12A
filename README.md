# Nhom-1-12A
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Giới thiệu Nhóm</title>
    <style>
        body {
            font-family: Courier;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background: url('https://images.unsplash.com/photo-1496170804262-975019a5cd34?fm=jpg&q=60&w=3000&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8M3x8Ymx1ZSUyMHNreSUyMHN0YXJ8ZW58MHx8MHx8fDA%3D') no-repeat center center/cover;
            color: white;
            padding: 50px 0;
            text-align: center;
            animation: fadeIn 2s;
        }
        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }
        .container {
            max-width: 800px;
            margin: 20px auto;
            padding: 20px;
            background: white;
            border-radius: 5px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        h2 {
            color: #00008B;
            text-align: center;
        }
        .member {
            margin: 20px 0;
            padding: 10px;
            border: 1px solid #ddd;
            border-radius: 5px;
            transition: transform 0.3s;
        }
        .member:hover {
            transform: scale(1.05);
            background-color: #f0f8ff;
        }
        .member a {
            text-decoration: none;
            color: #00008B;
            font-weight: bold;
        }
        .form-container {          
            margin-top: 30px;
            padding: 20px;
            background: #e9ecef;
            border-radius: 5px;
            color-text: white
        }
        .form-container input, .form-container textarea {
        	font-family: Courier;
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #ccc;
            border-radius: 5px;
       }
        .form-container button {
        	font-family: cursive;            color: #00008B;

            background-color: #00008B;
            color: white;
            border: none;
            padding: 10px;
            border-radius: 5px;
            cursor: pointer;
        }
        .form-container button:hover {
            background-color: #0056b3;
        }
    </style>
</head>
<body>

<header>
    <h1>Nhóm 1 12A</h1>
</header>

<div class="container">
    <h2>MEMBERS</h2>
    <div class="member">
        <a href="new 1.html" target="_blank">Võ Thành Danh</a> - 12A
    </div>
    <div class="member">
        <a href="LDK2.html" target="_blank">Nguyễn Phi Vũ</a> - 12A
    </div>
    <div class="member">
        <a href="VTMQ2.html" target="_blank">Phạm Yến Ngân</a> - 12A
    </div>
    <div class="member">
        <a href="HQTPVP.html" target="_blank">Cao Ngô Anh Vy</a> - 12A 
    </div>
</div>   
 <div class="container">
    <h2>VẬN DỤNG</h2>
    <div class="member">
        <a href="BÀI 7.html" target="_blank">Bài 7</a>
    </div>
    <div class="member">
        <a href="BÀI 8.html" target="_blank">Bài 8</a>
    </div>
    <div class="member">
        <a href="BÀI 9.html" target="_blank">Bài 9</a>
    </div>
    <div class="member">
        <a href="https://www.canva.com/design/DAGeylKMN6Q/8qlDOL7zoI1WaUNN2H1gxA/edit?utm_content=DAGeylKMN6Q&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton" target="_blank">Bài 19</a>
    </div>
    <div class="member">
        <a href="https://www.canva.com/design/DAGezCHDyXk/zPQHyBuUqG8yYIAulGoRfg/edit?utm_content=DAGezCHDyXk&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton" target="_blank">Bài 20</a>
    </div>
    <div class="member">
        <a href="https://www.canva.com/design/DAGezohi7ec/Y9rfzDmfGDD8FKm_aAOd2w/edit?utm_content=DAGezohi7ec&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton" target="_blank">Bài 21</a>
    </div>
     <div class="member">
        <a href="https://www.canva.com/design/DAGiuKmB8k0/oBXUHZJfP0ElPxYGendmcg/edit?utm_content=DAGiuKmB8k0&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton" target="_blank">Bài 22</a>
    </div>
</div>    
<div class="container form-container">
    <h2>FORM</h2>
    <form>
        <input type="text"placeholder="Họ và tên" required>
        <input type="date" placeholder="Ngày sinh" required>
        <input type="email" placeholder="Email" required>
        <textarea placeholder="Sở thích" rows="3"></textarea>
        <textarea placeholder="Hoạt động gần đây" rows="3"></textarea>
        <button type="submit">Submit</button>
    </form>
</div>
</body>
</html>
