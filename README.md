# Volt
A portable guitar amp that works with your bluetooth device, so you can play anywhere, anytime.

![Volt](img/render_1.png)
![Volt](img/pcbv2.2_2.png)

## BOM
|Designator    |Footprint         |Quantity|Value       |LCSC Part #| Link |
|--------------|------------------|--------|------------|-----------|------|
|C1, C13       |0402              |2       |1u          |C14445     |[LCSC](https://lcsc.com/product-detail/Multilayer-Ceramic-Capacitors-MLCC-SMD-SMT_Samsung-Electro-Mechanics-CL05A105KP5NNNC_C14445.html?s_z=n_C14445)|
|C10, C3, C5   |0402              |3       |100n        |C1525      |[LCSC](https://lcsc.com/product-detail/Multilayer-Ceramic-Capacitors-MLCC-SMD-SMT_Samsung-Electro-Mechanics-CL05B104KO5NNNC_C1525.html?s_z=n_C1525)|
|C2, C8        |0402              |2       |4u7         |C23733     |[LCSC](https://lcsc.com/product-detail/Multilayer-Ceramic-Capacitors-MLCC-SMD-SMT_Samsung-Electro-Mechanics-CL05A475MP5NRNC_C23733.html?s_z=n_C23733)|
|C4, C6        |0805              |2       |47u         |C1954938   |[LCSC](https://lcsc.com/product-detail/Tantalum-Capacitors_Kyocera-AVX-TLJR476M010R3200_C1954938.html?s_z=n_C1954938)|
|C7            |1206              |1       |100u        |C883598    |[LCSC](https://lcsc.com/product-detail/Multilayer-Ceramic-Capacitors-MLCC-SMD-SMT_Murata-Electronics-GRM31CR61A107MEA8L_C883598.html?s_z=n_C883598)|
|C9            |0402              |1       |0.22u       |C16772     |[LCSC](https://lcsc.com/product-detail/Multilayer-Ceramic-Capacitors-MLCC-SMD-SMT_Samsung-Electro-Mechanics-CL05B224KO5NNNC_C16772.html?s_z=n_C16772)|
|R1            |0402              |1       |1k          |C26083     |[LCSC](https://lcsc.com/product-detail/Chip-Resistor-Surface-Mount_UNI-ROYAL-Uniroyal-Elec-0402WGF1004TCE_C26083.html?s_z=n_C26083)|
|R10, R3       |0402              |2       |4k7         |C25900     |[LCSC](https://lcsc.com/product-detail/Chip-Resistor-Surface-Mount_UNI-ROYAL-Uniroyal-Elec-0402WGF4701TCE_C25900.html?s_z=n_C25900)|
|R11, R4, R6   |0402              |3       |10k         |C25744     |[LCSC](https://lcsc.com/product-detail/Chip-Resistor-Surface-Mount_UNI-ROYAL-Uniroyal-Elec-0402WGF1002TCE_C25744.html?s_z=n_C25744)|
|R2, R7, R8, R9|0402              |4       |100k        |C25741     |[LCSC](https://lcsc.com/product-detail/Chip-Resistor-Surface-Mount_UNI-ROYAL-Uniroyal-Elec-0402WGF1003TCE_C25741.html?s_z=n_C25741)|
|R5            |0402              |1       |220k        |C25767     |[LCSC](https://lcsc.com/product-detail/Chip-Resistor-Surface-Mount_UNI-ROYAL-Uniroyal-Elec-0402WGF2203TCE_C25767.html?s_z=n_C25767)|
|SW1           |SW_SPDT_PCM12     |1       |SW_SPDT     |C221841    |[LCSC](https://lcsc.com/product-detail/Slide-Switches_C-K-PCM12SMTR_C221841.html?s_z=n_C221841)|
|U3            |VREG_LM7805MP_NOPB|1       |LM7805_TO220|C2848241   |[LCSC](https://lcsc.com/product-detail/Voltage-Regulators-Linear-Low-Drop-Out-LDO-Regulators_Texas-Instruments-LM7805MPX-NOPB_C2848241.html?s_z=n_C2848241)|

Price: $6.47
### Parts to source yourself
|Designator    |Footprint         |Quantity|Value       | Link |
|--------------|------------------|--------|------------|------|
|U1|DIP-8|1|TL072|[AliExpress](https://www.aliexpress.com/item/1005006135219871.html?spm=a2g0o.order_list.order_list_main.17.5d4e1802HO5hMP)|
|U2||1|BT 5.3 Audio Transmitter|[AliExpress](https://www.aliexpress.com/item/1005006761214266.html?spm=a2g0o.order_list.order_list_main.35.5d4e1802HO5hMP)|
|J1||1|1/4" Audio Jack|[AliExpress](https://www.aliexpress.com/item/1005006199010497.html?pdp_ext_f=%7B%22sku_id%22%3A%2212000036235541089%22%7D&sourceType=1&spm=a2g0o.wish-manage-home.0.0)|
|J2||1|9V Battery Connector|[AliExpress](https://www.aliexpress.com/item/1005003688602261.html?spm=a2g0o.order_list.order_list_main.23.531a1802qO4r9D)|
|RV1||1|100k Potentiometer (logarithmic)|[Core Electronics](https://core-electronics.com.au/rotary-potentiometer-100k-ohm-logarithmic-panel-mount.html)|
|RV2||1|100k Potentiometer (linear)|[Core Electronics](https://core-electronics.com.au/rotary-potentiometer-100k-ohm-linear-panel-mount.html)|
|||4|M2 Screws|[AliExpress](https://www.aliexpress.com/item/4000970993800.html?spm=a2g0o.productlist.main.1.58de4aHV4aHVjt&algo_pvid=0fc23f4e-c433-440c-a35c-41e9ab94c65d&algo_exp_id=0fc23f4e-c433-440c-a35c-41e9ab94c65d-0&pdp_ext_f=%7B%22order%22%3A%222927%22%2C%22eval%22%3A%221%22%7D&pdp_npi=4%40dis%21AUD%211.84%211.68%21%21%211.19%211.09%21%402103244617511662003371305ef768%2110000013100721958%21sea%21AU%212685707787%21X&curPageLogUid=a6nSASSgxzOP&utparam-url=scene%3Asearch%7Cquery_from%3A)|

Price: $16.57

Also:
- 9V Battery
- Case (files in `case/`)
- Some wires & solder

Total PCB & PCBA Price: $32.51

Total Price: $49.08

**Total Price + est. shipping**: $60.00

(prices converted from AUD to USD, accurate as of 2025-06-29)
