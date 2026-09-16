setContentView - ustawia co jest głównym wyglądem ekranu i po niej dopiero działają pliki XML<br>
findViewById - szuka aktualnego layoutu po Id i go zwraca<br>
R - klasa którą Gradle generuje automatycznie przy każdym budowaniu, zawiera wszystkie Id które są w res/<br>
onCreate - pierwsza funkcja wywoływana przy tworzeniu lub odtwarzaniu aktywności<br>
super.onCreate - wywołuje wersję z klasy nadrzędnej i bez tego aplikacja nie wystartuje<br>
AndroidManifest.xml - dokument w którym są informacje o systemie czyli jak się nazywa jaką ma ikonę z jakich ekranów się składa od którego zacząć i czego potrzebuje, system czyta to przed uruchomieniem aplikacji<br>
@+id/ - odwołanie do zasobu (@) którego rodzajem jest id (id/) tworząc nowy unikalny identyfikator (+) <br>
match_parent - wartość wielkości np. layoutu, który jest pobierany od rodzica a to jest zwykle na cały ekran <br>
dp - density-independent pixel czyli jednostka, która jest niezależna od pixeli i jest przeliczana z rozdzielczości danego ekranu dla tego samego efektu dla różnych ekranów <br>
sp - scale-independent pixel czyli to samo co dp tylko dla tekstu żeby aplikacja dostosowała rozmiar do ustawień systemowych telefonu
