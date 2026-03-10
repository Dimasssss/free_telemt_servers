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

# Server Metrics 2026-03-10 15:35:53 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 4185.1 (1h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20901
telemt_connections_bad_total 291
telemt_handshake_timeouts_total 1060
telemt_upstream_connect_attempt_total 18222
telemt_upstream_connect_success_total 18218
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 18222
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16806
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1410
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 18216
telemt_user_connections_current{user="hello"} 340
telemt_user_octets_from_client{user="hello"} 297554309 (283.77 MB)
telemt_user_octets_to_client{user="hello"} 10212829201 (9.51 GB)
telemt_user_msgs_from_client{user="hello"} 396508
telemt_user_msgs_to_client{user="hello"} 727006
telemt_user_unique_ips_current{user="hello"} 69
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 4184.5 (1h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6087
telemt_connections_bad_total 49
telemt_handshake_timeouts_total 173
telemt_upstream_connect_attempt_total 5538
telemt_upstream_connect_success_total 5538
telemt_upstream_connect_attempts_per_request{bucket="1"} 5538
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4837
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 688
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 5536
telemt_user_connections_current{user="hello"} 91
telemt_user_octets_from_client{user="hello"} 104190036 (99.36 MB)
telemt_user_octets_to_client{user="hello"} 4422515351 (4.12 GB)
telemt_user_msgs_from_client{user="hello"} 152137
telemt_user_msgs_to_client{user="hello"} 1313890
telemt_user_unique_ips_current{user="hello"} 27
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 4184.2 (1h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9797
telemt_connections_bad_total 6
telemt_handshake_timeouts_total 348
telemt_upstream_connect_attempt_total 9013
telemt_upstream_connect_success_total 9013
telemt_upstream_connect_attempts_per_request{bucket="1"} 9013
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7974
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1038
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 9011
telemt_user_connections_current{user="hello"} 99
telemt_user_octets_from_client{user="hello"} 66139416 (63.08 MB)
telemt_user_octets_to_client{user="hello"} 3022588514 (2.82 GB)
telemt_user_msgs_from_client{user="hello"} 144883
telemt_user_msgs_to_client{user="hello"} 802607
telemt_user_unique_ips_current{user="hello"} 44
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 4183.3 (1h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9499
telemt_connections_bad_total 9
telemt_handshake_timeouts_total 126
telemt_upstream_connect_attempt_total 9079
telemt_upstream_connect_success_total 9056
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 9079
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7916
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1110
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 9054
telemt_user_connections_current{user="hello"} 148
telemt_user_octets_from_client{user="hello"} 161154475 (153.69 MB)
telemt_user_octets_to_client{user="hello"} 8835522118 (8.23 GB)
telemt_user_msgs_from_client{user="hello"} 194559
telemt_user_msgs_to_client{user="hello"} 1338387
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 4184.5 (1h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13611
telemt_connections_bad_total 995
telemt_handshake_timeouts_total 227
telemt_upstream_connect_attempt_total 11824
telemt_upstream_connect_success_total 11822
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 11824
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10597
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1214
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11820
telemt_user_connections_current{user="hello"} 194
telemt_user_octets_from_client{user="hello"} 1034396313 (986.48 MB)
telemt_user_octets_to_client{user="hello"} 8914658368 (8.30 GB)
telemt_user_msgs_from_client{user="hello"} 538876
telemt_user_msgs_to_client{user="hello"} 936742
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 20
```