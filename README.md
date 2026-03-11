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

# Server Metrics 2026-03-11 10:20:44 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 71674.8 (19h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 212656
telemt_connections_bad_total 3615
telemt_handshake_timeouts_total 4399
telemt_upstream_connect_attempt_total 194972
telemt_upstream_connect_success_total 194911
telemt_upstream_connect_fail_total 61
telemt_upstream_connect_attempts_per_request{bucket="1"} 194972
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 178239
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16615
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 61
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 194903
telemt_user_connections_current{user="hello"} 354
telemt_user_octets_from_client{user="hello"} 4250342340 (3.96 GB)
telemt_user_octets_to_client{user="hello"} 114077123517 (106.24 GB)
telemt_user_msgs_from_client{user="hello"} 4625591
telemt_user_msgs_to_client{user="hello"} 8568697
telemt_user_unique_ips_current{user="hello"} 92
telemt_user_unique_ips_recent_window{user="hello"} 41
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 71674.1 (19h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 83243
telemt_connections_bad_total 782
telemt_handshake_timeouts_total 3165
telemt_upstream_connect_attempt_total 75394
telemt_upstream_connect_success_total 75378
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 75394
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 64990
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10132
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 256
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 75370
telemt_user_connections_current{user="hello"} 124
telemt_user_octets_from_client{user="hello"} 5017603872 (4.67 GB)
telemt_user_octets_to_client{user="hello"} 56175831569 (52.32 GB)
telemt_user_msgs_from_client{user="hello"} 3218804
telemt_user_msgs_to_client{user="hello"} 14577504
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 71674.0 (19h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 115142
telemt_connections_bad_total 1077
telemt_handshake_timeouts_total 5301
telemt_upstream_connect_attempt_total 102199
telemt_upstream_connect_success_total 102195
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 102199
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 90622
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11508
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 64
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 102187
telemt_user_connections_current{user="hello"} 215
telemt_user_octets_from_client{user="hello"} 12148637255 (11.31 GB)
telemt_user_octets_to_client{user="hello"} 83813963959 (78.06 GB)
telemt_user_msgs_from_client{user="hello"} 5792533
telemt_user_msgs_to_client{user="hello"} 16292107
telemt_user_unique_ips_current{user="hello"} 51
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 71672.8 (19h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 126702
telemt_connections_bad_total 316
telemt_handshake_timeouts_total 1226
telemt_upstream_connect_attempt_total 120070
telemt_upstream_connect_success_total 119795
telemt_upstream_connect_fail_total 275
telemt_upstream_connect_attempts_per_request{bucket="1"} 120070
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 103540
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15869
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 62
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 324
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 275
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 119787
telemt_user_connections_current{user="hello"} 221
telemt_user_octets_from_client{user="hello"} 5594454319 (5.21 GB)
telemt_user_octets_to_client{user="hello"} 83538946620 (77.80 GB)
telemt_user_msgs_from_client{user="hello"} 3691977
telemt_user_msgs_to_client{user="hello"} 21710590
telemt_user_unique_ips_current{user="hello"} 58
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 71674.1 (19h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 198437
telemt_connections_bad_total 15583
telemt_handshake_timeouts_total 3381
telemt_upstream_connect_attempt_total 159115
telemt_upstream_connect_success_total 158713
telemt_upstream_connect_fail_total 402
telemt_upstream_connect_attempts_per_request{bucket="1"} 159115
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 136266
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22151
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 296
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 402
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 158705
telemt_user_connections_current{user="hello"} 294
telemt_user_octets_from_client{user="hello"} 3525347343 (3.28 GB)
telemt_user_octets_to_client{user="hello"} 140157567983 (130.53 GB)
telemt_user_msgs_from_client{user="hello"} 3684135
telemt_user_msgs_to_client{user="hello"} 18566236
telemt_user_unique_ips_current{user="hello"} 76
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 50643.4 (14h 4m)
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