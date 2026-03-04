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

# Server Metrics 2026-03-04 09:29:55 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.2.0

telemt_uptime_seconds 4010.7 (1h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7271
telemt_connections_bad_total 7
telemt_handshake_timeouts_total 117
telemt_upstream_connect_attempt_total 6401
telemt_upstream_connect_success_total 6401
telemt_upstream_connect_attempts_per_request{bucket="1"} 6401
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5940
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 460
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 6399
telemt_user_connections_current{user="hello"} 146
telemt_user_octets_from_client{user="hello"} 81032035 (77.28 MB)
telemt_user_octets_to_client{user="hello"} 2976877921 (2.77 GB)
telemt_user_msgs_from_client{user="hello"} 129143
telemt_user_msgs_to_client{user="hello"} 513989
telemt_user_unique_ips_current{user="hello"} 14
```

## psb.hosting

```
telemt 3.2.0

telemt_uptime_seconds 4021.9 (1h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 691
telemt_connections_bad_total 18
telemt_handshake_timeouts_total 20
telemt_upstream_connect_attempt_total 617
telemt_upstream_connect_success_total 617
telemt_upstream_connect_attempts_per_request{bucket="1"} 617
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 598
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 615
telemt_user_connections_current{user="hello"} 30
telemt_user_octets_from_client{user="hello"} 16702565 (15.93 MB)
telemt_user_octets_to_client{user="hello"} 245365808 (234.00 MB)
telemt_user_msgs_from_client{user="hello"} 19954
telemt_user_msgs_to_client{user="hello"} 77032
telemt_user_unique_ips_current{user="hello"} 1
```

## koara.io

```
telemt 3.2.0

telemt_uptime_seconds 4006.6 (1h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 628
telemt_connections_bad_total 58
telemt_upstream_connect_attempt_total 553
telemt_upstream_connect_success_total 553
telemt_upstream_connect_attempts_per_request{bucket="1"} 553
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 497
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 56
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 551
telemt_user_connections_current{user="hello"} 26
telemt_user_octets_from_client{user="hello"} 9394799 (8.96 MB)
telemt_user_octets_to_client{user="hello"} 1212072715 (1.13 GB)
telemt_user_msgs_from_client{user="hello"} 26466
telemt_user_msgs_to_client{user="hello"} 204385
telemt_user_unique_ips_current{user="hello"} 4
```

## landvps.ru

```
telemt 3.2.0

telemt_uptime_seconds 3997.2 (1h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1155
telemt_connections_bad_total 40
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 1033
telemt_upstream_connect_success_total 1033
telemt_upstream_connect_attempts_per_request{bucket="1"} 1033
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 975
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 47
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1031
telemt_user_connections_current{user="hello"} 4
telemt_user_octets_from_client{user="hello"} 5011006 (4.78 MB)
telemt_user_octets_to_client{user="hello"} 185827346 (177.22 MB)
telemt_user_msgs_from_client{user="hello"} 10046
telemt_user_msgs_to_client{user="hello"} 57677
telemt_user_unique_ips_current{user="hello"} 2
```

## rdp-onedash.ru

```
telemt 3.2.0

telemt_uptime_seconds 4008.5 (1h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1510
telemt_connections_bad_total 704
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 756
telemt_upstream_connect_success_total 756
telemt_upstream_connect_attempts_per_request{bucket="1"} 756
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 633
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 123
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 754
telemt_user_connections_current{user="hello"} 4
telemt_user_octets_from_client{user="hello"} 10369764 (9.89 MB)
telemt_user_octets_to_client{user="hello"} 375035866 (357.66 MB)
telemt_user_msgs_from_client{user="hello"} 23625
telemt_user_msgs_to_client{user="hello"} 98562
telemt_user_unique_ips_current{user="hello"} 1
```