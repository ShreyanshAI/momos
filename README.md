# Kalu Ji Momos — 3D Website

Files: `index.html` (site) + `menu.json` (menu, prices, hours, phone, WhatsApp, outlets).

## Chalana (VS Code)
Folder kholo > Live Server install karo > `index.html` pe right-click > Open with Live Server.
(`menu.json` sirf Live Server ya deploy ke baad load hota hai, file:// se nahi.)

## Menu / price / timing badalna (code ko haath lagaye bina)
`menu.json` kholo aur edit karo:
- `items[].z` = [["8 pcs",30],["14 pcs",50]] (pieces aur price)
- `hours` = "11:00 AM - 10:00 PM" (khaali ho to "Call to confirm timings" dikhta hai)
- `wa` = WhatsApp number (91 ke saath, bina + ke)
Phir save karke git push / dobara deploy karo.

## Deploy
Netlify Drop (app.netlify.com/drop) pe poora folder drag-drop karo, ya:
```
git add . && git commit -m "update" && git push
```
(GitHub Pages: Settings > Pages > Branch main / root)
