<!DOCTYPE html>  <html lang="fr">  
<head>  
    <meta charset="UTF-8">  
    <meta name="viewport" content="width=device-width, initial-scale=1.0">  
    <title>Chris Digit Shop - Produits Numériques</title>  
    <style>  
        :root {  
            --primary: #0284c7;  
            --primary-dark: #0369a1;  
            --accent: #f97316;  
            --airtel: #e11d48;  
            --mpesa: #16a34a;  
            --whatsapp: #25d366;  
            --dark: #0f172a;  
            --light: #f8fafc;  
            --gray: #64748b;  
        }  * {  
        margin: 0;  
        padding: 0;  
        box-sizing: border-box;  
        font-family: 'Segoe UI', Roboto, Helvetica, Arial, sans-serif;  
    }  

    body {  
        background-color: var(--light);  
        color: var(--dark);  
        line-height: 1.6;  
    }  

    header {  
        background-color: #ffffff;  
        box-shadow: 0 2px 10px rgba(0,0,0,0.05);  
        position: sticky;  
        top: 0;  
        z-index: 100;  
    }  

    nav {  
        display: flex;  
        justify-content: space-between;  
        align-items: center;  
        max-width: 1200px;  
        margin: 0 auto;  
        padding: 1rem 2rem;  
    }  

    .logo {  
        font-size: 1.5rem;  
        font-weight: bold;  
        color: var(--primary-dark);  
    }  

    .logo span {  
        color: var(--accent);  
    }  

    .hero {  
        max-width: 1200px;  
        margin: 2rem auto;  
        padding: 4rem 2rem;  
        text-align: center;  
        background: linear-gradient(135deg, #e0f2fe 0%, #f8fafc 100%);  
        border-radius: 12px;  
    }  

    .hero h1 {  
        font-size: 2.5rem;  
        margin-bottom: 1rem;  
    }  

    .payment-badges {  
        display: flex;  
        justify-content: center;  
        gap: 1rem;  
        margin-top: 1.5rem;  
        flex-wrap: wrap;  
    }  

    .badge {  
        padding: 0.5rem 1.2rem;  
        border-radius: 20px;  
        color: white;  
        font-weight: bold;  
        font-size: 0.9rem;  
    }  

    .badge-airtel { background-color: var(--airtel); }  
    .badge-mpesa { background-color: var(--mpesa); }  

    .products {  
        max-width: 1200px;  
        margin: 3rem auto;  
        padding: 0 2rem;  
    }  

    .grid {  
        display: grid;  
        grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));  
        gap: 2rem;  
    }  

    .card {  
        background: white;  
        border-radius: 10px;  
        padding: 1.5rem;  
        box-shadow: 0 4px 6px rgba(0,0,0,0.05);  
        display: flex;  
        flex-direction: column;  
        justify-content: space-between;  
    }  

    .card-icon {  
        font-size: 2.5rem;  
        margin-bottom: 1rem;  
    }  

    .price {  
        font-size: 1.3rem;  
        font-weight: bold;  
        color: var(--accent);  
        margin: 1rem 0;  
    }  

    .btn-buy {  
        display: block;  
        background-color: var(--primary);  
        color: white;  
        border: none;  
        padding: 0.8rem;  
        border-radius: 6px;  
        font-weight: bold;  
        cursor: pointer;  
        text-align: center;  
        text-decoration: none;  
        transition: background 0.3s;  
    }  

    .btn-buy:hover {  
        background-color: var(--primary-dark);  
    }  

    .payment-info {  
        background-color: white;  
        max-width: 800px;  
        margin: 3rem auto;  
        padding: 2rem;  
        border-radius: 10px;  
        border-left: 5px solid var(--primary);  
        box-shadow: 0 4px 6px rgba(0,0,0,0.05);  
    }  

    .payment-numbers {  
        list-style: none;  
        margin: 1.5rem 0;  
    }  

    .payment-numbers li {  
        font-size: 1.1rem;  
        margin-bottom: 0.8rem;  
        display: flex;  
        align-items: center;  
        gap: 10px;  
    }  

    .btn-whatsapp {  
        display: inline-block;  
        background-color: var(--whatsapp);  
        color: white;  
        padding: 0.8rem 1.5rem;  
        border-radius: 6px;  
        text-decoration: none;  
        font-weight: bold;  
        margin-top: 1rem;  
        transition: opacity 0.3s;  
    }  

    .btn-whatsapp:hover {  
        opacity: 0.9;  
    }  

    footer {  
        background-color: var(--dark);  
        color: white;  
        text-align: center;  
        padding: 2rem;  
        margin-top: 4rem;  
    }  
</style>

</head>  
<body>  <header>  
    <nav>  
        <div class="logo">CHRIS <span>DIGIT SHOP</span></div>  
    </nav>  
</header>  

<section class="hero">  
    <h1>Produits & Solutions Numériques</h1>  
    <p>Téléchargez vos formations, e-books et logiciels en toute simplicité.</p>  
      
    <div class="payment-badges">  
        <span class="badge badge-airtel">Paiement Airtel Money</span>  
        <span class="badge badge-mpesa">Paiement M-Pesa</span>  
    </div>  
</section>  

<section class="products">  
    <div class="grid">  
          
        <div class="card">  
            <div>  
                <div class="card-icon">📚</div>  
                <h3>Formation & E-book</h3>  
                <p>Guide complet pour lancer ton business digital rapidement.</p>  
            </div>  
            <div>  
                <div class="price">10 $ / 25.000 FC</div>  
                <a href="#payer" class="btn-buy">Acheter via Mobile Money</a>  
            </div>  
        </div>  

        <div class="card">  
            <div>  
                <div class="card-icon">⚙️</div>  
                <h3>Pack Templates Canva & Notion</h3>  
                <p>Modèles professionnels prêts à l'emploi pour gagner du temps.</p>  
            </div>  
            <div>  
                <div class="price">5 $ / 12.500 FC</div>  
                <a href="#payer" class="btn-buy">Acheter via Mobile Money</a>  
            </div>  
        </div>  

        <div class="card">  
            <div>  
                <div class="card-icon">💻</div>  
                <h3>Logiciels & Outillage Tech</h3>  
                <p>Outils d'automatisation et clés de licence d'activation.</p>  
            </div>  
            <div>  
                <div class="price">15 $ / 37.500 FC</div>  
                <a href="#payer" class="btn-buy">Acheter via Mobile Money</a>  
            </div>  
        </div>  

    </div>  
</section>  

<!-- Instructions de Paiement Mobile -->  
<section class="payment-info" id="payer">  
    <h2>Comment effectuer votre paiement ?</h2>  
    <br>  
    <p><strong>1. Effectuez votre transfert vers l'un de nos numéros officiels :</strong></p>  
    <ul class="payment-numbers">  
        <li>🔴 <strong>Airtel Money :</strong> +243 98 14 14 235</li>  
        <li>🟢 <strong>M-Pesa :</strong> +243 83 20 53 860</li>  
    </ul>  
    <p><strong>2. Validation & Réception :</strong> Une fois le transfert effectué, cliquez sur le bouton ci-dessous pour nous envoyer votre preuve de paiement (SMS de confirmation) via WhatsApp pour recevoir directement votre lien de téléchargement.</p>  
      
    <a href="https://wa.me/243981414235?text=Bonjour%20Chris%20Digit%20Shop,%20je%20viens%20d'effectuer%20un%20paiement%20pour%20un%20produit%20num%C3%A9rique." target="_blank" class="btn-whatsapp">  
        📱 Envoyer la preuve de paiement sur WhatsApp  
    </a>  
</section>  

<footer>  
    <p>&copy; 2026 Chris Digit Shop - Tous droits réservés.</p>  
</footer>

</body>  
</html>  
Créé moi une site avec c'est code 
