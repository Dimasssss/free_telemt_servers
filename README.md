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

# Server Metrics 2026-03-10 15:10:18 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 2650.0 (0h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13295
telemt_connections_bad_total 191
telemt_handshake_timeouts_total 47
telemt_upstream_connect_attempt_total 12458
telemt_upstream_connect_success_total 12457
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 12458
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11502
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 954
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 12455
telemt_user_connections_current{user="hello"} 399
telemt_user_octets_from_client{user="hello"} 176356821 (168.19 MB)
telemt_user_octets_to_client{user="hello"} 6769098187 (6.30 GB)
telemt_user_msgs_from_client{user="hello"} 247083
telemt_user_msgs_to_client{user="hello"} 421653
telemt_user_unique_ips_current{user="hello"} 82
telemt_user_unique_ips_recent_window{user="hello"} 47
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 2649.5 (0h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3795
telemt_connections_bad_total 44
telemt_handshake_timeouts_total 72
telemt_upstream_connect_attempt_total 3510
telemt_upstream_connect_success_total 3510
telemt_upstream_connect_attempts_per_request{bucket="1"} 3510
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3083
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 421
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3508
telemt_user_connections_current{user="hello"} 123
telemt_user_octets_from_client{user="hello"} 76420799 (72.88 MB)
telemt_user_octets_to_client{user="hello"} 3574815391 (3.33 GB)
telemt_user_msgs_from_client{user="hello"} 104607
telemt_user_msgs_to_client{user="hello"} 1045655
telemt_user_unique_ips_current{user="hello"} 31
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 2649.0 (0h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6408
telemt_connections_bad_total 4
telemt_handshake_timeouts_total 216
telemt_upstream_connect_attempt_total 5914
telemt_upstream_connect_success_total 5914
telemt_upstream_connect_attempts_per_request{bucket="1"} 5914
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5312
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 602
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 5912
telemt_user_connections_current{user="hello"} 119
telemt_user_octets_from_client{user="hello"} 42495236 (40.53 MB)
telemt_user_octets_to_client{user="hello"} 714369828 (681.28 MB)
telemt_user_msgs_from_client{user="hello"} 80954
telemt_user_msgs_to_client{user="hello"} 217306
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 2648.0 (0h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5974
telemt_connections_bad_total 4
telemt_handshake_timeouts_total 109
telemt_upstream_connect_attempt_total 5652
telemt_upstream_connect_success_total 5638
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 5652
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4930
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 690
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 5636
telemt_user_connections_current{user="hello"} 183
telemt_user_octets_from_client{user="hello"} 103758555 (98.95 MB)
telemt_user_octets_to_client{user="hello"} 4219122800 (3.93 GB)
telemt_user_msgs_from_client{user="hello"} 113986
telemt_user_msgs_to_client{user="hello"} 714364
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 2649.2 (0h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8429
telemt_connections_bad_total 720
telemt_handshake_timeouts_total 168
telemt_upstream_connect_attempt_total 7231
telemt_upstream_connect_success_total 7229
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 7231
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6405
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 813
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 7227
telemt_user_connections_current{user="hello"} 250
telemt_user_octets_from_client{user="hello"} 163259909 (155.70 MB)
telemt_user_octets_to_client{user="hello"} 3553314535 (3.31 GB)
telemt_user_msgs_from_client{user="hello"} 160559
telemt_user_msgs_to_client{user="hello"} 455234
telemt_user_unique_ips_current{user="hello"} 66
telemt_user_unique_ips_recent_window{user="hello"} 31
```