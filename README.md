# Saha-brothers-grocery<!DOCTYPE html>
<html>
<head>
    <title>Saha Brother's Grocery</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        body { font-family: Arial; margin: 0; padding: 0; background: #f9f9f9; }
        header { background: #2E8B57; color: white; padding: 1.5rem; text-align: center; }
        nav { background: #333; padding: 1rem; display: flex; justify-content: center; gap: 1rem; }
        nav a { color: white; text-decoration: none; font-weight: bold; }
        .products { padding: 1rem; display: grid; grid-template-columns: 1fr 1fr; gap: 1rem; }
        .product { background: white; border-radius: 8px; padding: 1rem; text-align: center; box-shadow: 0 2px 5px rgba(0,0,0,0.1); }
        footer { background: #333; color: white; text-align: center; padding: 1.5rem; margin-top: 2rem; }
        .whatsapp-btn {
            position: fixed; bottom: 20px; right: 20px;
            background: #25D366; color: white; width: 60px; height: 60px;
            border-radius: 50%; display: flex; align-items: center;
            justify-content: center; font-size: 1.8rem; box-shadow: 0 2px 10px rgba(0,0,0,0.2);
        }
    </style>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
</head>
<body>
    <header>
        <h1>SAHA BROTHER'S GROCERY</h1>
        <p>Fresh Products • Best Prices • Since 1990</p>
    </header>
    
    <nav>
        <a href="#home"><i class="fas fa-home"></i> Home</a>
        <a href="#products"><i class="fas fa-store"></i> Products</a>
    </nav>
    
    <section id="products" class="products">
        <div class="product">
            <h3><i class="fas fa-apple-alt" style="color:#2E8B57"></i> Fresh Fruits</h3>
            <p>Mango, Banana, Apple</p>
            <p>From ₹99/kg</p>
        </div>
        <div class="product">
            <h3><i class="fas fa-carrot" style="color:#FF7F00"></i> Vegetables</h3>
            <p>Potato, Onion, Tomato</p>
            <p>From ₹49/kg</p>
        </div>
    </section>
    
    <footer>
        <p><i class="fas fa-map-marker-alt"></i> 123 Market Street, Kolkata</p>
        <p><i class="fas fa-phone"></i> +91 YOUR_NUMBER_HERE</p>
        <p><i class="fas fa-clock"></i> 7AM-10PM Daily</p>
        
        <!-- WhatsApp Button - REPLACE THE NUMBER BELOW -->
        <a href="https://wa.me/91YOUR_NUMBER_HERE?text=Hi%20Saha%20Brothers!%20I%20want%20to%20order..." 
           class="whatsapp-btn">
           <i class="fab fa-whatsapp"></i>
        </a>
    </footer>
</body>
</html>