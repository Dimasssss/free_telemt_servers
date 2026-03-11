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

# Server Metrics 2026-03-11 03:32:38 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 47189.1 (13h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 121124
telemt_connections_bad_total 3365
telemt_handshake_timeouts_total 2586
telemt_upstream_connect_attempt_total 109660
telemt_upstream_connect_success_total 109621
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 109660
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 99861
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9706
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 109615
telemt_user_connections_current{user="hello"} 149
telemt_user_octets_from_client{user="hello"} 2950368820 (2.75 GB)
telemt_user_octets_to_client{user="hello"} 82718149941 (77.04 GB)
telemt_user_msgs_from_client{user="hello"} 2997847
telemt_user_msgs_to_client{user="hello"} 5728112
telemt_user_unique_ips_current{user="hello"} 49
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 47188.5 (13h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 50478
telemt_connections_bad_total 399
telemt_handshake_timeouts_total 2924
telemt_upstream_connect_attempt_total 44476
telemt_upstream_connect_success_total 44466
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 44476
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37448
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6792
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 226
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 44460
telemt_user_connections_current{user="hello"} 31
telemt_user_octets_from_client{user="hello"} 2316397838 (2.16 GB)
telemt_user_octets_to_client{user="hello"} 44038029494 (41.01 GB)
telemt_user_msgs_from_client{user="hello"} 1801666
telemt_user_msgs_to_client{user="hello"} 10456283
telemt_user_unique_ips_current{user="hello"} 16
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 47188.1 (13h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 70990
telemt_connections_bad_total 663
telemt_handshake_timeouts_total 4219
telemt_upstream_connect_attempt_total 62143
telemt_upstream_connect_success_total 62141
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 62143
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 55103
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6988
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 49
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 62135
telemt_user_connections_current{user="hello"} 43
telemt_user_octets_from_client{user="hello"} 11747016327 (10.94 GB)
telemt_user_octets_to_client{user="hello"} 70592360105 (65.74 GB)
telemt_user_msgs_from_client{user="hello"} 5139289
telemt_user_msgs_to_client{user="hello"} 13215159
telemt_user_unique_ips_current{user="hello"} 26
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 47187.2 (13h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 71295
telemt_connections_bad_total 152
telemt_handshake_timeouts_total 554
telemt_upstream_connect_attempt_total 68218
telemt_upstream_connect_success_total 68059
telemt_upstream_connect_fail_total 159
telemt_upstream_connect_attempts_per_request{bucket="1"} 68218
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 59204
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8642
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 180
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 159
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 68053
telemt_user_connections_current{user="hello"} 80
telemt_user_octets_from_client{user="hello"} 1774677337 (1.65 GB)
telemt_user_octets_to_client{user="hello"} 42815276827 (39.87 GB)
telemt_user_msgs_from_client{user="hello"} 1615220
telemt_user_msgs_to_client{user="hello"} 8421626
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 47188.4 (13h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 111312
telemt_connections_bad_total 10751
telemt_handshake_timeouts_total 1548
telemt_upstream_connect_attempt_total 94912
telemt_upstream_connect_success_total 94664
telemt_upstream_connect_fail_total 248
telemt_upstream_connect_attempts_per_request{bucket="1"} 94912
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 82665
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11771
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 228
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 248
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 94658
telemt_user_connections_current{user="hello"} 189
telemt_user_octets_from_client{user="hello"} 2254333938 (2.10 GB)
telemt_user_octets_to_client{user="hello"} 86290227620 (80.36 GB)
telemt_user_msgs_from_client{user="hello"} 2362532
telemt_user_msgs_to_client{user="hello"} 11399260
telemt_user_unique_ips_current{user="hello"} 59
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 26157.8 (7h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 87
telemt_connections_bad_total 83
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 4
telemt_upstream_connect_success_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 4
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
```