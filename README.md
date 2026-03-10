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

# Server Metrics 2026-03-10 21:00:18 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 23649.6 (6h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 86508
telemt_connections_bad_total 3270
telemt_handshake_timeouts_total 2147
telemt_upstream_connect_attempt_total 77186
telemt_upstream_connect_success_total 77155
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 77186
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 70397
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6708
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 77151
telemt_user_connections_current{user="hello"} 220
telemt_user_octets_from_client{user="hello"} 2455060175 (2.29 GB)
telemt_user_octets_to_client{user="hello"} 59424513772 (55.34 GB)
telemt_user_msgs_from_client{user="hello"} 2271130
telemt_user_msgs_to_client{user="hello"} 4069160
telemt_user_unique_ips_current{user="hello"} 63
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 23649.1 (6h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 33144
telemt_connections_bad_total 313
telemt_handshake_timeouts_total 591
telemt_upstream_connect_attempt_total 30233
telemt_upstream_connect_success_total 30225
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 30233
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25508
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4498
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 219
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 30221
telemt_user_connections_current{user="hello"} 68
telemt_user_octets_from_client{user="hello"} 1547254631 (1.44 GB)
telemt_user_octets_to_client{user="hello"} 25967215217 (24.18 GB)
telemt_user_msgs_from_client{user="hello"} 1202228
telemt_user_msgs_to_client{user="hello"} 7466543
telemt_user_unique_ips_current{user="hello"} 21
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 23648.9 (6h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 52997
telemt_connections_bad_total 296
telemt_handshake_timeouts_total 3711
telemt_upstream_connect_attempt_total 45954
telemt_upstream_connect_success_total 45953
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 45954
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 41552
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4355
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 45
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 45949
telemt_user_connections_current{user="hello"} 90
telemt_user_octets_from_client{user="hello"} 727846544 (694.13 MB)
telemt_user_octets_to_client{user="hello"} 42156313897 (39.26 GB)
telemt_user_msgs_from_client{user="hello"} 984256
telemt_user_msgs_to_client{user="hello"} 6328875
telemt_user_unique_ips_current{user="hello"} 30
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 23647.9 (6h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 47285
telemt_connections_bad_total 72
telemt_handshake_timeouts_total 315
telemt_upstream_connect_attempt_total 45395
telemt_upstream_connect_success_total 45263
telemt_upstream_connect_fail_total 132
telemt_upstream_connect_attempts_per_request{bucket="1"} 45395
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 39834
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5283
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 135
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 132
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 45259
telemt_user_connections_current{user="hello"} 103
telemt_user_octets_from_client{user="hello"} 763562858 (728.19 MB)
telemt_user_octets_to_client{user="hello"} 34330364928 (31.97 GB)
telemt_user_msgs_from_client{user="hello"} 1002693
telemt_user_msgs_to_client{user="hello"} 6555133
telemt_user_unique_ips_current{user="hello"} 33
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 23649.2 (6h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 66967
telemt_connections_bad_total 6121
telemt_handshake_timeouts_total 1386
telemt_upstream_connect_attempt_total 56688
telemt_upstream_connect_success_total 56444
telemt_upstream_connect_fail_total 244
telemt_upstream_connect_attempts_per_request{bucket="1"} 56688
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 49327
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6927
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 190
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 244
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 56440
telemt_user_connections_current{user="hello"} 173
telemt_user_octets_from_client{user="hello"} 1828923590 (1.70 GB)
telemt_user_octets_to_client{user="hello"} 44906588296 (41.82 GB)
telemt_user_msgs_from_client{user="hello"} 1641666
telemt_user_msgs_to_client{user="hello"} 6167508
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 2618.6 (0h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16
telemt_connections_bad_total 16
telemt_upstream_connect_attempt_total 2
telemt_upstream_connect_success_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
```