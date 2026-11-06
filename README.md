# Yucatán: law history in git

Part of [lexifina/global-law](https://github.com/lexifina/global-law), one git history for every country's law: this is the law of Yucatán, Mexico, which global-law reads at `mexico/yucatan/acts/`.

The law of the State of Yucatán (Estado Libre y Soberano de Yucatán, Mexico) as a git history: one file per article, one commit per publication that changed it, dated the day it took effect, with the decree as the commit's author. `git blame` names the decree behind every paragraph; `git log` lists every change to an article; checking out a date gives the text in force that day.

It follows the shared design of [lexifina/global-law](https://github.com/lexifina/global-law), which places it at `mx-yuc/`. Mexico's federal law is in [lexifina/mexico-law](https://github.com/lexifina/mexico-law).

The text is in Spanish, exactly as the source prints it.

## What this repository holds

104 ordenamientos with 704 versions so far: the constitution first, then the codes and laws in force, added in parts. Regulations, decrees and repealed laws are not included yet.

| Folder | Ordenamiento | Versions | History |
| --- | --- | ---: | --- |
| `constitucion-politica/` | CONSTITUCION POLITICA DEL ESTADO LIBRE Y SOBERANO DE YUCATAN | 188 | as first published, then each reform: 17 January 1918 to 5 September 2026 |
| `codigo-civil/` | CODIGO CIVIL DEL ESTADO DE YUCATAN | 19 | as first published, then each reform: 31 December 1993 to 31 December 2025 |
| `codigo-de-familia/` | CODIGO DE FAMILIA PARA EL ESTADO DE YUCATAN | 16 | as first published, then each reform: 3 May 2012 to 31 December 2025 |
| `codigo-de-la-administracion-publica-de-yucatan/` | CODIGO DE LA ADMINISTRACION PUBLICA DE YUCATAN | 38 | as first published, then each reform: 19 October 2007 to 31 December 2025 |
| `codigo-de-procedimientos-civiles-de-yucatan/` | CODIGO DE PROCEDIMIENTOS CIVILES DE YUCATAN | 18 | as first published, then each reform: 15 January 1942 to 29 December 2016 |
| `codigo-de-procedimientos-familiares/` | CODIGO DE PROCEDIMIENTOS FAMILIARES DEL ESTADO DE YUCATAN | 3 | as first published, then each reform: 3 May 2012 to 29 December 2016 |
| `codigo-fiscal/` | CODIGO FISCAL DEL ESTADO DE YUCATAN | 14 | as first published, then each reform: 23 December 2010 to 1 January 2026 |
| `codigo-penal/` | CODIGO PENAL DEL ESTADO DE YUCATAN | 88 | as first published, then each reform: 31 March 2000 to 20 October 2026 |
| `ley-de-acceso-de-las-mujeres-a-una-vida-libre-de-violencia/` | LEY DE ACCESO DE LAS MUJERES A UNA VIDA LIBRE DE VIOLENCIA DEL ESTADO DE YUCATAN | 21 | as first published, then each reform: 30 June 2014 to 9 April 2026 |
| `ley-de-actos-y-procedimientos-administrativos/` | LEY DE ACTOS Y PROCEDIMIENTOS ADMINISTRATIVOS DEL ESTADO DE YUCATAN | 7 | as first published, then each reform: 5 June 2010 to 26 May 2026 |
| `ley-de-adopciones-de-ninas-ninos-y-adolescentes/` | LEY DE ADOPCIONES DE NIÑAS, NIÑOS Y ADOLESCENTES DEL ESTADO DE YUCATAN | 1 | as first published: 27 April 2024 |
| `ley-de-adquisiciones-arrendamientos-y-prestacion-de-servicio/` | LEY DE ADQUISICIONES, ARRENDAMIENTOS Y PRESTACION DE SERVICIOS RELACIONADOS CON BIENES MUEBLES | 3 | as first published, then each reform: 5 October 1988 to 7 September 2021 |
| `ley-de-archivos/` | LEY DE ARCHIVOS PARA EL ESTADO DE YUCATAN | 3 | as first published, then each reform: 21 December 2020 to 29 August 2025 |
| `ley-de-asentamientos-humanos-ordenamiento-territorial-y-desa/` | LEY DE ASENTAMIENTOS HUMANOS, ORDENAMIENTO TERRITORIAL Y DESARROLLO URBANO DEL ESTADO DE YUCATAN | 3 | as first published, then each reform: 20 April 2024 to 26 May 2026 |
| `ley-de-bienes/` | LEY DE BIENES DEL ESTADO DE YUCATAN | 1 | as first published: 9 September 2012 |
| `ley-de-bienestar-energetico/` | LEY DE BIENESTAR ENERGETICO PARA EL ESTADO DE YUCATAN | 2 | as first published, then each reform: 4 December 2024 to 29 July 2025 |
| `ley-de-cambio-climatico/` | LEY DE CAMBIO CLIMATICO DEL ESTADO DE YUCATAN | 1 | as first published: 4 December 2021 |
| `ley-de-conservacion-y-desarrollo-del-arbolado-urbano/` | LEY DE CONSERVACION Y DESARROLLO DEL ARBOLADO URBANO DEL ESTADO DE YUCATAN | 3 | as first published, then each reform: 11 May 2017 to 15 October 2025 |
| `ley-de-coordinacion-de-zonas-economicas-especiales/` | LEY DE COORDINACION DE ZONAS ECONOMICAS ESPECIALES DEL ESTADO DE YUCATAN | 1 | as first published: 30 December 2016 |
| `ley-de-coordinacion-fiscal/` | LEY DE COORDINACION FISCAL DEL ESTADO DE YUCATAN | 12 | as first published, then each reform: 31 December 2001 to 29 December 2023 |
| `ley-de-coordinacion-metropolitana-desarrollo-regional-y-asoc/` | LEY DE COORDINACION METROPOLITANA, DESARROLLO REGIONAL Y ASOCIATIVIDAD INTERMUNICIPAL DEL ESTADO DE YUCATAN | 1 | as first published: 1 August 2024 |
| `ley-de-cultura-fisica-y-deporte/` | LEY DE CULTURA FISICA Y DEPORTE DEL ESTADO DE YUCATAN | 7 | as first published, then each reform: 3 December 2011 to 30 June 2026 |
| `ley-de-derechos-culturales/` | LEY DE DERECHOS CULTURALES PARA EL ESTADO Y MUNICIPIOS DE YUCATAN | 1 | as first published: 7 July 2021 |
| `ley-de-desarrollo-economico-y-fomento-al-empleo/` | LEY DE DESARROLLO ECONOMICO Y FOMENTO AL EMPLEO DEL ESTADO DE YUCATAN | 6 | as first published, then each reform: 22 December 2005 to 1 August 2024 |
| `ley-de-desarrollo-forestal-sustentable/` | LEY DE DESARROLLO FORESTAL SUSTENTABLE DEL ESTADO DE YUCATAN | 2 | as first published, then each reform: 1 October 2017 to 1 August 2019 |
| `ley-de-desarrollo-rural-sustentable/` | LEY DE DESARROLLO RURAL SUSTENTABLE DEL ESTADO DE YUCATAN | 2 | as first published, then each reform: 16 February 2013 to 1 August 2019 |
| `ley-de-desarrollo-social/` | LEY DE DESARROLLO SOCIAL DEL ESTADO DE YUCATAN | 1 | as first published: 8 June 2022 |
| `ley-de-desarrollos-inmobiliarios/` | LEY DE DESARROLLOS INMOBILIARIOS DEL ESTADO DE YUCATAN | 8 | as first published, then each reform: 8 December 2010 to 18 April 2025 |
| `ley-de-deuda-publica/` | LEY DE DEUDA PUBLICA DEL ESTADO DE YUCATAN | 2 | as first published, then each reform: 22 March 2018 to 1 January 2025 |
| `ley-de-edificios-y-espacios-cardioprotegidos/` | LEY DE EDIFICIOS Y ESPACIOS CARDIOPROTEGIDOS DEL ESTADO DE YUCATAN | 1 | as first published: 23 May 2020 |
| `ley-de-educacion/` | LEY DE EDUCACION DEL ESTADO DE YUCATAN | 15 | as first published, then each reform: 30 July 2020 to 20 October 2026 |
| `ley-de-emprendedores/` | LEY DE EMPRENDEDORES DEL ESTADO DE YUCATAN | 4 | as first published, then each reform: 10 June 2020 to 1 August 2024 |
| `ley-de-expropiacion/` | LEY DE EXPROPIACION | 2 | as first published, then each reform: 14 October 1938 to 3 August 1944 |
| `ley-de-fiscalizacion-de-la-cuenta-publica/` | LEY DE FISCALIZACION DE LA CUENTA PUBLICA DEL ESTADO DE YUCATAN | 7 | as first published, then each reform: 19 July 2017 to 25 December 2025 |
| `ley-de-fomento-a-las-actividades-de-las-organizaciones-de-la/` | LEY DE FOMENTO A LAS ACTIVIDADES DE LAS ORGANIZACIONES DE LA SOCIEDAD CIVIL EN EL ESTADO DE YUCATAN | 2 | as first published, then each reform: 1 August 2018 to 1 August 2019 |
| `ley-de-fomento-al-desarrollo-cientifico-tecnologico-y-a-la-i/` | LEY DE FOMENTO AL DESARROLLO CIENTIFICO, TECNOLOGICO Y A LA INNOVACION DEL ESTADO DE YUCATAN | 2 | as first published, then each reform: 24 March 2011 to 15 October 2015 |
| `ley-de-gobierno-de-los-municipios/` | LEY DE GOBIERNO DE LOS MUNICIPIOS DEL ESTADO DE YUCATAN | 32 | as first published, then each reform: 28 January 2006 to 1 January 2027 |
| `ley-de-gobierno-del-poder-legislativo/` | LEY DE GOBIERNO DEL PODER LEGISLATIVO DEL ESTADO DE YUCATAN | 18 | as first published, then each reform: 3 December 2010 to 29 July 2026 |
| `ley-de-hacienda-del-municipio-de-acanceh-yucatan/` | LEY DE HACIENDA DEL MUNICIPIO DE ACANCEH, YUCATAN | 2 | as first published, then each reform: 1 January 2013 to 30 April 2026 |
| `ley-de-hacienda-del-municipio-de-baca-yucatan/` | LEY DE HACIENDA DEL MUNICIPIO DE BACA, YUCATAN | 1 | as first published: 1 January 2016 |
| `ley-de-hacienda-del-municipio-de-buctzotz-yucatan/` | LEY DE HACIENDA DEL MUNICIPIO DE BUCTZOTZ, YUCATAN | 1 | as first published: 1 January 2009 |
| `ley-de-hacienda-del-municipio-de-calotmul-yucatan/` | LEY DE HACIENDA DEL MUNICIPIO DE CALOTMUL, YUCATAN | 2 | as first published, then each reform: 25 December 2007 to 28 December 2008 |
| `ley-de-hacienda-del-municipio-de-cansahcab-yucatan/` | LEY DE HACIENDA DEL MUNICIPIO DE CANSAHCAB, YUCATAN | 1 | as first published: 1 January 2026 |
| `ley-de-hacienda-del-municipio-de-celestun-yucatan/` | LEY DE HACIENDA DEL MUNICIPIO DE CELESTUN, YUCATAN | 1 | as first published: 22 April 2019 |
| `ley-de-hacienda-del-municipio-de-chankom-yucatan/` | LEY DE HACIENDA DEL MUNICIPIO DE CHANKOM, YUCATAN | 1 | as first published: 1 January 2026 |
| `ley-de-hacienda-del-municipio-de-chichimila-yucatan-para-el/` | LEY DE HACIENDA DEL MUNICIPIO DE CHICHIMILA, YUCATAN, PARA EL EJERCICIO 2026 | 1 | as first published: 1 January 2026 |
| `ley-de-hacienda-del-municipio-de-chicxulub-pueblo-yucatan/` | LEY DE HACIENDA DEL MUNICIPIO DE CHICXULUB PUEBLO, YUCATAN | 2 | as first published, then each reform: 29 December 2011 to 1 January 2020 |
| `ley-de-hacienda-del-municipio-de-espita-yucatan/` | LEY DE HACIENDA DEL MUNICIPIO DE ESPITA, YUCATAN | 1 | as first published: 1 January 2009 |
| `ley-de-hacienda-del-municipio-de-hoctun-yucatan/` | LEY DE HACIENDA DEL MUNICIPIO DE HOCTUN, YUCATAN | 1 | as first published: 1 January 2026 |
| `ley-de-hacienda-del-municipio-de-hunucma-yucatan/` | LEY DE HACIENDA DEL MUNICIPIO DE HUNUCMA, YUCATAN | 1 | as first published: 1 January 2026 |
| `ley-de-hacienda-del-municipio-de-izamal-yucatan/` | LEY DE HACIENDA DEL MUNICIPIO DE IZAMAL, YUCATAN | 4 | as first published, then each reform: 4 January 2006 to 3 January 2026 |
| `ley-de-hacienda-del-municipio-de-kanasin-yucatan/` | LEY DE HACIENDA DEL MUNICIPIO DE KANASIN, YUCATAN | 1 | as first published: 1 January 2026 |
| `ley-de-hacienda-del-municipio-de-kinchil-yucatan/` | LEY DE HACIENDA DEL MUNICIPIO DE KINCHIL, YUCATAN | 3 | as first published, then each reform: 1 January 2018 to 3 January 2026 |
| `ley-de-hacienda-del-municipio-de-kopoma-yucatan/` | LEY DE HACIENDA DEL MUNICIPIO DE KOPOMA, YUCATAN | 1 | as first published: 1 January 2026 |
| `ley-de-hacienda-del-municipio-de-maxcanu-yucatan/` | LEY DE HACIENDA DEL MUNICIPIO DE MAXCANU, YUCATAN | 2 | as first published, then each reform: 1 January 2013 to 27 December 2014 |
| `ley-de-hacienda-del-municipio-de-mayapan-yucatan/` | LEY DE HACIENDA DEL MUNICIPIO DE MAYAPAN, YUCATAN | 2 | as first published, then each reform: 31 December 2006 to 28 December 2008 |
| `ley-de-hacienda-del-municipio-de-merida-yucatan/` | LEY DE HACIENDA DEL MUNICIPIO DE MERIDA, YUCATAN | 16 | as first published, then each reform: 31 December 2012 to 3 January 2026 |
| `ley-de-hacienda-del-municipio-de-peto-yucatan/` | LEY DE HACIENDA DEL MUNICIPIO DE PETO, YUCATAN | 2 | as first published, then each reform: 30 December 2010 to 1 January 2019 |
| `ley-de-hacienda-del-municipio-de-progreso-yucatan/` | LEY DE HACIENDA DEL MUNICIPIO DE PROGRESO, YUCATAN | 5 | as first published, then each reform: 1 January 2014 to 3 January 2026 |
| `ley-de-hacienda-del-municipio-de-san-felipe-yucatan/` | LEY DE HACIENDA DEL MUNICIPIO DE SAN FELIPE, YUCATAN | 1 | as first published: 1 January 2009 |
| `ley-de-hacienda-del-municipio-de-tahdziu-yucatan/` | LEY DE HACIENDA DEL MUNICIPIO DE TAHDZIU, YUCATAN | 1 | as first published: 1 January 2026 |
| `ley-de-hacienda-del-municipio-de-teabo-yucatan/` | LEY DE HACIENDA DEL MUNICIPIO DE TEABO, YUCATAN | 1 | as first published: 30 December 2015 |
| `ley-de-hacienda-del-municipio-de-tecoh-yucatan/` | LEY DE HACIENDA DEL MUNICIPIO DE TECOH, YUCATAN | 3 | as first published, then each reform: 4 January 2006 to 1 January 2025 |
| `ley-de-hacienda-del-municipio-de-tekax-yucatan/` | LEY DE HACIENDA DEL MUNICIPIO DE TEKAX, YUCATAN | 7 | as first published, then each reform: 1 January 2019 to 3 January 2026 |
| `ley-de-hacienda-del-municipio-de-telchac-puerto-yucatan/` | LEY DE HACIENDA DEL MUNICIPIO DE TELCHAC PUERTO, YUCATAN | 2 | as first published, then each reform: 1 January 2014 to 3 January 2026 |
| `ley-de-hacienda-del-municipio-de-tetiz-yucatan/` | LEY DE HACIENDA DEL MUNICIPIO DE TETIZ, YUCATAN | 1 | as first published: 1 January 2026 |
| `ley-de-hacienda-del-municipio-de-tixcacalcupul-yucatan/` | LEY DE HACIENDA DEL MUNICIPIO DE TIXCACALCUPUL, YUCATAN | 1 | as first published: 1 January 2026 |
| `ley-de-hacienda-del-municipio-de-tixmehuac-yucatan/` | LEY DE HACIENDA DEL MUNICIPIO DE TIXMEHUAC, YUCATAN | 2 | as first published, then each reform: 31 December 2006 to 28 December 2008 |
| `ley-de-hacienda-del-municipio-de-tixpeual-yucatan/` | LEY DE HACIENDA DEL MUNICIPIO DE TIXPEUAL, YUCATAN | 1 | as first published: 1 January 2026 |
| `ley-de-hacienda-del-municipio-de-tizimin-yucatan/` | LEY DE HACIENDA DEL MUNICIPIO DE TIZIMIN, YUCATAN | 8 | as first published, then each reform: 31 December 2006 to 1 January 2022 |
| `ley-de-hacienda-del-municipio-de-valladolid-yucatan/` | LEY DE HACIENDA DEL MUNICIPIO DE VALLADOLID, YUCATAN | 1 | as first published: 1 January 2026 |
| `ley-de-hacienda-municipal/` | LEY DE HACIENDA MUNICIPAL DEL ESTADO DE YUCATAN | 2 | as first published, then each reform: 1 January 2016 to 25 June 2020 |
| `ley-de-hacienda-para-el-municipio-de-akil-yucatan/` | LEY DE HACIENDA PARA EL MUNICIPIO DE AKIL, YUCATAN | 2 | as first published, then each reform: 27 December 2011 to 31 December 2022 |
| `ley-de-hacienda-para-el-municipio-de-bokoba-yucatan/` | LEY DE HACIENDA PARA EL MUNICIPIO DE BOKOBA, YUCATAN | 1 | as first published: 1 January 2017 |
| `ley-de-hacienda-para-el-municipio-de-cacalchen-yucatan/` | LEY DE HACIENDA PARA EL MUNICIPIO DE CACALCHEN, YUCATAN | 2 | as first published, then each reform: 1 January 2017 to 1 January 2022 |
| `ley-de-hacienda-para-el-municipio-de-dzemul-yucatan/` | LEY DE HACIENDA PARA EL MUNICIPIO DE DZEMUL, YUCATAN | 4 | as first published, then each reform: 1 January 2017 to 3 January 2026 |
| `ley-de-hacienda-para-el-municipio-de-dzidzantun-yucatan/` | LEY DE HACIENDA PARA EL MUNICIPIO DE DZIDZANTUN, YUCATAN | 8 | as first published, then each reform: 1 January 2014 to 31 December 2022 |
| `ley-de-hacienda-para-el-municipio-de-dzilam-de-bravo-yucatan/` | LEY DE HACIENDA PARA EL MUNICIPIO DE DZILAM DE BRAVO, YUCATAN | 1 | as first published: 1 January 2017 |
| `ley-de-hacienda-para-el-municipio-de-dzilam-gonzalez-yucatan/` | LEY DE HACIENDA PARA EL MUNICIPIO DE DZILAM GONZALEZ, YUCATAN | 1 | as first published: 1 January 2017 |
| `ley-de-hacienda-para-el-municipio-de-halacho-yucatan/` | LEY DE HACIENDA PARA EL MUNICIPIO DE HALACHO, YUCATAN | 1 | as first published: 30 December 2010 |
| `ley-de-hacienda-para-el-municipio-de-huhi-yucatan/` | LEY DE HACIENDA PARA EL MUNICIPIO DE HUHI, YUCATAN | 1 | as first published: 1 January 2017 |
| `ley-de-hacienda-para-el-municipio-de-motul-yucatan/` | LEY DE HACIENDA PARA EL MUNICIPIO DE MOTUL, YUCATAN | 8 | as first published, then each reform: 1 January 2019 to 3 January 2026 |
| `ley-de-hacienda-para-el-municipio-de-muxupip-yucatan/` | LEY DE HACIENDA PARA EL MUNICIPIO DE MUXUPIP, YUCATAN | 1 | as first published: 1 January 2026 |
| `ley-de-hacienda-para-el-municipio-de-panaba-yucatan/` | LEY DE HACIENDA PARA EL MUNICIPIO DE PANABA, YUCATAN | 1 | as first published: 1 January 2017 |
| `ley-de-hacienda-para-el-municipio-de-quintana-roo-yucatan/` | LEY DE HACIENDA PARA EL MUNICIPIO DE QUINTANA ROO, YUCATAN | 1 | as first published: 1 January 2017 |
| `ley-de-hacienda-para-el-municipio-de-santa-elena-yucatan/` | LEY DE HACIENDA PARA EL MUNICIPIO DE SANTA ELENA, YUCATAN | 1 | as first published: 1 January 2017 |
| `ley-de-hacienda-para-el-municipio-de-sinanche-yucatan/` | LEY DE HACIENDA PARA EL MUNICIPIO DE SINANCHE, YUCATAN | 1 | as first published: 1 January 2017 |
| `ley-de-hacienda-para-el-municipio-de-sucila-yucatan/` | LEY DE HACIENDA PARA EL MUNICIPIO DE SUCILA, YUCATAN | 1 | as first published: 1 January 2017 |
| `ley-de-hacienda-para-el-municipio-de-sudzal-yucatan/` | LEY DE HACIENDA PARA EL MUNICIPIO DE SUDZAL, YUCATAN | 1 | as first published: 1 January 2017 |
| `ley-de-hacienda-para-el-municipio-de-suma-hidalgo-yucatan/` | LEY DE HACIENDA PARA EL MUNICIPIO DE SUMA HIDALGO, YUCATAN | 4 | as first published, then each reform: 3 January 2003 to 31 December 2016 |
| `ley-de-hacienda-para-el-municipio-de-tahmek-yucatan/` | LEY DE HACIENDA PARA EL MUNICIPIO DE TAHMEK, YUCATAN | 1 | as first published: 28 December 2013 |
| `ley-de-hacienda-para-el-municipio-de-tekal-de-venegas-yucata/` | LEY DE HACIENDA PARA EL MUNICIPIO DE TEKAL DE VENEGAS, YUCATAN | 1 | as first published: 1 January 2017 |
| `ley-de-hacienda-para-el-municipio-de-temax-yucatan/` | LEY DE HACIENDA PARA EL MUNICIPIO DE TEMAX, YUCATAN | 8 | as first published, then each reform: 31 December 2006 to 30 December 2023 |
| `ley-de-hacienda-para-el-municipio-de-temozon-yucatan/` | LEY DE HACIENDA PARA EL MUNICIPIO DE TEMOZON, YUCATAN | 1 | as first published: 1 January 2017 |
| `ley-de-hacienda-para-el-municipio-de-tepakan-yucatan/` | LEY DE HACIENDA PARA EL MUNICIPIO DE TEPAKAN, YUCATAN | 1 | as first published: 1 January 2026 |
| `ley-de-hacienda-para-el-municipio-de-ticul-yucatan/` | LEY DE HACIENDA PARA EL MUNICIPIO DE TICUL, YUCATAN | 4 | as first published, then each reform: 4 January 2006 to 3 January 2026 |
| `ley-de-hacienda-para-el-municipio-de-timucuy-yucatan/` | LEY DE HACIENDA PARA EL MUNICIPIO DE TIMUCUY, YUCATAN | 2 | as first published, then each reform: 31 December 2006 to 28 December 2008 |
| `ley-de-hacienda-para-el-municipio-de-tinum-yucatan/` | LEY DE HACIENDA PARA EL MUNICIPIO DE TINUM, YUCATAN | 1 | as first published: 1 January 2009 |
| `ley-de-hacienda-para-el-municipio-de-uayma-yucatan/` | LEY DE HACIENDA PARA EL MUNICIPIO DE UAYMA, YUCATAN | 1 | as first published: 1 January 2026 |
| `ley-de-hacienda-para-el-municipio-de-uman-yucatan/` | LEY DE HACIENDA PARA EL MUNICIPIO DE UMAN, YUCATAN | 1 | as first published: 1 January 2026 |
| `ley-de-hacienda-para-el-municipio-de-yobain-yucatan/` | LEY DE HACIENDA PARA EL MUNICIPIO DE YOBAIN, YUCATAN | 2 | as first published, then each reform: 1 January 2017 to 1 January 2025 |
| `ley-de-imagen-institucional/` | LEY DE IMAGEN INSTITUCIONAL PARA EL ESTADO DE YUCATAN Y SUS MUNICIPIOS | 1 | as first published: 8 April 2020 |
| `ley-de-imprenta/` | LEY DE IMPRENTA | 1 | as first published: 3 May 1917 |
| `ley-de-ingresos/` | LEY DE INGRESOS DEL ESTADO DE YUCATAN PARA EL EJERCICIO FISCAL 2026 | 2 | as first published, then each reform: 1 January 2026 to 5 September 2026 |

## Source

The legislation compilation of Mexico's Supreme Court, the Suprema Corte de Justicia de la Nación (SCJN), at <https://legislacion.scjn.gob.mx/>. For each ordenamiento it lists every publication in the state's official gazette (Periódico Oficial) that changed it (decree, erratum, ruling), with the date of publication, the decree's extract and the whole consolidated text as it stood after that publication. Each version here is one of those texts.

## Dates

- Each commit is dated at **noon, America/Merida, on the day the publication took effect**: the day its own transitorios name, as SCJN's extract quotes them (most often the day after publication). When a decree names none, 3 days after publication.
- A consolidated text holds every change published before it, so it is never dated before the latest of their in-force days. Different in-force days for parts of one decree are not split.
- An act's first commit is its first publication when SCJN holds the original text; otherwise it is the oldest version SCJN holds.
- Versions that take effect after the retrieval day are on the `futuro` branch, never merged into `main`.

## Files

`<act>/art-005.md` is Artículo 5, `art-005-bis.md` Artículo 5 Bis; `encabezado.md` holds the title, the promulgation and preamble; `transitorios-original.md` the original transitory articles and `transitorios-<date>.md` those of the reform published that day. Section headings and editor's notes such as "(REFORMADO, P.O. ...)" stay in the file of the article they stand before. One paragraph per line.

## How it is checked

- Every version of every act is read back from git on the day it took effect and on the day before (`tools/check_repo.py`); both must match `corpus.json`.
- The letters and digits of every version equal those of SCJN's own text of that version (read independently of the parser), and every unit's text appears in it in order.
- Health checks: no merge commits, commit dates never go backwards, nothing dated in the future, and every commit's trailers parse.

## What "author" means

The author of a commit is the publication that changed the text (a decree, an erratum or a ruling), named by its category, gazette date and issue, with an e-mail address that cannot exist (`<key>@legislacion.scjn.gob.mx.invalid`). The committer is always Lexifina.

## Limits

This is not an official publication. The binding text is the one published in the state's official gazette (Periódico Oficial). The history starts with the oldest text SCJN holds for each ordenamiento, which for many is later than its enactment. Only the ordenamientos listed above are included.
