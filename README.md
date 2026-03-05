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

# Server Metrics 2026-03-05 23:56:45 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.2

telemt_uptime_seconds 6085.5 (1h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 56697
telemt_connections_bad_total 51892
telemt_handshake_timeouts_total 944
telemt_upstream_connect_attempt_total 3821
telemt_upstream_connect_success_total 3821
telemt_upstream_connect_attempts_per_request{bucket="1"} 3821
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3612
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 207
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3819
telemt_user_connections_current{user="hello"} 82
telemt_user_octets_from_client{user="hello"} 57543762 (54.88 MB)
telemt_user_octets_to_client{user="hello"} 6687592855 (6.23 GB)
telemt_user_msgs_from_client{user="hello"} 127967
telemt_user_msgs_to_client{user="hello"} 947207
telemt_user_unique_ips_current{user="hello"} 19
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## psb.hosting

```
telemt 3.3.2

telemt_uptime_seconds 6083.3 (1h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 449
telemt_connections_bad_total 18
telemt_handshake_timeouts_total 1
telemt_upstream_connect_attempt_total 431
telemt_upstream_connect_success_total 431
telemt_upstream_connect_attempts_per_request{bucket="1"} 431
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 428
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 429
telemt_user_connections_current{user="hello"} 26
telemt_user_octets_from_client{user="hello"} 2203848 (2.10 MB)
telemt_user_octets_to_client{user="hello"} 112827676 (107.60 MB)
telemt_user_msgs_from_client{user="hello"} 6208
telemt_user_msgs_to_client{user="hello"} 41240
telemt_user_unique_ips_current{user="hello"} 6
```

## koara.io

```
telemt 3.3.2

telemt_uptime_seconds 6083.6 (1h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 424
telemt_connections_bad_total 90
telemt_upstream_connect_attempt_total 336
telemt_upstream_connect_success_total 336
telemt_upstream_connect_attempts_per_request{bucket="1"} 336
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 303
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 334
telemt_user_connections_current{user="hello"} 9
telemt_user_octets_from_client{user="hello"} 1193458 (1.14 MB)
telemt_user_octets_to_client{user="hello"} 55622023 (53.05 MB)
telemt_user_msgs_from_client{user="hello"} 3116
telemt_user_msgs_to_client{user="hello"} 16809
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## landvps.ru

```
telemt 3.3.2

telemt_uptime_seconds 6086.4 (1h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 759
telemt_connections_bad_total 73
telemt_handshake_timeouts_total 12
telemt_upstream_connect_attempt_total 656
telemt_upstream_connect_success_total 656
telemt_upstream_connect_attempts_per_request{bucket="1"} 656
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 543
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 109
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 654
telemt_user_connections_current{user="hello"} 9
telemt_user_octets_from_client{user="hello"} 19742888 (18.83 MB)
telemt_user_octets_to_client{user="hello"} 3240270050 (3.02 GB)
telemt_user_msgs_from_client{user="hello"} 56833
telemt_user_msgs_to_client{user="hello"} 569990
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## rdp-onedash.ru

```
telemt 3.3.2

telemt_uptime_seconds 6086.1 (1h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1918
telemt_connections_bad_total 1097
telemt_upstream_connect_attempt_total 807
telemt_upstream_connect_success_total 807
telemt_upstream_connect_attempts_per_request{bucket="1"} 807
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 652
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 153
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 805
telemt_user_connections_current{user="hello"} 12
telemt_user_octets_from_client{user="hello"} 29248559 (27.89 MB)
telemt_user_octets_to_client{user="hello"} 7863987441 (7.32 GB)
telemt_user_msgs_from_client{user="hello"} 80246
telemt_user_msgs_to_client{user="hello"} 1373813
telemt_user_unique_ips_current{user="hello"} 3
```