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

# Server Metrics 2026-03-07 07:40:57 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.7

telemt_uptime_seconds 1982.0 (0h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2615
telemt_connections_bad_total 19
telemt_handshake_timeouts_total 9
telemt_upstream_connect_attempt_total 2524
telemt_upstream_connect_success_total 2524
telemt_upstream_connect_attempts_per_request{bucket="1"} 2524
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2433
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 90
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2522
telemt_user_connections_current{user="hello"} 127
telemt_user_octets_from_client{user="hello"} 35777757 (34.12 MB)
telemt_user_octets_to_client{user="hello"} 3160663250 (2.94 GB)
telemt_user_msgs_from_client{user="hello"} 62462
telemt_user_msgs_to_client{user="hello"} 613348
telemt_user_unique_ips_current{user="hello"} 31
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## psb.hosting

```
telemt 3.3.7

telemt_uptime_seconds 1981.7 (0h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 627
telemt_connections_bad_total 4
telemt_handshake_timeouts_total 6
telemt_upstream_connect_attempt_total 573
telemt_upstream_connect_success_total 572
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 573
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 527
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 45
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 570
telemt_user_connections_current{user="hello"} 19
telemt_user_octets_from_client{user="hello"} 3210070 (3.06 MB)
telemt_user_octets_to_client{user="hello"} 169899524 (162.03 MB)
telemt_user_msgs_from_client{user="hello"} 7252
telemt_user_msgs_to_client{user="hello"} 48881
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## koara.io

```
telemt 3.3.7

telemt_uptime_seconds 1981.3 (0h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 518
telemt_connections_bad_total 3
telemt_handshake_timeouts_total 1
telemt_upstream_connect_attempt_total 512
telemt_upstream_connect_success_total 512
telemt_upstream_connect_attempts_per_request{bucket="1"} 512
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 454
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 57
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 510
telemt_user_connections_current{user="hello"} 16
telemt_user_octets_from_client{user="hello"} 25640738 (24.45 MB)
telemt_user_octets_to_client{user="hello"} 163503196 (155.93 MB)
telemt_user_msgs_from_client{user="hello"} 13665
telemt_user_msgs_to_client{user="hello"} 41564
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## landvps.ru

```
telemt 3.3.7

telemt_uptime_seconds 1981.2 (0h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 738
telemt_connections_bad_total 7
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 712
telemt_upstream_connect_success_total 711
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 712
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 673
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 709
telemt_user_connections_current{user="hello"} 24
telemt_user_octets_from_client{user="hello"} 6027207 (5.75 MB)
telemt_user_octets_to_client{user="hello"} 184406926 (175.86 MB)
telemt_user_msgs_from_client{user="hello"} 11261
telemt_user_msgs_to_client{user="hello"} 51584
telemt_user_unique_ips_current{user="hello"} 4
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## rdp-onedash.ru

```
telemt 3.3.7

telemt_uptime_seconds 1981.8 (0h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1371
telemt_connections_bad_total 356
telemt_handshake_timeouts_total 10
telemt_upstream_connect_attempt_total 931
telemt_upstream_connect_success_total 931
telemt_upstream_connect_attempts_per_request{bucket="1"} 931
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 750
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 181
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 929
telemt_user_connections_current{user="hello"} 7
telemt_user_octets_from_client{user="hello"} 17236661 (16.44 MB)
telemt_user_octets_to_client{user="hello"} 1884178628 (1.75 GB)
telemt_user_msgs_from_client{user="hello"} 22087
telemt_user_msgs_to_client{user="hello"} 335312
telemt_user_unique_ips_current{user="hello"} 4
telemt_user_unique_ips_recent_window{user="hello"} 1
```