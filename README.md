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

# Server Metrics 2026-03-11 21:47:44 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 176.6 (0h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 485
telemt_handshake_timeouts_total 6
telemt_upstream_connect_attempt_total 474
telemt_upstream_connect_success_total 473
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 474
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 421
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 52
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 471
telemt_user_connections_current{user="hello"} 228
telemt_user_octets_from_client{user="hello"} 4370484 (4.17 MB)
telemt_user_octets_to_client{user="hello"} 347216451 (331.13 MB)
telemt_user_msgs_from_client{user="hello"} 10504
telemt_user_msgs_to_client{user="hello"} 52931
telemt_user_unique_ips_current{user="hello"} 52
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 164.8 (0h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 244
telemt_upstream_connect_attempt_total 235
telemt_upstream_connect_success_total 235
telemt_upstream_connect_attempts_per_request{bucket="1"} 235
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 217
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 233
telemt_user_connections_current{user="hello"} 91
telemt_user_octets_from_client{user="hello"} 1549309 (1.48 MB)
telemt_user_octets_to_client{user="hello"} 28373449 (27.06 MB)
telemt_user_msgs_from_client{user="hello"} 3644
telemt_user_msgs_to_client{user="hello"} 11059
telemt_user_unique_ips_current{user="hello"} 25
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 138.4 (0h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 371
telemt_handshake_timeouts_total 1
telemt_upstream_connect_attempt_total 254
telemt_upstream_connect_success_total 253
telemt_upstream_connect_attempts_per_request{bucket="1"} 253
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 213
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 40
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 251
telemt_user_connections_current{user="hello"} 86
telemt_user_octets_from_client{user="hello"} 1225213 (1.17 MB)
telemt_user_octets_to_client{user="hello"} 46869275 (44.70 MB)
telemt_user_msgs_from_client{user="hello"} 3242
telemt_user_msgs_to_client{user="hello"} 11312
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 163.6 (0h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 220
telemt_connections_bad_total 1
telemt_handshake_timeouts_total 3
telemt_upstream_connect_attempt_total 215
telemt_upstream_connect_success_total 215
telemt_upstream_connect_attempts_per_request{bucket="1"} 215
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 188
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 213
telemt_user_connections_current{user="hello"} 103
telemt_user_octets_from_client{user="hello"} 890793 (869.92 KB)
telemt_user_octets_to_client{user="hello"} 76960651 (73.40 MB)
telemt_user_msgs_from_client{user="hello"} 2524
telemt_user_msgs_to_client{user="hello"} 16665
telemt_user_unique_ips_current{user="hello"} 29
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 164.9 (0h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 248
telemt_connections_bad_total 30
telemt_handshake_timeouts_total 1
telemt_upstream_connect_attempt_total 214
telemt_upstream_connect_success_total 214
telemt_upstream_connect_attempts_per_request{bucket="1"} 214
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 202
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 212
telemt_user_connections_current{user="hello"} 74
telemt_user_octets_from_client{user="hello"} 539338 (526.70 KB)
telemt_user_octets_to_client{user="hello"} 14223405 (13.56 MB)
telemt_user_msgs_from_client{user="hello"} 1441
telemt_user_msgs_to_client{user="hello"} 2885
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 164.4 (0h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 196
telemt_connections_bad_total 1
telemt_upstream_connect_attempt_total 195
telemt_upstream_connect_success_total 195
telemt_upstream_connect_attempts_per_request{bucket="1"} 195
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 140
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 55
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 193
telemt_user_connections_current{user="hello"} 31
telemt_user_octets_from_client{user="hello"} 959530 (937.04 KB)
telemt_user_octets_to_client{user="hello"} 52467625 (50.04 MB)
telemt_user_msgs_from_client{user="hello"} 2604
telemt_user_msgs_to_client{user="hello"} 8389
telemt_user_unique_ips_current{user="hello"} 14
telemt_user_unique_ips_recent_window{user="hello"} 6
```