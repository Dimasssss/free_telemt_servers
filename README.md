# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt  
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

-----

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

# Server Metrics 2026-03-07 08:16:52 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.7

telemt_uptime_seconds 4137.6 (1h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5619
telemt_connections_bad_total 23
telemt_handshake_timeouts_total 19
telemt_upstream_connect_attempt_total 5408
telemt_upstream_connect_success_total 5408
telemt_upstream_connect_attempts_per_request{bucket="1"} 5408
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5098
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 306
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 5406
telemt_user_connections_current{user="hello"} 144
telemt_user_octets_from_client{user="hello"} 216399932 (206.38 MB)
telemt_user_octets_to_client{user="hello"} 5731032493 (5.34 GB)
telemt_user_msgs_from_client{user="hello"} 190893
telemt_user_msgs_to_client{user="hello"} 1018624
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## psb.hosting

```
telemt 3.3.7

telemt_uptime_seconds 4137.3 (1h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1611
telemt_connections_bad_total 19
telemt_handshake_timeouts_total 6
telemt_upstream_connect_attempt_total 1522
telemt_upstream_connect_success_total 1521
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 1522
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1405
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 116
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1519
telemt_user_connections_current{user="hello"} 21
telemt_user_octets_from_client{user="hello"} 71941077 (68.61 MB)
telemt_user_octets_to_client{user="hello"} 771962374 (736.20 MB)
telemt_user_msgs_from_client{user="hello"} 48296
telemt_user_msgs_to_client{user="hello"} 219860
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## koara.io

```
telemt 3.3.7

telemt_uptime_seconds 4136.8 (1h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1239
telemt_connections_bad_total 7
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 1209
telemt_upstream_connect_success_total 1209
telemt_upstream_connect_attempts_per_request{bucket="1"} 1209
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1100
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 107
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1207
telemt_user_connections_current{user="hello"} 8
telemt_user_octets_from_client{user="hello"} 31358374 (29.91 MB)
telemt_user_octets_to_client{user="hello"} 345016036 (329.03 MB)
telemt_user_msgs_from_client{user="hello"} 23879
telemt_user_msgs_to_client{user="hello"} 87950
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## landvps.ru

```
telemt 3.3.7

telemt_uptime_seconds 4136.7 (1h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1402
telemt_connections_bad_total 7
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 1359
telemt_upstream_connect_success_total 1356
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 1359
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1297
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 53
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1354
telemt_user_connections_current{user="hello"} 26
telemt_user_octets_from_client{user="hello"} 9885861 (9.43 MB)
telemt_user_octets_to_client{user="hello"} 461321782 (439.95 MB)
telemt_user_msgs_from_client{user="hello"} 21534
telemt_user_msgs_to_client{user="hello"} 121352
telemt_user_unique_ips_current{user="hello"} 4
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## rdp-onedash.ru

```
telemt 3.3.7

telemt_uptime_seconds 4137.2 (1h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3177
telemt_connections_bad_total 786
telemt_handshake_timeouts_total 249
telemt_upstream_connect_attempt_total 2050
telemt_upstream_connect_success_total 2049
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 2050
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1691
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 355
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2047
telemt_user_connections_current{user="hello"} 10
telemt_user_octets_from_client{user="hello"} 41738186 (39.80 MB)
telemt_user_octets_to_client{user="hello"} 9538795869 (8.88 GB)
telemt_user_msgs_from_client{user="hello"} 62270
telemt_user_msgs_to_client{user="hello"} 1679496
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 2
```