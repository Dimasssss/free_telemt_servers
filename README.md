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

# Server Metrics 2026-03-11 11:11:56 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 74747.6 (20h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 226226
telemt_connections_bad_total 3623
telemt_handshake_timeouts_total 4459
telemt_upstream_connect_attempt_total 207965
telemt_upstream_connect_success_total 207900
telemt_upstream_connect_fail_total 65
telemt_upstream_connect_attempts_per_request{bucket="1"} 207965
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 190172
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17671
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 65
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 207892
telemt_user_connections_current{user="hello"} 387
telemt_user_octets_from_client{user="hello"} 4424162969 (4.12 GB)
telemt_user_octets_to_client{user="hello"} 119235946141 (111.05 GB)
telemt_user_msgs_from_client{user="hello"} 4904475
telemt_user_msgs_to_client{user="hello"} 9071623
telemt_user_unique_ips_current{user="hello"} 103
telemt_user_unique_ips_recent_window{user="hello"} 39
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 74746.8 (20h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 88670
telemt_connections_bad_total 845
telemt_handshake_timeouts_total 3202
telemt_upstream_connect_attempt_total 80560
telemt_upstream_connect_success_total 80544
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 80560
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 69551
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10729
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 264
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 80536
telemt_user_connections_current{user="hello"} 105
telemt_user_octets_from_client{user="hello"} 5075513753 (4.73 GB)
telemt_user_octets_to_client{user="hello"} 57203031164 (53.27 GB)
telemt_user_msgs_from_client{user="hello"} 3298739
telemt_user_msgs_to_client{user="hello"} 15109123
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 74746.6 (20h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 122717
telemt_connections_bad_total 1089
telemt_handshake_timeouts_total 5345
telemt_upstream_connect_attempt_total 109199
telemt_upstream_connect_success_total 109195
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 109199
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 96896
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12232
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 66
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 109187
telemt_user_connections_current{user="hello"} 126
telemt_user_octets_from_client{user="hello"} 12331381094 (11.48 GB)
telemt_user_octets_to_client{user="hello"} 87559805613 (81.55 GB)
telemt_user_msgs_from_client{user="hello"} 5974151
telemt_user_msgs_to_client{user="hello"} 17319266
telemt_user_unique_ips_current{user="hello"} 52
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 74745.5 (20h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 134105
telemt_connections_bad_total 325
telemt_handshake_timeouts_total 1242
telemt_upstream_connect_attempt_total 127223
telemt_upstream_connect_success_total 126923
telemt_upstream_connect_fail_total 300
telemt_upstream_connect_attempts_per_request{bucket="1"} 127223
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 109911
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16598
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 68
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 346
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 300
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 126915
telemt_user_connections_current{user="hello"} 181
telemt_user_octets_from_client{user="hello"} 5688437777 (5.30 GB)
telemt_user_octets_to_client{user="hello"} 93767131734 (87.33 GB)
telemt_user_msgs_from_client{user="hello"} 3867241
telemt_user_msgs_to_client{user="hello"} 25810534
telemt_user_unique_ips_current{user="hello"} 51
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 74746.8 (20h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 207689
telemt_connections_bad_total 16192
telemt_handshake_timeouts_total 3452
telemt_upstream_connect_attempt_total 167372
telemt_upstream_connect_success_total 166970
telemt_upstream_connect_fail_total 402
telemt_upstream_connect_attempts_per_request{bucket="1"} 167372
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 143712
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22946
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 312
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 402
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 166962
telemt_user_connections_current{user="hello"} 267
telemt_user_octets_from_client{user="hello"} 3711525687 (3.46 GB)
telemt_user_octets_to_client{user="hello"} 143676754490 (133.81 GB)
telemt_user_msgs_from_client{user="hello"} 3848814
telemt_user_msgs_to_client{user="hello"} 19223092
telemt_user_unique_ips_current{user="hello"} 66
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 53716.2 (14h 55m)
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