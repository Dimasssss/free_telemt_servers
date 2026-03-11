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

# Server Metrics 2026-03-11 17:01:07 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 48.5 (0h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 439
telemt_connections_bad_total 17
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 408
telemt_upstream_connect_success_total 407
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 408
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 391
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 405
telemt_user_connections_current{user="hello"} 277
telemt_user_octets_from_client{user="hello"} 2255968 (2.15 MB)
telemt_user_octets_to_client{user="hello"} 168926836 (161.10 MB)
telemt_user_msgs_from_client{user="hello"} 3870
telemt_user_msgs_to_client{user="hello"} 10062
telemt_user_unique_ips_current{user="hello"} 66
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 36.7 (0h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 219
telemt_upstream_connect_attempt_total 199
telemt_upstream_connect_success_total 198
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 199
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 175
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 196
telemt_user_connections_current{user="hello"} 134
telemt_user_octets_from_client{user="hello"} 334863 (327.01 KB)
telemt_user_octets_to_client{user="hello"} 16835174 (16.06 MB)
telemt_user_msgs_from_client{user="hello"} 867
telemt_user_msgs_to_client{user="hello"} 6259
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 40
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 56.4 (0h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 222
telemt_handshake_timeouts_total 1
telemt_upstream_connect_attempt_total 219
telemt_upstream_connect_success_total 219
telemt_upstream_connect_attempts_per_request{bucket="1"} 219
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 200
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 217
telemt_user_connections_current{user="hello"} 125
telemt_user_octets_from_client{user="hello"} 602948 (588.82 KB)
telemt_user_octets_to_client{user="hello"} 14235712 (13.58 MB)
telemt_user_msgs_from_client{user="hello"} 1972
telemt_user_msgs_to_client{user="hello"} 7105
telemt_user_unique_ips_current{user="hello"} 50
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 52.1 (0h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 275
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 268
telemt_upstream_connect_success_total 267
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 268
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 227
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 37
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 265
telemt_user_connections_current{user="hello"} 145
telemt_user_octets_from_client{user="hello"} 1200224 (1.14 MB)
telemt_user_octets_to_client{user="hello"} 50886819 (48.53 MB)
telemt_user_msgs_from_client{user="hello"} 2445
telemt_user_msgs_to_client{user="hello"} 11297
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 60.7 (0h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 355
telemt_connections_bad_total 10
telemt_upstream_connect_attempt_total 328
telemt_upstream_connect_success_total 328
telemt_upstream_connect_attempts_per_request{bucket="1"} 328
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 254
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 74
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 326
telemt_user_connections_current{user="hello"} 112
telemt_user_octets_from_client{user="hello"} 1919310 (1.83 MB)
telemt_user_octets_to_client{user="hello"} 55323232 (52.76 MB)
telemt_user_msgs_from_client{user="hello"} 3288
telemt_user_msgs_to_client{user="hello"} 20654
telemt_user_unique_ips_current{user="hello"} 45
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 74667.0 (20h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 491
telemt_connections_bad_total 467
telemt_handshake_timeouts_total 13
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