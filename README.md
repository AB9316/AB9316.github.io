<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Portfolio Ayoub</title>
  <link rel="stylesheet" href="Portfolio.css">
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">
  <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;500;600;700;800&display=swap" rel="stylesheet">
</head>
<body>
  
  <header class="header">
    <div class="container">
      <div class="header-content">
        <h1 class="logo">Portfolio<span class="accent">.</span></h1>
        

        <nav class="desktop-nav">
          <ul>
            <li><a href="#a-propos">À propos</a></li>
            <li><a href="#bd">Base de Données</a></li>
            <li><a href="#tetris">Jeu Tetris</a></li>
            <li><a href="#muraille">Muraille de Chine</a></li>
            <li><a href="#yams">Jeu Yams</a></li>
            <li><a href="#seniors">Plateforme Seniors</a></li>
          </ul>
        </nav>
  
  
    </div>
  </header>


  <section class="hero">
    <div class="container">
      <div class="hero-content">
        <h1 class="hero-title">Ayoub<span class="accent">.</span></h1>
        <p class="hero-subtitle">Étudiant en BUT Informatique à l'Université Gustave Eiffel</p>
        <p class="hero-text">Passionné par la cybersécurité et le développement web</p>
        <div class="hero-buttons">
          <a href="#a-propos" class="btn btn-primary">En savoir plus</a>
          <a href="#contact" class="btn btn-outline">Contact</a>
        </div>
      </div>
    </div>

    <div class="hero-shapes">
      <div class="shape shape-1"></div>
      <div class="shape shape-2"></div>
      <div class="shape shape-3"></div>
    </div>
  </section>

  
  <section id="a-propos" class="about section">
    <div class="container">
      <h2 class="section-title">À propos de moi</h2>
      
      <div class="about-grid">
        <div class="about-text">
          <div class="card">
            <p class="about-paragraph">
              Je m'appelle <strong>Ayoub Kherbouche</strong> et je suis actuellement en 
              première année de BUT Informatique à l'Université Gustave Eiffel. 
              Je suis passionné par l'informatique et, plus particulièrement, 
              par la cybersécurité, un domaine dans lequel je souhaite 
              travailler plus tard.
            </p>
            <p class="about-paragraph">
              Ma curiosité et mon enthousiasme pour le développement de projets 
              informatiques m'ont poussé à explorer de nombreuses technologies 
              et langages de programmation. Dans ce portfolio, je vous présente 
              quelques-unes de mes réalisations.
            </p>
            <p class="about-paragraph">
              En dehors de la programmation, j'aime également me documenter 
              sur les avancées technologiques et élargir mes connaissances 
              en cybersécurité afin de mieux comprendre et anticiper les 
              menaces informatiques.
            </p>
          </div>
        </div>
        
        <div class="about-skills">
          <div class="card image-card">
            <img src="https://images.unsplash.com/photo-1461749280684-dccba630e2f6?auto=format&fit=crop&w=800" alt="Développeur informatique">
            <div class="overlay">
              <h3>Mes compétences</h3>
              <div class="skill-tags">
                <span class="tag">HTML/CSS</span>
                <span class="tag">JavaScript</span>
                <span class="tag">SQL</span>
                <span class="tag">Java</span>
                <span class="tag">Cybersécurité</span>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>


  <section class="projects section bg-light">
    <div class="container">
      <h2 class="section-title">Mes Projets</h2>
      
      <div class="projects-grid">

        <div class="project-card" id="bd">
          <div class="project-image">
            <img src="https://images.unsplash.com/photo-1487058792275-0ad4aaf24ca7?auto=format&fit=crop&w=800" alt="Base de données">
          </div>
          <div class="project-content">
            <h3 class="project-title">Création d'une Base de Données</h3>
            <div class="project-tags">
              <span class="tag">MySQL</span>
              <span class="tag">PostgreSQL</span>
              <span class="tag">SQL</span>
              <span class="tag">Bases de données</span>
            </div>
            <p class="project-description">
              Dans ce projet, j'ai travaillé sur la conception et la mise en place d'une base de données complète pour gérer efficacement les informations des utilisateurs et des produits. J'ai utilisé des outils et technologies tels que MySQL, PostgreSQL ou SQL Server (selon le besoin) afin d'assurer une structure solide, ainsi qu'une bonne performance pour les requêtes complexes.
            </p>
            <p class="project-description">
              Cette expérience m'a permis de développer mes compétences en modélisation de données et optimisation des requêtes SQL, créant ainsi une base solide pour mes futurs projets.
            </p>
            <a href="#bd-detail" class="project-link">En savoir plus</a>
          </div>
        </div>

        <div class="project-card" id="tetris">
          <div class="project-image">
           <img src="Tetris.png" alt="Description de l'image">

          </div>
          <div class="project-content">
            <h3 class="project-title">Codage du Jeu Tetris</h3>
            <div class="project-tags">
              <span class="tag">Python</span>
              <span class="tag">Programmation orientée objet</span>
              <span class="tag">Logique de jeu</span>
              <span class="tag">Interface utilisateur</span>
            </div>
            <p class="project-description">
              Dans ce projet, j'ai codé une version simplifiée du célèbre jeu Tetris en utilisant Python. J'ai commencé par définir la logique du jeu : la création et le déplacement des pièces (tétrominos), la détection de collisions, ainsi que la gestion du score.
            </p>
            <p class="project-description">
              Le principal défi résidait dans la manipulation de la grille de jeu (placement des blocs, suppression des lignes complètes, etc.) et l'implémentation des différentes formes de tétrominos (I, O, T, S, Z, J, L).
            </p>
            <a href="#tetris-detail" class="project-link">En savoir plus</a>
            

          </div>
        </div>


        <div class="project-card" id="muraille">
          <div class="project-image">
            <img src="https://images.unsplash.com/photo-1508804185872-d7badad00f7d?auto=format&fit=crop&w=800" alt="Muraille de Chine">
          </div>
          <div class="project-content">
            <h3 class="project-title">Création d'un Site Web sur la Muraille de Chine</h3>
            <div class="project-tags">
              <span class="tag">HTML</span>
              <span class="tag">CSS</span>
              <span class="tag">Figma</span>
              <span class="tag">Responsive Design</span>
            </div>
            <p class="project-description">
              J'ai réalisé un site Web présentant l'histoire et les caractéristiques de la Grande Muraille de Chine. Le site est structuré en plusieurs pages, avec des sections consacrées à l'historique, à la géographie et à l'impact culturel de cet édifice.
            </p>
            <p class="project-description">
              Pour ce projet, j'ai commencé par créer une maquette détaillée sur Figma, ce qui m'a permis de planifier l'architecture et le design du site avant de passer à l'implémentation. J'ai ensuite développé le site en utilisant uniquement HTML et CSS.
            </p>
            <a href="#muraille-detail" class="project-link">En savoir plus</a>
          </div>
        </div>
      

        <div class="project-card" id="yams">
          <div class="project-image">
            <img src="https://images.unsplash.com/photo-1521791136064-7986c2920216?auto=format&fit=crop&w=800" alt="Jeu Yams Java">
          </div>
          <div class="project-content">
            <h3 class="project-title">Jeu Yams en Java</h3>
            <div class="project-tags">
              <span class="tag">Java</span>
              <span class="tag">Console</span>
              <span class="tag">Jeu</span>
              <span class="tag">POO</span>
            </div>
            <p class="project-description">
              Projet réalisé au deuxième semestre : un jeu de Yams programmé en Java. Il comprend la gestion des dés, du score et des règles officielles, en utilisant la programmation orientée objet.
            </p>
            <p class="project-description">
              Ce projet m’a permis d’approfondir ma maîtrise de Java et de structurer un programme en plusieurs classes de manière claire et modulaire.
            </p>
            <a href="#yams-detail" class="project-link">En savoir plus</a>
          </div>
        </div>


    
        <div class="project-card" id="seniors">
          <div class="project-image">
            <img src="Senior_meet2.png" alt="Description de l'image">
          </div>
          <div class="project-content">
            <h3 class="project-title">Plateforme Web pour les Seniors</h3>
            <div class="project-tags">
              <span class="tag">HTML</span>
              <span class="tag">CSS</span>
              <span class="tag">Chat</span>
              <span class="tag">Calendrier</span>
              <span class="tag">Agenda</span>
            </div>
            <p class="project-description">
              Site web destiné aux seniors intégrant un système de messagerie, un calendrier interactif et un agenda personnel. L’interface est simple et accessible, conçue pour répondre aux besoins des personnes âgées.
            </p>
            <p class="project-description">
              Ce projet m’a permis de réfléchir à l’ergonomie, à la simplicité d’utilisation et aux défis de l’accessibilité numérique.
            </p>
            <a href="#seniors-detail" class="project-link">En savoir plus</a>
          </div>
        </div>

      </div>
    </div>
  </section>

  
  <section id="bd-detail" class="project-detail">
    <div class="container">
      <h2 class="section-title bordered">Création d'une Base de Données</h2>
      
      <div class="detail-grid">
        <div class="detail-content">
          <div class="card">
            <p>
              Dans ce projet, j'ai travaillé sur la conception et la mise en place d'une base de données complète pour gérer efficacement les informations des utilisateurs et des produits. J'ai utilisé des outils et technologies tels que MySQL, PostgreSQL ou SQL Server (selon le besoin) afin d'assurer une structure solide, ainsi qu'une bonne performance pour les requêtes complexes.
            </p>
            <p>
              Ce projet m'a permis de développer mes compétences en modélisation de données, optimisation des requêtes SQL et création d'index. J'ai appris à concevoir des bases de données performantes qui répondent aux besoins spécifiques des applications tout en assurant l'intégrité des données.
            </p>
            <p>
              J'ai également pu explorer différentes méthodes d'accès aux données et comprendre les avantages et inconvénients de différentes approches de modélisation selon les cas d'usage.
            </p>
          </div>
        </div>
        
        <div class="detail-images">
          <div class="image-grid">
            <img src="https://images.unsplash.com/photo-1487058792275-0ad4aaf24ca7?auto=format&fit=crop&w=800" alt="Code de base de données" class="detail-image">
            <img src="https://images.unsplash.com/photo-1486312338219-ce68d2c6f44d?auto=format&fit=crop&w=800" alt="Personne travaillant sur un ordinateur" class="detail-image">
          </div>
        </div>
      </div>
    </div>
  </section>

  <section id="tetris-detail" class="project-detail">
    <div class="container">
      <h2 class="section-title bordered">Codage du Jeu Tetris en Python</h2>
      
      <div class="detail-grid">
        <div class="detail-content">
          <div class="card">
            <p>
              Dans ce projet, j'ai codé une version simplifiée du célèbre jeu Tetris en utilisant Python. J'ai commencé par définir la logique du jeu : la création et le déplacement des pièces (tétrominos), la détection de collisions, ainsi que la gestion du score.
            </p>
            <p>
              Le principal défi résidait dans la manipulation de la grille de jeu (placement des blocs, suppression des lignes complètes, etc.) et l'implémentation des différentes formes de tétrominos (I, O, T, S, Z, J, L).
            </p>
            <p>
              Au final, ce projet m'a permis d'approfondir ma compréhension de la programmation orientée objet en Python et de la logique de jeu. J'ai également eu l'opportunité de travailler sur des aspects importants tels que la gestion des collisions, des rotations des pièces et de l'interface utilisateur avec la bibliothèque Pygame.
            </p>
          </div>
        </div>
        
        <div class="detail-images">
          <div class="image-grid">
            <img src="Tetris.png" alt="Description de l'image">

          </div>
        </div>
      </div>
    </div>
  </section>

  <section id="muraille-detail" class="project-detail">
    <div class="container">
      <h2 class="section-title bordered">Création d'un Site Web sur la Muraille de Chine</h2>
      
      <div class="detail-grid">
        <div class="detail-content">
          <div class="card">
            <p>
              J'ai réalisé un site Web présentant l'histoire et les caractéristiques de la Grande Muraille de Chine. Le site est structuré en plusieurs pages, avec des sections consacrées à l'historique, à la géographie et à l'impact culturel de cet édifice.
            </p>
            <p>
              Pour ce projet, j'ai commencé par créer une maquette détaillée sur Figma, ce qui m'a permis de planifier l'architecture et le design du site avant de passer à l'implémentation. J'ai ensuite développé le site en utilisant uniquement HTML et CSS , en mettant l'accent sur un design responsive et une navigation intuitive.
            </p>
            <p>
              Ce projet m'a permis de renforcer mes compétences en intégration web (HTML/CSS) et d'apprendre à optimiser un site pour une bonne expérience utilisateur. J'ai également étudié les principes du responsive design pour assurer une expérience fluide sur tous les appareils.
            </p>
          </div>
        </div>
        
        <div class="detail-images">
          <div class="image-grid">
            <img src="https://images.unsplash.com/photo-1508804185872-d7badad00f7d?auto=format&fit=crop&w=800" alt="Grande Muraille de Chine" class="detail-image">
            <img src="https://images.unsplash.com/photo-1498050108023-c5249f4df085?auto=format&fit=crop&w=800" alt="Code sur un ordinateur" class="detail-image">
          </div>
        </div>
      </div>
    </div>
  </section>


  <section id="yams-detail" class="project-detail">
    <div class="container">
      <h2 class="section-title bordered">Jeu Yams en Java</h2>
      <div class="detail-grid">
        <div class="detail-content">
          <div class="card">
            <p>
              Le jeu de Yams que j’ai codé en Java repose sur une implémentation console. Chaque joueur peut lancer les dés, choisir quelles combinaisons conserver, et son score est calculé automatiquement selon les règles classiques.
            </p>
            <p>
              Ce projet m’a permis de développer mes compétences en programmation orientée objet et en conception de classes pour représenter les dés, le joueur et le plateau de jeu.
            </p>
            <p>
              Le projet utilise des boucles, des tableaux et des classes Java, ce qui a renforcé mes bases en algorithmique et structuration de projet.
            </p>
          </div>
        </div>
        <div class="detail-images">
          <div class="image-grid">
            <img src="https://images.unsplash.com/photo-1521791136064-7986c2920216?auto=format&fit=crop&w=800" alt="Code Java" class="detail-image">
          </div>
        </div>
      </div>
    </div>
  </section>


  <section id="seniors-detail" class="project-detail">
    <div class="container">
      <h2 class="section-title bordered">Plateforme Web pour les Seniors</h2>
      <div class="detail-grid">
        <div class="detail-content">
          <div class="card">
            <p>
              Cette plateforme vise à faciliter la vie numérique des personnes âgées. Elle propose une messagerie intuitive, un calendrier interactif et un agenda personnel pour suivre les rendez-vous et tâches.
            </p>
            <p>
              J’ai conçu cette interface en HTML/CSS avec un design clair et accessible. Chaque fonctionnalité est pensée pour minimiser les clics et maximiser la lisibilité.
            </p>
            <p>
              Ce projet m’a permis de réfléchir à l'accessibilité web et à la création de services numériques inclusifs.
            </p>
          </div>
        </div>
        <div class="detail-images">
          <div class="image-grid">
            <img src="Senior_meet2.png" alt="Description de l'image">
            <img src="Senior_meet.png" alt="Description de l'image">
          </div>
        </div>
      </div>
    </div>
  </section>


 
  <footer class="footer" id="contact">
    <div class="container">
      <div class="footer-grid">
        <div class="footer-about">
          <h3 class="footer-title">Portfolio<span class="accent">.</span></h3>
          <p>
            Portfolio professionnel d'Ayoub, étudiant en BUT Informatique
            à l'Université Gustave Eiffel.
          </p>
        </div>
        
        <div class="footer-nav">
          <h3 class="footer-subtitle">Navigation</h3>
          <ul>
            <li><a href="#a-propos">À propos</a></li>
            <li><a href="#bd">Base de Données</a></li>
            <li><a href="#tetris">Jeu Tetris</a></li>
            <li><a href="#muraille">Muraille de Chine</a></li>
            <li><a href="#yams">Jeu Yams</a></li>
            <li><a href="#seniors">Plateforme Seniors</a></li>
          </ul>
        </div>
        
        <div class="footer-contact">
          <h3 class="footer-subtitle">Contact</h3>
          <ul>
            <li><strong>Email:</strong> ayoubkherbouche93160@gmail.com</li>
            <li><strong>LinkedIn:</strong><a href="https://www.linkedin.com/in/ayoub-kherbouche-311087338/">linkedIn</a></li>
            <a href="cv.pdf" target="_blank" style="padding: 10px; background-color: #007BFF; color: white; text-decoration: none; border-radius: 5px;">📄 Télécharger mon CV</a>


          </ul>
        </div>
      </div>
    </div>
  </footer>
</body>
</html>
