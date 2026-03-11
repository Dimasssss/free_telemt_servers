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

# Server Metrics 2026-03-11 23:14:39 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 5391.5 (1h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8906
telemt_connections_bad_total 81
telemt_handshake_timeouts_total 65
telemt_upstream_connect_attempt_total 8536
telemt_upstream_connect_success_total 8532
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 8536
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7535
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 994
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 8530
telemt_user_connections_current{user="hello"} 239
telemt_user_octets_from_client{user="hello"} 122363110 (116.69 MB)
telemt_user_octets_to_client{user="hello"} 3799949723 (3.54 GB)
telemt_user_msgs_from_client{user="hello"} 196810
telemt_user_msgs_to_client{user="hello"} 540903
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 5379.6 (1h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3996
telemt_connections_bad_total 3
telemt_handshake_timeouts_total 18
telemt_upstream_connect_attempt_total 3842
telemt_upstream_connect_success_total 3842
telemt_upstream_connect_attempts_per_request{bucket="1"} 3842
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3343
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 499
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3840
telemt_user_connections_current{user="hello"} 57
telemt_user_octets_from_client{user="hello"} 17231061 (16.43 MB)
telemt_user_octets_to_client{user="hello"} 469656898 (447.90 MB)
telemt_user_msgs_from_client{user="hello"} 42917
telemt_user_msgs_to_client{user="hello"} 206858
telemt_user_unique_ips_current{user="hello"} 18
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 5353.2 (1h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6617
telemt_connections_bad_total 251
telemt_handshake_timeouts_total 146
telemt_upstream_connect_attempt_total 5480
telemt_upstream_connect_success_total 5480
telemt_upstream_connect_attempts_per_request{bucket="1"} 5480
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4784
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 696
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 5478
telemt_user_connections_current{user="hello"} 42
telemt_user_octets_from_client{user="hello"} 33962438 (32.39 MB)
telemt_user_octets_to_client{user="hello"} 2832031067 (2.64 GB)
telemt_user_msgs_from_client{user="hello"} 106368
telemt_user_msgs_to_client{user="hello"} 735454
telemt_user_unique_ips_current{user="hello"} 22
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 5378.6 (1h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5171
telemt_connections_bad_total 13
telemt_handshake_timeouts_total 55
telemt_upstream_connect_attempt_total 4958
telemt_upstream_connect_success_total 4952
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 4958
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4276
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 656
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4950
telemt_user_connections_current{user="hello"} 77
telemt_user_octets_from_client{user="hello"} 40465455 (38.59 MB)
telemt_user_octets_to_client{user="hello"} 1916904529 (1.79 GB)
telemt_user_msgs_from_client{user="hello"} 78365
telemt_user_msgs_to_client{user="hello"} 706462
telemt_user_unique_ips_current{user="hello"} 28
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 5379.8 (1h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5314
telemt_connections_bad_total 1057
telemt_handshake_timeouts_total 17
telemt_upstream_connect_attempt_total 4155
telemt_upstream_connect_success_total 4152
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 4155
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3782
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 356
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4150
telemt_user_connections_current{user="hello"} 61
telemt_user_octets_from_client{user="hello"} 45856566 (43.73 MB)
telemt_user_octets_to_client{user="hello"} 1557164579 (1.45 GB)
telemt_user_msgs_from_client{user="hello"} 60537
telemt_user_msgs_to_client{user="hello"} 288075
telemt_user_unique_ips_current{user="hello"} 28
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 5379.4 (1h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5293
telemt_connections_bad_total 11
telemt_handshake_timeouts_total 91
telemt_upstream_connect_attempt_total 4520
telemt_upstream_connect_success_total 4520
telemt_upstream_connect_attempts_per_request{bucket="1"} 4520
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3785
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 735
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4518
telemt_user_connections_current{user="hello"} 29
telemt_user_octets_from_client{user="hello"} 82516423 (78.69 MB)
telemt_user_octets_to_client{user="hello"} 11208064462 (10.44 GB)
telemt_user_msgs_from_client{user="hello"} 151254
telemt_user_msgs_to_client{user="hello"} 821801
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 6
```