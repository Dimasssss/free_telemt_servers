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

# Server Metrics 2026-03-10 22:47:26 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 30078.4 (8h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 96016
telemt_connections_bad_total 3305
telemt_handshake_timeouts_total 2209
telemt_upstream_connect_attempt_total 86243
telemt_upstream_connect_success_total 86211
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 86243
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 78555
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7603
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 86207
telemt_user_connections_current{user="hello"} 175
telemt_user_octets_from_client{user="hello"} 2569357284 (2.39 GB)
telemt_user_octets_to_client{user="hello"} 69704769803 (64.92 GB)
telemt_user_msgs_from_client{user="hello"} 2510005
telemt_user_msgs_to_client{user="hello"} 4670703
telemt_user_unique_ips_current{user="hello"} 53
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 30077.5 (8h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 36744
telemt_connections_bad_total 331
telemt_handshake_timeouts_total 768
telemt_upstream_connect_attempt_total 33443
telemt_upstream_connect_success_total 33434
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 33443
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28276
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4938
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 220
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 33430
telemt_user_connections_current{user="hello"} 40
telemt_user_octets_from_client{user="hello"} 1683445818 (1.57 GB)
telemt_user_octets_to_client{user="hello"} 35062558732 (32.65 GB)
telemt_user_msgs_from_client{user="hello"} 1372406
telemt_user_msgs_to_client{user="hello"} 8812461
telemt_user_unique_ips_current{user="hello"} 17
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 30077.2 (8h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 59329
telemt_connections_bad_total 446
telemt_handshake_timeouts_total 4061
telemt_upstream_connect_attempt_total 51383
telemt_upstream_connect_success_total 51381
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 51383
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 46322
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5011
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 47
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 51377
telemt_user_connections_current{user="hello"} 49
telemt_user_octets_from_client{user="hello"} 776337573 (740.37 MB)
telemt_user_octets_to_client{user="hello"} 48816912446 (45.46 GB)
telemt_user_msgs_from_client{user="hello"} 1091136
telemt_user_msgs_to_client{user="hello"} 7290387
telemt_user_unique_ips_current{user="hello"} 21
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 30076.1 (8h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 54698
telemt_connections_bad_total 87
telemt_handshake_timeouts_total 329
telemt_upstream_connect_attempt_total 52508
telemt_upstream_connect_success_total 52358
telemt_upstream_connect_fail_total 150
telemt_upstream_connect_attempts_per_request{bucket="1"} 52508
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 45990
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6200
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 17
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 151
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 150
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 52354
telemt_user_connections_current{user="hello"} 79
telemt_user_octets_from_client{user="hello"} 825947256 (787.68 MB)
telemt_user_octets_to_client{user="hello"} 37344334722 (34.78 GB)
telemt_user_msgs_from_client{user="hello"} 1124382
telemt_user_msgs_to_client{user="hello"} 7139597
telemt_user_unique_ips_current{user="hello"} 24
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 30077.5 (8h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 80287
telemt_connections_bad_total 7407
telemt_handshake_timeouts_total 1458
telemt_upstream_connect_attempt_total 68315
telemt_upstream_connect_success_total 68067
telemt_upstream_connect_fail_total 248
telemt_upstream_connect_attempts_per_request{bucket="1"} 68315
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 58877
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8978
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 212
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 248
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 68063
telemt_user_connections_current{user="hello"} 127
telemt_user_octets_from_client{user="hello"} 2060620709 (1.92 GB)
telemt_user_octets_to_client{user="hello"} 55045061477 (51.26 GB)
telemt_user_msgs_from_client{user="hello"} 1923382
telemt_user_msgs_to_client{user="hello"} 8061062
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 9046.8 (2h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 40
telemt_connections_bad_total 38
telemt_handshake_timeouts_total 1
telemt_upstream_connect_attempt_total 2
telemt_upstream_connect_success_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
```