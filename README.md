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

# Server Metrics 2026-03-07 12:38:40 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.7

telemt_uptime_seconds 19845.5 (5h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 38157
telemt_connections_bad_total 103
telemt_handshake_timeouts_total 394
telemt_upstream_connect_attempt_total 36405
telemt_upstream_connect_success_total 36394
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 36405
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34604
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1769
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 36390
telemt_user_connections_current{user="hello"} 177
telemt_user_octets_from_client{user="hello"} 1343825593 (1.25 GB)
telemt_user_octets_to_client{user="hello"} 23434779577 (21.83 GB)
telemt_user_msgs_from_client{user="hello"} 1041505
telemt_user_msgs_to_client{user="hello"} 3841732
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## psb.hosting

```
telemt 3.3.7

telemt_uptime_seconds 19845.0 (5h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9525
telemt_connections_bad_total 40
telemt_handshake_timeouts_total 59
telemt_upstream_connect_attempt_total 9054
telemt_upstream_connect_success_total 9048
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 9054
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8448
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 562
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 9046
telemt_user_connections_current{user="hello"} 38
telemt_user_octets_from_client{user="hello"} 398005945 (379.57 MB)
telemt_user_octets_to_client{user="hello"} 7386578282 (6.88 GB)
telemt_user_msgs_from_client{user="hello"} 452649
telemt_user_msgs_to_client{user="hello"} 2168363
telemt_user_unique_ips_current{user="hello"} 9
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## koara.io

```
telemt 3.3.7

telemt_uptime_seconds 19844.9 (5h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6565
telemt_connections_bad_total 163
telemt_handshake_timeouts_total 193
telemt_upstream_connect_attempt_total 5918
telemt_upstream_connect_success_total 5918
telemt_upstream_connect_attempts_per_request{bucket="1"} 5918
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5484
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 430
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 5914
telemt_user_connections_current{user="hello"} 13
telemt_user_octets_from_client{user="hello"} 71990489 (68.66 MB)
telemt_user_octets_to_client{user="hello"} 2944781144 (2.74 GB)
telemt_user_msgs_from_client{user="hello"} 111167
telemt_user_msgs_to_client{user="hello"} 659925
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## landvps.ru

```
telemt 3.3.7

telemt_uptime_seconds 19844.7 (5h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8624
telemt_connections_bad_total 26
telemt_handshake_timeouts_total 45
telemt_upstream_connect_attempt_total 7995
telemt_upstream_connect_success_total 7982
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 7995
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7456
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 487
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 7980
telemt_user_connections_current{user="hello"} 25
telemt_user_octets_from_client{user="hello"} 216185502 (206.17 MB)
telemt_user_octets_to_client{user="hello"} 3106545239 (2.89 GB)
telemt_user_msgs_from_client{user="hello"} 151954
telemt_user_msgs_to_client{user="hello"} 805787
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## rdp-onedash.ru

```
telemt 3.3.7

telemt_uptime_seconds 19845.1 (5h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11157
telemt_connections_bad_total 3817
telemt_handshake_timeouts_total 287
telemt_upstream_connect_attempt_total 6853
telemt_upstream_connect_success_total 6852
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 6853
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5468
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1367
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 6850
telemt_user_connections_current{user="hello"} 53
telemt_user_octets_from_client{user="hello"} 118892368 (113.38 MB)
telemt_user_octets_to_client{user="hello"} 14779432401 (13.76 GB)
telemt_user_msgs_from_client{user="hello"} 179466
telemt_user_msgs_to_client{user="hello"} 2731828
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 5
```