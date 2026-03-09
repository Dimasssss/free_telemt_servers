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

# Server Metrics 2026-03-09 15:48:12 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 59301.6 (16h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 107058
telemt_connections_bad_total 1655
telemt_handshake_timeouts_total 964
telemt_upstream_connect_attempt_total 99968
telemt_upstream_connect_success_total 99929
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 99968
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 92235
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7635
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 99923
telemt_user_connections_current{user="hello"} 225
telemt_user_octets_from_client{user="hello"} 2583101179 (2.41 GB)
telemt_user_octets_to_client{user="hello"} 52047320687 (48.47 GB)
telemt_user_msgs_from_client{user="hello"} 2419860
telemt_user_msgs_to_client{user="hello"} 3467091
telemt_user_unique_ips_current{user="hello"} 50
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 59300.4 (16h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 27405
telemt_connections_bad_total 215
telemt_handshake_timeouts_total 331
telemt_upstream_connect_attempt_total 25795
telemt_upstream_connect_success_total 25778
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 25795
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23594
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1996
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 188
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 25772
telemt_user_connections_current{user="hello"} 42
telemt_user_octets_from_client{user="hello"} 829177503 (790.77 MB)
telemt_user_octets_to_client{user="hello"} 14765888303 (13.75 GB)
telemt_user_msgs_from_client{user="hello"} 741167
telemt_user_msgs_to_client{user="hello"} 4030033
telemt_user_unique_ips_current{user="hello"} 12
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 59301.3 (16h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 34406
telemt_connections_bad_total 644
telemt_handshake_timeouts_total 1595
telemt_upstream_connect_attempt_total 25427
telemt_upstream_connect_success_total 25427
telemt_upstream_connect_attempts_per_request{bucket="1"} 25427
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22864
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2558
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 25421
telemt_user_connections_current{user="hello"} 75
telemt_user_octets_from_client{user="hello"} 4395462962 (4.09 GB)
telemt_user_octets_to_client{user="hello"} 15974929777 (14.88 GB)
telemt_user_msgs_from_client{user="hello"} 1900143
telemt_user_msgs_to_client{user="hello"} 2169972
telemt_user_unique_ips_current{user="hello"} 27
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 59295.7 (16h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 38641
telemt_connections_bad_total 191
telemt_handshake_timeouts_total 837
telemt_upstream_connect_attempt_total 35513
telemt_upstream_connect_success_total 35422
telemt_upstream_connect_fail_total 91
telemt_upstream_connect_attempts_per_request{bucket="1"} 35513
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30600
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4719
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 16
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 87
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 91
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 35416
telemt_user_connections_current{user="hello"} 119
telemt_user_octets_from_client{user="hello"} 1895059631 (1.76 GB)
telemt_user_octets_to_client{user="hello"} 28230897117 (26.29 GB)
telemt_user_msgs_from_client{user="hello"} 1196823
telemt_user_msgs_to_client{user="hello"} 7312086
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 59301.1 (16h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 66001
telemt_connections_bad_total 14256
telemt_handshake_timeouts_total 1566
telemt_upstream_connect_attempt_total 47090
telemt_upstream_connect_success_total 47088
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 47090
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 39701
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7343
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 44
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 47082
telemt_user_connections_current{user="hello"} 124
telemt_user_octets_from_client{user="hello"} 796014236 (759.14 MB)
telemt_user_octets_to_client{user="hello"} 49117852419 (45.74 GB)
telemt_user_msgs_from_client{user="hello"} 1082532
telemt_user_msgs_to_client{user="hello"} 5971227
telemt_user_unique_ips_current{user="hello"} 29
telemt_user_unique_ips_recent_window{user="hello"} 10
```