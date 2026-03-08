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

# Server Metrics 2026-03-08 16:53:28 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 35086.1 (9h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 84415
telemt_connections_bad_total 5042
telemt_handshake_timeouts_total 1099
telemt_upstream_connect_attempt_total 75427
telemt_upstream_connect_success_total 75402
telemt_upstream_connect_fail_total 25
telemt_upstream_connect_attempts_per_request{bucket="1"} 75427
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 70835
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4529
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 25
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 75396
telemt_user_connections_current{user="hello"} 218
telemt_user_octets_from_client{user="hello"} 1915304044 (1.78 GB)
telemt_user_octets_to_client{user="hello"} 43042613688 (40.09 GB)
telemt_user_msgs_from_client{user="hello"} 1796686
telemt_user_msgs_to_client{user="hello"} 2497749
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 35084.9 (9h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 18196
telemt_connections_bad_total 144
telemt_handshake_timeouts_total 123
telemt_upstream_connect_attempt_total 17605
telemt_upstream_connect_success_total 17602
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 17605
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16274
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1228
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 100
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 17598
telemt_user_connections_current{user="hello"} 71
telemt_user_octets_from_client{user="hello"} 644251544 (614.41 MB)
telemt_user_octets_to_client{user="hello"} 17910418658 (16.68 GB)
telemt_user_msgs_from_client{user="hello"} 702901
telemt_user_msgs_to_client{user="hello"} 4872137
telemt_user_unique_ips_current{user="hello"} 15
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 35084.7 (9h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11108
telemt_connections_bad_total 151
telemt_handshake_timeouts_total 36
telemt_upstream_connect_attempt_total 10472
telemt_upstream_connect_success_total 10396
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 10472
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9589
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 735
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 72
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 10392
telemt_user_connections_current{user="hello"} 21
telemt_user_octets_from_client{user="hello"} 225131442 (214.70 MB)
telemt_user_octets_to_client{user="hello"} 3729547034 (3.47 GB)
telemt_user_msgs_from_client{user="hello"} 181355
telemt_user_msgs_to_client{user="hello"} 652359
telemt_user_unique_ips_current{user="hello"} 9
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 35084.6 (9h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14999
telemt_connections_bad_total 168
telemt_handshake_timeouts_total 56
telemt_upstream_connect_attempt_total 14297
telemt_upstream_connect_success_total 14266
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 14297
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13165
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1030
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 65
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 14262
telemt_user_connections_current{user="hello"} 33
telemt_user_octets_from_client{user="hello"} 1004784007 (958.24 MB)
telemt_user_octets_to_client{user="hello"} 5137861932 (4.79 GB)
telemt_user_msgs_from_client{user="hello"} 504615
telemt_user_msgs_to_client{user="hello"} 1160064
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 35084.9 (9h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19932
telemt_connections_bad_total 6476
telemt_handshake_timeouts_total 189
telemt_upstream_connect_attempt_total 12966
telemt_upstream_connect_success_total 12962
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 12966
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10881
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2069
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 12958
telemt_user_connections_current{user="hello"} 16
telemt_user_octets_from_client{user="hello"} 253502920 (241.76 MB)
telemt_user_octets_to_client{user="hello"} 11000286821 (10.24 GB)
telemt_user_msgs_from_client{user="hello"} 327307
telemt_user_msgs_to_client{user="hello"} 1431615
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 3
```