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

# Server Metrics 2026-03-10 20:02:06 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 20158.0 (5h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 76026
telemt_connections_bad_total 2705
telemt_handshake_timeouts_total 2065
telemt_upstream_connect_attempt_total 67748
telemt_upstream_connect_success_total 67734
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 67747
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 61763
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5945
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 67732
telemt_user_connections_current{user="hello"} 297
telemt_user_octets_from_client{user="hello"} 2219934811 (2.07 GB)
telemt_user_octets_to_client{user="hello"} 52113152827 (48.53 GB)
telemt_user_msgs_from_client{user="hello"} 2033577
telemt_user_msgs_to_client{user="hello"} 3718386
telemt_user_unique_ips_current{user="hello"} 68
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 20157.0 (5h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 29720
telemt_connections_bad_total 229
telemt_handshake_timeouts_total 472
telemt_upstream_connect_attempt_total 27236
telemt_upstream_connect_success_total 27228
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 27236
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22976
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4039
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 213
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 27226
telemt_user_connections_current{user="hello"} 95
telemt_user_octets_from_client{user="hello"} 945387444 (901.59 MB)
telemt_user_octets_to_client{user="hello"} 22071426370 (20.56 GB)
telemt_user_msgs_from_client{user="hello"} 930962
telemt_user_msgs_to_client{user="hello"} 6708517
telemt_user_unique_ips_current{user="hello"} 31
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 20157.1 (5h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 47287
telemt_connections_bad_total 157
telemt_handshake_timeouts_total 3654
telemt_upstream_connect_attempt_total 40728
telemt_upstream_connect_success_total 40727
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 40728
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36857
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3831
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 39
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 40725
telemt_user_connections_current{user="hello"} 104
telemt_user_octets_from_client{user="hello"} 627536638 (598.47 MB)
telemt_user_octets_to_client{user="hello"} 38351265626 (35.72 GB)
telemt_user_msgs_from_client{user="hello"} 871696
telemt_user_msgs_to_client{user="hello"} 5755552
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 20155.6 (5h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 41931
telemt_connections_bad_total 65
telemt_handshake_timeouts_total 281
telemt_upstream_connect_attempt_total 40257
telemt_upstream_connect_success_total 40136
telemt_upstream_connect_fail_total 121
telemt_upstream_connect_attempts_per_request{bucket="1"} 40257
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35362
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4643
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 121
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 121
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 40134
telemt_user_connections_current{user="hello"} 100
telemt_user_octets_from_client{user="hello"} 690714776 (658.72 MB)
telemt_user_octets_to_client{user="hello"} 31425816671 (29.27 GB)
telemt_user_msgs_from_client{user="hello"} 876187
telemt_user_msgs_to_client{user="hello"} 5896092
telemt_user_unique_ips_current{user="hello"} 31
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 20157.0 (5h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 60895
telemt_connections_bad_total 5396
telemt_handshake_timeouts_total 1297
telemt_upstream_connect_attempt_total 51648
telemt_upstream_connect_success_total 51404
telemt_upstream_connect_fail_total 244
telemt_upstream_connect_attempts_per_request{bucket="1"} 51648
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 44945
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6275
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 184
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 244
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 51402
telemt_user_connections_current{user="hello"} 169
telemt_user_octets_from_client{user="hello"} 1542860329 (1.44 GB)
telemt_user_octets_to_client{user="hello"} 39202294211 (36.51 GB)
telemt_user_msgs_from_client{user="hello"} 1425682
telemt_user_msgs_to_client{user="hello"} 5517878
telemt_user_unique_ips_current{user="hello"} 52
telemt_user_unique_ips_recent_window{user="hello"} 13
```