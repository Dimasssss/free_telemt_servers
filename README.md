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

# Server Metrics 2026-03-11 02:36:36 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 43827.5 (12h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 115510
telemt_connections_bad_total 3353
telemt_handshake_timeouts_total 2560
telemt_upstream_connect_attempt_total 104344
telemt_upstream_connect_success_total 104308
telemt_upstream_connect_fail_total 36
telemt_upstream_connect_attempts_per_request{bucket="1"} 104344
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 94975
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9279
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 36
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 104302
telemt_user_connections_current{user="hello"} 192
telemt_user_octets_from_client{user="hello"} 2891477328 (2.69 GB)
telemt_user_octets_to_client{user="hello"} 80980688902 (75.42 GB)
telemt_user_msgs_from_client{user="hello"} 2929245
telemt_user_msgs_to_client{user="hello"} 5614349
telemt_user_unique_ips_current{user="hello"} 66
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 43826.8 (12h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 47723
telemt_connections_bad_total 366
telemt_handshake_timeouts_total 2416
telemt_upstream_connect_attempt_total 42294
telemt_upstream_connect_success_total 42285
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 42294
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35645
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6416
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 224
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 42281
telemt_user_connections_current{user="hello"} 58
telemt_user_octets_from_client{user="hello"} 2269005856 (2.11 GB)
telemt_user_octets_to_client{user="hello"} 41535473857 (38.68 GB)
telemt_user_msgs_from_client{user="hello"} 1747438
telemt_user_msgs_to_client{user="hello"} 10077313
telemt_user_unique_ips_current{user="hello"} 20
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 43826.5 (12h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 68832
telemt_connections_bad_total 655
telemt_handshake_timeouts_total 4202
telemt_upstream_connect_attempt_total 60103
telemt_upstream_connect_success_total 60101
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 60103
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 53518
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6534
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 60095
telemt_user_connections_current{user="hello"} 55
telemt_user_octets_from_client{user="hello"} 11737812465 (10.93 GB)
telemt_user_octets_to_client{user="hello"} 69997818208 (65.19 GB)
telemt_user_msgs_from_client{user="hello"} 5123344
telemt_user_msgs_to_client{user="hello"} 13123336
telemt_user_unique_ips_current{user="hello"} 28
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 43825.5 (12h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 67477
telemt_connections_bad_total 147
telemt_handshake_timeouts_total 543
telemt_upstream_connect_attempt_total 64543
telemt_upstream_connect_success_total 64387
telemt_upstream_connect_fail_total 156
telemt_upstream_connect_attempts_per_request{bucket="1"} 64543
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 56146
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8044
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 170
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 156
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 64381
telemt_user_connections_current{user="hello"} 73
telemt_user_octets_from_client{user="hello"} 1758224267 (1.64 GB)
telemt_user_octets_to_client{user="hello"} 42605665438 (39.68 GB)
telemt_user_msgs_from_client{user="hello"} 1585686
telemt_user_msgs_to_client{user="hello"} 8347809
telemt_user_unique_ips_current{user="hello"} 22
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 43826.7 (12h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 101350
telemt_connections_bad_total 10133
telemt_handshake_timeouts_total 1525
telemt_upstream_connect_attempt_total 85908
telemt_upstream_connect_success_total 85660
telemt_upstream_connect_fail_total 248
telemt_upstream_connect_attempts_per_request{bucket="1"} 85908
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 74310
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11124
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 226
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 248
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 85656
telemt_user_connections_current{user="hello"} 111
telemt_user_octets_from_client{user="hello"} 2184688744 (2.03 GB)
telemt_user_octets_to_client{user="hello"} 73571484139 (68.52 GB)
telemt_user_msgs_from_client{user="hello"} 2214735
telemt_user_msgs_to_client{user="hello"} 10266578
telemt_user_unique_ips_current{user="hello"} 41
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 22796.2 (6h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 80
telemt_connections_bad_total 76
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 2
telemt_upstream_connect_success_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
```