body {
  margin: 0;
  font-family: "Segoe UI", Arial, sans-serif;
  background-color: #002a6e;
  color: white;
}

.header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 15px 40px;
  background: rgba(0, 0, 0, 0.1);
  position: fixed;
  width: 100%;
  top: 0;
}

.logo {
  font-weight: 700;
  font-size: 22px;
  color: white;
}

.nav a {
  margin-left: 25px;
  text-decoration: none;
  color: white;
  font-weight: 500;
}

.nav a:hover {
  text-decoration: underline;
}

.hero {
  height: 100vh;
  background: linear-gradient(160deg, #002a6e, #0055aa);
  display: flex;
  align-items: center;
  justify-content: center;
  text-align: center;
  padding: 0 20px;
}

.hero-content h1 {
  font-size: 2.5em;
  margin-bottom: 10px;
}

.btn-hero, .btn-whatsapp {
  background-color: #ffcc00;
  color: #002a6e;
  padding: 12px 30px;
  border-radius: 6px;
  text-decoration: none;
  font-weight: bold;
}

.sobre, .produtos {
  padding: 100px 20px;
  text-align: center;
  background-color: #003a8c;
}

.grid-produtos {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
  gap: 20px;
  margin-top: 30px;
}

.produto-card {
  background: white;
  color: #002a6e;
  border-radius: 8px;
  padding: 20px;
  font-weight: 600;
}

.footer {
  background: #001a44;
  padding: 30px;
  text-align: center;
  font-size: 0.9em;
}
