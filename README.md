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

# Server Metrics 2026-03-10 21:30:54 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 25486.0 (7h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 90126
telemt_connections_bad_total 3272
telemt_handshake_timeouts_total 2171
telemt_upstream_connect_attempt_total 80677
telemt_upstream_connect_success_total 80645
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 80677
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 73583
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7009
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 80641
telemt_user_connections_current{user="hello"} 220
telemt_user_octets_from_client{user="hello"} 2493062534 (2.32 GB)
telemt_user_octets_to_client{user="hello"} 62223088993 (57.95 GB)
telemt_user_msgs_from_client{user="hello"} 2352686
telemt_user_msgs_to_client{user="hello"} 4217225
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 25485.5 (7h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 34247
telemt_connections_bad_total 319
telemt_handshake_timeouts_total 638
telemt_upstream_connect_attempt_total 31234
telemt_upstream_connect_success_total 31225
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 31234
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26373
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4632
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 220
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 31221
telemt_user_connections_current{user="hello"} 42
telemt_user_octets_from_client{user="hello"} 1627356382 (1.52 GB)
telemt_user_octets_to_client{user="hello"} 29631773790 (27.60 GB)
telemt_user_msgs_from_client{user="hello"} 1278959
telemt_user_msgs_to_client{user="hello"} 8019065
telemt_user_unique_ips_current{user="hello"} 19
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 25485.3 (7h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 55308
telemt_connections_bad_total 407
telemt_handshake_timeouts_total 3734
telemt_upstream_connect_attempt_total 48051
telemt_upstream_connect_success_total 48049
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 48051
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 43403
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4600
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 45
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 48045
telemt_user_connections_current{user="hello"} 63
telemt_user_octets_from_client{user="hello"} 743233118 (708.80 MB)
telemt_user_octets_to_client{user="hello"} 43016556693 (40.06 GB)
telemt_user_msgs_from_client{user="hello"} 1013439
telemt_user_msgs_to_client{user="hello"} 6509694
telemt_user_unique_ips_current{user="hello"} 25
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 25484.2 (7h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 49994
telemt_connections_bad_total 73
telemt_handshake_timeouts_total 316
telemt_upstream_connect_attempt_total 47983
telemt_upstream_connect_success_total 47844
telemt_upstream_connect_fail_total 138
telemt_upstream_connect_attempts_per_request{bucket="1"} 47982
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 42122
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5570
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 12
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 140
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 138
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 47840
telemt_user_connections_current{user="hello"} 103
telemt_user_octets_from_client{user="hello"} 793337971 (756.59 MB)
telemt_user_octets_to_client{user="hello"} 36257579527 (33.77 GB)
telemt_user_msgs_from_client{user="hello"} 1059749
telemt_user_msgs_to_client{user="hello"} 6885013
telemt_user_unique_ips_current{user="hello"} 28
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 25485.5 (7h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 72701
telemt_connections_bad_total 6480
telemt_handshake_timeouts_total 1401
telemt_upstream_connect_attempt_total 61883
telemt_upstream_connect_success_total 61639
telemt_upstream_connect_fail_total 244
telemt_upstream_connect_attempts_per_request{bucket="1"} 61883
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 53429
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8011
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 199
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 244
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 61635
telemt_user_connections_current{user="hello"} 187
telemt_user_octets_from_client{user="hello"} 1854569269 (1.73 GB)
telemt_user_octets_to_client{user="hello"} 46149185391 (42.98 GB)
telemt_user_msgs_from_client{user="hello"} 1700975
telemt_user_msgs_to_client{user="hello"} 6485848
telemt_user_unique_ips_current{user="hello"} 48
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 4454.8 (1h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19
telemt_connections_bad_total 19
telemt_upstream_connect_attempt_total 2
telemt_upstream_connect_success_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
```