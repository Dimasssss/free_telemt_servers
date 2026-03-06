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

# Server Metrics 2026-03-06 16:16:53 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.4

telemt_uptime_seconds 21295.4 (5h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 50376
telemt_connections_bad_total 3104
telemt_handshake_timeouts_total 208
telemt_upstream_connect_attempt_total 43505
telemt_upstream_connect_success_total 43493
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 43505
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 41080
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2405
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 43491
telemt_user_connections_current{user="hello"} 161
telemt_user_octets_from_client{user="hello"} 2353806999 (2.19 GB)
telemt_user_octets_to_client{user="hello"} 27570181510 (25.68 GB)
telemt_user_msgs_from_client{user="hello"} 1558885
telemt_user_msgs_to_client{user="hello"} 4377208
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## psb.hosting

```
telemt 3.3.4

telemt_uptime_seconds 21294.7 (5h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9533
telemt_connections_bad_total 172
telemt_handshake_timeouts_total 96
telemt_upstream_connect_attempt_total 9039
telemt_upstream_connect_success_total 9021
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 9039
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8388
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 545
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 84
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 9019
telemt_user_connections_current{user="hello"} 43
telemt_user_octets_from_client{user="hello"} 107425764 (102.45 MB)
telemt_user_octets_to_client{user="hello"} 5131140407 (4.78 GB)
telemt_user_msgs_from_client{user="hello"} 186271
telemt_user_msgs_to_client{user="hello"} 1598775
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## koara.io

```
telemt 3.3.4

telemt_uptime_seconds 21294.0 (5h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7801
telemt_connections_bad_total 132
telemt_handshake_timeouts_total 16
telemt_upstream_connect_attempt_total 7515
telemt_upstream_connect_success_total 7513
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 7515
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7089
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 419
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 7511
telemt_user_connections_current{user="hello"} 25
telemt_user_octets_from_client{user="hello"} 112144875 (106.95 MB)
telemt_user_octets_to_client{user="hello"} 4686051544 (4.36 GB)
telemt_user_msgs_from_client{user="hello"} 170955
telemt_user_msgs_to_client{user="hello"} 1100856
telemt_user_unique_ips_current{user="hello"} 12
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## landvps.ru

```
telemt 3.3.4

telemt_uptime_seconds 21293.4 (5h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11090
telemt_connections_bad_total 120
telemt_handshake_timeouts_total 54
telemt_upstream_connect_attempt_total 10290
telemt_upstream_connect_success_total 10254
telemt_upstream_connect_fail_total 36
telemt_upstream_connect_attempts_per_request{bucket="1"} 10290
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9560
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 651
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 36
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 10252
telemt_user_connections_current{user="hello"} 22
telemt_user_octets_from_client{user="hello"} 146513490 (139.73 MB)
telemt_user_octets_to_client{user="hello"} 3418852741 (3.18 GB)
telemt_user_msgs_from_client{user="hello"} 181968
telemt_user_msgs_to_client{user="hello"} 888270
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## rdp-onedash.ru

```
telemt 3.3.4

telemt_uptime_seconds 21294.6 (5h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15637
telemt_connections_bad_total 5389
telemt_handshake_timeouts_total 556
telemt_upstream_connect_attempt_total 9416
telemt_upstream_connect_success_total 9416
telemt_upstream_connect_attempts_per_request{bucket="1"} 9416
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8111
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1294
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 9414
telemt_user_connections_current{user="hello"} 14
telemt_user_octets_from_client{user="hello"} 230935802 (220.24 MB)
telemt_user_octets_to_client{user="hello"} 21005427847 (19.56 GB)
telemt_user_msgs_from_client{user="hello"} 377983
telemt_user_msgs_to_client{user="hello"} 3782737
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 3
```