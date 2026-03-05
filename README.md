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

# Server Metrics 2026-03-05 01:10:47 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.2.1

telemt_uptime_seconds 49433.0 (13h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 70224
telemt_connections_bad_total 162
telemt_handshake_timeouts_total 1559
telemt_upstream_connect_attempt_total 63554
telemt_upstream_connect_success_total 63539
telemt_upstream_connect_attempts_per_request{bucket="1"} 63524
telemt_upstream_connect_attempts_per_request{bucket="2"} 15
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 59426
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4069
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 44
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 63533
telemt_user_connections_current{user="hello"} 63
telemt_user_octets_from_client{user="hello"} 2355462495 (2.19 GB)
telemt_user_octets_to_client{user="hello"} 48391691191 (45.07 GB)
telemt_user_msgs_from_client{user="hello"} 2035963
telemt_user_msgs_to_client{user="hello"} 7710345
telemt_user_unique_ips_current{user="hello"} 9
```

## psb.hosting

```
telemt 3.2.1

telemt_uptime_seconds 49435.9 (13h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15971
telemt_connections_bad_total 251
telemt_handshake_timeouts_total 41
telemt_upstream_connect_attempt_total 11462
telemt_upstream_connect_success_total 11460
telemt_upstream_connect_attempts_per_request{bucket="1"} 11458
telemt_upstream_connect_attempts_per_request{bucket="2"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10547
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 829
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 84
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11454
telemt_user_connections_current{user="hello"} 8
telemt_user_octets_from_client{user="hello"} 1056610683 (1007.66 MB)
telemt_user_octets_to_client{user="hello"} 11094129487 (10.33 GB)
telemt_user_msgs_from_client{user="hello"} 650636
telemt_user_msgs_to_client{user="hello"} 3738263
telemt_user_unique_ips_current{user="hello"} 2
```

## koara.io

```
telemt 3.2.1

telemt_uptime_seconds 49433.9 (13h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11371
telemt_connections_bad_total 180
telemt_handshake_timeouts_total 17
telemt_upstream_connect_attempt_total 7470
telemt_upstream_connect_success_total 7470
telemt_upstream_connect_attempts_per_request{bucket="1"} 7470
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6960
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 509
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 7464
telemt_user_connections_current{user="hello"} 2
telemt_user_octets_from_client{user="hello"} 308631826 (294.33 MB)
telemt_user_octets_to_client{user="hello"} 5269545925 (4.91 GB)
telemt_user_msgs_from_client{user="hello"} 270005
telemt_user_msgs_to_client{user="hello"} 1140276
telemt_user_unique_ips_current{user="hello"} 1
```

## landvps.ru

```
telemt 3.2.1

telemt_uptime_seconds 49431.8 (13h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16655
telemt_connections_bad_total 690
telemt_handshake_timeouts_total 88
telemt_upstream_connect_attempt_total 14505
telemt_upstream_connect_success_total 14500
telemt_upstream_connect_attempts_per_request{bucket="1"} 14495
telemt_upstream_connect_attempts_per_request{bucket="2"} 5
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13293
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1111
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 88
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 14494
telemt_user_connections_current{user="hello"} 16
telemt_user_octets_from_client{user="hello"} 397592571 (379.17 MB)
telemt_user_octets_to_client{user="hello"} 5667316128 (5.28 GB)
telemt_user_msgs_from_client{user="hello"} 311799
telemt_user_msgs_to_client{user="hello"} 1425779
```

## rdp-onedash.ru

```
telemt 3.2.1

telemt_uptime_seconds 49433.6 (13h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19144
telemt_connections_bad_total 8900
telemt_handshake_timeouts_total 30
telemt_upstream_connect_attempt_total 9871
telemt_upstream_connect_success_total 9867
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 9865
telemt_upstream_connect_attempts_per_request{bucket="2"} 3
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8282
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1553
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 9861
telemt_user_connections_current{user="hello"} 14
telemt_user_octets_from_client{user="hello"} 520008502 (495.92 MB)
telemt_user_octets_to_client{user="hello"} 22396855896 (20.86 GB)
telemt_user_msgs_from_client{user="hello"} 561315
telemt_user_msgs_to_client{user="hello"} 4251511
telemt_user_unique_ips_current{user="hello"} 1
```