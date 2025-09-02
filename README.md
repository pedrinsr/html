<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
         body {
            font-family: Arial, sans-serif;
            padding: 20px;
        }

        p {
            font-size: 18px;
            color: #333;
        }

        button {
            padding: 10px 20px;
            font-size: 16px;
            background-color: #007BFF;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }

        /* Media Query para telas menores que 600px */
        @media (max-width: 600px) {
            p {
                font-size: 14px;
            }

            button {
                background-color: #FF5733; /* muda para laranja */
            }
        }
    </style>
</head>


<body>
 <p>Este é um parágrafo de exemplo. Redimensione a janela para ver o efeito da media query.</p>
    <button>Clique Aqui</button>


    
</body>
</html>
