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

# Server Metrics 2026-03-04 14:22:23 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.2.1

telemt_uptime_seconds 10530.2 (2h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 17368
telemt_connections_bad_total 40
telemt_handshake_timeouts_total 527
telemt_upstream_connect_attempt_total 16389
telemt_upstream_connect_success_total 16386
telemt_upstream_connect_attempts_per_request{bucket="1"} 16383
telemt_upstream_connect_attempts_per_request{bucket="2"} 3
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15664
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 715
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 16384
telemt_user_connections_current{user="hello"} 131
telemt_user_octets_from_client{user="hello"} 447172094 (426.46 MB)
telemt_user_octets_to_client{user="hello"} 14461540089 (13.47 GB)
telemt_user_msgs_from_client{user="hello"} 502327
telemt_user_msgs_to_client{user="hello"} 2283294
telemt_user_unique_ips_current{user="hello"} 6
```

## psb.hosting

```
telemt 3.2.1

telemt_uptime_seconds 10533.1 (2h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3746
telemt_connections_bad_total 75
telemt_handshake_timeouts_total 7
telemt_upstream_connect_attempt_total 3501
telemt_upstream_connect_success_total 3500
telemt_upstream_connect_attempts_per_request{bucket="1"} 3499
telemt_upstream_connect_attempts_per_request{bucket="2"} 1
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3282
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 203
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3498
telemt_user_connections_current{user="hello"} 23
telemt_user_octets_from_client{user="hello"} 219642025 (209.47 MB)
telemt_user_octets_to_client{user="hello"} 3770665407 (3.51 GB)
telemt_user_msgs_from_client{user="hello"} 160502
telemt_user_msgs_to_client{user="hello"} 1202622
telemt_user_unique_ips_current{user="hello"} 3
```

## koara.io

```
telemt 3.2.1

telemt_uptime_seconds 10531.3 (2h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1920
telemt_connections_bad_total 27
telemt_handshake_timeouts_total 6
telemt_upstream_connect_attempt_total 1852
telemt_upstream_connect_success_total 1852
telemt_upstream_connect_attempts_per_request{bucket="1"} 1852
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1758
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 94
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1850
telemt_user_connections_current{user="hello"} 16
telemt_user_octets_from_client{user="hello"} 77793298 (74.19 MB)
telemt_user_octets_to_client{user="hello"} 752051210 (717.21 MB)
telemt_user_msgs_from_client{user="hello"} 67776
telemt_user_msgs_to_client{user="hello"} 190937
```

## landvps.ru

```
telemt 3.2.1

telemt_uptime_seconds 10529.3 (2h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4200
telemt_connections_bad_total 28
telemt_handshake_timeouts_total 32
telemt_upstream_connect_attempt_total 3837
telemt_upstream_connect_success_total 3835
telemt_upstream_connect_attempts_per_request{bucket="1"} 3833
telemt_upstream_connect_attempts_per_request{bucket="2"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3515
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 290
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3833
telemt_user_connections_current{user="hello"} 29
telemt_user_octets_from_client{user="hello"} 33581612 (32.03 MB)
telemt_user_octets_to_client{user="hello"} 2916058624 (2.72 GB)
telemt_user_msgs_from_client{user="hello"} 67354
telemt_user_msgs_to_client{user="hello"} 644999
telemt_user_unique_ips_current{user="hello"} 3
```

## rdp-onedash.ru

```
telemt 3.2.1

telemt_uptime_seconds 10531.1 (2h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4575
telemt_connections_bad_total 1892
telemt_handshake_timeouts_total 6
telemt_upstream_connect_attempt_total 2539
telemt_upstream_connect_success_total 2538
telemt_upstream_connect_attempts_per_request{bucket="1"} 2537
telemt_upstream_connect_attempts_per_request{bucket="2"} 1
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2164
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 368
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2536
telemt_user_connections_current{user="hello"} 22
telemt_user_octets_from_client{user="hello"} 47571934 (45.37 MB)
telemt_user_octets_to_client{user="hello"} 6872949330 (6.40 GB)
telemt_user_msgs_from_client{user="hello"} 113913
telemt_user_msgs_to_client{user="hello"} 1257001
telemt_user_unique_ips_current{user="hello"} 2
```