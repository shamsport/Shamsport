<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>تفاصيل المنتج - تيشيرت رياضي</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #f8f8f8;
      margin: 0;
      padding: 0;
    }

    header {
      background: #222;
      color: white;
      padding: 1rem 2rem;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }

    header h1 {
      margin: 0;
    }

    .product-details {
      display: flex;
      flex-direction: column;
      gap: 20px;
      max-width: 1000px;
      margin: 2rem auto;
      padding: 1rem;
      background: white;
      border-radius: 10px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }

    @media(min-width: 768px) {
      .product-details {
        flex-direction: row;
      }
    }

    .product-image {
      flex: 1;
      padding: 1rem;
    }

    .product-image img {
      width: 100%;
      border-radius: 10px;
    }

    .product-info {
      flex: 2;
      padding: 1rem;
    }

    .product-info h2 {
      margin-top: 0;
    }

    .sizes label {
      display: inline-block;
      margin: 5px;
    }

    .product-info button {
      margin-top: 20px;
      background: #0d6efd;
      color: white;
      border: none;
      padding: 10px 20px;
      border-radius: 5px;
      cursor: pointer;
    }

    .product-info button:hover {
      background: #0b5ed7;
    }
  </style>
</head>
<body>

<header>
  <h1>شام سبورت</h1>
  <nav>
    <a href="index.html" style="color:white;text-decoration:none;">العودة للمنتجات</a>
  </nav>
</header>

<div class="product-details">
  <div class="product-image">
    <img src="https://via.placeholder.com/500x500?text=تيشيرت+رياضي" alt="تيشيرت رياضي" />
  </div>
  <div class="product-info">
    <h2>تيشيرت رياضي</h2>
    <p><strong>السعر:</strong> 120 ريال</p>
    <p>تيشيرت رياضي عالي الجودة، مصنوع من قماش قابل للتنفس مثالي للتمارين والأنشطة الخارجية.</p>
    
    <div class="sizes">
      <strong>اختر المقاس:</strong><br />
      <label><input type="radio" name="size" /> S</label>
      <label><input type="radio" name="size" /> M</label>
      <label><input type="radio" name="size" /> L</label>
      <label><input type="radio" name="size" /> XL</label>
    </div>

    <button>أضف إلى السلة</button>
  </div>
</div>

</body>
</html>
<div class="product-card">
  <a href="details-tshirt.html">
    <img src="https://via.placeholder.com/300x300?text=تيشيرت+رياضي" alt="تيشيرت رياضي" />
  </a>
  <h3><a href="details-tshirt.html" style="text-decoration:none; color: black;">تيشيرت رياضي</a></h3>
  <p>السعر: 120 ريال</p>
  <button>أضف إلى السلة</button>
</div>
<a href="details-tshirt.html">...</a>
<a href="details-pants.html">...</a>
<a href="details-hoodie.html">...</a>
