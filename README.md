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

# Server Metrics 2026-03-08 10:48:22 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 13180.0 (3h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 27224
telemt_connections_bad_total 2559
telemt_handshake_timeouts_total 178
telemt_upstream_connect_attempt_total 23432
telemt_upstream_connect_success_total 23417
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 23432
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22123
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1282
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 23415
telemt_user_connections_current{user="hello"} 225
telemt_user_octets_from_client{user="hello"} 855387915 (815.76 MB)
telemt_user_octets_to_client{user="hello"} 13861448626 (12.91 GB)
telemt_user_msgs_from_client{user="hello"} 678454
telemt_user_msgs_to_client{user="hello"} 778850
telemt_user_unique_ips_current{user="hello"} 41
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 13178.9 (3h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6784
telemt_connections_bad_total 69
telemt_handshake_timeouts_total 95
telemt_upstream_connect_attempt_total 6449
telemt_upstream_connect_success_total 6449
telemt_upstream_connect_attempts_per_request{bucket="1"} 6449
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5974
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 428
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 47
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 6447
telemt_user_connections_current{user="hello"} 43
telemt_user_octets_from_client{user="hello"} 91767917 (87.52 MB)
telemt_user_octets_to_client{user="hello"} 4319978045 (4.02 GB)
telemt_user_msgs_from_client{user="hello"} 167770
telemt_user_msgs_to_client{user="hello"} 1136628
telemt_user_unique_ips_current{user="hello"} 12
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 13178.7 (3h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4596
telemt_connections_bad_total 17
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 4489
telemt_upstream_connect_success_total 4489
telemt_upstream_connect_attempts_per_request{bucket="1"} 4489
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4158
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 329
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4487
telemt_user_connections_current{user="hello"} 9
telemt_user_octets_from_client{user="hello"} 106559949 (101.62 MB)
telemt_user_octets_to_client{user="hello"} 1329842496 (1.24 GB)
telemt_user_msgs_from_client{user="hello"} 73204
telemt_user_msgs_to_client{user="hello"} 225904
telemt_user_unique_ips_current{user="hello"} 4
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 13178.5 (3h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6201
telemt_connections_bad_total 68
telemt_handshake_timeouts_total 33
telemt_upstream_connect_attempt_total 5919
telemt_upstream_connect_success_total 5909
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 5919
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5501
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 384
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 5907
telemt_user_connections_current{user="hello"} 34
telemt_user_octets_from_client{user="hello"} 872289750 (831.88 MB)
telemt_user_octets_to_client{user="hello"} 2569565728 (2.39 GB)
telemt_user_msgs_from_client{user="hello"} 358527
telemt_user_msgs_to_client{user="hello"} 555665
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 13178.9 (3h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8142
telemt_connections_bad_total 2462
telemt_handshake_timeouts_total 10
telemt_upstream_connect_attempt_total 5556
telemt_upstream_connect_success_total 5555
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 5556
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4453
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1098
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 5553
telemt_user_connections_current{user="hello"} 12
telemt_user_octets_from_client{user="hello"} 73392256 (69.99 MB)
telemt_user_octets_to_client{user="hello"} 4124733979 (3.84 GB)
telemt_user_msgs_from_client{user="hello"} 129857
telemt_user_msgs_to_client{user="hello"} 575196
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 3
```