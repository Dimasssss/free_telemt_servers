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

# Server Metrics 2026-03-09 07:32:46 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 29576.7 (8h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 31582
telemt_connections_bad_total 68
telemt_handshake_timeouts_total 580
telemt_upstream_connect_attempt_total 29268
telemt_upstream_connect_success_total 29260
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 29268
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27034
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2217
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 29256
telemt_user_connections_current{user="hello"} 131
telemt_user_octets_from_client{user="hello"} 279508442 (266.56 MB)
telemt_user_octets_to_client{user="hello"} 15615516544 (14.54 GB)
telemt_user_msgs_from_client{user="hello"} 560502
telemt_user_msgs_to_client{user="hello"} 835156
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 29575.1 (8h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5453
telemt_connections_bad_total 135
telemt_handshake_timeouts_total 96
telemt_upstream_connect_attempt_total 5089
telemt_upstream_connect_success_total 5088
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 5089
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4758
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 330
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 5084
telemt_user_connections_current{user="hello"} 58
telemt_user_octets_from_client{user="hello"} 81541926 (77.76 MB)
telemt_user_octets_to_client{user="hello"} 4323841358 (4.03 GB)
telemt_user_msgs_from_client{user="hello"} 153022
telemt_user_msgs_to_client{user="hello"} 853008
telemt_user_unique_ips_current{user="hello"} 12
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 29575.5 (8h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2601
telemt_connections_bad_total 110
telemt_handshake_timeouts_total 6
telemt_upstream_connect_attempt_total 2448
telemt_upstream_connect_success_total 2448
telemt_upstream_connect_attempts_per_request{bucket="1"} 2448
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2112
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 335
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2444
telemt_user_connections_current{user="hello"} 4
telemt_user_octets_from_client{user="hello"} 915165902 (872.77 MB)
telemt_user_octets_to_client{user="hello"} 1524445297 (1.42 GB)
telemt_user_msgs_from_client{user="hello"} 361930
telemt_user_msgs_to_client{user="hello"} 290733
telemt_user_unique_ips_current{user="hello"} 3
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 29570.3 (8h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5376
telemt_connections_bad_total 77
telemt_handshake_timeouts_total 353
telemt_upstream_connect_attempt_total 4434
telemt_upstream_connect_success_total 4431
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 4434
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3650
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 761
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4427
telemt_user_connections_current{user="hello"} 26
telemt_user_octets_from_client{user="hello"} 140982091 (134.45 MB)
telemt_user_octets_to_client{user="hello"} 5560170035 (5.18 GB)
telemt_user_msgs_from_client{user="hello"} 110810
telemt_user_msgs_to_client{user="hello"} 1394846
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 29575.8 (8h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12050
telemt_connections_bad_total 6365
telemt_handshake_timeouts_total 29
telemt_upstream_connect_attempt_total 5315
telemt_upstream_connect_success_total 5315
telemt_upstream_connect_attempts_per_request{bucket="1"} 5315
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4358
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 949
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 5311
telemt_user_connections_current{user="hello"} 18
telemt_user_octets_from_client{user="hello"} 65596646 (62.56 MB)
telemt_user_octets_to_client{user="hello"} 3278414869 (3.05 GB)
telemt_user_msgs_from_client{user="hello"} 103660
telemt_user_msgs_to_client{user="hello"} 467096
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 4
```