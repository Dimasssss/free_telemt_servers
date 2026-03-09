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

# Server Metrics 2026-03-09 17:45:52 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 66361.2 (18h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 124695
telemt_connections_bad_total 1664
telemt_handshake_timeouts_total 1057
telemt_upstream_connect_attempt_total 116774
telemt_upstream_connect_success_total 116732
telemt_upstream_connect_fail_total 42
telemt_upstream_connect_attempts_per_request{bucket="1"} 116774
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 107642
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9031
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 42
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 116724
telemt_user_connections_current{user="hello"} 214
telemt_user_octets_from_client{user="hello"} 3203008225 (2.98 GB)
telemt_user_octets_to_client{user="hello"} 63149502165 (58.81 GB)
telemt_user_msgs_from_client{user="hello"} 2934867
telemt_user_msgs_to_client{user="hello"} 4070384
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 66359.9 (18h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 34811
telemt_connections_bad_total 232
telemt_handshake_timeouts_total 413
telemt_upstream_connect_attempt_total 32742
telemt_upstream_connect_success_total 32723
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 32742
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29524
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2930
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 269
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 32717
telemt_user_connections_current{user="hello"} 78
telemt_user_octets_from_client{user="hello"} 1045615252 (997.18 MB)
telemt_user_octets_to_client{user="hello"} 16929503665 (15.77 GB)
telemt_user_msgs_from_client{user="hello"} 910939
telemt_user_msgs_to_client{user="hello"} 4762770
telemt_user_unique_ips_current{user="hello"} 18
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 66360.3 (18h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 44421
telemt_connections_bad_total 691
telemt_handshake_timeouts_total 2036
telemt_upstream_connect_attempt_total 34409
telemt_upstream_connect_success_total 34409
telemt_upstream_connect_attempts_per_request{bucket="1"} 34409
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30610
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3793
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 34401
telemt_user_connections_current{user="hello"} 77
telemt_user_octets_from_client{user="hello"} 4607370520 (4.29 GB)
telemt_user_octets_to_client{user="hello"} 24253195549 (22.59 GB)
telemt_user_msgs_from_client{user="hello"} 2126546
telemt_user_msgs_to_client{user="hello"} 3233302
telemt_user_unique_ips_current{user="hello"} 28
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 66355.3 (18h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 50063
telemt_connections_bad_total 238
telemt_handshake_timeouts_total 906
telemt_upstream_connect_attempt_total 45619
telemt_upstream_connect_success_total 45508
telemt_upstream_connect_fail_total 111
telemt_upstream_connect_attempts_per_request{bucket="1"} 45619
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 39153
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6219
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 26
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 110
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 111
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 45500
telemt_user_connections_current{user="hello"} 103
telemt_user_octets_from_client{user="hello"} 2071225638 (1.93 GB)
telemt_user_octets_to_client{user="hello"} 33902827941 (31.57 GB)
telemt_user_msgs_from_client{user="hello"} 1404597
telemt_user_msgs_to_client{user="hello"} 8482765
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 66360.6 (18h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 80720
telemt_connections_bad_total 15856
telemt_handshake_timeouts_total 2110
telemt_upstream_connect_attempt_total 59092
telemt_upstream_connect_success_total 59090
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 59092
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 50095
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8941
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 59082
telemt_user_connections_current{user="hello"} 119
telemt_user_octets_from_client{user="hello"} 964326862 (919.65 MB)
telemt_user_octets_to_client{user="hello"} 57638610086 (53.68 GB)
telemt_user_msgs_from_client{user="hello"} 1352145
telemt_user_msgs_to_client{user="hello"} 7309306
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 13
```