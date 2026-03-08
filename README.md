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

# Server Metrics 2026-03-08 16:07:13 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 32311.9 (8h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 79141
telemt_connections_bad_total 5038
telemt_handshake_timeouts_total 1067
telemt_upstream_connect_attempt_total 70318
telemt_upstream_connect_success_total 70293
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 70316
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 66137
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4121
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 70289
telemt_user_connections_current{user="hello"} 181
telemt_user_octets_from_client{user="hello"} 1758350104 (1.64 GB)
telemt_user_octets_to_client{user="hello"} 37731350788 (35.14 GB)
telemt_user_msgs_from_client{user="hello"} 1638028
telemt_user_msgs_to_client{user="hello"} 2275069
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 32311.0 (8h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16725
telemt_connections_bad_total 142
telemt_handshake_timeouts_total 120
telemt_upstream_connect_attempt_total 16162
telemt_upstream_connect_success_total 16161
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 16162
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14913
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1161
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 87
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 16157
telemt_user_connections_current{user="hello"} 54
telemt_user_octets_from_client{user="hello"} 610280344 (582.01 MB)
telemt_user_octets_to_client{user="hello"} 16199304756 (15.09 GB)
telemt_user_msgs_from_client{user="hello"} 645305
telemt_user_msgs_to_client{user="hello"} 4342457
telemt_user_unique_ips_current{user="hello"} 13
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 32310.7 (8h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10487
telemt_connections_bad_total 150
telemt_handshake_timeouts_total 36
telemt_upstream_connect_attempt_total 9852
telemt_upstream_connect_success_total 9776
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 9852
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9036
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 668
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 72
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 9772
telemt_user_connections_current{user="hello"} 18
telemt_user_octets_from_client{user="hello"} 219265632 (209.11 MB)
telemt_user_octets_to_client{user="hello"} 3290467879 (3.06 GB)
telemt_user_msgs_from_client{user="hello"} 165522
telemt_user_msgs_to_client{user="hello"} 566591
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 32310.6 (8h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13961
telemt_connections_bad_total 157
telemt_handshake_timeouts_total 54
telemt_upstream_connect_attempt_total 13308
telemt_upstream_connect_success_total 13278
telemt_upstream_connect_fail_total 30
telemt_upstream_connect_attempts_per_request{bucket="1"} 13308
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12242
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 971
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 60
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 30
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 13274
telemt_user_connections_current{user="hello"} 46
telemt_user_octets_from_client{user="hello"} 963000382 (918.39 MB)
telemt_user_octets_to_client{user="hello"} 4880028295 (4.54 GB)
telemt_user_msgs_from_client{user="hello"} 481795
telemt_user_msgs_to_client{user="hello"} 1100711
telemt_user_unique_ips_current{user="hello"} 9
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 32310.9 (8h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 18294
telemt_connections_bad_total 5937
telemt_handshake_timeouts_total 122
telemt_upstream_connect_attempt_total 11962
telemt_upstream_connect_success_total 11958
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 11962
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10025
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1924
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11954
telemt_user_connections_current{user="hello"} 42
telemt_user_octets_from_client{user="hello"} 239841569 (228.73 MB)
telemt_user_octets_to_client{user="hello"} 9233048737 (8.60 GB)
telemt_user_msgs_from_client{user="hello"} 299258
telemt_user_msgs_to_client{user="hello"} 1261501
telemt_user_unique_ips_current{user="hello"} 12
telemt_user_unique_ips_recent_window{user="hello"} 3
```