<style>
	h1, figure, p {
		text-align: center;
		margin: 0 auto;
	}

	h1 {
		font-size: 2.8em;
		text-transform: uppercase;
		font-weight: 700;
		margin: 0 0 0.5em 0;
	}

	figure {
		margin: 0 0 1em 0;
	}

	img {
		width: 100%;
		max-width: 400px;
		margin: 0 0 1em 0;
	}

	p {
		margin: 1em auto;
	}

	@media (min-width: 480px) {
		h1 {
			font-size: 4em;
		}
	}
</style>

<svelte:head>
	<title>Sapper project template</title>
</svelte:head>

<h1>Yo M'sieur Triggeur!</h1>

<figure>
	<img alt='Borat' src='great-success.png'>
	<figcaption>HIGH FIVE!</figcaption>
</figure>

<p><strong>Nikta mérenlimo</strong></p>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.0-beta2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-BmbxuPwQa2lc/FVzBcNJ7UAyJxM6wuqIj61tLrc4wSX0szH/Ev+nYRRuWlolflfl" crossorigin="anonymous">
</head>
<body>
    <nav class="navbar navbar-expand-lg navbar-light bg-warning">
        <div class="container-fluid">
          <a class="navbar-brand" href="#"><img src="../intro/img/logo.png" alt="logo MolenGeek"></a>
          <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="collapse navbar-collapse" id="navbarNav">
            <ul class="navbar-nav">
              <li class="nav-item">
                <a class="nav-link" aria-current="page" href="#">Carousel</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#">Textes random</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#">Collapse</a>
              </li>
            </ul>
          </div>
        </div>
      </nav>

    <div class="container border border-1 border-dark mt-4 p-3 w-75">
        
        <div id="carouselExampleIndicators" class="carousel slide" data-bs-ride="carousel">
            <div class="carousel-indicators">
              <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
              <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="1" aria-label="Slide 2"></button>
              <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="2" aria-label="Slide 3"></button>
            </div>
            <div class="carousel-inner">
              <div class="carousel-item active">
                <img src="./img/space.png" class="d-block w-100" alt="Vaisseau">

                <div class="carousel-caption d-none d-md-block">
                    <h5>Vaisseau</h5>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
                  </div>

              </div>
              <div class="carousel-item">
                <img src="./img/sky_girl.jpg" class="d-block w-100" alt="Sky girl">

                <div class="carousel-caption d-none d-md-block">
                    <h5>Sky girl</h5>
                    <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit.</p>
                  </div>

              </div>
              <div class="carousel-item">
                <img src="./img/autruche.jpg" class="d-block w-100" alt="Autruche">

                <div class="carousel-caption d-none d-md-block">
                    <h5>Autruche</h5>
                    <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit.</p>
                  </div>

              </div>
            </div>
            <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleIndicators"  data-bs-slide="prev">
              <span class="carousel-control-prev-icon" aria-hidden="true"></span>
              <span class="visually-hidden">Previous</span>
            </button>
            <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleIndicators"  data-bs-slide="next">
              <span class="carousel-control-next-icon" aria-hidden="true"></span>
              <span class="visually-hidden">Next</span>
            </button>
          </div>
    </div>

    <div class="container border border-1 border-danger mt-4 p-3 w-75">
        
        <h1>Un peu de contenu</h1>

        <p class="bg-primary p-5 w-75 ms-auto">Lorem ipsum, dolor sit amet consectetur adipisicing elit. Accusantium natus voluptatum delectus praesentium doloremque ut eaque pariatur molestias magni molestiae corrupti veritatis ipsa voluptas optio, voluptate repellat possimus at perferendis velit. Vel quo saepe autem libero vero asperiores incidunt. Vero reprehenderit rem qui fugit labore, totam porro iure odit saepe officia culpa tempore praesentium suscipit nam dignissimos debitis, reiciendis molestiae consectetur quam ex dolor architecto aliquid. Unde quo quidem, nobis architecto in repellat delectus veritatis voluptatibus sequi quaerat magni? Necessitatibus voluptatum laudantium adipisci quod sequi animi dicta dignissimos magnam ea asperiores recusandae ex eaque officia, fugit voluptas. Dolor animi, odit maxime dolore numquam eveniet provident veniam cupiditate vel vero perspiciatis, voluptate necessitatibus error. Beatae harum nemo totam quae, quos eum tenetur neque quod officiis esse ipsa libero eveniet inventore, repellendus aperiam quo? Repellendus sapiente aliquid ducimus dolorem sit, veritatis maiores aperiam, atque, id exercitationem voluptate culpa! Placeat assumenda soluta veniam sit, vel nemo libero vero provident ex autem perspiciatis magni vitae, sapiente, obcaecati animi commodi dignissimos dicta cupiditate ullam amet alias aliquam architecto pariatur! Similique assumenda facere officia nihil cum aut repellendus rem pariatur incidunt perferendis nobis ratione sint deserunt velit veritatis quod, illum veniam est reprehenderit? Omnis, pariatur saepe.</p>
        
        <p class="text-danger mx-auto w-75 p-5">Lorem ipsum dolor sit amet consectetur adipisicing elit. Eos est, consectetur error laborum deleniti dolorem rem impedit commodi iure rerum fugiat porro, quisquam nihil similique, voluptatibus aut pariatur modi accusantium nam quibusdam minima maxime! Impedit, aut voluptatibus? Hic dignissimos rem fugiat aspernatur cum? Facere alias error deleniti! Error qui quisquam deleniti, quaerat beatae inventore, suscipit vel obcaecati molestiae, quasi facere quam. Aliquid praesentium et placeat blanditiis accusamus, voluptates magnam ut velit cupiditate ex optio minus, earum mollitia repellendus beatae saepe odio quibusdam provident dignissimos perferendis dicta sapiente doloremque accusantium! Sequi, reprehenderit! Animi distinctio repellat aspernatur recusandae, possimus consequuntur! Earum minus officiis molestiae dolores. Velit, eaque reprehenderit? Unde corrupti iste quam, similique libero quia impedit non vel minus! Officia sint illum praesentium magni ducimus, laborum assumenda molestias a provident eos iusto deserunt obcaecati similique odio rerum quae, nemo minima, nihil porro?</p>
        
        <p class="text-info me-auto w-75">Lorem ipsum dolor sit amet consectetur adipisicing elit. Repellendus blanditiis, veritatis maiores expedita veniam, id voluptas minima quam, iure quis deleniti odit perferendis. Beatae animi ipsum veritatis minima praesentium itaque, eos repellat iure est nisi vero unde facere! Repellat nisi odit placeat, corporis at consequuntur velit nesciunt incidunt quaerat architecto itaque vitae iste blanditiis voluptates ipsa explicabo nemo eos, nostrum voluptatem deserunt! Tempore facere nam dolor commodi, veritatis animi a molestiae nemo cupiditate quam ab saepe, doloremque ducimus aliquid architecto totam expedita dicta voluptatem magnam quas sint mollitia nulla. Atque placeat necessitatibus voluptate, ad molestiae beatae quisquam expedita adipisci dolore assumenda! Atque repudiandae voluptate ipsa, aut, incidunt sit officiis, rem minima esse odio mollitia cum facilis. Sunt blanditiis minus, magni totam natus autem suscipit accusamus voluptates? Eligendi, vero minima? Quibusdam distinctio at natus odio fugit velit. Officiis in aperiam pariatur aut quidem a quod placeat debitis. Quos totam aperiam nesciunt perspiciatis molestiae voluptas consectetur ipsum quasi aspernatur rerum asperiores doloribus non, inventore laborum cumque quaerat. Natus, harum facere vel reprehenderit sit modi aspernatur dolores necessitatibus veniam eaque earum! Atque, odio quam! Molestiae sint ad ex harum vel nihil doloremque quae! Dolorem velit id officia consequatur, harum tenetur placeat repellendus perspiciatis quasi dolor tempora ipsum ab voluptate explicabo ipsam ut. Dolor qui est vero fuga quasi tempore, dolorum consectetur sunt soluta quam eius consequuntur expedita nisi voluptatum corporis adipisci, deleniti temporibus aliquid blanditiis illum, commodi dignissimos placeat quis rem. Earum at doloribus in iusto amet repudiandae natus rerum illo. Facere animi soluta quidem corporis ea, eaque nam aut earum repellendus fugit eveniet consequatur dolores quaerat numquam cupiditate iste fugiat cum accusantium similique impedit. Quod, unde quos fuga eaque consequuntur, rerum iure quaerat amet repellat explicabo qui, sed impedit? Corporis a voluptatibus harum similique beatae quasi sed, perferendis nostrum. Delectus, dolorem pariatur?</p>
        
    </div>

    <div class="container border border-1 border-warning mt-4 p-3 w-75">
        
        <h1>Tu veux des infos sur l'un ou l'autre sujet ?</h1>

        <div class="accordion" id="accordionExample">
            <div class="accordion-item">
              <h2 class="accordion-header" id="headingOne">
                <button class="accordion-button" type="button" data-bs-toggle="collapse" data-bs-target="#collapseOne" aria-expanded="true" aria-controls="collapseOne">
                  Jeux vidéo
                </button>
              </h2>
              <div id="collapseOne" class="accordion-collapse collapse show" aria-labelledby="headingOne" data-bs-parent="#accordionExample">
                <div class="accordion-body">
                
                    <p>Un jeu vidéo est un jeu électronique doté d'une interface utilisateur permettant une interaction humaine ludique en générant un retour visuel sur un dispositif vidéo. Le joueur de jeu vidéo dispose de périphériques pour agir sur le jeu et percevoir les conséquences de ses actes sur un environnement virtuel. Le mot « vidéo » dans le jeu vidéo fait traditionnellement référence à un dispositif d'affichage de trame, mais, à la suite de la vulgarisation du terme, il implique désormais tout type de dispositif d'affichage.</p>

                    <p>Les systèmes électroniques utilisés pour jouer à des jeux vidéo, ou plates-formes, peuvent être aussi bien des ordinateurs de bureau que de petits appareils portables, tels la borne d'arcade, la console portable, l'ordinateur portable ou le smartphone. Les jeux vidéo spécialisés tels que les jeux d'arcade, auparavant communs, ont vu leur usage progressivement diminuer. Le jeu vidéo est aujourd'hui considéré comme une industrie et parfois envisagé comme une forme d'art.</p>
                    
                    <p>Les jeux vidéo utilisent comme périphérique d'entrée un contrôleur de jeu, qui varie selon les plates-formes. Un contrôleur peut ainsi être constitué d'un unique bouton et d'une manette de jeu, ou disposer d'une douzaine de boutons et d'un ou plusieurs joystick. Les premiers jeux sur ordinateurs personnels requéraient souvent l'achat d'un joystick, tandis que les jeux modernes sur ordinateur permettent ou imposent au joueur d'utiliser un clavier et une souris simultanément.</p>
                    
                    <p>Dans les années 2010, de nouvelles méthodes d'entrée ont émergé, comme l'observation du joueur par caméra, la détection de mouvements de périphériques tenus en mains pour les consoles de jeux vidéo, ou les écrans tactiles sur les appareils mobiles. De même, de nouvelles formes de retours sont apparues : visuels, comme la vision 3D ou en relief (avec ou sans lunettes stéréoscopiques), tactiles, avec des terminaux vibrants (sièges, volants, etc.), ou pilotés (sièges inclinables simulant l’accélération, la rotation et le freinage d'un engin).</p>
                </div>
                </div>
              </div>
            </div>
            <div class="accordion-item">
              <h2 class="accordion-header" id="headingTwo">
                <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#collapseTwo" aria-expanded="false" aria-controls="collapseTwo">
                  Musique
                </button>
              </h2>
              <div id="collapseTwo" class="accordion-collapse collapse" aria-labelledby="headingTwo" data-bs-parent="#accordionExample">
                <div class="accordion-body">
                
                    <p>Un jeu vidéo est un jeu électronique doté d'une interface utilisateur permettant une interaction humaine ludique en générant un retour visuel sur un dispositif vidéo. Le joueur de jeu vidéo dispose de périphériques pour agir sur le jeu et percevoir les conséquences de ses actes sur un environnement virtuel. Le mot « vidéo » dans le jeu vidéo fait traditionnellement référence à un dispositif d'affichage de trame, mais, à la suite de la vulgarisation du terme, il implique désormais tout type de dispositif d'affichage.</p>

                    <p>Les systèmes électroniques utilisés pour jouer à des jeux vidéo, ou plates-formes, peuvent être aussi bien des ordinateurs de bureau que de petits appareils portables, tels la borne d'arcade, la console portable, l'ordinateur portable ou le smartphone. Les jeux vidéo spécialisés tels que les jeux d'arcade, auparavant communs, ont vu leur usage progressivement diminuer. Le jeu vidéo est aujourd'hui considéré comme une industrie et parfois envisagé comme une forme d'art.</p>
                    
                    <p>Les jeux vidéo utilisent comme périphérique d'entrée un contrôleur de jeu, qui varie selon les plates-formes. Un contrôleur peut ainsi être constitué d'un unique bouton et d'une manette de jeu, ou disposer d'une douzaine de boutons et d'un ou plusieurs joystick. Les premiers jeux sur ordinateurs personnels requéraient souvent l'achat d'un joystick, tandis que les jeux modernes sur ordinateur permettent ou imposent au joueur d'utiliser un clavier et une souris simultanément.</p>
                    
                    <p>Dans les années 2010, de nouvelles méthodes d'entrée ont émergé, comme l'observation du joueur par caméra, la détection de mouvements de périphériques tenus en mains pour les consoles de jeux vidéo, ou les écrans tactiles sur les appareils mobiles. De même, de nouvelles formes de retours sont apparues : visuels, comme la vision 3D ou en relief (avec ou sans lunettes stéréoscopiques), tactiles, avec des terminaux vibrants (sièges, volants, etc.), ou pilotés (sièges inclinables simulant l’accélération, la rotation et le freinage d'un engin).</p>
                </div>
              </div>
            </div>
            <div class="accordion-item">
              <h2 class="accordion-header" id="headingThree">
                <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#collapseThree" aria-expanded="false" aria-controls="collapseThree">
                  Dessin
                </button>
              </h2>
              <div id="collapseThree" class="accordion-collapse collapse" aria-labelledby="headingThree" data-bs-parent="#accordionExample">
                <div class="accordion-body">
                  It is hidden by default, until the collapse plugin adds the appropriate classes that we use to style each element. These classes control the overall appearance, as well as the showing and hiding via CSS transitions. You can modify any of this with custom CSS or overriding our default variables. It's also worth noting that just about any HTML can go within the <code>.accordion-body</code>, though the transition does limit overflow.
                </div>
              </div>
            </div>
          </div>

    </div>
    

    <p class="text-center p-5">END</p>

    
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.0-beta2/dist/js/bootstrap.bundle.min.js" integrity="sha384-b5kHyXgcpbZJO/tY9Ul7kGkf1S0CWuKcCD38l8YkeH8z8QjE0GmW1gYU5S9FOnJ0" crossorigin="anonymous"></script>
</body>
</html>
