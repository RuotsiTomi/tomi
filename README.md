import React from "react";
import "./App.css";

function App() {
  return (
    <div className="app">
      {/* Navigaatio */}
      <nav className="navbar">
        <div className="logo">TR</div>
        <ul className="nav-links">
          <li><a href="#about">Osaaminen</a></li>
          <li><a href="#projects">Projektit</a></li>
          <li><a href="#interests">Mielenkiinnon kohteet</a></li>
          <li><a href="#contact">Yhteydenotto</a></li>
        </ul>
      </nav>
      
      {/* Etusivu */}
      <header className="hero">
        <h1>Tomi Ruotsalainen</h1>
        <p>Tekninen asiantuntija | Koodaaja | Sijoittaja</p>
      </header>

      {/* Osaaminen */}
      <section id="about" className="section">
        <h2>Osaaminen & Kokemus</h2>
        <p>11+ vuotta kokemusta talotekniikka-alalta. Talotekniikan insinööriopiskelija.</p>
      </section>
      
      {/* Projektit */}
      <section id="projects" className="section">
        <h2>Projektit</h2>
        <p>Esimerkkejä koodaus- ja mallinnusprojekteista.</p>
      </section>
      
      {/* Mielenkiinnon kohteet */}
      <section id="interests" className="section">
        <h2>Mielenkiinnon kohteet</h2>
        <p>Koodaus, sijoittaminen ja 3D-tulostaminen.</p>
      </section>
      
      {/* Yhteydenotto */}
      <section id="contact" className="section">
        <h2>Ota yhteyttä</h2>
        <p>Voit ottaa yhteyttä sähköpostilla tai sosiaalisessa mediassa.</p>
      </section>
    </div>
  );
}

export default App;
