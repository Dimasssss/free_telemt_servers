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

# Server Metrics 2026-03-04 11:22:47 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.2.0

telemt_uptime_seconds 10782.0 (2h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 18426
telemt_connections_bad_total 36
telemt_handshake_timeouts_total 217
telemt_upstream_connect_attempt_total 17000
telemt_upstream_connect_success_total 16999
telemt_upstream_connect_attempts_per_request{bucket="1"} 16998
telemt_upstream_connect_attempts_per_request{bucket="2"} 1
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15869
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1128
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 16997
telemt_user_connections_current{user="hello"} 137
telemt_user_octets_from_client{user="hello"} 721078518 (687.67 MB)
telemt_user_octets_to_client{user="hello"} 9367419480 (8.72 GB)
telemt_user_msgs_from_client{user="hello"} 568377
telemt_user_msgs_to_client{user="hello"} 1540479
telemt_user_unique_ips_current{user="hello"} 14
```

## psb.hosting

```
telemt 3.2.0

telemt_uptime_seconds 10793.0 (2h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2631
telemt_connections_bad_total 67
telemt_handshake_timeouts_total 35
telemt_upstream_connect_attempt_total 2447
telemt_upstream_connect_success_total 2444
telemt_upstream_connect_attempts_per_request{bucket="1"} 2441
telemt_upstream_connect_attempts_per_request{bucket="2"} 3
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2343
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 91
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2442
telemt_user_connections_current{user="hello"} 40
telemt_user_octets_from_client{user="hello"} 80877945 (77.13 MB)
telemt_user_octets_to_client{user="hello"} 1373558511 (1.28 GB)
telemt_user_msgs_from_client{user="hello"} 79564
telemt_user_msgs_to_client{user="hello"} 418886
telemt_user_unique_ips_current{user="hello"} 3
```

## koara.io

```
telemt 3.2.0

telemt_uptime_seconds 10777.5 (2h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2121
telemt_connections_bad_total 80
telemt_handshake_timeouts_total 3
telemt_upstream_connect_attempt_total 2003
telemt_upstream_connect_success_total 2003
telemt_upstream_connect_attempts_per_request{bucket="1"} 2003
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1795
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 208
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2001
telemt_user_connections_current{user="hello"} 19
telemt_user_octets_from_client{user="hello"} 45445503 (43.34 MB)
telemt_user_octets_to_client{user="hello"} 3382328878 (3.15 GB)
telemt_user_msgs_from_client{user="hello"} 98049
telemt_user_msgs_to_client{user="hello"} 646334
telemt_user_unique_ips_current{user="hello"} 4
```

## landvps.ru

```
telemt 3.2.0

telemt_uptime_seconds 10768.1 (2h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3808
telemt_connections_bad_total 82
telemt_handshake_timeouts_total 23
telemt_upstream_connect_attempt_total 3468
telemt_upstream_connect_success_total 3467
telemt_upstream_connect_attempts_per_request{bucket="1"} 3466
telemt_upstream_connect_attempts_per_request{bucket="2"} 1
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3330
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 107
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3465
telemt_user_connections_current{user="hello"} 22
telemt_user_octets_from_client{user="hello"} 24174184 (23.05 MB)
telemt_user_octets_to_client{user="hello"} 1243963121 (1.16 GB)
telemt_user_msgs_from_client{user="hello"} 41895
telemt_user_msgs_to_client{user="hello"} 347369
telemt_user_unique_ips_current{user="hello"} 2
```

## rdp-onedash.ru

```
telemt 3.2.0

telemt_uptime_seconds 10779.6 (2h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3943
telemt_connections_bad_total 1927
telemt_handshake_timeouts_total 5
telemt_upstream_connect_attempt_total 1942
telemt_upstream_connect_success_total 1942
telemt_upstream_connect_attempts_per_request{bucket="1"} 1942
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1726
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 215
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1940
telemt_user_connections_current{user="hello"} 17
telemt_user_octets_from_client{user="hello"} 28093144 (26.79 MB)
telemt_user_octets_to_client{user="hello"} 1029377347 (981.69 MB)
telemt_user_msgs_from_client{user="hello"} 53962
telemt_user_msgs_to_client{user="hello"} 256036
telemt_user_unique_ips_current{user="hello"} 4
```