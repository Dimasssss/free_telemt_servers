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

# Server Metrics 2026-03-06 17:13:21 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.4

telemt_uptime_seconds 24682.9 (6h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 58047
telemt_connections_bad_total 3184
telemt_handshake_timeouts_total 242
telemt_upstream_connect_attempt_total 50798
telemt_upstream_connect_success_total 50786
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 50798
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 47916
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2862
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 50782
telemt_user_connections_current{user="hello"} 148
telemt_user_octets_from_client{user="hello"} 2671323993 (2.49 GB)
telemt_user_octets_to_client{user="hello"} 34287175279 (31.93 GB)
telemt_user_msgs_from_client{user="hello"} 1812993
telemt_user_msgs_to_client{user="hello"} 5394559
telemt_user_unique_ips_current{user="hello"} 33
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## psb.hosting

```
telemt 3.3.4

telemt_uptime_seconds 24682.0 (6h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10949
telemt_connections_bad_total 201
telemt_handshake_timeouts_total 101
telemt_upstream_connect_attempt_total 10395
telemt_upstream_connect_success_total 10376
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 10395
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9639
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 645
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 88
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 10374
telemt_user_connections_current{user="hello"} 81
telemt_user_octets_from_client{user="hello"} 142410555 (135.81 MB)
telemt_user_octets_to_client{user="hello"} 5965387952 (5.56 GB)
telemt_user_msgs_from_client{user="hello"} 226895
telemt_user_msgs_to_client{user="hello"} 1839846
telemt_user_unique_ips_current{user="hello"} 10
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## koara.io

```
telemt 3.3.4

telemt_uptime_seconds 24681.7 (6h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9035
telemt_connections_bad_total 143
telemt_handshake_timeouts_total 23
telemt_upstream_connect_attempt_total 8703
telemt_upstream_connect_success_total 8701
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 8703
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8172
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 524
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 8699
telemt_user_connections_current{user="hello"} 24
telemt_user_octets_from_client{user="hello"} 127181690 (121.29 MB)
telemt_user_octets_to_client{user="hello"} 5214467984 (4.86 GB)
telemt_user_msgs_from_client{user="hello"} 196701
telemt_user_msgs_to_client{user="hello"} 1230531
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## landvps.ru

```
telemt 3.3.4

telemt_uptime_seconds 24680.9 (6h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12621
telemt_connections_bad_total 123
telemt_handshake_timeouts_total 117
telemt_upstream_connect_attempt_total 11712
telemt_upstream_connect_success_total 11672
telemt_upstream_connect_fail_total 40
telemt_upstream_connect_attempts_per_request{bucket="1"} 11712
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10845
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 778
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 40
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11668
telemt_user_connections_current{user="hello"} 28
telemt_user_octets_from_client{user="hello"} 166132656 (158.44 MB)
telemt_user_octets_to_client{user="hello"} 3922177564 (3.65 GB)
telemt_user_msgs_from_client{user="hello"} 204869
telemt_user_msgs_to_client{user="hello"} 1000396
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## rdp-onedash.ru

```
telemt 3.3.4

telemt_uptime_seconds 24682.0 (6h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 17721
telemt_connections_bad_total 5999
telemt_handshake_timeouts_total 569
telemt_upstream_connect_attempt_total 10834
telemt_upstream_connect_success_total 10834
telemt_upstream_connect_attempts_per_request{bucket="1"} 10834
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9184
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1637
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 10832
telemt_user_connections_current{user="hello"} 32
telemt_user_octets_from_client{user="hello"} 244899793 (233.55 MB)
telemt_user_octets_to_client{user="hello"} 21961770860 (20.45 GB)
telemt_user_msgs_from_client{user="hello"} 410077
telemt_user_msgs_to_client{user="hello"} 3977928
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 4
```