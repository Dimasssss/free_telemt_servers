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

# Server Metrics 2026-03-11 09:50:01 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 69832.3 (19h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 205197
telemt_connections_bad_total 3594
telemt_handshake_timeouts_total 4297
telemt_upstream_connect_attempt_total 187892
telemt_upstream_connect_success_total 187832
telemt_upstream_connect_fail_total 59
telemt_upstream_connect_attempts_per_request{bucket="1"} 187891
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 171647
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16128
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 59
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 187824
telemt_user_connections_current{user="hello"} 364
telemt_user_octets_from_client{user="hello"} 4080308301 (3.80 GB)
telemt_user_octets_to_client{user="hello"} 111419082898 (103.77 GB)
telemt_user_msgs_from_client{user="hello"} 4448840
telemt_user_msgs_to_client{user="hello"} 8304835
telemt_user_unique_ips_current{user="hello"} 88
telemt_user_unique_ips_recent_window{user="hello"} 38
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 69831.4 (19h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 79965
telemt_connections_bad_total 780
telemt_handshake_timeouts_total 3144
telemt_upstream_connect_attempt_total 72308
telemt_upstream_connect_success_total 72292
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 72308
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 62245
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9795
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 252
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 72284
telemt_user_connections_current{user="hello"} 153
telemt_user_octets_from_client{user="hello"} 4986519292 (4.64 GB)
telemt_user_octets_to_client{user="hello"} 55501895385 (51.69 GB)
telemt_user_msgs_from_client{user="hello"} 3166444
telemt_user_msgs_to_client{user="hello"} 14266733
telemt_user_unique_ips_current{user="hello"} 45
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 69831.7 (19h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 110617
telemt_connections_bad_total 1075
telemt_handshake_timeouts_total 5225
telemt_upstream_connect_attempt_total 98067
telemt_upstream_connect_success_total 98063
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 98067
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 86901
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11098
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 63
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 98055
telemt_user_connections_current{user="hello"} 162
telemt_user_octets_from_client{user="hello"} 12002123241 (11.18 GB)
telemt_user_octets_to_client{user="hello"} 81180127751 (75.60 GB)
telemt_user_msgs_from_client{user="hello"} 5666602
telemt_user_msgs_to_client{user="hello"} 15769758
telemt_user_unique_ips_current{user="hello"} 48
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 69830.1 (19h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 121881
telemt_connections_bad_total 251
telemt_handshake_timeouts_total 1121
telemt_upstream_connect_attempt_total 115727
telemt_upstream_connect_success_total 115466
telemt_upstream_connect_fail_total 261
telemt_upstream_connect_attempts_per_request{bucket="1"} 115727
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 99695
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15398
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 58
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 315
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 261
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 115458
telemt_user_connections_current{user="hello"} 171
telemt_user_octets_from_client{user="hello"} 5509156218 (5.13 GB)
telemt_user_octets_to_client{user="hello"} 82302644618 (76.65 GB)
telemt_user_msgs_from_client{user="hello"} 3618270
telemt_user_msgs_to_client{user="hello"} 21287984
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 69831.4 (19h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 192764
telemt_connections_bad_total 15226
telemt_handshake_timeouts_total 3349
telemt_upstream_connect_attempt_total 154007
telemt_upstream_connect_success_total 153605
telemt_upstream_connect_fail_total 402
telemt_upstream_connect_attempts_per_request{bucket="1"} 154007
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 131735
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21584
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 286
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 402
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 153597
telemt_user_connections_current{user="hello"} 199
telemt_user_octets_from_client{user="hello"} 3022222737 (2.81 GB)
telemt_user_octets_to_client{user="hello"} 136194744159 (126.84 GB)
telemt_user_msgs_from_client{user="hello"} 3429796
telemt_user_msgs_to_client{user="hello"} 17783080
telemt_user_unique_ips_current{user="hello"} 68
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 48800.8 (13h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 422
telemt_connections_bad_total 400
telemt_handshake_timeouts_total 9
telemt_upstream_connect_attempt_total 17
telemt_upstream_connect_success_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 17
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11
telemt_user_octets_from_client{user="hello"} 7489 (7.31 KB)
telemt_user_octets_to_client{user="hello"} 2462 (2.40 KB)
telemt_user_msgs_from_client{user="hello"} 23
telemt_user_msgs_to_client{user="hello"} 15
```