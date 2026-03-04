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

# Server Metrics 2026-03-04 09:50:27 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.2.0

telemt_uptime_seconds 5242.1 (1h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9261
telemt_connections_bad_total 7
telemt_handshake_timeouts_total 147
telemt_upstream_connect_attempt_total 8202
telemt_upstream_connect_success_total 8202
telemt_upstream_connect_attempts_per_request{bucket="1"} 8202
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7683
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 8200
telemt_user_connections_current{user="hello"} 79
telemt_user_octets_from_client{user="hello"} 112041224 (106.85 MB)
telemt_user_octets_to_client{user="hello"} 3792607491 (3.53 GB)
telemt_user_msgs_from_client{user="hello"} 175726
telemt_user_msgs_to_client{user="hello"} 656298
telemt_user_unique_ips_current{user="hello"} 6
```

## psb.hosting

```
telemt 3.2.0

telemt_uptime_seconds 5253.4 (1h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 970
telemt_connections_bad_total 33
telemt_handshake_timeouts_total 22
telemt_upstream_connect_attempt_total 878
telemt_upstream_connect_success_total 878
telemt_upstream_connect_attempts_per_request{bucket="1"} 878
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 854
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 876
telemt_user_connections_current{user="hello"} 18
telemt_user_octets_from_client{user="hello"} 32529324 (31.02 MB)
telemt_user_octets_to_client{user="hello"} 357667070 (341.10 MB)
telemt_user_msgs_from_client{user="hello"} 31064
telemt_user_msgs_to_client{user="hello"} 111057
telemt_user_unique_ips_current{user="hello"} 1
```

## koara.io

```
telemt 3.2.0

telemt_uptime_seconds 5238.2 (1h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 976
telemt_connections_bad_total 62
telemt_upstream_connect_attempt_total 892
telemt_upstream_connect_success_total 892
telemt_upstream_connect_attempts_per_request{bucket="1"} 892
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 789
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 103
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 890
telemt_user_connections_current{user="hello"} 19
telemt_user_octets_from_client{user="hello"} 15276561 (14.57 MB)
telemt_user_octets_to_client{user="hello"} 1651859566 (1.54 GB)
telemt_user_msgs_from_client{user="hello"} 43219
telemt_user_msgs_to_client{user="hello"} 298260
telemt_user_unique_ips_current{user="hello"} 2
```

## landvps.ru

```
telemt 3.2.0

telemt_uptime_seconds 5228.7 (1h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1986
telemt_connections_bad_total 44
telemt_handshake_timeouts_total 11
telemt_upstream_connect_attempt_total 1755
telemt_upstream_connect_success_total 1754
telemt_upstream_connect_attempts_per_request{bucket="1"} 1753
telemt_upstream_connect_attempts_per_request{bucket="2"} 1
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1686
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 48
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1752
telemt_user_connections_current{user="hello"} 20
telemt_user_octets_from_client{user="hello"} 6983576 (6.66 MB)
telemt_user_octets_to_client{user="hello"} 244263901 (232.95 MB)
telemt_user_msgs_from_client{user="hello"} 15314
telemt_user_msgs_to_client{user="hello"} 79021
telemt_user_unique_ips_current{user="hello"} 1
```

## rdp-onedash.ru

```
telemt 3.2.0

telemt_uptime_seconds 5240.1 (1h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1902
telemt_connections_bad_total 919
telemt_handshake_timeouts_total 3
telemt_upstream_connect_attempt_total 930
telemt_upstream_connect_success_total 930
telemt_upstream_connect_attempts_per_request{bucket="1"} 930
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 785
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 145
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 928
telemt_user_connections_current{user="hello"} 12
telemt_user_octets_from_client{user="hello"} 13021046 (12.42 MB)
telemt_user_octets_to_client{user="hello"} 482317570 (459.97 MB)
telemt_user_msgs_from_client{user="hello"} 29231
telemt_user_msgs_to_client{user="hello"} 124587
```