# SLM_1920
Statistical Learning Methods - laboratories repository

## Zasady konkursu SRD Semestr zimowy 19/20
### Zespoły
Należy dobrać się w zespoły złożone z 1-3 osób. Proszę nazwać zespół (nazwa pojawi się w tabeli z wynikami). Proszę nie używać danych osobowych w nazwach (bo RODO). 

### Zbiór danych i cel konkursu
Celem konkursu jest uzyskanie jak największego **accuracy** (procent poprawnie zaklasyfikowanych obserwacji [TP+TN/(TP+TN+FP+FN)]) w klasyfikacji zmiennej celu **IsIPA**. Do stworzenia modelu proszę wykorzystać zbiór danych **IPA.csv**, natomiast finalną predykcję należy wykonanać na zbiorze **IPA_test.csv**. Opis zbioru znajduje się w pliku **IPA_description.txt**.

### Wyniki
Wyniki należy przesłać na adres lukasz.krainski123@gmail.com. Grupa nr 100 może wysyłać wyniki do godziny 18:50, natomiast grupa nr 101 do 20:40. Wiadomości otrzymane po określonych godzinach nie będą przyjmowane. W treści maila należy podać nazwę grupy oraz imiona i nazwiska członków. Jako załączniki należy zamieścić:
1. Skrypt R/Python/Julia ze stworzonym kodem
2. Plik CSV o nazwie **[nazwa_grupy]_IPA_prediction.csv** zawierający jedną kolumnę o nazwie **Prediction** i 5000 obserwacji z wartościami 1/0 lub TRUE/FALSE oznaczających predykcję dla kolejnych wierszy ze zbioru testowego **IPA_test.csv**. 

Proszę dokładnie sprawdzić czy kolejność predykcji zgadza się z kolejnością obserwacji w zbiorze testowym.

Tabela z rankingiem zespołów pojawi się na GitHubie w poniższym pliku README. Najlepszy zespół otrzyma dodatkowe 5 punktów, kolejny 4 punkty, itd.

Życzę powodzenia. 

# Wyniki konkursu
Mam nadzieję, że podobało się Państwu zadanie i była to dobra okazja, żeby wykorzystać metody poznane na zajęciach. Poniżej zamieszczam wyniki dla obu grup ćwiczeniowych i komentarz.

Wśród wykorzystanych modeli przeważają metody oparte na drzewach decyzyjnych. 
* Warto zauważyć, że wysoki wynik uzyskały prostsze algorytmy np. CART. 
  - Zbiór testowy był losowo wybraną częścią głównego zbioru ze strony Brewer's Friend, więc charakterystyka danych train vs. test powinna być podobna (z zajęć powinni Państwo pamiętać, że pojedyncze drzewa mają problem ze stabilnością, ale tu problem nie występuje). 
  - Dodatkowo wygląda na to, że predyktory wyjaśniają dosyć dużą część wariancji zmiennej celu i bardziej skomplikowane metody (np. ensemble models: Random Forest i Boosting) nie "wyciskają" dużo więcej z danych. 
* Z drugiej strony, to właśnie modele ensemble wygrały w obu grupach. Proszę też pamiętać, że podałem klasę modeli, ale kluczowa dla wysokiego accuracy było dopasowanie hiperparametrów i wykorzystanie odpowiednich pakietów (niektórzy stosowali biblioteki, które nie były omawiane na zajęciach).
### Grupa 100

| Miejsce | Punkty | Zespół            | Accuracy | Język  | Model                | Komentarz                                           |
|---------|--------|-------------------|----------|--------|----------------------|-----------------------------------------------------|
| 1       | 5pkt   | Zespół R          | 86.92%   | R      | Random Forest        | Gratuluję wygranej :)                               |
| 2       | 4pkt   | Nasza Fajna Grupa | 86.44%   | R      | CART Tree            | Proszę pamiętać, że 1 to TRUE a 0 to FALSE                                                    |
| 3       | 3pkt   | Kuflowe Mocne     | 86.20%   | R      | Random Forest        |                                                     |
| 4       | 2pkt   | Poziomki          | 83.96%   | R      | CHAID Tree           |                                                     |
| 5       | 1pkt   | Jupyter           | 86.41%*  | Python | KNeighborsClassifier | *Model zająłby 3. miejsce, gdybym dostał predykcję. |

### Grupa 101

| Miejsce | Punkty | Zespół           | Accuracy | Język | Model               | Komentarz             |
|---------|--------|------------------|----------|-------|---------------------|-----------------------|
| 1       | 5pkt   | JMP              | 86.62%   | R     | GBoosted Trees      | Gratuluję wygranej :) |
| 2       | 4pkt   | Team Drzewo      | 86.02%   | R     | CART Tree           |                       |
| 3       | 3pkt   | Imp Bridge       | 85.84%   | R     | GBoosted Trees      |                       |
| 4       | 2pkt   | Decyzyjne Kocury | 84.62%   | R     | Random Forest       |                       |
| 5       | 1pkt   | Gołąbki          | 78.38%   | R     | Logistic Regression |                       |
