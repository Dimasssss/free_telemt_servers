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

# Server Metrics 2026-03-09 15:32:54 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 58383.6 (16h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 104919
telemt_connections_bad_total 1655
telemt_handshake_timeouts_total 949
telemt_upstream_connect_attempt_total 97884
telemt_upstream_connect_success_total 97846
telemt_upstream_connect_fail_total 38
telemt_upstream_connect_attempts_per_request{bucket="1"} 97884
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 90318
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7469
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 38
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 97840
telemt_user_connections_current{user="hello"} 246
telemt_user_octets_from_client{user="hello"} 2558772192 (2.38 GB)
telemt_user_octets_to_client{user="hello"} 51162870001 (47.65 GB)
telemt_user_msgs_from_client{user="hello"} 2384329
telemt_user_msgs_to_client{user="hello"} 3387368
telemt_user_unique_ips_current{user="hello"} 48
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 58382.6 (16h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 26680
telemt_connections_bad_total 212
telemt_handshake_timeouts_total 327
telemt_upstream_connect_attempt_total 25092
telemt_upstream_connect_success_total 25075
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 25092
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22968
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1927
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 180
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 25069
telemt_user_connections_current{user="hello"} 69
telemt_user_octets_from_client{user="hello"} 824505748 (786.31 MB)
telemt_user_octets_to_client{user="hello"} 14359462931 (13.37 GB)
telemt_user_msgs_from_client{user="hello"} 728746
telemt_user_msgs_to_client{user="hello"} 3911065
telemt_user_unique_ips_current{user="hello"} 13
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 58383.2 (16h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 33225
telemt_connections_bad_total 644
telemt_handshake_timeouts_total 1583
telemt_upstream_connect_attempt_total 24325
telemt_upstream_connect_success_total 24325
telemt_upstream_connect_attempts_per_request{bucket="1"} 24325
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21882
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2438
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 24319
telemt_user_connections_current{user="hello"} 72
telemt_user_octets_from_client{user="hello"} 4364838693 (4.07 GB)
telemt_user_octets_to_client{user="hello"} 15224658419 (14.18 GB)
telemt_user_msgs_from_client{user="hello"} 1876006
telemt_user_msgs_to_client{user="hello"} 2099104
telemt_user_unique_ips_current{user="hello"} 29
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 58377.7 (16h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 36930
telemt_connections_bad_total 190
telemt_handshake_timeouts_total 835
telemt_upstream_connect_attempt_total 33896
telemt_upstream_connect_success_total 33806
telemt_upstream_connect_fail_total 90
telemt_upstream_connect_attempts_per_request{bucket="1"} 33896
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29330
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4375
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 15
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 86
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 90
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 33800
telemt_user_connections_current{user="hello"} 114
telemt_user_octets_from_client{user="hello"} 1868287602 (1.74 GB)
telemt_user_octets_to_client{user="hello"} 26848643388 (25.00 GB)
telemt_user_msgs_from_client{user="hello"} 1158299
telemt_user_msgs_to_client{user="hello"} 6951959
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 58383.2 (16h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 64387
telemt_connections_bad_total 14060
telemt_handshake_timeouts_total 1552
telemt_upstream_connect_attempt_total 45758
telemt_upstream_connect_success_total 45756
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 45758
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 38607
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7107
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 42
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 45750
telemt_user_connections_current{user="hello"} 102
telemt_user_octets_from_client{user="hello"} 776785043 (740.80 MB)
telemt_user_octets_to_client{user="hello"} 48525656811 (45.19 GB)
telemt_user_msgs_from_client{user="hello"} 1037525
telemt_user_msgs_to_client{user="hello"} 5817315
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 19
```