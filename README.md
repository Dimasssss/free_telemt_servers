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

# Server Metrics 2026-03-06 16:52:49 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.4

telemt_uptime_seconds 23451.6 (6h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 55375
telemt_connections_bad_total 3112
telemt_handshake_timeouts_total 219
telemt_upstream_connect_attempt_total 48330
telemt_upstream_connect_success_total 48318
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 48330
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 45562
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2748
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 48314
telemt_user_connections_current{user="hello"} 160
telemt_user_octets_from_client{user="hello"} 2501614172 (2.33 GB)
telemt_user_octets_to_client{user="hello"} 31677086502 (29.50 GB)
telemt_user_msgs_from_client{user="hello"} 1702511
telemt_user_msgs_to_client{user="hello"} 5007082
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## psb.hosting

```
telemt 3.3.4

telemt_uptime_seconds 23450.9 (6h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10380
telemt_connections_bad_total 176
telemt_handshake_timeouts_total 101
telemt_upstream_connect_attempt_total 9853
telemt_upstream_connect_success_total 9834
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 9853
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9138
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 606
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 86
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 9832
telemt_user_connections_current{user="hello"} 60
telemt_user_octets_from_client{user="hello"} 128493394 (122.54 MB)
telemt_user_octets_to_client{user="hello"} 5651855825 (5.26 GB)
telemt_user_msgs_from_client{user="hello"} 209024
telemt_user_msgs_to_client{user="hello"} 1743936
telemt_user_unique_ips_current{user="hello"} 10
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## koara.io

```
telemt 3.3.4

telemt_uptime_seconds 23450.2 (6h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8630
telemt_connections_bad_total 142
telemt_handshake_timeouts_total 21
telemt_upstream_connect_attempt_total 8314
telemt_upstream_connect_success_total 8312
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 8314
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7829
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 478
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 8310
telemt_user_connections_current{user="hello"} 53
telemt_user_octets_from_client{user="hello"} 123055973 (117.36 MB)
telemt_user_octets_to_client{user="hello"} 4961370933 (4.62 GB)
telemt_user_msgs_from_client{user="hello"} 185699
telemt_user_msgs_to_client{user="hello"} 1168682
telemt_user_unique_ips_current{user="hello"} 11
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## landvps.ru

```
telemt 3.3.4

telemt_uptime_seconds 23449.5 (6h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12230
telemt_connections_bad_total 123
telemt_handshake_timeouts_total 117
telemt_upstream_connect_attempt_total 11320
telemt_upstream_connect_success_total 11283
telemt_upstream_connect_fail_total 37
telemt_upstream_connect_attempts_per_request{bucket="1"} 11320
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10499
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 736
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 37
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11281
telemt_user_connections_current{user="hello"} 43
telemt_user_octets_from_client{user="hello"} 155558821 (148.35 MB)
telemt_user_octets_to_client{user="hello"} 3812172809 (3.55 GB)
telemt_user_msgs_from_client{user="hello"} 194457
telemt_user_msgs_to_client{user="hello"} 968400
telemt_user_unique_ips_current{user="hello"} 9
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## rdp-onedash.ru

```
telemt 3.3.4

telemt_uptime_seconds 23450.8 (6h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16912
telemt_connections_bad_total 5776
telemt_handshake_timeouts_total 557
telemt_upstream_connect_attempt_total 10287
telemt_upstream_connect_success_total 10287
telemt_upstream_connect_attempts_per_request{bucket="1"} 10287
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8777
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1498
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 10285
telemt_user_connections_current{user="hello"} 15
telemt_user_octets_from_client{user="hello"} 241741868 (230.54 MB)
telemt_user_octets_to_client{user="hello"} 21806895750 (20.31 GB)
telemt_user_msgs_from_client{user="hello"} 402754
telemt_user_msgs_to_client{user="hello"} 3939255
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 2
```