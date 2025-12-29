# Vlada Republike Hrvatske – tijela u sastavu (dijagrami)

---

## Vlada Republike Hrvatske – osnovna struktura

```mermaid
flowchart TB
    VRH[Vlada Republike Hrvatske]
    VRH --> PRED[Predsjednik Vlade]
    VRH --> POTP[Potpredsjednici Vlade]
    VRH --> MIN[Ministri]
```


```mermaid
flowchart TB
    UZK[Uži kabinet Vlade]
    UZK --> PRED[Predsjednik Vlade]
    UZK --> POTP[Potpredsjednici Vlade]

    NOTE1[[Ministri nisu članovi Užeg kabineta]]
```

## Uži kabinet Vlade

```mermaid
flowchart TB
    UZK[Uži kabinet Vlade]
    UZK --> PRED[Predsjednik Vlade]
    UZK --> POTP[Potpredsjednici Vlade]

    NOTE1[[Ministri nisu članovi Užeg kabineta]]
```

## Ured predsjednika Vlade

```mermaid
flowchart TB
    UPV[Ured predsjednika Vlade]
    UPV --> PREDST[Predstojnik Ureda]
    PREDST --> STATUS[Državni dužnosnik]
    PREDST --> OV[Ovlasti čelnika tijela državne uprave]
```

## Glavno tajništvo Vlade

```mermaid
flowchart TB
    GT[Glavno tajništvo Vlade]
    GT --> GTJ[Glavni tajnik]
    GTJ --> STATUS[Državni dužnosnik]
    GTJ --> OV[Ovlasti čelnika tijela državne uprave]
    GT --> ZAM[Zamjenik glavnog tajnika]
```

## Uredi i druge stručne službe Vlade

```mermaid
flowchart TB
    VLADA[Vlada RH]
    VLADA --> UREDI[Uredi i stručne službe Vlade]

    UREDI --> OSN[Osnivaju se **uredbom Vlade**]

    UREDI --> RAV[Ravnatelj]
    RAV --> STATUS[Državni službenik]

```


## Stalna radna tijela Vlade

```mermaid
flowchart TB
    SRJ[Stalna radna tijela Vlade]
    SRJ --> POS[**Osnivaju se Poslovnikom Vlade**]
    SRJ --> PRED[Predsjedava potpredsjednik Vlade]
```

## Povremena radna tijela Vlade

```mermaid
flowchart TB
    PRJ[Povremena radna tijela Vlade]
    PRJ --> ODL[Osnivaju se **odlukom** Vlade]
```
## Povjerenstva Vlade

```mermaid
flowchart TB
    POV[Povjerenstva Vlade]
    POV --> UPR[Rješavaju upravne stvari]
    POV --> SPOR[Protiv rješenja: upravni spor]
```
## Mentalna mapa – brzo ponavljanje

```mermaid
mindmap
  root((Vlada RH))
    Predsjednik
    Potpredsjednici
    Ministri
    Uži kabinet
      Predsjednik
      Potpredsjednici
    Ured predsjednika Vlade
      Predstojnik (dužnosnik)
    Glavno tajništvo
      Glavni tajnik (dužnosnik)
    Uredi i službe
      Ravnatelji (službenici)
    Radna tijela
      Stalna
      Povremena
    Povjerenstva
```
