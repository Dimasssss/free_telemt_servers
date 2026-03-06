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

# Server Metrics 2026-03-06 16:22:01 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.4

telemt_uptime_seconds 21603.4 (6h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 51166
telemt_connections_bad_total 3105
telemt_handshake_timeouts_total 215
telemt_upstream_connect_attempt_total 44279
telemt_upstream_connect_success_total 44267
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 44279
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 41780
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2479
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 44265
telemt_user_connections_current{user="hello"} 192
telemt_user_octets_from_client{user="hello"} 2374213202 (2.21 GB)
telemt_user_octets_to_client{user="hello"} 28195330057 (26.26 GB)
telemt_user_msgs_from_client{user="hello"} 1580540
telemt_user_msgs_to_client{user="hello"} 4469914
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## psb.hosting

```
telemt 3.3.4

telemt_uptime_seconds 21602.8 (6h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9610
telemt_connections_bad_total 172
telemt_handshake_timeouts_total 96
telemt_upstream_connect_attempt_total 9116
telemt_upstream_connect_success_total 9098
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 9116
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8460
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 550
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 84
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 9096
telemt_user_connections_current{user="hello"} 42
telemt_user_octets_from_client{user="hello"} 110442885 (105.33 MB)
telemt_user_octets_to_client{user="hello"} 5142228573 (4.79 GB)
telemt_user_msgs_from_client{user="hello"} 188531
telemt_user_msgs_to_client{user="hello"} 1603222
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## koara.io

```
telemt 3.3.4

telemt_uptime_seconds 21602.3 (6h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7881
telemt_connections_bad_total 136
telemt_handshake_timeouts_total 16
telemt_upstream_connect_attempt_total 7591
telemt_upstream_connect_success_total 7589
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 7591
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7164
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 420
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 7587
telemt_user_connections_current{user="hello"} 10
telemt_user_octets_from_client{user="hello"} 114681586 (109.37 MB)
telemt_user_octets_to_client{user="hello"} 4698654810 (4.38 GB)
telemt_user_msgs_from_client{user="hello"} 172272
telemt_user_msgs_to_client{user="hello"} 1104548
telemt_user_unique_ips_current{user="hello"} 9
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## landvps.ru

```
telemt 3.3.4

telemt_uptime_seconds 21601.5 (6h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11390
telemt_connections_bad_total 120
telemt_handshake_timeouts_total 54
telemt_upstream_connect_attempt_total 10570
telemt_upstream_connect_success_total 10533
telemt_upstream_connect_fail_total 37
telemt_upstream_connect_attempts_per_request{bucket="1"} 10570
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9825
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 664
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 39
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 37
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 10531
telemt_user_connections_current{user="hello"} 29
telemt_user_octets_from_client{user="hello"} 147192303 (140.37 MB)
telemt_user_octets_to_client{user="hello"} 3454402520 (3.22 GB)
telemt_user_msgs_from_client{user="hello"} 183880
telemt_user_msgs_to_client{user="hello"} 899107
telemt_user_unique_ips_current{user="hello"} 4
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## rdp-onedash.ru

```
telemt 3.3.4

telemt_uptime_seconds 21602.6 (6h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15796
telemt_connections_bad_total 5446
telemt_handshake_timeouts_total 556
telemt_upstream_connect_attempt_total 9518
telemt_upstream_connect_success_total 9518
telemt_upstream_connect_attempts_per_request{bucket="1"} 9518
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8177
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1330
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 9516
telemt_user_connections_current{user="hello"} 22
telemt_user_octets_from_client{user="hello"} 231810780 (221.07 MB)
telemt_user_octets_to_client{user="hello"} 21056872014 (19.61 GB)
telemt_user_msgs_from_client{user="hello"} 380162
telemt_user_msgs_to_client{user="hello"} 3793552
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 3
```