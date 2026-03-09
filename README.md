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

# Server Metrics 2026-03-09 00:39:56 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 4807.2 (1h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4049
telemt_connections_bad_total 6
telemt_handshake_timeouts_total 170
telemt_upstream_connect_attempt_total 3539
telemt_upstream_connect_success_total 3538
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 3539
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3176
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 361
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3536
telemt_user_connections_current{user="hello"} 132
telemt_user_octets_from_client{user="hello"} 43095450 (41.10 MB)
telemt_user_octets_to_client{user="hello"} 5855220396 (5.45 GB)
telemt_user_msgs_from_client{user="hello"} 105822
telemt_user_msgs_to_client{user="hello"} 188162
telemt_user_unique_ips_current{user="hello"} 27
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 4805.4 (1h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 303
telemt_connections_bad_total 4
telemt_handshake_timeouts_total 3
telemt_upstream_connect_attempt_total 295
telemt_upstream_connect_success_total 295
telemt_upstream_connect_attempts_per_request{bucket="1"} 295
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 287
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 293
telemt_user_connections_current{user="hello"} 16
telemt_user_octets_from_client{user="hello"} 1910261 (1.82 MB)
telemt_user_octets_to_client{user="hello"} 46640841 (44.48 MB)
telemt_user_msgs_from_client{user="hello"} 5458
telemt_user_msgs_to_client{user="hello"} 14905
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 4806.1 (1h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 354
telemt_connections_bad_total 29
telemt_handshake_timeouts_total 3
telemt_upstream_connect_attempt_total 316
telemt_upstream_connect_success_total 316
telemt_upstream_connect_attempts_per_request{bucket="1"} 316
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 276
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 40
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 314
telemt_user_connections_current{user="hello"} 4
telemt_user_octets_from_client{user="hello"} 16138915 (15.39 MB)
telemt_user_octets_to_client{user="hello"} 47682692 (45.47 MB)
telemt_user_msgs_from_client{user="hello"} 9405
telemt_user_msgs_to_client{user="hello"} 13030
telemt_user_unique_ips_current{user="hello"} 4
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 4800.8 (1h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 610
telemt_connections_bad_total 3
telemt_upstream_connect_attempt_total 600
telemt_upstream_connect_success_total 600
telemt_upstream_connect_attempts_per_request{bucket="1"} 600
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 501
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 95
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 598
telemt_user_connections_current{user="hello"} 30
telemt_user_octets_from_client{user="hello"} 3907318 (3.73 MB)
telemt_user_octets_to_client{user="hello"} 182740421 (174.27 MB)
telemt_user_msgs_from_client{user="hello"} 9663
telemt_user_msgs_to_client{user="hello"} 36625
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 4806.4 (1h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1498
telemt_connections_bad_total 861
telemt_handshake_timeouts_total 1
telemt_upstream_connect_attempt_total 626
telemt_upstream_connect_success_total 626
telemt_upstream_connect_attempts_per_request{bucket="1"} 626
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 532
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 94
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 624
telemt_user_connections_current{user="hello"} 9
telemt_user_octets_from_client{user="hello"} 6233820 (5.95 MB)
telemt_user_octets_to_client{user="hello"} 1260260336 (1.17 GB)
telemt_user_msgs_from_client{user="hello"} 17566
telemt_user_msgs_to_client{user="hello"} 153048
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 1
```