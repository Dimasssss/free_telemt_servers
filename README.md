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

# Server Metrics 2026-03-11 04:18:28 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 49939.3 (13h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 127431
telemt_connections_bad_total 3383
telemt_handshake_timeouts_total 2659
telemt_upstream_connect_attempt_total 115498
telemt_upstream_connect_success_total 115457
telemt_upstream_connect_fail_total 41
telemt_upstream_connect_attempts_per_request{bucket="1"} 115498
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 105315
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10087
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 55
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 41
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 115451
telemt_user_connections_current{user="hello"} 221
telemt_user_octets_from_client{user="hello"} 3012352399 (2.81 GB)
telemt_user_octets_to_client{user="hello"} 84234040822 (78.45 GB)
telemt_user_msgs_from_client{user="hello"} 3082957
telemt_user_msgs_to_client{user="hello"} 5862351
telemt_user_unique_ips_current{user="hello"} 63
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 49938.6 (13h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 52282
telemt_connections_bad_total 405
telemt_handshake_timeouts_total 2941
telemt_upstream_connect_attempt_total 46176
telemt_upstream_connect_success_total 46166
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 46176
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 38971
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6969
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 226
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 46160
telemt_user_connections_current{user="hello"} 47
telemt_user_octets_from_client{user="hello"} 2334712483 (2.17 GB)
telemt_user_octets_to_client{user="hello"} 44341990809 (41.30 GB)
telemt_user_msgs_from_client{user="hello"} 1834778
telemt_user_msgs_to_client{user="hello"} 10558375
telemt_user_unique_ips_current{user="hello"} 23
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 49938.3 (13h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 73126
telemt_connections_bad_total 672
telemt_handshake_timeouts_total 4259
telemt_upstream_connect_attempt_total 64141
telemt_upstream_connect_success_total 64138
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 64141
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 56835
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7251
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 51
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 64132
telemt_user_connections_current{user="hello"} 40
telemt_user_octets_from_client{user="hello"} 11766145566 (10.96 GB)
telemt_user_octets_to_client{user="hello"} 70821163306 (65.96 GB)
telemt_user_msgs_from_client{user="hello"} 5163726
telemt_user_msgs_to_client{user="hello"} 13286601
telemt_user_unique_ips_current{user="hello"} 27
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 49937.6 (13h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 74934
telemt_connections_bad_total 155
telemt_handshake_timeouts_total 566
telemt_upstream_connect_attempt_total 71738
telemt_upstream_connect_success_total 71575
telemt_upstream_connect_fail_total 163
telemt_upstream_connect_attempts_per_request{bucket="1"} 71738
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 62129
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9223
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 35
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 188
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 163
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 71569
telemt_user_connections_current{user="hello"} 77
telemt_user_octets_from_client{user="hello"} 1791311043 (1.67 GB)
telemt_user_octets_to_client{user="hello"} 43879725525 (40.87 GB)
telemt_user_msgs_from_client{user="hello"} 1652955
telemt_user_msgs_to_client{user="hello"} 8749597
telemt_user_unique_ips_current{user="hello"} 30
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 49938.6 (13h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 118484
telemt_connections_bad_total 11315
telemt_handshake_timeouts_total 1657
telemt_upstream_connect_attempt_total 100989
telemt_upstream_connect_success_total 100740
telemt_upstream_connect_fail_total 249
telemt_upstream_connect_attempts_per_request{bucket="1"} 100989
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 88239
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12272
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 229
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 249
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 100734
telemt_user_connections_current{user="hello"} 168
telemt_user_octets_from_client{user="hello"} 2303116685 (2.14 GB)
telemt_user_octets_to_client{user="hello"} 93438528334 (87.02 GB)
telemt_user_msgs_from_client{user="hello"} 2462884
telemt_user_msgs_to_client{user="hello"} 12004775
telemt_user_unique_ips_current{user="hello"} 52
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 28907.9 (8h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 128
telemt_connections_bad_total 119
telemt_handshake_timeouts_total 7
telemt_upstream_connect_attempt_total 4
telemt_upstream_connect_success_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 4
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
```