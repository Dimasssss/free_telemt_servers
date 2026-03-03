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

# Server Metrics 2026-03-03 21:30:25 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.1.6

telemt_uptime_seconds 1166.5 (0h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 577
telemt_connections_bad_total 7
telemt_handshake_timeouts_total 3
telemt_upstream_connect_attempt_total 567
telemt_upstream_connect_success_total 566
telemt_upstream_connect_attempts_per_request{bucket="1"} 565
telemt_upstream_connect_attempts_per_request{bucket="2"} 1
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 529
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 564
telemt_user_connections_current{user="hello"} 23
telemt_user_octets_from_client{user="hello"} 5050118 (4.82 MB)
telemt_user_octets_to_client{user="hello"} 301898451 (287.91 MB)
telemt_user_msgs_from_client{user="hello"} 9617
telemt_user_msgs_to_client{user="hello"} 46838
telemt_user_unique_ips_current{user="hello"} 4
```

## psb.hosting

```
telemt 3.1.6

telemt_uptime_seconds 1169.7 (0h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 41
telemt_upstream_connect_attempt_total 40
telemt_upstream_connect_success_total 40
telemt_upstream_connect_attempts_per_request{bucket="1"} 40
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 38
telemt_user_connections_current{user="hello"} 11
telemt_user_octets_from_client{user="hello"} 297796 (290.82 KB)
telemt_user_octets_to_client{user="hello"} 12692114 (12.10 MB)
telemt_user_msgs_from_client{user="hello"} 860
telemt_user_msgs_to_client{user="hello"} 6776
telemt_user_unique_ips_current{user="hello"} 1
```

## koara.io

```
telemt 3.1.6

telemt_uptime_seconds 1165.9 (0h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 117
telemt_connections_bad_total 5
telemt_upstream_connect_attempt_total 112
telemt_upstream_connect_success_total 112
telemt_upstream_connect_attempts_per_request{bucket="1"} 112
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 96
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 110
telemt_user_connections_current{user="hello"} 3
telemt_user_octets_from_client{user="hello"} 1395667 (1.33 MB)
telemt_user_octets_to_client{user="hello"} 28263711 (26.95 MB)
telemt_user_msgs_from_client{user="hello"} 4146
telemt_user_msgs_to_client{user="hello"} 10273
```

## landvps.ru

```
telemt 3.1.6

telemt_uptime_seconds 1167.8 (0h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 932
telemt_connections_bad_total 7
telemt_handshake_timeouts_total 749
telemt_upstream_connect_attempt_total 149
telemt_upstream_connect_success_total 149
telemt_upstream_connect_attempts_per_request{bucket="1"} 149
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 143
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 147
telemt_user_octets_from_client{user="hello"} 365788 (357.21 KB)
telemt_user_octets_to_client{user="hello"} 16115855 (15.37 MB)
telemt_user_msgs_from_client{user="hello"} 939
telemt_user_msgs_to_client{user="hello"} 5019
```

## rdp-onedash.ru

```
telemt 3.1.6

telemt_uptime_seconds 1167.6 (0h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 379
telemt_connections_bad_total 211
telemt_upstream_connect_attempt_total 165
telemt_upstream_connect_success_total 165
telemt_upstream_connect_attempts_per_request{bucket="1"} 165
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 147
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 163
telemt_user_connections_current{user="hello"} 5
telemt_user_octets_from_client{user="hello"} 7788294 (7.43 MB)
telemt_user_octets_to_client{user="hello"} 2424389438 (2.26 GB)
telemt_user_msgs_from_client{user="hello"} 21233
telemt_user_msgs_to_client{user="hello"} 416115
telemt_user_unique_ips_current{user="hello"} 1
```