# T02: Selecció d’un SAI per una empresa client

## 1. Inventari d’equips

- **4 ordinadors d’escriptori** (Lenovo A100 AIO, 24" Intel)  
  - Potència: 65 W  
  - VA: \(65\,W / 0,85 = 76,47\,VA\)
- **4 monitors** (Lenovo A100 AIO, 24" Intel)  
  - Potència: 65 W  
  - VA: \(65\,W / 0,85 = 76,47\,VA\)
- **1 impressora-fotocopiadora** (Brother DCP-L3560CDW Multifunció Làser LED Color WiFi Dúplex)  
  - Potència: 446 W  
  - VA: 700 VA  
- **1 router d’accés a Internet** (TP-Link TL-MR100 Router Wi-Fi N 4G LTE)  
  - Potència: 9 W  
  - VA: \(9\,W / 0.85 = 7,65\,VA\)

**Connexió al SAI:**  
- Sí: ordinadors, monitors i router  
- No: impressora multifunció (motiu: consum molt alt en imprimir, 300W que baixaria l’autonomia i no és per protegir dades)

## 2. Càlcul de potència total

**Dispositius connectats al SAI:**  
- 4 ordinadors + 4 monitors + 1 router

**Total Watts:**  
- 4 × 65 W (ordinadors) = 260 W  
- 4 × 65 W (monitors) = 260 W  
- Router = 9 W  
- **Total W = 260 + 260 + 9 = 529 W**

**Total VA:**  
- 4 × 76,47 VA (ordinadors) = 305,88 VA  
- 4 × 76,47 VA (monitors) = 305,88 VA  
- Router = 10,59 VA  
- **Total VA = 305,88 + 305,88 + 10,59 = 622,35 VA**

## 3. Determinació de l’autonomia

- **Objectiu:** Mantenir els equips en funcionament almenys 10 minuts per poder desar la feina i apagar els ordinadors amb seguretat.
- **Càrrega estimada total:** 1.360 W (inclou marge del 20%)

| Model SAI                  | Autonomia estimada | Observacions                                      |
|----------------------------|--------------------|---------------------------------------------------|
| Salicru SPS 2000 ONE V2    | 8–10 minuts        | 20 minuts en càrregues moderades (~50%-60%)       |
| CyberPower OL2200RTXL2U    | 10–15 minuts       | Eficiència millor, autonomia més estable           |

**Conclusió:**  
- Tots dos models compleixen el requisit mínim de 10 minuts, però el **CyberPower** ofereix una autonomia més estable i segura sota càrregues altes.

## 4. Recerca de models de SAI

- [Salicru SPS 2000 ONE V2 a Amazon](https://amzn.eu/d/0IQNmFm)
- [CyberPower OL2200RTXL2U a IT Planet](https://it-planet.com/es/p/cyberpower-ol2200ertxl2u-460125.html)

## 5. Informe tècnic — Comparativa SAI

### 1. Salicru SPS 2000 ONE V2
- **Potència:** 2000 VA / 1200 W
- **Autonomia:** fins a 20 minuts
- **Sortides:** 4 Schuko AC
- **Preu:** ~209 €
- **Tecnologia:** Line-interactive  
- **Observacions:** Econòmic, adequat per oficines petites, no ofereix ona sinusoïdal pura.

### 2. CyberPower OL2200RTXL2U
- **Potència:** 2200 VA / 1800 W
- **Autonomia:** 10–15 minuts
- **Sortides:** 8 IEC C13, 2 IEC C19
- **Preu:** ~1.318 €
- **Tecnologia:** Online (doble conversió)
- **Observacions:** Molt fiable, ofereix ona sinusoïdal pura, més car.

### Recomanació final

- **Si el pressupost és limitat:** El Salicru és suficient per a ús bàsic.
- **Si es vol màxima protecció i fiabilitat:** Triar el CyberPower OL2200RTXL2U.

