<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Page d'Accueil</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            background-color: #f5f5f5;
        }

        .form-container {
            background: white;
            padding: 20px 30px;
            border-radius: 10px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            text-align: center;
        }

        .form-container input {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #ddd;
            border-radius: 5px;
        }

        .form-container button {
            padding: 10px 20px;
            background: #333;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            font-size: 16px;
        }

        .form-container button:hover {
            background: #ff7e5f;
        }
    </style>
</head>
<body>
    <div class="form-container">
        <h2>Bienvenue sur Mouslim Style</h2>
        <form id="userForm">
            <input type="text" id="name" placeholder="Entrez votre nom" required>
            <input type="tel" id="phone" placeholder="Entrez votre numéro de téléphone" required>
            <button type="submit">Entrer</button>
        </form>
    </div>

    <script>
        document.getElementById("userForm").addEventListener("submit", function(event) {
            event.preventDefault(); // منع تحديث الصفحة
            const name = document.getElementById("name").value;
            const phone = document.getElementById("phone").value;

            if (name && phone) {
                // الانتقال إلى صفحة المنتجات
                window.location.href = "html produit.html";
            } else {
                alert("Veuillez remplir tous les champs.");
            }
        });
    </script>
   <style>
   body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background: linear-gradient(135deg, #ff7e5f, #feb47b);
    color: #333;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
}

/* Style du formulaire */
form {
    background: white;
    padding: 30px 40px;
    border-radius: 10px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
    width: 100%;
    max-width: 400px;
}

/* Titre de la page */
h1 {
    font-size: 24px;
    text-align: center;
    margin-bottom: 20px;
    color: #333;
}

/* Style des étiquettes */
label {
    font-size: 16px;
    margin-bottom: 5px;
    display: block;
    color: #555;
}

/* Style des champs de saisie */
input[type="text"],
input[type="tel"] {
    width: 100%;
    padding: 10px;
    margin-bottom: 20px;
    border: 1px solid #ddd;
    border-radius: 5px;
    font-size: 14px;
    box-sizing: border-box;
}

/* Bouton de soumission */
button {
    width: 100%;
    background: #ff7e5f;
    color: white;
    border: none;
    border-radius: 5px;
    padding: 10px;
    font-size: 16px;
    cursor: pointer;
    transition: background 0.3s;
}

/* Effet au survol du bouton */
button:hover {
    background: #feb47b;
}
</style>
	
</body>
</html>
