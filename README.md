# HandyGCCS++
port python to c++
It's faster and simpler, more stable.
It's a single file, so it's easier to manage.
Additionally, closing the back cover(lid-switch) is also supported.

below is same as HandyGCCS..

# HandyGCCS
Handheld Game Console Controller Support (Handy Geeks) for Linux

Designed to bring the full controller functionality to handheld game consoles including:
- Programmable extra buttons
- Rumble effects

## Background
Many of the handheld game consoles designed for windows have buttons on then in addition to the normal "X-Box" style controls. These controls are typically keyboard macros for built in windows functions (such as CTRL+ALT+DEL). This software captures all input from these devices, as well as the built in controller, hides them from the system, and creates a new virtual controller that acts as a single input device. This ensures that input isn't duplicated, and all buttons appear to come from the same controller.

## Supported Devices

### Anbernic
- Win600

### AOKZOE
- AOKZOE A1/Pro
 
### ASUS
- ROG Ally

### Aya Neo
- Founders Edition and 2021 Series
- Next Series
- Air/Pro/Plus
- 2/2S
- GEEK/1S

### Ayn
- Loki Max
- Loki Zero
- Loki MiniPro

### GPD
- GPD Win3
- GPD WinMax2
- GPD Win4

### Lenovo
- Legion Go

### OneNetBook
- OneXPlayer 1S
- OneXPlayer Mini/Pro
- OneXPlayer 2/Pro
- OneXFly

## Installation

git clone https://github.com/teslakang/HandyGCCS.git<br>
cd HandyGCCS<br>
sudo ./install.sh<br>
sudo systemctl enable --now handycon<br>

## Removal
sudo ./remove.sh

## Log view
./log.sh

## Config file
/etc/handygccs/handygccs.conf
