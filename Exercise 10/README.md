# CSS – Stylowanie tekstu

1. Stwórz element div, a w nim element h1, span oraz p. Ze strony [lipsum.pl](http://lipsum.pl/) ściągnij kawałek przykładowego tekstu i wstaw go do paragrafu. Uzupełnij również tekst w elemencie h1 oraz span. Następnie ostyluj element zgodnie z obrazkiem poniżej. **Postaraj się jak najlepiej odzwierciedlić przykład, zwracając uwagę na szczegóły. Nie wszystko jest opisane w specyfikacji poniżej.**

	Kilka pomocnych informacji:  
	* czcionka użyta w przykładzie -   Verdana, Arial, sans-serif;
	* szerokość elementu div -   500px;
	* h1 – kolor tła: #ACC4CE, kolor tekstu: white, wielkość czionki: 20px,  kolor cienia: #878787 (generator text-shadow: 
	[lipsum.pl](http://www.cssportal.com/css3-text-shadow-generator/) )
	* span – kolor tekstu: #395075, odległość między literami: 10px
	* p – kolor tekstu: grey, wielkość czcionki: 14px; wysokość linii: 20px,  wcięcie: 20px;

	![Przykładowy tekst](images/text1.jpg)


2. Wykonaj następujące kroki w celu dodania czcionki na stronę:
	* Za pomocą strony [fontsquirrel.com](http://www.fontsquirrel.com/)  ściągnij dowolną czcionkę na dysk w formacie ttf. 
	* Następnie na tej samej stronie przejdź do generatora i załaduj do niego ściągniętą czcionkę. (Wystarczy jeden rodzaj np. regular lub bold)
	* Wybierz standard Basic i zaznacz oświadczenie, że została ściągnięta legalnie.
	* Po ściągnięciu zbioru na dysk rozpakuj archiwum. 
	* W katalogu projektu stwórz jeszcze jeden katalog pod nazwą fonts. Umieść w nim wszystkie pliki czcionki czyli (eot, ttf, woff, woff2, svg). 
	* Otwórz plik stylesheet.css i  przekopiuj kod załączający czcionkę: @font-face i ustaw odpowiednio ścieżki do katalogu fonts.
	../ - wyście z katalogu
	/fonts – wejście do katalogu fonts
	* Przetestuj w przeglądarce/przeglądarkach czy czcionka została załączona poprawnie.

3. Wejdź na stronę [google.com/fonts](https://www.google.com/fonts)  wybierz dowolną czcionkę i załącz ją do swojego projektu.
