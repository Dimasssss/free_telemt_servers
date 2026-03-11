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

# Server Metrics 2026-03-11 11:06:50 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 74440.7 (20h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 224797
telemt_connections_bad_total 3623
telemt_handshake_timeouts_total 4447
telemt_upstream_connect_attempt_total 206593
telemt_upstream_connect_success_total 206528
telemt_upstream_connect_fail_total 65
telemt_upstream_connect_attempts_per_request{bucket="1"} 206593
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 188907
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17564
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 65
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 206520
telemt_user_connections_current{user="hello"} 414
telemt_user_octets_from_client{user="hello"} 4391103029 (4.09 GB)
telemt_user_octets_to_client{user="hello"} 118500549651 (110.36 GB)
telemt_user_msgs_from_client{user="hello"} 4865692
telemt_user_msgs_to_client{user="hello"} 9014406
telemt_user_unique_ips_current{user="hello"} 94
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 74439.7 (20h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 88132
telemt_connections_bad_total 830
telemt_handshake_timeouts_total 3202
telemt_upstream_connect_attempt_total 80051
telemt_upstream_connect_success_total 80034
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 80050
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 69094
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10677
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 263
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 80026
telemt_user_connections_current{user="hello"} 101
telemt_user_octets_from_client{user="hello"} 5065002292 (4.72 GB)
telemt_user_octets_to_client{user="hello"} 56998514171 (53.08 GB)
telemt_user_msgs_from_client{user="hello"} 3288011
telemt_user_msgs_to_client{user="hello"} 15000691
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 74439.4 (20h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 121998
telemt_connections_bad_total 1089
telemt_handshake_timeouts_total 5341
telemt_upstream_connect_attempt_total 108522
telemt_upstream_connect_success_total 108518
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 108522
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 96277
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12174
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 66
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 108510
telemt_user_connections_current{user="hello"} 141
telemt_user_octets_from_client{user="hello"} 12326134320 (11.48 GB)
telemt_user_octets_to_client{user="hello"} 87298380077 (81.30 GB)
telemt_user_msgs_from_client{user="hello"} 5959515
telemt_user_msgs_to_client{user="hello"} 17240738
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 74438.3 (20h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 133386
telemt_connections_bad_total 325
telemt_handshake_timeouts_total 1240
telemt_upstream_connect_attempt_total 126529
telemt_upstream_connect_success_total 126230
telemt_upstream_connect_fail_total 299
telemt_upstream_connect_attempts_per_request{bucket="1"} 126529
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 109315
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16503
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 67
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 345
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 299
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 126222
telemt_user_connections_current{user="hello"} 177
telemt_user_octets_from_client{user="hello"} 5684110154 (5.29 GB)
telemt_user_octets_to_client{user="hello"} 93131178868 (86.74 GB)
telemt_user_msgs_from_client{user="hello"} 3856440
telemt_user_msgs_to_client{user="hello"} 25533525
telemt_user_unique_ips_current{user="hello"} 50
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 74439.5 (20h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 206657
telemt_connections_bad_total 16136
telemt_handshake_timeouts_total 3442
telemt_upstream_connect_attempt_total 166465
telemt_upstream_connect_success_total 166063
telemt_upstream_connect_fail_total 402
telemt_upstream_connect_attempts_per_request{bucket="1"} 166465
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 142872
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22882
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 309
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 402
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 166055
telemt_user_connections_current{user="hello"} 252
telemt_user_octets_from_client{user="hello"} 3701744164 (3.45 GB)
telemt_user_octets_to_client{user="hello"} 143454653967 (133.60 GB)
telemt_user_msgs_from_client{user="hello"} 3835132
telemt_user_msgs_to_client{user="hello"} 19179571
telemt_user_unique_ips_current{user="hello"} 71
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 53408.9 (14h 50m)
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