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

# Server Metrics 2026-03-05 14:36:43 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.2.1

telemt_uptime_seconds 97789.5 (27h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 146465
telemt_connections_bad_total 554
telemt_handshake_timeouts_total 4255
telemt_upstream_connect_attempt_total 130812
telemt_upstream_connect_success_total 130777
telemt_upstream_connect_attempts_per_request{bucket="1"} 130742
telemt_upstream_connect_attempts_per_request{bucket="2"} 35
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 122569
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8130
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 78
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 130767
telemt_user_connections_current{user="hello"} 161
telemt_user_octets_from_client{user="hello"} 3592482997 (3.35 GB)
telemt_user_octets_to_client{user="hello"} 86673533891 (80.72 GB)
telemt_user_msgs_from_client{user="hello"} 3662228
telemt_user_msgs_to_client{user="hello"} 14200071
telemt_user_unique_ips_current{user="hello"} 12
```

## psb.hosting

```
telemt 3.2.1

telemt_uptime_seconds 97792.3 (27h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 27211
telemt_connections_bad_total 510
telemt_handshake_timeouts_total 85
telemt_upstream_connect_attempt_total 22223
telemt_upstream_connect_success_total 22219
telemt_upstream_connect_attempts_per_request{bucket="1"} 22215
telemt_upstream_connect_attempts_per_request{bucket="2"} 4
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20581
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1525
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 113
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 22209
telemt_user_connections_current{user="hello"} 11
telemt_user_octets_from_client{user="hello"} 1255429498 (1.17 GB)
telemt_user_octets_to_client{user="hello"} 17020112783 (15.85 GB)
telemt_user_msgs_from_client{user="hello"} 941545
telemt_user_msgs_to_client{user="hello"} 5427790
```

## koara.io

```
telemt 3.2.1

telemt_uptime_seconds 97790.6 (27h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 24764
telemt_connections_bad_total 432
telemt_handshake_timeouts_total 54
telemt_upstream_connect_attempt_total 20223
telemt_upstream_connect_success_total 20223
telemt_upstream_connect_attempts_per_request{bucket="1"} 20223
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19117
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1094
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 20211
telemt_user_connections_current{user="hello"} 25
telemt_user_octets_from_client{user="hello"} 489462298 (466.79 MB)
telemt_user_octets_to_client{user="hello"} 12488087157 (11.63 GB)
telemt_user_msgs_from_client{user="hello"} 552845
telemt_user_msgs_to_client{user="hello"} 2720391
telemt_user_unique_ips_current{user="hello"} 3
```

## landvps.ru

```
telemt 3.2.1

telemt_uptime_seconds 97788.4 (27h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 38906
telemt_connections_bad_total 1071
telemt_handshake_timeouts_total 654
telemt_upstream_connect_attempt_total 34506
telemt_upstream_connect_success_total 34487
telemt_upstream_connect_attempts_per_request{bucket="1"} 34468
telemt_upstream_connect_attempts_per_request{bucket="2"} 19
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32051
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2197
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 18
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 221
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 34477
telemt_user_connections_current{user="hello"} 4
telemt_user_octets_from_client{user="hello"} 555925357 (530.17 MB)
telemt_user_octets_to_client{user="hello"} 19746121354 (18.39 GB)
telemt_user_msgs_from_client{user="hello"} 626718
telemt_user_msgs_to_client{user="hello"} 4470699
telemt_user_unique_ips_current{user="hello"} 1
```

## rdp-onedash.ru

```
telemt 3.2.1

telemt_uptime_seconds 97790.0 (27h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 39278
telemt_connections_bad_total 17624
telemt_handshake_timeouts_total 76
telemt_upstream_connect_attempt_total 20957
telemt_upstream_connect_success_total 20952
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 20949
telemt_upstream_connect_attempts_per_request{bucket="2"} 4
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18064
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2831
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 56
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 20942
telemt_user_connections_current{user="hello"} 44
telemt_user_octets_from_client{user="hello"} 691507168 (659.47 MB)
telemt_user_octets_to_client{user="hello"} 30216980643 (28.14 GB)
telemt_user_msgs_from_client{user="hello"} 836101
telemt_user_msgs_to_client{user="hello"} 5856335
telemt_user_unique_ips_current{user="hello"} 4
```