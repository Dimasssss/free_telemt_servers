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

# Server Metrics 2026-03-11 10:00:15 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 70446.7 (19h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 207518
telemt_connections_bad_total 3613
telemt_handshake_timeouts_total 4352
telemt_upstream_connect_attempt_total 190065
telemt_upstream_connect_success_total 190005
telemt_upstream_connect_fail_total 60
telemt_upstream_connect_attempts_per_request{bucket="1"} 190065
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 173671
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16277
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 60
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 189997
telemt_user_connections_current{user="hello"} 364
telemt_user_octets_from_client{user="hello"} 4100991920 (3.82 GB)
telemt_user_octets_to_client{user="hello"} 112076677048 (104.38 GB)
telemt_user_msgs_from_client{user="hello"} 4489987
telemt_user_msgs_to_client{user="hello"} 8389123
telemt_user_unique_ips_current{user="hello"} 89
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 70446.0 (19h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 81028
telemt_connections_bad_total 782
telemt_handshake_timeouts_total 3144
telemt_upstream_connect_attempt_total 73338
telemt_upstream_connect_success_total 73322
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 73338
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 63180
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9889
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 253
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 73314
telemt_user_connections_current{user="hello"} 113
telemt_user_octets_from_client{user="hello"} 5002742923 (4.66 GB)
telemt_user_octets_to_client{user="hello"} 55802829310 (51.97 GB)
telemt_user_msgs_from_client{user="hello"} 3184819
telemt_user_msgs_to_client{user="hello"} 14397986
telemt_user_unique_ips_current{user="hello"} 41
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 70446.1 (19h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 112256
telemt_connections_bad_total 1075
telemt_handshake_timeouts_total 5236
telemt_upstream_connect_attempt_total 99575
telemt_upstream_connect_success_total 99571
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 99575
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 88282
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11225
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 63
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 99563
telemt_user_connections_current{user="hello"} 171
telemt_user_octets_from_client{user="hello"} 12016460873 (11.19 GB)
telemt_user_octets_to_client{user="hello"} 81946673396 (76.32 GB)
telemt_user_msgs_from_client{user="hello"} 5696895
telemt_user_msgs_to_client{user="hello"} 15919557
telemt_user_unique_ips_current{user="hello"} 57
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 70444.5 (19h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 123264
telemt_connections_bad_total 251
telemt_handshake_timeouts_total 1137
telemt_upstream_connect_attempt_total 117012
telemt_upstream_connect_success_total 116744
telemt_upstream_connect_fail_total 267
telemt_upstream_connect_attempts_per_request{bucket="1"} 117011
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 100834
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15532
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 60
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 318
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 267
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 116736
telemt_user_connections_current{user="hello"} 151
telemt_user_octets_from_client{user="hello"} 5515416986 (5.14 GB)
telemt_user_octets_to_client{user="hello"} 82660356604 (76.98 GB)
telemt_user_msgs_from_client{user="hello"} 3633247
telemt_user_msgs_to_client{user="hello"} 21424618
telemt_user_unique_ips_current{user="hello"} 51
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 70445.9 (19h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 194703
telemt_connections_bad_total 15342
telemt_handshake_timeouts_total 3369
telemt_upstream_connect_attempt_total 155725
telemt_upstream_connect_success_total 155320
telemt_upstream_connect_fail_total 402
telemt_upstream_connect_attempts_per_request{bucket="1"} 155722
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 133227
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21804
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 289
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 402
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 155312
telemt_user_connections_current{user="hello"} 216
telemt_user_octets_from_client{user="hello"} 3037997622 (2.83 GB)
telemt_user_octets_to_client{user="hello"} 136774208257 (127.38 GB)
telemt_user_msgs_from_client{user="hello"} 3454266
telemt_user_msgs_to_client{user="hello"} 17924554
telemt_user_unique_ips_current{user="hello"} 65
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 49415.2 (13h 43m)
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