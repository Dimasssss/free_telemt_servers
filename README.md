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

# Server Metrics 2026-03-09 01:00:19 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 6030.2 (1h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5093
telemt_connections_bad_total 8
telemt_handshake_timeouts_total 171
telemt_upstream_connect_attempt_total 4568
telemt_upstream_connect_success_total 4566
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 4568
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4127
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 438
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4564
telemt_user_connections_current{user="hello"} 116
telemt_user_octets_from_client{user="hello"} 54402137 (51.88 MB)
telemt_user_octets_to_client{user="hello"} 6406758590 (5.97 GB)
telemt_user_msgs_from_client{user="hello"} 128365
telemt_user_msgs_to_client{user="hello"} 218439
telemt_user_unique_ips_current{user="hello"} 25
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 6028.2 (1h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 368
telemt_connections_bad_total 5
telemt_handshake_timeouts_total 5
telemt_upstream_connect_attempt_total 354
telemt_upstream_connect_success_total 354
telemt_upstream_connect_attempts_per_request{bucket="1"} 354
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 343
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 352
telemt_user_connections_current{user="hello"} 17
telemt_user_octets_from_client{user="hello"} 2469969 (2.36 MB)
telemt_user_octets_to_client{user="hello"} 79240561 (75.57 MB)
telemt_user_msgs_from_client{user="hello"} 6985
telemt_user_msgs_to_client{user="hello"} 20692
telemt_user_unique_ips_current{user="hello"} 6
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 6028.8 (1h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 436
telemt_connections_bad_total 45
telemt_handshake_timeouts_total 3
telemt_upstream_connect_attempt_total 379
telemt_upstream_connect_success_total 379
telemt_upstream_connect_attempts_per_request{bucket="1"} 379
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 328
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 51
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 377
telemt_user_connections_current{user="hello"} 5
telemt_user_octets_from_client{user="hello"} 16311665 (15.56 MB)
telemt_user_octets_to_client{user="hello"} 55307517 (52.75 MB)
telemt_user_msgs_from_client{user="hello"} 9884
telemt_user_msgs_to_client{user="hello"} 15128
telemt_user_unique_ips_current{user="hello"} 4
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 6023.5 (1h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 731
telemt_connections_bad_total 4
telemt_upstream_connect_attempt_total 719
telemt_upstream_connect_success_total 719
telemt_upstream_connect_attempts_per_request{bucket="1"} 719
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 583
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 132
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 717
telemt_user_connections_current{user="hello"} 33
telemt_user_octets_from_client{user="hello"} 5185346 (4.95 MB)
telemt_user_octets_to_client{user="hello"} 202729430 (193.34 MB)
telemt_user_msgs_from_client{user="hello"} 12914
telemt_user_msgs_to_client{user="hello"} 45604
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 6029.1 (1h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1825
telemt_connections_bad_total 1084
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 727
telemt_upstream_connect_success_total 727
telemt_upstream_connect_attempts_per_request{bucket="1"} 727
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 617
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 110
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 725
telemt_user_connections_current{user="hello"} 15
telemt_user_octets_from_client{user="hello"} 6659042 (6.35 MB)
telemt_user_octets_to_client{user="hello"} 1273599824 (1.19 GB)
telemt_user_msgs_from_client{user="hello"} 18571
telemt_user_msgs_to_client{user="hello"} 156882
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 3
```