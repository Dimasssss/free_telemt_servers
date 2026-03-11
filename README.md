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

# Server Metrics 2026-03-11 06:56:25 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 59416.4 (16h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 160772
telemt_connections_bad_total 3504
telemt_handshake_timeouts_total 3948
telemt_upstream_connect_attempt_total 145243
telemt_upstream_connect_success_total 145198
telemt_upstream_connect_fail_total 45
telemt_upstream_connect_attempts_per_request{bucket="1"} 145243
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 132460
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12682
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 56
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 45
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 145192
telemt_user_connections_current{user="hello"} 302
telemt_user_octets_from_client{user="hello"} 3460451830 (3.22 GB)
telemt_user_octets_to_client{user="hello"} 95444216889 (88.89 GB)
telemt_user_msgs_from_client{user="hello"} 3657967
telemt_user_msgs_to_client{user="hello"} 6826198
telemt_user_unique_ips_current{user="hello"} 78
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 59415.5 (16h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 63315
telemt_connections_bad_total 453
telemt_handshake_timeouts_total 3064
telemt_upstream_connect_attempt_total 56665
telemt_upstream_connect_success_total 56653
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 56665
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 48379
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8043
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 231
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 56647
telemt_user_connections_current{user="hello"} 61
telemt_user_octets_from_client{user="hello"} 4653144146 (4.33 GB)
telemt_user_octets_to_client{user="hello"} 49524069983 (46.12 GB)
telemt_user_msgs_from_client{user="hello"} 2857692
telemt_user_msgs_to_client{user="hello"} 11929383
telemt_user_unique_ips_current{user="hello"} 28
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 59415.3 (16h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 85146
telemt_connections_bad_total 743
telemt_handshake_timeouts_total 4418
telemt_upstream_connect_attempt_total 75236
telemt_upstream_connect_success_total 75233
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 75236
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 66779
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8394
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 75227
telemt_user_connections_current{user="hello"} 85
telemt_user_octets_from_client{user="hello"} 11844153594 (11.03 GB)
telemt_user_octets_to_client{user="hello"} 73571720988 (68.52 GB)
telemt_user_msgs_from_client{user="hello"} 5299449
telemt_user_msgs_to_client{user="hello"} 14032196
telemt_user_unique_ips_current{user="hello"} 41
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 59414.2 (16h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 92554
telemt_connections_bad_total 204
telemt_handshake_timeouts_total 644
telemt_upstream_connect_attempt_total 88656
telemt_upstream_connect_success_total 88459
telemt_upstream_connect_fail_total 197
telemt_upstream_connect_attempts_per_request{bucket="1"} 88656
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 76591
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11572
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 47
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 249
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 197
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 88453
telemt_user_connections_current{user="hello"} 120
telemt_user_octets_from_client{user="hello"} 1993508329 (1.86 GB)
telemt_user_octets_to_client{user="hello"} 59430744137 (55.35 GB)
telemt_user_msgs_from_client{user="hello"} 1996303
telemt_user_msgs_to_client{user="hello"} 14586872
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 59415.7 (16h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 156809
telemt_connections_bad_total 13156
telemt_handshake_timeouts_total 1824
telemt_upstream_connect_attempt_total 124118
telemt_upstream_connect_success_total 123869
telemt_upstream_connect_fail_total 249
telemt_upstream_connect_attempts_per_request{bucket="1"} 124118
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 106211
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17420
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 238
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 249
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 123863
telemt_user_connections_current{user="hello"} 171
telemt_user_octets_from_client{user="hello"} 2527245355 (2.35 GB)
telemt_user_octets_to_client{user="hello"} 119623312874 (111.41 GB)
telemt_user_msgs_from_client{user="hello"} 2888149
telemt_user_msgs_to_client{user="hello"} 15416927
telemt_user_unique_ips_current{user="hello"} 61
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 38384.9 (10h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 219
telemt_connections_bad_total 199
telemt_handshake_timeouts_total 8
telemt_upstream_connect_attempt_total 15
telemt_upstream_connect_success_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 15
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11
telemt_user_octets_from_client{user="hello"} 7489 (7.31 KB)
telemt_user_octets_to_client{user="hello"} 2462 (2.40 KB)
telemt_user_msgs_from_client{user="hello"} 23
telemt_user_msgs_to_client{user="hello"} 15
```