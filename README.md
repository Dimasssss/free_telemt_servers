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

# Server Metrics 2026-03-08 13:38:16 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 23374.5 (6h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 52310
telemt_connections_bad_total 2661
telemt_handshake_timeouts_total 304
telemt_upstream_connect_attempt_total 47251
telemt_upstream_connect_success_total 47230
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 47251
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 44485
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2724
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 47226
telemt_user_connections_current{user="hello"} 218
telemt_user_octets_from_client{user="hello"} 1422074229 (1.32 GB)
telemt_user_octets_to_client{user="hello"} 22780290938 (21.22 GB)
telemt_user_msgs_from_client{user="hello"} 1155337
telemt_user_msgs_to_client{user="hello"} 1407953
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 23373.8 (6h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11875
telemt_connections_bad_total 87
telemt_handshake_timeouts_total 109
telemt_upstream_connect_attempt_total 11441
telemt_upstream_connect_success_total 11440
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 11441
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10653
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 718
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 69
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11436
telemt_user_connections_current{user="hello"} 24
telemt_user_octets_from_client{user="hello"} 459874186 (438.57 MB)
telemt_user_octets_to_client{user="hello"} 7582023751 (7.06 GB)
telemt_user_msgs_from_client{user="hello"} 400793
telemt_user_msgs_to_client{user="hello"} 1945567
telemt_user_unique_ips_current{user="hello"} 10
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 23373.5 (6h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8121
telemt_connections_bad_total 134
telemt_handshake_timeouts_total 34
telemt_upstream_connect_attempt_total 7675
telemt_upstream_connect_success_total 7600
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 7675
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7085
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 451
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 64
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 7596
telemt_user_connections_current{user="hello"} 7
telemt_user_octets_from_client{user="hello"} 195060498 (186.02 MB)
telemt_user_octets_to_client{user="hello"} 2121051287 (1.98 GB)
telemt_user_msgs_from_client{user="hello"} 126248
telemt_user_msgs_to_client{user="hello"} 373129
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 23373.4 (6h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10299
telemt_connections_bad_total 144
telemt_handshake_timeouts_total 45
telemt_upstream_connect_attempt_total 9849
telemt_upstream_connect_success_total 9830
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 9849
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9115
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 669
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 42
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 9828
telemt_user_connections_current{user="hello"} 28
telemt_user_octets_from_client{user="hello"} 908042156 (865.98 MB)
telemt_user_octets_to_client{user="hello"} 4004005418 (3.73 GB)
telemt_user_msgs_from_client{user="hello"} 421980
telemt_user_msgs_to_client{user="hello"} 872312
telemt_user_unique_ips_current{user="hello"} 6
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 23373.6 (6h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13466
telemt_connections_bad_total 4330
telemt_handshake_timeouts_total 38
telemt_upstream_connect_attempt_total 8887
telemt_upstream_connect_success_total 8884
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 8887
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7214
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1662
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 8880
telemt_user_connections_current{user="hello"} 16
telemt_user_octets_from_client{user="hello"} 215367993 (205.39 MB)
telemt_user_octets_to_client{user="hello"} 7691288913 (7.16 GB)
telemt_user_msgs_from_client{user="hello"} 244218
telemt_user_msgs_to_client{user="hello"} 1050941
telemt_user_unique_ips_current{user="hello"} 8
```