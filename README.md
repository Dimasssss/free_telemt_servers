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

# Server Metrics 2026-03-08 15:51:48 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 31386.5 (8h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 76830
telemt_connections_bad_total 5037
telemt_handshake_timeouts_total 1057
telemt_upstream_connect_attempt_total 68066
telemt_upstream_connect_success_total 68043
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 68066
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 64019
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3991
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 68039
telemt_user_connections_current{user="hello"} 202
telemt_user_octets_from_client{user="hello"} 1741685616 (1.62 GB)
telemt_user_octets_to_client{user="hello"} 36846962360 (34.32 GB)
telemt_user_msgs_from_client{user="hello"} 1602275
telemt_user_msgs_to_client{user="hello"} 2206129
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 31385.8 (8h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16222
telemt_connections_bad_total 141
telemt_handshake_timeouts_total 120
telemt_upstream_connect_attempt_total 15664
telemt_upstream_connect_success_total 15663
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 15664
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14450
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1127
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 86
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 15659
telemt_user_connections_current{user="hello"} 69
telemt_user_octets_from_client{user="hello"} 582574741 (555.59 MB)
telemt_user_octets_to_client{user="hello"} 14861109992 (13.84 GB)
telemt_user_msgs_from_client{user="hello"} 607168
telemt_user_msgs_to_client{user="hello"} 3954314
telemt_user_unique_ips_current{user="hello"} 13
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 31385.4 (8h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10296
telemt_connections_bad_total 150
telemt_handshake_timeouts_total 36
telemt_upstream_connect_attempt_total 9662
telemt_upstream_connect_success_total 9586
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 9662
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8857
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 657
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 72
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 9582
telemt_user_connections_current{user="hello"} 5
telemt_user_octets_from_client{user="hello"} 217764139 (207.68 MB)
telemt_user_octets_to_client{user="hello"} 3210992965 (2.99 GB)
telemt_user_msgs_from_client{user="hello"} 162009
telemt_user_msgs_to_client{user="hello"} 554382
telemt_user_unique_ips_current{user="hello"} 4
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 31385.3 (8h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13381
telemt_connections_bad_total 157
telemt_handshake_timeouts_total 53
telemt_upstream_connect_attempt_total 12756
telemt_upstream_connect_success_total 12726
telemt_upstream_connect_fail_total 30
telemt_upstream_connect_attempts_per_request{bucket="1"} 12756
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11722
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 941
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 58
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 30
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 12722
telemt_user_connections_current{user="hello"} 32
telemt_user_octets_from_client{user="hello"} 956351487 (912.05 MB)
telemt_user_octets_to_client{user="hello"} 4732892697 (4.41 GB)
telemt_user_msgs_from_client{user="hello"} 475273
telemt_user_msgs_to_client{user="hello"} 1065268
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 31385.5 (8h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 17789
telemt_connections_bad_total 5772
telemt_handshake_timeouts_total 119
telemt_upstream_connect_attempt_total 11632
telemt_upstream_connect_success_total 11628
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 11632
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9725
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1894
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11624
telemt_user_connections_current{user="hello"} 15
telemt_user_octets_from_client{user="hello"} 235694777 (224.78 MB)
telemt_user_octets_to_client{user="hello"} 8517513926 (7.93 GB)
telemt_user_msgs_from_client{user="hello"} 289041
telemt_user_msgs_to_client{user="hello"} 1198018
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 3
```