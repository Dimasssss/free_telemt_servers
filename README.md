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

# Server Metrics 2026-03-10 20:34:45 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 22117.3 (6h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 82682
telemt_connections_bad_total 3144
telemt_handshake_timeouts_total 2111
telemt_upstream_connect_attempt_total 73605
telemt_upstream_connect_success_total 73579
telemt_upstream_connect_fail_total 26
telemt_upstream_connect_attempts_per_request{bucket="1"} 73605
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 67117
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6424
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 26
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 73577
telemt_user_connections_current{user="hello"} 255
telemt_user_octets_from_client{user="hello"} 2404770029 (2.24 GB)
telemt_user_octets_to_client{user="hello"} 57449320691 (53.50 GB)
telemt_user_msgs_from_client{user="hello"} 2198494
telemt_user_msgs_to_client{user="hello"} 3954167
telemt_user_unique_ips_current{user="hello"} 72
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 22116.5 (6h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 31606
telemt_connections_bad_total 242
telemt_handshake_timeouts_total 531
telemt_upstream_connect_attempt_total 28927
telemt_upstream_connect_success_total 28919
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 28927
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24422
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4280
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 217
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 28915
telemt_user_connections_current{user="hello"} 91
telemt_user_octets_from_client{user="hello"} 1370995578 (1.28 GB)
telemt_user_octets_to_client{user="hello"} 24326083479 (22.66 GB)
telemt_user_msgs_from_client{user="hello"} 1112308
telemt_user_msgs_to_client{user="hello"} 7164081
telemt_user_unique_ips_current{user="hello"} 29
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 22116.3 (6h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 50844
telemt_connections_bad_total 290
telemt_handshake_timeouts_total 3686
telemt_upstream_connect_attempt_total 43942
telemt_upstream_connect_success_total 43941
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 43942
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 39722
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4174
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 44
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 43937
telemt_user_connections_current{user="hello"} 117
telemt_user_octets_from_client{user="hello"} 673730196 (642.52 MB)
telemt_user_octets_to_client{user="hello"} 41689602044 (38.83 GB)
telemt_user_msgs_from_client{user="hello"} 942623
telemt_user_msgs_to_client{user="hello"} 6233441
telemt_user_unique_ips_current{user="hello"} 44
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 22115.2 (6h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 45323
telemt_connections_bad_total 69
telemt_handshake_timeouts_total 314
telemt_upstream_connect_attempt_total 43467
telemt_upstream_connect_success_total 43340
telemt_upstream_connect_fail_total 127
telemt_upstream_connect_attempts_per_request{bucket="1"} 43467
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 38214
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4986
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 129
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 127
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 43336
telemt_user_connections_current{user="hello"} 105
telemt_user_octets_from_client{user="hello"} 736425900 (702.31 MB)
telemt_user_octets_to_client{user="hello"} 32778735226 (30.53 GB)
telemt_user_msgs_from_client{user="hello"} 944743
telemt_user_msgs_to_client{user="hello"} 6291149
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 22116.5 (6h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 64365
telemt_connections_bad_total 5814
telemt_handshake_timeouts_total 1352
telemt_upstream_connect_attempt_total 54500
telemt_upstream_connect_success_total 54256
telemt_upstream_connect_fail_total 244
telemt_upstream_connect_attempts_per_request{bucket="1"} 54500
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 47433
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6636
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 187
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 244
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 54252
telemt_user_connections_current{user="hello"} 194
telemt_user_octets_from_client{user="hello"} 1736853599 (1.62 GB)
telemt_user_octets_to_client{user="hello"} 42900454879 (39.95 GB)
telemt_user_msgs_from_client{user="hello"} 1563042
telemt_user_msgs_to_client{user="hello"} 5899660
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 1085.9 (0h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16
telemt_connections_bad_total 16
telemt_upstream_connect_attempt_total 2
telemt_upstream_connect_success_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
```