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

# Server Metrics 2026-03-07 01:31:18 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.5

telemt_uptime_seconds 26592.5 (7h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 33640
telemt_connections_bad_total 200
telemt_handshake_timeouts_total 494
telemt_upstream_connect_attempt_total 31396
telemt_upstream_connect_success_total 31388
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 31396
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29479
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1881
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 31384
telemt_user_connections_current{user="hello"} 57
telemt_user_octets_from_client{user="hello"} 2082488594 (1.94 GB)
telemt_user_octets_to_client{user="hello"} 33092857547 (30.82 GB)
telemt_user_msgs_from_client{user="hello"} 1383519
telemt_user_msgs_to_client{user="hello"} 5218951
telemt_user_unique_ips_current{user="hello"} 16
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## psb.hosting

```
telemt 3.3.5

telemt_uptime_seconds 26591.3 (7h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6718
telemt_connections_bad_total 174
telemt_handshake_timeouts_total 104
telemt_upstream_connect_attempt_total 6286
telemt_upstream_connect_success_total 6283
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 6286
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5926
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 350
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 6279
telemt_user_connections_current{user="hello"} 6
telemt_user_octets_from_client{user="hello"} 215467552 (205.49 MB)
telemt_user_octets_to_client{user="hello"} 3896911139 (3.63 GB)
telemt_user_msgs_from_client{user="hello"} 202255
telemt_user_msgs_to_client{user="hello"} 1090071
telemt_user_unique_ips_current{user="hello"} 4
```

## koara.io

```
telemt 3.3.5

telemt_uptime_seconds 26591.2 (7h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3215
telemt_connections_bad_total 170
telemt_handshake_timeouts_total 23
telemt_upstream_connect_attempt_total 2923
telemt_upstream_connect_success_total 2923
telemt_upstream_connect_attempts_per_request{bucket="1"} 2923
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2666
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 257
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2919
telemt_user_connections_current{user="hello"} 8
telemt_user_octets_from_client{user="hello"} 65322269 (62.30 MB)
telemt_user_octets_to_client{user="hello"} 1871312589 (1.74 GB)
telemt_user_msgs_from_client{user="hello"} 64703
telemt_user_msgs_to_client{user="hello"} 397306
telemt_user_unique_ips_current{user="hello"} 4
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## landvps.ru

```
telemt 3.3.5

telemt_uptime_seconds 26591.3 (7h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4497
telemt_connections_bad_total 130
telemt_handshake_timeouts_total 16
telemt_upstream_connect_attempt_total 4295
telemt_upstream_connect_success_total 4288
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 4295
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3858
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 406
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4284
telemt_user_connections_current{user="hello"} 21
telemt_user_octets_from_client{user="hello"} 100972968 (96.30 MB)
telemt_user_octets_to_client{user="hello"} 1374085791 (1.28 GB)
telemt_user_msgs_from_client{user="hello"} 86548
telemt_user_msgs_to_client{user="hello"} 355252
telemt_user_unique_ips_current{user="hello"} 6
```

## rdp-onedash.ru

```
telemt 3.3.5

telemt_uptime_seconds 26591.8 (7h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12726
telemt_connections_bad_total 5734
telemt_handshake_timeouts_total 35
telemt_upstream_connect_attempt_total 6831
telemt_upstream_connect_success_total 6830
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 6831
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5758
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1064
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 6826
telemt_user_connections_current{user="hello"} 5
telemt_user_octets_from_client{user="hello"} 229378501 (218.75 MB)
telemt_user_octets_to_client{user="hello"} 7685195670 (7.16 GB)
telemt_user_msgs_from_client{user="hello"} 219034
telemt_user_msgs_to_client{user="hello"} 1576558
telemt_user_unique_ips_current{user="hello"} 2
telemt_user_unique_ips_recent_window{user="hello"} 1
```