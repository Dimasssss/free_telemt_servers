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

# Server Metrics 2026-03-10 20:17:26 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 21078.1 (5h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 79458
telemt_connections_bad_total 2925
telemt_handshake_timeouts_total 2082
telemt_upstream_connect_attempt_total 70844
telemt_upstream_connect_success_total 70831
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 70844
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 64617
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6186
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 70829
telemt_user_connections_current{user="hello"} 263
telemt_user_octets_from_client{user="hello"} 2377323225 (2.21 GB)
telemt_user_octets_to_client{user="hello"} 56430574009 (52.56 GB)
telemt_user_msgs_from_client{user="hello"} 2150511
telemt_user_msgs_to_client{user="hello"} 3873805
telemt_user_unique_ips_current{user="hello"} 67
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 21077.2 (5h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 30692
telemt_connections_bad_total 240
telemt_handshake_timeouts_total 473
telemt_upstream_connect_attempt_total 28140
telemt_upstream_connect_success_total 28132
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 28140
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23746
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4170
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 216
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 28130
telemt_user_connections_current{user="hello"} 106
telemt_user_octets_from_client{user="hello"} 1363609150 (1.27 GB)
telemt_user_octets_to_client{user="hello"} 23970019879 (22.32 GB)
telemt_user_msgs_from_client{user="hello"} 1095277
telemt_user_msgs_to_client{user="hello"} 7056865
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 21077.0 (5h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 49276
telemt_connections_bad_total 289
telemt_handshake_timeouts_total 3674
telemt_upstream_connect_attempt_total 42461
telemt_upstream_connect_success_total 42460
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 42461
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 38367
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4048
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 44
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 42456
telemt_user_connections_current{user="hello"} 97
telemt_user_octets_from_client{user="hello"} 660888512 (630.27 MB)
telemt_user_octets_to_client{user="hello"} 39646116279 (36.92 GB)
telemt_user_msgs_from_client{user="hello"} 907930
telemt_user_msgs_to_client{user="hello"} 5954998
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 21075.8 (5h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 43650
telemt_connections_bad_total 68
telemt_handshake_timeouts_total 314
telemt_upstream_connect_attempt_total 41821
telemt_upstream_connect_success_total 41698
telemt_upstream_connect_fail_total 123
telemt_upstream_connect_attempts_per_request{bucket="1"} 41821
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36710
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4850
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 128
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 123
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 41694
telemt_user_connections_current{user="hello"} 103
telemt_user_octets_from_client{user="hello"} 715306133 (682.17 MB)
telemt_user_octets_to_client{user="hello"} 32188787954 (29.98 GB)
telemt_user_msgs_from_client{user="hello"} 913539
telemt_user_msgs_to_client{user="hello"} 6129974
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 21077.1 (5h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 62575
telemt_connections_bad_total 5561
telemt_handshake_timeouts_total 1325
telemt_upstream_connect_attempt_total 53086
telemt_upstream_connect_success_total 52842
telemt_upstream_connect_fail_total 244
telemt_upstream_connect_attempts_per_request{bucket="1"} 53086
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 46216
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6441
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 185
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 244
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 52840
telemt_user_connections_current{user="hello"} 169
telemt_user_octets_from_client{user="hello"} 1586590872 (1.48 GB)
telemt_user_octets_to_client{user="hello"} 41357391181 (38.52 GB)
telemt_user_msgs_from_client{user="hello"} 1474845
telemt_user_msgs_to_client{user="hello"} 5718783
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 14
```