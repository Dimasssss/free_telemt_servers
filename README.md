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

# Server Metrics 2026-03-11 05:19:37 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 53608.1 (14h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 137162
telemt_connections_bad_total 3400
telemt_handshake_timeouts_total 3010
telemt_upstream_connect_attempt_total 124558
telemt_upstream_connect_success_total 124514
telemt_upstream_connect_fail_total 44
telemt_upstream_connect_attempts_per_request{bucket="1"} 124558
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 113573
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10886
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 55
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 44
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 124508
telemt_user_connections_current{user="hello"} 280
telemt_user_octets_from_client{user="hello"} 3103206625 (2.89 GB)
telemt_user_octets_to_client{user="hello"} 87956258995 (81.92 GB)
telemt_user_msgs_from_client{user="hello"} 3246836
telemt_user_msgs_to_client{user="hello"} 6170253
telemt_user_unique_ips_current{user="hello"} 77
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 53607.4 (14h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 55968
telemt_connections_bad_total 435
telemt_handshake_timeouts_total 2972
telemt_upstream_connect_attempt_total 49681
telemt_upstream_connect_success_total 49669
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 49681
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 42003
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7438
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 228
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 49663
telemt_user_connections_current{user="hello"} 73
telemt_user_octets_from_client{user="hello"} 4502477438 (4.19 GB)
telemt_user_octets_to_client{user="hello"} 47118335112 (43.88 GB)
telemt_user_msgs_from_client{user="hello"} 2685788
telemt_user_msgs_to_client{user="hello"} 11077374
telemt_user_unique_ips_current{user="hello"} 20
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 53607.0 (14h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 76694
telemt_connections_bad_total 718
telemt_handshake_timeouts_total 4323
telemt_upstream_connect_attempt_total 67289
telemt_upstream_connect_success_total 67286
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 67289
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 59656
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7578
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 51
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 67280
telemt_user_connections_current{user="hello"} 76
telemt_user_octets_from_client{user="hello"} 11784083524 (10.97 GB)
telemt_user_octets_to_client{user="hello"} 71276166676 (66.38 GB)
telemt_user_msgs_from_client{user="hello"} 5196470
telemt_user_msgs_to_client{user="hello"} 13419878
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 53606.0 (14h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 80102
telemt_connections_bad_total 159
telemt_handshake_timeouts_total 587
telemt_upstream_connect_attempt_total 76690
telemt_upstream_connect_success_total 76521
telemt_upstream_connect_fail_total 169
telemt_upstream_connect_attempts_per_request{bucket="1"} 76690
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 66261
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10019
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 36
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 205
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 169
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 76515
telemt_user_connections_current{user="hello"} 113
telemt_user_octets_from_client{user="hello"} 1835981820 (1.71 GB)
telemt_user_octets_to_client{user="hello"} 49352241837 (45.96 GB)
telemt_user_msgs_from_client{user="hello"} 1749509
telemt_user_msgs_to_client{user="hello"} 10843758
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 53607.1 (14h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 127187
telemt_connections_bad_total 12064
telemt_handshake_timeouts_total 1722
telemt_upstream_connect_attempt_total 107950
telemt_upstream_connect_success_total 107700
telemt_upstream_connect_fail_total 249
telemt_upstream_connect_attempts_per_request{bucket="1"} 107949
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 93907
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13563
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 230
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 249
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 107694
telemt_user_connections_current{user="hello"} 179
telemt_user_octets_from_client{user="hello"} 2408591844 (2.24 GB)
telemt_user_octets_to_client{user="hello"} 103210414252 (96.12 GB)
telemt_user_msgs_from_client{user="hello"} 2632208
telemt_user_msgs_to_client{user="hello"} 13242911
telemt_user_unique_ips_current{user="hello"} 55
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 32576.6 (9h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 135
telemt_connections_bad_total 126
telemt_handshake_timeouts_total 7
telemt_upstream_connect_attempt_total 4
telemt_upstream_connect_success_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 4
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
```