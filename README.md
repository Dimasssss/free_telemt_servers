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

# Server Metrics 2026-03-05 00:40:00 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.2.1

telemt_uptime_seconds 47585.6 (13h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 68873
telemt_connections_bad_total 151
telemt_handshake_timeouts_total 1557
telemt_upstream_connect_attempt_total 62230
telemt_upstream_connect_success_total 62215
telemt_upstream_connect_attempts_per_request{bucket="1"} 62200
telemt_upstream_connect_attempts_per_request{bucket="2"} 15
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 58208
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3963
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 44
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 62209
telemt_user_connections_current{user="hello"} 43
telemt_user_octets_from_client{user="hello"} 2348954847 (2.19 GB)
telemt_user_octets_to_client{user="hello"} 47747121361 (44.47 GB)
telemt_user_msgs_from_client{user="hello"} 2018119
telemt_user_msgs_to_client{user="hello"} 7612391
telemt_user_unique_ips_current{user="hello"} 7
```

## psb.hosting

```
telemt 3.2.1

telemt_uptime_seconds 47588.5 (13h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15956
telemt_connections_bad_total 251
telemt_handshake_timeouts_total 39
telemt_upstream_connect_attempt_total 11449
telemt_upstream_connect_success_total 11447
telemt_upstream_connect_attempts_per_request{bucket="1"} 11445
telemt_upstream_connect_attempts_per_request{bucket="2"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10534
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 829
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 84
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11441
telemt_user_connections_current{user="hello"} 8
telemt_user_octets_from_client{user="hello"} 1056517296 (1007.57 MB)
telemt_user_octets_to_client{user="hello"} 11093605080 (10.33 GB)
telemt_user_msgs_from_client{user="hello"} 650258
telemt_user_msgs_to_client{user="hello"} 3737771
telemt_user_unique_ips_current{user="hello"} 2
```

## koara.io

```
telemt 3.2.1

telemt_uptime_seconds 47587.0 (13h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11294
telemt_connections_bad_total 176
telemt_handshake_timeouts_total 15
telemt_upstream_connect_attempt_total 7399
telemt_upstream_connect_success_total 7399
telemt_upstream_connect_attempts_per_request{bucket="1"} 7399
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6913
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 485
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 7393
telemt_user_connections_current{user="hello"} 1
telemt_user_octets_from_client{user="hello"} 308351413 (294.07 MB)
telemt_user_octets_to_client{user="hello"} 5256086336 (4.90 GB)
telemt_user_msgs_from_client{user="hello"} 269261
telemt_user_msgs_to_client{user="hello"} 1135039
```

## landvps.ru

```
telemt 3.2.1

telemt_uptime_seconds 47584.7 (13h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15886
telemt_connections_bad_total 687
telemt_handshake_timeouts_total 80
telemt_upstream_connect_attempt_total 13836
telemt_upstream_connect_success_total 13831
telemt_upstream_connect_attempts_per_request{bucket="1"} 13826
telemt_upstream_connect_attempts_per_request{bucket="2"} 5
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12645
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1091
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 87
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 13825
telemt_user_connections_current{user="hello"} 1
telemt_user_octets_from_client{user="hello"} 394225151 (375.96 MB)
telemt_user_octets_to_client{user="hello"} 5638645042 (5.25 GB)
telemt_user_msgs_from_client{user="hello"} 306580
telemt_user_msgs_to_client{user="hello"} 1410245
```

## rdp-onedash.ru

```
telemt 3.2.1

telemt_uptime_seconds 47586.4 (13h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 18559
telemt_connections_bad_total 8569
telemt_handshake_timeouts_total 28
telemt_upstream_connect_attempt_total 9621
telemt_upstream_connect_success_total 9617
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 9615
telemt_upstream_connect_attempts_per_request{bucket="2"} 3
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8100
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1486
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 31
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 9611
telemt_user_connections_current{user="hello"} 34
telemt_user_octets_from_client{user="hello"} 517500572 (493.53 MB)
telemt_user_octets_to_client{user="hello"} 22057829596 (20.54 GB)
telemt_user_msgs_from_client{user="hello"} 555003
telemt_user_msgs_to_client{user="hello"} 4171858
telemt_user_unique_ips_current{user="hello"} 2
```