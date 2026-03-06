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

# Server Metrics 2026-03-06 07:12:51 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.2

telemt_uptime_seconds 32250.0 (8h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 87929
telemt_connections_bad_total 51945
telemt_handshake_timeouts_total 2484
telemt_upstream_connect_attempt_total 31621
telemt_upstream_connect_success_total 31617
telemt_upstream_connect_attempts_per_request{bucket="1"} 31613
telemt_upstream_connect_attempts_per_request{bucket="2"} 4
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29700
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1906
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 31613
telemt_user_connections_current{user="hello"} 160
telemt_user_octets_from_client{user="hello"} 445999007 (425.34 MB)
telemt_user_octets_to_client{user="hello"} 28521874793 (26.56 GB)
telemt_user_msgs_from_client{user="hello"} 782770
telemt_user_msgs_to_client{user="hello"} 4274238
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## psb.hosting

```
telemt 3.3.2

telemt_uptime_seconds 32247.7 (8h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4267
telemt_connections_bad_total 160
telemt_handshake_timeouts_total 21
telemt_upstream_connect_attempt_total 4038
telemt_upstream_connect_success_total 4037
telemt_upstream_connect_attempts_per_request{bucket="1"} 4036
telemt_upstream_connect_attempts_per_request{bucket="2"} 1
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3876
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 155
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4033
telemt_user_connections_current{user="hello"} 33
telemt_user_octets_from_client{user="hello"} 82047182 (78.25 MB)
telemt_user_octets_to_client{user="hello"} 2027922778 (1.89 GB)
telemt_user_msgs_from_client{user="hello"} 123672
telemt_user_msgs_to_client{user="hello"} 622002
telemt_user_unique_ips_current{user="hello"} 9
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## koara.io

```
telemt 3.3.2

telemt_uptime_seconds 32248.5 (8h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3803
telemt_connections_bad_total 236
telemt_handshake_timeouts_total 23
telemt_upstream_connect_attempt_total 3508
telemt_upstream_connect_success_total 3508
telemt_upstream_connect_attempts_per_request{bucket="1"} 3508
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3209
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 299
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3504
telemt_user_connections_current{user="hello"} 29
telemt_user_octets_from_client{user="hello"} 70753861 (67.48 MB)
telemt_user_octets_to_client{user="hello"} 3073271884 (2.86 GB)
telemt_user_msgs_from_client{user="hello"} 107083
telemt_user_msgs_to_client{user="hello"} 661846
telemt_user_unique_ips_current{user="hello"} 9
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## landvps.ru

```
telemt 3.3.2

telemt_uptime_seconds 32251.0 (8h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6815
telemt_connections_bad_total 148
telemt_handshake_timeouts_total 313
telemt_upstream_connect_attempt_total 5958
telemt_upstream_connect_success_total 5957
telemt_upstream_connect_attempts_per_request{bucket="1"} 5956
telemt_upstream_connect_attempts_per_request{bucket="2"} 1
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5391
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 532
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 5953
telemt_user_connections_current{user="hello"} 15
telemt_user_octets_from_client{user="hello"} 120440875 (114.86 MB)
telemt_user_octets_to_client{user="hello"} 8330554251 (7.76 GB)
telemt_user_msgs_from_client{user="hello"} 193166
telemt_user_msgs_to_client{user="hello"} 1771893
telemt_user_unique_ips_current{user="hello"} 4
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## rdp-onedash.ru

```
telemt 3.3.2

telemt_uptime_seconds 32250.7 (8h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11583
telemt_connections_bad_total 5927
telemt_handshake_timeouts_total 177
telemt_upstream_connect_attempt_total 5328
telemt_upstream_connect_success_total 5328
telemt_upstream_connect_attempts_per_request{bucket="1"} 5328
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4601
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 718
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 5324
telemt_user_connections_current{user="hello"} 35
telemt_user_octets_from_client{user="hello"} 135062975 (128.81 MB)
telemt_user_octets_to_client{user="hello"} 22430867756 (20.89 GB)
telemt_user_msgs_from_client{user="hello"} 290702
telemt_user_msgs_to_client{user="hello"} 4195447
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 4
```