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

# Server Metrics 2026-03-10 10:18:33 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 125920.9 (34h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 265266
telemt_connections_bad_total 3451
telemt_handshake_timeouts_total 2736
telemt_upstream_connect_attempt_total 248343
telemt_upstream_connect_success_total 248255
telemt_upstream_connect_fail_total 87
telemt_upstream_connect_attempts_per_request{bucket="1"} 248342
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 229257
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18920
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 78
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 87
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 248243
telemt_user_connections_current{user="hello"} 290
telemt_user_octets_from_client{user="hello"} 6140151411 (5.72 GB)
telemt_user_octets_to_client{user="hello"} 149644653524 (139.37 GB)
telemt_user_msgs_from_client{user="hello"} 5991106
telemt_user_msgs_to_client{user="hello"} 9468508
telemt_user_unique_ips_current{user="hello"} 64
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 125919.9 (34h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 79951
telemt_connections_bad_total 3258
telemt_handshake_timeouts_total 1045
telemt_upstream_connect_attempt_total 71544
telemt_upstream_connect_success_total 71501
telemt_upstream_connect_fail_total 43
telemt_upstream_connect_attempts_per_request{bucket="1"} 71544
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 64350
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6749
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 401
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 43
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 71489
telemt_user_connections_current{user="hello"} 54
telemt_user_octets_from_client{user="hello"} 2349259615 (2.19 GB)
telemt_user_octets_to_client{user="hello"} 32963301365 (30.70 GB)
telemt_user_msgs_from_client{user="hello"} 1945220
telemt_user_msgs_to_client{user="hello"} 9440245
telemt_user_unique_ips_current{user="hello"} 17
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 125920.5 (34h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 115013
telemt_connections_bad_total 1158
telemt_handshake_timeouts_total 5699
telemt_upstream_connect_attempt_total 82303
telemt_upstream_connect_success_total 82301
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 82303
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 72835
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9443
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 82289
telemt_user_connections_current{user="hello"} 69
telemt_user_octets_from_client{user="hello"} 6405128190 (5.97 GB)
telemt_user_octets_to_client{user="hello"} 63304815601 (58.96 GB)
telemt_user_msgs_from_client{user="hello"} 4125887
telemt_user_msgs_to_client{user="hello"} 10220502
telemt_user_unique_ips_current{user="hello"} 27
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 125915.3 (34h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 117139
telemt_connections_bad_total 1025
telemt_handshake_timeouts_total 1344
telemt_upstream_connect_attempt_total 109033
telemt_upstream_connect_success_total 108791
telemt_upstream_connect_fail_total 242
telemt_upstream_connect_attempts_per_request{bucket="1"} 109033
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 96348
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12121
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 61
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 261
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 242
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 108779
telemt_user_connections_current{user="hello"} 130
telemt_user_octets_from_client{user="hello"} 2995656841 (2.79 GB)
telemt_user_octets_to_client{user="hello"} 80072855337 (74.57 GB)
telemt_user_msgs_from_client{user="hello"} 2786464
telemt_user_msgs_to_client{user="hello"} 18340833
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 125920.6 (34h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 177845
telemt_connections_bad_total 27593
telemt_handshake_timeouts_total 4456
telemt_upstream_connect_attempt_total 138324
telemt_upstream_connect_success_total 137511
telemt_upstream_connect_fail_total 813
telemt_upstream_connect_attempts_per_request{bucket="1"} 138324
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 118783
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18535
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 193
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 813
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 137497
telemt_user_connections_current{user="hello"} 163
telemt_user_octets_from_client{user="hello"} 2055661479 (1.91 GB)
telemt_user_octets_to_client{user="hello"} 107189243010 (99.83 GB)
telemt_user_msgs_from_client{user="hello"} 2865849
telemt_user_msgs_to_client{user="hello"} 14614347
telemt_user_unique_ips_current{user="hello"} 48
telemt_user_unique_ips_recent_window{user="hello"} 29
```