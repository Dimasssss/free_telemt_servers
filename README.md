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

# Server Metrics 2026-03-12 01:50:46 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 14741.4 (4h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 28378
telemt_connections_bad_total 1861
telemt_handshake_timeouts_total 169
telemt_upstream_connect_attempt_total 25331
telemt_upstream_connect_success_total 25324
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 25331
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22800
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2511
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 25322
telemt_user_connections_current{user="hello"} 228
telemt_user_octets_from_client{user="hello"} 261891184 (249.76 MB)
telemt_user_octets_to_client{user="hello"} 8847029755 (8.24 GB)
telemt_user_msgs_from_client{user="hello"} 451212
telemt_user_msgs_to_client{user="hello"} 1101079
telemt_user_unique_ips_current{user="hello"} 63
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 14729.5 (4h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11966
telemt_connections_bad_total 47
telemt_handshake_timeouts_total 35
telemt_upstream_connect_attempt_total 11495
telemt_upstream_connect_success_total 11495
telemt_upstream_connect_attempts_per_request{bucket="1"} 11495
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10169
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1321
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11493
telemt_user_connections_current{user="hello"} 84
telemt_user_octets_from_client{user="hello"} 75470972 (71.97 MB)
telemt_user_octets_to_client{user="hello"} 3861431603 (3.60 GB)
telemt_user_msgs_from_client{user="hello"} 186759
telemt_user_msgs_to_client{user="hello"} 1296275
telemt_user_unique_ips_current{user="hello"} 31
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 14702.9 (4h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19968
telemt_connections_bad_total 292
telemt_handshake_timeouts_total 875
telemt_upstream_connect_attempt_total 16891
telemt_upstream_connect_success_total 16891
telemt_upstream_connect_attempts_per_request{bucket="1"} 16891
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14542
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2344
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 16889
telemt_user_connections_current{user="hello"} 87
telemt_user_octets_from_client{user="hello"} 3576856309 (3.33 GB)
telemt_user_octets_to_client{user="hello"} 8928739483 (8.32 GB)
telemt_user_msgs_from_client{user="hello"} 1533535
telemt_user_msgs_to_client{user="hello"} 1857786
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 14728.2 (4h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 22030
telemt_connections_bad_total 7143
telemt_handshake_timeouts_total 693
telemt_upstream_connect_attempt_total 13550
telemt_upstream_connect_success_total 13537
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 13550
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11719
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1779
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 13535
telemt_user_connections_current{user="hello"} 87
telemt_user_octets_from_client{user="hello"} 111713890 (106.54 MB)
telemt_user_octets_to_client{user="hello"} 6479509697 (6.03 GB)
telemt_user_msgs_from_client{user="hello"} 216560
telemt_user_msgs_to_client{user="hello"} 2467023
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## rdp-onedash.ru

Не удалось получить метрики для этого сервера.

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 14729.2 (4h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16081
telemt_connections_bad_total 131
telemt_handshake_timeouts_total 127
telemt_upstream_connect_attempt_total 14635
telemt_upstream_connect_success_total 14635
telemt_upstream_connect_attempts_per_request{bucket="1"} 14635
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12385
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2246
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 14633
telemt_user_connections_current{user="hello"} 70
telemt_user_octets_from_client{user="hello"} 335033087 (319.51 MB)
telemt_user_octets_to_client{user="hello"} 20738299151 (19.31 GB)
telemt_user_msgs_from_client{user="hello"} 458060
telemt_user_msgs_to_client{user="hello"} 2075564
telemt_user_unique_ips_current{user="hello"} 26
telemt_user_unique_ips_recent_window{user="hello"} 4
```