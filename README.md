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

# Server Metrics 2026-03-06 15:25:33 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.4

telemt_uptime_seconds 18216.1 (5h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 43254
telemt_connections_bad_total 3088
telemt_handshake_timeouts_total 172
telemt_upstream_connect_attempt_total 36620
telemt_upstream_connect_success_total 36610
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 36620
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34626
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1977
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 36608
telemt_user_connections_current{user="hello"} 149
telemt_user_octets_from_client{user="hello"} 2036953367 (1.90 GB)
telemt_user_octets_to_client{user="hello"} 23438762520 (21.83 GB)
telemt_user_msgs_from_client{user="hello"} 1340498
telemt_user_msgs_to_client{user="hello"} 3715520
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## psb.hosting

```
telemt 3.3.4

telemt_uptime_seconds 18215.5 (5h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8090
telemt_connections_bad_total 167
telemt_handshake_timeouts_total 94
telemt_upstream_connect_attempt_total 7613
telemt_upstream_connect_success_total 7595
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 7613
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7070
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 444
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 80
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 7593
telemt_user_connections_current{user="hello"} 57
telemt_user_octets_from_client{user="hello"} 88245568 (84.16 MB)
telemt_user_octets_to_client{user="hello"} 4688609197 (4.37 GB)
telemt_user_msgs_from_client{user="hello"} 160933
telemt_user_msgs_to_client{user="hello"} 1466063
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## koara.io

```
telemt 3.3.4

telemt_uptime_seconds 18214.6 (5h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6823
telemt_connections_bad_total 66
telemt_handshake_timeouts_total 15
telemt_upstream_connect_attempt_total 6614
telemt_upstream_connect_success_total 6613
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 6614
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6249
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 359
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 6611
telemt_user_connections_current{user="hello"} 8
telemt_user_octets_from_client{user="hello"} 96689523 (92.21 MB)
telemt_user_octets_to_client{user="hello"} 4168536526 (3.88 GB)
telemt_user_msgs_from_client{user="hello"} 146338
telemt_user_msgs_to_client{user="hello"} 975741
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## landvps.ru

```
telemt 3.3.4

telemt_uptime_seconds 18214.1 (5h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9733
telemt_connections_bad_total 112
telemt_handshake_timeouts_total 42
telemt_upstream_connect_attempt_total 9004
telemt_upstream_connect_success_total 8974
telemt_upstream_connect_fail_total 30
telemt_upstream_connect_attempts_per_request{bucket="1"} 9004
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8424
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 511
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 34
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 30
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 8972
telemt_user_connections_current{user="hello"} 40
telemt_user_octets_from_client{user="hello"} 136767939 (130.43 MB)
telemt_user_octets_to_client{user="hello"} 3084102363 (2.87 GB)
telemt_user_msgs_from_client{user="hello"} 162386
telemt_user_msgs_to_client{user="hello"} 793951
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## rdp-onedash.ru

```
telemt 3.3.4

telemt_uptime_seconds 18215.3 (5h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13623
telemt_connections_bad_total 4800
telemt_handshake_timeouts_total 538
telemt_upstream_connect_attempt_total 8066
telemt_upstream_connect_success_total 8066
telemt_upstream_connect_attempts_per_request{bucket="1"} 8066
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7005
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1054
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 8064
telemt_user_connections_current{user="hello"} 24
telemt_user_octets_from_client{user="hello"} 210820599 (201.05 MB)
telemt_user_octets_to_client{user="hello"} 19456834410 (18.12 GB)
telemt_user_msgs_from_client{user="hello"} 339480
telemt_user_msgs_to_client{user="hello"} 3480782
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 2
```