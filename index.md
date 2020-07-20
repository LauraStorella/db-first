DATABASE
Nome-repo: db-first

Creare un file di testo con la struttura di una tabella di auto usate.
Inserire i nomi delle colonne, il tipo di dato e gli attributi.



STRUTTURA TABELLA DB
Nome Tabella : DB_Autovetture_usate

Nome_Colonne: ----- Formato --------- Tipo dato ---------- Tipo num ---------- Tipo str ---------- Attributo
ID   (Prim_Key)                       Num                  Int                                     Auto_incr - Unique
Marca                                 Str                                      Varchar(20)         NotNull - Auto_incr - Unique
Modello                               Str                                      Varchar(150)        NotNull
Foto                                  Str                                      Varchar(30)         Default
Targa                                 Str                                      Varchar(7)          NotNull - Unique            
Km                                    Num                  Dbl(8,2)                                NotNull
N° immatr.                            Num                  Int                                     NotNull - Unique
Anno immatr.       YYYY/MM/DD         Num                  Date                                    NotNull
Descriz.                              Str                                      Text
Costo                                 Num                  Float(7,2)                              NotNull
Disponibile                           Boolean              TinyInt                                 NotNull










Esempio DB

ID - Marca --- Modello ----- Foto ------------ Targa ---- Km ---- N° immatr. --- Anno immatr. --- Descriz. -- Costo ---- Disponib.
1    Audi      Avant-wagon   audi.png          EY486WF    81447   123XYZ         2015/02/26       testo       €          sì
2    Fiat      Fiat Punto    fiat.png          EP348YC    9902    456LKJ         06/03/2013       testo       €          sì
3    Renault   Ren. Scenic   img-default.png   AZ820NM    51889   789ASD         15/05/2015       testo       €          no



