\# Grid\_line\_All\_24x24\_Map (SpringRTS / BAR Widget)



\*\*Author:\*\* GOJO1314  

\*\*Date:\*\* 2025  

\*\*Game:\*\* Beyond All Reason / SpringRTS  

\*\*File:\*\* `Grid\_line\_All\_24x24\_Map.lua`



---



\## 🧩 Overview



This widget automatically \*\*draws a symmetrical grid\*\* for \*\*12-player setups\*\* (NuttyB Raptor layout style).  

It progressively draws each grid line using in-game \*\*markers\*\*, so you can visually see the grid being constructed.



Originally written for the map \*\*Full Metal Plate\*\*, this version has been updated to \*\*run on all maps\*\* without restrictions.



---



\## ⚙️ Features



\- ✅ Works on \*\*any map\*\*

\- 🕓 Draws lines \*\*progressively\*\* (configurable speed)

\- 📏 Supports \*\*12-player layout\*\*

\- 🧭 Draws \*\*cardinal\*\*, \*\*horizontal\*\*, and \*\*vertical\*\* grid lines

\- 💬 Prints progress messages to the in-game chat



---



\## 🚀 Installation



1\. Download or copy the file \[`auto\_draw\_grid.lua`](auto\_draw\_grid.lua)

2\. Place it in your Spring or BAR widget directory:

&nbsp;  - For \*\*BAR\*\* (Beyond All Reason):

&nbsp;    ```

&nbsp;    Documents\\Beyond All Reason\\LuaUI\\Widgets\\

&nbsp;    ```

&nbsp;  - For \*\*SpringRTS\*\*:

&nbsp;    ```

&nbsp;    Spring\\LuaUI\\Widgets\\

&nbsp;    ```

3\. Launch the game and start any map.

4\. The grid will automatically begin drawing line-by-line.



---



\## ⚡ Configuration



You can tweak a few settings near the top of the file:



| Variable | Default | Description |

|-----------|----------|-------------|

| `lineLength` | 2975 | Length of the cardinal direction lines |

| `startOffset` | 3650 | Offset from center for the main lines |

| `drawInterval` | 0.16 | Time (in seconds) between drawing each line |

| `square` | 192 | Base unit for grid spacing |



Example:  

If you want the grid to draw faster, change:

```lua

local drawInterval = 0.1



