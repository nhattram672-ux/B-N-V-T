* {
  box-sizing: border-box;
  font-family: Arial, sans-serif;
}

body {
  margin: 0;
  background: #f6f6f6;
}

header {
  background: #000;
  color: white;
  text-align: center;
  padding: 15px;
}

.category {
  padding: 10px;
}

.category h2 {
  margin: 10px 0;
}

.grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr); /* 3 vợt / hàng */
  gap: 10px;
}

.card {
  background: white;
  border-radius: 10px;
  padding: 8px;
  text-align: center;
  box-shadow: 0 2px 5px rgba(0,0,0,0.1);
}

.card img {
  width: 100%;
  border-radius: 8px;
}

.card h3 {
  font-size: 14px;
  margin: 5px 0;
}

.price {
  font-weight: bold;
  color: #d60000;
}

.tag {
  display: inline-block;
  padding: 2px 6px;
  font-size: 11px;
  border-radius: 5px;
  margin: 2px;
  color: white;
}

.jp { background: #000; }
.sp { background: #0066cc; }
.percent { background: #2ecc71; }

footer {
  text-align: center;
  padding: 15px;
  background: #222;
  color: white;
  margin-top: 20px;
}
