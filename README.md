<!DOCTYPE html>

<head>
    <title>Moda Universal</title>

    <meta charset="UTF-8">

    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-T3c6CoIi6uLrA9TneNEoa7RxnatzjcDSCmG1MXxSR1GAsXEV/Dwwykc2MPK8M2HN" crossorigin="anonymous">
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-C6RzsynM9kWDrMNeT87bh95OGNyZPhcTNXj1NW7RuBCsyN/o0jlpcV8Qyq46cDfL" crossorigin="anonymous"></script>

    <script src="loja.js" async></script>
    
    <style>
        body{
            background-color: black;
            background-size: cover;
        }

        .mainDiv{
            width: 98%;
            margin-top: 2%;
            margin-left: 1%;
            color: white;
            padding: 2%;
            padding-top: 5px;
        }
        .image {
            display: inline-block;
            vertical-align: middle;
            width: 300px;
            height: 200px;
        }
        .text {
            padding-left: 50px;
            display:inline-block;
            position: absolute;
            vertical-align: top;
        }

        .text2{
            padding-left: 170px;
            display:inline-block;
            position: absolute;
            vertical-align: top;
        }

        .imgSelect {
            margin-left: 20px;
            display: inline-block;
            height: 60px;
            vertical-align: bottom;
        }

        .imgSelect:hover {
            border: 3px solid #00d9ff;
        }

        .imageDiv{
            padding-bottom: 50px;
        }
    </style>

    <script>
        function changeImage(name, source) {
            document.getElementById(name).src=source;
        }
    </script>
</head>
<body>
    <img src="imagens/logo.png" width="5%" height="auto" style="padding-left: 50px; padding-top: 20px; position: absolute">
    <div class="container">
        <div class="btn-group" style="padding-top: 20px;">
            <button class="btn btn-primary" style="width: 100px;"></button>
            <a type="button" class="btn btn-primary" href="index.html">Pagina Principal</a>
            <a type="button" class="btn btn-primary" href="novidades.html">Novidades</button>
            <a type="button" class="btn btn-primary" href="contacto.html">Contactos</button>
            <a type="button" class="btn btn-primary" href="termos.html">Termos e Condições</button>
            <a type="button" class="btn btn-primary" href="outros.html">Outros</a>
            <div class="btn-group">
                <button type="button" class="btn btn-primary dropdown-toggle" data-bs-toggle="dropdown">Criança</button>
                <ul class="dropdown-menu">
                    <li><a class="dropdown-item" href="crianca-t-shirt.html">T-Shirt</a></li>
                    <li><a class="dropdown-item" href="crianca-camisola.html">Camisola</a></li>
                </ul>
            </div>
            <div class="btn-group">
                <button type="button" class="btn btn-primary dropdown-toggle" data-bs-toggle="dropdown">Homem</button>
                <ul class="dropdown-menu">
                    <li><a class="dropdown-item" href="homem-t-shirt.html">T-Shirt</a></li>
                    <li><a class="dropdown-item" href="homem-camisola.html">Camisola</a></li>
                    <li><a class="dropdown-item" href="homem-calcoes.html">Calções</a></li>
                    <li><a class="dropdown-item" href="homem-casaco.html">Casaco</a></li>
                </ul>
            </div>
            <div class="btn-group">
                <button type="button" class="btn btn-primary dropdown-toggle" data-bs-toggle="dropdown">Mulher</button>
                <ul class="dropdown-menu">
                    <li><a class="dropdown-item" href="mulher-t-shirt.html">T-Shirt</a></li>
                    <li><a class="dropdown-item" href="mulher-camisola.html">Camisola</a></li>
                    <li><a class="dropdown-item" href="mulher-calcas.html">Calças</a></li>
                </ul>
            </div>
        </div>
    </div>
    <div class="mainDiv">
        <hr style="width: 100%; border: 5px solid rgb(255, 255, 255); border-radius: 5px;">
        <h1>Entre em contacto connosco:</h1>
        <h6>Email:</h6>
        <input type="text">
        <input type="submit" value="Prosseguir">
        <p><br>Entre em contacto<br>
            Visite-nos<br>
            Rua do Ouro 797, 4150-555 Porto<br>
            
            Ligue-nos<br>
            226 106 312<br>
            
            E-mail <br>
            anan91547@gmail.com<br>
        </p>
        <hr style="width: 100%; border: 5px solid rgb(255, 255, 255); border-radius: 5px;">
    </div>
</body>
<!DOCTYPE html>

<head>
    <title>Moda Universal</title>

    <meta charset="UTF-8">

    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-T3c6CoIi6uLrA9TneNEoa7RxnatzjcDSCmG1MXxSR1GAsXEV/Dwwykc2MPK8M2HN" crossorigin="anonymous">
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-C6RzsynM9kWDrMNeT87bh95OGNyZPhcTNXj1NW7RuBCsyN/o0jlpcV8Qyq46cDfL" crossorigin="anonymous"></script>

    <link rel="stylesheet" href="styles.css">

    <script src="loja.js" async></script>
    
    <style>
        body{
            background-image: url("https://images.alphacoders.com/112/112121.jpg");
            background-size: cover;
        }
    </style>

    <script>
        function changeImage(name, source) {
            document.getElementById(name).src=source;
        }
    </script>
</head>
<body>
    <img src="imagens/logo.png" width="5%" height="auto" style="padding-left: 50px; padding-top: 20px; position: absolute">
    <div class="container">
        <div class="btn-group" style="padding-top: 20px;">
            <button class="btn btn-primary" style="width: 100px;"></button>
            <a type="button" class="btn btn-primary" href="index.html">Pagina Principal</a>
            <a type="button" class="btn btn-primary" href="novidades.html">Novidades</button>
            <a type="button" class="btn btn-primary" href="contacto.html">Contactos</button>
            <a type="button" class="btn btn-primary" href="termos.html">Termos e Condições</button>
            <a type="button" class="btn btn-primary" href="outros.html">Outros</a>
            <div class="btn-group">
                <button type="button" class="btn btn-primary dropdown-toggle" data-bs-toggle="dropdown">Criança</button>
                <ul class="dropdown-menu">
                    <li><a class="dropdown-item" href="crianca-t-shirt.html">T-Shirt</a></li>
                    <li><a class="dropdown-item" href="crianca-camisola.html">Camisola</a></li>
                </ul>
            </div>
            <div class="btn-group">
                <button type="button" class="btn btn-primary dropdown-toggle" data-bs-toggle="dropdown">Homem</button>
                <ul class="dropdown-menu">
                    <li><a class="dropdown-item" href="homem-t-shirt.html">T-Shirt</a></li>
                    <li><a class="dropdown-item" href="homem-camisola.html">Camisola</a></li>
                    <li><a class="dropdown-item" href="homem-calcoes.html">Calções</a></li>
                    <li><a class="dropdown-item" href="homem-casaco.html">Casaco</a></li>
                </ul>
            </div>
            <div class="btn-group">
                <button type="button" class="btn btn-primary dropdown-toggle" data-bs-toggle="dropdown">Mulher</button>
                <ul class="dropdown-menu">
                    <li><a class="dropdown-item" href="mulher-t-shirt.html">T-Shirt</a></li>
                    <li><a class="dropdown-item" href="mulher-camisola.html">Camisola</a></li>
                    <li><a class="dropdown-item" href="mulher-calcas.html">Calças</a></li>
                </ul>
            </div>
        </div>
    </div> 
    <div class="mainDiv">
        <h1>Crianca</h1>

        <hr style="width: 100%; border: 5px solid rgb(255, 255, 255); border-radius: 5px;">

        <div class="imageDiv">
            <br>
            <h2 class="product-title title">Camisola Respect</h2>
            <br><br><br>
            <img class="image product-image" src="imagens/57.png" id="2"/>
            <h2 class="text product-price">59.99€</h2>
            <h6 class="text2">Apresentamos nossas Camisolas 'Respect' para crianças, inspiradas na mensagem de respeito e no espírito ousado da cultura urbana.<br>Com a palavra 'respect' estampada, essa peça incentiva valores importantes.<br>Tamanho: S | M | L</h6>
            <img class="imgSelect" src="imagens/57.png" width="70px" onclick="changeImage(2, 'imagens/57.png')"/>
            <img class="imgSelect" src="imagens/58.png" width="70px" onclick="changeImage(2, 'imagens/58.png')"/>
            <img class="imgSelect" src="imagens/59.png" width="70px" onclick="changeImage(2, 'imagens/59.png')"/>
            <img class="imgSelect" src="imagens/60.png" width="70px" onclick="changeImage(2, 'imagens/60.png')"/>

            <img class="imgSelect" src="imagens/61.png" width="70px" onclick="changeImage(2, 'imagens/61.png')"/>
            <img class="imgSelect" src="imagens/62.png" width="70px" onclick="changeImage(2, 'imagens/62.png')"/>
            <img class="imgSelect" src="imagens/63.png" width="70px" onclick="changeImage(2, 'imagens/63.png')"/>
            <img class="imgSelect" src="imagens/64.png" width="70px" onclick="changeImage(2, 'imagens/64.png')"/>
            <div class="product-price-container">
                <button type="button" class="button-hover-background">Adicionar ao carrinho</button>
            </div>
        </div>

        <div class="imageDiv">
            <br>
            <h2 class="product-title title">Camisola Volkswagen</h2>
            <br><br><br>
            <img class="image product-image" src="imagens/101.png" id="3"/>
            <h2 class="text product-price">39.99€</h2>
            <h6 class="text2">Prepare seu pequeno entusiasta para uma aventura na moda com a nossa Sweet Volkswagen Kids.<br>Feita para os futuros amantes da marca Volkswagen, esta doce peça é tão divertida quanto os próprios carros.Com design inspirado na icônica marca, seu filho irá desfrutar de conforto e estilo onde quer que vá.<br>Tamanho: S | M | L</h6>
            <img class="imgSelect" src="imagens/101.png" width="70px" onclick="changeImage(3, 'imagens/101.png')"/>
            <img class="imgSelect" src="imagens/102.png" width="70px" onclick="changeImage(3, 'imagens/102.png')"/>
            <img class="imgSelect" src="imagens/103.png" width="70px" onclick="changeImage(3, 'imagens/103.png')"/>
            <img class="imgSelect" src="imagens/104.png" width="70px" onclick="changeImage(3, 'imagens/104.png')"/>
            <div class="product-price-container">
                <button type="button" class="button-hover-background">Adicionar ao carrinho</button>
            </div>
        </div>
       <section class="container normal-section">
        <h2 class="section-title">Carrinho</h2>

        <table class="cart-table">
            <thead>
            <tr>
                <th class="table-head-item first-col">Item</th>
                <th class="table-head-item second-col">Preço</th>
                <th class="table-head-item third-col">Quantidade</th>
            </tr>
            </thead>

            <tbody>

            </tbody>

            <tfoot>
            <tr>
                <td colspan="3" class="cart-total-container">
                <strong>Total</strong>
                <span>0,00€</span>
                </td>
            </tr>
            </tfoot>
        </table>

        <button type="button" class="purchase-button">Finalizar Compra</button>
    </section>
    </div>
</body>
<!DOCTYPE html>

<head>
    <title>Moda Universal</title>

    <meta charset="UTF-8">

    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-T3c6CoIi6uLrA9TneNEoa7RxnatzjcDSCmG1MXxSR1GAsXEV/Dwwykc2MPK8M2HN" crossorigin="anonymous">
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-C6RzsynM9kWDrMNeT87bh95OGNyZPhcTNXj1NW7RuBCsyN/o0jlpcV8Qyq46cDfL" crossorigin="anonymous"></script>

    <link rel="stylesheet" href="styles.css">

    <script src="loja.js" async></script>
    
    <style>
        body{
            background-image: url("https://images.alphacoders.com/112/112121.jpg");
            background-size: cover;
        }
    </style>

    <script>
        function changeImage(name, source) {
            document.getElementById(name).src=source;
        }
    </script>
</head>
<body>
    <img src="imagens/logo.png" width="5%" height="auto" style="padding-left: 50px; padding-top: 20px; position: absolute">
    <div class="container">
        <div class="btn-group" style="padding-top: 20px;">
            <button class="btn btn-primary" style="width: 100px;"></button>
            <a type="button" class="btn btn-primary" href="index.html">Pagina Principal</a>
            <a type="button" class="btn btn-primary" href="novidades.html">Novidades</button>
            <a type="button" class="btn btn-primary" href="contacto.html">Contactos</button>
            <a type="button" class="btn btn-primary" href="termos.html">Termos e Condições</button>
            <a type="button" class="btn btn-primary" href="outros.html">Outros</a>
            <div class="btn-group">
                <button type="button" class="btn btn-primary dropdown-toggle" data-bs-toggle="dropdown">Criança</button>
                <ul class="dropdown-menu">
                    <li><a class="dropdown-item" href="crianca-t-shirt.html">T-Shirt</a></li>
                    <li><a class="dropdown-item" href="crianca-camisola.html">Camisola</a></li>
                </ul>
            </div>
            <div class="btn-group">
                <button type="button" class="btn btn-primary dropdown-toggle" data-bs-toggle="dropdown">Homem</button>
                <ul class="dropdown-menu">
                    <li><a class="dropdown-item" href="homem-t-shirt.html">T-Shirt</a></li>
                    <li><a class="dropdown-item" href="homem-camisola.html">Camisola</a></li>
                    <li><a class="dropdown-item" href="homem-calcoes.html">Calções</a></li>
                    <li><a class="dropdown-item" href="homem-casaco.html">Casaco</a></li>
                </ul>
            </div>
            <div class="btn-group">
                <button type="button" class="btn btn-primary dropdown-toggle" data-bs-toggle="dropdown">Mulher</button>
                <ul class="dropdown-menu">
                    <li><a class="dropdown-item" href="mulher-t-shirt.html">T-Shirt</a></li>
                    <li><a class="dropdown-item" href="mulher-camisola.html">Camisola</a></li>
                    <li><a class="dropdown-item" href="mulher-calcas.html">Calças</a></li>
                </ul>
            </div>
        </div>
    </div> 
    <div class="mainDiv">
        <h1>Crianca</h1>

        <hr style="width: 100%; border: 5px solid rgb(255, 255, 255); border-radius: 5px;">

        <div class="imageDiv">
            <br>
            <h2 class="product-title title">T-Shirt Cruz</h2>
            <br><br><br>
            <img class="image product-image" src="imagens/5.png" id="1"/>
            <h2 class="text product-price">49.99€</h2>
            <h6 class="text2">Uma camisola de algodão leve e confortável, adornada com uma cruz e uma pomba branca, é uma representação de simplicidade e espiritualidade.<br> O algodão macio proporciona conforto durante todo o dia, enquanto a cruz e a pomba adicionam um toque de significado e paz ao design, tornando-a uma escolha ideal para quem procura estilo e simbolismo em sua roupa.<br>Tamanho: S | M | L</h6>
            <img class="imgSelect" src="imagens/5.png" width="70px" onclick="changeImage(1, 'imagens/5.png')"/>
            <img class="imgSelect" src="imagens/6.png" width="70px" onclick="changeImage(1, 'imagens/6.png')"/>
            <div class="product-price-container">
                <button type="button" class="button-hover-background">Adicionar ao carrinho</button>
            </div>
        </div>
       <section class="container normal-section">
        <h2 class="section-title">Carrinho</h2>

        <table class="cart-table">
            <thead>
            <tr>
                <th class="table-head-item first-col">Item</th>
                <th class="table-head-item second-col">Preço</th>
                <th class="table-head-item third-col">Quantidade</th>
            </tr>
            </thead>

            <tbody>

            </tbody>

            <tfoot>
            <tr>
                <td colspan="3" class="cart-total-container">
                <strong>Total</strong>
                <span>0,00€</span>
                </td>
            </tr>
            </tfoot>
        </table>

        <button type="button" class="purchase-button">Finalizar Compra</button>
    </section>
    </div>
</body>
<!DOCTYPE html>

<head>
    <title>Moda Universal</title>

    <meta charset="UTF-8">

    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-T3c6CoIi6uLrA9TneNEoa7RxnatzjcDSCmG1MXxSR1GAsXEV/Dwwykc2MPK8M2HN" crossorigin="anonymous">
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-C6RzsynM9kWDrMNeT87bh95OGNyZPhcTNXj1NW7RuBCsyN/o0jlpcV8Qyq46cDfL" crossorigin="anonymous"></script>

    <link rel="stylesheet" href="styles.css">

    <script src="loja.js" async></script>
    
    <style>
        body{
            background-image: url("https://images.alphacoders.com/112/112121.jpg");
            background-size: cover;
        }
    </style>

    <script>
        function changeImage(name, source) {
            document.getElementById(name).src=source;
        }
    </script>
</head>
<body>
    <img src="imagens/logo.png" width="5%" height="auto" style="padding-left: 50px; padding-top: 20px; position: absolute">
    <div class="container">
        <div class="btn-group" style="padding-top: 20px;">
            <button class="btn btn-primary" style="width: 100px;"></button>
            <a type="button" class="btn btn-primary" href="index.html">Pagina Principal</a>
            <a type="button" class="btn btn-primary" href="novidades.html">Novidades</button>
            <a type="button" class="btn btn-primary" href="contacto.html">Contactos</button>
            <a type="button" class="btn btn-primary" href="termos.html">Termos e Condições</button>
            <a type="button" class="btn btn-primary" href="outros.html">Outros</a>
            <div class="btn-group">
                <button type="button" class="btn btn-primary dropdown-toggle" data-bs-toggle="dropdown">Criança</button>
                <ul class="dropdown-menu">
                    <li><a class="dropdown-item" href="crianca-t-shirt.html">T-Shirt</a></li>
                    <li><a class="dropdown-item" href="crianca-camisola.html">Camisola</a></li>
                </ul>
            </div>
            <div class="btn-group">
                <button type="button" class="btn btn-primary dropdown-toggle" data-bs-toggle="dropdown">Homem</button>
                <ul class="dropdown-menu">
                    <li><a class="dropdown-item" href="homem-t-shirt.html">T-Shirt</a></li>
                    <li><a class="dropdown-item" href="homem-camisola.html">Camisola</a></li>
                    <li><a class="dropdown-item" href="homem-calcoes.html">Calções</a></li>
                    <li><a class="dropdown-item" href="homem-casaco.html">Casaco</a></li>
                </ul>
            </div>
            <div class="btn-group">
                <button type="button" class="btn btn-primary dropdown-toggle" data-bs-toggle="dropdown">Mulher</button>
                <ul class="dropdown-menu">
                    <li><a class="dropdown-item" href="mulher-t-shirt.html">T-Shirt</a></li>
                    <li><a class="dropdown-item" href="mulher-camisola.html">Camisola</a></li>
                    <li><a class="dropdown-item" href="mulher-calcas.html">Calças</a></li>
                </ul>
            </div>
        </div>
    </div> 
    <div class="mainDiv">
        <h1>Crianca</h1>

        <hr style="width: 100%; border: 5px solid rgb(255, 255, 255); border-radius: 5px;">

        <div class="imageDiv">
            <br>
            <h2 class="product-title title">T-Shirt Cruz</h2>
            <br><br><br>
            <img class="image product-image" src="imagens/5.png" id="1"/>
            <h2 class="text product-price">49.99€</h2>
            <h6 class="text2">Uma camisola de algodão leve e confortável, adornada com uma cruz e uma pomba branca, é uma representação de simplicidade e espiritualidade.<br> O algodão macio proporciona conforto durante todo o dia, enquanto a cruz e a pomba adicionam um toque de significado e paz ao design, tornando-a uma escolha ideal para quem procura estilo e simbolismo em sua roupa.<br>Tamanho: S | M | L</h6>
            <img class="imgSelect" src="imagens/5.png" width="70px" onclick="changeImage(1, 'imagens/5.png')"/>
            <img class="imgSelect" src="imagens/6.png" width="70px" onclick="changeImage(1, 'imagens/6.png')"/>
            <div class="product-price-container">
                <button type="button" class="button-hover-background">Adicionar ao carrinho</button>
            </div>
        </div>
       <section class="container normal-section">
        <h2 class="section-title">Carrinho</h2>

        <table class="cart-table">
            <thead>
            <tr>
                <th class="table-head-item first-col">Item</th>
                <th class="table-head-item second-col">Preço</th>
                <th class="table-head-item third-col">Quantidade</th>
            </tr>
            </thead>

            <tbody>

            </tbody>

            <tfoot>
            <tr>
                <td colspan="3" class="cart-total-container">
                <strong>Total</strong>
                <span>0,00€</span>
                </td>
            </tr>
            </tfoot>
        </table>

        <button type="button" class="purchase-button">Finalizar Compra</button>
    </section>
    </div>
</body>
<!DOCTYPE html>

<head>
    <title>Moda Universal</title>

    <meta charset="UTF-8">

    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-T3c6CoIi6uLrA9TneNEoa7RxnatzjcDSCmG1MXxSR1GAsXEV/Dwwykc2MPK8M2HN" crossorigin="anonymous">
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-C6RzsynM9kWDrMNeT87bh95OGNyZPhcTNXj1NW7RuBCsyN/o0jlpcV8Qyq46cDfL" crossorigin="anonymous"></script>

    <link rel="stylesheet" href="styles.css">

    <script src="loja.js" async></script>

    <style>
        body{
            background-image: url("https://images.alphacoders.com/112/112121.jpg");
            background-size: cover;
        }
    </style>

    <script>
        function changeImage(name, source) {
            document.getElementById(name).src=source;
        }
    </script>
</head>
<body>
    <img src="imagens/logo.png" width="5%" height="auto" style="padding-left: 50px; padding-top: 20px; position: absolute">
    <div class="container">
        <div class="btn-group" style="padding-top: 20px;">
            <button class="btn btn-primary" style="width: 100px;"></button>
            <a type="button" class="btn btn-primary" href="index.html">Pagina Principal</a>
            <a type="button" class="btn btn-primary" href="novidades.html">Novidades</button>
            <a type="button" class="btn btn-primary" href="contacto.html">Contactos</button>
            <a type="button" class="btn btn-primary" href="termos.html">Termos e Condições</button>
            <a type="button" class="btn btn-primary" href="outros.html">Outros</a>
            <div class="btn-group">
                <button type="button" class="btn btn-primary dropdown-toggle" data-bs-toggle="dropdown">Criança</button>
                <ul class="dropdown-menu">
                    <li><a class="dropdown-item" href="crianca-t-shirt.html">T-Shirt</a></li>
                    <li><a class="dropdown-item" href="crianca-camisola.html">Camisola</a></li>
                </ul>
            </div>
            <div class="btn-group">
                <button type="button" class="btn btn-primary dropdown-toggle" data-bs-toggle="dropdown">Homem</button>
                <ul class="dropdown-menu">
                    <li><a class="dropdown-item" href="homem-t-shirt.html">T-Shirt</a></li>
                    <li><a class="dropdown-item" href="homem-camisola.html">Camisola</a></li>
                    <li><a class="dropdown-item" href="homem-calcoes.html">Calções</a></li>
                    <li><a class="dropdown-item" href="homem-casaco.html">Casaco</a></li>
                </ul>
            </div>
            <div class="btn-group">
                <button type="button" class="btn btn-primary dropdown-toggle" data-bs-toggle="dropdown">Mulher</button>
                <ul class="dropdown-menu">
                    <li><a class="dropdown-item" href="mulher-t-shirt.html">T-Shirt</a></li>
                    <li><a class="dropdown-item" href="mulher-camisola.html">Camisola</a></li>
                    <li><a class="dropdown-item" href="mulher-calcas.html">Calças</a></li>
                </ul>
            </div>
        </div>
    </div>  
    <div class="mainDiv">
        <h1>Homem</h1>

        <hr style="width: 100%; border: 5px solid rgb(255, 255, 255); border-radius: 5px;">
        <div class="imageDiv">
            <br>
            <h2 class="product-title title">Calções Volkswagen</h2>
            <br><br><br>
            <img class="image product-image" src="imagens/10.png" id="2"/>
            <h2 class="text product-price">79.99€</h2>
            <h6 class="text2">Explore o equilíbrio perfeito entre estilo e desempenho com nossos Calções Inspirados pela Volkswagen.<br>Inspirados na estrutura leve e eficiente dos carros Volkswagen, esses calções são a escolha ideal para os entusiastas automobilísticos.<br>Desfrute do conforto e da mobilidade proporcionados por sua engenharia inspirada, enquanto exibe seu amor pela marca Volkswagen.<br>Tamanho: S | M | L</h6>
            <img class="imgSelect" src="imagens/10.png" width="70px" onclick="changeImage(2, 'imagens/10.png')"/>
            <img class="imgSelect" src="imagens/11.png" width="70px" onclick="changeImage(2, 'imagens/11.png')"/>
            <img class="imgSelect" src="imagens/12.png" width="70px" onclick="changeImage(2, 'imagens/12.png')"/>
            <img class="imgSelect" src="imagens/14.png" width="70px" onclick="changeImage(2, 'imagens/14.png')"/>
            <img class="imgSelect" src="imagens/15.png" width="70px" onclick="changeImage(2, 'imagens/15.png')"/>
            <img class="imgSelect" src="imagens/16.png" width="70px" onclick="changeImage(2, 'imagens/16.png')"/>
            <div class="product-price-container">
                <button type="button" class="button-hover-background">Adicionar ao carrinho</button>
            </div>
        </div>
        <section class="container normal-section">
            <h2 class="section-title">Carrinho</h2>

            <table class="cart-table">
                <thead>
                <tr>
                    <th class="table-head-item first-col">Item</th>
                    <th class="table-head-item second-col">Preço</th>
                    <th class="table-head-item third-col">Quantidade</th>
                </tr>
                </thead>

                <tbody>

                </tbody>

                <tfoot>
                <tr>
                    <td colspan="3" class="cart-total-container">
                    <strong>Total</strong>
                    <span>0,00€</span>
                    </td>
                </tr>
                </tfoot>
            </table>

            <button type="button" class="purchase-button">Finalizar Compra</button>
        </section>
    </div>
</body>
<!DOCTYPE html>

<head>
    <title>Moda Universal</title>

    <meta charset="UTF-8">

    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-T3c6CoIi6uLrA9TneNEoa7RxnatzjcDSCmG1MXxSR1GAsXEV/Dwwykc2MPK8M2HN" crossorigin="anonymous">
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-C6RzsynM9kWDrMNeT87bh95OGNyZPhcTNXj1NW7RuBCsyN/o0jlpcV8Qyq46cDfL" crossorigin="anonymous"></script>

    <link rel="stylesheet" href="styles.css">

    <script src="loja.js" async></script>

    <style>
        body{
            background-image: url("https://images.alphacoders.com/112/112121.jpg");
            background-size: cover;
        }
    </style>

    <script>
        function changeImage(name, source) {
            document.getElementById(name).src=source;
        }
    </script>
</head>
<body>
    <img src="imagens/logo.png" width="5%" height="auto" style="padding-left: 50px; padding-top: 20px; position: absolute">
    <div class="container">
        <div class="btn-group" style="padding-top: 20px;">
            <button class="btn btn-primary" style="width: 100px;"></button>
            <a type="button" class="btn btn-primary" href="index.html">Pagina Principal</a>
            <a type="button" class="btn btn-primary" href="novidades.html">Novidades</button>
            <a type="button" class="btn btn-primary" href="contacto.html">Contactos</button>
            <a type="button" class="btn btn-primary" href="termos.html">Termos e Condições</button>
            <a type="button" class="btn btn-primary" href="outros.html">Outros</a>
            <div class="btn-group">
                <button type="button" class="btn btn-primary dropdown-toggle" data-bs-toggle="dropdown">Criança</button>
                <ul class="dropdown-menu">
                    <li><a class="dropdown-item" href="crianca-t-shirt.html">T-Shirt</a></li>
                    <li><a class="dropdown-item" href="crianca-camisola.html">Camisola</a></li>
                </ul>
            </div>
            <div class="btn-group">
                <button type="button" class="btn btn-primary dropdown-toggle" data-bs-toggle="dropdown">Homem</button>
                <ul class="dropdown-menu">
                    <li><a class="dropdown-item" href="homem-t-shirt.html">T-Shirt</a></li>
                    <li><a class="dropdown-item" href="homem-camisola.html">Camisola</a></li>
                    <li><a class="dropdown-item" href="homem-calcoes.html">Calções</a></li>
                    <li><a class="dropdown-item" href="homem-casaco.html">Casaco</a></li>
                </ul>
            </div>
            <div class="btn-group">
                <button type="button" class="btn btn-primary dropdown-toggle" data-bs-toggle="dropdown">Mulher</button>
                <ul class="dropdown-menu">
                    <li><a class="dropdown-item" href="mulher-t-shirt.html">T-Shirt</a></li>
                    <li><a class="dropdown-item" href="mulher-camisola.html">Camisola</a></li>
                    <li><a class="dropdown-item" href="mulher-calcas.html">Calças</a></li>
                </ul>
            </div>
        </div>
    </div>  
    <div class="mainDiv">
        <h1>Homem</h1>

        <hr style="width: 100%; border: 5px solid rgb(255, 255, 255); border-radius: 5px;">

        <div class="imageDiv">
            <br>
            <h2 class="product-title title">Camisola Supra</h2>
            <br><br><br>
            <img class="image product-image" src="imagens/27.png" id="4"/>
            <h2 class="text product-price">54.99€</h2>
            <h6 class="text2">Para os verdadeiros entusiastas do Supra, apresentamos a nossa Sweet Supra com pelo por dentro.<br>Inspirada nas linhas elegantes e cores variáveis desse ícone automobilístico, esta peça de vestuário oferece não apenas estilo, mas também conforto supremo.<br>Com seu interior macio e quente, você poderá enfrentar os dias mais frios com o espírito do Supra.<br>Tamanho: S | M | L</h6>
            <img class="imgSelect" src="imagens/27.png" width="70px" onclick="changeImage(4, 'imagens/27.png')"/>
            <img class="imgSelect" src="imagens/37.png" width="70px" onclick="changeImage(4, 'imagens/37.png')"/>
            <img class="imgSelect" src="imagens/28.png" width="70px" onclick="changeImage(4, 'imagens/28.png')"/>
            <img class="imgSelect" src="imagens/29.png" width="70px" onclick="changeImage(4, 'imagens/29.png')"/>
            <img class="imgSelect" src="imagens/30.png" width="70px" onclick="changeImage(4, 'imagens/30.png')"/>
            <img class="imgSelect" src="imagens/31.png" width="70px" onclick="changeImage(4, 'imagens/31.png')"/>
            <img class="imgSelect" src="imagens/32.png" width="70px" onclick="changeImage(4, 'imagens/32.png')"/>
            <img class="imgSelect" src="imagens/33.png" width="70px" onclick="changeImage(4, 'imagens/33.png')"/>
            <img class="imgSelect" src="imagens/34.png" width="70px" onclick="changeImage(4, 'imagens/34.png')"/>
            <img class="imgSelect" src="imagens/40.png" width="70px" onclick="changeImage(4, 'imagens/40.png')"/>
            <img class="imgSelect" src="imagens/35.png" width="70px" onclick="changeImage(4, 'imagens/35.png')"/>
            <img class="imgSelect" src="imagens/36.png" width="70px" onclick="changeImage(4, 'imagens/36.png')"/>
            <img class="imgSelect" src="imagens/38.png" width="70px" onclick="changeImage(4, 'imagens/38.png')"/>
            <img class="imgSelect" src="imagens/39.png" width="70px" onclick="changeImage(4, 'imagens/39.png')"/>
            <div class="product-price-container">
                <button type="button" class="button-hover-background">Adicionar ao carrinho</button>
            </div>
        </div>

        <div class="imageDiv">
            <br>
            <h2 class="product-title title">Camisola Wasted</h2>
            <br><br><br>
            <img class="image product-image" src="imagens/41.png" id="5"/>
            <h2 class="text product-price">77.99€</h2>
            <h6 class="text2">Apresentamos nossa Camisola 'Wasted' - uma fusão de estilo urbano e paixão automobilística.<br>Com a palavra 'wasted' estampada na frente, esta camisola expressa uma atitude ousada e descontraída.<br>Na parte de trás, você encontrará três lendários carros - o Supra, o R34 e o RX7 - em todo o seu esplendor.<br>Tamanho: S | M | L</h6>
            <img class="imgSelect" src="imagens/41.png" width="70px" onclick="changeImage(5, 'imagens/41.png')"/>
            <img class="imgSelect" src="imagens/49.png" width="70px" onclick="changeImage(5, 'imagens/49.png')"/>
            <img class="imgSelect" src="imagens/44.png" width="70px" onclick="changeImage(5, 'imagens/44.png')"/>
            <img class="imgSelect" src="imagens/52.png" width="70px" onclick="changeImage(5, 'imagens/52.png')"/>
            <img class="imgSelect" src="imagens/46.png" width="70px" onclick="changeImage(5, 'imagens/46.png')"/>
            <img class="imgSelect" src="imagens/54.png" width="70px" onclick="changeImage(5, 'imagens/54.png')"/>
            <img class="imgSelect" src="imagens/47.png" width="70px" onclick="changeImage(5, 'imagens/47.png')"/>
            <img class="imgSelect" src="imagens/55.png" width="70px" onclick="changeImage(5, 'imagens/55.png')"/>
            <img class="imgSelect" src="imagens/50.png" width="70px" onclick="changeImage(5, 'imagens/50.png')"/>
            <img class="imgSelect" src="imagens/42.png" width="70px" onclick="changeImage(5, 'imagens/42.png')"/>
            <img class="imgSelect" src="imagens/53.png" width="70px" onclick="changeImage(5, 'imagens/53.png')"/>
            <img class="imgSelect" src="imagens/45.png" width="70px" onclick="changeImage(5, 'imagens/45.png')"/>
            <img class="imgSelect" src="imagens/56.png" width="70px" onclick="changeImage(5, 'imagens/56.png')"/>
            <img class="imgSelect" src="imagens/48.png" width="70px" onclick="changeImage(5, 'imagens/48.png')"/> 
            <div class="product-price-container">
                <button type="button" class="button-hover-background">Adicionar ao carrinho</button>
            </div>
        </div>
        <section class="container normal-section">
            <h2 class="section-title">Carrinho</h2>

            <table class="cart-table">
                <thead>
                <tr>
                    <th class="table-head-item first-col">Item</th>
                    <th class="table-head-item second-col">Preço</th>
                    <th class="table-head-item third-col">Quantidade</th>
                </tr>
                </thead>

                <tbody>

                </tbody>

                <tfoot>
                <tr>
                    <td colspan="3" class="cart-total-container">
                    <strong>Total</strong>
                    <span>0,00€</span>
                    </td>
                </tr>
                </tfoot>
            </table>

            <button type="button" class="purchase-button">Finalizar Compra</button>
        </section>
    </div>
</body>
<!DOCTYPE html>

<head>
    <title>Moda Universal</title>

    <meta charset="UTF-8">

    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-T3c6CoIi6uLrA9TneNEoa7RxnatzjcDSCmG1MXxSR1GAsXEV/Dwwykc2MPK8M2HN" crossorigin="anonymous">
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-C6RzsynM9kWDrMNeT87bh95OGNyZPhcTNXj1NW7RuBCsyN/o0jlpcV8Qyq46cDfL" crossorigin="anonymous"></script>

    <link rel="stylesheet" href="styles.css">

    <script src="loja.js" async></script>

    <style>
        body{
            background-image: url("https://images.alphacoders.com/112/112121.jpg");
            background-size: cover;
        }
    </style>

    <script>
        function changeImage(name, source) {
            document.getElementById(name).src=source;
        }
    </script>
</head>
<body>
    <img src="imagens/logo.png" width="5%" height="auto" style="padding-left: 50px; padding-top: 20px; position: absolute">
    <div class="container">
        <div class="btn-group" style="padding-top: 20px;">
            <button class="btn btn-primary" style="width: 100px;"></button>
            <a type="button" class="btn btn-primary" href="index.html">Pagina Principal</a>
            <a type="button" class="btn btn-primary" href="novidades.html">Novidades</button>
            <a type="button" class="btn btn-primary" href="contacto.html">Contactos</button>
            <a type="button" class="btn btn-primary" href="termos.html">Termos e Condições</button>
            <a type="button" class="btn btn-primary" href="outros.html">Outros</a>
            <div class="btn-group">
                <button type="button" class="btn btn-primary dropdown-toggle" data-bs-toggle="dropdown">Criança</button>
                <ul class="dropdown-menu">
                    <li><a class="dropdown-item" href="crianca-t-shirt.html">T-Shirt</a></li>
                    <li><a class="dropdown-item" href="crianca-camisola.html">Camisola</a></li>
                </ul>
            </div>
            <div class="btn-group">
                <button type="button" class="btn btn-primary dropdown-toggle" data-bs-toggle="dropdown">Homem</button>
                <ul class="dropdown-menu">
                    <li><a class="dropdown-item" href="homem-t-shirt.html">T-Shirt</a></li>
                    <li><a class="dropdown-item" href="homem-camisola.html">Camisola</a></li>
                    <li><a class="dropdown-item" href="homem-calcoes.html">Calções</a></li>
                    <li><a class="dropdown-item" href="homem-casaco.html">Casaco</a></li>
                </ul>
            </div>
            <div class="btn-group">
                <button type="button" class="btn btn-primary dropdown-toggle" data-bs-toggle="dropdown">Mulher</button>
                <ul class="dropdown-menu">
                    <li><a class="dropdown-item" href="mulher-t-shirt.html">T-Shirt</a></li>
                    <li><a class="dropdown-item" href="mulher-camisola.html">Camisola</a></li>
                    <li><a class="dropdown-item" href="mulher-calcas.html">Calças</a></li>
                </ul>
            </div>
        </div>
    </div>  
    <div class="mainDiv">
        <h1>Homem</h1>

        <hr style="width: 100%; border: 5px solid rgb(255, 255, 255); border-radius: 5px;">
        <div class="imageDiv">
            <br>
            <h2 class="product-title title">Casaco Volkswagen</h2>
            <br><br><br>
            <img class="image product-image" src="imagens/17.png"id="3"/>
            <h2 class="text product-price">59.99€</h2>
            <h6 class="text2">Introduzindo o Casaco de Algodão Leve Volkswagen, a fusão perfeita entre moda e paixão automobilística.<br>Este casaco é inspirado na elegância e funcionalidade dos carros Volkswagen, oferecendo um estilo versátil e uma sensação incrivelmente leve.<br>Com ele, você pode desfrutar de conforto durante todo o ano e expressar seu amor pela marca Volkswagen de forma sutil e sofisticada.<br>Tamanho: S | M | L</h6>
            <img class="imgSelect" src="imagens/17.png" width="70px" onclick="changeImage(3, 'imagens/17.png')"/>
            <img class="imgSelect" src="imagens/18.png" width="70px" onclick="changeImage(3, 'imagens/18.png')"/>
            <img class="imgSelect" src="imagens/19.png" width="70px" onclick="changeImage(3, 'imagens/19.png')"/>
            <img class="imgSelect" src="imagens/20.png" width="70px" onclick="changeImage(3, 'imagens/20.png')"/>
            <img class="imgSelect" src="imagens/21.png" width="70px" onclick="changeImage(3, 'imagens/21.png')"/>
            <div class="product-price-container">
                <button type="button" class="button-hover-background">Adicionar ao carrinho</button>
            </div>
        </div>
        <section class="container normal-section">
            <h2 class="section-title">Carrinho</h2>

            <table class="cart-table">
                <thead>
                <tr>
                    <th class="table-head-item first-col">Item</th>
                    <th class="table-head-item second-col">Preço</th>
                    <th class="table-head-item third-col">Quantidade</th>
                </tr>
                </thead>

                <tbody>

                </tbody>

                <tfoot>
                <tr>
                    <td colspan="3" class="cart-total-container">
                    <strong>Total</strong>
                    <span>0,00€</span>
                    </td>
                </tr>
                </tfoot>
            </table>

            <button type="button" class="purchase-button">Finalizar Compra</button>
        </section>
    </div>
</body>
<!DOCTYPE html>

<head>
    <title>Moda Universal</title>

    <meta charset="UTF-8">

    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-T3c6CoIi6uLrA9TneNEoa7RxnatzjcDSCmG1MXxSR1GAsXEV/Dwwykc2MPK8M2HN" crossorigin="anonymous">
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-C6RzsynM9kWDrMNeT87bh95OGNyZPhcTNXj1NW7RuBCsyN/o0jlpcV8Qyq46cDfL" crossorigin="anonymous"></script>

    <link rel="stylesheet" href="styles.css">

    <script src="loja.js" async></script>

    <style>
        body{
            background-image: url("https://images.alphacoders.com/112/112121.jpg");
            background-size: cover;
        }
    </style>

    <script>
        function changeImage(name, source) {
            document.getElementById(name).src=source;
        }
    </script>
</head>
<body>
    <img src="imagens/logo.png" width="5%" height="auto" style="padding-left: 50px; padding-top: 20px; position: absolute">
    <div class="container">
        <div class="btn-group" style="padding-top: 20px;">
            <button class="btn btn-primary" style="width: 100px;"></button>
            <a type="button" class="btn btn-primary" href="index.html">Pagina Principal</a>
            <a type="button" class="btn btn-primary" href="novidades.html">Novidades</button>
            <a type="button" class="btn btn-primary" href="contacto.html">Contactos</button>
            <a type="button" class="btn btn-primary" href="termos.html">Termos e Condições</button>
            <a type="button" class="btn btn-primary" href="outros.html">Outros</a>
            <div class="btn-group">
                <button type="button" class="btn btn-primary dropdown-toggle" data-bs-toggle="dropdown">Criança</button>
                <ul class="dropdown-menu">
                    <li><a class="dropdown-item" href="crianca-t-shirt.html">T-Shirt</a></li>
                    <li><a class="dropdown-item" href="crianca-camisola.html">Camisola</a></li>
                </ul>
            </div>
            <div class="btn-group">
                <button type="button" class="btn btn-primary dropdown-toggle" data-bs-toggle="dropdown">Homem</button>
                <ul class="dropdown-menu">
                    <li><a class="dropdown-item" href="homem-t-shirt.html">T-Shirt</a></li>
                    <li><a class="dropdown-item" href="homem-camisola.html">Camisola</a></li>
                    <li><a class="dropdown-item" href="homem-calcoes.html">Calções</a></li>
                    <li><a class="dropdown-item" href="homem-casaco.html">Casaco</a></li>
                </ul>
            </div>
            <div class="btn-group">
                <button type="button" class="btn btn-primary dropdown-toggle" data-bs-toggle="dropdown">Mulher</button>
                <ul class="dropdown-menu">
                    <li><a class="dropdown-item" href="mulher-t-shirt.html">T-Shirt</a></li>
                    <li><a class="dropdown-item" href="mulher-camisola.html">Camisola</a></li>
                    <li><a class="dropdown-item" href="mulher-calcas.html">Calças</a></li>
                </ul>
            </div>
        </div>
    </div>  
    <div class="mainDiv">
        <h1>Homem</h1>

        <hr style="width: 100%; border: 5px solid rgb(255, 255, 255); border-radius: 5px;">

        <div class="imageDiv">
            <br>
            <h2 class="product-title title">T-Shirt Cruz</h2>
            <br><br><br>
            <img class="image product-image" src="imagens/7.png" id="1"/>
            <h2 class="text product-price">99.99€</h2>
            <h6 class="text2">Uma camisola de algodão leve e confortável, adornada com uma cruz e uma pomba branca, é uma representação de simplicidade e espiritualidade.<br> O algodão macio proporciona conforto durante todo o dia, enquanto a cruz e a pomba adicionam um toque de significado e paz ao design, tornando-a uma escolha ideal para quem procura estilo e simbolismo em sua roupa.<br>Tamanho: S | M | L</h6>
            <img class="imgSelect" src="imagens/7.png" width="70px" onclick="changeImage(1, 'imagens/7.png')"/>
            <img class="imgSelect" src="imagens/8.png" width="70px" onclick="changeImage(1, 'imagens/8.png')"/>
            <div class="product-price-container">
                <button type="button" class="button-hover-background">Adicionar ao carrinho</button>
            </div>
        </div>
        <section class="container normal-section">
            <h2 class="section-title">Carrinho</h2>

            <table class="cart-table">
                <thead>
                <tr>
                    <th class="table-head-item first-col">Item</th>
                    <th class="table-head-item second-col">Preço</th>
                    <th class="table-head-item third-col">Quantidade</th>
                </tr>
                </thead>

                <tbody>

                </tbody>

                <tfoot>
                <tr>
                    <td colspan="3" class="cart-total-container">
                    <strong>Total</strong>
                    <span>0,00€</span>
                    </td>
                </tr>
                </tfoot>
            </table>

            <button type="button" class="purchase-button">Finalizar Compra</button>
        </section>
    </div>
</body>
<!DOCTYPE html>

<head>
    <title>Moda Universal</title>

    <meta charset="UTF-8">

    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-T3c6CoIi6uLrA9TneNEoa7RxnatzjcDSCmG1MXxSR1GAsXEV/Dwwykc2MPK8M2HN" crossorigin="anonymous">
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-C6RzsynM9kWDrMNeT87bh95OGNyZPhcTNXj1NW7RuBCsyN/o0jlpcV8Qyq46cDfL" crossorigin="anonymous"></script>

    <link rel="stylesheet" href="styles.css">

    <script src="loja.js" async></script>

    <style>
        body{
            background-image: url("https://images.alphacoders.com/112/112121.jpg");
            background-size: cover;
        }
    </style>

    <script>
        function changeImage(name, source) {
            document.getElementById(name).src=source;
        }
    </script>
</head>
<body>
    <img src="imagens/logo.png" width="5%" height="auto" style="padding-left: 50px; padding-top: 20px; position: absolute">
    <div class="container">
        <div class="btn-group" style="padding-top: 20px;">
            <button class="btn btn-primary" style="width: 100px;"></button>
            <a type="button" class="btn btn-primary" href="index.html">Pagina Principal</a>
            <a type="button" class="btn btn-primary" href="novidades.html">Novidades</button>
            <a type="button" class="btn btn-primary" href="contacto.html">Contactos</button>
            <a type="button" class="btn btn-primary" href="termos.html">Termos e Condições</button>
            <a type="button" class="btn btn-primary" href="outros.html">Outros</a>
            <div class="btn-group">
                <button type="button" class="btn btn-primary dropdown-toggle" data-bs-toggle="dropdown">Criança</button>
                <ul class="dropdown-menu">
                    <li><a class="dropdown-item" href="crianca-t-shirt.html">T-Shirt</a></li>
                    <li><a class="dropdown-item" href="crianca-camisola.html">Camisola</a></li>
                </ul>
            </div>
            <div class="btn-group">
                <button type="button" class="btn btn-primary dropdown-toggle" data-bs-toggle="dropdown">Homem</button>
                <ul class="dropdown-menu">
                    <li><a class="dropdown-item" href="homem-t-shirt.html">T-Shirt</a></li>
                    <li><a class="dropdown-item" href="homem-camisola.html">Camisola</a></li>
                    <li><a class="dropdown-item" href="homem-calcoes.html">Calções</a></li>
                    <li><a class="dropdown-item" href="homem-casaco.html">Casaco</a></li>
                </ul>
            </div>
            <div class="btn-group">
                <button type="button" class="btn btn-primary dropdown-toggle" data-bs-toggle="dropdown">Mulher</button>
                <ul class="dropdown-menu">
                    <li><a class="dropdown-item" href="mulher-t-shirt.html">T-Shirt</a></li>
                    <li><a class="dropdown-item" href="mulher-camisola.html">Camisola</a></li>
                    <li><a class="dropdown-item" href="mulher-calcas.html">Calças</a></li>
                </ul>
            </div>
        </div>
    </div>  
    <div class="mainDiv">
        <h1 style="text-align: center;">'A Moda Universal: Estilo Além das Fronteiras' <br> Este título evoca a ideia de que a moda é uma linguagem global, transcendendo fronteiras culturais e geográficas. <br>É um convite para explorar a diversidade e a criatividade no mundo da moda.</h1>
        
        <hr style="width: 100%; border: 5px solid rgb(255, 255, 255); border-radius: 5px;">

        <h1 style="text-align: center; color: red;">PROMOÇÃO</h1>
        <div class="imageDiv">
            <br>
            <h2 class="product-title title">Camisola Cruz (Mulher)</h2>
            <br><br><br>
            <img class="image product-image" src="imagens/1.png" id="1"/>
            <h2 class="text" style="color: red; text-decoration:line-through;">99.99€</h2>
            <h2 class="text2 product-price">49.99€</h2>
            <h2 class="text2"><br>Tamanhos: S | M | L</h2>
            <img class="imgSelect" src="imagens/1.png" width="70px" onclick="changeImage(1, 'imagens/1.png')"/>
            <img class="imgSelect" src="imagens/2.png" width="70px" onclick="changeImage(1, 'imagens/2.png')"/>
            <img class="imgSelect" src="imagens/3.png" width="70px" onclick="changeImage(1, 'imagens/3.png')"/>
            <img class="imgSelect" src="imagens/4.png" width="70px" onclick="changeImage(1, 'imagens/4.png')"/>
            <div class="product-price-container">
                <button type="button" class="button-hover-background">Adicionar ao carrinho</button>
            </div>
        </div>

        <div class="imageDiv">
            <br>
            <h2 class="product-title title">Camisola Cruz (Criança)</h2>
            <br><br><br>
            <img class="image product-image" src="imagens/5.png" id="2"/>
            <h2 class="text" style="color: red; text-decoration:line-through;">89.99€</h2>
            <h2 class="text2 product-price">39.99€</h2>
            <h2 class="text2"><br>Tamanhos: S | M | L</h2>
            <img class="imgSelect" src="imagens/5.png" width="70px" onclick="changeImage(2, 'imagens/5.png')"/>
            <img class="imgSelect" src="imagens/6.png" width="70px" onclick="changeImage(2, 'imagens/6.png')"/>
            <div class="product-price-container">
                <button type="button" class="button-hover-background">Adicionar ao carrinho</button>
            </div>
        </div>

        <div class="imageDiv">
            <br>
            <h2 class="product-title title">Camisola Cruz (Homem)</h2>
            <br><br><br>
            <img class="image product-image" src="imagens/7.png"id="3"/>
            <h2 class="text" style="color: red; text-decoration:line-through;">95.99€</h2>
            <h2 class="text2 product-price">69.99€</h2>
            <h2 class="text2"><br>Tamanhos: S | M | L</h2>
            <img class="imgSelect" src="imagens/7.png" width="70px" onclick="changeImage(3, 'imagens/7.png')"/>
            <img class="imgSelect" src="imagens/8.png" width="70px" onclick="changeImage(3, 'imagens/8.png')"/>
            <div class="product-price-container">
                <button type="button" class="button-hover-background">Adicionar ao carrinho</button>
            </div>
        </div>
        <section class="container normal-section">
            <h2 class="section-title">Carrinho</h2>

            <table class="cart-table">
                <thead>
                <tr>
                    <th class="table-head-item first-col">Item</th>
                    <th class="table-head-item second-col">Preço</th>
                    <th class="table-head-item third-col">Quantidade</th>
                </tr>
                </thead>

                <tbody>

                </tbody>

                <tfoot>
                <tr>
                    <td colspan="3" class="cart-total-container">
                    <strong>Total</strong>
                    <span>0,00€</span>
                    </td>
                </tr>
                </tfoot>
            </table>

            <button type="button" class="purchase-button">Finalizar Compra</button>
        </section>
    </div>
</body>
<!DOCTYPE html>

<head>
    <title>Moda Universal</title>

    <meta charset="UTF-8">

    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-T3c6CoIi6uLrA9TneNEoa7RxnatzjcDSCmG1MXxSR1GAsXEV/Dwwykc2MPK8M2HN" crossorigin="anonymous">
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-C6RzsynM9kWDrMNeT87bh95OGNyZPhcTNXj1NW7RuBCsyN/o0jlpcV8Qyq46cDfL" crossorigin="anonymous"></script>

    <link rel="stylesheet" href="styles.css">

    <script src="loja.js" async></script>

    <style>
        body{
            background-image: url("https://images.alphacoders.com/112/112121.jpg");
            background-size: cover;
        }
    </style>

    <script>
        function changeImage(name, source) {
            document.getElementById(name).src=source;
        }
    </script>
</head>
<body>
    <img src="imagens/logo.png" width="5%" height="auto" style="padding-left: 50px; padding-top: 20px; position: absolute">
    <div class="container">
        <div class="btn-group" style="padding-top: 20px;">
            <button class="btn btn-primary" style="width: 100px;"></button>
            <a type="button" class="btn btn-primary" href="index.html">Pagina Principal</a>
            <a type="button" class="btn btn-primary" href="novidades.html">Novidades</button>
            <a type="button" class="btn btn-primary" href="contacto.html">Contactos</button>
            <a type="button" class="btn btn-primary" href="termos.html">Termos e Condições</button>
            <a type="button" class="btn btn-primary" href="outros.html">Outros</a>
            <div class="btn-group">
                <button type="button" class="btn btn-primary dropdown-toggle" data-bs-toggle="dropdown">Criança</button>
                <ul class="dropdown-menu">
                    <li><a class="dropdown-item" href="crianca-t-shirt.html">T-Shirt</a></li>
                    <li><a class="dropdown-item" href="crianca-camisola.html">Camisola</a></li>
                </ul>
            </div>
            <div class="btn-group">
                <button type="button" class="btn btn-primary dropdown-toggle" data-bs-toggle="dropdown">Homem</button>
                <ul class="dropdown-menu">
                    <li><a class="dropdown-item" href="homem-t-shirt.html">T-Shirt</a></li>
                    <li><a class="dropdown-item" href="homem-camisola.html">Camisola</a></li>
                    <li><a class="dropdown-item" href="homem-calcoes.html">Calções</a></li>
                    <li><a class="dropdown-item" href="homem-casaco.html">Casaco</a></li>
                </ul>
            </div>
            <div class="btn-group">
                <button type="button" class="btn btn-primary dropdown-toggle" data-bs-toggle="dropdown">Mulher</button>
                <ul class="dropdown-menu">
                    <li><a class="dropdown-item" href="mulher-t-shirt.html">T-Shirt</a></li>
                    <li><a class="dropdown-item" href="mulher-camisola.html">Camisola</a></li>
                    <li><a class="dropdown-item" href="mulher-calcas.html">Calças</a></li>
                </ul>
            </div>
        </div>
    </div>  
    <div class="mainDiv">
        <h1>Mulher</h1>

        <hr style="width: 100%; border: 5px solid rgb(255, 255, 255); border-radius: 5px;">
        <div class="imageDiv">
            <br>
            <h2 class="product-title title">Leggings Volkswagen</h2>
            <br><br><br>
            <img class="image product-image" src="imagens/22.png" id="4"/>
            <h2 class="text product-price">59.99€</h2>
            <h6 class="text2">Apresentamos nossas Leggings Volkswagen, o equilíbrio perfeito entre moda e paixão automobilística. Feitas para os amantes da Volkswagen, estas leggings têm um padrão canelado exclusivo que adiciona um toque de estilo e conforto.<br>Sinta-se conectado à sua paixão pelos carros Volkswagen enquanto desfruta do ajuste perfeito e da flexibilidade que essas leggings proporcionam.<br>Tamanho: S | M | L</h6>
            <img class="imgSelect" src="imagens/22.png" width="70px" onclick="changeImage(4, 'imagens/22.png')"/>
            <img class="imgSelect" src="imagens/23.png" width="70px" onclick="changeImage(4, 'imagens/23.png')"/>
            <img class="imgSelect" src="imagens/24.png" width="70px" onclick="changeImage(4, 'imagens/24.png')"/>
            <img class="imgSelect" src="imagens/25.png" width="70px" onclick="changeImage(4, 'imagens/25.png')"/>
            <div class="product-price-container">
                <button type="button" class="button-hover-background">Adicionar ao carrinho</button>
            </div>
        </div>
        <section class="container normal-section">
            <h2 class="section-title">Carrinho</h2>

            <table class="cart-table">
                <thead>
                <tr>
                    <th class="table-head-item first-col">Item</th>
                    <th class="table-head-item second-col">Preço</th>
                    <th class="table-head-item third-col">Quantidade</th>
                </tr>
                </thead>

                <tbody>

                </tbody>

                <tfoot>
                <tr>
                    <td colspan="3" class="cart-total-container">
                    <strong>Total</strong>
                    <span>0,00€</span>
                    </td>
                </tr>
                </tfoot>
            </table>

            <button type="button" class="purchase-button">Finalizar Compra</button>
        </section>
    </div>
</body>
<!DOCTYPE html>

<head>
    <title>Moda Universal</title>

    <meta charset="UTF-8">

    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-T3c6CoIi6uLrA9TneNEoa7RxnatzjcDSCmG1MXxSR1GAsXEV/Dwwykc2MPK8M2HN" crossorigin="anonymous">
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-C6RzsynM9kWDrMNeT87bh95OGNyZPhcTNXj1NW7RuBCsyN/o0jlpcV8Qyq46cDfL" crossorigin="anonymous"></script>

    <link rel="stylesheet" href="styles.css">

    <script src="loja.js" async></script>

    <style>
        body{
            background-image: url("https://images.alphacoders.com/112/112121.jpg");
            background-size: cover;
        }
    </style>

    <script>
        function changeImage(name, source) {
            document.getElementById(name).src=source;
        }
    </script>
</head>
<body>
    <img src="imagens/logo.png" width="5%" height="auto" style="padding-left: 50px; padding-top: 20px; position: absolute">
    <div class="container">
        <div class="btn-group" style="padding-top: 20px;">
            <button class="btn btn-primary" style="width: 100px;"></button>
            <a type="button" class="btn btn-primary" href="index.html">Pagina Principal</a>
            <a type="button" class="btn btn-primary" href="novidades.html">Novidades</button>
            <a type="button" class="btn btn-primary" href="contacto.html">Contactos</button>
            <a type="button" class="btn btn-primary" href="termos.html">Termos e Condições</button>
            <a type="button" class="btn btn-primary" href="outros.html">Outros</a>
            <div class="btn-group">
                <button type="button" class="btn btn-primary dropdown-toggle" data-bs-toggle="dropdown">Criança</button>
                <ul class="dropdown-menu">
                    <li><a class="dropdown-item" href="crianca-t-shirt.html">T-Shirt</a></li>
                    <li><a class="dropdown-item" href="crianca-camisola.html">Camisola</a></li>
                </ul>
            </div>
            <div class="btn-group">
                <button type="button" class="btn btn-primary dropdown-toggle" data-bs-toggle="dropdown">Homem</button>
                <ul class="dropdown-menu">
                    <li><a class="dropdown-item" href="homem-t-shirt.html">T-Shirt</a></li>
                    <li><a class="dropdown-item" href="homem-camisola.html">Camisola</a></li>
                    <li><a class="dropdown-item" href="homem-calcoes.html">Calções</a></li>
                    <li><a class="dropdown-item" href="homem-casaco.html">Casaco</a></li>
                </ul>
            </div>
            <div class="btn-group">
                <button type="button" class="btn btn-primary dropdown-toggle" data-bs-toggle="dropdown">Mulher</button>
                <ul class="dropdown-menu">
                    <li><a class="dropdown-item" href="mulher-t-shirt.html">T-Shirt</a></li>
                    <li><a class="dropdown-item" href="mulher-camisola.html">Camisola</a></li>
                    <li><a class="dropdown-item" href="mulher-calcas.html">Calças</a></li>
                </ul>
            </div>
        </div>
    </div>  
    <div class="mainDiv">
        <h1>Mulher</h1>

        <hr style="width: 100%; border: 5px solid rgb(255, 255, 255); border-radius: 5px;">

        <div class="imageDiv">
            <br>
            <h2 class="product-title title">Camisola Mustang</h2>
            <br><br><br>
            <img class="image product-image" src="imagens/66.png" id="1"/>
            <h2 class="text product-price">99.99€</h2>
            <h6 class="text2">Apresentamos nossa Camisola Mustang, perfeita para os entusiastas deste ícone automobilístico. Na parte traseira, uma arte vibrante retrata a paixão por Mustang, com uma jovem admirando esse símbolo de poder. Feita com 100% de algodão, esta camisola não apenas expressa sua criatividade, mas também oferece o conforto inigualável do algodão.<br>Para quem ama Mustang, esta camisola é uma maneira única de usar sua paixão com estilo<br>Tamanho: S | M | L</h6>
            <img class="imgSelect" src="imagens/66.png" width="70px" onclick="changeImage(1, 'imagens/66.png')"/>
            <img class="imgSelect" src="imagens/67.png" width="70px" onclick="changeImage(1, 'imagens/67.png')"/>
            <img class="imgSelect" src="imagens/72.png" width="70px" onclick="changeImage(1, 'imagens/72.png')"/>
            <img class="imgSelect" src="imagens/73.png" width="70px" onclick="changeImage(1, 'imagens/73.png')"/>
            <div class="product-price-container">
                <button type="button" class="button-hover-background">Adicionar ao carrinho</button>
            </div>
        </div>
        <section class="container normal-section">
            <h2 class="section-title">Carrinho</h2>

            <table class="cart-table">
                <thead>
                <tr>
                    <th class="table-head-item first-col">Item</th>
                    <th class="table-head-item second-col">Preço</th>
                    <th class="table-head-item third-col">Quantidade</th>
                </tr>
                </thead>

                <tbody>

                </tbody>

                <tfoot>
                <tr>
                    <td colspan="3" class="cart-total-container">
                    <strong>Total</strong>
                    <span>0,00€</span>
                    </td>
                </tr>
                </tfoot>
            </table>

            <button type="button" class="purchase-button">Finalizar Compra</button>
        </section>
    </div>
</body>
<!DOCTYPE html>

<head>
    <title>Moda Universal</title>

    <meta charset="UTF-8">

    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-T3c6CoIi6uLrA9TneNEoa7RxnatzjcDSCmG1MXxSR1GAsXEV/Dwwykc2MPK8M2HN" crossorigin="anonymous">
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-C6RzsynM9kWDrMNeT87bh95OGNyZPhcTNXj1NW7RuBCsyN/o0jlpcV8Qyq46cDfL" crossorigin="anonymous"></script>

    <link rel="stylesheet" href="styles.css">

    <script src="loja.js" async></script>

    <style>
        body{
            background-image: url("https://images.alphacoders.com/112/112121.jpg");
            background-size: cover;
        }
    </style>

    <script>
        function changeImage(name, source) {
            document.getElementById(name).src=source;
        }
    </script>
</head>
<body>
    <img src="imagens/logo.png" width="5%" height="auto" style="padding-left: 50px; padding-top: 20px; position: absolute">
    <div class="container">
        <div class="btn-group" style="padding-top: 20px;">
            <button class="btn btn-primary" style="width: 100px;"></button>
            <a type="button" class="btn btn-primary" href="index.html">Pagina Principal</a>
            <a type="button" class="btn btn-primary" href="novidades.html">Novidades</button>
            <a type="button" class="btn btn-primary" href="contacto.html">Contactos</button>
            <a type="button" class="btn btn-primary" href="termos.html">Termos e Condições</button>
            <a type="button" class="btn btn-primary" href="outros.html">Outros</a>
            <div class="btn-group">
                <button type="button" class="btn btn-primary dropdown-toggle" data-bs-toggle="dropdown">Criança</button>
                <ul class="dropdown-menu">
                    <li><a class="dropdown-item" href="crianca-t-shirt.html">T-Shirt</a></li>
                    <li><a class="dropdown-item" href="crianca-camisola.html">Camisola</a></li>
                </ul>
            </div>
            <div class="btn-group">
                <button type="button" class="btn btn-primary dropdown-toggle" data-bs-toggle="dropdown">Homem</button>
                <ul class="dropdown-menu">
                    <li><a class="dropdown-item" href="homem-t-shirt.html">T-Shirt</a></li>
                    <li><a class="dropdown-item" href="homem-camisola.html">Camisola</a></li>
                    <li><a class="dropdown-item" href="homem-calcoes.html">Calções</a></li>
                    <li><a class="dropdown-item" href="homem-casaco.html">Casaco</a></li>
                </ul>
            </div>
            <div class="btn-group">
                <button type="button" class="btn btn-primary dropdown-toggle" data-bs-toggle="dropdown">Mulher</button>
                <ul class="dropdown-menu">
                    <li><a class="dropdown-item" href="mulher-t-shirt.html">T-Shirt</a></li>
                    <li><a class="dropdown-item" href="mulher-camisola.html">Camisola</a></li>
                    <li><a class="dropdown-item" href="mulher-calcas.html">Calças</a></li>
                </ul>
            </div>
        </div>
    </div>  
    <div class="mainDiv">
        <h1>Mulher</h1>

        <hr style="width: 100%; border: 5px solid rgb(255, 255, 255); border-radius: 5px;">
        <div class="imageDiv">
            <br>
            <h2 class="product-title title">T-Shirt Nunes Moda</h2>
            <br><br><br>
            <img class="image product-image" src="imagens/85.png" id="2"/>
            <h2 class="text product-price">99.99€</h2>
            <h6 class="text2">A T-SHIRT de logotipo da marca é um clássico atemporal. Feita de algodão de alta qualidade, esta peça oferece conforto excepcional e durabilidade.<br> Com o logotipo da marca em destaque, tu agora podes mostrar o teu estilo e lealdade à marca com orgulho.<br> Esta T-SHIRT de algodão é a escolha perfeita para um visual casual e elegante.<br>Tamanho: S | M | L</h6>
            <img class="imgSelect" src="imagens/85.png" width="70px" onclick="changeImage(2, 'imagens/85.png')"/>
            <img class="imgSelect" src="imagens/87.png" width="70px" onclick="changeImage(2, 'imagens/87.png')"/>
            <img class="imgSelect" src="imagens/88.png" width="70px" onclick="changeImage(2, 'imagens/88.png')"/>
            <img class="imgSelect" src="imagens/89.png" width="70px" onclick="changeImage(2, 'imagens/89.png')"/>
            <img class="imgSelect" src="imagens/90.png" width="70px" onclick="changeImage(2, 'imagens/90.png')"/>
            <div class="product-price-container">
                <button type="button" class="button-hover-background">Adicionar ao carrinho</button>
            </div>
        </div>

        <div class="imageDiv">
            <br>
            <h2 class="product-title title">T-Shirt Cruz</h2>
            <br><br><br>
            <img class="image product-image" src="imagens/1.png" id="3"/>
            <h2 class="text product-price">59.99€</h2>
            <h6 class="text2">Uma camisola de algodão leve e confortável, adornada com uma cruz e uma pomba branca, é uma representação de simplicidade e espiritualidade.<br> O algodão macio proporciona conforto durante todo o dia, enquanto a cruz e a pomba adicionam um toque de significado e paz ao design, tornando-a uma escolha ideal para quem procura estilo e simbolismo em sua roupa.<br>Tamanho: S | M | L</h6>
            <img class="imgSelect" src="imagens/1.png" width="70px" onclick="changeImage(3, 'imagens/1.png')"/>
            <img class="imgSelect" src="imagens/2.png" width="70px" onclick="changeImage(3, 'imagens/2.png')"/>
            <img class="imgSelect" src="imagens/3.png" width="70px" onclick="changeImage(3, 'imagens/3.png')"/>
            <img class="imgSelect" src="imagens/4.png" width="70px" onclick="changeImage(3, 'imagens/4.png')"/>
            <div class="product-price-container">
                <button type="button" class="button-hover-background">Adicionar ao carrinho</button>
            </div>
        </div>
        <section class="container normal-section">
            <h2 class="section-title">Carrinho</h2>

            <table class="cart-table">
                <thead>
                <tr>
                    <th class="table-head-item first-col">Item</th>
                    <th class="table-head-item second-col">Preço</th>
                    <th class="table-head-item third-col">Quantidade</th>
                </tr>
                </thead>

                <tbody>

                </tbody>

                <tfoot>
                <tr>
                    <td colspan="3" class="cart-total-container">
                    <strong>Total</strong>
                    <span>0,00€</span>
                    </td>
                </tr>
                </tfoot>
            </table>

            <button type="button" class="purchase-button">Finalizar Compra</button>
        </section>
    </div>
</body>
<!DOCTYPE html>

<head>
    <title>Moda Universal</title>

    <meta charset="UTF-8">

    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-T3c6CoIi6uLrA9TneNEoa7RxnatzjcDSCmG1MXxSR1GAsXEV/Dwwykc2MPK8M2HN" crossorigin="anonymous">
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-C6RzsynM9kWDrMNeT87bh95OGNyZPhcTNXj1NW7RuBCsyN/o0jlpcV8Qyq46cDfL" crossorigin="anonymous"></script>

    <link rel="stylesheet" href="styles.css">

    <script src="loja.js" async></script>

    <style>
        body{
            background-image: url("https://images.alphacoders.com/112/112121.jpg");
            background-size: cover;
        }
    </style>
    
    <script>
        function changeImage(name, source) {
            document.getElementById(name).src=source;
        }
    </script>
</head>
<body>
    <img src="imagens/logo.png" width="5%" height="auto" style="padding-left: 50px; padding-top: 20px; position: absolute">
    <div class="container">
        <div class="btn-group" style="padding-top: 20px;">
            <button class="btn btn-primary" style="width: 100px;"></button>
            <a type="button" class="btn btn-primary" href="index.html">Pagina Principal</a>
            <a type="button" class="btn btn-primary" href="novidades.html">Novidades</button>
            <a type="button" class="btn btn-primary" href="contacto.html">Contactos</button>
            <a type="button" class="btn btn-primary" href="termos.html">Termos e Condições</button>
            <a type="button" class="btn btn-primary" href="outros.html">Outros</a>
            <div class="btn-group">
                <button type="button" class="btn btn-primary dropdown-toggle" data-bs-toggle="dropdown">Criança</button>
                <ul class="dropdown-menu">
                    <li><a class="dropdown-item" href="crianca-t-shirt.html">T-Shirt</a></li>
                    <li><a class="dropdown-item" href="crianca-camisola.html">Camisola</a></li>
                </ul>
            </div>
            <div class="btn-group">
                <button type="button" class="btn btn-primary dropdown-toggle" data-bs-toggle="dropdown">Homem</button>
                <ul class="dropdown-menu">
                    <li><a class="dropdown-item" href="homem-t-shirt.html">T-Shirt</a></li>
                    <li><a class="dropdown-item" href="homem-camisola.html">Camisola</a></li>
                    <li><a class="dropdown-item" href="homem-calcoes.html">Calções</a></li>
                    <li><a class="dropdown-item" href="homem-casaco.html">Casaco</a></li>
                </ul>
            </div>
            <div class="btn-group">
                <button type="button" class="btn btn-primary dropdown-toggle" data-bs-toggle="dropdown">Mulher</button>
                <ul class="dropdown-menu">
                    <li><a class="dropdown-item" href="mulher-t-shirt.html">T-Shirt</a></li>
                    <li><a class="dropdown-item" href="mulher-camisola.html">Camisola</a></li>
                    <li><a class="dropdown-item" href="mulher-calcas.html">Calças</a></li>
                </ul>
            </div>
        </div>
    </div>
    <div class="mainDiv">
        <h1>Destaques</h1>

        <hr style="width: 100%; border: 5px solid rgb(255, 255, 255); border-radius: 5px;">

        <div class="imageDiv">
            <br>
            <h2 class="product-title title">Camisola Cruz (Mulher)</h2>
            <br><br><br>
            <img class="image product-image" src="imagens/1.png" id="1"/>
            <h2 class="text product-price">49.99€</h2>
            <h2 class="text2"><br>Tamanhos: S | M | L</h2>
            <img class="imgSelect" src="imagens/1.png" width="70px" onclick="changeImage(1, 'imagens/1.png')"/>
            <img class="imgSelect" src="imagens/2.png" width="70px" onclick="changeImage(1, 'imagens/2.png')"/>
            <img class="imgSelect" src="imagens/3.png" width="70px" onclick="changeImage(1, 'imagens/3.png')"/>
            <img class="imgSelect" src="imagens/4.png" width="70px" onclick="changeImage(1, 'imagens/4.png')"/>
            <div class="product-price-container">
                <button type="button" class="button-hover-background">Adicionar ao carrinho</button>
            </div>
        </div>

        <div class="imageDiv">
            <br>
            <h2 class="product-title title">Camisola Cruz (Criança)</h2>
            <br><br><br>
            <img class="image product-image" src="imagens/5.png" id="2"/>
            <h2 class="text product-price">39.99€</h2>
            <h2 class="text2"><br>Tamanhos: S | M | L</h2>
            <img class="imgSelect" src="imagens/5.png" width="70px" onclick="changeImage(2, 'imagens/5.png')"/>
            <img class="imgSelect" src="imagens/6.png" width="70px" onclick="changeImage(2, 'imagens/6.png')"/>
            <div class="product-price-container">
                <button type="button" class="button-hover-background">Adicionar ao carrinho</button>
            </div>
        </div>

        <div class="imageDiv">
            <br>
            <h2 class="product-title title">Camisola Cruz (Homem)</h2>
            <br><br><br>
            <img class="image product-image" src="imagens/7.png"id="3"/>
            <h2 class="text product-price">69.99€</h2>
            <h2 class="text2"><br>Tamanhos: S | M | L</h2>
            <img class="imgSelect" src="imagens/7.png" width="70px" onclick="changeImage(3, 'imagens/7.png')"/>
            <img class="imgSelect" src="imagens/8.png" width="70px" onclick="changeImage(3, 'imagens/8.png')"/>
            <div class="product-price-container">
                <button type="button" class="button-hover-background">Adicionar ao carrinho</button>
            </div>
        </div>
        <section class="container normal-section">
            <h2 class="section-title">Carrinho</h2>
    
            <table class="cart-table">
              <thead>
                <tr>
                  <th class="table-head-item first-col">Item</th>
                  <th class="table-head-item second-col">Preço</th>
                  <th class="table-head-item third-col">Quantidade</th>
                </tr>
              </thead>
    
              <tbody>
    
              </tbody>
    
              <tfoot>
                <tr>
                  <td colspan="3" class="cart-total-container">
                    <strong>Total</strong>
                    <span>0,00€</span>
                  </td>
                </tr>
              </tfoot>
            </table>
    
            <button type="button" class="purchase-button">Finalizar Compra</button>
        </section>
    </div>
</body>
<!DOCTYPE html>

<head>
    <title>Moda Universal</title>

    <meta charset="UTF-8">

    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-T3c6CoIi6uLrA9TneNEoa7RxnatzjcDSCmG1MXxSR1GAsXEV/Dwwykc2MPK8M2HN" crossorigin="anonymous">
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-C6RzsynM9kWDrMNeT87bh95OGNyZPhcTNXj1NW7RuBCsyN/o0jlpcV8Qyq46cDfL" crossorigin="anonymous"></script>

    <link rel="stylesheet" href="styles.css">

    <script src="loja.js" async></script>
    
    <style>
        body{
            background-image: url("https://images.alphacoders.com/112/112121.jpg");
            background-size: cover;
        }
    </style>

    <script>
        function changeImage(name, source) {
            document.getElementById(name).src=source;
        }
    </script>
</head>
<body>
    <img src="imagens/logo.png" width="5%" height="auto" style="padding-left: 50px; padding-top: 20px; position: absolute">
    <div class="container">
        <div class="btn-group" style="padding-top: 20px;">
            <button class="btn btn-primary" style="width: 100px;"></button>
            <a type="button" class="btn btn-primary" href="index.html">Pagina Principal</a>
            <a type="button" class="btn btn-primary" href="novidades.html">Novidades</button>
            <a type="button" class="btn btn-primary" href="contacto.html">Contactos</button>
            <a type="button" class="btn btn-primary" href="termos.html">Termos e Condições</button>
            <a type="button" class="btn btn-primary" href="outros.html">Outros</a>
            <div class="btn-group">
                <button type="button" class="btn btn-primary dropdown-toggle" data-bs-toggle="dropdown">Criança</button>
                <ul class="dropdown-menu">
                    <li><a class="dropdown-item" href="crianca-t-shirt.html">T-Shirt</a></li>
                    <li><a class="dropdown-item" href="crianca-camisola.html">Camisola</a></li>
                </ul>
            </div>
            <div class="btn-group">
                <button type="button" class="btn btn-primary dropdown-toggle" data-bs-toggle="dropdown">Homem</button>
                <ul class="dropdown-menu">
                    <li><a class="dropdown-item" href="homem-t-shirt.html">T-Shirt</a></li>
                    <li><a class="dropdown-item" href="homem-camisola.html">Camisola</a></li>
                    <li><a class="dropdown-item" href="homem-calcoes.html">Calções</a></li>
                    <li><a class="dropdown-item" href="homem-casaco.html">Casaco</a></li>
                </ul>
            </div>
            <div class="btn-group">
                <button type="button" class="btn btn-primary dropdown-toggle" data-bs-toggle="dropdown">Mulher</button>
                <ul class="dropdown-menu">
                    <li><a class="dropdown-item" href="mulher-t-shirt.html">T-Shirt</a></li>
                    <li><a class="dropdown-item" href="mulher-camisola.html">Camisola</a></li>
                    <li><a class="dropdown-item" href="mulher-calcas.html">Calças</a></li>
                </ul>
            </div>
        </div>
    </div> 
    <div class="mainDiv">
        <h1>Outros</h1>

        <hr style="width: 100%; border: 5px solid rgb(255, 255, 255); border-radius: 5px;">

        <div class="imageDiv">
            <br>
            <h2 class="product-title title">Capa Telemóvel</h2>
            <br><br><br>
            <img class="image product-image" src="imagens/105.png" id="1"/>
            <h2 class="text product-price">40.99€</h2>
            <h6 class="text2">Apresentamos nossa Capa de Telemóvel com Logotipo Exclusivo, uma fusão perfeita de estilo e personalização.<br>Desenvolvemos este produto com um logotipo único da nossa marca, tornando-o verdadeiramente exclusivo.<br>Além de proteger o seu dispositivo, esta capa é uma declaração de identidade, destacando a sua afinidade com nossa marca.<br>Seja parte do nosso universo, onde a proteção encontra a personalização, proporcionando uma experiência única e elegante</h6>
            <img class="imgSelect" src="imagens/105.png" width="70px" onclick="changeImage(1, 'imagens/105.png')"/>
            <img class="imgSelect" src="imagens/106.png" width="70px" onclick="changeImage(1, 'imagens/106.png')"/>
            <img class="imgSelect" src="imagens/107.png" width="70px" onclick="changeImage(1, 'imagens/107.png')"/>
            <img class="imgSelect" src="imagens/108.png" width="70px" onclick="changeImage(1, 'imagens/108.png')"/>
            <div class="product-price-container">
                <button type="button" class="button-hover-background">Adicionar ao carrinho</button>
            </div>
        </div>

        <div class="imageDiv">
            <br>
            <h2 class="product-title title">Capa de Fones</h2>
            <br><br><br>
            <img class="image product-image" src="imagens/91.png" id="2"/>
            <h2 class="text product-price">29.99€</h2>
            <h6 class="text2">Eleve sua paixão automobilística a um novo nível com nossa Capa de Fones com a imagem de um Supra.<br>Este acessório é um tributo à lenda dos carros esportivos, com uma imagem nítida do Supra que fará seu coração acelerar. Além de fornecer proteção aos seus fones de ouvido, esta capa adiciona um toque de estilo e personalidade, permitindo que você carregue sua paixão automobilística para onde quer que vá.<br>Mostre ao mundo que você é um entusiasta do Supra com esta capa única e elegante</h6>
            <img class="imgSelect" src="imagens/91.png" width="70px" onclick="changeImage(2, 'imagens/91.png')"/>
            <img class="imgSelect" src="imagens/92.png" width="70px" onclick="changeImage(2, 'imagens/92.png')"/>
            <img class="imgSelect" src="imagens/93.png" width="70px" onclick="changeImage(2, 'imagens/93.png')"/>
            <img class="imgSelect" src="imagens/94.png" width="70px" onclick="changeImage(2, 'imagens/94.png')"/>
            <div class="product-price-container">
                <button type="button" class="button-hover-background">Adicionar ao carrinho</button>
            </div>
        </div>
        <section class="container normal-section">
            <h2 class="section-title">Carrinho</h2>

            <table class="cart-table">
                <thead>
                <tr>
                    <th class="table-head-item first-col">Item</th>
                    <th class="table-head-item second-col">Preço</th>
                    <th class="table-head-item third-col">Quantidade</th>
                </tr>
                </thead>

                <tbody>

                </tbody>

                <tfoot>
                <tr>
                    <td colspan="3" class="cart-total-container">
                    <strong>Total</strong>
                    <span>0,00€</span>
                    </td>
                </tr>
                </tfoot>
            </table>

            <button type="button" class="purchase-button">Finalizar Compra</button>
        </section>
    </div>
</body>
<!DOCTYPE html>

<head>
    <title>Moda Universal</title>

    <meta charset="UTF-8">

    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-T3c6CoIi6uLrA9TneNEoa7RxnatzjcDSCmG1MXxSR1GAsXEV/Dwwykc2MPK8M2HN" crossorigin="anonymous">
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-C6RzsynM9kWDrMNeT87bh95OGNyZPhcTNXj1NW7RuBCsyN/o0jlpcV8Qyq46cDfL" crossorigin="anonymous"></script>
    
    <script src="loja.js" async></script>

    <style>
        body{
            background-color: black;
            /* background-image: url("https://images.alphacoders.com/112/112121.jpg"); */
            background-size: cover;
        }

        .mainDiv{
            width: 98%;
            margin-top: 2%;
            margin-left: 1%;
            color: white;
            padding: 2%;
            padding-top: 5px;
            /* background-image: url("http://getwallpapers.com/wallpaper/full/1/a/3/1519947-vertical-dark-theme-wallpaper-1920x1080-4k.jpg"); */
        }
        .image {
            display: inline-block;
            vertical-align: middle;
            width: 300px;
            height: 200px;
        }
        .text {
            padding-left: 50px;
            display:inline-block;
            position: absolute;
            vertical-align: top;
        }

        .text2{
            padding-left: 170px;
            display:inline-block;
            position: absolute;
            vertical-align: top;
        }

        .imgSelect {
            margin-left: 20px;
            display: inline-block;
            height: 60px;
            vertical-align: bottom;
        }

        .imgSelect:hover {
            border: 3px solid #00d9ff;
        }

        .imageDiv{
            padding-bottom: 50px;
        }
    </style>

    <script>
        function changeImage(name, source) {
            document.getElementById(name).src=source;
        }
    </script>
</head>
<body>
    <img src="imagens/logo.png" width="5%" height="auto" style="padding-left: 50px; padding-top: 20px; position: absolute">
    <div class="container">
        <div class="btn-group" style="padding-top: 20px;">
            <button class="btn btn-primary" style="width: 100px;"></button>
            <a type="button" class="btn btn-primary" href="index.html">Pagina Principal</a>
            <a type="button" class="btn btn-primary" href="novidades.html">Novidades</button>
            <a type="button" class="btn btn-primary" href="contacto.html">Contactos</button>
            <a type="button" class="btn btn-primary" href="termos.html">Termos e Condições</button>
            <a type="button" class="btn btn-primary" href="outros.html">Outros</a>
            <div class="btn-group">
                <button type="button" class="btn btn-primary dropdown-toggle" data-bs-toggle="dropdown">Criança</button>
                <ul class="dropdown-menu">
                    <li><a class="dropdown-item" href="crianca-t-shirt.html">T-Shirt</a></li>
                    <li><a class="dropdown-item" href="crianca-camisola.html">Camisola</a></li>
                </ul>
            </div>
            <div class="btn-group">
                <button type="button" class="btn btn-primary dropdown-toggle" data-bs-toggle="dropdown">Homem</button>
                <ul class="dropdown-menu">
                    <li><a class="dropdown-item" href="homem-t-shirt.html">T-Shirt</a></li>
                    <li><a class="dropdown-item" href="homem-camisola.html">Camisola</a></li>
                    <li><a class="dropdown-item" href="homem-calcoes.html">Calções</a></li>
                    <li><a class="dropdown-item" href="homem-casaco.html">Casaco</a></li>
                </ul>
            </div>
            <div class="btn-group">
                <button type="button" class="btn btn-primary dropdown-toggle" data-bs-toggle="dropdown">Mulher</button>
                <ul class="dropdown-menu">
                    <li><a class="dropdown-item" href="mulher-t-shirt.html">T-Shirt</a></li>
                    <li><a class="dropdown-item" href="mulher-camisola.html">Camisola</a></li>
                    <li><a class="dropdown-item" href="mulher-calcas.html">Calças</a></li>
                </ul>
            </div>
        </div>
    </div> 
    <div class="mainDiv">
        <hr style="width: 100%; border: 5px solid rgb(255, 255, 255); border-radius: 5px;">

        <h1 style="text-align: center;">Termos e Condições</h1>
        <p style="text-align: center;">
            Bem-vindo aos Termos e Condições da Nunes Moda.<br>
            Estes termos estabelecem as diretrizes e as regras que regem o uso de nossa loja online e a compra de produtos de vestuário.<br>
            Ao acessar nosso site e realizar uma compra, você concorda com estes termos em sua totalidade.<br>
            Por favor, leia-os com atenção antes de prosseguir<br>

            Uso do Site:<br>
            Ao utilizar nosso site, você concorda em não utilizar informações falsas ou enganosas, nem realizar atividades ilegais ou prejudiciais. Reservamo-nos o direito de recusar o serviço, encerrar contas ou cancelar pedidos a nosso critério.<br>

            Informações Pessoais:<br>

            Ao fazer uma compra, você concorda em fornecer informações precisas e atualizadas. Nós respeitamos sua privacidade e protegemos suas informações pessoais conforme estabelecido em nossa Política de Privacidade.<br>

            Produtos e Pedidos:<br>

            Fazemos o nosso melhor para exibir cores, tamanhos e detalhes dos produtos com precisão. No entanto, não garantimos que a exibição do seu dispositivo seja 100% precisa. Nos reservamos o direito de limitar a quantidade de produtos disponíveis ou recusar pedidos.<br>

            Preços e Pagamentos:<br>

            Os preços dos produtos estão sujeitos a alterações sem aviso prévio. O pagamento deve ser efetuado no momento da compra e aceitamos os métodos de pagamento especificados em nosso site.<br>
            Envio e Entrega:<br>

            Fornecemos informações detalhadas sobre opções de envio e prazos de entrega em nosso site. A entrega está sujeita a condições de terceiros, e não nos responsabilizamos por atrasos causados por fatores fora de nosso controle.<br>

            Trocas e Devoluções:<br>

            Nós aceitamos trocas e devoluções de acordo com nossa Política de Trocas e Devoluções. Certifique-se de ler e entender essas políticas antes de comprar.<br>

            Propriedade Intelectual:<br>

            Todo o conteúdo presente em nosso site, incluindo textos, imagens, logotipos e gráficos, é protegido por direitos autorais e propriedade intelectual. Não é permitido copiar, reproduzir ou utilizar qualquer conteúdo sem nossa autorização.<br>

            Limitação de Responsabilidade:<br>

            Não nos responsabilizamos por quaisquer danos diretos, indiretos, incidentais ou consequenciais resultantes do uso de nossos produtos ou do acesso ao nosso site.<br>

            Alterações nos Termos:<br>

            Reservamo-nos o direito de atualizar ou modificar estes termos a qualquer momento. As mudanças entrarão em vigor assim que forem publicadas em nosso site.<br>

            Contato:<br>

            Para quaisquer dúvidas, sugestões ou reclamações relacionadas aos nossos termos e condições, entre em contato conosco através dos canais especificados em nosso site.<br>

            Ao continuar usando nosso site e comprar nossos produtos, você concorda com estes Termos e Condições. Obrigado por escolher Nunes Moda!<br>
        </p>
        <hr style="width: 100%; border: 5px solid rgb(255, 255, 255); border-radius: 5px;">
    </div>
</body>
