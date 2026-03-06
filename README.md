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

# Server Metrics 2026-03-06 06:06:07 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.2

telemt_uptime_seconds 28246.1 (7h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 80544
telemt_connections_bad_total 51940
telemt_handshake_timeouts_total 2466
telemt_upstream_connect_attempt_total 24555
telemt_upstream_connect_success_total 24552
telemt_upstream_connect_attempts_per_request{bucket="1"} 24549
telemt_upstream_connect_attempts_per_request{bucket="2"} 3
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23044
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1501
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 24548
telemt_user_connections_current{user="hello"} 100
telemt_user_octets_from_client{user="hello"} 359722906 (343.06 MB)
telemt_user_octets_to_client{user="hello"} 21371575655 (19.90 GB)
telemt_user_msgs_from_client{user="hello"} 618390
telemt_user_msgs_to_client{user="hello"} 3224624
telemt_user_unique_ips_current{user="hello"} 25
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## psb.hosting

```
telemt 3.3.2

telemt_uptime_seconds 28243.8 (7h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3265
telemt_connections_bad_total 147
telemt_handshake_timeouts_total 19
telemt_upstream_connect_attempt_total 3057
telemt_upstream_connect_success_total 3056
telemt_upstream_connect_attempts_per_request{bucket="1"} 3055
telemt_upstream_connect_attempts_per_request{bucket="2"} 1
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2935
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 115
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3052
telemt_user_connections_current{user="hello"} 26
telemt_user_octets_from_client{user="hello"} 61265142 (58.43 MB)
telemt_user_octets_to_client{user="hello"} 1317826702 (1.23 GB)
telemt_user_msgs_from_client{user="hello"} 88702
telemt_user_msgs_to_client{user="hello"} 421957
telemt_user_unique_ips_current{user="hello"} 6
```

## koara.io

```
telemt 3.3.2

telemt_uptime_seconds 28244.3 (7h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2424
telemt_connections_bad_total 218
telemt_handshake_timeouts_total 8
telemt_upstream_connect_attempt_total 2179
telemt_upstream_connect_success_total 2179
telemt_upstream_connect_attempts_per_request{bucket="1"} 2179
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1976
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 203
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2175
telemt_user_connections_current{user="hello"} 18
telemt_user_octets_from_client{user="hello"} 53731481 (51.24 MB)
telemt_user_octets_to_client{user="hello"} 2594599660 (2.42 GB)
telemt_user_msgs_from_client{user="hello"} 79399
telemt_user_msgs_to_client{user="hello"} 548178
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## landvps.ru

```
telemt 3.3.2

telemt_uptime_seconds 28246.9 (7h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4454
telemt_connections_bad_total 140
telemt_handshake_timeouts_total 310
telemt_upstream_connect_attempt_total 3793
telemt_upstream_connect_success_total 3793
telemt_upstream_connect_attempts_per_request{bucket="1"} 3793
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3328
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 441
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3789
telemt_user_connections_current{user="hello"} 19
telemt_user_octets_from_client{user="hello"} 100526772 (95.87 MB)
telemt_user_octets_to_client{user="hello"} 5997978140 (5.59 GB)
telemt_user_msgs_from_client{user="hello"} 147250
telemt_user_msgs_to_client{user="hello"} 1289658
telemt_user_unique_ips_current{user="hello"} 3
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## rdp-onedash.ru

```
telemt 3.3.2

telemt_uptime_seconds 28246.8 (7h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9513
telemt_connections_bad_total 5129
telemt_handshake_timeouts_total 163
telemt_upstream_connect_attempt_total 4111
telemt_upstream_connect_success_total 4111
telemt_upstream_connect_attempts_per_request{bucket="1"} 4111
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3536
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 570
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4107
telemt_user_connections_current{user="hello"} 2
telemt_user_octets_from_client{user="hello"} 80153121 (76.44 MB)
telemt_user_octets_to_client{user="hello"} 16008644979 (14.91 GB)
telemt_user_msgs_from_client{user="hello"} 204024
telemt_user_msgs_to_client{user="hello"} 3054186
telemt_user_unique_ips_current{user="hello"} 2
telemt_user_unique_ips_recent_window{user="hello"} 1
```