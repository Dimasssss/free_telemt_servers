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

# Server Metrics 2026-03-09 03:07:43 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 13673.2 (3h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10976
telemt_connections_bad_total 22
telemt_handshake_timeouts_total 187
telemt_upstream_connect_attempt_total 10104
telemt_upstream_connect_success_total 10101
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 10104
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9258
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 842
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 10099
telemt_user_connections_current{user="hello"} 135
telemt_user_octets_from_client{user="hello"} 115603300 (110.25 MB)
telemt_user_octets_to_client{user="hello"} 8654319758 (8.06 GB)
telemt_user_msgs_from_client{user="hello"} 231263
telemt_user_msgs_to_client{user="hello"} 363405
telemt_user_unique_ips_current{user="hello"} 33
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 13671.5 (3h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 806
telemt_connections_bad_total 19
telemt_handshake_timeouts_total 7
telemt_upstream_connect_attempt_total 769
telemt_upstream_connect_success_total 769
telemt_upstream_connect_attempts_per_request{bucket="1"} 769
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 737
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 767
telemt_user_connections_current{user="hello"} 19
telemt_user_octets_from_client{user="hello"} 9855438 (9.40 MB)
telemt_user_octets_to_client{user="hello"} 518948030 (494.91 MB)
telemt_user_msgs_from_client{user="hello"} 26790
telemt_user_msgs_to_client{user="hello"} 108104
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 13672.1 (3h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 950
telemt_connections_bad_total 82
telemt_handshake_timeouts_total 3
telemt_upstream_connect_attempt_total 854
telemt_upstream_connect_success_total 854
telemt_upstream_connect_attempts_per_request{bucket="1"} 854
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 691
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 162
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 852
telemt_user_connections_current{user="hello"} 10
telemt_user_octets_from_client{user="hello"} 318334998 (303.59 MB)
telemt_user_octets_to_client{user="hello"} 657995596 (627.51 MB)
telemt_user_msgs_from_client{user="hello"} 129868
telemt_user_msgs_to_client{user="hello"} 121701
telemt_user_unique_ips_current{user="hello"} 4
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 13666.9 (3h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1841
telemt_connections_bad_total 18
telemt_handshake_timeouts_total 201
telemt_upstream_connect_attempt_total 1506
telemt_upstream_connect_success_total 1506
telemt_upstream_connect_attempts_per_request{bucket="1"} 1506
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1129
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 372
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1504
telemt_user_connections_current{user="hello"} 39
telemt_user_octets_from_client{user="hello"} 12328400 (11.76 MB)
telemt_user_octets_to_client{user="hello"} 814980526 (777.23 MB)
telemt_user_msgs_from_client{user="hello"} 31472
telemt_user_msgs_to_client{user="hello"} 230057
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 13672.4 (3h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3715
telemt_connections_bad_total 2487
telemt_handshake_timeouts_total 3
telemt_upstream_connect_attempt_total 1199
telemt_upstream_connect_success_total 1199
telemt_upstream_connect_attempts_per_request{bucket="1"} 1199
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1043
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 156
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1197
telemt_user_connections_current{user="hello"} 9
telemt_user_octets_from_client{user="hello"} 9528231 (9.09 MB)
telemt_user_octets_to_client{user="hello"} 1582064565 (1.47 GB)
telemt_user_msgs_from_client{user="hello"} 25068
telemt_user_msgs_to_client{user="hello"} 190836
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 2
```