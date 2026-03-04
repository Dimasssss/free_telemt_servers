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

# Server Metrics 2026-03-04 13:56:44 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.2.1

telemt_uptime_seconds 8991.1 (2h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14744
telemt_connections_bad_total 27
telemt_handshake_timeouts_total 521
telemt_upstream_connect_attempt_total 13838
telemt_upstream_connect_success_total 13836
telemt_upstream_connect_attempts_per_request{bucket="1"} 13834
telemt_upstream_connect_attempts_per_request{bucket="2"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13228
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 603
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 13834
telemt_user_connections_current{user="hello"} 160
telemt_user_octets_from_client{user="hello"} 418997029 (399.59 MB)
telemt_user_octets_to_client{user="hello"} 13664050068 (12.73 GB)
telemt_user_msgs_from_client{user="hello"} 461391
telemt_user_msgs_to_client{user="hello"} 2139603
telemt_user_unique_ips_current{user="hello"} 13
```

## psb.hosting

```
telemt 3.2.1

telemt_uptime_seconds 8993.8 (2h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3261
telemt_connections_bad_total 72
telemt_handshake_timeouts_total 5
telemt_upstream_connect_attempt_total 3030
telemt_upstream_connect_success_total 3029
telemt_upstream_connect_attempts_per_request{bucket="1"} 3028
telemt_upstream_connect_attempts_per_request{bucket="2"} 1
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2844
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 173
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3027
telemt_user_connections_current{user="hello"} 10
telemt_user_octets_from_client{user="hello"} 169579157 (161.72 MB)
telemt_user_octets_to_client{user="hello"} 3335099518 (3.11 GB)
telemt_user_msgs_from_client{user="hello"} 129168
telemt_user_msgs_to_client{user="hello"} 1049366
telemt_user_unique_ips_current{user="hello"} 1
```

## koara.io

```
telemt 3.2.1

telemt_uptime_seconds 8991.9 (2h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1463
telemt_connections_bad_total 17
telemt_handshake_timeouts_total 5
telemt_upstream_connect_attempt_total 1411
telemt_upstream_connect_success_total 1411
telemt_upstream_connect_attempts_per_request{bucket="1"} 1411
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1339
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 72
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1409
telemt_user_connections_current{user="hello"} 11
telemt_user_octets_from_client{user="hello"} 31194908 (29.75 MB)
telemt_user_octets_to_client{user="hello"} 647908231 (617.89 MB)
telemt_user_msgs_from_client{user="hello"} 48935
telemt_user_msgs_to_client{user="hello"} 156067
telemt_user_unique_ips_current{user="hello"} 2
```

## landvps.ru

```
telemt 3.2.1

telemt_uptime_seconds 8989.8 (2h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3470
telemt_connections_bad_total 22
telemt_handshake_timeouts_total 31
telemt_upstream_connect_attempt_total 3185
telemt_upstream_connect_success_total 3183
telemt_upstream_connect_attempts_per_request{bucket="1"} 3181
telemt_upstream_connect_attempts_per_request{bucket="2"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2951
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 208
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3181
telemt_user_connections_current{user="hello"} 24
telemt_user_octets_from_client{user="hello"} 21515056 (20.52 MB)
telemt_user_octets_to_client{user="hello"} 917137052 (874.65 MB)
telemt_user_msgs_from_client{user="hello"} 42805
telemt_user_msgs_to_client{user="hello"} 258519
telemt_user_unique_ips_current{user="hello"} 4
```

## rdp-onedash.ru

```
telemt 3.2.1

telemt_uptime_seconds 8991.6 (2h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3922
telemt_connections_bad_total 1615
telemt_handshake_timeouts_total 6
telemt_upstream_connect_attempt_total 2200
telemt_upstream_connect_success_total 2199
telemt_upstream_connect_attempts_per_request{bucket="1"} 2198
telemt_upstream_connect_attempts_per_request{bucket="2"} 1
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1876
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 317
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2197
telemt_user_connections_current{user="hello"} 17
telemt_user_octets_from_client{user="hello"} 44757131 (42.68 MB)
telemt_user_octets_to_client{user="hello"} 6799006972 (6.33 GB)
telemt_user_msgs_from_client{user="hello"} 107495
telemt_user_msgs_to_client{user="hello"} 1235112
telemt_user_unique_ips_current{user="hello"} 3
```