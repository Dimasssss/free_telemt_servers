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

# Server Metrics 2026-03-08 09:36:23 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 8860.9 (2h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 18963
telemt_connections_bad_total 2558
telemt_handshake_timeouts_total 113
telemt_upstream_connect_attempt_total 15581
telemt_upstream_connect_success_total 15568
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 15581
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14672
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 889
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 15566
telemt_user_connections_current{user="hello"} 135
telemt_user_octets_from_client{user="hello"} 498899416 (475.79 MB)
telemt_user_octets_to_client{user="hello"} 9856885798 (9.18 GB)
telemt_user_msgs_from_client{user="hello"} 427502
telemt_user_msgs_to_client{user="hello"} 516497
telemt_user_unique_ips_current{user="hello"} 33
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 8859.7 (2h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4081
telemt_connections_bad_total 50
telemt_handshake_timeouts_total 15
telemt_upstream_connect_attempt_total 3880
telemt_upstream_connect_success_total 3880
telemt_upstream_connect_attempts_per_request{bucket="1"} 3880
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3630
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 222
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3878
telemt_user_connections_current{user="hello"} 25
telemt_user_octets_from_client{user="hello"} 50249277 (47.92 MB)
telemt_user_octets_to_client{user="hello"} 2760452845 (2.57 GB)
telemt_user_msgs_from_client{user="hello"} 94773
telemt_user_msgs_to_client{user="hello"} 708648
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 8859.4 (2h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3329
telemt_connections_bad_total 11
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 3251
telemt_upstream_connect_success_total 3251
telemt_upstream_connect_attempts_per_request{bucket="1"} 3251
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2970
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 279
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3249
telemt_user_connections_current{user="hello"} 15
telemt_user_octets_from_client{user="hello"} 33473874 (31.92 MB)
telemt_user_octets_to_client{user="hello"} 1141671607 (1.06 GB)
telemt_user_msgs_from_client{user="hello"} 35350
telemt_user_msgs_to_client{user="hello"} 178031
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 8859.3 (2h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3809
telemt_connections_bad_total 30
telemt_handshake_timeouts_total 26
telemt_upstream_connect_attempt_total 3642
telemt_upstream_connect_success_total 3637
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 3642
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3369
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 249
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3635
telemt_user_connections_current{user="hello"} 23
telemt_user_octets_from_client{user="hello"} 81885644 (78.09 MB)
telemt_user_octets_to_client{user="hello"} 1507623123 (1.40 GB)
telemt_user_msgs_from_client{user="hello"} 68274
telemt_user_msgs_to_client{user="hello"} 350458
telemt_user_unique_ips_current{user="hello"} 4
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 8859.6 (2h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5490
telemt_connections_bad_total 1688
telemt_handshake_timeouts_total 5
telemt_upstream_connect_attempt_total 3744
telemt_upstream_connect_success_total 3744
telemt_upstream_connect_attempts_per_request{bucket="1"} 3744
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3053
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 689
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3742
telemt_user_connections_current{user="hello"} 26
telemt_user_octets_from_client{user="hello"} 46574242 (44.42 MB)
telemt_user_octets_to_client{user="hello"} 3194302618 (2.97 GB)
telemt_user_msgs_from_client{user="hello"} 83124
telemt_user_msgs_to_client{user="hello"} 365423
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 4
```