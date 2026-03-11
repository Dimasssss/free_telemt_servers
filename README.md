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

# Server Metrics 2026-03-11 08:58:52 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 66763.2 (18h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 191187
telemt_connections_bad_total 3551
telemt_handshake_timeouts_total 4193
telemt_upstream_connect_attempt_total 174464
telemt_upstream_connect_success_total 174410
telemt_upstream_connect_fail_total 54
telemt_upstream_connect_attempts_per_request{bucket="1"} 174464
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 159202
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15151
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 54
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 174402
telemt_user_connections_current{user="hello"} 361
telemt_user_octets_from_client{user="hello"} 3868605590 (3.60 GB)
telemt_user_octets_to_client{user="hello"} 107011732053 (99.66 GB)
telemt_user_msgs_from_client{user="hello"} 4182236
telemt_user_msgs_to_client{user="hello"} 7816793
telemt_user_unique_ips_current{user="hello"} 95
telemt_user_unique_ips_recent_window{user="hello"} 36
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 66762.5 (18h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 74292
telemt_connections_bad_total 593
telemt_handshake_timeouts_total 3136
telemt_upstream_connect_attempt_total 67079
telemt_upstream_connect_success_total 67064
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 67079
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 57687
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9136
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 241
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 67058
telemt_user_connections_current{user="hello"} 129
telemt_user_octets_from_client{user="hello"} 4920417612 (4.58 GB)
telemt_user_octets_to_client{user="hello"} 53627661512 (49.94 GB)
telemt_user_msgs_from_client{user="hello"} 3087729
telemt_user_msgs_to_client{user="hello"} 13713189
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 66762.6 (18h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 102569
telemt_connections_bad_total 927
telemt_handshake_timeouts_total 5195
telemt_upstream_connect_attempt_total 90513
telemt_upstream_connect_success_total 90510
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 90513
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 80450
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9998
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 90502
telemt_user_connections_current{user="hello"} 151
telemt_user_octets_from_client{user="hello"} 11952252670 (11.13 GB)
telemt_user_octets_to_client{user="hello"} 77552213391 (72.23 GB)
telemt_user_msgs_from_client{user="hello"} 5527224
telemt_user_msgs_to_client{user="hello"} 15125948
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 66761.1 (18h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 114064
telemt_connections_bad_total 226
telemt_handshake_timeouts_total 1040
telemt_upstream_connect_attempt_total 108334
telemt_upstream_connect_success_total 108090
telemt_upstream_connect_fail_total 244
telemt_upstream_connect_attempts_per_request{bucket="1"} 108334
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 93210
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14530
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 56
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 294
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 244
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 108082
telemt_user_connections_current{user="hello"} 196
telemt_user_octets_from_client{user="hello"} 4649165000 (4.33 GB)
telemt_user_octets_to_client{user="hello"} 75929910094 (70.72 GB)
telemt_user_msgs_from_client{user="hello"} 3210993
telemt_user_msgs_to_client{user="hello"} 19305702
telemt_user_unique_ips_current{user="hello"} 49
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 66762.5 (18h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 182682
telemt_connections_bad_total 14656
telemt_handshake_timeouts_total 3085
telemt_upstream_connect_attempt_total 145632
telemt_upstream_connect_success_total 145231
telemt_upstream_connect_fail_total 401
telemt_upstream_connect_attempts_per_request{bucket="1"} 145632
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 124484
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20473
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 274
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 401
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 145225
telemt_user_connections_current{user="hello"} 271
telemt_user_octets_from_client{user="hello"} 2876625932 (2.68 GB)
telemt_user_octets_to_client{user="hello"} 132449325427 (123.35 GB)
telemt_user_msgs_from_client{user="hello"} 3262274
telemt_user_msgs_to_client{user="hello"} 17124903
telemt_user_unique_ips_current{user="hello"} 71
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 45731.8 (12h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 419
telemt_connections_bad_total 397
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