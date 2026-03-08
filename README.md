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

# Server Metrics 2026-03-08 16:38:03 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 34161.9 (9h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 82449
telemt_connections_bad_total 5039
telemt_handshake_timeouts_total 1098
telemt_upstream_connect_attempt_total 73522
telemt_upstream_connect_success_total 73497
telemt_upstream_connect_fail_total 25
telemt_upstream_connect_attempts_per_request{bucket="1"} 73522
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 69109
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4351
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 25
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 73493
telemt_user_connections_current{user="hello"} 219
telemt_user_octets_from_client{user="hello"} 1892182449 (1.76 GB)
telemt_user_octets_to_client{user="hello"} 40406426208 (37.63 GB)
telemt_user_msgs_from_client{user="hello"} 1748068
telemt_user_msgs_to_client{user="hello"} 2411850
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 34160.4 (9h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 17668
telemt_connections_bad_total 143
telemt_handshake_timeouts_total 122
telemt_upstream_connect_attempt_total 17088
telemt_upstream_connect_success_total 17085
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 17088
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15785
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1210
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 17081
telemt_user_connections_current{user="hello"} 41
telemt_user_octets_from_client{user="hello"} 639960281 (610.31 MB)
telemt_user_octets_to_client{user="hello"} 17533523397 (16.33 GB)
telemt_user_msgs_from_client{user="hello"} 691851
telemt_user_msgs_to_client{user="hello"} 4747040
telemt_user_unique_ips_current{user="hello"} 16
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 34160.2 (9h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10836
telemt_connections_bad_total 150
telemt_handshake_timeouts_total 36
telemt_upstream_connect_attempt_total 10201
telemt_upstream_connect_success_total 10125
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 10201
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9353
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 700
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 72
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 10121
telemt_user_connections_current{user="hello"} 10
telemt_user_octets_from_client{user="hello"} 223087830 (212.75 MB)
telemt_user_octets_to_client{user="hello"} 3605051491 (3.36 GB)
telemt_user_msgs_from_client{user="hello"} 175797
telemt_user_msgs_to_client{user="hello"} 625688
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 34160.1 (9h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14691
telemt_connections_bad_total 165
telemt_handshake_timeouts_total 55
telemt_upstream_connect_attempt_total 13998
telemt_upstream_connect_success_total 13967
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 13998
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12890
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1007
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 64
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 13963
telemt_user_connections_current{user="hello"} 29
telemt_user_octets_from_client{user="hello"} 1003751427 (957.25 MB)
telemt_user_octets_to_client{user="hello"} 5111491020 (4.76 GB)
telemt_user_msgs_from_client{user="hello"} 502223
telemt_user_msgs_to_client{user="hello"} 1151730
telemt_user_unique_ips_current{user="hello"} 4
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 34160.3 (9h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19431
telemt_connections_bad_total 6303
telemt_handshake_timeouts_total 188
telemt_upstream_connect_attempt_total 12644
telemt_upstream_connect_success_total 12640
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 12644
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10619
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2009
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 12636
telemt_user_connections_current{user="hello"} 36
telemt_user_octets_from_client{user="hello"} 247612468 (236.14 MB)
telemt_user_octets_to_client{user="hello"} 10712083499 (9.98 GB)
telemt_user_msgs_from_client{user="hello"} 319441
telemt_user_msgs_to_client{user="hello"} 1390469
telemt_user_unique_ips_current{user="hello"} 12
telemt_user_unique_ips_recent_window{user="hello"} 7
```