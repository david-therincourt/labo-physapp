# Labo Physapp

## Amplificateurs opérationnels et comparateurs

| Référence | Type                  | Fonction principale                                | Qté |
| --------- | --------------------- | -------------------------------------------------- | --- |
| AD595     | AO spécialisé         | Conditionneur thermocouple type K, sortie 10 mV/°C |     |
| AD623A    | Ampli instrumentation | Gain réglable par 1 résistance (×1 à ×1000)        |     |
| AD711     | AO BiFET précision    | Faible offset, faible bruit, usage général         |     |
| AD8221    | Ampli instrumentation | Haute précision, faible bruit, CMRR élevé          |     |
| CA3130    | AO CMOS/BiMOS         | Entrée MOSFET, sortie rail-to-rail                 |     |
| CA3140    | AO BiMOS              | Très haute impédance d'entrée (MOSFET)             |     |
| INA132    | Ampli instrumentation | Gain fixe ×1/×2/×5/×10 selon câblage               |     |
| LF356     | AO BiFET              | Haute impédance, faible courant de biais           |     |
| LF357     | AO BiFET rapide       | Slew rate élevé, compensation externe              |     |
| LM308     | AO précision          | Faible consommation, faible offset                 |     |
| LM311N    | Comparateur           | Sortie collecteur ouvert (boîtier DIP)             |     |
| LM311P    | Comparateur           | Sortie collecteur ouvert, usage général            |     |
| LM324     | AO ×4                 | Quad AO alimentation simple, faible coût           |     |
| LM339N    | Comparateur ×4        | Quad comparateur, sortie collecteur ouvert         |     |
| LM358     | AO ×2                 | Dual AO alimentation simple                        |     |
| LM386N    | Ampli audio           | Ampli BF, gain ×20 à ×200, sortie HP               |     |
| LM393     | Comparateur ×2        | Dual comparateur, sortie collecteur ouvert         |     |
| LM833     | AO audio ×2           | Dual AO faible bruit, optimisé audio               |     |
| LM13600   | OTA ×2                | Transconductance variable, tampon de sortie        |     |
| LM13700   | OTA ×2                | OTA amélioré, diodes de linéarisation intégrées    |     |
| LMC64     | AO CMOS ×4            | Quad rail-to-rail, très faible courant d'entrée    |     |
| MAX412    | AO précision          | Faible bruit, faible offset, rail-to-rail          |     |
| MCP602    | AO CMOS ×2            | Dual AO rail-to-rail, faible consommation          |     |
| NE5532    | AO audio ×2           | Dual AO faible bruit, référence audio              |     |
| OP497     | AO précision ×4       | Quad AO, très faible offset et dérive              |     |
| SFC2458   | AO ×2                 | Dual AO généraliste (équiv. LM358)                 |     |
| TDB0157   | Ampli différentiel    | Ampli différentiel/instrumentation                 |     |
| TL071     | AO BiFET              | AO JFET faible bruit, usage général                |     |
| TL081     | AO BiFET              | AO JFET usage général, faible courant de biais     |     |
| TL082     | AO BiFET ×2           | Dual AO JFET, faible bruit                         |     |
| TL084     | AO BiFET ×4           | Quad AO JFET, faible bruit                         |     |
| µA741     | AO classique          | AO universel historique, référence pédagogique     |     |

## Circuits spécialisés

| Référence | Type                    | Fonction principale                                       | Qté |
| --------- | ----------------------- | --------------------------------------------------------- | --- |
| AD534     | Multiplieur analogique  | Multiplieur/diviseur 4 quadrants, précision               |     |
| AD633     | Multiplieur analogique  | Multiplieur 4 quadrants, faible coût                      |     |
| AD652     | Convertisseur V/F       | Tension → Fréquence, haute précision                      |     |
| AD7569    | CAN/CNA                 | CAN + CNA 8 bits intégrés sur puce                        |     |
| CY8C24173 | µC PSoC                 | Microcontrôleur Cypress PSoC (analogique programmable)    |     |
| DAC08     | CNA 8 bits              | Convertisseur numérique-analogique 8 bits rapide          |     |
| DS1803    | Potentiomètre numérique | Dual potentiomètre numérique, interface I²C               |     |
| LM2907    | Convertisseur F/V       | Fréquence → Tension (tachymètre)                          |     |
| MAX038    | Générateur de fonctions | Sinus/triangle/carré, fréquence programmable              |     |
| MC14046   | PLL CMOS                | Boucle à verrouillage de phase (VCO + comparateurs)       |     |
| MC14066   | Interrupteur CMOS       | Quad switch analogique CMOS (série 4000)                  |     |
| MCP4902   | CNA 8 bits ×2           | Dual CNA 8 bits, interface SPI                            |     |
| MCP4922   | CNA 12 bits ×2          | Dual CNA 12 bits, interface SPI                           |     |
| MF10      | Filtre commuté ×2       | Dual filtre à capacités commutées, fréquence programmable |     |
| NE555N    | Temporisateur           | Timer monostable/astable classique                        |     |
| NE555CN   | Temporisateur           | Idem NE555N (boîtier céramique)                           |     |
| NE556CN   | Temporisateur ×2        | Dual timer 555                                            |     |
| PCF8574   | Expandeur I²C           | Expander 8 bits I/O via I²C                               |     |
| SMP04EPZ  | Sample & Hold ×4        | Quad échantillonneur-bloqueur                             |     |
| UC2950T   | Superviseur tension     | Détecteur de sous-tension / reset                         |     |
| 4066      | Interrupteur analogique | Quad switch analogique CMOS                               |     |
| ZN426     | CNA 8 bits              | Convertisseur numérique-analogique 8 bits                 |     |



## Régulateurs de tension / Alimentation

| Référence  | Type                     | Fonction principale                               | Qté |
| ---------- | ------------------------ | ------------------------------------------------- | --- |
| 7805       | Régulateur linéaire fixe | +5 V, 1 A (série 78xx)                            |     |
| 7806       | Régulateur linéaire fixe | +6 V, 1 A (série 78xx)                            |     |
| 7808       | Régulateur linéaire fixe | +8 V, 1 A (série 78xx)                            |     |
| 7809       | Régulateur linéaire fixe | +9 V, 1 A (série 78xx)                            |     |
| 7812       | Régulateur linéaire fixe | +12 V, 1 A (série 78xx)                           |     |
| 7612       | Régulateur linéaire fixe | +12 V (variante série 76xx)                       |     |
| 7905       | Régulateur linéaire fixe | −5 V, 1 A (série 79xx, tension négative)          |     |
| Alim. déc. | Découplage               | Condensateurs/module de découplage d'alimentation |     |
| DC/DC      | Convertisseur DC/DC      | Convertisseur à découpage isolé (module)          |     |
| DI06N8     | Pont redresseur          | Pont de diodes monophasé                          |     |
| KA317      | Régulateur ajustable     | Équiv. LM317 (fabricant Samsung/Fairchild)        |     |
| L200C      | Régulateur ajustable     | Tension et courant de sortie ajustables           |     |
| L4815      | Régulateur linéaire fixe | +15 V, 1 A (série 78xx)                           |     |
| LM317      | Régulateur ajustable     | +1,25 V à +37 V ajustable, 1,5 A                  |     |
| LM723      | Régulateur ajustable     | 2 V à 37 V, faible courant, classique             |     |
| MC3423P    | Détecteur de surtension  | Protection surtension par circuit crowbar         |     |
| Reg. 3,3 V | Régulateur LDO fixe      | 3,3 V (référence non précisée)                    |     |
| Reg. 5 V   | Régulateur LDO fixe      | 5 V (référence non précisée)                      |     |
| SFC2741    | Régulateur               | Régulateur de tension (série SFC)                 |     |
| TDB039     | Régulateur               | Régulateur de tension (équiv. 78xx)               |     |
| TL431CP    | Référence de tension     | Référence ajustable 2,5 V–36 V (shunt)            |     |
| UA723      | Régulateur ajustable     | Équiv. LM723 (fabricant différent)                |     |
