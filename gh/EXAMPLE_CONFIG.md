# Example Configuration — Custom SVG Paths

This file documents an example `energy_values` configuration with custom SVG paths for a specific isometric layout.

> **Note:** All entries use `sensor.energy_consumption_new` as a placeholder entity. Replace each `entity` value with the actual sensor for your setup.

---

## energy_values

```yaml
energy_values:
  - entity: sensor.energy_consumption_new
    position: middle-right
    label: bk roof to house
    color_positive: "#ff00ff"
    path_positive: >-
      M1466.01 1387C1466.01 1387 1466.01 1157.5 1466.01 1147.5C1466.01 1137.5
      1466.33 1126.75 1473.77 1114C1480.77 1102.01 1493.01 1093.5 1500.01
      1086.5C1507.01 1079.5 1742.39 848.022 1862.46 731.824
    color_negative: ""
    path_negative: ""
    delay_positive: 1s
    delay_negative: ""
    hide_value: true

  - entity: sensor.energy_consumption_new
    position: top-left
    label: solar to house
    color_positive: "#ff0000"
    path_positive: >-
      M1465.81 1386.42C1465.81 1386.42 1465.81 1147.93 1465.81 1137.12C1465.81
      1126.31 1468.7 1119.51 1470.44 1115.81C1472.19 1112.1 1478.17 1105.3
      1484.04 1099.43C1489.91 1093.56 2013.21 585.088 2013.21 585.088
    color_negative: ""
    path_negative: ""
    delay_positive: ""
    delay_negative: ""
    hide_value: false

  - entity: sensor.energy_consumption_new
    position: top-center
    label: grid (both ways)
    color_positive: "#00ff00"
    path_positive: >-
      M1457.5 1502.5C1457.5 1502.5 1457.5 1553.5 1457.5 1557C1457.5 1560.5
      1457.2 1563.9 1455 1567.5C1452.54 1571.53 1449 1573 1445.5 1575C1442 1577
      1376.5 1614.19 1372.5 1616.5C1368.5 1618.81 1367.09 1622.97 1366.5
      1628C1365.89 1633.22 1367.5 1638.78 1372.5 1641.67C1377.5 1644.56 1665
      1790 1665 1790L1382 1935
    color_negative: "#0000ff"
    path_negative: >-
      M1382 1935L1665 1790C1665 1790 1377.5 1644.56 1372.5 1641.67C1367.5
      1638.78 1365.89 1633.22 1366.5 1628C1367.09 1622.97 1368.5 1618.81 1372.5
      1616.5C1376.5 1614.19 1442 1577 1445.5 1575C1449 1573 1452.54 1571.53 1455
      1567.5C1457.2 1563.9 1457.5 1560.5 1457.5 1557C1457.5 1553.5 1457.5 1502.5
      1457.5 1502.5
    delay_positive: ""
    delay_negative: ""
    hide_value: false

  - entity: sensor.energy_consumption_new
    position: top-right
    label: battery (both ways)
    color_positive: "#0000ff"
    path_positive: >-
      M1478 1512.5C1478 1512.5 1478 1562.66 1478 1571C1478 1579.34 1482.83
      1585.21 1485.61 1587.99C1488.39 1590.77 1632.01 1662.28 1640.96
      1666.6C1649.92 1670.93 1657.95 1674.22 1665.37 1674.64C1670.31 1674.92
      1679.27 1674.33 1685.76 1670.93C1692.24 1667.53 1711.71 1657.03 1711.71
      1657.03
    color_negative: "#00ff00"
    path_negative: >-
      M1711.71 1657.03C1711.71 1657.03 1692.24 1667.53 1685.76 1670.93C1679.27
      1674.33 1670.31 1674.92 1665.37 1674.64C1657.95 1674.22 1649.92 1670.93
      1640.96 1666.6C1632.01 1662.28 1488.39 1590.77 1485.61 1587.99C1482.83
      1585.21 1478 1579.34 1478 1571C1478 1562.66 1478 1512.5 1478 1512.5
    delay_positive: ""
    delay_negative: ""
    hide_value: false

  - entity: sensor.energy_consumption_new
    position: middle-left
    label: car charger (both ways)
    color_positive: "#ff0000"
    path_positive: >-
      M1155.2 1360C1155.2 1360 1155.2 1402.48 1155.2 1406.81C1155.2 1411.13
      1157.43 1416.94 1161.41 1421.94C1165.25 1426.77 1170.8 1429.25 1174.19
      1431.21C1177.59 1433.17 1410.01 1551.29 1413.41 1553.25C1416.8 1555.21
      1421.72 1558.13 1427.31 1557.27C1431.79 1556.57 1437 1552.94 1437
      1548C1437 1543.06 1437 1493.32 1437 1493.32
    color_negative: "#00ff00"
    path_negative: >-
      M1437 1493.32C1437 1493.32 1437 1543.06 1437 1548C1437 1552.94 1431.79
      1556.57 1427.31 1557.27C1421.72 1558.13 1416.8 1555.21 1413.41
      1553.25C1410.01 1551.29 1177.59 1433.17 1174.19 1431.21C1170.8 1429.25
      1165.25 1426.77 1161.41 1421.94C1157.43 1416.94 1155.2 1411.13 1155.2
      1406.81C1155.2 1402.48 1155.2 1360 1155.2 1360
    delay_positive: ""
    delay_negative: ""
    hide_value: false

  - entity: sensor.energy_consumption_new
    position: bottom-left
    label: bk roof to battery
    color_positive: "#ff00ff"
    path_positive: >-
      M1779.44 1423.5C1779.44 1423.5 1779.44 1126.54 1779.44 1110.17C1779.44
      1093.79 1777.99 1092.74 1772.02 1083.91C1766.05 1075.07 1761.83 1073.1
      1750.4 1067.23C1738.97 1061.36 1660.5 1023.05 1642.59 1014.4C1624.67
      1005.75 1626.85 1008.63 1620.96 1000.5C1616.86 994.84 1614.75 990.803
      1614.48 983.819C1614.17 976.042 1614.48 971.462 1620.96 964.975C1624.87
      961.072 1738.1 852.177 1862.46 731.824
    color_negative: ""
    path_negative: ""
    delay_positive: ""
    delay_negative: ""
    hide_value: false

  - entity: sensor.energy_consumption_new
    position: bottom-center
    label: bk garage to house
    color_positive: "#ff9966"
    path_positive: >-
      M1464.69 1385.44C1464.69 1385.44 1464.69 1156.34 1464.69 1139.35C1464.69
      1134.89 1463.99 1125.08 1458.51 1116C1451.77 1104.86 1440.31 1099.5
      1432.01 1095.5L1204.47 980.5C1199.51 977.5 1186.14 972.16 1172.03
      972.16C1161.41 972.16 1152.88 974.631 1141.14 980.5C1129.4 986.369 675.912
      1214.66 675.912 1214.66
    color_negative: ""
    path_negative: ""
    delay_positive: ""
    delay_negative: ""
    hide_value: true

  - entity: sensor.energy_consumption_new
    position: bottom-right
    label: bk garage to battery
    color_positive: "#ff9966"
    path_positive: >-
      M1757.19 1434.94C1757.19 1434.94 1757.19 1236.34 1757.19 1219.35C1757.19
      1214.89 1758.43 1197.19 1753.17 1192.49C1746.58 1186.59 1742.67 1183.22
      1730 1186C1723.74 1187.37 1704.72 1198.78 1690.39 1205.39C1675.73 1212.16
      1666.95 1211.27 1663.52 1210.33C1656.72 1208.48 1636.33 1198.6 1630.15
      1195.51C1623.98 1192.42 1215.17 986.678 1204.47 980.5C1193.77 974.321
      1186.14 972.16 1172.03 972.16C1161.41 972.16 1152.88 974.631 1141.14
      980.5C1129.4 986.369 675.912 1214.66 675.912 1214.66
    color_negative: ""
    path_negative: ""
    delay_positive: ""
    delay_negative: ""
    hide_value: true
```

---

## Path overview

| Position | Label | Positive color | Negative color | hide_value |
|---|---|---|---|---|
| `middle-right` | bk roof to house | `#ff00ff` | — | yes |
| `top-left` | solar to house | `#ff0000` | — | no |
| `top-center` | grid (both ways) | `#00ff00` | `#0000ff` | no |
| `top-right` | battery (both ways) | `#0000ff` | `#00ff00` | no |
| `middle-left` | car charger (both ways) | `#ff0000` | `#00ff00` | no |
| `bottom-left` | bk roof to battery | `#ff00ff` | — | no |
| `bottom-center` | bk garage to house | `#ff9966` | — | yes |
| `bottom-right` | bk garage to battery | `#ff9966` | — | yes |
