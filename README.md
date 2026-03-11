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

# Server Metrics 2026-03-11 17:16:30 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 970.9 (0h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4393
telemt_connections_bad_total 255
telemt_handshake_timeouts_total 25
telemt_upstream_connect_attempt_total 3932
telemt_upstream_connect_success_total 3930
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 3932
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3596
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 333
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3928
telemt_user_connections_current{user="hello"} 325
telemt_user_octets_from_client{user="hello"} 111898250 (106.71 MB)
telemt_user_octets_to_client{user="hello"} 1290064115 (1.20 GB)
telemt_user_msgs_from_client{user="hello"} 88589
telemt_user_msgs_to_client{user="hello"} 120231
telemt_user_unique_ips_current{user="hello"} 80
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 959.2 (0h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2314
telemt_connections_bad_total 1
telemt_handshake_timeouts_total 50
telemt_upstream_connect_attempt_total 2082
telemt_upstream_connect_success_total 2081
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 2082
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1789
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 199
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 93
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2079
telemt_user_connections_current{user="hello"} 172
telemt_user_octets_from_client{user="hello"} 14436773 (13.77 MB)
telemt_user_octets_to_client{user="hello"} 848457929 (809.15 MB)
telemt_user_msgs_from_client{user="hello"} 34379
telemt_user_msgs_to_client{user="hello"} 301567
telemt_user_unique_ips_current{user="hello"} 44
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 978.3 (0h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2432
telemt_connections_bad_total 1
telemt_handshake_timeouts_total 11
telemt_upstream_connect_attempt_total 2340
telemt_upstream_connect_success_total 2340
telemt_upstream_connect_attempts_per_request{bucket="1"} 2340
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2118
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 222
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2338
telemt_user_connections_current{user="hello"} 111
telemt_user_octets_from_client{user="hello"} 13303237 (12.69 MB)
telemt_user_octets_to_client{user="hello"} 477973336 (455.83 MB)
telemt_user_msgs_from_client{user="hello"} 36538
telemt_user_msgs_to_client{user="hello"} 193341
telemt_user_unique_ips_current{user="hello"} 60
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 974.1 (0h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2410
telemt_connections_bad_total 15
telemt_handshake_timeouts_total 113
telemt_upstream_connect_attempt_total 2192
telemt_upstream_connect_success_total 2184
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 2192
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1944
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 233
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2182
telemt_user_connections_current{user="hello"} 183
telemt_user_octets_from_client{user="hello"} 52856744 (50.41 MB)
telemt_user_octets_to_client{user="hello"} 957883333 (913.51 MB)
telemt_user_msgs_from_client{user="hello"} 48945
telemt_user_msgs_to_client{user="hello"} 247323
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 982.4 (0h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2729
telemt_connections_bad_total 202
telemt_handshake_timeouts_total 35
telemt_upstream_connect_attempt_total 2411
telemt_upstream_connect_success_total 2411
telemt_upstream_connect_attempts_per_request{bucket="1"} 2411
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2091
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 318
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2409
telemt_user_connections_current{user="hello"} 140
telemt_user_octets_from_client{user="hello"} 14722359 (14.04 MB)
telemt_user_octets_to_client{user="hello"} 303980992 (289.90 MB)
telemt_user_msgs_from_client{user="hello"} 25608
telemt_user_msgs_to_client{user="hello"} 113250
telemt_user_unique_ips_current{user="hello"} 57
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 75588.6 (20h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 492
telemt_connections_bad_total 468
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