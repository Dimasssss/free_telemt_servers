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

# Server Metrics 2026-03-12 00:29:43 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 9878.8 (2h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 18985
telemt_connections_bad_total 1804
telemt_handshake_timeouts_total 129
telemt_upstream_connect_attempt_total 16485
telemt_upstream_connect_success_total 16480
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 16485
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14758
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1718
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 16478
telemt_user_connections_current{user="hello"} 171
telemt_user_octets_from_client{user="hello"} 194927216 (185.90 MB)
telemt_user_octets_to_client{user="hello"} 6625360496 (6.17 GB)
telemt_user_msgs_from_client{user="hello"} 337017
telemt_user_msgs_to_client{user="hello"} 876854
telemt_user_unique_ips_current{user="hello"} 62
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 9867.0 (2h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7617
telemt_connections_bad_total 38
telemt_handshake_timeouts_total 22
telemt_upstream_connect_attempt_total 7302
telemt_upstream_connect_success_total 7302
telemt_upstream_connect_attempts_per_request{bucket="1"} 7302
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6352
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 950
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 7300
telemt_user_connections_current{user="hello"} 102
telemt_user_octets_from_client{user="hello"} 46821066 (44.65 MB)
telemt_user_octets_to_client{user="hello"} 2241601210 (2.09 GB)
telemt_user_msgs_from_client{user="hello"} 116133
telemt_user_msgs_to_client{user="hello"} 762821
telemt_user_unique_ips_current{user="hello"} 29
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 9841.8 (2h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12848
telemt_connections_bad_total 276
telemt_handshake_timeouts_total 781
telemt_upstream_connect_attempt_total 10342
telemt_upstream_connect_success_total 10342
telemt_upstream_connect_attempts_per_request{bucket="1"} 10342
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8863
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1479
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 10340
telemt_user_connections_current{user="hello"} 80
telemt_user_octets_from_client{user="hello"} 64770991 (61.77 MB)
telemt_user_octets_to_client{user="hello"} 6016730905 (5.60 GB)
telemt_user_msgs_from_client{user="hello"} 203834
telemt_user_msgs_to_client{user="hello"} 1397790
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 9865.9 (2h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11777
telemt_connections_bad_total 2211
telemt_handshake_timeouts_total 251
telemt_upstream_connect_attempt_total 8953
telemt_upstream_connect_success_total 8942
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 8953
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7836
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1074
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 8940
telemt_user_connections_current{user="hello"} 73
telemt_user_octets_from_client{user="hello"} 66337073 (63.26 MB)
telemt_user_octets_to_client{user="hello"} 3952173593 (3.68 GB)
telemt_user_msgs_from_client{user="hello"} 139548
telemt_user_msgs_to_client{user="hello"} 1426030
telemt_user_unique_ips_current{user="hello"} 27
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## rdp-onedash.ru

Не удалось получить метрики для этого сервера.

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 9866.7 (2h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9716
telemt_connections_bad_total 79
telemt_handshake_timeouts_total 113
telemt_upstream_connect_attempt_total 8607
telemt_upstream_connect_success_total 8607
telemt_upstream_connect_attempts_per_request{bucket="1"} 8607
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7200
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1405
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 8605
telemt_user_connections_current{user="hello"} 50
telemt_user_octets_from_client{user="hello"} 122111428 (116.45 MB)
telemt_user_octets_to_client{user="hello"} 16866396881 (15.71 GB)
telemt_user_msgs_from_client{user="hello"} 255299
telemt_user_msgs_to_client{user="hello"} 1512848
telemt_user_unique_ips_current{user="hello"} 17
telemt_user_unique_ips_recent_window{user="hello"} 10
```