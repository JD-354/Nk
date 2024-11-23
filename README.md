<html><head><base href="javascript:void(0)" />

<meta charset="UTF-8">

<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>NIKE Collection - ZapatoStyle</title>



<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">

<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"></script>

<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">



<style>

:root {

--nike-orange: #FF6B00;

--nike-black: #000000;

}



body {

background: linear-gradient(135deg, #f5f5f5 0%, white 100%); font-family: 'Helvetica', Arial, sans-serif;

}



.navbar {

background-color: var(--nike-black) !important;

}



.product-card {

transition: transform 0.3s; background: white; border-radius: 10px;

box-shadow: 0 4px 8px rgba(0,0,0,0.1); margin-bottom: 20px;

}



.product-card:hover { transform: translateY(-5px);

}



.product-price {

color: var(--nike-orange); font-size: 1.25rem;

font-weight: bold;

}



.nike-btn {

background-color: var(--nike-orange); color: white;

 

border: none;

}



.nike-btn:hover {

background-color: #e65c00; color: white;

}



#cart-counter { position: relative; top: -10px;

right: -5px;

background-color: var(--nike-orange); color: white;

border-radius: 50%; padding: 2px 6px; font-size: 12px;

}



.footer {

background-color: var(--nike-black); color: white;

padding: 20px 0; margin-top: 40px;

}



.sale-badge { position: absolute; top: 10px;

right: 10px;

background-color: var(--nike-orange); color: white;

padding: 5px 10px; border-radius: 5px;

}

</style>

</head>

<body>



<nav class="navbar navbar-expand-lg navbar-dark">

<div class="container">

<a class="navbar-brand" href="https://zapatostyle.com">

<img src="https://images.unsplash.com/photo-1542291026-7eec264c27ff" alt="NIKE Logo" width="40" height="40" class="d-inline-block align-text-top me-2">

NIKE Collection

</a>

 

<button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">

<span class="navbar-toggler-icon"></span>

</button>



<div class="collapse navbar-collapse" id="navbarNav">

<ul class="navbar-nav me-auto">

<li class="nav-item">

<a class="nav-link" href="https://jd-354.github.io/Z/"><i class="fas fa-home"></i> Inicio</a>

</li>

<li class="nav-item">

<a class="nav-link" href="https://zapatostyle.com/nike/nuevos"><i class="fas fa-fire"></i> Nuevos Lanzamientos</a>

</li>

<li class="nav-item">

<a class="nav-link" href="https://zapatostyle.com/nike/deportivos"><i class="fas fa-running"></i> Deportivos</a>

</li>

</ul>



<div class="cart-container">

<button class="btn btn-outline-light">

<i class="fas fa-shopping-cart"></i>

<span id="cart-counter">0</span>

</button>

</div>

</div>

</div>

</nav>



<div class="container mt-4">

<h1 class="text-center mb-4">Colección NIKE</h1>



<div class="row">

<!-- Nike Air Max 90 -->

<div class="col-md-4">

<div class="product-card p-3">

<div class="position-relative">

<img src="https://images.unsplash.com/photo-1514989940723-e8e51635b782" alt="Nike Air Max 90, classic sporty design" class="img-fluid mb-3" width="100%" height="300">

<span class="sale-badge">Nuevo</span>

</div>

<h5>Nike Air Max 90</h5>

<p class="product-price">$149.99</p>

<div class="d-flex justify-content-between">

<select class="form-select w-50 me-2">

 

<option>Talla 7</option>

<option>Talla 8</option>

<option>Talla 9</option>

<option>Talla 10</option>

</select>

<button class="btn nike-btn flex-grow-1">Añadir al carrito</button>

</div>

</div>

</div>



<!-- Nike Air Force 1 -->

<div class="col-md-4">

<div class="product-card p-3">

<img src="https://images.unsplash.com/photo-1549298916-b41d501d3772" alt="Nike Air Force 1, iconic white sneaker" class="img-fluid mb-3" width="100%" height="300">

<h5>Nike Air Force 1</h5>

<p class="product-price">$109.99</p>

<div class="d-flex justify-content-between">

<select class="form-select w-50 me-2">

<option>Talla 7</option>

<option>Talla 8</option>

<option>Talla 9</option>

<option>Talla 10</option>

</select>

<button class="btn nike-btn flex-grow-1">Añadir al carrito</button>

</div>

</div>

</div>



<!-- Nike Zoom Pegasus -->

<div class="col-md-4">

<div class="product-card p-3">

<img src="https://images.unsplash.com/photo-1556906781-9a412961c28c" alt="Nike Zoom Pegasus, performance running shoe" class="img-fluid mb-3" width="100%" height="300">

<h5>Nike Zoom Pegasus</h5>

<p class="product-price">$129.99</p>

<div class="d-flex justify-content-between">

<select class="form-select w-50 me-2">

<option>Talla 7</option>

<option>Talla 8</option>

<option>Talla 9</option>

<option>Talla 10</option>

</select>

<button class="btn nike-btn flex-grow-1">Añadir al carrito</button>

</div>

</div>

 

</div>



<!-- Nike Air VaporMax -->

<div class="col-md-4">

<div class="product-card p-3">

<img src="https://images.unsplash.com/photo-1542291026-7eec264c27ff" alt="Nike Air VaporMax, modern cushioning technology" class="img-fluid mb-3" width="100%" height="300">

<h5>Nike Air VaporMax</h5>

<p class="product-price">$189.99</p>

<div class="d-flex justify-content-between">

<select class="form-select w-50 me-2">

<option>Talla 7</option>

<option>Talla 8</option>

<option>Talla 9</option>

<option>Talla 10</option>

</select>

<button class="btn nike-btn flex-grow-1">Añadir al carrito</button>

</div>

</div>

</div>



<!-- Nike React Element -->

<div class="col-md-4">

<div class="product-card p-3">

<img src="https://images.unsplash.com/photo-1512374382149-233c42b6a83b" alt="Nike React Element, lifestyle comfort shoe" class="img-fluid mb-3" width="100%" height="300">

<h5>Nike React Element</h5>

<p class="product-price">$159.99</p>

<div class="d-flex justify-content-between">

<select class="form-select w-50 me-2">

<option>Talla 7</option>

<option>Talla 8</option>

<option>Talla 9</option>

<option>Talla 10</option>

</select>

<button class="btn nike-btn flex-grow-1">Añadir al carrito</button>

</div>

</div>

</div>

</div>

</div>



<footer class="footer">

<div class="container">

<div class="row">

<div class="col-md-4">

 

<h5>Contacto</h5>

<p><i class="fas fa-phone"></i> +1 234 567 890</p>

<p><i class="fas fa-envelope"></i> nike@zapatostyle.com</p>

</div>

<div class="col-md-4">

<h5>Síguenos</h5>

<a href="https://facebook.com/nike" class="text-white me-3"><i class="fab fa-facebook"></i></a>

<a href="https://instagram.com/nike" class="text-white me-3"><i class="fab fa-instagram"></i></a>

<a href="https://twitter.com/nike" class="text-white"><i class="fab fa-twitter"></i></a>

</div>

<div class="col-md-4">

<h5>Newsletter</h5>

<p>Recibe las últimas novedades de NIKE</p>

<form class="d-flex">

<input type="email" class="form-control me-2" placeholder="Tu email">

<button class="btn nike-btn">Suscribir</button>

</form>

</div>

</div>

</div>

</footer>



<script>

let cartCount = 0;



document.querySelectorAll('.nike-btn').forEach(button => { button.addEventListener('click', () => {

if(button.textContent.includes('Añadir al carrito')) { cartCount++;

document.getElementById('cart-counter').textContent = cartCount;



 













}

});

});

 

const counter = document.getElementById('cart-counter'); counter.style.transform = 'scale(1.5)';

setTimeout(() => { counter.style.transform = 'scale(1)';

}, 200);

 

</script>



</body>

</html>

