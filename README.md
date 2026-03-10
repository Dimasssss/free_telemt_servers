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

# Server Metrics 2026-03-10 20:44:58 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 22730.5 (6h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 84296
telemt_connections_bad_total 3263
telemt_handshake_timeouts_total 2129
telemt_upstream_connect_attempt_total 75052
telemt_upstream_connect_success_total 75022
telemt_upstream_connect_fail_total 30
telemt_upstream_connect_attempts_per_request{bucket="1"} 75052
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 68429
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6544
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 49
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 30
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 75018
telemt_user_connections_current{user="hello"} 234
telemt_user_octets_from_client{user="hello"} 2439462203 (2.27 GB)
telemt_user_octets_to_client{user="hello"} 58264962365 (54.26 GB)
telemt_user_msgs_from_client{user="hello"} 2233498
telemt_user_msgs_to_client{user="hello"} 4010184
telemt_user_unique_ips_current{user="hello"} 67
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 22729.7 (6h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 32298
telemt_connections_bad_total 302
telemt_handshake_timeouts_total 561
telemt_upstream_connect_attempt_total 29487
telemt_upstream_connect_success_total 29479
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 29487
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24892
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4370
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 217
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 29475
telemt_user_connections_current{user="hello"} 81
telemt_user_octets_from_client{user="hello"} 1479507808 (1.38 GB)
telemt_user_octets_to_client{user="hello"} 25033576382 (23.31 GB)
telemt_user_msgs_from_client{user="hello"} 1163208
telemt_user_msgs_to_client{user="hello"} 7298785
telemt_user_unique_ips_current{user="hello"} 26
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 22729.8 (6h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 51802
telemt_connections_bad_total 291
telemt_handshake_timeouts_total 3702
telemt_upstream_connect_attempt_total 44846
telemt_upstream_connect_success_total 44845
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 44846
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40563
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4236
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 45
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 44841
telemt_user_connections_current{user="hello"} 103
telemt_user_octets_from_client{user="hello"} 678542402 (647.11 MB)
telemt_user_octets_to_client{user="hello"} 41959243979 (39.08 GB)
telemt_user_msgs_from_client{user="hello"} 956350
telemt_user_msgs_to_client{user="hello"} 6291614
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 22728.6 (6h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 46137
telemt_connections_bad_total 69
telemt_handshake_timeouts_total 314
telemt_upstream_connect_attempt_total 44268
telemt_upstream_connect_success_total 44136
telemt_upstream_connect_fail_total 132
telemt_upstream_connect_attempts_per_request{bucket="1"} 44268
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 38878
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5115
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 132
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 132
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 44132
telemt_user_connections_current{user="hello"} 115
telemt_user_octets_from_client{user="hello"} 748560182 (713.88 MB)
telemt_user_octets_to_client{user="hello"} 33707489985 (31.39 GB)
telemt_user_msgs_from_client{user="hello"} 972518
telemt_user_msgs_to_client{user="hello"} 6446976
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 22729.7 (6h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 65487
telemt_connections_bad_total 5928
telemt_handshake_timeouts_total 1353
telemt_upstream_connect_attempt_total 55462
telemt_upstream_connect_success_total 55218
telemt_upstream_connect_fail_total 244
telemt_upstream_connect_attempts_per_request{bucket="1"} 55462
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 48234
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6796
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 188
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 244
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 55214
telemt_user_connections_current{user="hello"} 234
telemt_user_octets_from_client{user="hello"} 1744862019 (1.63 GB)
telemt_user_octets_to_client{user="hello"} 43644509843 (40.65 GB)
telemt_user_msgs_from_client{user="hello"} 1583689
telemt_user_msgs_to_client{user="hello"} 6002381
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 1699.0 (0h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16
telemt_connections_bad_total 16
telemt_upstream_connect_attempt_total 2
telemt_upstream_connect_success_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
```