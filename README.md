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

# Server Metrics 2026-03-10 22:52:33 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 30384.9 (8h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 96376
telemt_connections_bad_total 3305
telemt_handshake_timeouts_total 2209
telemt_upstream_connect_attempt_total 86592
telemt_upstream_connect_success_total 86560
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 86592
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 78870
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7637
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 86556
telemt_user_connections_current{user="hello"} 161
telemt_user_octets_from_client{user="hello"} 2573462446 (2.40 GB)
telemt_user_octets_to_client{user="hello"} 70548902808 (65.70 GB)
telemt_user_msgs_from_client{user="hello"} 2521605
telemt_user_msgs_to_client{user="hello"} 4764653
telemt_user_unique_ips_current{user="hello"} 45
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 30384.3 (8h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 37003
telemt_connections_bad_total 331
telemt_handshake_timeouts_total 814
telemt_upstream_connect_attempt_total 33628
telemt_upstream_connect_success_total 33619
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 33628
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28435
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4964
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 220
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 33615
telemt_user_connections_current{user="hello"} 61
telemt_user_octets_from_client{user="hello"} 1686854022 (1.57 GB)
telemt_user_octets_to_client{user="hello"} 35222469219 (32.80 GB)
telemt_user_msgs_from_client{user="hello"} 1380051
telemt_user_msgs_to_client{user="hello"} 8862549
telemt_user_unique_ips_current{user="hello"} 21
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 30383.9 (8h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 59548
telemt_connections_bad_total 446
telemt_handshake_timeouts_total 4061
telemt_upstream_connect_attempt_total 51586
telemt_upstream_connect_success_total 51584
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 51586
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 46481
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5055
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 47
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 51580
telemt_user_connections_current{user="hello"} 61
telemt_user_octets_from_client{user="hello"} 778683016 (742.61 MB)
telemt_user_octets_to_client{user="hello"} 49280798538 (45.90 GB)
telemt_user_msgs_from_client{user="hello"} 1097368
telemt_user_msgs_to_client{user="hello"} 7345935
telemt_user_unique_ips_current{user="hello"} 24
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 30382.8 (8h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 54925
telemt_connections_bad_total 87
telemt_handshake_timeouts_total 329
telemt_upstream_connect_attempt_total 52728
telemt_upstream_connect_success_total 52577
telemt_upstream_connect_fail_total 151
telemt_upstream_connect_attempts_per_request{bucket="1"} 52728
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 46168
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6239
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 17
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 153
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 151
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 52573
telemt_user_connections_current{user="hello"} 83
telemt_user_octets_from_client{user="hello"} 826756113 (788.46 MB)
telemt_user_octets_to_client{user="hello"} 37396729365 (34.83 GB)
telemt_user_msgs_from_client{user="hello"} 1126457
telemt_user_msgs_to_client{user="hello"} 7155830
telemt_user_unique_ips_current{user="hello"} 24
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 30384.0 (8h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 80665
telemt_connections_bad_total 7467
telemt_handshake_timeouts_total 1462
telemt_upstream_connect_attempt_total 68618
telemt_upstream_connect_success_total 68370
telemt_upstream_connect_fail_total 248
telemt_upstream_connect_attempts_per_request{bucket="1"} 68618
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 59140
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9018
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 212
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 248
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 68366
telemt_user_connections_current{user="hello"} 117
telemt_user_octets_from_client{user="hello"} 2064026584 (1.92 GB)
telemt_user_octets_to_client{user="hello"} 55103789981 (51.32 GB)
telemt_user_msgs_from_client{user="hello"} 1931280
telemt_user_msgs_to_client{user="hello"} 8077400
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 9353.5 (2h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 40
telemt_connections_bad_total 38
telemt_handshake_timeouts_total 1
telemt_upstream_connect_attempt_total 2
telemt_upstream_connect_success_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
```