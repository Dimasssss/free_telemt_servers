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

# Server Metrics 2026-03-08 10:07:11 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 10709.1 (2h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 22300
telemt_connections_bad_total 2558
telemt_handshake_timeouts_total 140
telemt_upstream_connect_attempt_total 18703
telemt_upstream_connect_success_total 18689
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 18703
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17625
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1054
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 18687
telemt_user_connections_current{user="hello"} 159
telemt_user_octets_from_client{user="hello"} 630792545 (601.57 MB)
telemt_user_octets_to_client{user="hello"} 11406513915 (10.62 GB)
telemt_user_msgs_from_client{user="hello"} 527170
telemt_user_msgs_to_client{user="hello"} 614887
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 10708.2 (2h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5133
telemt_connections_bad_total 68
telemt_handshake_timeouts_total 95
telemt_upstream_connect_attempt_total 4811
telemt_upstream_connect_success_total 4811
telemt_upstream_connect_attempts_per_request{bucket="1"} 4811
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4472
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 305
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 34
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4809
telemt_user_connections_current{user="hello"} 32
telemt_user_octets_from_client{user="hello"} 70167246 (66.92 MB)
telemt_user_octets_to_client{user="hello"} 3351485207 (3.12 GB)
telemt_user_msgs_from_client{user="hello"} 122699
telemt_user_msgs_to_client{user="hello"} 875713
telemt_user_unique_ips_current{user="hello"} 10
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 10708.1 (2h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3987
telemt_connections_bad_total 15
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 3904
telemt_upstream_connect_success_total 3904
telemt_upstream_connect_attempts_per_request{bucket="1"} 3904
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3611
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 291
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3902
telemt_user_connections_current{user="hello"} 19
telemt_user_octets_from_client{user="hello"} 35619779 (33.97 MB)
telemt_user_octets_to_client{user="hello"} 1197986580 (1.12 GB)
telemt_user_msgs_from_client{user="hello"} 41367
telemt_user_msgs_to_client{user="hello"} 195452
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 10707.8 (2h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4792
telemt_connections_bad_total 48
telemt_handshake_timeouts_total 27
telemt_upstream_connect_attempt_total 4591
telemt_upstream_connect_success_total 4584
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 4591
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4260
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 303
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4582
telemt_user_connections_current{user="hello"} 39
telemt_user_octets_from_client{user="hello"} 161907413 (154.41 MB)
telemt_user_octets_to_client{user="hello"} 2164578862 (2.02 GB)
telemt_user_msgs_from_client{user="hello"} 95189
telemt_user_msgs_to_client{user="hello"} 465256
telemt_user_unique_ips_current{user="hello"} 9
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 10708.1 (2h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6473
telemt_connections_bad_total 2017
telemt_handshake_timeouts_total 9
telemt_upstream_connect_attempt_total 4383
telemt_upstream_connect_success_total 4383
telemt_upstream_connect_attempts_per_request{bucket="1"} 4383
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3569
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 811
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4381
telemt_user_connections_current{user="hello"} 16
telemt_user_octets_from_client{user="hello"} 53899587 (51.40 MB)
telemt_user_octets_to_client{user="hello"} 3473489469 (3.23 GB)
telemt_user_msgs_from_client{user="hello"} 101081
telemt_user_msgs_to_client{user="hello"} 422370
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 2
```