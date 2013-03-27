CROMagento
==========

Lokalizacija Magento CE na hrvatski jezik 

Nekoliko sitnih pravila o lokaliziranju Magenta.
Lokalizicija unutar modula radi overwrite cijele lokalizacije.
Lokalizcija unutar locale foldera sa imenom modula Mage_????? radi overwrite na mjestima gdje se modul koristi, bez obzira dali se lokalizacija poziva eksplicitno ili implicitno sa imenom modula.
U slučajevima kad prijevod ne postoji ili nije definiran u locale folderu pod istim imenom kao modul (Mage_?????) uzima se posljedni prijevod ako postoji.
