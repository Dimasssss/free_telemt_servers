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

# Server Metrics 2026-03-08 06:46:59 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.10

telemt_uptime_seconds 50509.5 (14h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 74796
telemt_connections_bad_total 6702
telemt_handshake_timeouts_total 754
telemt_upstream_connect_attempt_total 63828
telemt_upstream_connect_success_total 63709
telemt_upstream_connect_fail_total 119
telemt_upstream_connect_attempts_per_request{bucket="1"} 63828
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 60368
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3296
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 45
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 119
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 63703
telemt_user_connections_current{user="hello"} 156
telemt_user_octets_from_client{user="hello"} 2631932702 (2.45 GB)
telemt_user_octets_to_client{user="hello"} 40258675236 (37.49 GB)
telemt_user_msgs_from_client{user="hello"} 1859658
telemt_user_msgs_to_client{user="hello"} 6336973
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## psb.hosting

```
telemt 3.3.10

telemt_uptime_seconds 50508.5 (14h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11039
telemt_connections_bad_total 372
telemt_handshake_timeouts_total 30
telemt_upstream_connect_attempt_total 10468
telemt_upstream_connect_success_total 10459
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 10468
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9602
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 807
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 10453
telemt_user_connections_current{user="hello"} 13
telemt_user_octets_from_client{user="hello"} 285438754 (272.22 MB)
telemt_user_octets_to_client{user="hello"} 15690971153 (14.61 GB)
telemt_user_msgs_from_client{user="hello"} 514664
telemt_user_msgs_to_client{user="hello"} 3638797
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## koara.io

```
telemt 3.3.10

telemt_uptime_seconds 50508.3 (14h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7256
telemt_connections_bad_total 351
telemt_handshake_timeouts_total 297
telemt_upstream_connect_attempt_total 6475
telemt_upstream_connect_success_total 6475
telemt_upstream_connect_attempts_per_request{bucket="1"} 6475
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5660
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 813
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 6469
telemt_user_connections_current{user="hello"} 10
telemt_user_octets_from_client{user="hello"} 136910940 (130.57 MB)
telemt_user_octets_to_client{user="hello"} 14765408822 (13.75 GB)
telemt_user_msgs_from_client{user="hello"} 248474
telemt_user_msgs_to_client{user="hello"} 3164813
telemt_user_unique_ips_current{user="hello"} 4
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## landvps.ru

```
telemt 3.3.10

telemt_uptime_seconds 50336.6 (13h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16017
telemt_connections_bad_total 245
telemt_handshake_timeouts_total 66
telemt_upstream_connect_attempt_total 15356
telemt_upstream_connect_success_total 15327
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 15356
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12961
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2287
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 71
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 15321
telemt_user_connections_current{user="hello"} 31
telemt_user_octets_from_client{user="hello"} 483855885 (461.44 MB)
telemt_user_octets_to_client{user="hello"} 13880218427 (12.93 GB)
telemt_user_msgs_from_client{user="hello"} 471230
telemt_user_msgs_to_client{user="hello"} 3870396
telemt_user_unique_ips_current{user="hello"} 9
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## rdp-onedash.ru

```
telemt 3.3.10

telemt_uptime_seconds 50508.5 (14h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 21059
telemt_connections_bad_total 9338
telemt_handshake_timeouts_total 43
telemt_upstream_connect_attempt_total 11428
telemt_upstream_connect_success_total 11420
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 11428
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8917
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2439
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 64
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11414
telemt_user_connections_current{user="hello"} 15
telemt_user_octets_from_client{user="hello"} 1659997890 (1.55 GB)
telemt_user_octets_to_client{user="hello"} 10875079020 (10.13 GB)
telemt_user_msgs_from_client{user="hello"} 891943
telemt_user_msgs_to_client{user="hello"} 2365601
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 3
```