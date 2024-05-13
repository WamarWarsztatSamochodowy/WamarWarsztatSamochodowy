<html lang="pl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Warsztat Samochodowy WAMAR</title>
    <style>
        /* Resetowanie podstawowych stylów */
        body, h1, h2, p, ul, li {
            margin: 0;
            padding: 0;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            padding: 150px;
            color: #3;
            background-color: #e7dcd9;
        }   
	.gallery-container {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    grid-gap: 15px;
    padding: 20px;
}

.gallery-container img {
    width: 100%;
    height: auto;
    border-radius: 5px;
    box-shadow: 0 4px 8px rgba(0,0,0,0.1);
}
		
        /* Stylizacja headera */
        header {
            background: #B22222;
            color: #fff;
            padding: 20px 40px;
            text-align: center;
            margin-bottom: 20px;
        }

        /* Stylizacja nawigacji */
        nav {
            display: white;
            background: #333;
            text-align: center;
        }
        nav ul {
            list-style: none;
        }
        nav ul li {
            display: inline;
        }
        nav ul li a {
            color: white;
            padding: 10px 20px;
            display: inline-block;
            text-decoration: none;
            transition: background .3s;
        }
        nav ul li a:hover {
            background-color: #555;
        }
        
        /* Stylizacja sekcji */
        section {
            background:#808078 ;
            margin: 0 20px 20px;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }

        /* Stylizacja stopki */
        footer {
            text-align: center;
            padding: 1px;
            background-color: #333;
            color: #fff;
            position: absolute;
            bottom: 1;
            width: 90%; /* Adjust as per padding of body */
        }

        /* Responsywność (Przykład) */
        @media (max-width: 600px) {
            nav ul li {
                display: block;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Witaj w Warsztacie Samochodowym WAMAR!</h1>
        <p>Znajdujesz się na stronie lidera w naprawach samochodowych w Suwałkach.</p>
    </header>

    <nav>
        <ul>
            <li><a href="#o-nas">O nas</a></li>
            <li><a href="#uslugi">Usługi</a></li>
			<li><a href="#lakiernictwo">Lakiernictwo</a></li>
            <li><a href="#dlaczego-my">Dlaczego My?</a></li>
            <li><a href="#galeria">Galeria</a></li>
			<li><a href="#kontakt">Kontakt</a></li>
        </ul>
    </nav>

    <section id="o-nas">
        <h2>O Nas</h2>
        <p>Nasz zespół specjalistów z wieloletnim doświadczeniem gwarantuje profesjonalną obsługę i najwyższą jakość usług. Dziękujemy, że wybrałeś właśnie nas!. Twoje auto w dobrych rękach.

Warsztat Samochodowy WAMAR działa na rynku od 2001 roku, oferując kompleksowe usługi naprawcze dla szerokiej gamy marek i modeli samochodów. Nasza misja to dostarczanie niezawodnych usług, które przywrócą Twojemu pojazdowi sprawność i bezpieczeństwo. Stawiamy na ciągły rozwój naszych mechaników, którzy regularnie uczestniczą w szkoleniach technicznych, aby być na bieżąco z najnowszymi technologiami w branży motoryzacyjnej.</p>
    </section>

    <section id="uslugi">
        <h2>Nasze Usługi</h2>
        <ul>
            <li>Diagnostyka komputerowa - szybkie wykrywanie problemów dzięki nowoczesnemu sprzętowi diagnostycznemu.</li>
            <li>Naprawa mechaniczna - od drobnych napraw po generalne remonty silnika.</li>
            <li>Serwis klimatyzacji - dbamy o to, by Twoja klimatyzacja była efektywna i bezpieczna.</li>
            <li>Wymiana opon i wyważanie kół - przygotujemy Twoje auto na każdą porę roku.</li>
            <li>Przeglądy okresowe - zapewnij sobie spokój i bezpieczeństwo dzięki regularnym przeglądom technicznym.</li>
            <li>samochodowy serwis blacharski</li>
            <li>samochodowy serwis lakierniczy</li>
            <li>lakiernictwo samochodowe</li>
            <li>blacharstwo samochodowe</li>
            <li>lakiernik</li>
            <li></li>
            <li></li>
            <li></li>
            <li></li>
            <li></li>
            <li></li>
            <li></li>
	
        </ul>
    </section>

    <section id="dlaczego-my">
        <h2>Dlaczego My?</h2>
        <li>Profesjonalizm, który widać i czuć na każdym kroku:</li>
            <li>Szybki czas realizacji usług.</li>
            <li>Przejrzyste i konkurencyjne ceny.</li>
            <li>Indywidualne podejście do każdego klienta i jego potrzeb.</li>
            <li>Gwarancja na wykonane usługi.</li>


    </section>
	<section id="lakiernictwo">
        <h2>Lakiernictwo i Usługi Blacharskie</h2>
        <li>Nasz warsztat wyposażony jest w własną mieszalnię lakierów</li>
		<li>Precyzyjne dopasowanie kolorów
		<li>Oferujemy kompleksowe usługi lakiernicze oraz blacharskie<li>
		<li>Naprawy powypadkowe
		<li>enowacje starych powłok lakierniczych.</li>
    
	
	
	</section>

<section id="kontakt" style="display: flex; flex-direction: column;">
    <h2>Kontakt</h2>
    <p style="align-self: flex-start;">Jeśli masz jakiekolwiek pytania, prosimy o kontakt poprzez formularz poniżej:</p>
    <form action="sendmail.php" method="POST">
        <input type="text" name="name" placeholder="Twoje imię" required>
        <input type="email" name="email" placeholder="Twój email" required>
        <textarea name="message" placeholder="Twoja wiadomość" style="width: 15cm; height: 5cm;" required></textarea>
        <button type="submit">Wyślij Wiadomość</button>
    </form>
</section>
<section id="galeria">
    <h2>Galeria</h2>
    <div class="gallery-container">
        <img src="https://app.degoo.com/share/wTkcLzfDYgF3lY9SWqE69g" alt="Opis zdjęcia 1">
        <img src="ścieżka_do_zdjęcia_2.jpg" alt="Opis zdjęcia 2">
        <img src="ścieżka_do_zdjęcia_3.jpg" alt="Opis zdjęcia 3">
        <!-- Dodaj więcej zdjęć według potrzeb -->
    </div>
</section>




   

