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

# Server Metrics 2026-03-11 15:28:03 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 90113.6 (25h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 305030
telemt_connections_bad_total 4822
telemt_handshake_timeouts_total 5168
telemt_upstream_connect_attempt_total 281462
telemt_upstream_connect_success_total 281382
telemt_upstream_connect_fail_total 80
telemt_upstream_connect_attempts_per_request{bucket="1"} 281462
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 257304
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24017
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 80
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 281372
telemt_user_connections_current{user="hello"} 305
telemt_user_octets_from_client{user="hello"} 5242531787 (4.88 GB)
telemt_user_octets_to_client{user="hello"} 138585005181 (129.07 GB)
telemt_user_msgs_from_client{user="hello"} 6095904
telemt_user_msgs_to_client{user="hello"} 11134943
telemt_user_unique_ips_current{user="hello"} 84
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 90112.6 (25h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 120667
telemt_connections_bad_total 969
telemt_handshake_timeouts_total 3409
telemt_upstream_connect_attempt_total 111129
telemt_upstream_connect_success_total 111108
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 111129
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 96599
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13987
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 522
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 111098
telemt_user_connections_current{user="hello"} 181
telemt_user_octets_from_client{user="hello"} 6036229356 (5.62 GB)
telemt_user_octets_to_client{user="hello"} 69667368985 (64.88 GB)
telemt_user_msgs_from_client{user="hello"} 4037142
telemt_user_msgs_to_client{user="hello"} 20231000
telemt_user_unique_ips_current{user="hello"} 49
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 90112.4 (25h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 165935
telemt_connections_bad_total 1434
telemt_handshake_timeouts_total 7203
telemt_upstream_connect_attempt_total 148087
telemt_upstream_connect_success_total 148073
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 148087
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 131480
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16489
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 103
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 148063
telemt_user_connections_current{user="hello"} 175
telemt_user_octets_from_client{user="hello"} 12734972671 (11.86 GB)
telemt_user_octets_to_client{user="hello"} 130969406127 (121.97 GB)
telemt_user_msgs_from_client{user="hello"} 6847091
telemt_user_msgs_to_client{user="hello"} 29361747
telemt_user_unique_ips_current{user="hello"} 52
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 90111.4 (25h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 184812
telemt_connections_bad_total 8151
telemt_handshake_timeouts_total 2194
telemt_upstream_connect_attempt_total 167051
telemt_upstream_connect_success_total 166642
telemt_upstream_connect_fail_total 409
telemt_upstream_connect_attempts_per_request{bucket="1"} 167051
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 145221
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20879
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 91
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 451
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 409
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 166632
telemt_user_connections_current{user="hello"} 132
telemt_user_octets_from_client{user="hello"} 9906382719 (9.23 GB)
telemt_user_octets_to_client{user="hello"} 115204912989 (107.29 GB)
telemt_user_msgs_from_client{user="hello"} 5902645
telemt_user_msgs_to_client{user="hello"} 34495572
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 90112.7 (25h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 262008
telemt_connections_bad_total 19815
telemt_handshake_timeouts_total 6336
telemt_upstream_connect_attempt_total 213722
telemt_upstream_connect_success_total 213218
telemt_upstream_connect_fail_total 504
telemt_upstream_connect_attempts_per_request{bucket="1"} 213722
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 184700
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28159
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 359
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 504
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 213210
telemt_user_connections_current{user="hello"} 302
telemt_user_octets_from_client{user="hello"} 5113683525 (4.76 GB)
telemt_user_octets_to_client{user="hello"} 173780607446 (161.85 GB)
telemt_user_msgs_from_client{user="hello"} 5036002
telemt_user_msgs_to_client{user="hello"} 24233756
telemt_user_unique_ips_current{user="hello"} 88
telemt_user_unique_ips_recent_window{user="hello"} 36
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 69082.0 (19h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 469
telemt_connections_bad_total 446
telemt_handshake_timeouts_total 12
telemt_upstream_connect_attempt_total 19
telemt_upstream_connect_success_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 19
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11
telemt_user_octets_from_client{user="hello"} 7489 (7.31 KB)
telemt_user_octets_to_client{user="hello"} 2462 (2.40 KB)
telemt_user_msgs_from_client{user="hello"} 23
telemt_user_msgs_to_client{user="hello"} 15
```