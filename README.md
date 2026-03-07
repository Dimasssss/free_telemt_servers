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

# Server Metrics 2026-03-07 16:39:54 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.9

telemt_uptime_seconds 741.6 (0h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1542
telemt_handshake_timeouts_total 3
telemt_upstream_connect_attempt_total 1506
telemt_upstream_connect_success_total 1506
telemt_upstream_connect_attempts_per_request{bucket="1"} 1506
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1389
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 116
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1504
telemt_user_connections_current{user="hello"} 150
telemt_user_octets_from_client{user="hello"} 75096562 (71.62 MB)
telemt_user_octets_to_client{user="hello"} 1456250845 (1.36 GB)
telemt_user_msgs_from_client{user="hello"} 60247
telemt_user_msgs_to_client{user="hello"} 215569
telemt_user_unique_ips_current{user="hello"} 31
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## psb.hosting

```
telemt 3.3.9

telemt_uptime_seconds 741.1 (0h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 357
telemt_connections_bad_total 20
telemt_handshake_timeouts_total 1
telemt_upstream_connect_attempt_total 331
telemt_upstream_connect_success_total 331
telemt_upstream_connect_attempts_per_request{bucket="1"} 331
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 322
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 329
telemt_user_connections_current{user="hello"} 44
telemt_user_octets_from_client{user="hello"} 2523001 (2.41 MB)
telemt_user_octets_to_client{user="hello"} 127149637 (121.26 MB)
telemt_user_msgs_from_client{user="hello"} 5985
telemt_user_msgs_to_client{user="hello"} 42041
telemt_user_unique_ips_current{user="hello"} 12
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## koara.io

```
telemt 3.3.9

telemt_uptime_seconds 741.0 (0h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 135
telemt_upstream_connect_attempt_total 137
telemt_upstream_connect_success_total 137
telemt_upstream_connect_attempts_per_request{bucket="1"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 126
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 135
telemt_user_connections_current{user="hello"} 11
telemt_user_octets_from_client{user="hello"} 1816948 (1.73 MB)
telemt_user_octets_to_client{user="hello"} 161286092 (153.81 MB)
telemt_user_msgs_from_client{user="hello"} 3981
telemt_user_msgs_to_client{user="hello"} 32758
telemt_user_unique_ips_current{user="hello"} 7
```

## landvps.ru

```
telemt 3.3.9

telemt_uptime_seconds 740.6 (0h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 221
telemt_handshake_timeouts_total 1
telemt_upstream_connect_attempt_total 213
telemt_upstream_connect_success_total 213
telemt_upstream_connect_attempts_per_request{bucket="1"} 213
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 201
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 211
telemt_user_connections_current{user="hello"} 15
telemt_user_octets_from_client{user="hello"} 1212583 (1.16 MB)
telemt_user_octets_to_client{user="hello"} 57494106 (54.83 MB)
telemt_user_msgs_from_client{user="hello"} 2836
telemt_user_msgs_to_client{user="hello"} 15443
telemt_user_unique_ips_current{user="hello"} 2
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## rdp-onedash.ru

```
telemt 3.3.9

telemt_uptime_seconds 741.0 (0h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 533
telemt_connections_bad_total 132
telemt_upstream_connect_attempt_total 400
telemt_upstream_connect_success_total 400
telemt_upstream_connect_attempts_per_request{bucket="1"} 400
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 303
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 92
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 398
telemt_user_connections_current{user="hello"} 35
telemt_user_octets_from_client{user="hello"} 20694746 (19.74 MB)
telemt_user_octets_to_client{user="hello"} 145732082 (138.98 MB)
telemt_user_msgs_from_client{user="hello"} 13766
telemt_user_msgs_to_client{user="hello"} 35089
telemt_user_unique_ips_current{user="hello"} 11
telemt_user_unique_ips_recent_window{user="hello"} 4
```