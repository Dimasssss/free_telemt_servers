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

# Server Metrics 2026-03-10 04:04:30 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 103478.4 (28h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 189225
telemt_connections_bad_total 2375
telemt_handshake_timeouts_total 1826
telemt_upstream_connect_attempt_total 177436
telemt_upstream_connect_success_total 177380
telemt_upstream_connect_fail_total 56
telemt_upstream_connect_attempts_per_request{bucket="1"} 177436
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 163319
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13997
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 64
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 56
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 177370
telemt_user_connections_current{user="hello"} 236
telemt_user_octets_from_client{user="hello"} 5033670243 (4.69 GB)
telemt_user_octets_to_client{user="hello"} 107536421343 (100.15 GB)
telemt_user_msgs_from_client{user="hello"} 4600774
telemt_user_msgs_to_client{user="hello"} 6767915
telemt_user_unique_ips_current{user="hello"} 59
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 103477.0 (28h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 58385
telemt_connections_bad_total 3135
telemt_handshake_timeouts_total 882
telemt_upstream_connect_attempt_total 51411
telemt_upstream_connect_success_total 51370
telemt_upstream_connect_fail_total 41
telemt_upstream_connect_attempts_per_request{bucket="1"} 51411
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 45987
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5019
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 364
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 41
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 51360
telemt_user_connections_current{user="hello"} 48
telemt_user_octets_from_client{user="hello"} 2151931780 (2.00 GB)
telemt_user_octets_to_client{user="hello"} 24424103041 (22.75 GB)
telemt_user_msgs_from_client{user="hello"} 1580878
telemt_user_msgs_to_client{user="hello"} 7003433
telemt_user_unique_ips_current{user="hello"} 14
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 103477.5 (28h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 77246
telemt_connections_bad_total 980
telemt_handshake_timeouts_total 3965
telemt_upstream_connect_attempt_total 55698
telemt_upstream_connect_success_total 55696
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 55698
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 48953
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6730
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 55686
telemt_user_connections_current{user="hello"} 41
telemt_user_octets_from_client{user="hello"} 6067505480 (5.65 GB)
telemt_user_octets_to_client{user="hello"} 55145924380 (51.36 GB)
telemt_user_msgs_from_client{user="hello"} 3531641
telemt_user_msgs_to_client{user="hello"} 8286332
telemt_user_unique_ips_current{user="hello"} 21
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 103472.5 (28h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 78762
telemt_connections_bad_total 550
telemt_handshake_timeouts_total 1061
telemt_upstream_connect_attempt_total 72961
telemt_upstream_connect_success_total 72794
telemt_upstream_connect_fail_total 167
telemt_upstream_connect_attempts_per_request{bucket="1"} 72961
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 63929
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8653
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 39
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 173
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 167
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 72784
telemt_user_connections_current{user="hello"} 84
telemt_user_octets_from_client{user="hello"} 2329442598 (2.17 GB)
telemt_user_octets_to_client{user="hello"} 50265078410 (46.81 GB)
telemt_user_msgs_from_client{user="hello"} 1955598
telemt_user_msgs_to_client{user="hello"} 12005707
telemt_user_unique_ips_current{user="hello"} 27
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 103477.7 (28h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 130142
telemt_connections_bad_total 22855
telemt_handshake_timeouts_total 3049
telemt_upstream_connect_attempt_total 98945
telemt_upstream_connect_success_total 98928
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 98945
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 84620
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14156
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 152
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 98918
telemt_user_connections_current{user="hello"} 97
telemt_user_octets_from_client{user="hello"} 1631507227 (1.52 GB)
telemt_user_octets_to_client{user="hello"} 90435216029 (84.22 GB)
telemt_user_msgs_from_client{user="hello"} 2234483
telemt_user_msgs_to_client{user="hello"} 12219519
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 15
```