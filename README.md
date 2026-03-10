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

# Server Metrics 2026-03-10 15:15:25 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 2957.0 (0h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14606
telemt_connections_bad_total 202
telemt_handshake_timeouts_total 49
telemt_upstream_connect_attempt_total 13689
telemt_upstream_connect_success_total 13686
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 13689
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12618
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1066
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 13684
telemt_user_connections_current{user="hello"} 324
telemt_user_octets_from_client{user="hello"} 197941583 (188.77 MB)
telemt_user_octets_to_client{user="hello"} 7643971014 (7.12 GB)
telemt_user_msgs_from_client{user="hello"} 280341
telemt_user_msgs_to_client{user="hello"} 488652
telemt_user_unique_ips_current{user="hello"} 73
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 2956.2 (0h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4276
telemt_connections_bad_total 44
telemt_handshake_timeouts_total 76
telemt_upstream_connect_attempt_total 3958
telemt_upstream_connect_success_total 3958
telemt_upstream_connect_attempts_per_request{bucket="1"} 3958
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3457
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 492
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3956
telemt_user_connections_current{user="hello"} 87
telemt_user_octets_from_client{user="hello"} 80013746 (76.31 MB)
telemt_user_octets_to_client{user="hello"} 3858122632 (3.59 GB)
telemt_user_msgs_from_client{user="hello"} 114711
telemt_user_msgs_to_client{user="hello"} 1131563
telemt_user_unique_ips_current{user="hello"} 26
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 2956.1 (0h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7100
telemt_connections_bad_total 4
telemt_handshake_timeouts_total 226
telemt_upstream_connect_attempt_total 6580
telemt_upstream_connect_success_total 6580
telemt_upstream_connect_attempts_per_request{bucket="1"} 6580
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5873
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 707
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 6578
telemt_user_connections_current{user="hello"} 93
telemt_user_octets_from_client{user="hello"} 47741158 (45.53 MB)
telemt_user_octets_to_client{user="hello"} 1030214035 (982.49 MB)
telemt_user_msgs_from_client{user="hello"} 94086
telemt_user_msgs_to_client{user="hello"} 280713
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 2955.0 (0h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6741
telemt_connections_bad_total 4
telemt_handshake_timeouts_total 116
telemt_upstream_connect_attempt_total 6406
telemt_upstream_connect_success_total 6390
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 6406
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5579
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 791
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 6388
telemt_user_connections_current{user="hello"} 185
telemt_user_octets_from_client{user="hello"} 109672267 (104.59 MB)
telemt_user_octets_to_client{user="hello"} 5070659086 (4.72 GB)
telemt_user_msgs_from_client{user="hello"} 127823
telemt_user_msgs_to_client{user="hello"} 848528
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 2956.2 (0h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9542
telemt_connections_bad_total 775
telemt_handshake_timeouts_total 198
telemt_upstream_connect_attempt_total 8200
telemt_upstream_connect_success_total 8198
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 8200
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7291
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 896
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 8196
telemt_user_connections_current{user="hello"} 244
telemt_user_octets_from_client{user="hello"} 466992639 (445.36 MB)
telemt_user_octets_to_client{user="hello"} 4614458676 (4.30 GB)
telemt_user_msgs_from_client{user="hello"} 282210
telemt_user_msgs_to_client{user="hello"} 545467
telemt_user_unique_ips_current{user="hello"} 62
telemt_user_unique_ips_recent_window{user="hello"} 25
```