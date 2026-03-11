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

# Server Metrics 2026-03-11 10:46:19 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 73210.6 (20h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 219438
telemt_connections_bad_total 3618
telemt_handshake_timeouts_total 4423
telemt_upstream_connect_attempt_total 201440
telemt_upstream_connect_success_total 201376
telemt_upstream_connect_fail_total 64
telemt_upstream_connect_attempts_per_request{bucket="1"} 201440
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 184210
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17109
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 64
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 201368
telemt_user_connections_current{user="hello"} 329
telemt_user_octets_from_client{user="hello"} 4328836286 (4.03 GB)
telemt_user_octets_to_client{user="hello"} 116367702657 (108.38 GB)
telemt_user_msgs_from_client{user="hello"} 4752985
telemt_user_msgs_to_client{user="hello"} 8796160
telemt_user_unique_ips_current{user="hello"} 92
telemt_user_unique_ips_recent_window{user="hello"} 38
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 73209.8 (20h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 86098
telemt_connections_bad_total 799
telemt_handshake_timeouts_total 3176
telemt_upstream_connect_attempt_total 78147
telemt_upstream_connect_success_total 78131
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 78147
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 67391
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10480
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 260
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 78123
telemt_user_connections_current{user="hello"} 96
telemt_user_octets_from_client{user="hello"} 5034042989 (4.69 GB)
telemt_user_octets_to_client{user="hello"} 56675703261 (52.78 GB)
telemt_user_msgs_from_client{user="hello"} 3255341
telemt_user_msgs_to_client{user="hello"} 14828567
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 73209.7 (20h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 118944
telemt_connections_bad_total 1078
telemt_handshake_timeouts_total 5316
telemt_upstream_connect_attempt_total 105719
telemt_upstream_connect_success_total 105715
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 105719
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 93769
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11880
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 65
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 105707
telemt_user_connections_current{user="hello"} 144
telemt_user_octets_from_client{user="hello"} 12307988127 (11.46 GB)
telemt_user_octets_to_client{user="hello"} 86869218081 (80.90 GB)
telemt_user_msgs_from_client{user="hello"} 5914540
telemt_user_msgs_to_client{user="hello"} 17082155
telemt_user_unique_ips_current{user="hello"} 58
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 73208.8 (20h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 130385
telemt_connections_bad_total 324
telemt_handshake_timeouts_total 1233
telemt_upstream_connect_attempt_total 123611
telemt_upstream_connect_success_total 123325
telemt_upstream_connect_fail_total 286
telemt_upstream_connect_attempts_per_request{bucket="1"} 123611
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 106722
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16199
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 66
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 338
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 286
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 123317
telemt_user_connections_current{user="hello"} 211
telemt_user_octets_from_client{user="hello"} 5648273240 (5.26 GB)
telemt_user_octets_to_client{user="hello"} 88622551384 (82.54 GB)
telemt_user_msgs_from_client{user="hello"} 3785221
telemt_user_msgs_to_client{user="hello"} 23495033
telemt_user_unique_ips_current{user="hello"} 47
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 73209.8 (20h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 203245
telemt_connections_bad_total 15892
telemt_handshake_timeouts_total 3417
telemt_upstream_connect_attempt_total 163427
telemt_upstream_connect_success_total 163025
telemt_upstream_connect_fail_total 402
telemt_upstream_connect_attempts_per_request{bucket="1"} 163427
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 140102
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22620
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 303
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 402
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 163017
telemt_user_connections_current{user="hello"} 245
telemt_user_octets_from_client{user="hello"} 3623407147 (3.37 GB)
telemt_user_octets_to_client{user="hello"} 142935434974 (133.12 GB)
telemt_user_msgs_from_client{user="hello"} 3773430
telemt_user_msgs_to_client{user="hello"} 19064180
telemt_user_unique_ips_current{user="hello"} 72
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 52179.3 (14h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 422
telemt_connections_bad_total 400
telemt_handshake_timeouts_total 9
telemt_upstream_connect_attempt_total 17
telemt_upstream_connect_success_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 17
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11
telemt_user_octets_from_client{user="hello"} 7489 (7.31 KB)
telemt_user_octets_to_client{user="hello"} 2462 (2.40 KB)
telemt_user_msgs_from_client{user="hello"} 23
telemt_user_msgs_to_client{user="hello"} 15
```