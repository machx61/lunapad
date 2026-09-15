# lunapad
i made this macropad because well my desk was too empty and i needed something(also out of boredom). it can be mainly used to control music and scroll through pages?(or whatever you may like)

# Features:
- 3x3 matrix: 9 keys to handle the best of your tasks
- Rotary encoder: do stuff with just a twist.
- 14 SK6812 Mini LEDs
- QMK firmware

# Renders

<img width="1920" height="692" alt="lunapad_render" src="https://github.com/user-attachments/assets/b00f1506-36d3-43dc-8bd4-ad5fd518d542" />

<img width="851" height="877" alt="Screenshot 2026-09-15 152213" src="https://github.com/user-attachments/assets/ba28c171-e8b9-490e-92ee-19bd1a932ca0" />

<img width="1396" height="833" alt="Screenshot 2026-09-15 151823" src="https://github.com/user-attachments/assets/7b792f89-990d-4a08-b295-611d6299f9f0" />

<img width="892" height="861" alt="Screenshot 2026-09-15 151733" src="https://github.com/user-attachments/assets/57d3818e-fd27-4fec-b40d-0be921451560" />

# Working:
- It utilises SEEED XIAORP2040 and a custom designed PCB with custom designed 3d printed enclosure and stuff.
- The macropad runs on QMK firmware and the programmed keys can be changed easily using the source files.

# Assembly:
- the case is split into two parts- top and bottom, held together by 4 M3 screws from the underside. there are also 4 M3x3mm heatset inserts on the topside standoffs. the pcb is sandwiched between the parts.

<img width="785" height="760" alt="Screenshot 2026-09-15 155345" src="https://github.com/user-attachments/assets/08b91e6b-d222-4b60-9406-02c270e9596b" />
the screwholes can be seen in the image.

# Bill of Materials

| Part | Quantity | Link |
|:-----|--------:|:------|
| Seeed XIAO RP2040 | 1 | [XIAO](https://robocraze.com/products/seeed-studio-xiao-rp2040-development-board?variant=47742255562976&country=IN&currency=INR&utm_medium=product_sync&utm_source=google&utm_content=sag_organic&utm_campaign=sag_organic&campaignid=23145906364&adgroupid=182236965810&keyword=&device=c&gad_source=1&gad_campaignid=23145906364&gbraid=0AAAAADgHQvYtYGwxuRugn9Vvs_5Luixta&gclid=CjwKCAjw2aPVBhBkEiwA0Cptt0xo3sHi-IdjsARB6GH6TKfZ1M9eswIn35SV6bqsJBOXxCKbRXXIgBoC-xAQAvD_BwE)
| MX-style Mechanical Switch | 9 | [switch](https://neomacro.in/products/cherry-mx-switches?srsltid=AfmBOor8tow3bfeM9PI4JXjRf0VAG1diVYeQj8hqUGDjs-gqPkzoR4SC)
| 1N4148 Diode | 9 | [diode](https://www.ktron.in/product/diode-1n4148-th/?srsltid=AfmBOooRQUjsKqpK_EiK3c9zfrjn3DoaM1cKq1ImvCJTQZmOqeq-VMQ6)
| EC11 Rotary Encoder | 1 | [encoder](https://robu.in/product/rotary-encoder-module/)
| SK6812MINI Addressable RGB LED | 9 | [led](https://www.desertcart.in/products/824340559-50-%E5%80%8B-sk6812-mini-e-rgb-2812b-%E3%81%A8%E5%90%8C%E6%A7%98-sk6812-3228?gad_source=1&gad_campaignid=23077216304&gbraid=0AAAAACnLYYvNHCZW8H4DWDfVWvF8gxS9Q&gclid=CjwKCAjw2aPVBhBkEiwA0Cptt4Ja3nVrBJ97lmX0pUguF7jc3NVgRkxuFrKZ9N5f6J9Q7V-lYQpT1RoC440QAvD_BwE)
| Custom PCB | 1 |
| M3 × 3 mm Brass Heat-Set Insert | 4 | [insert](https://onlyscrews.in/products/m3-x-3mm-brass-threaded-inserts?currency=INR&country=IN&variant=49729062273337&stkn=6e84ebfba1b8&utm_source=google&utm_medium=cpc&utm_campaign=googleads_23949204632&utm_id=23949204632&utm_adgroup=&utm_assetgroup=6722775387&utm_content=ad_&utm_term=&utm_matchtype=&utm_device=c&utm_network=x&gad_source=1&gad_campaignid=23953886635&gbraid=0AAAAA9sP2SRjj_2bfcZD9uxIjMuaLaIao&gclid=CjwKCAjw2aPVBhBkEiwA0Cptt7qy5Bg6gMEtFvCYIa8UhckvOcrG2VIVSBWy-0QVkHM6xJ50sQYSwRoCiMsQAvD_BwE)
| M3 × 12 mm Screw | 4 | [screw](https://onlyscrews.in/products/m3-x-12mm-hex-allen-socket-head-high-tensile12-9-black-anodized-screw?currency=INR&country=IN&variant=49862396903737&stkn=6e84ebfba1b8&utm_source=google&utm_medium=cpc&utm_campaign=googleads_22229903987&utm_id=22229903987&utm_adgroup=&utm_assetgroup=6553248255&utm_content=ad_&utm_term=&utm_matchtype=&utm_device=c&utm_network=x&gad_source=1&gad_campaignid=22229905346&gbraid=0AAAAA9sP2SRGRPWr5iqQc1qZ9YGRh8i3g&gclid=CjwKCAjw2aPVBhBkEiwA0CpttxG6n4pTu_Hwbiq8nsTTyXZsGK1pGMrzw8ansKFSEFKX_LcLPL4uwRoC4dcQAvD_BwE)
| MX Keycap | 9 | [keycap](https://keebmaker.com/products/1u-ymdk-mx-keycaps?variant=49717255012651)
| 3D-Printed Encoder Knob | 1 |
| 3D-Printed Case Top | 1 |
| 3D-Printed Case Bottom | 1 |

# Missing Stuff
- VIA support(i intend to roll it out sometime after)
- an OLED screen(if youd want)
- nothing else for a 3x3 macropad
