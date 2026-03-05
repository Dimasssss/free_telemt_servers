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

# Server Metrics 2026-03-05 11:36:58 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.2.1

telemt_uptime_seconds 87005.0 (24h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 126595
telemt_connections_bad_total 529
telemt_handshake_timeouts_total 4189
telemt_upstream_connect_attempt_total 111485
telemt_upstream_connect_success_total 111460
telemt_upstream_connect_attempts_per_request{bucket="1"} 111435
telemt_upstream_connect_attempts_per_request{bucket="2"} 25
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 104289
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7110
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 111450
telemt_user_connections_current{user="hello"} 202
telemt_user_octets_from_client{user="hello"} 3261611535 (3.04 GB)
telemt_user_octets_to_client{user="hello"} 76689529590 (71.42 GB)
telemt_user_msgs_from_client{user="hello"} 3199540
telemt_user_msgs_to_client{user="hello"} 12515726
telemt_user_unique_ips_current{user="hello"} 13
```

## psb.hosting

```
telemt 3.2.1

telemt_uptime_seconds 87007.8 (24h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 23180
telemt_connections_bad_total 477
telemt_handshake_timeouts_total 72
telemt_upstream_connect_attempt_total 18303
telemt_upstream_connect_success_total 18300
telemt_upstream_connect_attempts_per_request{bucket="1"} 18297
telemt_upstream_connect_attempts_per_request{bucket="2"} 3
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16985
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1221
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 94
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 18290
telemt_user_connections_current{user="hello"} 12
telemt_user_octets_from_client{user="hello"} 1178559216 (1.10 GB)
telemt_user_octets_to_client{user="hello"} 15027610493 (14.00 GB)
telemt_user_msgs_from_client{user="hello"} 833650
telemt_user_msgs_to_client{user="hello"} 4800187
```

## koara.io

```
telemt 3.2.1

telemt_uptime_seconds 87006.1 (24h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19461
telemt_connections_bad_total 393
telemt_handshake_timeouts_total 32
telemt_upstream_connect_attempt_total 15177
telemt_upstream_connect_success_total 15177
telemt_upstream_connect_attempts_per_request{bucket="1"} 15177
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14266
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 902
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 15167
telemt_user_connections_current{user="hello"} 10
telemt_user_octets_from_client{user="hello"} 447989677 (427.24 MB)
telemt_user_octets_to_client{user="hello"} 9699501058 (9.03 GB)
telemt_user_msgs_from_client{user="hello"} 454947
telemt_user_msgs_to_client{user="hello"} 2062757
telemt_user_unique_ips_current{user="hello"} 1
```

## landvps.ru

```
telemt 3.2.1

telemt_uptime_seconds 87003.8 (24h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 33139
telemt_connections_bad_total 999
telemt_handshake_timeouts_total 636
telemt_upstream_connect_attempt_total 29101
telemt_upstream_connect_success_total 29091
telemt_upstream_connect_attempts_per_request{bucket="1"} 29081
telemt_upstream_connect_attempts_per_request{bucket="2"} 10
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27024
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1876
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 15
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 176
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 29081
telemt_user_connections_current{user="hello"} 27
telemt_user_octets_from_client{user="hello"} 516594375 (492.66 MB)
telemt_user_octets_to_client{user="hello"} 17774589954 (16.55 GB)
telemt_user_msgs_from_client{user="hello"} 557471
telemt_user_msgs_to_client{user="hello"} 3972746
```

## rdp-onedash.ru

```
telemt 3.2.1

telemt_uptime_seconds 87005.5 (24h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 33675
telemt_connections_bad_total 15729
telemt_handshake_timeouts_total 69
telemt_upstream_connect_attempt_total 17388
telemt_upstream_connect_success_total 17383
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 17380
telemt_upstream_connect_attempts_per_request{bucket="2"} 4
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14934
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2402
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 17373
telemt_user_connections_current{user="hello"} 24
telemt_user_octets_from_client{user="hello"} 655243259 (624.89 MB)
telemt_user_octets_to_client{user="hello"} 28276378485 (26.33 GB)
telemt_user_msgs_from_client{user="hello"} 754871
telemt_user_msgs_to_client{user="hello"} 5413622
telemt_user_unique_ips_current{user="hello"} 3
```