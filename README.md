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

# Server Metrics 2026-03-09 02:16:45 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 10615.8 (2h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8815
telemt_connections_bad_total 16
telemt_handshake_timeouts_total 184
telemt_upstream_connect_attempt_total 8086
telemt_upstream_connect_success_total 8084
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 8086
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7398
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 685
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 8082
telemt_user_connections_current{user="hello"} 99
telemt_user_octets_from_client{user="hello"} 93289034 (88.97 MB)
telemt_user_octets_to_client{user="hello"} 8284076874 (7.72 GB)
telemt_user_msgs_from_client{user="hello"} 197867
telemt_user_msgs_to_client{user="hello"} 323847
telemt_user_unique_ips_current{user="hello"} 26
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 10614.3 (2h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 643
telemt_connections_bad_total 14
telemt_handshake_timeouts_total 7
telemt_upstream_connect_attempt_total 613
telemt_upstream_connect_success_total 613
telemt_upstream_connect_attempts_per_request{bucket="1"} 613
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 582
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 611
telemt_user_connections_current{user="hello"} 17
telemt_user_octets_from_client{user="hello"} 8141991 (7.76 MB)
telemt_user_octets_to_client{user="hello"} 464620030 (443.10 MB)
telemt_user_msgs_from_client{user="hello"} 22693
telemt_user_msgs_to_client{user="hello"} 92554
telemt_user_unique_ips_current{user="hello"} 6
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 10614.8 (2h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 727
telemt_connections_bad_total 74
telemt_handshake_timeouts_total 3
telemt_upstream_connect_attempt_total 640
telemt_upstream_connect_success_total 640
telemt_upstream_connect_attempts_per_request{bucket="1"} 640
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 536
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 104
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 638
telemt_user_connections_current{user="hello"} 4
telemt_user_octets_from_client{user="hello"} 313627264 (299.10 MB)
telemt_user_octets_to_client{user="hello"} 101307344 (96.61 MB)
telemt_user_msgs_from_client{user="hello"} 117213
telemt_user_msgs_to_client{user="hello"} 34382
telemt_user_unique_ips_current{user="hello"} 4
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 10609.5 (2h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1362
telemt_connections_bad_total 11
telemt_handshake_timeouts_total 117
telemt_upstream_connect_attempt_total 1167
telemt_upstream_connect_success_total 1167
telemt_upstream_connect_attempts_per_request{bucket="1"} 1167
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 902
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 260
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1165
telemt_user_connections_current{user="hello"} 34
telemt_user_octets_from_client{user="hello"} 9556790 (9.11 MB)
telemt_user_octets_to_client{user="hello"} 591995694 (564.57 MB)
telemt_user_msgs_from_client{user="hello"} 24714
telemt_user_msgs_to_client{user="hello"} 169823
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 10615.1 (2h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2939
telemt_connections_bad_total 1907
telemt_handshake_timeouts_total 3
telemt_upstream_connect_attempt_total 1005
telemt_upstream_connect_success_total 1005
telemt_upstream_connect_attempts_per_request{bucket="1"} 1005
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 869
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 136
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1003
telemt_user_connections_current{user="hello"} 7
telemt_user_octets_from_client{user="hello"} 7508784 (7.16 MB)
telemt_user_octets_to_client{user="hello"} 1312735330 (1.22 GB)
telemt_user_msgs_from_client{user="hello"} 20754
telemt_user_msgs_to_client{user="hello"} 164274
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 1
```