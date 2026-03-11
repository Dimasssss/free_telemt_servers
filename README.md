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

# Server Metrics 2026-03-11 17:36:58 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 2199.3 (0h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9296
telemt_connections_bad_total 505
telemt_handshake_timeouts_total 52
telemt_upstream_connect_attempt_total 8329
telemt_upstream_connect_success_total 8326
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 8329
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7472
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 849
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 8324
telemt_user_connections_current{user="hello"} 368
telemt_user_octets_from_client{user="hello"} 173236755 (165.21 MB)
telemt_user_octets_to_client{user="hello"} 5632804245 (5.25 GB)
telemt_user_msgs_from_client{user="hello"} 185859
telemt_user_msgs_to_client{user="hello"} 418904
telemt_user_unique_ips_current{user="hello"} 88
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 2187.5 (0h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5029
telemt_connections_bad_total 8
telemt_handshake_timeouts_total 94
telemt_upstream_connect_attempt_total 4551
telemt_upstream_connect_success_total 4550
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 4551
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3968
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 460
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 122
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4548
telemt_user_connections_current{user="hello"} 184
telemt_user_octets_from_client{user="hello"} 53691838 (51.20 MB)
telemt_user_octets_to_client{user="hello"} 3118456994 (2.90 GB)
telemt_user_msgs_from_client{user="hello"} 96645
telemt_user_msgs_to_client{user="hello"} 1246895
telemt_user_unique_ips_current{user="hello"} 41
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 2206.8 (0h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5130
telemt_connections_bad_total 4
telemt_handshake_timeouts_total 25
telemt_upstream_connect_attempt_total 4846
telemt_upstream_connect_success_total 4845
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 4846
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4349
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 496
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4843
telemt_user_connections_current{user="hello"} 135
telemt_user_octets_from_client{user="hello"} 36414114 (34.73 MB)
telemt_user_octets_to_client{user="hello"} 1575838782 (1.47 GB)
telemt_user_msgs_from_client{user="hello"} 90906
telemt_user_msgs_to_client{user="hello"} 490685
telemt_user_unique_ips_current{user="hello"} 60
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 2202.8 (0h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5018
telemt_connections_bad_total 17
telemt_handshake_timeouts_total 176
telemt_upstream_connect_attempt_total 4654
telemt_upstream_connect_success_total 4642
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 4654
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4133
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 496
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4640
telemt_user_connections_current{user="hello"} 135
telemt_user_octets_from_client{user="hello"} 205599002 (196.07 MB)
telemt_user_octets_to_client{user="hello"} 2065101035 (1.92 GB)
telemt_user_msgs_from_client{user="hello"} 135658
telemt_user_msgs_to_client{user="hello"} 510126
telemt_user_unique_ips_current{user="hello"} 48
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 2210.7 (0h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5820
telemt_connections_bad_total 498
telemt_handshake_timeouts_total 52
telemt_upstream_connect_attempt_total 5148
telemt_upstream_connect_success_total 5148
telemt_upstream_connect_attempts_per_request{bucket="1"} 5148
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4403
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 743
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 5146
telemt_user_connections_current{user="hello"} 197
telemt_user_octets_from_client{user="hello"} 31503441 (30.04 MB)
telemt_user_octets_to_client{user="hello"} 679477764 (648.00 MB)
telemt_user_msgs_from_client{user="hello"} 65609
telemt_user_msgs_to_client{user="hello"} 239914
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 76817.1 (21h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 495
telemt_connections_bad_total 471
telemt_handshake_timeouts_total 14
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