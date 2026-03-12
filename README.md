# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt  
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-40
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 26 марта
- Ссылка:
```bash
tg://proxy?server=s1.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## psb.hosting
- Локация: Finland
- Тариф: FI-200
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 12$
- Оплачен до: 25 марта
- Ссылка:
```bash
tg://proxy?server=s2.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## koara.io
- Локация: Германия, Франкфурт-на-Майне
- Тариф: DE-2
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 639 RUB
- Оплачен до: 25 марта
- Ссылка:
```bash
tg://proxy?server=s3.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## landvps.ru
- Локация: Финляндия
- Тариф: FL-2
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 200 Mbps/s
- Цена в месяц: 800 RUB
- Оплачен до: 26 марта
- Ссылка:
```bash
tg://proxy?server=s4.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## rdp-onedash.ru
- Локация: Нидерланды
- Тариф: Mini
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 1 Gbit/s
- Цена в месяц: 844 RUB
- Оплачен до: 14 апреля
- Ссылка:
```bash
tg://proxy?server=s5.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## hostvds.com
- Локация: Нидерланды, Амстердам
- Тариф: Burstable
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 10 Gbit/s
- Цена в месяц: €7.98
- Оплачен до: 13 апреля
- Ссылка:
```bash
tg://proxy?server=s6.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

# Server Metrics 2026-03-12 00:51:20 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 11175.5 (3h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 21300
telemt_connections_bad_total 1806
telemt_handshake_timeouts_total 136
telemt_upstream_connect_attempt_total 18677
telemt_upstream_connect_success_total 18671
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 18677
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16754
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1912
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 18669
telemt_user_connections_current{user="hello"} 167
telemt_user_octets_from_client{user="hello"} 208149904 (198.51 MB)
telemt_user_octets_to_client{user="hello"} 6940008765 (6.46 GB)
telemt_user_msgs_from_client{user="hello"} 360104
telemt_user_msgs_to_client{user="hello"} 934911
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 11163.8 (3h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8503
telemt_connections_bad_total 39
telemt_handshake_timeouts_total 22
telemt_upstream_connect_attempt_total 8157
telemt_upstream_connect_success_total 8157
telemt_upstream_connect_attempts_per_request{bucket="1"} 8157
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7070
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1083
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 8155
telemt_user_connections_current{user="hello"} 70
telemt_user_octets_from_client{user="hello"} 56464044 (53.85 MB)
telemt_user_octets_to_client{user="hello"} 2966399648 (2.76 GB)
telemt_user_msgs_from_client{user="hello"} 141579
telemt_user_msgs_to_client{user="hello"} 951862
telemt_user_unique_ips_current{user="hello"} 24
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 11137.4 (3h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14764
telemt_connections_bad_total 279
telemt_handshake_timeouts_total 838
telemt_upstream_connect_attempt_total 12117
telemt_upstream_connect_success_total 12117
telemt_upstream_connect_attempts_per_request{bucket="1"} 12117
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10332
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1781
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 12115
telemt_user_connections_current{user="hello"} 94
telemt_user_octets_from_client{user="hello"} 77181610 (73.61 MB)
telemt_user_octets_to_client{user="hello"} 7099458121 (6.61 GB)
telemt_user_msgs_from_client{user="hello"} 239246
telemt_user_msgs_to_client{user="hello"} 1599273
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 11162.7 (3h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13862
telemt_connections_bad_total 2251
telemt_handshake_timeouts_total 631
telemt_upstream_connect_attempt_total 10402
telemt_upstream_connect_success_total 10391
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 10402
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9107
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1250
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 10389
telemt_user_connections_current{user="hello"} 119
telemt_user_octets_from_client{user="hello"} 82190490 (78.38 MB)
telemt_user_octets_to_client{user="hello"} 4734149738 (4.41 GB)
telemt_user_msgs_from_client{user="hello"} 163877
telemt_user_msgs_to_client{user="hello"} 1756222
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## rdp-onedash.ru

Не удалось получить метрики для этого сервера.

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 11163.7 (3h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11336
telemt_connections_bad_total 84
telemt_handshake_timeouts_total 115
telemt_upstream_connect_attempt_total 10151
telemt_upstream_connect_success_total 10151
telemt_upstream_connect_attempts_per_request{bucket="1"} 10151
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8573
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1574
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 10149
telemt_user_connections_current{user="hello"} 73
telemt_user_octets_from_client{user="hello"} 155317026 (148.12 MB)
telemt_user_octets_to_client{user="hello"} 17037971410 (15.87 GB)
telemt_user_msgs_from_client{user="hello"} 278165
telemt_user_msgs_to_client{user="hello"} 1544658
telemt_user_unique_ips_current{user="hello"} 29
telemt_user_unique_ips_recent_window{user="hello"} 15
```