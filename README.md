

<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>هلو كيتي</title>
    <style>
        body {
            margin: 0;
            font-family: 'Arial', sans-serif;
            background: linear-gradient(135deg, #ffe9f7, #ffdee7);
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            overflow: hidden;
        }

        .fade-out {
            animation: fadeOut 1s forwards;
        }
        .fade-in {
            animation: fadeIn 1s forwards;
        }
        @keyframes fadeOut {
            from { opacity: 1; }
            to { opacity: 0; }
        }
        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }

        #formContainer {
            text-align: center;
            position: relative;
            width: 350px;
            padding: 20px;
            background: rgba(255, 255, 255, 0.8);
            border-radius: 15px;
            box-shadow: 0 8px 20px rgba(0, 0, 0, 0.1);
        }

        #textInput {
            width: 100%;
            padding: 10px 15px;
            font-size: 16px;
            border: 2px solid #ff85b3;
            border-radius: 20px;
            text-align: center;
            outline: none;
            transition: all 0.3s ease;
        }

        #textInput::placeholder {
            color: rgba(150, 75, 100, 0.6);
        }

        #textInput:focus {
            border-color: #ff5d9e;
            box-shadow: 0 4px 8px rgba(255, 93, 158, 0.2);
        }

        button {
            margin-top: 15px;
            padding: 10px 25px;
            font-size: 16px;
            color: white;
            background-color: #ff85b3;
            border: none;
            border-radius: 20px;
            cursor: pointer;
            transition: all 0.3s ease;
        }

        button:hover {
            background-color: #ff5d9e;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }

        #message {
            display: none;
            font-size: 24px;
            font-weight: bold;
            color: #ff85b3;
            text-shadow: 1px 1px 4px rgba(0, 0, 0, 0.2);
            position: relative;
        }

        #kittyImage {
            display: none;
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%) scale(0);
            opacity: 0;
            animation: fadeInScale 2s forwards;
            width: 50%; /* تصغير عرض الصورة إلى النصف */
            height: auto; /* الحفاظ على التناسب */
        }

        @keyframes fadeInScale {
            from {
                transform: translate(-50%, -50%) scale(0.5);
                opacity: 0;
            }
            to {
                transform: translate(-50%, -50%) scale(1);
                opacity: 1;
            }
        }
    </style>
</head>
<body>
    <div id="formContainer" class="fade-in">
        <input type="text" id="textInput" placeholder="اكتب شيئاً">
        <button onclick="handleSubmit()">Send</button>
    </div>
    <div id="message" class="fade-in">نوران عمتككك</div>
    <img id="kittyImage" src="<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>هلو كيتي</title>
    <style>
        body {
            margin: 0;
            font-family: 'Arial', sans-serif;
            background: linear-gradient(135deg, #ffe9f7, #ffdee7);
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            overflow: hidden;
        }

        .fade-out {
            animation: fadeOut 1s forwards;
        }
        .fade-in {
            animation: fadeIn 1s forwards;
        }
        @keyframes fadeOut {
            from { opacity: 1; }
            to { opacity: 0; }
        }
        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }

        #formContainer {
            text-align: center;
            position: relative;
            width: 350px;
            padding: 20px;
            background: rgba(255, 255, 255, 0.8);
            border-radius: 15px;
            box-shadow: 0 8px 20px rgba(0, 0, 0, 0.1);
        }

        #textInput {
            width: 100%;
            padding: 10px 15px;
            font-size: 16px;
            border: 2px solid #ff85b3;
            border-radius: 20px;
            text-align: center;
            outline: none;
            transition: all 0.3s ease;
        }

        #textInput::placeholder {
            color: rgba(150, 75, 100, 0.6);
        }

        #textInput:focus {
            border-color: #ff5d9e;
            box-shadow: 0 4px 8px rgba(255, 93, 158, 0.2);
        }

        button {
            margin-top: 15px;
            padding: 10px 25px;
            font-size: 16px;
            color: white;
            background-color: #ff85b3;
            border: none;
            border-radius: 20px;
            cursor: pointer;
            transition: all 0.3s ease;
        }

        button:hover {
            background-color: #ff5d9e;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }

        #message {
            display: none;
            font-size: 24px;
            font-weight: bold;
            color: #ff85b3;
            text-shadow: 1px 1px 4px rgba(0, 0, 0, 0.2);
            position: relative;
        }

        #kittyImage {
            display: none;
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%) scale(0);
            opacity: 0;
            animation: fadeInScale 2s forwards;
            width: 50%; /* تصغير عرض الصورة إلى النصف */
            height: auto; /* الحفاظ على التناسب */
        }

        @keyframes fadeInScale {
            from {
                transform: translate(-50%, -50%) scale(0.5);
                opacity: 0;
            }
            to {
                transform: translate(-50%, -50%) scale(1);
                opacity: 1;
            }
        }
    </style>
</head>
<body>
    <div id="formContainer" class="fade-in">
        <input type="text" id="textInput" placeholder="اكتب شيئاً">
        <button onclick="handleSubmit()">Send</button>
    </div>
    <div id="message" class="fade-in">نوران عمتككك</div>
    <img id="kittyImage" src="https://i.postimg.cc/5N899whj/IMG-0577.png" alt="Hello Kitty">

    <script>
        const formContainer = document.getElementById('formContainer');
        const message = document.getElementById('message');
        const kittyImage = document.getElementById('kittyImage');

        function handleSubmit() {
            formContainer.classList.add('fade-out');
            setTimeout(() => {
                formContainer.style.display = 'none';

                // إظهار النص
                message.style.display = 'block';

                // بعد 2 ثانية، تظهر الصورة الشفافة
                setTimeout(() => {
                    kittyImage.style.display = 'block';
                    kittyImage.style.opacity = 1;
                    kittyImage.style.transform = "translate(-50%, -50%) scale(1)";

                    // اختفاء تدريجي للصورة بعد 2 ثانية
                    setTimeout(() => {
                        kittyImage.style.opacity = 0;
                        kittyImage.style.transform = "translate(-50%, -50%) scale(1.5)";
                    }, 2000);
                }, 2000);
            }, 1000);

            // بعد 6 ثوانٍ، يعود النموذج ويختفي النص والصورة
            setTimeout(() => {
                message.classList.add('fade-out');
                setTimeout(() => {
                    message.style.display = 'none';
                    message.classList.remove('fade-in', 'fade-out');
                    kittyImage.style.display = 'none';
                    kittyImage.style.opacity = 1;
                    kittyImage.style.transform = "translate(-50%, -50%) scale(0)";

                    formContainer.style.display = 'block';
                    formContainer.classList.add('fade-in');
                    document.getElementById('textInput').value = '';
                }, 1000);
            }, 6000);
        }
    </script>
</body>
</html>" alt="Hello Kitty">

    <script>
        const formContainer = document.getElementById('formContainer');
        const message = document.getElementById('message');
        const kittyImage = document.getElementById('kittyImage');

        function handleSubmit() {
            formContainer.classList.add('fade-out');
            setTimeout(() => {
                formContainer.style.display = 'none';

                // إظهار النص
                message.style.display = 'block';

                // بعد 2 ثانية، تظهر الصورة الشفافة
                setTimeout(() => {
                    kittyImage.style.display = 'block';
                    kittyImage.style.opacity = 1;
                    kittyImage.style.transform = "translate(-50%, -50%) scale(1)";

                    // اختفاء تدريجي للصورة بعد 2 ثانية
                    setTimeout(() => {
                        kittyImage.style.opacity = 0;
                        kittyImage.style.transform = "translate(-50%, -50%) scale(1.5)";
                    }, 2000);
                }, 2000);
            }, 1000);

            // بعد 6 ثوانٍ، يعود النموذج ويختفي النص والصورة
            setTimeout(() => {
                message.classList.add('fade-out');
                setTimeout(() => {
                    message.style.display = 'none';
                    message.classList.remove('fade-in', 'fade-out');
                    kittyImage.style.display = 'none';
                    kittyImage.style.opacity = 1;
                    kittyImage.style.transform = "translate(-50%, -50%) scale(0)";

                    formContainer.style.display = 'block';
                    formContainer.classList.add('fade-in');
                    document.getElementById('textInput').value = '';
                }, 1000);
            }, 6000);
        }
    </script>
</body>
</html>
