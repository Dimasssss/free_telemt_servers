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

# Server Metrics 2026-03-06 03:11:41 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.2

telemt_uptime_seconds 17780.4 (4h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 67101
telemt_connections_bad_total 51931
telemt_handshake_timeouts_total 2236
telemt_upstream_connect_attempt_total 11898
telemt_upstream_connect_success_total 11897
telemt_upstream_connect_attempts_per_request{bucket="1"} 11896
telemt_upstream_connect_attempts_per_request{bucket="2"} 1
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11203
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 691
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11895
telemt_user_connections_current{user="hello"} 68
telemt_user_octets_from_client{user="hello"} 157888725 (150.57 MB)
telemt_user_octets_to_client{user="hello"} 9837351435 (9.16 GB)
telemt_user_msgs_from_client{user="hello"} 280423
telemt_user_msgs_to_client{user="hello"} 1480329
telemt_user_unique_ips_current{user="hello"} 21
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## psb.hosting

```
telemt 3.3.2

telemt_uptime_seconds 17778.1 (4h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1595
telemt_connections_bad_total 133
telemt_handshake_timeouts_total 3
telemt_upstream_connect_attempt_total 1438
telemt_upstream_connect_success_total 1437
telemt_upstream_connect_attempts_per_request{bucket="1"} 1436
telemt_upstream_connect_attempts_per_request{bucket="2"} 1
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1406
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1435
telemt_user_connections_current{user="hello"} 29
telemt_user_octets_from_client{user="hello"} 46167694 (44.03 MB)
telemt_user_octets_to_client{user="hello"} 686880739 (655.06 MB)
telemt_user_msgs_from_client{user="hello"} 54944
telemt_user_msgs_to_client{user="hello"} 213569
telemt_user_unique_ips_current{user="hello"} 9
```

## koara.io

```
telemt 3.3.2

telemt_uptime_seconds 17778.5 (4h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1197
telemt_connections_bad_total 192
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 995
telemt_upstream_connect_success_total 995
telemt_upstream_connect_attempts_per_request{bucket="1"} 995
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 841
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 154
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 993
telemt_user_connections_current{user="hello"} 5
telemt_user_octets_from_client{user="hello"} 35533058 (33.89 MB)
telemt_user_octets_to_client{user="hello"} 1672802226 (1.56 GB)
telemt_user_msgs_from_client{user="hello"} 43334
telemt_user_msgs_to_client{user="hello"} 331786
telemt_user_unique_ips_current{user="hello"} 4
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## landvps.ru

```
telemt 3.3.2

telemt_uptime_seconds 17781.3 (4h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2169
telemt_connections_bad_total 125
telemt_handshake_timeouts_total 250
telemt_upstream_connect_attempt_total 1733
telemt_upstream_connect_success_total 1733
telemt_upstream_connect_attempts_per_request{bucket="1"} 1733
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1388
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 339
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1731
telemt_user_connections_current{user="hello"} 4
telemt_user_octets_from_client{user="hello"} 93122273 (88.81 MB)
telemt_user_octets_to_client{user="hello"} 5596658687 (5.21 GB)
telemt_user_msgs_from_client{user="hello"} 128612
telemt_user_msgs_to_client{user="hello"} 1166927
telemt_user_unique_ips_current{user="hello"} 1
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## rdp-onedash.ru

```
telemt 3.3.2

telemt_uptime_seconds 17781.1 (4h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5670
telemt_connections_bad_total 3256
telemt_handshake_timeouts_total 137
telemt_upstream_connect_attempt_total 2218
telemt_upstream_connect_success_total 2218
telemt_upstream_connect_attempts_per_request{bucket="1"} 2218
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1919
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 297
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2216
telemt_user_connections_current{user="hello"} 9
telemt_user_octets_from_client{user="hello"} 48545319 (46.30 MB)
telemt_user_octets_to_client{user="hello"} 11182382697 (10.41 GB)
telemt_user_msgs_from_client{user="hello"} 128429
telemt_user_msgs_to_client{user="hello"} 2029413
telemt_user_unique_ips_current{user="hello"} 4
telemt_user_unique_ips_recent_window{user="hello"} 2
```