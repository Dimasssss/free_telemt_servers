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

# Server Metrics 2026-03-11 01:40:34 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 40465.8 (11h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 109690
telemt_connections_bad_total 3353
telemt_handshake_timeouts_total 2529
telemt_upstream_connect_attempt_total 98845
telemt_upstream_connect_success_total 98809
telemt_upstream_connect_fail_total 36
telemt_upstream_connect_attempts_per_request{bucket="1"} 98845
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 89890
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8865
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 36
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 98805
telemt_user_connections_current{user="hello"} 154
telemt_user_octets_from_client{user="hello"} 2759678713 (2.57 GB)
telemt_user_octets_to_client{user="hello"} 79121927523 (73.69 GB)
telemt_user_msgs_from_client{user="hello"} 2818021
telemt_user_msgs_to_client{user="hello"} 5435335
telemt_user_unique_ips_current{user="hello"} 51
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 40464.8 (11h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 45050
telemt_connections_bad_total 356
telemt_handshake_timeouts_total 1935
telemt_upstream_connect_attempt_total 40213
telemt_upstream_connect_success_total 40203
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 40212
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34007
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5972
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 224
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 40199
telemt_user_connections_current{user="hello"} 34
telemt_user_octets_from_client{user="hello"} 2024280004 (1.89 GB)
telemt_user_octets_to_client{user="hello"} 38774767835 (36.11 GB)
telemt_user_msgs_from_client{user="hello"} 1620412
telemt_user_msgs_to_client{user="hello"} 9625433
telemt_user_unique_ips_current{user="hello"} 19
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 40464.7 (11h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 66616
telemt_connections_bad_total 621
telemt_handshake_timeouts_total 4130
telemt_upstream_connect_attempt_total 58099
telemt_upstream_connect_success_total 58096
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 58098
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 51871
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6176
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 58092
telemt_user_connections_current{user="hello"} 55
telemt_user_octets_from_client{user="hello"} 10301948275 (9.59 GB)
telemt_user_octets_to_client{user="hello"} 67123412938 (62.51 GB)
telemt_user_msgs_from_client{user="hello"} 4588570
telemt_user_msgs_to_client{user="hello"} 12154638
telemt_user_unique_ips_current{user="hello"} 25
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 40463.7 (11h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 65027
telemt_connections_bad_total 123
telemt_handshake_timeouts_total 533
telemt_upstream_connect_attempt_total 62211
telemt_upstream_connect_success_total 62056
telemt_upstream_connect_fail_total 155
telemt_upstream_connect_attempts_per_request{bucket="1"} 62211
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 54209
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7656
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 26
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 165
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 155
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 62052
telemt_user_connections_current{user="hello"} 66
telemt_user_octets_from_client{user="hello"} 1745524508 (1.63 GB)
telemt_user_octets_to_client{user="hello"} 42504837442 (39.59 GB)
telemt_user_msgs_from_client{user="hello"} 1562620
telemt_user_msgs_to_client{user="hello"} 8304055
telemt_user_unique_ips_current{user="hello"} 27
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 40465.0 (11h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 93890
telemt_connections_bad_total 9447
telemt_handshake_timeouts_total 1497
telemt_upstream_connect_attempt_total 79511
telemt_upstream_connect_success_total 79263
telemt_upstream_connect_fail_total 248
telemt_upstream_connect_attempts_per_request{bucket="1"} 79511
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 68799
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10243
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 221
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 248
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 79259
telemt_user_connections_current{user="hello"} 105
telemt_user_octets_from_client{user="hello"} 2136174259 (1.99 GB)
telemt_user_octets_to_client{user="hello"} 63109105565 (58.77 GB)
telemt_user_msgs_from_client{user="hello"} 2110731
telemt_user_msgs_to_client{user="hello"} 9139491
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 19434.4 (5h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 56
telemt_connections_bad_total 52
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 2
telemt_upstream_connect_success_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
```