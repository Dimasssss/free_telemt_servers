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

# Server Metrics 2026-03-08 07:07:31 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.10

telemt_uptime_seconds 51741.3 (14h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 76884
telemt_connections_bad_total 6900
telemt_handshake_timeouts_total 759
telemt_upstream_connect_attempt_total 65657
telemt_upstream_connect_success_total 65537
telemt_upstream_connect_fail_total 120
telemt_upstream_connect_attempts_per_request{bucket="1"} 65657
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 62099
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3391
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 47
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 120
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 65531
telemt_user_connections_current{user="hello"} 143
telemt_user_octets_from_client{user="hello"} 2745262091 (2.56 GB)
telemt_user_octets_to_client{user="hello"} 41097006941 (38.27 GB)
telemt_user_msgs_from_client{user="hello"} 1928441
telemt_user_msgs_to_client{user="hello"} 6470873
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## psb.hosting

```
telemt 3.3.10

telemt_uptime_seconds 51740.9 (14h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11357
telemt_connections_bad_total 373
telemt_handshake_timeouts_total 30
telemt_upstream_connect_attempt_total 10778
telemt_upstream_connect_success_total 10769
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 10778
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9907
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 811
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 51
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 10763
telemt_user_connections_current{user="hello"} 15
telemt_user_octets_from_client{user="hello"} 299444136 (285.57 MB)
telemt_user_octets_to_client{user="hello"} 15898730081 (14.81 GB)
telemt_user_msgs_from_client{user="hello"} 526923
telemt_user_msgs_to_client{user="hello"} 3699655
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## koara.io

```
telemt 3.3.10

telemt_uptime_seconds 51740.2 (14h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7724
telemt_connections_bad_total 351
telemt_handshake_timeouts_total 297
telemt_upstream_connect_attempt_total 6939
telemt_upstream_connect_success_total 6939
telemt_upstream_connect_attempts_per_request{bucket="1"} 6939
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6109
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 827
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 6933
telemt_user_connections_current{user="hello"} 3
telemt_user_octets_from_client{user="hello"} 149319124 (142.40 MB)
telemt_user_octets_to_client{user="hello"} 14828616335 (13.81 GB)
telemt_user_msgs_from_client{user="hello"} 254221
telemt_user_msgs_to_client{user="hello"} 3181778
telemt_user_unique_ips_current{user="hello"} 3
```

## landvps.ru

```
telemt 3.3.10

telemt_uptime_seconds 51568.5 (14h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16443
telemt_connections_bad_total 249
telemt_handshake_timeouts_total 73
telemt_upstream_connect_attempt_total 15738
telemt_upstream_connect_success_total 15709
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 15738
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13326
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2304
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 71
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 15703
telemt_user_connections_current{user="hello"} 47
telemt_user_octets_from_client{user="hello"} 487860380 (465.26 MB)
telemt_user_octets_to_client{user="hello"} 13971862750 (13.01 GB)
telemt_user_msgs_from_client{user="hello"} 476506
telemt_user_msgs_to_client{user="hello"} 3897502
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## rdp-onedash.ru

```
telemt 3.3.10

telemt_uptime_seconds 51740.4 (14h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 21773
telemt_connections_bad_total 9557
telemt_handshake_timeouts_total 43
telemt_upstream_connect_attempt_total 11919
telemt_upstream_connect_success_total 11911
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 11919
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9292
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2554
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 65
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11905
telemt_user_connections_current{user="hello"} 57
telemt_user_octets_from_client{user="hello"} 1664326578 (1.55 GB)
telemt_user_octets_to_client{user="hello"} 11098720400 (10.34 GB)
telemt_user_msgs_from_client{user="hello"} 901511
telemt_user_msgs_to_client{user="hello"} 2413180
telemt_user_unique_ips_current{user="hello"} 13
telemt_user_unique_ips_recent_window{user="hello"} 7
```