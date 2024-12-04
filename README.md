# menu-interacting

**Functions**
```c
ShowMenuFloatingForPlayer(playerid, extraid, const header[], header_colour, const list_items[][]);
HideMenuFloatingForPlayer(playerid);
```
**Callbacks**
```c
OnPlayerMenuFloatingResponse(playerid, extraid, bool:response, listitem);
```
**Use**
```c
#define MENU_ID_WEAPONS (2)

static const list[][] =
{
    "Tec-9",
    "Micro Uzi",
    "Desert Eagle"
};
ShowMenuFloatingForPlayer(playerid, MENU_ID_WEAPONS, "Weapons", 0xDA2B2BFF, list);
```
![screenshot](https://github.com/dotdue/menu-floating/blob/main/screenshot.png?raw=true)
