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

# Server Metrics 2026-03-06 15:51:13 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.4

telemt_uptime_seconds 19755.8 (5h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 46279
telemt_connections_bad_total 3097
telemt_handshake_timeouts_total 177
telemt_upstream_connect_attempt_total 39528
telemt_upstream_connect_success_total 39517
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 39528
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37391
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2118
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 39515
telemt_user_connections_current{user="hello"} 124
telemt_user_octets_from_client{user="hello"} 2193013470 (2.04 GB)
telemt_user_octets_to_client{user="hello"} 24943337613 (23.23 GB)
telemt_user_msgs_from_client{user="hello"} 1428531
telemt_user_msgs_to_client{user="hello"} 3959347
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## psb.hosting

```
telemt 3.3.4

telemt_uptime_seconds 19755.3 (5h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8715
telemt_connections_bad_total 169
telemt_handshake_timeouts_total 96
telemt_upstream_connect_attempt_total 8228
telemt_upstream_connect_success_total 8210
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 8228
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7667
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 458
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 82
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 8208
telemt_user_connections_current{user="hello"} 54
telemt_user_octets_from_client{user="hello"} 92223809 (87.95 MB)
telemt_user_octets_to_client{user="hello"} 4821008362 (4.49 GB)
telemt_user_msgs_from_client{user="hello"} 168882
telemt_user_msgs_to_client{user="hello"} 1511233
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## koara.io

```
telemt 3.3.4

telemt_uptime_seconds 19754.4 (5h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7289
telemt_connections_bad_total 76
telemt_handshake_timeouts_total 16
telemt_upstream_connect_attempt_total 7061
telemt_upstream_connect_success_total 7059
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 7061
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6654
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 400
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 7057
telemt_user_connections_current{user="hello"} 24
telemt_user_octets_from_client{user="hello"} 105626135 (100.73 MB)
telemt_user_octets_to_client{user="hello"} 4405174172 (4.10 GB)
telemt_user_msgs_from_client{user="hello"} 159886
telemt_user_msgs_to_client{user="hello"} 1037381
telemt_user_unique_ips_current{user="hello"} 9
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## landvps.ru

```
telemt 3.3.4

telemt_uptime_seconds 19753.7 (5h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10389
telemt_connections_bad_total 117
telemt_handshake_timeouts_total 51
telemt_upstream_connect_attempt_total 9624
telemt_upstream_connect_success_total 9590
telemt_upstream_connect_fail_total 34
telemt_upstream_connect_attempts_per_request{bucket="1"} 9624
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8961
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 586
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 34
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 9588
telemt_user_connections_current{user="hello"} 22
telemt_user_octets_from_client{user="hello"} 141861980 (135.29 MB)
telemt_user_octets_to_client{user="hello"} 3218687506 (3.00 GB)
telemt_user_msgs_from_client{user="hello"} 171216
telemt_user_msgs_to_client{user="hello"} 832697
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## rdp-onedash.ru

```
telemt 3.3.4

telemt_uptime_seconds 19755.1 (5h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14685
telemt_connections_bad_total 5110
telemt_handshake_timeouts_total 550
telemt_upstream_connect_attempt_total 8769
telemt_upstream_connect_success_total 8769
telemt_upstream_connect_attempts_per_request{bucket="1"} 8769
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7599
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1161
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 8767
telemt_user_connections_current{user="hello"} 15
telemt_user_octets_from_client{user="hello"} 224776815 (214.36 MB)
telemt_user_octets_to_client{user="hello"} 20786076908 (19.36 GB)
telemt_user_msgs_from_client{user="hello"} 367216
telemt_user_msgs_to_client{user="hello"} 3730034
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 3
```