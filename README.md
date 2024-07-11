nome_tabella: concessionario_auto_usate

marca                      VARCHAR(50)       NOT_NULL
modello                    VARCHAR(50)       NOT_NULL
potenza_cv                 SMALLINT          UNSIGNED NOT_NULL
alimentazione              VARCHAR(50)       NOT_NULL
km_percorsi                SMALLINT          UNSIGNED NOT_NULL
colore                     VARCHAR(50)       NULL
porte                      TINYINT           UNSIGNED NULL
anno_immatricolazione      YEAR              NOT_NULL
cambio                     VARCHAR(50)       NOT_NULL
trazione                   VARCHAR(50)       NULL
carrozzeria                VARCHAR(50)       NOT_NULL
prezzo                     SMALLINT          UNSIGNED NOT_NULL