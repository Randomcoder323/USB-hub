# USB-hub

## What? 
This is a USB hub I made on easyeda assembled using PCBA. I have an intake of usb-c and three usb-a outakes with one usb c out take too. This project was so fun maiking and I learned lots of new stuff. I made this project to learn more about usb connections on pcbs and mainly pcba.

## Pics 

<img width="568" height="484" alt="Screenshot 2026-03-28 210405" src="https://github.com/user-attachments/assets/6b205004-4e07-496d-b3dc-27f927db7d5c" />
<img width="782" height="473" alt="Screenshot 2026-03-28 210346" src="https://github.com/user-attachments/assets/a94200e6-055b-4e37-bd37-ad79998f519c" />
<img width="1098" height="632" alt="Screenshot 2026-03-28 150457" src="https://github.com/user-attachments/assets/6cfc467f-0151-43c2-9b69-1d7ff3d5700a" />
<img width="569" height="427" alt="image" src="https://github.com/user-attachments/assets/827cd1bd-8716-4312-81b7-897470b876da" />
<img width="629" height="539" alt="1000019670" src="https://github.com/user-attachments/assets/619ba6bf-bb84-4cff-88e7-15fb97cc866b" />
<img width="1424" height="866" alt="1000019671" src="https://github.com/user-attachments/assets/dee8e279-b000-4bdf-9e7f-119e4fe26d46" />


## BOM
| Item | Description                               | Quantity | Price | Link                | Supplier |
|------|-------------------------------------------|----------|-------|---------------------|----------|
| PCBA | To put all the components since they are tiny | 2        | 22.44 | https://jlcpcb.com | JLC PCB  |
| PCB  | To put the components on                  | 5        | 4.00  | https://jlcpcb.com | JLC PCB  |

## PCBA BOM 

| No. | Quantity | Comment                  | Designator                  | Footprint                          | Value | Manufacturer Part | Manufacturer             | Supplier Part | Supplier |
|-----|----------|--------------------------|-----------------------------|------------------------------------|-------|-------------------|--------------------------|---------------|----------|
| 1   | 8        | 1uF                      | C1,C3,C4,C5,C6,C8,C10,C12   | C0603                              | 1uF   |                   |                          |               |          |
| 2   | 3        | 100nF                    | C7,C9,C11                   | C0603                              | 100nF |                   |                          |               |          |
| 3   | 4        | 5.1K                     | R1,R2,R3,R4                 | R0603                              | 5.1K  |                   |                          |               |          |
| 4   | 1        | SL2.1s                   | U1                          | SSOP-16_L4.6-W2.6-P0.53-LS4.0-BL   |       | SL2.1s            | CoreChips (和芯润德)     | C2684433      | LCSC     |
| 5   | 2        | TYPE-C 16PIN 2MD(073)   | USB1,USB5                   | USB-C-SMD_TYPE-C-6PIN-2MD-073      |       | TYPE-C 16PIN 2MD  | SHOU HAN (首韩)          | C2765186      | LCSC     |
| 6   | 3        | 10.0 QHHTZB6.3          | USB2,USB3,USB4              | USB-A-TH_10.0QHHTZB6.3             |       | 10.0 QHHTZB6.3    | SHOU HAN (首韩)          | C668591       | LCSC     |
