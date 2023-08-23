# Modyfikacja Switcha Mikrotik CRS326-24G-2S+RM.
## Instalacja wewnętrznego zasilacza i wentylatora.

> [!WARNING]
> Prace montażowe przy napięciu 230V wymagają odpowiednich kwalifikacji i doświadczenia.
> Poniższe opracowanie jest tylko dokumentacją prac w powyższym temacie.

  Temperatura CPU w wyniku modyfikacji 69 -> **33** stopni Celcjiusza.

### Wykorzystane akcesoria:

- Gniazdo Zasilające AC IEC C14 IBM (Schurter 6100.3300)
![](https://github.com/dMbski/mod-CRS326-intPS-FAN/blob/f8333734e8bbd605ca0092e646631674a3d16567/images/Schurter-6100-3300.png)
![](images/Schurter-6100-3300photo.jpg)

- Śrubki mocujące z nakrętkami M3, długość ok 6mm (M3x6mm) płaska lub stożkowa.

- Dioda Schottky obudowa SMB lub SMA: B340LB-13-F (SMB), **SS34A** (SMA):

  Prąd przewodzenia: 3A, Napięcie wsteczne: 40V, Obudowa: DO214AC (SMA) lub DO-214AA (SMB)

  [Karta charektyrystyki B340LB ](/images/B340LA_B.pdf), [karta charakterystyki SS34](/images/ss32.pdf)

- Wentylator 4020 24V DC (wymiary: 40mm x 40mm x 20mm): Sunon MF40202V2-1000U-A99
  
  [Karta charakterystyki wentylatora](/images/Sunon_MF40202V2_1000U_A99D04115160G_010-3078676.pdf)

- Śrubki mocujące: M3x25mm z nakrętkami lub wkręty do wentylatora (wymagane rozwiercenie otworów w obudowie switcha do 5mm)
- Zasilacz modułowy, impulsowy 24V DC: Mean Well LRS-50-24 24V 2.2A 52.8W
  
  [Karta charakterystyki zasilacza](/images/LRS-50-SPEC.PDF)

  [Wyskalowana maska wymiarów](/images/lrs50-dimensions.pdf) do wykonania otworów montażowych.

### Etapy prac:

1. Wykonanie otworów montażowych pod zasilacz.
    Wydrukować maskę z wymiarami zasilacza, umiejscowić i zaznaczyć miejsca wiercenia otworów montażowych (na wydruku strzałki).

      Odległość między otworami wynosi 55mm.
     ![](/images/p1.jpg)
3. Wybić zaślepkę gniazda zasilania.
4. Poszerzyć otwory mocowania wentylatora (tylko jeżeli korzystasz z wkrętów mocujących do wentylatorów 5mm).
5. Wyczyścić obudowę z metalowych wiórków.
6. Przygotować zaznaczone miejsca do lutowania. Wyczyścić IPA i posmarować topnikiem.

    ![](/images/p2.jpg)
7. Przylutować diodę Schotky'ego w miejscu D6 w kierunku takim samym jak dioda D1.

    ![](/images/p3.jpg)
8. Przylutować przewody zasilające. Odmierzyć długość do zasilacza ok 220mm.
9. Wyczyścić z resztek topnika.
10. Zabezpieczyć przewody zasilania DC. Klejem termo i rurką termokurczliwą (opcjonalnie). 

    ![](/images/p4.jpg)

11. Przygotować gniazdo AC. Przylutować i zabezpieczyć przewody.

12. Zamontować i zabezbieczyć gniazdo AC.

13. Zamontować zasilacz.

    **UWAGA!** Śrubki montażowe nie mogą być dłuższe niż **3mm** po stronie montażowej zasilacza.
    
16. Podłaczyć przewody zasilające AC i uziemnienie.

    ![](/images/p5.jpg)

    Na fotografii przewoód uziemnienia (GND) jest w kolorze niebieskim, powinien być żółto-zielony.

17. Zamontować wentylator, wylot na zewnątrz poza obudowę.
18. Podłączyć przewody zasilania DC switcha i wentylatora.

    ![](/images/p6.jpg)

19. Zmodyfikować otwory wentylacyjne podobnie jak na zdjęciu poniżej.    

    ![](/images/p7.jpg)
