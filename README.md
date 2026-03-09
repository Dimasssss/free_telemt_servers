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

# Server Metrics 2026-03-09 16:49:28 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 62977.6 (17h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 116391
telemt_connections_bad_total 1656
telemt_handshake_timeouts_total 982
telemt_upstream_connect_attempt_total 109014
telemt_upstream_connect_success_total 108974
telemt_upstream_connect_fail_total 40
telemt_upstream_connect_attempts_per_request{bucket="1"} 109014
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 100674
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8241
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 40
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 108968
telemt_user_connections_current{user="hello"} 206
telemt_user_octets_from_client{user="hello"} 2946168367 (2.74 GB)
telemt_user_octets_to_client{user="hello"} 57505526819 (53.56 GB)
telemt_user_msgs_from_client{user="hello"} 2719906
telemt_user_msgs_to_client{user="hello"} 3812706
telemt_user_unique_ips_current{user="hello"} 50
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 62976.3 (17h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 31117
telemt_connections_bad_total 222
telemt_handshake_timeouts_total 355
telemt_upstream_connect_attempt_total 29364
telemt_upstream_connect_success_total 29346
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 29364
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26574
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2536
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 236
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 29340
telemt_user_connections_current{user="hello"} 61
telemt_user_octets_from_client{user="hello"} 1003368113 (956.89 MB)
telemt_user_octets_to_client{user="hello"} 15831432317 (14.74 GB)
telemt_user_msgs_from_client{user="hello"} 850820
telemt_user_msgs_to_client{user="hello"} 4382867
telemt_user_unique_ips_current{user="hello"} 15
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 62976.9 (17h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 39455
telemt_connections_bad_total 656
telemt_handshake_timeouts_total 1753
telemt_upstream_connect_attempt_total 30035
telemt_upstream_connect_success_total 30035
telemt_upstream_connect_attempts_per_request{bucket="1"} 30035
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26764
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3266
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 30029
telemt_user_connections_current{user="hello"} 97
telemt_user_octets_from_client{user="hello"} 4464011177 (4.16 GB)
telemt_user_octets_to_client{user="hello"} 18538762136 (17.27 GB)
telemt_user_msgs_from_client{user="hello"} 1989493
telemt_user_msgs_to_client{user="hello"} 2465306
telemt_user_unique_ips_current{user="hello"} 30
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 62971.5 (17h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 45161
telemt_connections_bad_total 198
telemt_handshake_timeouts_total 878
telemt_upstream_connect_attempt_total 41301
telemt_upstream_connect_success_total 41201
telemt_upstream_connect_fail_total 100
telemt_upstream_connect_attempts_per_request{bucket="1"} 41301
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35280
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5800
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 21
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 100
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 100
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 41193
telemt_user_connections_current{user="hello"} 87
telemt_user_octets_from_client{user="hello"} 1954582351 (1.82 GB)
telemt_user_octets_to_client{user="hello"} 31226677321 (29.08 GB)
telemt_user_msgs_from_client{user="hello"} 1285939
telemt_user_msgs_to_client{user="hello"} 7895084
telemt_user_unique_ips_current{user="hello"} 28
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 62977.1 (17h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 73775
telemt_connections_bad_total 15253
telemt_handshake_timeouts_total 1676
telemt_upstream_connect_attempt_total 53449
telemt_upstream_connect_success_total 53447
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 53449
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 45263
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8134
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 53439
telemt_user_connections_current{user="hello"} 136
telemt_user_octets_from_client{user="hello"} 895523528 (854.04 MB)
telemt_user_octets_to_client{user="hello"} 55364812072 (51.56 GB)
telemt_user_msgs_from_client{user="hello"} 1232083
telemt_user_msgs_to_client{user="hello"} 6769698
telemt_user_unique_ips_current{user="hello"} 33
telemt_user_unique_ips_recent_window{user="hello"} 19
```