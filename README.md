# soulmate
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Para mi baby claya</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Dancing+Script:wght@400..700&family=Inter:wght@400;700&display=swap" rel="stylesheet">
    <script src="https://cdn.tailwindcss.com"></script>
    <style>

        
        body {
            font-family: 'Inter', sans-serif;
            background: linear-gradient(135deg, #f0f0f0 0%, #d8d8d8 100%);
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            color: #4b5563;
        }
        .container {
            background-color: pink;
            padding: 2.5rem;
            border-radius: 20px;
            box-shadow: 0 10px 25px rgba(0, 0, 0, 0.1);
            max-width: 90%;
            width: 500px;
            text-align: center;
            animation: fadeIn 1.5s ease-in-out;
        }
         .container7 {
            background-color: rgb(108, 192, 207);
            padding: 2.5rem;
            border-radius: 20px;
            box-shadow: 0 10px 25px rgba(0, 0, 0, 0.1);
            max-width: 90%;
            width: 500px;
            text-align: center;
            animation: fadeIn 1.5s ease-in-out;
        }
        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(20px); }
            to { opacity: 1; transform: translateY(0); }
        }
        .title {
            font-family: 'Dancing Script', cursive;
            font-size: 3rem;
            color: #ef4444;
            margin-bottom: 1rem;
            animation: popIn 1s ease-out;
        }
        @keyframes popIn {
            from { transform: scale(0.8); opacity: 0; }
            to { transform: scale(1); opacity: 1; }
        }
        .message-container {
            margin-top: 1.5rem;
            min-height: 150px;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            font-size: 1.125rem;
            line-height: 1.75rem;
        }
        .cursor {
            display: inline-block;
            width: 2px;
            height: 1.2em;
            background-color: #4b5563;
            margin-left: 2px;
            animation: blink 0.7s infinite;
        }
        @keyframes blink {
            0%, 100% { opacity: 1; }
            50% { opacity: 0; }
        }
        .heart-icon {
            color: #ef4444;
            font-size: 2rem;
            animation: pulse 1.5s infinite;
            margin-top: 1rem;
        }
        @keyframes pulse {
            0%, 100% { transform: scale(1); }
            50% { transform: scale(1.1); }
        }
        .images-container {
            display: flex;
            justify-content: center;
            gap: 1rem;
            margin-top: 2rem;
            flex-wrap: wrap;

            }
        .images-container1 img {
            border-radius: 12px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
            width: 150px;
            height: 150px;
            object-fit: cover;
        }
         
        .images-container6 img {
            border-radius: 12px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
            width: 150px;
            height: 150px;
            object-fit: cover;
        }
        .images-container img {
            border-radius: 12px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
            width: 150px;
            height: 150px;
            object-fit: cover;
        }
        .social-icons-container {
            display: flex;
            justify-content: center;
            gap: 1.5rem;
            margin-top: 2rem;
        }
        .social-icons-container a {
            color: #4b5563;
            transition: color 0.3s ease;
        }
        .social-icons-container a:hover {
            color: #ef4444;
        }
        .social-icons-container svg {
            width: 32px;
            height: 32px;
        }
        .letter-container {
            background-color: #ffe4e6;
            text-align: left;
        }
        .music-container {
            background-color: #c4e9ff;
        }
        .letter-title {
            font-family: 'Dancing Script', cursive;
            font-size: 2.5rem;
            color: #e57373;
            margin-bottom: 1rem;
            text-align: center;
        }
         .title {
            font-family: 'Dancing Script', cursive;
            font-size: 3rem;
            color: #ef4444;
            margin-bottom: 1rem;
            animation: popIn 1s ease-out;
        }
         
        .container, .letter-container, .music-container {
            padding: 2.5rem;
            border-radius: 20px;
            box-shadow: 0 10px 25px rgba(0, 0, 0, 0.1);
            max-width: 90%;
            width: 500px;
            text-align: center;
            animation: fadeIn 1.5s ease-in-out;
            margin-bottom: 2rem;
        }
    </style>
</head>
<body>

    <div class="container">
        <h1 class="title">Para mi baby claya</h1>
        <div class="message-container">
            <span id="message"></span><span class="cursor"></span>
        </div>
        <div class="heart-icon">
            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-8 h-8 mx-auto">
                <path d="m11.645 20.917-7.397-7.397 7.393-7.393a.75.75 0 0 1 1.063 0l7.394 7.394-7.393 7.393a.75.75 0 0 1-1.063 0Z" />
                <path d="M12.75 21.666a.75.75 0 0 1-.75-.75V8.14a6.75 6.75 0 0 0-6.75-6.75H2.5a.75.75 0 0 1-.75-.75V.75a.75.75 0 0 1 .75-.75h3.5a8.25 8.25 0 0 1 8.25 8.25V20.916a.75.75 0 0 1-.75.75h-1.5Z" />
            </svg>
        </div>
    </div>
    
    <!-- Contenedor para imágenes -->
    <div class="images-container">
        <!-- Reemplaza estos enlaces (URL) por los de tus fotos subidas a internet -->
        <img src="C:\Users\User\Desktop\programa\WhatsApp Image 2025-09-04 at 11.26.35 PM.jpeg" alt="Imagen 1">
        <img src="C:\Users\User\Downloads\WhatsApp Image 2025-09-04 at 11.26.37 PM.jpeg" alt="Imagen 2">
        <img src="C:\Users\User\Documents\1757049195277.jpg" alt="Imagen 1">
         <img src="C:\Users\User\Documents\1757049195293.jpg" alt="Imagen 6">

    </div>

    <!-- Contenedor para redes sociales -->
    <div class="social-icons-container">
        <!-- Ícono de Instagram -->
        <a href="#" target="_blank">
            <svg xmlns="https://www.instagram.com/stories/highlights/18012434867655693/" viewBox="0 0 24 24" fill="currentColor">
                <path d="https://www.instagram.com/stories/highlights/18012434867655693/https://www.instagram.com/stories/highlights/18012434867655693/"/>
            </svg>
        </a>
        <!-- Ícono de TikTok -->
        <div class="social-icons-container">
    <a href="https://www.instagram.com/stories/highlights/18012434867655693/" target="_blank">
        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor">
            <path d="M12 2C8.686 2 8.243 2.015 6.958 2.08s-2.054.341-2.76.618c-.705.277-1.258.629-1.802 1.173s-.896 1.11-1.173 1.802c-.277.705-.618 2.054-.618 2.76s-.08 1.343-.08 4.646c0 3.303.015 3.746.08 5.031.065 1.393.341 2.054.618 2.76s.629 1.258 1.173 1.802 1.11.896 1.802 1.173c.705.277 2.054.618 2.76.618s1.343.08 4.646.08c3.303 0 3.746-.015 5.031-.08s2.054-.341 2.76-.618c.705-.277 1.258-.629 1.802-1.173s.896-1.11 1.173-1.802c.277-.705.618-2.054.618-2.76s.08-1.343.08-4.646c0-3.303-.015-3.746-.08-5.031s-.341-2.054-.618-2.76c-.277-.705-.629-1.258-1.173-1.802s-1.11-.896-1.802-1.173c-.705-.277-2.054-.618-2.76-.618s-1.343-.08-4.646-.08zM12 4c2.81 0 3.167.01 4.298.077c1.077.065 1.706.31 2.222.527s.94.526 1.285.871c.345.345.65.77.871 1.285s.462 1.145.527 2.222c.067 1.131.077 1.488.077 4.298s-.01 3.167-.077 4.298c-.065 1.077-.31 1.706-.527 2.222s-.526.94-.871 1.285c-.345.345-.77.65-1.285.871s-1.145.462-2.222.527c-1.131.067-1.488.077-4.298.077s-3.167-.01-4.298-.077c-1.077-.065-1.706-.31-2.222-.527s-.94-.526-1.285-.871c-.345-.345-.65-.77-.871-1.285s-.462-1.145-.527-2.222c-.067-1.131-.077-1.488-.077-4.298s.01-3.167.077-4.298c.065-1.077.31-1.706.527-2.222s.526-.94.871-1.285c.345-.345.77-.65 1.285-.871s1.145-.462 2.222-.527c1.131-.067 1.488-.077 4.298-.077zM12 6.875c-2.825 0-5.125 2.3-5.125 5.125s2.3 5.125 5.125 5.125 5.125-2.3 5.125-5.125-2.3-5.125-5.125-5.125zM12 8.75c1.795 0 3.25 1.455 3.25 3.25s-1.455 3.25-3.25 3.25-3.25-1.455-3.25-3.25 1.455-3.25 3.25-3.25zM17.25 5.75c-.69 0-1.25-.56-1.25-1.25s.56-1.25 1.25-1.25 1.25.56 1.25 1.25-.56 1.25-1.25 1.25z"/>
        </svg>
    </a>
    <a href="https://vm.tiktok.com/ZMArYuRKM/" target="_blank">
        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor">
            <path d="M12.525 2.112v-1.127c0-.285.34-.406.533-.207 1.748 1.83 2.853 3.996 3.328 6.368.04.195-.084.382-.277.422-2.583.54-5.076-.842-5.754-3.526zm-2.127.327c-.201-.066-.406.012-.497.195-.884 1.768-1.034 3.73-.55 5.632.483 1.902 2.33 3.33 4.544 3.497.202.015.378-.148.423-.35.045-.202-.124-.378-.326-.423-1.89-.39-3.41-1.636-3.83-3.504-.42-1.868-.204-3.904.55-5.787zm.75 6.049c-.22.106-.475.148-.71.12-.236-.028-.466-.12-.676-.237l-1.432.842c-2.148 1.256-4.225 3.125-5.835 5.48-1.61 2.355-2.54 5.253-2.738 8.169-.02.29.13.565.39.69.26.12.56.09.8-.07l1.49-.91c.21-.13.31-.38.25-.63-.16-.67-.28-1.35-.35-2.04-.07-.7-.03-1.4.12-2.1.15-.7.4-1.35.75-1.95.35-.6.75-1.15 1.2-1.65.45-.5.95-.9 1.5-.1.55-.15 1.1-.2 1.65-.15.55-.05.5-1.05 1.25-1.5.75-2.5 1.4-2.8 2.5-3.4s2.25-1.45 4.35-1.55c2.1-.1 4.2-.05 6.3.15 2.1.2 4.2.6 6.1 1.4.45-.05.85-.15 1.25-.25.4-.1.75-.25 1.1-.45.35-.2.65-.4.9-.6.25-.2.45-.45.6-.7.15-.25.25-.5.3-.75.05-.25.05-.5.05-.75-.05-.2-.15-.4-.25-.6-.1-.2-.25-.4-.4-.55-.15-.15-.3-.25-.5-.35-.2-.1-.4-.15-.6-.2-.2-.05-.4-.05-.6-.05z"/>
        </svg>
    </a>
</div>

    <div class="letter-container">
        <h2 class="letter-title">Una mi cartita pa vos </h2>
        <p>hola nena de mi corazon te hice esto para que veas que soy una pro jajja y para que sepa que te amo con mi alma por que siempre te llevare conmigo  eres mi nena por siempre 
            son la una de la mañana y sigo aqui por que ando fiebrua y ya eso es todo espero y te guste y la valores por que ya en estos momento cargo los 
            deo tuyio te me bebe bye 
        </p>
        <p>por siempre nacho</p>
    </div>

    <div class="music-container">
        <h2 class="letter-title">dale clik para que te acuerdes mio</h2>
        <a href="https://www.youtube.com/watch?v=3udfT6NFg8Q&list=RD3udfT6NFg8Q&start_radio=1" target="_blank" style="color:#ef4444; font-weight:bold;">¡Haz clic aquí para escuchar nuestra canción!</a>
   <h3 class="letter-title">dale clik que te la dedico bebe </h3>
        <a href="https://www.youtube.com/watch?v=XoJNjj81eOM&list=RDXoJNjj81eOM&start_radio=1" target="_blank" style="color:#dda0e9; font-weight:bold;">¡Haz clic aquí para escuchar nuestra canción!</a>
    </div>
    <script>
  

        const messageElement = document.getElementById('message');
        const messages = [
            "Eres la persona más maravillosa que he conocido.",
            "te amo un mundo gracias por ser parte de mi live.",
            "Gracias por todo .",
            "mas nadie te resuelve como yo kaskaskas."
            
        ];
        let messageIndex = 0;
        let charIndex = 0;
        let isDeleting = false;
        let typingSpeed = 100;

        function typeMessage() {
            const currentMessage = messages[messageIndex];
            
            if (isDeleting) {
                messageElement.textContent = currentMessage.substring(0, charIndex - 1);
                charIndex--;
            } else {
                messageElement.textContent = currentMessage.substring(0, charIndex + 1);
                charIndex++;
            }

            if (!isDeleting && charIndex === currentMessage.length) {
                isDeleting = true;
                typingSpeed = 2000; // Pausa antes de borrar
            } else if (isDeleting && charIndex === 0) {
                isDeleting = false;
                messageIndex = (messageIndex + 1) % messages.length;
                typingSpeed = 100; // Velocidad de escritura normal
            }

            setTimeout(typeMessage, isDeleting ? 50 : typingSpeed);
        }

        document.addEventListener('DOMContentLoaded', () => {
            typeMessage();
        });
    </script>

</body>
</html>
