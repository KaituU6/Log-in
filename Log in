<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>تسجيل الدخول</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background-color: #f4f4f4;
        }
        .login-container {
            width: 300px;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            background-color: #fff;
        }
        h2 {
            text-align: center;
        }
        label {
            display: block;
            margin-top: 10px;
        }
        input[type="email"],
        input[type="password"],
        input[type="submit"] {
            width: 100%;
            padding: 8px;
            margin-top: 5px;
            border: 1px solid #ddd;
            border-radius: 4px;
        }
        input[type="submit"] {
            background-color: #007bff;
            color: white;
            cursor: pointer;
            font-weight: bold;
        }
        input[type="submit"]:hover {
            background-color: #0056b3;
        }
    </style>
</head>
<body>
    <div class="login-container">
        <h2>تسجيل الدخول</h2>
        <form onsubmit="return validateCredentials()">
            <label for="email">البريد الإلكتروني:</label>
            <input type="email" id="email" placeholder="example@example.com" required>

            <label for="password">كلمة المرور:</label>
            <input type="password" id="password" placeholder="********" required>

            <input type="submit" value="تسجيل الدخول">
        </form>
    </div>

    <script>
        // بيانات الدخول الصحيحة
        const correctEmail = "user@example.com";
        const correctPassword = "password123";

        function validateCredentials() {
            const email = document.getElementById("email").value;
            const password = document.getElementById("password").value;

            if (email === correctEmail && password === correctPassword) {
                alert("تم تسجيل الدخول بنجاح!");
                return true; // يسمح بإرسال النموذج
            } else {
                alert("البريد الإلكتروني أو كلمة المرور غير صحيحة.");
                return false; // يمنع إرسال النموذج إذا كانت البيانات غير صحيحة
            }
        }
    </script>
</body>
</html>
