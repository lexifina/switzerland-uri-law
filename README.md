# Uri: law history in git

The law of the canton of Uri (Kanton Uri, Switzerland) as a git history: one file per article, one commit per amending act on the day it took effect, and the amending act as the commit's author. `git blame` names the act behind every paragraph; `git log` lists every change to an article; checking out a date gives the text in force that day.

It follows the shared design of [lexifina/global-law](https://github.com/lexifina/global-law), which places it at `ch-ur/`. The federal law is in [lexifina/switzerland-law](https://github.com/lexifina/switzerland-law).

The text is in German, the canton's official language, exactly as the canton publishes it.

## What this repository holds

317 acts with 346 versions so far: the cantonal constitution, the cantonal laws (Gesetze) in force and 262 Verordnungen and Reglemente in force, in the order of the systematic collection, added in parts. Other decrees and decisions, intercantonal agreements and repealed acts are not included yet.

| Folder | Act | Versions | History |
| --- | --- | ---: | --- |
| `1-1101/` | Verfassung des Kantons Uri (RB 1.1101) | 1 | one version (the oldest available), 1 June 2023 |
| `1-1111-geg/` | Gemeindegesetz (RB 1.1111) | 2 | as enacted, then each consolidated version: 1 June 2017 to 1 January 2026 |
| `1-4121-kantonales-burgerrechtsgesetz-kbug/` | Gesetz über das Kantons- und Gemeindebürgerrecht (RB 1.4121) | 1 | one version (the oldest available), 1 January 2018 |
| `1-4201-kantonales-registerharmonisierungsgesetz-krg/` | Gesetz über die Harmonisierung amtlicher Register (RB 1.4201) | 1 | one version (the oldest available), 11 November 2023 |
| `1-4211/` | Gesetz über Niederlassung und Aufenthalt der Schweizer (RB 1.4211) | 1 | one version (the oldest available), 1 January 2009 |
| `2-1201-wavg/` | Gesetz über die geheimen Wahlen, Abstimmungen und die Volksrechte (RB 2.1201) | 1 | one version (the oldest available), 1 January 2010 |
| `2-1205-proporzgesetz/` | Gesetz über die Verhältniswahl des Landrates (RB 2.1205) | 1 | one version (the oldest available), 1 October 2019 |
| `2-2221-gbb/` | Gesetz zur Besetzung von Behörden (RB 2.2221) | 1 | one version (the oldest available), 1 June 2019 |
| `2-2321-ausstandsgesetz-aug/` | Gesetz über den Ausstand (RB 2.2321) | 1 | one version (the oldest available), 1 January 2021 |
| `2-2511-kantonales-datenschutzgesetz-kdsg/` | Gesetz über den Schutz von Personendaten (RB 2.2511) | 1 | as enacted, 11 November 2023 |
| `2-2711-offentlichkeitsgesetz-oeg/` | Gesetz über das Öffentlichkeitsprinzip (RB 2.2711) | 2 | as enacted, then each consolidated version: 1 April 2007 to 1 January 2026 |
| `2-3221-gerichtsorganisationsgesetz-gog/` | Gesetz über die Organisation der richterlichen Behörden (RB 2.3221) | 1 | one version (the oldest available), 1 June 2023 |
| `3-1310-publikationsgesetz-pug/` | Gesetz über die amtliche Publikation (RB 3.1310) | 1 | as enacted, 1 January 2022 |
| `3-2110/` | Gesetz zum Haushaltsgleichgewicht des Kantons Uri (RB 3.2110) | 1 | as enacted, 1 January 2019 |
| `3-2131-filag/` | Gesetz über den Finanz- und Lastenausgleich zwischen dem Kanton und den Gemeinden (RB 3.2131) | 2 | oldest version available, then each consolidated version: 1 January 2021 to 1 January 2026 |
| `3-2211-steuergesetz-stg/` | Gesetz über die direkten Steuern im Kanton Uri (RB 3.2211) | 2 | oldest version available, then each consolidated version: 1 January 2025 to 1 January 2026 |
| `3-3211-expropriationsgesetz/` | Gesetz über die Enteignung (RB 3.3211) | 1 | one version (the oldest available), 19 May 2025 |
| `3-6201-bevolkerungsschutzgesetz-bsg/` | Gesetz über den Bevölkerungsschutz im Kanton Uri (RB 3.6201) | 1 | one version (the oldest available), 1 January 2021 |
| `3-8111-polg/` | Polizeigesetz (RB 3.8111) | 1 | one version (the oldest available), 1 July 2024 |
| `3-9211/` | Gesetz über die Einführung des Schweizerischen Strafgesetzbuches (RB 3.9211) | 1 | one version (the oldest available), 1 July 2015 |
| `9-2111-eg-zgb/` | Gesetz über die Einführung des Schweizerischen Zivilgesetzbuches (RB 9.2111) | 1 | one version (the oldest available), 1 June 2019 |
| `9-2113-eg-kesr/` | Gesetz über die Einführung des Kindes- und Erwachsenenschutzrechts (RB 9.2113) | 1 | as enacted, 1 January 2013 |
| `9-2421-eg-schkg/` | Gesetz über die Einführung des Bundesgesetzes über Schuldbetreibung und Konkurs (RB 9.2421) | 1 | as enacted, 1 April 1997 |
| `9-3401-gbg/` | Gesetz über das Grundbuch (RB 9.3401) | 1 | one version (the oldest available), 1 January 2007 |
| `10-1111-bildungsgesetz/` | Gesetz über Schule und Bildung (RB 10.1111) | 1 | one version (the oldest available), 1 August 2023 |
| `10-4211-schwimmbadfinanzierungsgesetz/` | Gesetz über die finanzielle Unterstützung des Schwimmbads Altdorf (RB 10.4211) | 1 | as enacted, 1 July 2016 |
| `10-5101/` | Gesetz über den Natur- und Heimatschutz (RB 10.5101) | 1 | one version (the oldest available), 1 January 2008 |
| `10-7111-kantonales-kinder-und-jugendforderungsgesetz-kkjfg/` | Gesetz über die Förderung von Kindern und Jugendlichen im Kanton Uri (RB 10.7111) | 1 | as enacted, 1 January 2017 |
| `10-8111-kulturforderungsgesetz-kfg/` | Gesetz über die Förderung der Kultur im Kanton Uri (RB 10.8111) | 1 | as enacted, 1 January 2022 |
| `20-2231/` | Gesetz über die Langzeitpflege (RB 20.2231) | 1 | one version (the oldest available), 1 June 2023 |
| `20-2421/` | Gesetz über die Ergänzungsleistungen zur AHV/IV (RB 20.2421) | 1 | as enacted, 1 January 2008 |
| `20-2511-fzg/` | Gesetz über die Familienzulagen (RB 20.2511) | 1 | one version (the oldest available), 1 January 2021 |
| `20-3221-ksug/` | Gesetz über das Kantonsspital Uri (RB 20.3221) | 1 | as enacted, 1 January 2018 |
| `20-3421-sozialhilfegesetz/` | Gesetz über die öffentliche Sozialhilfe (RB 20.3421) | 1 | one version (the oldest available), 11 November 2023 |
| `20-3461-alimentenbevorschussungsgesetz/` | Gesetz über die Bevorschussung von Unterhaltsbeiträgen (RB 20.3461) | 1 | one version (the oldest available), 1 January 2013 |
| `30-2111-gg/` | Gesundheitsgesetz (RB 30.2111) | 1 | one version (the oldest available), 1 June 2023 |
| `30-3111-fsg/` | Gesetz über den Feuerschutz (RB 30.3111) | 1 | as enacted, 1 January 1997 |
| `40-1111-pbg/` | Planungs- und Baugesetz (RB 40.1111) | 1 | one version (the oldest available), 1 January 2022 |
| `40-1211-wbg/` | Wasserbaugesetz (RB 40.1211) | 1 | one version (the oldest available), 1 January 2008 |
| `40-1225/` | Gesetz über das Reussdelta (RB 40.1225) | 1 | one version (the oldest available), 1 January 2011 |
| `40-1401/` | Gesetz über die Staatshilfe bei Elementarschäden (RB 40.1401) | 1 | one version (the oldest available), 1 September 2008 |
| `40-1402-gebaudeversicherungsgesetz-gvg/` | Gesetz über die obligatorische Gebäudeversicherung (RB 40.1402) | 1 | as enacted, 1 January 2023 |
| `40-4101-gng/` | Gewässernutzungsgesetz (RB 40.4101) | 1 | as enacted, 1 April 1993 |
| `40-5111-bug/` | Gesetz über das Bergregal und die Nutzung des Untergrundes (RB 40.5111) | 1 | as enacted, 5 December 1995 |
| `40-7011-kug/` | Kantonales Umweltgesetz (RB 40.7011) | 1 | one version (the oldest available), 1 July 2024 |
| `40-7211-eng/` | Energiegesetz des Kantons Uri (RB 40.7211) | 2 | as enacted, then each consolidated version: 1 January 2000 to 1 October 2026 |
| `50-1111-strg/` | Strassengesetz (RB 50.1111) | 1 | as enacted, 1 January 2014 |
| `50-1161-kantonales-fuss-und-wanderweggesetz-kfwg/` | Gesetz über Fuss- und Wanderwege (RB 50.1161) | 1 | one version (the oldest available), 1 January 2021 |
| `50-1411/` | Gesetz über die Strassenverkehrssteuern (RB 50.1411) | 1 | as enacted, 1 January 1998 |
| `50-5111-verkehrsgesetz/` | Gesetz über die Förderung des öffentlichen Verkehrs (RB 50.5111) | 1 | one version (the oldest available), 1 January 2008 |
| `70-1311-ukbg/` | Gesetz über die Urner Kantonalbank (RB 70.1311) | 1 | one version (the oldest available), 1 January 2024 |
| `70-1421-lsg/` | Gesetz über den Ladenschluss und die Sonntagsruhe (RB 70.1421) | 1 | as enacted, 1 January 2003 |
| `70-1611-wfg/` | Wirtschaftsförderungsgesetz (RB 70.1611) | 1 | one version (the oldest available), 23 September 2013 |
| `70-2111-gwg/` | Gastwirtschaftsgesetz (RB 70.2111) | 1 | as enacted, 1 January 1999 |
| `70-2411-tourismusgesetz-tourg/` | Gesetz über die Förderung des Tourismus (RB 70.2411) | 1 | one version (the oldest available), 1 June 2023 |
| `1-1205/` | Reglement zur Fachstelle für Frauenfragen der kantonalen Verwaltung und zum Bundesgesetz über die Gleichstellung von Frau und Mann (RB 1.1205) | 1 | one version (the oldest available), 1 January 2011 |
| `1-4123/` | Verordnung über die Eignungsvoraussetzungen für das Kantons- und Gemeindebürgerrecht (RB 1.4123) | 1 | as enacted, 1 January 2018 |
| `1-4125-aur/` | Reglement zum Ausweisgesetz (RB 1.4125) | 1 | one version (the oldest available), 1 June 2023 |
| `1-4205-krgr/` | Reglement zum Kantonalen Registerharmonisierungsgesetz (RB 1.4205) | 1 | one version (the oldest available), 1 February 2025 |
| `1-4215/` | Reglement über Niederlassung und Aufenthalt der Schweizer (RB 1.4215) | 1 | as enacted, 1 April 1986 |
| `1-4221/` | Reglement zum Bundesgesetz über die Ausländerinnen und Ausländer und über die Integration und zum Asylgesetz (RB 1.4221) | 1 | one version (the oldest available), 1 March 2025 |
| `1-4231/` | Reglement über den Fonds «Programm S» (RB 1.4231) | 1 | as enacted, 15 October 2022 |
| `2-1203/` | Reglement über das Stimmregister für Auslandschweizerinnen und Auslandschweizer (RB 2.1203) | 1 | as enacted, 1 January 2010 |
| `2-2251/` | Nebenamtsverordnung (RB 2.2251) | 2 | oldest version available, then each consolidated version: 1 June 2023 to 18 March 2026 |
| `2-2345-vrpv/` | Verordnung über die Verwaltungsrechtspflege (RB 2.2345) | 1 | one version (the oldest available), 1 March 2016 |
| `2-2347/` | Reglement über die berufsmässige Vertretung in Steuer- und Sozialversicherungssachen vor Obergericht (RB 2.2347) | 1 | as enacted, 1 July 2002 |
| `2-3111-landratsverordnung-lrv/` | Verordnung über den Landrat (RB 2.3111) | 1 | as enacted, 1 August 2005 |
| `2-3225/` | Reglement über die Justizverwaltung (RB 2.3225) | 1 | one version (the oldest available), 1 October 2023 |
| `2-3227/` | Reglement über die Bildung der Spruchkörper der verwaltungsrechtlichen Abteilung des Obergerichts (RB 2.3227) | 1 | as enacted, 1 January 2020 |
| `2-3229/` | Reglement über die Zuständigkeit der Landgerichtspräsidien I und II Uri (RB 2.3229) | 1 | as enacted, 1 June 2023 |
| `2-3231-gerichtsgebuhrenverordnung-ggebv/` | Verordnung über die Gebühren und Entschädigungen vor Gerichtsbehörden (RB 2.3231) | 2 | oldest version available, then each consolidated version: 1 January 2020 to 1 January 2026 |
| `2-3232-gerichtsgebuhrenreglement-ggebr/` | Reglement über die Gebühren und Entschädigungen vor Gerichtsbehörden (RB 2.3232) | 1 | one version (the oldest available), 1 October 2023 |
| `2-3243/` | Reglement über die Akkreditierung von Medienschaffenden an den Urner Gerichten (RB 2.3243) | 1 | as enacted, 1 June 2021 |
| `2-3320/` | Verordnung zur versuchsweisen Weiterführung der Kostenlenkung im Personalbereich mittels Globalbudget (RB 2.3320) | 1 | as enacted, 1 January 2019 |
| `2-3321-organisationsverordnung/` | Verordnung über die Organisation der Regierungs- und der Verwaltungstätigkeit (RB 2.3321) | 2 | oldest version available, then each consolidated version: 1 January 2023 to 1 January 2026 |
| `2-3322-organisationsreglement-orr/` | Reglement über die Organisation der Regierungs- und der Verwaltungstätigkeit (RB 2.3322) | 2 | oldest version available, then each consolidated version: 1 April 2025 to 1 January 2026 |
| `2-3323/` | Reglement über die Koordination im Verwaltungsverfahren (RB 2.3323) | 1 | one version (the oldest available), 1 January 2014 |
| `2-3325-vorsorgeverordnung-vvr/` | Verordnung über die Vorsorge für Mitglieder des Regierungsrates (RB 2.3325) | 1 | one version (the oldest available), 1 January 2019 |
| `2-3327/` | Reglement über die Unterschriftsberechtigung (RB 2.3327) | 2 | oldest version available, then each consolidated version: 1 January 2022 to 1 January 2026 |
| `2-3331-parkplatzreglement/` | Reglement über die Benützung von Parkplätzen der Kantonsverwaltung und der kantonalen Schulen (RB 2.3331) | 1 | as enacted, 1 July 2020 |
| `2-4211-pv/` | Personalverordnung (RB 2.4211) | 1 | one version (the oldest available), 1 January 2023 |
| `2-4213-pr/` | Personalreglement (RB 2.4213) | 1 | one version (the oldest available), 1 January 2023 |
| `2-4215/` | Reglement über die Mitarbeiterinnen- und Mitarbeitergespräche (RB 2.4215) | 1 | one version (the oldest available), 1 July 2016 |
| `2-4219-rap/` | Reglement über die angepassten Arbeitsplätze (RB 2.4219) | 1 | as enacted, 1 January 2023 |
| `2-4221-pensionskassenverordnung-pkv/` | Verordnung über die Pensionskasse Uri (RB 2.4221) | 1 | one version (the oldest available), 1 January 2019 |
| `3-1311-publikationsreglement-pur/` | Reglement über die amtliche Publikation (RB 3.1311) | 1 | as enacted, 1 January 2022 |
| `3-2111-fhv/` | Verordnung über den Finanzhaushalt des Kantons Uri (RB 3.2111) | 1 | one version (the oldest available), 1 January 2019 |
| `3-2115/` | Reglement über das Rechnungswesen der Einwohnergemeinden (RB 3.2115) | 1 | one version (the oldest available), 1 January 2021 |
| `3-2117/` | Reglement über den Fonds Integrationsagenda (RB 3.2117) | 1 | as enacted, 15 October 2019 |
| `3-2119/` | Reglement über den Solidaritätsfonds im Zusammenhang mit der Zusammenarbeitsvereinbarung zwischen dem Kanton, den Gemeinden und dem SRK (RB 3.2119) | 1 | as enacted, 1 January 2020 |
| `3-2141-zlr/` | Reglement über die Zentrumsleistungen (RB 3.2141) | 1 | as enacted, 1 January 2008 |
| `3-2213/` | Reglement über die Besteuerung nach dem Aufwand (RB 3.2213) | 1 | as enacted, 1 January 2016 |
| `3-2214-quellensteuerreglement-qstr/` | Reglement über die Quellensteuer und das vereinfachte Abrechnungsverfahren (RB 3.2214) | 1 | one version (the oldest available), 1 January 2025 |
| `3-2217-liegenschaftskostenreglement-lkr/` | Reglement über den Abzug der Kosten von Liegenschaften des Privatvermögens (RB 3.2217) | 1 | as enacted, 1 January 2020 |
| `3-2218-ekor/` | Reglement über die Entschädigung und Kostenbeteiligung zwischen Kanton und Gemeinden im Steuerwesen (RB 3.2218) | 1 | as enacted, 1 January 2019 |
| `3-2219-steuerbezugsreglement-bezr/` | Reglement über den allgemeinen Steuerbezug und das Abrechnungsverfahren (RB 3.2219) | 2 | oldest version available, then each consolidated version: 1 January 2025 to 1 January 2026 |
| `3-2225/` | Reglement über die elektronische Einreichung der Steuererklärung und die elektronische Aufbewahrung und Archivierung von Steuerakten (RB 3.2225) | 1 | as enacted, 1 January 2025 |
| `3-2227-schatzungsreglement-schar/` | Reglement über die Schätzung, die Festlegung der Eigenmiet- und Steuerwerte sowie das Bewertungsverfahren für nichtlandwirtschaftliche Grundstücke (RB 3.2227) | 1 | as enacted, 1 January 2025 |
| `3-2402-dbgr/` | Reglement zum Bundesgesetz über die direkte Bundessteuer (RB 3.2402) | 1 | one version (the oldest available), 1 January 2019 |
| `3-2403-vstgr/` | Reglement zum Bundesgesetz über die Verrechnungssteuer (RB 3.2403) | 1 | one version (the oldest available), 1 January 2019 |
| `3-2404-pstar/` | Reglement zur Verordnung über die pauschale Steueranrechnung (RB 3.2404) | 1 | one version (the oldest available), 1 January 2001 |
| `3-2512/` | Gebührenverordnung (RB 3.2512) | 1 | one version (the oldest available), 1 January 2005 |
| `3-2521/` | Gebührenreglement (RB 3.2521) | 1 | one version (the oldest available), 1 March 2000 |
| `3-3115-submissionsreglement/` | Reglement über den Vollzug der Interkantonalen Vereinbarung über das öffentliche Beschaffungswesen (RB 3.3115) | 1 | as enacted, 1 June 2024 |
| `3-6110/` | Verordnung über die Aufhebung von Militärrecht (RB 3.6110) | 1 | as enacted, 1 April 1999 |
| `3-6115-mwr/` | Reglement über das Militär und den Wehrpflichtersatz (RB 3.6115) | 1 | one version (the oldest available), 1 March 2022 |
| `3-6205-zivilschutzreglement-zsr/` | Reglement über den Zivilschutz im Kanton Uri (RB 3.6205) | 1 | one version (the oldest available), 1 January 2021 |
| `3-6207-kafur-reglement-kfsr/` | Reglement über den kantonalen Führungsstab Uri (RB 3.6207) | 1 | as enacted, 1 January 2007 |
| `3-6301/` | Verordnung über die Organisation und die Aufgaben der wirtschaftlichen Landesversorgung (RB 3.6301) | 1 | as enacted, 1 January 2001 |
| `3-8115/` | Videoverordnung (RB 3.8115) | 1 | one version (the oldest available), 1 July 2024 |
| `3-8127-polr/` | Polizeireglement (RB 3.8127) | 1 | as enacted, 1 May 2010 |
| `3-8325/` | Reglement zur Umsetzung des Bundesgesetzes über Massnahmen zur Wahrung der inneren Sicherheit und des Konkordats über Massnahmen gegen Gewalt anlässlich von Sportveranstaltungen (RB 3.8325) | 1 | as enacted, 1 January 2011 |
| `3-8327/` | Reglement über die Überwachung des Post- und Fernmeldeverkehrs ausserhalb von Strafverfahren (RB 3.8327) | 1 | as enacted, 1 February 2021 |
| `3-9213/` | Reglement über den straflosen Schwangerschaftsabbruch (RB 3.9213) | 1 | as enacted, 1 November 2002 |
| `3-9223-ordnungsbussenreglement-obr/` | Reglement über die Erhebung von Ordnungsbussen (RB 3.9223) | 1 | one version (the oldest available), 1 April 2025 |
| `3-9321-vsmv/` | Verordnung über den Straf- und Massnahmenvollzug (RB 3.9321) | 1 | one version (the oldest available), 1 January 2018 |
| `3-9323/` | Verordnung über das Strafregister, die Leumundsberichte und die Leumundszeugnisse (RB 3.9323) | 1 | one version (the oldest available), 1 January 2007 |
| `9-2115/` | Reglement über die berufsmässige Ehe- und Partnerschaftsvermittlung (RB 9.2115) | 1 | one version (the oldest available), 1 March 2003 |
| `9-2117/` | Reglement über die Einführung des Kindes- und Erwachsenenschutzrechts (RB 9.2117) | 1 | as enacted, 1 July 2018 |
| `9-2125-pflegekinderreglement/` | Reglement über die Aufnahme von Kindern zur Pflege und zur Adoption (RB 9.2125) | 1 | as enacted, 1 January 2014 |
| `9-2311/` | Verordnung über das Notariat (RB 9.2311) | 1 | one version (the oldest available), 1 January 2001 |
| `9-2313/` | Reglement betreffend die Ausführung der Verordnung über das Notariat (RB 9.2313) | 1 | one version (the oldest available), 1 January 2001 |
| `9-2315/` | Reglement über die Notariatsprüfung (RB 9.2315) | 1 | as enacted, 1 June 2002 |
| `9-2321-anv/` | Anwaltsverordnung (RB 9.2321) | 1 | one version (the oldest available), 1 December 2012 |
| `9-2325/` | Reglement über die Anwaltsprüfung (RB 9.2325) | 1 | one version (the oldest available), 1 January 2007 |
| `9-3101-kzstv/` | Kantonale Zivilstandsverordnung (RB 9.3101) | 1 | as enacted, 1 January 2004 |
| `9-3104/` | Verordnung über die Stiftungsaufsicht (RB 9.3104) | 1 | one version (the oldest available), 1 June 2023 |
| `9-3115/` | Reglement zum über den Vollzug zivilgerichtlicher Anordnungen der elektronischen Überwachung (RB 9.3115) | 1 | as enacted, 1 January 2022 |
| `9-3408-gbr/` | Reglement über das Grundbuch (RB 9.3408) | 1 | as enacted, 1 January 2005 |
| `9-3431-kantonale-geoinformationsverordnung-kgeoiv/` | Verordnung über Geoinformation (RB 9.3431) | 1 | as enacted, 1 January 2013 |
| `9-3432-kantonales-geoinformationsreglement-kgeoir/` | Reglement über Geoinformation (RB 9.3432) | 1 | one version (the oldest available), 1 April 2024 |
| `9-3436/` | Reglement über die Gebühren für die laufende Nachführung der amtlichen Vermessung (RB 9.3436) | 1 | as enacted, 1 January 2021 |
| `9-3441/` | Reglement über das Verfahren vor der Zivilschätzungskommission (RB 9.3441) | 1 | one version (the oldest available), 1 June 1995 |
| `9-3616/` | Verordnung über die öffentlich-rechtliche Bodenverbesserungsgenossenschaft (RB 9.3616) | 1 | one version (the oldest available), 1 January 2003 |
| `9-4222/` | Reglement zum Miet- und Pachtrecht im Obligationenrecht (RB 9.4222) | 2 | oldest version available, then each consolidated version: 1 January 2011 to 1 October 2025 |
| `9-4225/` | Reglement über die berufsmässige Vertretung in Streitigkeiten aus dem Arbeitsverhältnis zwischen Arbeitnehmenden und Arbeitgebenden vor richterlichen Behörden (RB 9.4225) | 1 | as enacted, 1 January 2011 |
| `9-5121/` | Verordnung zum Bundesgesetz über den Erwerb von Grundstücken durch Personen im Ausland (RB 9.5121) | 1 | as enacted, 1 January 1985 |
| `9-5125/` | Reglement zum Bundesgesetz über den Erwerb von Grundstücken durch Personen im Ausland (RB 9.5125) | 1 | as enacted, 1 January 1985 |
| `10-1115-volksschulverordnung/` | Verordnung über die Volksschule (RB 10.1115) | 2 | oldest version available, then each consolidated version: 1 August 2016 to 1 August 2026 |
| `10-1117/` | Reglement über die Einführungsklasse (RB 10.1117) | 1 | one version (the oldest available), 1 August 2002 |
| `10-1135/` | Reglement über die Beurteilung im Kindergarten (RB 10.1135) | 2 | oldest version available, then each consolidated version: 1 August 2018 to 1 August 2026 |
| `10-1137/` | Reglement über die Beurteilung und die Promotion in der Primarstufe (RB 10.1137) | 2 | as enacted, then each consolidated version: 1 August 2016 to 1 August 2026 |
| `10-1139/` | Reglement über die Beurteilung und die Promotion auf der Oberstufe (RB 10.1139) | 1 | as enacted, 1 August 2026 |
| `10-1212/` | Reglement über den beruflichen Auftrag der Lehrpersonen an der Volksschule (Amtsauftrag) (RB 10.1212) | 1 | as enacted, 1 August 2016 |
| `10-1213-prl/` | Personalreglement für die kantonalen Lehrpersonen (RB 10.1213) | 1 | one version (the oldest available), 1 August 2023 |
| `10-1219-ral/` | Reglement über den beruflichen Auftrag der kantonalen Lehrpersonen (RB 10.1219) | 1 | as enacted, 1 August 2008 |
| `10-1222-schulische-beitragsverordnung-vbv/` | Verordnung über Beiträge des Kantons an die Volksschulen (RB 10.1222) | 1 | one version (the oldest available), 1 August 2023 |
| `10-1224-awr/` | Reglement über die Anstellung und Weiterbildung der Lehrpersonen an den Volksschulen (RB 10.1224) | 1 | one version (the oldest available), 1 January 2017 |
| `10-1310/` | Reglement über den Fonds Kantonaler Lehrmittelverlag (RB 10.1310) | 1 | as enacted, 1 July 2023 |
| `10-1421/` | Reglement über den Schulmedizinischen Dienst (RB 10.1421) | 2 | oldest version available, then each consolidated version: 1 August 2018 to 1 August 2026 |
| `10-1447/` | Reglement über die Schulleitung (RB 10.1447) | 1 | one version (the oldest available), 1 August 2019 |
| `10-1462-vmv/` | Verordnung über den freiwilligen Musikunterricht an der Volksschule (RB 10.1462) | 1 | one version (the oldest available), 1 August 2025 |
| `10-1467/` | Reglement über die Absenzen und Beurlaubungen für Schülerinnen und Schüler (RB 10.1467) | 1 | one version (the oldest available), 1 August 2015 |
| `10-1611/` | Verordnung über das sonderpädagogische Angebot im Kanton Uri (RB 10.1611) | 1 | one version (the oldest available), 1 January 2017 |
| `10-1615/` | Reglement über die Kostenbeteiligung der Erziehungsberechtigten im Bereich des sonderpädagogischen Angebots (RB 10.1615) | 1 | one version (the oldest available), 1 January 2008 |
| `10-1617/` | Reglement über die Entschädigung bei unzumutbarem Schulweg im Rahmen des sonderpädagogischen Angebots (RB 10.1617) | 1 | as enacted, 1 January 2009 |
| `10-1711-ubertrittsreglement/` | Reglement über den Übertritt der Schülerinnen und Schüler in die Oberstufe und in das Gymnasium (RB 10.1711) | 1 | one version (the oldest available), 1 January 2012 |
| `10-2201-stipendienverordnung/` | Verordnung über die Ausrichtung von Ausbildungsbeiträgen (RB 10.2201) | 1 | one version (the oldest available), 1 January 2016 |
| `10-2205-stipendienreglement/` | Reglement über die Ausrichtung von Ausbildungsbeiträgen (RB 10.2205) | 1 | one version (the oldest available), 1 September 2021 |
| `10-2401-mittelschulverordnung/` | Verordnung über die Kantonale Mittelschule Uri (RB 10.2401) | 1 | one version (the oldest available), 1 August 2023 |
| `10-2406/` | Reglement über die bilinguale Maturität an der Kantonalen Mittelschule Uri (RB 10.2406) | 1 | as enacted, 1 April 2015 |
| `10-2414-mpr/` | Reglement über die Maturitätsprüfungen an der Kantonalen Mittelschule Uri (RB 10.2414) | 1 | one version (the oldest available), 1 August 2024 |
| `10-2416/` | Reglement über die Maturaarbeit an der Kantonalen Mittelschule Uri (RB 10.2416) | 1 | as enacted, 1 August 2018 |
| `10-2418-promotionsreglement-promr/` | Reglement über die Promotion an der Kantonalen Mittelschule Uri (RB 10.2418) | 2 | oldest version available, then each consolidated version: 1 August 2022 to 1 August 2026 |
| `10-2420/` | Reglement über die Aufnahme in das Gymnasium an der Kantonalen Mittelschule Uri (RB 10.2420) | 1 | as enacted, 1 August 2012 |
| `10-2425-fms-aufnahmereglement/` | Reglement über die Aufnahme in die Fachmittelschule (RB 10.2425) | 1 | as enacted, 1 August 2006 |
| `10-2427-fmp-abschlussprufungsreglement/` | Reglement über die Abschlussprüfungen der Fachmaturität Pädagogik (RB 10.2427) | 1 | as enacted, 1 December 2008 |
| `10-2923/` | Verordnung über die Führung des Urner Forschungsinstituts Kulturen der Alpen als Hochschule (RB 10.2923) | 1 | as enacted, 1 January 2023 |
| `10-2935/` | Verordnung über die Anerkennung privater universitärer Hochschulen (RB 10.2935) | 1 | one version (the oldest available), 1 January 2007 |
| `10-4111-sportverordnung/` | Verordnung über die Förderung des Sports (RB 10.4111) | 1 | one version (the oldest available), 1 January 2019 |
| `10-4113-sportreglement/` | Reglement über die Förderung des Sports (RB 10.4113) | 2 | oldest version available, then each consolidated version: 1 August 2023 to 1 August 2025 |
| `10-5105-blnv/` | Verordnung über Beiträge für den landwirtschaftlichen Naturschutz (RB 10.5105) | 1 | one version (the oldest available), 1 January 2003 |
| `10-5106-blnr/` | Reglement zur Verordnung über Beiträge für den landwirtschaftlichen Naturschutz (RB 10.5106) | 1 | as enacted, 1 January 2016 |
| `10-5110/` | Reglement über den Schutz des Südufers des Urnersees (RB 10.5110) | 1 | as enacted, 1 October 2000 |
| `10-5111/` | Reglement über den Schutz der Region Maderanertal und Fellital (RB 10.5111) | 1 | one version (the oldest available), 1 October 2014 |
| `10-5112/` | Reglement über den Schutz von Hoch- und Flachmooren und von Quellen auf dem Urnerboden (RB 10.5112) | 1 | as enacted, 1 June 1988 |
| `10-5113/` | Reglement über den Schutz der Flach- und Übergangsmoore «Brunnen» und «Fliesmatt» inkl. Moorlehrpfad in der Gemeinde Andermatt (RB 10.5113) | 1 | as enacted, 1 March 2000 |
| `10-5114/` | Reglement über den Schutz der Moore und Trockenwiesen auf Gitschenen in der Gemeinde Isenthal (RB 10.5114) | 1 | as enacted, 1 November 2018 |
| `10-5115/` | Reglement über den Schutz des Gebiets Wilerschachen («Polenschachen») in der Gemeinde Erstfeld (RB 10.5115) | 1 | as enacted, 1 August 2011 |
| `10-5116/` | Reglement über den Schutz renaturierter Bäche in der unteren Urner Reussebene (RB 10.5116) | 1 | as enacted, 1 March 2022 |
| `10-5117/` | Reglement über das Naturschutzgebiet Bäz in Andermatt (RB 10.5117) | 1 | as enacted, 1 January 2012 |
| `10-5118/` | Reglement über den Schutz der Gewässer im Gebiet Uri Mitte zwischen Silenen und Göschenen (RB 10.5118) | 1 | as enacted, 1 January 2016 |
| `10-5119/` | Reglement über den Schutz der Gewässer im Urserntal (RB 10.5119) | 1 | as enacted, 2 June 2015 |
| `10-5122/` | Reglement über den Schutz der Gewässer im Gebiet Uri Nord zwischen dem Urnersee und Erstfeld (RB 10.5122) | 1 | as enacted, 15 October 2020 |
| `10-5126/` | Reglement über den Schutz der Aue Widen und weiterer Lebensräume entlang der Furkareuss zwischen Realp und Hospental (RB 10.5126) | 1 | as enacted, 1 October 2024 |
| `10-5127/` | Reglement über den Schutz der Aue Rüti am Vorderschächen in der Gemeinde Unterschächen (RB 10.5127) | 1 | as enacted, 1 May 2023 |
| `10-5131/` | Reglement über den Schutz wildwachsender Pilze (RB 10.5131) | 1 | one version (the oldest available), 1 May 2007 |
| `10-5132/` | Reglement über den Schutz der Landschaft Unteralptal in der Gemeinde Andermatt (RB 10.5132) | 1 | as enacted, 1 January 2026 |
| `10-5133/` | Reglement über den Schutz der Flachmoore auf dem Oberalppass in der Gemeinde Andermatt (RB 10.5133) | 1 | as enacted, 1 January 2026 |
| `10-5134/` | Reglement über den Schutz des Amphibienlaichgebiets Bodenwald in der Gemeinde Attinghausen (RB 10.5134) | 1 | as enacted, 1 October 2024 |
| `10-5135/` | Reglement über den Schutz des BLN-Objekts Scheidnössli und angrenzender Lebensräume in der Gemeinde Erstfeld (RB 10.5135) | 1 | as enacted, 1 July 2024 |
| `10-6115/` | Verordnung über die Unterstützung der Kantonsbibliothek Uri (RB 10.6115) | 1 | as enacted, 1 January 2001 |
| `10-6212/` | Archivreglement (RB 10.6212) | 1 | as enacted, 1 July 2002 |
| `10-6240/` | Reglement über die Umsetzung des Covid-19-Gesetzes im Kulturbereich und der Covid-19-Kulturverordnung im Kanton Uri (RB 10.6240) | 1 | one version (the oldest available), 1 January 2022 |
| `10-8211/` | Verordnung über die Förderung von Kunst und Bau (RB 10.8211) | 1 | as enacted, 1 July 2024 |
| `20-1101/` | Verordnung über die Errichtung eines kantonalen Einigungsamtes (RB 20.1101) | 1 | one version (the oldest available), 1 June 1995 |
| `20-1111-kav/` | Kantonale Arbeitsverordnung (RB 20.1111) | 1 | as enacted, 1 February 2002 |
| `20-1311/` | Reglement über den Normalarbeitsvertrag für hauswirtschaftliche Arbeitnehmer (RB 20.1311) | 1 | one version (the oldest available), 1 January 2022 |
| `20-1321/` | Reglement über den Normalarbeitsvertrag für landwirtschaftliche Arbeitnehmer (RB 20.1321) | 1 | one version (the oldest available), 1 May 1998 |
| `20-1515/` | Reglement zum Bundesgesetz über die minimalen Arbeits- und Lohnbedingungen für in die Schweiz entsandte Arbeitnehmerinnen und Arbeitnehmer und flankierende Massnahmen (Entsendegesetz, EntsG) (RB 20.1515) | 1 | as enacted, 1 March 2005 |
| `20-2202/` | Verordnung zum Bundesgesetz über die Krankenversicherung (RB 20.2202) | 1 | one version (the oldest available), 1 November 2024 |
| `20-2204-zulassungsreglement/` | Reglement über die Zulassung von Leistungserbringern zur Tätigkeit zulasten der obligatorischen Krankenpflegeversicherung (RB 20.2204) | 2 | as enacted, then each consolidated version: 1 October 2023 to 1 October 2025 |
| `20-2210-pramienverbilligungsfonds/` | Reglement über den Fonds Prämienverbilligung für die Krankenpflege-Grundversicherung (RB 20.2210) | 1 | as enacted, 1 January 2021 |
| `20-2211/` | Reglement über die Nichtbezahlung von Prämien und Kostenbeteiligungen für die Krankenpflege-Grundversicherung (RB 20.2211) | 1 | one version (the oldest available), 1 January 2025 |
| `20-2213-pramienverbilligungsreglement-pvr/` | Reglement über die Prämienverbilligung für die Krankenpflege-Grundversicherung (RB 20.2213) | 1 | as enacted, 1 November 2024 |
| `20-2215/` | Verordnung über die Einführung der Bundesgesetzgebung über die Unfallversicherung (RB 20.2215) | 1 | as enacted, 1 January 1984 |
| `20-2216/` | Reglement über die Einführung der Bundesgesetzgebung über die Unfallversicherung (RB 20.2216) | 1 | as enacted, 1 January 1984 |
| `20-2221/` | Verordnung über die Rechtspflege in der Unfallversicherung (RB 20.2221) | 1 | one version (the oldest available), 1 June 1995 |
| `20-2235/` | Verordnung über die Akut- und Übergangspflege (RB 20.2235) | 1 | as enacted, 1 January 2011 |
| `20-2237/` | Verordnung zum Bundesgesetz über die Förderung der Ausbildung im Bereich der Pflege (RB 20.2237) | 1 | as enacted, 1 July 2024 |
| `20-2239/` | Reglement zum Bundesgesetz über die Förderung der Ausbildung im Bereich der Pflege (RB 20.2239) | 1 | as enacted, 1 July 2024 |
| `20-2311-arbeitsmassnahmeverordnung-amv/` | Verordnung über die Arbeitsvermittlung, die Arbeitsbeschaffung und die Arbeitslosenversicherung (RB 20.2311) | 1 | one version (the oldest available), 1 September 2008 |
| `20-2313-arbeitsmassnahmereglement-amr/` | Reglement über die ergänzenden kantonalen Massnahmen zur beruflichen Wiedereingliederung (RB 20.2313) | 1 | one version (the oldest available), 1 February 2007 |
| `20-2315/` | Reglement für die kantonale Arbeitslosenkasse Uri (RB 20.2315) | 1 | as enacted, 1 January 1984 |
| `20-2332/` | Verordnung über die Patientenbeteiligung in der Langzeitpflege (RB 20.2332) | 1 | one version (the oldest available), 1 January 2021 |
| `20-2411/` | Verordnung über die Sozialversicherungsstelle Uri (RB 20.2411) | 1 | as enacted, 1 January 2013 |
| `20-2413/` | Reglement der kantonalen Rekurskommission für die Alters- und Hinterlassenenversicherung (RB 20.2413) | 1 | one version (the oldest available), 1 June 1995 |
| `20-2425/` | Verordnung über die Ergänzungsleistungen zur AHV/IV (RB 20.2425) | 1 | one version (the oldest available), 1 January 2011 |
| `20-2435/` | Reglement über die Vergütung von Krankheits- und Behinderungskosten bei Ergänzungsleistungen (RB 20.2435) | 1 | as enacted, 1 January 2020 |
| `20-2513-fzr/` | Reglement zum Gesetz über die Familienzulagen (RB 20.2513) | 2 | oldest version available, then each consolidated version: 1 January 2023 to 1 January 2026 |
| `20-2521/` | Verordnung zum Bundesgesetz über die Familienzulagen in der Landwirtschaft (RB 20.2521) | 1 | one version (the oldest available), 1 January 2008 |
| `20-2611/` | Kantonale Vollziehungsverordnung zum Bundesgesetz über die Erwerbsausfallentschädigungen an Wehrpflichtige (RB 20.2611) | 1 | one version (the oldest available), 1 June 1995 |
| `20-2715/` | Reglement zum Bundesgesetz über die berufliche Alters-, Hinterlassenen- und Invalidenversicherung (RB 20.2715) | 1 | as enacted, 1 January 2006 |
| `20-3223-ksuv/` | Verordnung über das Kantonsspital Uri (RB 20.3223) | 1 | as enacted, 1 July 2023 |
| `20-3311/` | Kantonale Vollziehungsverordnung zum Bundesgesetz vom 19. März 1965 über Massnahmen zur Förderung des Wohnungsbaues (RB 20.3311) | 1 | one version (the oldest available), 1 March 1983 |
| `20-3321/` | Verordnung über die Verbesserung der Wohnverhältnisse in Berggebieten (RB 20.3321) | 1 | as enacted, 1 January 2008 |
| `20-3325-rvw/` | Reglement über die Verbesserung der Wohnverhältnisse in Berggebieten (RB 20.3325) | 1 | as enacted, 1 January 2008 |
| `20-3331/` | Verordnung über die Wohnbau- und Eigentumsförderung (RB 20.3331) | 1 | as enacted, 1 April 1994 |
| `20-3425-bsr/` | Reglement über die Baubeiträge nach dem Sozialhilfegesetz (RB 20.3425) | 1 | one version (the oldest available), 1 January 2008 |
| `20-3447/` | Verordnung über die Institutionen der Behindertenhilfe (RB 20.3447) | 1 | one version (the oldest available), 1 January 2015 |
| `20-3449/` | Verordnung über Betreuungseinrichtungen (RB 20.3449) | 1 | as enacted, 1 January 2019 |
| `20-3455/` | Reglement über die Schwangerschafts-, Ehe- und Familienberatungsstellen (RB 20.3455) | 1 | as enacted, 1 January 1990 |
| `20-3456-ohr/` | Opferhilfereglement (RB 20.3456) | 1 | as enacted, 1 July 2003 |
| `30-2115-heilmittelreglement/` | Reglement über den Vollzug des Heilmittelgesetzes (RB 30.2115) | 1 | as enacted, 1 April 2022 |
| `30-2117/` | Reglement über die Berufe und Organisationen im Gesundheitswesen (RB 30.2117) | 1 | one version (the oldest available), 1 September 2023 |
| `30-2122/` | Reglement über die amtlichen Medizinalpersonen (RB 30.2122) | 2 | as enacted, then each consolidated version: 1 January 2009 to 1 September 2018 |
| `30-2135/` | Verordnung über die Bereitschaftsentschädigung für Hebammen (RB 30.2135) | 1 | as enacted, 1 January 2018 |
| `30-2145/` | Reglement zum Schutz vor Passivrauchen (RB 30.2145) | 1 | as enacted, 1 May 2010 |
| `30-2215-epidemienreglement/` | Reglement über den Vollzug der eidgenössischen Epidemiengesetzgebung (RB 30.2215) | 1 | as enacted, 1 September 2020 |
| `30-2311-klmv/` | Kantonale Lebensmittelverordnung (RB 30.2311) | 1 | as enacted, 1 January 2011 |
| `30-2325/` | Reglement über die Gebühren der Fleischschauer (RB 30.2325) | 1 | as enacted, 1 June 1994 |
| `30-3115/` | Reglement zum Gesetz über den Feuerschutz (RB 30.3115) | 1 | as enacted, 1 March 1997 |
| `30-3117-stutzpunktfeuerwehrreglement-sfwr/` | Reglement über die Stützpunktfeuerwehren (RB 30.3117) | 1 | as enacted, 1 January 2010 |
| `30-3312/` | Verordnung über die Beitragspflicht sowie die Verwendung der Löschsteuer und freiwilligen Beiträge der im Kanton Uri arbeitenden Feuerversicherungs-Gesellschaften (RB 30.3312) | 1 | as enacted, 6 July 1959 |
| `30-3313-ffr/` | Reglement über den kantonalen Feuerlöschfonds (RB 30.3313) | 1 | one version (the oldest available), 1 January 2019 |
| `30-4111/` | Verordnung zum Bundesgesetz über explosionsgefährliche Stoffe (RB 30.4111) | 1 | one version (the oldest available), 1 June 1995 |
| `30-4321/` | Kantonale Vollziehungsverordnung zum Bundesgesetz über die Sicherheit von technischen Einrichtungen und Geräten (RB 30.4321) | 1 | one version (the oldest available), 1 June 1995 |
| `30-4415/` | Reglement zur Bundesgesetzgebung über Waffen, Waffenzubehör und Munition (RB 30.4415) | 1 | as enacted, 1 July 1999 |
| `40-1115-rpbg/` | Reglement zum Planungs- und Baugesetz (RB 40.1115) | 2 | oldest version available, then each consolidated version: 1 January 2018 to 1 July 2026 |
| `40-1227/` | Reglement über die Kommission für das Reussdelta (RB 40.1227) | 1 | one version (the oldest available), 1 March 2015 |
| `40-1405/` | Reglement über die Bemessung der Kantonshilfe bei Elementarschäden (RB 40.1405) | 1 | one version (the oldest available), 1 January 2023 |
| `40-2111-kwv/` | Kantonale Waldverordnung (RB 40.2111) | 1 | one version (the oldest available), 1 April 2019 |
| `40-2115/` | Kantonales Waldreglement (RB 40.2115) | 1 | one version (the oldest available), 1 January 2020 |
| `40-2211/` | Verordnung über das Beerensammeln (RB 40.2211) | 1 | as enacted, 15 July 1932 |
| `40-3111-jagdverordnung-kjsv/` | Verordnung zum Bundesgesetz über die Jagd und den Schutz wildlebender Säugetiere und Vögel (RB 40.3111) | 1 | one version (the oldest available), 1 February 2024 |
| `40-3121-jagdbetriebsvorschriften/` | Reglement über die Ausübung der Jagd (RB 40.3121) | 1 | one version (the oldest available), 1 June 2024 |
| `40-3152/` | Reglement über den Jagdlehrgang und die Jägerprüfung (RB 40.3152) | 1 | one version (the oldest available), 1 January 2025 |
| `40-3154/` | Reglement über die Kontrolle und das Einschiessen von Jagdwaffen (RB 40.3154) | 1 | one version (the oldest available), 15 March 2020 |
| `40-3156-hegereglement/` | Reglement über die Hege (RB 40.3156) | 1 | one version (the oldest available), 1 February 2024 |
| `40-3161/` | Wildschadenreglement (RB 40.3161) | 1 | one version (the oldest available), 1 March 2017 |
| `40-3211/` | Verordnung über die Fischerei (RB 40.3211) | 1 | one version (the oldest available), 1 January 2015 |
| `40-3215/` | Fischereireglement (RB 40.3215) | 1 | one version (the oldest available), 1 December 2024 |
| `40-3217/` | Reglement über den Fischereifonds (RB 40.3217) | 1 | as enacted, 1 April 2022 |
| `40-4105-gnv/` | Gewässernutzungsverordnung (RB 40.4105) | 1 | one version (the oldest available), 1 January 2025 |
| `40-4111/` | Verordnung über die Ausbeutung öffentlicher Gewässer (RB 40.4111) | 1 | one version (the oldest available), 1 April 1993 |
| `40-4325-schadenwehrverordnung/` | Verordnung über die Schadenwehr (RB 40.4325) | 1 | as enacted, 1 July 2017 |
| `40-4328-schadenwehrreglement/` | Reglement über die Entschädigung der Schadenwehr (RB 40.4328) | 1 | as enacted, 1 July 2017 |
| `40-4335-snr/` | Reglement über den Fonds Schadenwehr Nationalstrassen (RB 40.4335) | 1 | as enacted, 1 January 2025 |
| `40-6111-vsg/` | Verordnung zum Stromversorgungsgesetz (RB 40.6111) | 1 | as enacted, 1 January 2009 |
| `40-7015-kuv/` | Kantonale Umweltverordnung (RB 40.7015) | 1 | one version (the oldest available), 1 January 2009 |
| `40-7017-uvpr/` | Reglement über die Umweltverträglichkeitsprüfung (RB 40.7017) | 1 | one version (the oldest available), 1 January 2018 |
| `40-7025-rgwp/` | Reglement über die Generelle Wasserversorgungsplanung (RB 40.7025) | 1 | as enacted, 1 October 2025 |
| `40-7040/` | Reglement über die Aufgaben und Zuständigkeiten in der Chemikaliengesetzgebung (RB 40.7040) | 1 | as enacted, 1 April 2015 |
| `40-7110/` | Reglement zur Partikelfilterpflicht für stationäre, dieselbetriebene Maschinen, Geräte und Motoren (RB 40.7110) | 1 | as enacted, 1 November 2014 |
| `40-7115-smog-reglement/` | Reglement über zeitlich begrenzte Sofortmassnahmen bei gesundheitsgefährdenden Luftbelastungen (RB 40.7115) | 1 | one version (the oldest available), 1 January 2010 |
| `40-7213-env/` | Energieverordnung (RB 40.7213) | 1 | as enacted, 1 October 2026 |
| `40-7215-enr/` | Energiereglement (RB 40.7215) | 2 | oldest version available, then each consolidated version: 1 January 2023 to 1 October 2026 |
| `40-7219/` | Reglement über den Fonds Förderprogramm Energie Uri (RB 40.7219) | 1 | as enacted, 23 October 2018 |
| `50-1113-strr/` | Strassenreglement (RB 50.1113) | 1 | as enacted, 1 January 2014 |
| `50-1133/` | Reglement über das Verfahren zum freihändigen Landerwerb für den Nationalstrassenbau (RB 50.1133) | 1 | as enacted, 16 June 1969 |
| `50-1135/` | Reglement über das Amt für Betrieb Nationalstrassen (RB 50.1135) | 2 | oldest version available, then each consolidated version: 1 January 2024 to 1 April 2026 |
| `50-1138-rbs/` | Reglement über den Betrieb des Schwerverkehrszentrums (RB 50.1138) | 1 | as enacted, 1 January 2008 |
| `50-1165/` | Reglement über den Fonds «Weg der Schweiz» (RB 50.1165) | 1 | as enacted, 1 January 2020 |
| `50-1311/` | Verordnung über den Strassenverkehr (RB 50.1311) | 1 | as enacted, 1 September 2015 |
| `50-1315/` | Reglement über die kantonale Bewilligung nach der Personenbeförderungskonzession des Bundes (RB 50.1315) | 1 | as enacted, 1 July 1999 |
| `50-1413/` | Verordnung über die Strassenverkehrssteuern (RB 50.1413) | 1 | as enacted, 1 January 1998 |
| `50-1421-perimeterordnung/` | Verordnung über die Erhebung von Perimeterbeiträgen an Strassen (RB 50.1421) | 1 | one version (the oldest available), 1 January 2012 |
| `50-2111-binnenschifffahrtsverordnung-kbsv/` | Kantonale Vollziehungsverordnung zum Bundesgesetz über die Binnenschifffahrt (RB 50.2111) | 1 | one version (the oldest available), 1 November 2023 |
| `50-2115/` | Reglement über die Beschränkung der Schifffahrt und des Surfersports (RB 50.2115) | 1 | one version (the oldest available), 1 February 2016 |
| `50-2117-einwasserungsreglement-ewr/` | Reglement über die Einwasserung von Schiffen (RB 50.2117) | 1 | as enacted, 1 August 2024 |
| `50-3215-seilbahnreglement/` | Reglement über die Luftseilbahnen mit Personenbeförderung ohne Bundeskonzession und über die Skilifte (RB 50.3215) | 1 | one version (the oldest available), 1 January 2014 |
| `50-3305/` | Reglement zum Bundesgesetz über die Anschlussgleise (RB 50.3305) | 1 | as enacted, 1 January 1993 |
| `50-5115/` | Verordnung zum Verkehrsgesetz (RB 50.5115) | 2 | oldest version available, then each consolidated version: 1 January 2008 to 1 January 2026 |
| `60-1111-klwv/` | Kantonale Landwirtschaftsverordnung (RB 60.1111) | 2 | oldest version available, then each consolidated version: 1 January 2019 to 1 April 2026 |
| `60-1113-klwr/` | Kantonales Landwirtschaftsreglement (RB 60.1113) | 2 | oldest version available, then each consolidated version: 1 January 2023 to 1 August 2026 |
| `60-2111/` | Veterinärverordnung (RB 60.2111) | 1 | one version (the oldest available), 1 January 2024 |
| `60-2113/` | Veterinärreglement (RB 60.2113) | 1 | as enacted, 1 January 2017 |
| `60-3231-weinreglement/` | Reglement über den Rebbau und die kontrollierte Ursprungsbezeichnung für Weine (RB 60.3231) | 1 | as enacted, 1 June 2009 |
| `60-4111-lpv/` | Verordnung zum Bundesgesetz über die landwirtschaftliche Pacht (RB 60.4111) | 1 | one version (the oldest available), 1 January 2011 |
| `70-1103-bwv/` | Verordnung über die Berufs- und Weiterbildung (RB 70.1103) | 1 | one version (the oldest available), 1 January 2023 |
| `70-1105-bwr/` | Reglement über die Berufs- und Weiterbildung (RB 70.1105) | 1 | one version (the oldest available), 1 January 2011 |
| `70-1107-bfsr/` | Reglement über die Rechte und Pflichten der Lernenden an der Berufsfachschule (RB 70.1107) | 1 | one version (the oldest available), 1 August 2014 |
| `70-1125/` | Reglement über die Berufsmaturitätsschule (RB 70.1125) | 2 | oldest version available, then each consolidated version: 1 August 2023 to 1 March 2026 |
| `70-1131/` | Reglement über die Berufsvorbereitungsschule (RB 70.1131) | 2 | oldest version available, then each consolidated version: 1 August 2017 to 1 August 2026 |
| `70-1211/` | Reglement über das Messwesen (RB 70.1211) | 1 | one version (the oldest available), 1 January 2014 |
| `70-1312-ukbv/` | Verordnung über die Urner Kantonalbank (RB 70.1312) | 1 | one version (the oldest available), 1 January 2015 |
| `70-1411/` | Verordnung über das Reklamewesen (RB 70.1411) | 1 | one version (the oldest available), 1 January 2019 |
| `70-1615-covid-19-hartefallreglement/` | Reglement über die Umsetzung von Härtefallmassnahmen für Unternehmen im Zusammenhang mit der COVID-19-Epidemie (RB 70.1615) | 1 | as enacted, 10 February 2022 |
| `70-1621/` | Verordnung über die steuerbegünstigten Arbeitsbeschaffungsreserven (RB 70.1621) | 1 | as enacted, 1 June 1990 |
| `70-2115-gwr/` | Reglement der Abgaben zum Gastwirtschaftsgesetz (RB 70.2115) | 1 | as enacted, 1 January 2006 |
| `70-2117/` | Reglement über die befristete Senkung der Abgaben zum Gastwirtschaftsgesetz (RB 70.2117) | 1 | as enacted, 1 January 2021 |
| `70-2322-risikoaktivitatenreglement-riskr/` | Einführungsreglement zum Bundesgesetz über das Bergführerwesen und Anbieten weiterer Risikoaktivitäten (RB 70.2322) | 1 | as enacted, 1 January 2014 |
| `70-2415-tourismusreglement-tourr/` | Reglement über die Förderung des Tourismus (RB 70.2415) | 1 | as enacted, 1 January 2013 |
| `70-2431-campingverordnung/` | Verordnung über Errichtung und Betrieb von öffentlichen Zeltplätzen (RB 70.2431) | 1 | one version (the oldest available), 1 June 1995 |
| `70-3121/` | Reglement zum Bundesgesetz über das Gewerbe der Reisenden (RB 70.3121) | 1 | as enacted, 1 August 2003 |
| `70-3915-geldspielverordnung-gsv/` | Verordnung über Geldspiele (RB 70.3915) | 1 | as enacted, 1 January 2021 |
| `70-3917-geldspielreglement-gsr/` | Reglement über Geldspiele (RB 70.3917) | 1 | one version (the oldest available), 1 October 2024 |

## Source

The RB (systematic collection) of the canton, published by the canton at <https://rechtsbuch.ur.ch/>. For each act it gives every consolidated version it holds, with the day each version took effect, and a change table listing each amendment: its decision date, the day it took effect, the provision it touched and its entry in the chronological collection (CRS). Annexes the collection publishes only as separate PDF files are not included.

## Dates

- Each commit is dated at **noon, Europe/Zurich, on the day the version took effect**, as the collection gives it ("in Kraft seit / von"). The decision date of each amending act is the `Enacted:` trailer.
- An act's first commit is its oldest version in the collection. It is credited to the act as enacted only when the change table shows no amendment in force before it; otherwise it is the "oldest version available", naming the earlier amendments.
- Versions that take effect after the retrieval day are on the `zukunft` branch, never merged into `main`.
- `--before="YYYY-MM-DD"` alone uses your clock's time of day; use `T23:59:59Z` or `tools/on.py`.

## Files

`<act>/art-005.md` is Art. 5 (or § 5), `art-005a.md` Art. 5a; `ingress.md` holds the title, date and preamble; `gliederung.md` the section headings; `schluss.md` the closing formula and signatures. One paragraph or list item per line. Amendment markers (`*`), footnote numbers and the "Stand" date are left out.

## How it is checked

- Every version of every act is read back from git on the day it took effect and on the day before (`tools/check_repo.py`); both must match `corpus.json`.
- The letters and digits of every version equal those of the canton's own text of that version, and every article's text appears in it in order.
- Health checks: no merge commits, commit dates never go backwards, nothing dated in the future, and every commit's trailers parse.

## What "author" means

The author of a commit is the amending act, named by its entry in the chronological collection (CRS), with an e-mail address that cannot exist (`<act key>@rechtsbuch.ur.ch.invalid`). Where one version holds changes by several amending acts and the change table does not say which provision each one touched, the commit names them all. The committer is always Lexifina.

## Limits

This is not an official publication. The binding text is the one the canton publishes as binding (its chronological collection, or its systematic collection where cantonal law makes that binding). The history starts with the oldest consolidated version the collection holds for each act, which for many acts is later than the act's enactment. Only the acts listed above are included.
