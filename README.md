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

# Server Metrics 2026-03-06 15:40:57 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.4

telemt_uptime_seconds 19140.2 (5h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 45104
telemt_connections_bad_total 3097
telemt_handshake_timeouts_total 173
telemt_upstream_connect_attempt_total 38382
telemt_upstream_connect_success_total 38372
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 38382
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36302
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2062
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 38370
telemt_user_connections_current{user="hello"} 159
telemt_user_octets_from_client{user="hello"} 2095113395 (1.95 GB)
telemt_user_octets_to_client{user="hello"} 24379620919 (22.71 GB)
telemt_user_msgs_from_client{user="hello"} 1381085
telemt_user_msgs_to_client{user="hello"} 3864357
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## psb.hosting

```
telemt 3.3.4

telemt_uptime_seconds 19139.1 (5h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8498
telemt_connections_bad_total 168
telemt_handshake_timeouts_total 94
telemt_upstream_connect_attempt_total 8016
telemt_upstream_connect_success_total 7998
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 8016
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7460
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 455
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 81
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 7996
telemt_user_connections_current{user="hello"} 63
telemt_user_octets_from_client{user="hello"} 90355597 (86.17 MB)
telemt_user_octets_to_client{user="hello"} 4791842453 (4.46 GB)
telemt_user_msgs_from_client{user="hello"} 166498
telemt_user_msgs_to_client{user="hello"} 1500494
telemt_user_unique_ips_current{user="hello"} 9
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## koara.io

```
telemt 3.3.4

telemt_uptime_seconds 19138.5 (5h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7105
telemt_connections_bad_total 75
telemt_handshake_timeouts_total 15
telemt_upstream_connect_attempt_total 6880
telemt_upstream_connect_success_total 6878
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 6880
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6499
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 374
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 6876
telemt_user_connections_current{user="hello"} 17
telemt_user_octets_from_client{user="hello"} 103181957 (98.40 MB)
telemt_user_octets_to_client{user="hello"} 4259905544 (3.97 GB)
telemt_user_msgs_from_client{user="hello"} 152679
telemt_user_msgs_to_client{user="hello"} 1001435
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## landvps.ru

```
telemt 3.3.4

telemt_uptime_seconds 19137.8 (5h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10085
telemt_connections_bad_total 112
telemt_handshake_timeouts_total 50
telemt_upstream_connect_attempt_total 9328
telemt_upstream_connect_success_total 9296
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 9328
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8705
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 551
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 9294
telemt_user_connections_current{user="hello"} 26
telemt_user_octets_from_client{user="hello"} 140366701 (133.86 MB)
telemt_user_octets_to_client{user="hello"} 3162451515 (2.95 GB)
telemt_user_msgs_from_client{user="hello"} 167819
telemt_user_msgs_to_client{user="hello"} 815813
telemt_user_unique_ips_current{user="hello"} 9
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## rdp-onedash.ru

```
telemt 3.3.4

telemt_uptime_seconds 19139.1 (5h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14239
telemt_connections_bad_total 5000
telemt_handshake_timeouts_total 548
telemt_upstream_connect_attempt_total 8467
telemt_upstream_connect_success_total 8467
telemt_upstream_connect_attempts_per_request{bucket="1"} 8467
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7355
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1105
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 8465
telemt_user_connections_current{user="hello"} 48
telemt_user_octets_from_client{user="hello"} 221743597 (211.47 MB)
telemt_user_octets_to_client{user="hello"} 20660021169 (19.24 GB)
telemt_user_msgs_from_client{user="hello"} 362640
telemt_user_msgs_to_client{user="hello"} 3701729
telemt_user_unique_ips_current{user="hello"} 12
telemt_user_unique_ips_recent_window{user="hello"} 7
```