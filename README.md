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

# Server Metrics 2026-03-06 15:20:25 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.4

telemt_uptime_seconds 17908.1 (4h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 42559
telemt_connections_bad_total 3088
telemt_handshake_timeouts_total 171
telemt_upstream_connect_attempt_total 35947
telemt_upstream_connect_success_total 35937
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 35947
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34010
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1920
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 35935
telemt_user_connections_current{user="hello"} 120
telemt_user_octets_from_client{user="hello"} 2015019853 (1.88 GB)
telemt_user_octets_to_client{user="hello"} 23285094039 (21.69 GB)
telemt_user_msgs_from_client{user="hello"} 1327902
telemt_user_msgs_to_client{user="hello"} 3685353
telemt_user_unique_ips_current{user="hello"} 31
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## psb.hosting

```
telemt 3.3.4

telemt_uptime_seconds 17907.1 (4h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7989
telemt_connections_bad_total 163
telemt_handshake_timeouts_total 94
telemt_upstream_connect_attempt_total 7517
telemt_upstream_connect_success_total 7499
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 7517
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6983
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 435
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 80
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 7497
telemt_user_connections_current{user="hello"} 52
telemt_user_octets_from_client{user="hello"} 87535336 (83.48 MB)
telemt_user_octets_to_client{user="hello"} 4522199443 (4.21 GB)
telemt_user_msgs_from_client{user="hello"} 158955
telemt_user_msgs_to_client{user="hello"} 1429990
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## koara.io

```
telemt 3.3.4

telemt_uptime_seconds 17906.2 (4h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6774
telemt_connections_bad_total 66
telemt_handshake_timeouts_total 15
telemt_upstream_connect_attempt_total 6565
telemt_upstream_connect_success_total 6564
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 6565
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6205
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 354
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 6562
telemt_user_connections_current{user="hello"} 9
telemt_user_octets_from_client{user="hello"} 96292674 (91.83 MB)
telemt_user_octets_to_client{user="hello"} 4160574317 (3.87 GB)
telemt_user_msgs_from_client{user="hello"} 145275
telemt_user_msgs_to_client{user="hello"} 973088
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## landvps.ru

```
telemt 3.3.4

telemt_uptime_seconds 17905.5 (4h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9575
telemt_connections_bad_total 111
telemt_handshake_timeouts_total 35
telemt_upstream_connect_attempt_total 8880
telemt_upstream_connect_success_total 8850
telemt_upstream_connect_fail_total 30
telemt_upstream_connect_attempts_per_request{bucket="1"} 8880
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8309
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 503
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 30
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 8848
telemt_user_connections_current{user="hello"} 32
telemt_user_octets_from_client{user="hello"} 135808196 (129.52 MB)
telemt_user_octets_to_client{user="hello"} 3054831460 (2.85 GB)
telemt_user_msgs_from_client{user="hello"} 159805
telemt_user_msgs_to_client{user="hello"} 785437
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## rdp-onedash.ru

```
telemt 3.3.4

telemt_uptime_seconds 17906.8 (4h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13395
telemt_connections_bad_total 4743
telemt_handshake_timeouts_total 538
telemt_upstream_connect_attempt_total 7906
telemt_upstream_connect_success_total 7906
telemt_upstream_connect_attempts_per_request{bucket="1"} 7906
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6872
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1027
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 7904
telemt_user_connections_current{user="hello"} 18
telemt_user_octets_from_client{user="hello"} 210227672 (200.49 MB)
telemt_user_octets_to_client{user="hello"} 19435779931 (18.10 GB)
telemt_user_msgs_from_client{user="hello"} 338128
telemt_user_msgs_to_client{user="hello"} 3474902
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 3
```