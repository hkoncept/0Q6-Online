<p align="center"><img src="../../../includes/logo.svg" alt="drawing" width="100"/></p>
<h4 align="center">0SH - Structure de données</h4>

# 🏋🏻‍♂️ Exercices 04 - Les conteneurs 🏋🏻‍♂️

## printProductsByCategory()

### Affichage requis :
```plaintext
-----------------------------------------------------------------------------------
Components: Pièces internes(CPU, GPU, RAM, Cartes mères).
-----------------------------------------------------------------------------------
| #109332 | Corsair         | Vengeance 32GB DDR5    |  140.00$ | Components      |
| #123309 | Intel           | Core i5-13600K         |  319.00$ | Components      |
| #192230 | Cooler Master   | MasterLiquid ML240     |  110.00$ | Components      |
| #202291 | AMD             | Ryzen 9 7950X          |  549.00$ | Components      |
| #221134 | Sapphire        | Radeon RX 7900 XTX     |  950.00$ | Components      |
| #271103 | Be Quiet!       | Dark Rock Pro 4        |   89.00$ | Components      |
| #311029 | Noctua          | NH-D15 Cooler          |   99.90$ | Components      |
| #321104 | NZXT            | Kraken Z73             |  280.00$ | Components      |
| #382210 | Gigabyte        | RTX 4070 Ti            |  799.00$ | Components      |
| #443321 | Zotac           | RTX 3060               |  280.00$ | Components      |
| #451102 | ASUS            | ROG Maximus Z790       |  629.99$ | Components      |
| #540029 | Kingston        | FURY Renegade 32GB     |  125.00$ | Components      |
| #553310 | ASRock          | X670E Taichi           |  499.00$ | Components      |
| #592201 | EVGA            | SuperNOVA 850W         |  130.00$ | Components      |
| #654412 | G.Skill         | Trident Z5 64GB        |  250.00$ | Components      |
| #662219 | Crucial         | 16GB DDR4 3200         |   45.00$ | Components      |
| #673301 | Intel           | Core i9-13900K         |  589.99$ | Components      |
| #710023 | Fractal         | Meshify 2 Case         |  160.00$ | Components      |
| #772210 | MSI             | MAG B650 Tomahawk      |  220.00$ | Components      |
| #819923 | Seasonic        | Focus GX-750           |  115.00$ | Components      |
| #839912 | Lian Li         | O11 Dynamic            |  150.00$ | Components      |
| #883310 | NVIDIA          | RTX 4090               | 1599.99$ | Components      |
| #901128 | Thermaltake     | Toughpower 1000W       |  170.00$ | Components      |
| #904432 | AMD             | Ryzen 5 7600X          |  230.00$ | Components      |
| #991122 | Phanteks        | Evolv X                |  210.00$ | Components      |
-----------------------------------------------------------------------------------


-----------------------------------------------------------------------------------
Laptops: Ordinateurs portables, notebooks et ultrabooks.
-----------------------------------------------------------------------------------
| #112290 | VAIO            | FE15                   |  800.00$ | Laptops         |
| #120034 | Gigabyte        | Aero 16                | 1800.00$ | Laptops         |
| #159302 | HP              | Spectre x360           | 1350.50$ | Laptops         |
| #199384 | MSI             | Katana GF66            |  950.00$ | Laptops         |
| #215587 | Razer           | Blade 15               | 2200.00$ | Laptops         |
| #228103 | LG              | Gram 17                | 1300.00$ | Laptops         |
| #273349 | HP              | Pavilion Gaming        |  850.00$ | Laptops         |
| #332198 | ASUS            | ROG Zephyrus G14       | 1450.99$ | Laptops         |
| #340091 | Google          | Pixelbook Go           |  649.00$ | Laptops         |
| #394821 | Apple           | MacBook Pro 14         | 1999.99$ | Laptops         |
| #430021 | Alienware       | m16 R1                 | 2100.00$ | Laptops         |
| #447102 | MSI             | Prestige 14            | 1100.00$ | Laptops         |
| #492103 | Apple           | MacBook Air M2         | 1199.99$ | Laptops         |
| #500129 | ASUS            | Zenbook S 13           | 1200.00$ | Laptops         |
| #552093 | Samsung         | Galaxy Book3           | 1250.00$ | Laptops         |
| #567712 | Dynabook        | Portege X30            | 1150.00$ | Laptops         |
| #602331 | Microsoft       | Surface Laptop 5       |  999.99$ | Laptops         |
| #661022 | Lenovo          | Legion 5 Pro           | 1400.00$ | Laptops         |
| #712203 | Acer            | Predator Helios        | 1550.00$ | Laptops         |
| #774019 | Lenovo          | ThinkPad X1 Carbon     | 1600.00$ | Laptops         |
| #801123 | Panasonic       | Toughbook 55           | 2500.00$ | Laptops         |
| #821044 | Dell            | XPS 13                 | 1099.00$ | Laptops         |
| #881203 | Dell            | Inspiron 15            |  550.00$ | Laptops         |
| #908821 | Acer            | Swift 3                |  650.00$ | Laptops         |
| #992102 | Framework       | Laptop 13              | 1050.00$ | Laptops         |
-----------------------------------------------------------------------------------


-----------------------------------------------------------------------------------
Networking: Routeurs, commutateurs(switches) et câbles.
-----------------------------------------------------------------------------------
-----------------------------------------------------------------------------------


-----------------------------------------------------------------------------------
Peripherals: Claviers, souris, moniteurs et imprimantes.
-----------------------------------------------------------------------------------
| #104432 | Epson           | EcoTank ET-2800        |  250.00$ | Peripherals     |
| #119932 | Keychron        | K2 Mechanical          |   85.00$ | Peripherals     |
| #182230 | BenQ            | PD3200U 4K             |  700.00$ | Peripherals     |
| #219934 | ViewSonic       | VP2771                 |  450.00$ | Peripherals     |
| #227710 | Wacom           | Intuos Pro             |  380.00$ | Peripherals     |
| #283310 | Logitech        | MX Master 3S           |   99.99$ | Peripherals     |
| #301129 | Rode            | NT1 Gen 5              |  250.00$ | Peripherals     |
| #331109 | LG              | UltraGear 34           |  800.00$ | Peripherals     |
| #339912 | Glorious        | Model O                |   50.00$ | Peripherals     |
| #401129 | Audio-Technica  | AT2020                 |   99.00$ | Peripherals     |
| #473310 | JBL             | Quantum 800            |  200.00$ | Peripherals     |
| #493321 | SteelSeries     | Arctis Nova Pro        |  350.00$ | Peripherals     |
| #510023 | Samsung         | Odyssey G7             |  600.00$ | Peripherals     |
| #582210 | HyperX          | Cloud II               |   90.00$ | Peripherals     |
| #602231 | Dell            | UltraSharp 27          |  540.00$ | Peripherals     |
| #641102 | Canon           | Pixma TR150            |  200.00$ | Peripherals     |
| #664432 | Sennheiser      | HD 600                 |  300.00$ | Peripherals     |
| #741102 | Razer           | DeathAdder V3          |   69.99$ | Peripherals     |
| #752210 | Focusrite       | Scarlett 2i2           |  180.00$ | Peripherals     |
| #773310 | Elgato          | Stream Deck MK.2       |  150.00$ | Peripherals     |
| #852210 | Blue            | Yeti USB Mic           |  129.00$ | Peripherals     |
| #883321 | Bose            | Companion 2            |  149.00$ | Peripherals     |
| #902234 | Corsair         | K70 RGB Pro            |  160.00$ | Peripherals     |
| #912230 | Shure           | SM7B                   |  400.00$ | Peripherals     |
| #928810 | Microsoft       | Ergonomic Keyboard     |   60.00$ | Peripherals     |
-----------------------------------------------------------------------------------


-----------------------------------------------------------------------------------
Storage: Disques durs(HDD), SSD et clés USB.
-----------------------------------------------------------------------------------
| #102239 | Lexar           | NM790 4TB              |  230.00$ | Storage         |
| #110023 | WD              | Blue 2TB HDD           |   55.00$ | Storage         |
| #182209 | Toshiba         | X300 4TB               |  100.00$ | Storage         |
| #193302 | Samsung         | 870 EVO 500GB          |   60.00$ | Storage         |
| #201139 | SanDisk         | Ultra Flair 128GB      |   15.00$ | Storage         |
| #229910 | Samsung         | T7 Shield 2TB          |  150.00$ | Storage         |
| #273310 | Seagate         | IronWolf 8TB           |  190.00$ | Storage         |
| #302219 | Sabrent         | Rocket 4 Plus 2TB      |  200.00$ | Storage         |
| #331120 | Silicon Power   | A55 1TB                |   50.00$ | Storage         |
| #447710 | PNY             | CS900 500GB            |   30.00$ | Storage         |
| #482210 | Crucial         | X8 Portable 2TB        |  140.00$ | Storage         |
| #491103 | Corsair         | MP600 Pro 1TB          |  120.00$ | Storage         |
| #512210 | Teamgroup       | T-Force Vulcan 500GB   |   40.00$ | Storage         |
| #553321 | WD              | Black SN850X 2TB       |  160.00$ | Storage         |
| #592231 | Samsung         | 980 Pro 1TB            |  110.00$ | Storage         |
| #661102 | SanDisk         | Extreme Portable 1TB   |  100.00$ | Storage         |
| #663310 | WD              | My Passport 5TB        |  120.00$ | Storage         |
| #672230 | Seagate         | BarraCuda 2TB          |   50.00$ | Storage         |
| #710034 | SK Hynix        | Gold P31 1TB           |  105.00$ | Storage         |
| #784410 | ADATA           | XPG SX8200 1TB         |   65.00$ | Storage         |
| #804412 | LaCie           | Rugged Mini 2TB        |   90.00$ | Storage         |
| #849912 | Crucial         | MX500 1TB              |   80.00$ | Storage         |
| #881129 | Patriot         | P300 256GB             |   25.00$ | Storage         |
| #918832 | Kingston        | A400 480GB             |   35.00$ | Storage         |
| #938812 | G-Technology    | G-Drive 4TB            |  140.00$ | Storage         |
-----------------------------------------------------------------------------------
```

<hr><p align="Center"><img src="../../../includes/end.png" alt="drawing" width="150"/></p>