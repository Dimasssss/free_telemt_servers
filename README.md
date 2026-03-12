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

# Server Metrics 2026-03-12 07:05:42 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 33653.9 (9h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 96614
telemt_connections_bad_total 2120
telemt_handshake_timeouts_total 2437
telemt_upstream_connect_attempt_total 87601
telemt_upstream_connect_success_total 87318
telemt_upstream_connect_fail_total 283
telemt_upstream_connect_attempts_per_request{bucket="1"} 87601
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 74041
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12955
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 322
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 283
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 87314
telemt_user_connections_current{user="hello"} 318
telemt_user_octets_from_client{user="hello"} 880931984 (840.12 MB)
telemt_user_octets_to_client{user="hello"} 25780565569 (24.01 GB)
telemt_user_msgs_from_client{user="hello"} 1301425
telemt_user_msgs_to_client{user="hello"} 2942550
telemt_user_unique_ips_current{user="hello"} 83
telemt_user_unique_ips_recent_window{user="hello"} 38
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 33642.0 (9h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 39336
telemt_connections_bad_total 211
telemt_handshake_timeouts_total 557
telemt_upstream_connect_attempt_total 37207
telemt_upstream_connect_success_total 37118
telemt_upstream_connect_fail_total 89
telemt_upstream_connect_attempts_per_request{bucket="1"} 37207
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31899
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5105
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 114
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 89
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 37114
telemt_user_connections_current{user="hello"} 135
telemt_user_octets_from_client{user="hello"} 321731266 (306.83 MB)
telemt_user_octets_to_client{user="hello"} 16514050758 (15.38 GB)
telemt_user_msgs_from_client{user="hello"} 639039
telemt_user_msgs_to_client{user="hello"} 5277373
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 33615.8 (9h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 58342
telemt_connections_bad_total 758
telemt_handshake_timeouts_total 1142
telemt_upstream_connect_attempt_total 52690
telemt_upstream_connect_success_total 52606
telemt_upstream_connect_fail_total 84
telemt_upstream_connect_attempts_per_request{bucket="1"} 52690
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 43509
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8975
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 122
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 84
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 52602
telemt_user_connections_current{user="hello"} 176
telemt_user_octets_from_client{user="hello"} 5484968497 (5.11 GB)
telemt_user_octets_to_client{user="hello"} 31313448414 (29.16 GB)
telemt_user_msgs_from_client{user="hello"} 2777595
telemt_user_msgs_to_client{user="hello"} 5582993
telemt_user_unique_ips_current{user="hello"} 78
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 33641.1 (9h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 63417
telemt_connections_bad_total 13098
telemt_handshake_timeouts_total 931
telemt_upstream_connect_attempt_total 46744
telemt_upstream_connect_success_total 44946
telemt_upstream_connect_fail_total 1798
telemt_upstream_connect_attempts_per_request{bucket="1"} 46744
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37087
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7659
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 190
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1798
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 44942
telemt_user_connections_current{user="hello"} 157
telemt_user_octets_from_client{user="hello"} 1431627173 (1.33 GB)
telemt_user_octets_to_client{user="hello"} 36385582865 (33.89 GB)
telemt_user_msgs_from_client{user="hello"} 1209054
telemt_user_msgs_to_client{user="hello"} 14586899
telemt_user_unique_ips_current{user="hello"} 48
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 3833.4 (1h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6167
telemt_connections_bad_total 708
telemt_handshake_timeouts_total 141
telemt_upstream_connect_attempt_total 5136
telemt_upstream_connect_success_total 5075
telemt_upstream_connect_fail_total 61
telemt_upstream_connect_attempts_per_request{bucket="1"} 5136
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4528
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 480
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 67
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 61
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 5073
telemt_user_connections_current{user="hello"} 121
telemt_user_octets_from_client{user="hello"} 140313047 (133.81 MB)
telemt_user_octets_to_client{user="hello"} 5015507942 (4.67 GB)
telemt_user_msgs_from_client{user="hello"} 152069
telemt_user_msgs_to_client{user="hello"} 747652
telemt_user_unique_ips_current{user="hello"} 41
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 33641.9 (9h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 61524
telemt_connections_bad_total 1033
telemt_handshake_timeouts_total 342
telemt_upstream_connect_attempt_total 57503
telemt_upstream_connect_success_total 57356
telemt_upstream_connect_fail_total 146
telemt_upstream_connect_attempts_per_request{bucket="1"} 57502
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 47767
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9442
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 144
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 146
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 57352
telemt_user_connections_current{user="hello"} 231
telemt_user_octets_from_client{user="hello"} 1002994896 (956.53 MB)
telemt_user_octets_to_client{user="hello"} 50977296055 (47.48 GB)
telemt_user_msgs_from_client{user="hello"} 1435037
telemt_user_msgs_to_client{user="hello"} 6572340
telemt_user_unique_ips_current{user="hello"} 78
telemt_user_unique_ips_recent_window{user="hello"} 38
```