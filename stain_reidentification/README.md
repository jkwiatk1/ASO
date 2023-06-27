# Cel i analiza tematu

* Celem jest stworzenie modeli służących do reidentyfikacji plam zabrudzeń. 
* Reidentyfikacja jest niezbędna w celu śledzenia poruszających się obiektów w sekwencji klatek.
* Reidentyfikację można sprowadzić do problemu znalezienia 'najbliższego' innego zdjęcia. 
* W tym celu wykorzystano poniższe modele:
  - VGG16 
  - ResNet50
  - EfficientNet B7

# Zbiór danych

Zbiór [Fabric Stain Dataset](https://www.kaggle.com/datasets/priemshpathirana/fabric-stain-dataset) powstał z myślą o problemie klasyfikacji. Możliwe jest wykorzystanie go również w celach reidentyfikacji. Zawiera on 466 zdjęć podzielonych na 2 kategorie: 68 zdjęć tkanin bez 
defektów (14.59% zbioru) oraz 398 zdjęć (85.41% zbioru) tkanin z plamami atramentu, brudu, oraz oleju (bez podziału na podkategorie). Zdjęcia są w dwóch rozdzielczościach: 1488x1984 (305 zdjęć) oraz 1984x1488 (161 
zdjęć).

# Realizacja
Uzyskane wyniki, analiza wybranych architektur oraz realizacja zostały dokładnie opisane w dokumentacji:
https://github.com/jkwiatk1/ASO/blob/main/stain_reidentification/Etap3_4/ASO_doc_koncowa.pdf