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

# Server Metrics 2026-03-06 17:18:31 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.4

telemt_uptime_seconds 24993.1 (6h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 58638
telemt_connections_bad_total 3242
telemt_handshake_timeouts_total 247
telemt_upstream_connect_attempt_total 51325
telemt_upstream_connect_success_total 51313
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 51325
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 48404
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2900
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 51309
telemt_user_connections_current{user="hello"} 126
telemt_user_octets_from_client{user="hello"} 2677484973 (2.49 GB)
telemt_user_octets_to_client{user="hello"} 34700239591 (32.32 GB)
telemt_user_msgs_from_client{user="hello"} 1828463
telemt_user_msgs_to_client{user="hello"} 5459007
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## psb.hosting

```
telemt 3.3.4

telemt_uptime_seconds 24992.8 (6h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11059
telemt_connections_bad_total 201
telemt_handshake_timeouts_total 101
telemt_upstream_connect_attempt_total 10505
telemt_upstream_connect_success_total 10486
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 10505
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9746
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 647
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 10484
telemt_user_connections_current{user="hello"} 54
telemt_user_octets_from_client{user="hello"} 143275742 (136.64 MB)
telemt_user_octets_to_client{user="hello"} 5984691484 (5.57 GB)
telemt_user_msgs_from_client{user="hello"} 228845
telemt_user_msgs_to_client{user="hello"} 1846731
telemt_user_unique_ips_current{user="hello"} 9
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## koara.io

```
telemt 3.3.4

telemt_uptime_seconds 24992.1 (6h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9080
telemt_connections_bad_total 144
telemt_handshake_timeouts_total 23
telemt_upstream_connect_attempt_total 8747
telemt_upstream_connect_success_total 8745
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 8747
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8215
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 525
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 8743
telemt_user_connections_current{user="hello"} 8
telemt_user_octets_from_client{user="hello"} 127448305 (121.54 MB)
telemt_user_octets_to_client{user="hello"} 5233898129 (4.87 GB)
telemt_user_msgs_from_client{user="hello"} 197448
telemt_user_msgs_to_client{user="hello"} 1235195
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## landvps.ru

```
telemt 3.3.4

telemt_uptime_seconds 24991.3 (6h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12734
telemt_connections_bad_total 123
telemt_handshake_timeouts_total 117
telemt_upstream_connect_attempt_total 11825
telemt_upstream_connect_success_total 11785
telemt_upstream_connect_fail_total 40
telemt_upstream_connect_attempts_per_request{bucket="1"} 11825
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10949
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 787
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 40
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11781
telemt_user_connections_current{user="hello"} 27
telemt_user_octets_from_client{user="hello"} 172647351 (164.65 MB)
telemt_user_octets_to_client{user="hello"} 5147400167 (4.79 GB)
telemt_user_msgs_from_client{user="hello"} 215179
telemt_user_msgs_to_client{user="hello"} 1215576
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## rdp-onedash.ru

```
telemt 3.3.4

telemt_uptime_seconds 24992.7 (6h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 17906
telemt_connections_bad_total 6055
telemt_handshake_timeouts_total 573
telemt_upstream_connect_attempt_total 10962
telemt_upstream_connect_success_total 10962
telemt_upstream_connect_attempts_per_request{bucket="1"} 10962
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9275
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1674
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 10960
telemt_user_connections_current{user="hello"} 39
telemt_user_octets_from_client{user="hello"} 246926855 (235.49 MB)
telemt_user_octets_to_client{user="hello"} 22116943675 (20.60 GB)
telemt_user_msgs_from_client{user="hello"} 414981
telemt_user_msgs_to_client{user="hello"} 4010419
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 2
```