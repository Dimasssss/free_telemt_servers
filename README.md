# Информация

Покупаю сервера у разных хостингов для тестов и запуска прокси для Telegram

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
```tg://proxy?server=s1.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d```

-----

## psb.hosting
- Локация: Finland
- Тариф: FI-200
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 12$
- Оплачен до: 25 марта
- Ссылка:
```tg://proxy?server=s2.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d```

-----

## koara.io
- Локация: Германия, Франкфурт-на-Майне
- Тариф: DE-2
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 639 RUB
- Оплачен до: 25 марта
- Ссылка:
```tg://proxy?server=s3.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d```

-----

## landvps.ru
- Локация: Финляндия
- Тариф: FL-2
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 200 Mbps/s
- Цена в месяц: 800 RUB
- Оплачен до: 26 марта
- Ссылка:
```tg://proxy?server=s4.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d```

-----

## rdp-onedash.ru
- Локация: Нидерланды
- Тариф: Mini
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 1 Gbit/s
- Цена в месяц: 844 RUB
- Оплачен до: 14 апреля
- Ссылка:
```tg://proxy?server=s5.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d```

-----

# Server Metrics 2026-03-03 21:35:33 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.1.6

telemt_uptime_seconds 1474.2 (0h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 703
telemt_connections_bad_total 7
telemt_handshake_timeouts_total 3
telemt_upstream_connect_attempt_total 693
telemt_upstream_connect_success_total 692
telemt_upstream_connect_attempts_per_request{bucket="1"} 691
telemt_upstream_connect_attempts_per_request{bucket="2"} 1
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 650
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 41
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 690
telemt_user_connections_current{user="hello"} 34
telemt_user_octets_from_client{user="hello"} 5858910 (5.59 MB)
telemt_user_octets_to_client{user="hello"} 327563136 (312.39 MB)
telemt_user_msgs_from_client{user="hello"} 11427
telemt_user_msgs_to_client{user="hello"} 51821
telemt_user_unique_ips_current{user="hello"} 6
```

## psb.hosting

```
telemt 3.1.6

telemt_uptime_seconds 1477.3 (0h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 56
telemt_upstream_connect_attempt_total 55
telemt_upstream_connect_success_total 55
telemt_upstream_connect_attempts_per_request{bucket="1"} 55
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 55
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 53
telemt_user_connections_current{user="hello"} 9
telemt_user_octets_from_client{user="hello"} 418494 (408.69 KB)
telemt_user_octets_to_client{user="hello"} 13563644 (12.94 MB)
telemt_user_msgs_from_client{user="hello"} 1134
telemt_user_msgs_to_client{user="hello"} 7403
```

## koara.io

```
telemt 3.1.6

telemt_uptime_seconds 1474.0 (0h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 138
telemt_connections_bad_total 5
telemt_upstream_connect_attempt_total 133
telemt_upstream_connect_success_total 133
telemt_upstream_connect_attempts_per_request{bucket="1"} 133
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 115
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 131
telemt_user_connections_current{user="hello"} 4
telemt_user_octets_from_client{user="hello"} 1471126 (1.40 MB)
telemt_user_octets_to_client{user="hello"} 30470701 (29.06 MB)
telemt_user_msgs_from_client{user="hello"} 4355
telemt_user_msgs_to_client{user="hello"} 11296
telemt_user_unique_ips_current{user="hello"} 1
```

## landvps.ru

```
telemt 3.1.6

telemt_uptime_seconds 1475.5 (0h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1153
telemt_connections_bad_total 8
telemt_handshake_timeouts_total 965
telemt_upstream_connect_attempt_total 159
telemt_upstream_connect_success_total 159
telemt_upstream_connect_attempts_per_request{bucket="1"} 159
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 153
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 157
telemt_user_octets_from_client{user="hello"} 390926 (381.76 KB)
telemt_user_octets_to_client{user="hello"} 16449386 (15.69 MB)
telemt_user_msgs_from_client{user="hello"} 1008
telemt_user_msgs_to_client{user="hello"} 5220
```

## rdp-onedash.ru

```
telemt 3.1.6

telemt_uptime_seconds 1475.3 (0h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 451
telemt_connections_bad_total 266
telemt_upstream_connect_attempt_total 182
telemt_upstream_connect_success_total 182
telemt_upstream_connect_attempts_per_request{bucket="1"} 182
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 159
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 180
telemt_user_connections_current{user="hello"} 8
telemt_user_octets_from_client{user="hello"} 7953957 (7.59 MB)
telemt_user_octets_to_client{user="hello"} 2426710092 (2.26 GB)
telemt_user_msgs_from_client{user="hello"} 21736
telemt_user_msgs_to_client{user="hello"} 417675
telemt_user_unique_ips_current{user="hello"} 1
```