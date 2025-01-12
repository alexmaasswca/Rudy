# BOM

// Note 0: Many parts are 3d printable, i will mark them with 
a *. For testing, i'm using the 120mm bed but it should fit 150mm with about 140mm^2 usable print area.

// Note 1: feel free to buy the cheapest parts you find, there are added tolerances in the 
plastic parts that use the flexibility of PETG to let you pull everything square

| Thing | Price | Link |
| --- | --- | --- |
| Hardware |   |   |
| M3 T-nuts (optional) * | $5.70 | [link](https://www.aliexpress.com/item/32814359094.html?spm=a2g0o.order_list.order_list_main.11.145f1802vFsakT) |
| M3 sliding T-nuts x200 * (2020 series) | $9 | [link](https://www.aliexpress.com/item/1005002114332413.html?spm=a2g0o.productlist.main.5.3641402fC0BsdY) |
| M3x6 metric screws x200 |  |  |
| M3x35 metric screws x3 (or x4 with bigger bed) |  |  |
| M3x something between 10 and 20 x2 |  |  |
| M2x10 metric screws x2 (optional, hot glue is fine) |  |  |
| M5x30 metric screws x10 |  |  |
| M5 hex nut x2 |  |  |
| M3 (XD5.0XL4.0) inserts x100 (you need 20) | $7.34 | [link](https://www.aliexpress.com/item/4000232858343.html?spm=a2g0o.order_list.order_list_main.107.21ef1802qkslow) |
| --- | --- | --- |
| GT2 pulley x2 * | $6.34 | [link](https://www.aliexpress.com/item/32995102911.html?spm=a2g0o.order_list.order_list_main.107.145f1802vFsakT) |
| 6mm GT2 belt x3m | $7.61 | [link](https://www.aliexpress.com/item/902692789.html?spm=a2g0o.order_list.order_list_main.108.145f1802vFsakT) |
| F695 bearing x20 | $23 | [link](https://www.aliexpress.com/item/33001186278.html?spm=a2g0o.order_list.order_list_main.97.145f1802vFsakT) |
| Cheaper F695 (they work fine) | $11 | [link](https://www.aliexpress.com/item/1005004095001000.html) |
| 2020 extrusion 150mm x12 * | $32.75 | [link](https://www.aliexpress.com/item/33019355789.html?spm=a2g0o.cart.0.0.5c4138daTHlXeg&mp=1) |
| mgn9c rail 150mm x3 * | $30 | [link](https://www.aliexpress.com/item/1005003787436599.html?spm=a2g0o.productlist.main.13.18b842f5EcsFd3&algo_pvid=b4a6afa4-cb7e-4f33-8298-45ea8625b379) |
| mgn9c rail 100mm x2 * |  $17.20 | ^ |
| T8 leadscrew (100mm) P:2mm L:8mm| $2.50 | [link](https://www.aliexpress.com/item/1005002277808736.html?spm=a2g0o.cart.0.0.5c4138daTHlXeg&mp=1) |
| 5x8mm coupler * | $1 | [link](https://www.aliexpress.com/item/32693571252.html?spm=a2g0o.order_detail.order_detail_item.3.2ce7f19cw1xHpY) |
| 120mm voron 0 bed | $20 | [link](https://www.aliexpress.com/item/1005003229750626.html?spm=a2g0o.order_list.order_list_main.102.21ef1802qkslow) |
| OR 150mm reprap bed | $10 | [link](https://www.aliexpress.com/item/1005003245703342.html?spm=a2g0o.order_list.order_list_main.17.21ef1802qkslow) |
| 8x20mm bed springs | $2 | [link](https://www.aliexpress.com/item/1005002971412129.html?spm=a2g0o.productlist.main.1.6c086ad58K77Ue) |
| --- | --- | --- |
| 3x NEMA17 | $25 | [link - pancake](https://www.aliexpress.com/item/1005004708155105.html?spm=a2g0o.order_list.order_list_main.102.145f1802vFsakT) |
| other motor listing (cheaper if you wanna buy 5) | $38 | [link](https://www.aliexpress.com/item/1005001650755939.html?spm=a2g0o.cart.0.0.202b38da9QMU82&mp=1)
| literally any mainboard | $20-30 | [ramps](https://www.aliexpress.com/item/1005001631916842.html?spm=a2g0o.cart.0.0.3bee38daN6zSnp&mp=1), [pico](https://www.aliexpress.com/item/1005004046648820.html?spm=a2g0o.productlist.main.3.3697bf5bSHKD6H)|
| something with tmc drivers for sensorless homing (like the pico) | ^ | ^ |
| Orange Pi Zero 2 (or something to run klipper) | $30 | [link](https://www.aliexpress.com/item/1005001823662622.html?spm=a2g0o.productlist.main.1.3a4a1cacYamf5s) |
| Limit switches x3 (MS-1A 13.5) | $1.50 | [link](https://www.aliexpress.com/item/4001033375208.html?) |
| Power supply, depends on your mainboard | $20-30 | [link](https://www.aliexpress.com/item/1005004623323483.html?spm=a2g0o.cart.0.0.64b338dahPVvNM&mp=1) |
| Extruder (titan or bmg recommended) | $5-10 | [titan link](https://www.aliexpress.com/item/10000404181488.html?spm=a2g0o.productlist.main.29.219338f9jwvYx4) |

## Alternative config for 150mm Z
| Thing |  |  |
| --- | --- | --- |
| 2020 extrusion 150mm x5 |  |  |
| 2020 extrusion 200mm x4 |  |  |
| mgn9c rail 150mm x5 |  |  |
| T8 leadscrew (150mm) P:2mm L:8mm|  |  |

---

### Alt for whatever Z

Replace the 4 longer extrusions with X long ones

Replace 2 rails with X-50mm long ones

Replace lead screw with x-50mm one

#### example: 500mm tall Z
| thing | # |
| --- | --- |
| 150mm long 2020 | 8 |
| 550mm long 2020 | 4 |
| 150mm long mgn9c | 3 |
| 500mm long mgn9c | 2 |
| 500mm long T8 | 1 |

---

// BOM subject to change