# Sparia<!DOCTYPE html>
<html lang="fa">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>خرید سی‌پی و بتل‌پس</title>
    <style>
        body { font-family: Arial, sans-serif; text-align: center; }
        .product { border: 1px solid #ddd; padding: 10px; margin: 10px; display: inline-block; }
        button { background-color: #28a745; color: white; padding: 10px; border: none; cursor: pointer; }
    </style>
</head>
<body>
    <h1>خرید سی‌پی و بتل‌پس</h1>
    
    <div class="product">
        <h2>سی‌پی 240</h2>
        <p>قیمت: 100,000 تومان</p>
        <button onclick="buy('سی‌پی 240', 100000)">خرید</button>
    </div>

    <div class="product">
        <h2>بتل‌پس</h2>
        <p>قیمت: 300,000 تومان</p>
        <button onclick="buy('بتل‌پس', 300000)">خرید</button>
    </div>

    <div class="product">
        <h2>آفر ویژه</h2>
        <p>قیمت: 500,000 تومان</p>
        <button onclick="buy('آفر ویژه', 500000)">خرید</button>
    </div>

    <script>
        function buy(product, price) {
            alert('شما ' + product + ' را به قیمت ' + price + ' تومان خریداری کردید.');
            // اینجا می‌توانی کد اتصال به درگاه پرداخت را اضافه کنی.
        }
    </script>
</body>
</html>