* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}
html {
  scroll-behavior: smooth;
}
body {
  font-family: Inter, Arial, sans-serif;
  color: #17202a;
  background: #fff;
  line-height: 1.6;
}
.container {
  width: min(1120px, 92%);
  margin: auto;
}
.header {
  position: sticky;
  top: 0;
  z-index: 100;
  background: rgba(255, 255, 255, 0.95);
  backdrop-filter: blur(12px);
  border-bottom: 1px solid #eee;
}
.nav {
  height: 76px;
  display: flex;
  align-items: center;
  justify-content: space-between;
}
.brand {
  display: flex;
  align-items: center;
  gap: 10px;
  text-decoration: none;
  color: #171717;
}
.brand strong {
  display: block;
  font-size: 22px;
}
.brand span {
  display: block;
  font-size: 12px;
  letter-spacing: 3px;
  color: #b8860b;
  text-transform: uppercase;
}
.logo {
  width: 46px;
  height: 46px;
  border-radius: 14px;
  background: linear-gradient(135deg, #b8860b, #f4d77b);
  display: grid;
  place-items: center;
  font-size: 27px;
  color: #fff;
  box-shadow: 0 8px 20px #b8860b40;
}
nav {
  display: flex;
  gap: 28px;
}
nav a {
  color: #333;
  text-decoration: none;
  font-weight: 600;
}
nav a:hover {
  color: #b8860b;
}
.menu-btn {
  display: none;
  border: 0;
  background: none;
  font-size: 28px;
}
.hero {
  min-height: 650px;
  display: flex;
  align-items: center;
  background: radial-gradient(circle at 80% 30%, #fff0bd, transparent 35%),
    linear-gradient(135deg, #fff, #fff8e8);
}
.hero-grid {
  display: grid;
  grid-template-columns: 1.25fr 0.75fr;
  gap: 70px;
  align-items: center;
}
.eyebrow {
  font-size: 13px;
  letter-spacing: 3px;
  font-weight: 800;
  color: #b17b00;
  margin-bottom: 14px;
}
.hero h1 {
  font-size: clamp(42px, 6vw, 70px);
  line-height: 1.08;
  letter-spacing: -2px;
}
.hero h1 span {
  color: #b8860b;
}
.hero-text {
  font-size: 18px;
  color: #666;
  max-width: 650px;
  margin: 24px 0;
}
.buttons {
  display: flex;
  gap: 14px;
  flex-wrap: wrap;
}
.btn {
  display: inline-block;
  padding: 13px 23px;
  border-radius: 10px;
  border: 1px solid #b8860b;
  text-decoration: none;
  font-weight: 800;
  cursor: pointer;
}
.primary {
  background: #b8860b;
  color: white;
}
.outline {
  color: #9a6d00;
  background: white;
}
.hero-card {
  background: #171717;
  color: #fff;
  border-radius: 28px;
  padding: 55px 35px;
  text-align: center;
  box-shadow: 0 25px 60px #0002;
  transform: rotate(2deg);
}
.om {
  font-size: 80px;
  color: #f0c75e;
}
.hero-card h2 {
  font-size: 28px;
}
.hero-card p {
  color: #ddd;
}
.card-line {
  height: 2px;
  background: #b8860b;
  margin: 22px auto;
  width: 70%;
}
.section {
  padding: 95px 0;
}
.section h2 {
  font-size: 42px;
  line-height: 1.15;
  margin-bottom: 25px;
}
.two-col,
.contact-grid {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 70px;
  align-items: center;
}
.two-col p {
  color: #666;
  margin-bottom: 15px;
}
.stats {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 18px;
}
.stats div {
  padding: 30px;
  background: #fffaf0;
  border: 1px solid #f0dfae;
  border-radius: 18px;
}
.stats b {
  display: block;
  font-size: 28px;
  color: #b8860b;
}
.stats span {
  color: #666;
}
.dark {
  background: #171717;
  color: #fff;
}
.dark .eyebrow {
  color: #f0c75e;
}
.cards,
.product-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 22px;
}
.cards article {
  padding: 34px;
  border: 1px solid #444;
  border-radius: 20px;
  background: #202020;
}
.icon {
  font-size: 30px;
  color: #f0c75e;
  margin-bottom: 18px;
}
.cards p {
  color: #bbb;
  margin-top: 8px;
}
.product {
  border: 1px solid #eee;
  border-radius: 20px;
  overflow: hidden;
  background: #fff;
  box-shadow: 0 10px 30px #0000000a;
}
.product-img {
  height: 180px;
  background: linear-gradient(135deg, #181818, #6b531d);
  display: grid;
  place-items: center;
  color: #f0c75e;
  font-weight: 900;
  letter-spacing: 3px;
}
.product h3,
.product p {
  padding: 0 22px;
}
.product h3 {
  margin-top: 20px;
}
.product p {
  padding-bottom: 24px;
  color: #777;
}
.contact {
  background: #fff8e8;
}
.contact-info {
  margin-top: 25px;
  color: #555;
}
.contact-info p {
  margin: 10px 0;
}
form {
  background: #fff;
  padding: 30px;
  border-radius: 22px;
  box-shadow: 0 15px 40px #00000010;
}
input,
textarea {
  width: 100%;
  padding: 14px 15px;
  margin-bottom: 13px;
  border: 1px solid #ddd;
  border-radius: 10px;
  font: inherit;
  outline: none;
}
input:focus,
textarea:focus {
  border-color: #b8860b;
}
form .btn {
  width: 100%;
}
#formMsg {
  margin-top: 12px;
  color: #b17b00;
  font-weight: 700;
}
footer {
  background: #111;
  color: #bbb;
  padding: 30px 0;
}
.footer {
  display: flex;
  justify-content: space-between;
  gap: 20px;
}
.footer strong {
  color: #fff;
}
.whatsapp {
  position: fixed;
  right: 22px;
  bottom: 22px;
  width: 56px;
  height: 56px;
  border-radius: 50%;
  display: grid;
  place-items: center;
  background: #20c967;
  color: #fff;
  text-decoration: none;
  font-size: 25px;
  box-shadow: 0 10px 30px #0003;
}
@media (max-width: 800px) {
  nav {
    display: none;
    position: absolute;
    top: 76px;
    left: 0;
    right: 0;
    background: #fff;
    padding: 20px;
    flex-direction: column;
    gap: 15px;
    box-shadow: 0 10px 20px #0001;
  }
  .menu-btn {
    display: block;
  }
  .hero {
    padding: 70px 0;
  }
  .hero-grid,
  .two-col,
  .contact-grid {
    grid-template-columns: 1fr;
    gap: 40px;
  }
  .hero-card {
    transform: none;
  }
  .cards,
  .product-grid {
    grid-template-columns: 1fr;
  }
  .section {
    padding: 70px 0;
  }
  .section h2 {
    font-size: 34px;
  }
  .footer {
    flex-direction: column;
  }
}
