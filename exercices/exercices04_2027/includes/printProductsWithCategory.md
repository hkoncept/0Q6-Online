<p align="center"><img src="../../../includes/logo.svg" alt="drawing" width="100"/></p>
<h4 align="center">0SH - Structure de données</h4>

# 🏋🏻‍♂️ Exercices 04 - Les conteneurs 🏋🏻‍♂️

## printProductsWithCategory()

### Affichage requis :
```plaintext
| #102239 | Lexar           | NM790 4TB              |  230.00$ |Storage        |
| #104432 | Epson           | EcoTank ET-2800        |  250.00$ |Peripherals    |
| #109332 | Corsair         | Vengeance 32GB DDR5    |  140.00$ |Components     |
| #110023 | WD              | Blue 2TB HDD           |   55.00$ |Storage        |
| #112290 | VAIO            | FE15                   |  800.00$ |Laptops        |
| #119932 | Keychron        | K2 Mechanical          |   85.00$ |Peripherals    |
| #120034 | Gigabyte        | Aero 16                | 1800.00$ |Laptops        |
| #123309 | Intel           | Core i5-13600K         |  319.00$ |Components     |
| #159302 | HP              | Spectre x360           | 1350.50$ |Laptops        |
| #182209 | Toshiba         | X300 4TB               |  100.00$ |Storage        |
| #182230 | BenQ            | PD3200U 4K             |  700.00$ |Peripherals    |
| #192230 | Cooler Master   | MasterLiquid ML240     |  110.00$ |Components     |
| #193302 | Samsung         | 870 EVO 500GB          |   60.00$ |Storage        |
| #199384 | MSI             | Katana GF66            |  950.00$ |Laptops        |
| #201139 | SanDisk         | Ultra Flair 128GB      |   15.00$ |Storage        |
| #202291 | AMD             | Ryzen 9 7950X          |  549.00$ |Components     |
| #215587 | Razer           | Blade 15               | 2200.00$ |Laptops        |
| #219934 | ViewSonic       | VP2771                 |  450.00$ |Peripherals    |
| #221134 | Sapphire        | Radeon RX 7900 XTX     |  950.00$ |Components     |
| #227710 | Wacom           | Intuos Pro             |  380.00$ |Peripherals    |
| #228103 | LG              | Gram 17                | 1300.00$ |Laptops        |
| #229910 | Samsung         | T7 Shield 2TB          |  150.00$ |Storage        |
| #271103 | Be Quiet!       | Dark Rock Pro 4        |   89.00$ |Components     |
| #273310 | Seagate         | IronWolf 8TB           |  190.00$ |Storage        |
| #273349 | HP              | Pavilion Gaming        |  850.00$ |Laptops        |
| #283310 | Logitech        | MX Master 3S           |   99.99$ |Peripherals    |
| #301129 | Rode            | NT1 Gen 5              |  250.00$ |Peripherals    |
| #302219 | Sabrent         | Rocket 4 Plus 2TB      |  200.00$ |Storage        |
| #311029 | Noctua          | NH-D15 Cooler          |   99.90$ |Components     |
| #321104 | NZXT            | Kraken Z73             |  280.00$ |Components     |
| #331109 | LG              | UltraGear 34           |  800.00$ |Peripherals    |
| #331120 | Silicon Power   | A55 1TB                |   50.00$ |Storage        |
| #332198 | ASUS            | ROG Zephyrus G14       | 1450.99$ |Laptops        |
| #339912 | Glorious        | Model O                |   50.00$ |Peripherals    |
| #340091 | Google          | Pixelbook Go           |  649.00$ |Laptops        |
| #382210 | Gigabyte        | RTX 4070 Ti            |  799.00$ |Components     |
| #394821 | Apple           | MacBook Pro 14         | 1999.99$ |Laptops        |
| #401129 | Audio-Technica  | AT2020                 |   99.00$ |Peripherals    |
| #430021 | Alienware       | m16 R1                 | 2100.00$ |Laptops        |
| #443321 | Zotac           | RTX 3060               |  280.00$ |Components     |
| #447102 | MSI             | Prestige 14            | 1100.00$ |Laptops        |
| #447710 | PNY             | CS900 500GB            |   30.00$ |Storage        |
| #451102 | ASUS            | ROG Maximus Z790       |  629.99$ |Components     |
| #473310 | JBL             | Quantum 800            |  200.00$ |Peripherals    |
| #482210 | Crucial         | X8 Portable 2TB        |  140.00$ |Storage        |
| #491103 | Corsair         | MP600 Pro 1TB          |  120.00$ |Storage        |
| #492103 | Apple           | MacBook Air M2         | 1199.99$ |Laptops        |
| #493321 | SteelSeries     | Arctis Nova Pro        |  350.00$ |Peripherals    |
| #500129 | ASUS            | Zenbook S 13           | 1200.00$ |Laptops        |
| #510023 | Samsung         | Odyssey G7             |  600.00$ |Peripherals    |
| #512210 | Teamgroup       | T-Force Vulcan 500GB   |   40.00$ |Storage        |
| #540029 | Kingston        | FURY Renegade 32GB     |  125.00$ |Components     |
| #552093 | Samsung         | Galaxy Book3           | 1250.00$ |Laptops        |
| #553310 | ASRock          | X670E Taichi           |  499.00$ |Components     |
| #553321 | WD              | Black SN850X 2TB       |  160.00$ |Storage        |
| #567712 | Dynabook        | Portege X30            | 1150.00$ |Laptops        |
| #582210 | HyperX          | Cloud II               |   90.00$ |Peripherals    |
| #592201 | EVGA            | SuperNOVA 850W         |  130.00$ |Components     |
| #592231 | Samsung         | 980 Pro 1TB            |  110.00$ |Storage        |
| #602231 | Dell            | UltraSharp 27          |  540.00$ |Peripherals    |
| #602331 | Microsoft       | Surface Laptop 5       |  999.99$ |Laptops        |
| #641102 | Canon           | Pixma TR150            |  200.00$ |Peripherals    |
| #654412 | G.Skill         | Trident Z5 64GB        |  250.00$ |Components     |
| #661022 | Lenovo          | Legion 5 Pro           | 1400.00$ |Laptops        |
| #661102 | SanDisk         | Extreme Portable 1TB   |  100.00$ |Storage        |
| #662219 | Crucial         | 16GB DDR4 3200         |   45.00$ |Components     |
| #663310 | WD              | My Passport 5TB        |  120.00$ |Storage        |
| #664432 | Sennheiser      | HD 600                 |  300.00$ |Peripherals    |
| #672230 | Seagate         | BarraCuda 2TB          |   50.00$ |Storage        |
| #673301 | Intel           | Core i9-13900K         |  589.99$ |Components     |
| #710023 | Fractal         | Meshify 2 Case         |  160.00$ |Components     |
| #710034 | SK Hynix        | Gold P31 1TB           |  105.00$ |Storage        |
| #712203 | Acer            | Predator Helios        | 1550.00$ |Laptops        |
| #741102 | Razer           | DeathAdder V3          |   69.99$ |Peripherals    |
| #752210 | Focusrite       | Scarlett 2i2           |  180.00$ |Peripherals    |
| #772210 | MSI             | MAG B650 Tomahawk      |  220.00$ |Components     |
| #773310 | Elgato          | Stream Deck MK.2       |  150.00$ |Peripherals    |
| #774019 | Lenovo          | ThinkPad X1 Carbon     | 1600.00$ |Laptops        |
| #784410 | ADATA           | XPG SX8200 1TB         |   65.00$ |Storage        |
| #801123 | Panasonic       | Toughbook 55           | 2500.00$ |Laptops        |
| #804412 | LaCie           | Rugged Mini 2TB        |   90.00$ |Storage        |
| #819923 | Seasonic        | Focus GX-750           |  115.00$ |Components     |
| #821044 | Dell            | XPS 13                 | 1099.00$ |Laptops        |
| #839912 | Lian Li         | O11 Dynamic            |  150.00$ |Components     |
| #849912 | Crucial         | MX500 1TB              |   80.00$ |Storage        |
| #852210 | Blue            | Yeti USB Mic           |  129.00$ |Peripherals    |
| #881129 | Patriot         | P300 256GB             |   25.00$ |Storage        |
| #881203 | Dell            | Inspiron 15            |  550.00$ |Laptops        |
| #883310 | NVIDIA          | RTX 4090               | 1599.99$ |Components     |
| #883321 | Bose            | Companion 2            |  149.00$ |Peripherals    |
| #901128 | Thermaltake     | Toughpower 1000W       |  170.00$ |Components     |
| #902234 | Corsair         | K70 RGB Pro            |  160.00$ |Peripherals    |
| #904432 | AMD             | Ryzen 5 7600X          |  230.00$ |Components     |
| #908821 | Acer            | Swift 3                |  650.00$ |Laptops        |
| #912230 | Shure           | SM7B                   |  400.00$ |Peripherals    |
| #918832 | Kingston        | A400 480GB             |   35.00$ |Storage        |
| #928810 | Microsoft       | Ergonomic Keyboard     |   60.00$ |Peripherals    |
| #938812 | G-Technology    | G-Drive 4TB            |  140.00$ |Storage        |
| #991122 | Phanteks        | Evolv X                |  210.00$ |Components     |
| #992102 | Framework       | Laptop 13              | 1050.00$ |Laptops        |
```

<hr><p align="Center"><img src="../../../includes/end.png" alt="drawing" width="150"/></p>