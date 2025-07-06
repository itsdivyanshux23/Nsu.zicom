# Nsu.zicom
Camera sell company cheap and affordable price 
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>NSU Trading – Camera Store</title>
  <link rel="stylesheet" href="css/styles.css">
</head>
<body>
  <header>
    <h1>NSU Trading</h1>
    <p>Quality Cameras from ₹200 to ₹50,000</p>
  </header>

  <main class="gallery">
    <!-- Repeat this block for each camera -->
    <div class="product-card">
      <img src="images/camera1.jpg" alt="Camera Model X">
      <h2>Camera Model X</h2>
      <p>₹12,999</p>
      <button>Add to Cart</button>
    </div>
    <!-- … more .product-card blocks … -->
  </main>

  <footer>
    <p>© 2025 NSU Trading. All rights reserved.</p>
  </footer>
</body>
</html>
body { font-family: sans-serif; margin: 0; padding: 0; }
header { text-align: center; padding: 2rem; background: #f4f4f4; }
.gallery {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
  gap: 1rem;
  padding: 1rem;
}
.product-card {
  border: 1px solid #ddd;
  border-radius: 8px;
  padding: 1rem;
  text-align: center;
}
.product-card img {
  max-width: 100%;
  height: auto;
  border-radius: 4px;
}
button {
  margin-top: .5rem;
  padding: .5rem 1rem;
  border: none;
  border-radius: 4px;
  cursor: pointer;
}
