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

# Server Metrics 2026-03-08 10:53:30 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 13488.0 (3h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 27856
telemt_connections_bad_total 2559
telemt_handshake_timeouts_total 184
telemt_upstream_connect_attempt_total 24044
telemt_upstream_connect_success_total 24029
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 24044
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22693
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1323
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 24027
telemt_user_connections_current{user="hello"} 136
telemt_user_octets_from_client{user="hello"} 864705067 (824.65 MB)
telemt_user_octets_to_client{user="hello"} 14133632791 (13.16 GB)
telemt_user_msgs_from_client{user="hello"} 688971
telemt_user_msgs_to_client{user="hello"} 793364
telemt_user_unique_ips_current{user="hello"} 31
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 13487.2 (3h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6966
telemt_connections_bad_total 70
telemt_handshake_timeouts_total 95
telemt_upstream_connect_attempt_total 6630
telemt_upstream_connect_success_total 6630
telemt_upstream_connect_attempts_per_request{bucket="1"} 6630
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6131
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 449
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 6628
telemt_user_connections_current{user="hello"} 33
telemt_user_octets_from_client{user="hello"} 94035532 (89.68 MB)
telemt_user_octets_to_client{user="hello"} 4397477896 (4.10 GB)
telemt_user_msgs_from_client{user="hello"} 172589
telemt_user_msgs_to_client{user="hello"} 1156668
telemt_user_unique_ips_current{user="hello"} 11
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 13486.9 (3h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4675
telemt_connections_bad_total 17
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 4568
telemt_upstream_connect_success_total 4568
telemt_upstream_connect_attempts_per_request{bucket="1"} 4568
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4235
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 331
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4566
telemt_user_connections_current{user="hello"} 7
telemt_user_octets_from_client{user="hello"} 106769529 (101.82 MB)
telemt_user_octets_to_client{user="hello"} 1331051908 (1.24 GB)
telemt_user_msgs_from_client{user="hello"} 73543
telemt_user_msgs_to_client{user="hello"} 226757
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 13487.0 (3h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6381
telemt_connections_bad_total 78
telemt_handshake_timeouts_total 33
telemt_upstream_connect_attempt_total 6089
telemt_upstream_connect_success_total 6079
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 6089
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5662
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 391
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 6077
telemt_user_connections_current{user="hello"} 32
telemt_user_octets_from_client{user="hello"} 874488971 (833.98 MB)
telemt_user_octets_to_client{user="hello"} 2609051357 (2.43 GB)
telemt_user_msgs_from_client{user="hello"} 361195
telemt_user_msgs_to_client{user="hello"} 564391
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 13487.2 (3h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8342
telemt_connections_bad_total 2517
telemt_handshake_timeouts_total 10
telemt_upstream_connect_attempt_total 5700
telemt_upstream_connect_success_total 5699
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 5700
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4577
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1118
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 5697
telemt_user_connections_current{user="hello"} 16
telemt_user_octets_from_client{user="hello"} 82436604 (78.62 MB)
telemt_user_octets_to_client{user="hello"} 4136292090 (3.85 GB)
telemt_user_msgs_from_client{user="hello"} 133122
telemt_user_msgs_to_client{user="hello"} 579585
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 3
```