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

# Server Metrics 2026-03-06 06:16:23 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.2

telemt_uptime_seconds 28862.3 (8h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 81921
telemt_connections_bad_total 51942
telemt_handshake_timeouts_total 2470
telemt_upstream_connect_attempt_total 25753
telemt_upstream_connect_success_total 25749
telemt_upstream_connect_attempts_per_request{bucket="1"} 25745
telemt_upstream_connect_attempts_per_request{bucket="2"} 4
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24170
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1569
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 25745
telemt_user_connections_current{user="hello"} 117
telemt_user_octets_from_client{user="hello"} 377403446 (359.92 MB)
telemt_user_octets_to_client{user="hello"} 22375966359 (20.84 GB)
telemt_user_msgs_from_client{user="hello"} 650388
telemt_user_msgs_to_client{user="hello"} 3388140
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## psb.hosting

```
telemt 3.3.2

telemt_uptime_seconds 28859.8 (8h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3389
telemt_connections_bad_total 148
telemt_handshake_timeouts_total 19
telemt_upstream_connect_attempt_total 3180
telemt_upstream_connect_success_total 3179
telemt_upstream_connect_attempts_per_request{bucket="1"} 3178
telemt_upstream_connect_attempts_per_request{bucket="2"} 1
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3055
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 118
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3175
telemt_user_connections_current{user="hello"} 32
telemt_user_octets_from_client{user="hello"} 64558689 (61.57 MB)
telemt_user_octets_to_client{user="hello"} 1358447514 (1.27 GB)
telemt_user_msgs_from_client{user="hello"} 91986
telemt_user_msgs_to_client{user="hello"} 435080
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## koara.io

```
telemt 3.3.2

telemt_uptime_seconds 28860.3 (8h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2588
telemt_connections_bad_total 221
telemt_handshake_timeouts_total 8
telemt_upstream_connect_attempt_total 2338
telemt_upstream_connect_success_total 2338
telemt_upstream_connect_attempts_per_request{bucket="1"} 2338
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2130
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 208
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2334
telemt_user_connections_current{user="hello"} 22
telemt_user_octets_from_client{user="hello"} 55910084 (53.32 MB)
telemt_user_octets_to_client{user="hello"} 2673250030 (2.49 GB)
telemt_user_msgs_from_client{user="hello"} 82895
telemt_user_msgs_to_client{user="hello"} 567750
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## landvps.ru

```
telemt 3.3.2

telemt_uptime_seconds 28863.1 (8h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4847
telemt_connections_bad_total 142
telemt_handshake_timeouts_total 311
telemt_upstream_connect_attempt_total 4146
telemt_upstream_connect_success_total 4146
telemt_upstream_connect_attempts_per_request{bucket="1"} 4146
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3646
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 472
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4142
telemt_user_connections_current{user="hello"} 19
telemt_user_octets_from_client{user="hello"} 105159676 (100.29 MB)
telemt_user_octets_to_client{user="hello"} 6662897225 (6.21 GB)
telemt_user_msgs_from_client{user="hello"} 158594
telemt_user_msgs_to_client{user="hello"} 1428576
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## rdp-onedash.ru

```
telemt 3.3.2

telemt_uptime_seconds 28862.9 (8h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9850
telemt_connections_bad_total 5282
telemt_handshake_timeouts_total 164
telemt_upstream_connect_attempt_total 4290
telemt_upstream_connect_success_total 4290
telemt_upstream_connect_attempts_per_request{bucket="1"} 4290
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3680
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 604
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4286
telemt_user_connections_current{user="hello"} 36
telemt_user_octets_from_client{user="hello"} 85481753 (81.52 MB)
telemt_user_octets_to_client{user="hello"} 17451349378 (16.25 GB)
telemt_user_msgs_from_client{user="hello"} 217060
telemt_user_msgs_to_client{user="hello"} 3302790
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 3
```