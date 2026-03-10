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

# Server Metrics 2026-03-10 17:54:16 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 12488.1 (3h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 50558
telemt_connections_bad_total 882
telemt_handshake_timeouts_total 1422
telemt_upstream_connect_attempt_total 45610
telemt_upstream_connect_success_total 45600
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 45610
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 41728
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3865
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 45598
telemt_user_connections_current{user="hello"} 306
telemt_user_octets_from_client{user="hello"} 1394407752 (1.30 GB)
telemt_user_octets_to_client{user="hello"} 34390263753 (32.03 GB)
telemt_user_msgs_from_client{user="hello"} 1293631
telemt_user_msgs_to_client{user="hello"} 2569053
telemt_user_unique_ips_current{user="hello"} 85
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 12487.5 (3h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 18301
telemt_connections_bad_total 143
telemt_handshake_timeouts_total 332
telemt_upstream_connect_attempt_total 16703
telemt_upstream_connect_success_total 16698
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 16701
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14243
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2374
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 81
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 16696
telemt_user_connections_current{user="hello"} 111
telemt_user_octets_from_client{user="hello"} 525519002 (501.17 MB)
telemt_user_octets_to_client{user="hello"} 8807011665 (8.20 GB)
telemt_user_msgs_from_client{user="hello"} 496839
telemt_user_msgs_to_client{user="hello"} 2751319
telemt_user_unique_ips_current{user="hello"} 26
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 12487.1 (3h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 28103
telemt_connections_bad_total 12
telemt_handshake_timeouts_total 2531
telemt_upstream_connect_attempt_total 23848
telemt_upstream_connect_success_total 23848
telemt_upstream_connect_attempts_per_request{bucket="1"} 23848
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21330
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2491
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 23846
telemt_user_connections_current{user="hello"} 78
telemt_user_octets_from_client{user="hello"} 289094120 (275.70 MB)
telemt_user_octets_to_client{user="hello"} 17660445715 (16.45 GB)
telemt_user_msgs_from_client{user="hello"} 486742
telemt_user_msgs_to_client{user="hello"} 3073214
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 12486.1 (3h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 27891
telemt_connections_bad_total 20
telemt_handshake_timeouts_total 259
telemt_upstream_connect_attempt_total 26640
telemt_upstream_connect_success_total 26566
telemt_upstream_connect_fail_total 74
telemt_upstream_connect_attempts_per_request{bucket="1"} 26640
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23364
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3119
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 79
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 74
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 26564
telemt_user_connections_current{user="hello"} 135
telemt_user_octets_from_client{user="hello"} 376682154 (359.23 MB)
telemt_user_octets_to_client{user="hello"} 25680491611 (23.92 GB)
telemt_user_msgs_from_client{user="hello"} 548725
telemt_user_msgs_to_client{user="hello"} 4429944
telemt_user_unique_ips_current{user="hello"} 41
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 12487.4 (3h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 38312
telemt_connections_bad_total 2887
telemt_handshake_timeouts_total 664
telemt_upstream_connect_attempt_total 33253
telemt_upstream_connect_success_total 33016
telemt_upstream_connect_fail_total 237
telemt_upstream_connect_attempts_per_request{bucket="1"} 33253
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28974
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3950
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 92
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 237
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 33014
telemt_user_connections_current{user="hello"} 230
telemt_user_octets_from_client{user="hello"} 1327527616 (1.24 GB)
telemt_user_octets_to_client{user="hello"} 21052186413 (19.61 GB)
telemt_user_msgs_from_client{user="hello"} 989944
telemt_user_msgs_to_client{user="hello"} 3053083
telemt_user_unique_ips_current{user="hello"} 63
telemt_user_unique_ips_recent_window{user="hello"} 24
```