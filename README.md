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

# Server Metrics 2026-03-08 19:01:50 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 42788.4 (11h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 98907
telemt_connections_bad_total 5056
telemt_handshake_timeouts_total 1253
telemt_upstream_connect_attempt_total 89356
telemt_upstream_connect_success_total 89325
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 89356
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 84129
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5144
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 52
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 89319
telemt_user_connections_current{user="hello"} 234
telemt_user_octets_from_client{user="hello"} 2180026478 (2.03 GB)
telemt_user_octets_to_client{user="hello"} 55049498260 (51.27 GB)
telemt_user_msgs_from_client{user="hello"} 2163079
telemt_user_msgs_to_client{user="hello"} 3033250
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 42787.3 (11h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 22371
telemt_connections_bad_total 202
telemt_handshake_timeouts_total 127
telemt_upstream_connect_attempt_total 21658
telemt_upstream_connect_success_total 21653
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 21658
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20127
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1407
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 119
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 21649
telemt_user_connections_current{user="hello"} 46
telemt_user_octets_from_client{user="hello"} 737144264 (703.00 MB)
telemt_user_octets_to_client{user="hello"} 20133003619 (18.75 GB)
telemt_user_msgs_from_client{user="hello"} 859274
telemt_user_msgs_to_client{user="hello"} 5514040
telemt_user_unique_ips_current{user="hello"} 11
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 42787.0 (11h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13726
telemt_connections_bad_total 173
telemt_handshake_timeouts_total 686
telemt_upstream_connect_attempt_total 12399
telemt_upstream_connect_success_total 12323
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 12399
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11356
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 894
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 73
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 12319
telemt_user_connections_current{user="hello"} 9
telemt_user_octets_from_client{user="hello"} 241670232 (230.47 MB)
telemt_user_octets_to_client{user="hello"} 4229238489 (3.94 GB)
telemt_user_msgs_from_client{user="hello"} 207792
telemt_user_msgs_to_client{user="hello"} 758681
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 42786.9 (11h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 17683
telemt_connections_bad_total 182
telemt_handshake_timeouts_total 59
telemt_upstream_connect_attempt_total 16923
telemt_upstream_connect_success_total 16887
telemt_upstream_connect_fail_total 36
telemt_upstream_connect_attempts_per_request{bucket="1"} 16923
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15548
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1257
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 75
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 36
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 16883
telemt_user_connections_current{user="hello"} 25
telemt_user_octets_from_client{user="hello"} 1039193645 (991.05 MB)
telemt_user_octets_to_client{user="hello"} 5991164652 (5.58 GB)
telemt_user_msgs_from_client{user="hello"} 542349
telemt_user_msgs_to_client{user="hello"} 1355853
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 42787.2 (11h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 25201
telemt_connections_bad_total 8103
telemt_handshake_timeouts_total 231
telemt_upstream_connect_attempt_total 16473
telemt_upstream_connect_success_total 16466
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 16473
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13657
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2782
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 16460
telemt_user_connections_current{user="hello"} 23
telemt_user_octets_from_client{user="hello"} 311342370 (296.92 MB)
telemt_user_octets_to_client{user="hello"} 12569068820 (11.71 GB)
telemt_user_msgs_from_client{user="hello"} 403592
telemt_user_msgs_to_client{user="hello"} 1655841
telemt_user_unique_ips_current{user="hello"} 9
telemt_user_unique_ips_recent_window{user="hello"} 5
```