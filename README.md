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

# Server Metrics 2026-03-10 15:05:10 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 2342.4 (0h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11942
telemt_connections_bad_total 176
telemt_handshake_timeouts_total 46
telemt_upstream_connect_attempt_total 11178
telemt_upstream_connect_success_total 11177
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 11178
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10329
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 847
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11175
telemt_user_connections_current{user="hello"} 407
telemt_user_octets_from_client{user="hello"} 129324467 (123.33 MB)
telemt_user_octets_to_client{user="hello"} 5729159542 (5.34 GB)
telemt_user_msgs_from_client{user="hello"} 203881
telemt_user_msgs_to_client{user="hello"} 345644
telemt_user_unique_ips_current{user="hello"} 85
telemt_user_unique_ips_recent_window{user="hello"} 40
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 2342.0 (0h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3288
telemt_connections_bad_total 1
telemt_handshake_timeouts_total 71
telemt_upstream_connect_attempt_total 3064
telemt_upstream_connect_success_total 3064
telemt_upstream_connect_attempts_per_request{bucket="1"} 3064
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2711
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 347
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3062
telemt_user_connections_current{user="hello"} 106
telemt_user_octets_from_client{user="hello"} 48400572 (46.16 MB)
telemt_user_octets_to_client{user="hello"} 2858167818 (2.66 GB)
telemt_user_msgs_from_client{user="hello"} 89652
telemt_user_msgs_to_client{user="hello"} 853536
telemt_user_unique_ips_current{user="hello"} 26
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 2341.2 (0h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5359
telemt_connections_bad_total 4
telemt_handshake_timeouts_total 186
telemt_upstream_connect_attempt_total 4928
telemt_upstream_connect_success_total 4928
telemt_upstream_connect_attempts_per_request{bucket="1"} 4928
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4509
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 419
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4926
telemt_user_connections_current{user="hello"} 81
telemt_user_octets_from_client{user="hello"} 38162946 (36.40 MB)
telemt_user_octets_to_client{user="hello"} 603790066 (575.82 MB)
telemt_user_msgs_from_client{user="hello"} 69614
telemt_user_msgs_to_client{user="hello"} 183596
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 2340.1 (0h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5077
telemt_connections_bad_total 4
telemt_handshake_timeouts_total 109
telemt_upstream_connect_attempt_total 4779
telemt_upstream_connect_success_total 4766
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 4779
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4134
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 616
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4764
telemt_user_connections_current{user="hello"} 223
telemt_user_octets_from_client{user="hello"} 82612759 (78.79 MB)
telemt_user_octets_to_client{user="hello"} 3250380646 (3.03 GB)
telemt_user_msgs_from_client{user="hello"} 95701
telemt_user_msgs_to_client{user="hello"} 574143
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 2341.4 (0h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7624
telemt_connections_bad_total 665
telemt_handshake_timeouts_total 167
telemt_upstream_connect_attempt_total 6522
telemt_upstream_connect_success_total 6520
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 6522
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5776
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 733
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 6518
telemt_user_connections_current{user="hello"} 266
telemt_user_octets_from_client{user="hello"} 134660793 (128.42 MB)
telemt_user_octets_to_client{user="hello"} 2567035208 (2.39 GB)
telemt_user_msgs_from_client{user="hello"} 136978
telemt_user_msgs_to_client{user="hello"} 372958
telemt_user_unique_ips_current{user="hello"} 70
telemt_user_unique_ips_recent_window{user="hello"} 24
```