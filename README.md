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

# Server Metrics 2026-03-11 21:52:51 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 483.5 (0h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1083
telemt_connections_bad_total 1
telemt_handshake_timeouts_total 6
telemt_upstream_connect_attempt_total 1063
telemt_upstream_connect_success_total 1062
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 1063
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 939
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 123
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1060
telemt_user_connections_current{user="hello"} 218
telemt_user_octets_from_client{user="hello"} 10348511 (9.87 MB)
telemt_user_octets_to_client{user="hello"} 690456063 (658.47 MB)
telemt_user_msgs_from_client{user="hello"} 24766
telemt_user_msgs_to_client{user="hello"} 106706
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 471.7 (0h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 435
telemt_upstream_connect_attempt_total 421
telemt_upstream_connect_success_total 421
telemt_upstream_connect_attempts_per_request{bucket="1"} 421
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 394
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 419
telemt_user_connections_current{user="hello"} 76
telemt_user_octets_from_client{user="hello"} 4432777 (4.23 MB)
telemt_user_octets_to_client{user="hello"} 100883660 (96.21 MB)
telemt_user_msgs_from_client{user="hello"} 10911
telemt_user_msgs_to_client{user="hello"} 31067
telemt_user_unique_ips_current{user="hello"} 22
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 445.3 (0h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1127
telemt_connections_bad_total 15
telemt_handshake_timeouts_total 1
telemt_upstream_connect_attempt_total 701
telemt_upstream_connect_success_total 701
telemt_upstream_connect_attempts_per_request{bucket="1"} 701
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 615
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 86
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 699
telemt_user_connections_current{user="hello"} 81
telemt_user_octets_from_client{user="hello"} 3767166 (3.59 MB)
telemt_user_octets_to_client{user="hello"} 158196002 (150.87 MB)
telemt_user_msgs_from_client{user="hello"} 10728
telemt_user_msgs_to_client{user="hello"} 40086
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 470.8 (0h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 564
telemt_connections_bad_total 1
telemt_handshake_timeouts_total 46
telemt_upstream_connect_attempt_total 505
telemt_upstream_connect_success_total 503
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 505
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 422
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 80
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 501
telemt_user_connections_current{user="hello"} 108
telemt_user_octets_from_client{user="hello"} 4087319 (3.90 MB)
telemt_user_octets_to_client{user="hello"} 266032709 (253.71 MB)
telemt_user_msgs_from_client{user="hello"} 9628
telemt_user_msgs_to_client{user="hello"} 88859
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 471.9 (0h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 681
telemt_connections_bad_total 86
telemt_handshake_timeouts_total 1
telemt_upstream_connect_attempt_total 580
telemt_upstream_connect_success_total 580
telemt_upstream_connect_attempts_per_request{bucket="1"} 580
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 536
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 43
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 578
telemt_user_connections_current{user="hello"} 107
telemt_user_octets_from_client{user="hello"} 8362496 (7.98 MB)
telemt_user_octets_to_client{user="hello"} 156480035 (149.23 MB)
telemt_user_msgs_from_client{user="hello"} 7362
telemt_user_msgs_to_client{user="hello"} 28386
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 471.3 (0h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 592
telemt_connections_bad_total 1
telemt_upstream_connect_attempt_total 527
telemt_upstream_connect_success_total 527
telemt_upstream_connect_attempts_per_request{bucket="1"} 527
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 378
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 149
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 525
telemt_user_connections_current{user="hello"} 37
telemt_user_octets_from_client{user="hello"} 2648237 (2.53 MB)
telemt_user_octets_to_client{user="hello"} 178555740 (170.28 MB)
telemt_user_msgs_from_client{user="hello"} 7422
telemt_user_msgs_to_client{user="hello"} 24556
telemt_user_unique_ips_current{user="hello"} 11
telemt_user_unique_ips_recent_window{user="hello"} 5
```