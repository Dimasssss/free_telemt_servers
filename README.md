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

# Server Metrics 2026-03-10 16:47:47 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 8499.5 (2h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 36806
telemt_connections_bad_total 339
telemt_handshake_timeouts_total 1327
telemt_upstream_connect_attempt_total 32935
telemt_upstream_connect_success_total 32926
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 32935
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30311
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2610
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 32924
telemt_user_connections_current{user="hello"} 303
telemt_user_octets_from_client{user="hello"} 1070044792 (1020.47 MB)
telemt_user_octets_to_client{user="hello"} 22614835435 (21.06 GB)
telemt_user_msgs_from_client{user="hello"} 946936
telemt_user_msgs_to_client{user="hello"} 1455808
telemt_user_unique_ips_current{user="hello"} 75
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 8498.7 (2h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12102
telemt_connections_bad_total 98
telemt_handshake_timeouts_total 308
telemt_upstream_connect_attempt_total 10857
telemt_upstream_connect_success_total 10855
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 10857
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9460
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1353
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 42
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 10853
telemt_user_connections_current{user="hello"} 79
telemt_user_octets_from_client{user="hello"} 321565695 (306.67 MB)
telemt_user_octets_to_client{user="hello"} 6430613268 (5.99 GB)
telemt_user_msgs_from_client{user="hello"} 342651
telemt_user_msgs_to_client{user="hello"} 2028993
telemt_user_unique_ips_current{user="hello"} 22
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 8499.1 (2h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19829
telemt_connections_bad_total 9
telemt_handshake_timeouts_total 1583
telemt_upstream_connect_attempt_total 16979
telemt_upstream_connect_success_total 16979
telemt_upstream_connect_attempts_per_request{bucket="1"} 16979
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15115
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1849
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 16977
telemt_user_connections_current{user="hello"} 127
telemt_user_octets_from_client{user="hello"} 146763771 (139.96 MB)
telemt_user_octets_to_client{user="hello"} 8385369636 (7.81 GB)
telemt_user_msgs_from_client{user="hello"} 326023
telemt_user_msgs_to_client{user="hello"} 1845726
telemt_user_unique_ips_current{user="hello"} 52
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 8497.5 (2h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 18496
telemt_connections_bad_total 16
telemt_handshake_timeouts_total 204
telemt_upstream_connect_attempt_total 17600
telemt_upstream_connect_success_total 17549
telemt_upstream_connect_fail_total 51
telemt_upstream_connect_attempts_per_request{bucket="1"} 17600
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15310
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2175
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 62
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 51
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 17547
telemt_user_connections_current{user="hello"} 160
telemt_user_octets_from_client{user="hello"} 260957399 (248.87 MB)
telemt_user_octets_to_client{user="hello"} 17878163070 (16.65 GB)
telemt_user_msgs_from_client{user="hello"} 366812
telemt_user_msgs_to_client{user="hello"} 2927835
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 8498.7 (2h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 26001
telemt_connections_bad_total 1765
telemt_handshake_timeouts_total 510
telemt_upstream_connect_attempt_total 22579
telemt_upstream_connect_success_total 22344
telemt_upstream_connect_fail_total 235
telemt_upstream_connect_attempts_per_request{bucket="1"} 22579
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19773
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2506
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 65
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 235
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 22342
telemt_user_connections_current{user="hello"} 240
telemt_user_octets_from_client{user="hello"} 1216405078 (1.13 GB)
telemt_user_octets_to_client{user="hello"} 16488361992 (15.36 GB)
telemt_user_msgs_from_client{user="hello"} 784217
telemt_user_msgs_to_client{user="hello"} 2244473
telemt_user_unique_ips_current{user="hello"} 61
telemt_user_unique_ips_recent_window{user="hello"} 24
```