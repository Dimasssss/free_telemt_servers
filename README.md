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

# Server Metrics 2026-03-06 10:48:23 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.4

telemt_uptime_seconds 1585.5 (0h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3294
telemt_handshake_timeouts_total 84
telemt_upstream_connect_attempt_total 3069
telemt_upstream_connect_success_total 3069
telemt_upstream_connect_attempts_per_request{bucket="1"} 3069
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2918
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 150
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3067
telemt_user_connections_current{user="hello"} 225
telemt_user_octets_from_client{user="hello"} 59833606 (57.06 MB)
telemt_user_octets_to_client{user="hello"} 1725376346 (1.61 GB)
telemt_user_msgs_from_client{user="hello"} 76853
telemt_user_msgs_to_client{user="hello"} 290418
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## psb.hosting

```
telemt 3.3.4

telemt_uptime_seconds 1584.4 (0h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 578
telemt_connections_bad_total 13
telemt_handshake_timeouts_total 3
telemt_upstream_connect_attempt_total 554
telemt_upstream_connect_success_total 554
telemt_upstream_connect_attempts_per_request{bucket="1"} 554
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 507
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 47
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 552
telemt_user_connections_current{user="hello"} 58
telemt_user_octets_from_client{user="hello"} 7145415 (6.81 MB)
telemt_user_octets_to_client{user="hello"} 224107600 (213.73 MB)
telemt_user_msgs_from_client{user="hello"} 14827
telemt_user_msgs_to_client{user="hello"} 72176
telemt_user_unique_ips_current{user="hello"} 11
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## koara.io

```
telemt 3.3.4

telemt_uptime_seconds 1584.3 (0h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 519
telemt_connections_bad_total 5
telemt_upstream_connect_attempt_total 507
telemt_upstream_connect_success_total 507
telemt_upstream_connect_attempts_per_request{bucket="1"} 507
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 477
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 505
telemt_user_connections_current{user="hello"} 25
telemt_user_octets_from_client{user="hello"} 12777474 (12.19 MB)
telemt_user_octets_to_client{user="hello"} 246245614 (234.84 MB)
telemt_user_msgs_from_client{user="hello"} 15341
telemt_user_msgs_to_client{user="hello"} 53363
telemt_user_unique_ips_current{user="hello"} 9
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## landvps.ru

```
telemt 3.3.4

telemt_uptime_seconds 1583.0 (0h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1148
telemt_connections_bad_total 3
telemt_handshake_timeouts_total 1
telemt_upstream_connect_attempt_total 1076
telemt_upstream_connect_success_total 1069
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 1076
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1028
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 38
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1067
telemt_user_connections_current{user="hello"} 85
telemt_user_octets_from_client{user="hello"} 14319744 (13.66 MB)
telemt_user_octets_to_client{user="hello"} 173793821 (165.74 MB)
telemt_user_msgs_from_client{user="hello"} 14199
telemt_user_msgs_to_client{user="hello"} 51505
telemt_user_unique_ips_current{user="hello"} 13
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## rdp-onedash.ru

```
telemt 3.3.4

telemt_uptime_seconds 1584.5 (0h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 990
telemt_connections_bad_total 286
telemt_handshake_timeouts_total 44
telemt_upstream_connect_attempt_total 612
telemt_upstream_connect_success_total 612
telemt_upstream_connect_attempts_per_request{bucket="1"} 612
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 545
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 66
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 610
telemt_user_connections_current{user="hello"} 26
telemt_user_octets_from_client{user="hello"} 10372947 (9.89 MB)
telemt_user_octets_to_client{user="hello"} 167447276 (159.69 MB)
telemt_user_msgs_from_client{user="hello"} 8458
telemt_user_msgs_to_client{user="hello"} 35806
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 3
```