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

# Server Metrics 2026-03-08 19:53:11 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 45869.8 (12h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 104941
telemt_connections_bad_total 5066
telemt_handshake_timeouts_total 1273
telemt_upstream_connect_attempt_total 95237
telemt_upstream_connect_success_total 95204
telemt_upstream_connect_fail_total 33
telemt_upstream_connect_attempts_per_request{bucket="1"} 95237
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 89663
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5479
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 62
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 95198
telemt_user_connections_current{user="hello"} 193
telemt_user_octets_from_client{user="hello"} 2279460736 (2.12 GB)
telemt_user_octets_to_client{user="hello"} 60102817468 (55.98 GB)
telemt_user_msgs_from_client{user="hello"} 2309181
telemt_user_msgs_to_client{user="hello"} 3244949
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 45868.4 (12h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 24356
telemt_connections_bad_total 232
telemt_handshake_timeouts_total 129
telemt_upstream_connect_attempt_total 23567
telemt_upstream_connect_success_total 23562
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 23567
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21924
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1505
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 133
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 23558
telemt_user_connections_current{user="hello"} 38
telemt_user_octets_from_client{user="hello"} 793251589 (756.50 MB)
telemt_user_octets_to_client{user="hello"} 21384323181 (19.92 GB)
telemt_user_msgs_from_client{user="hello"} 915399
telemt_user_msgs_to_client{user="hello"} 5805411
telemt_user_unique_ips_current{user="hello"} 10
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 45868.3 (12h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14335
telemt_connections_bad_total 178
telemt_handshake_timeouts_total 686
telemt_upstream_connect_attempt_total 12998
telemt_upstream_connect_success_total 12922
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 12998
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11897
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 951
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 74
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 12916
telemt_user_connections_current{user="hello"} 15
telemt_user_octets_from_client{user="hello"} 418355983 (398.98 MB)
telemt_user_octets_to_client{user="hello"} 5432366343 (5.06 GB)
telemt_user_msgs_from_client{user="hello"} 288012
telemt_user_msgs_to_client{user="hello"} 905557
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 45868.1 (12h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 18729
telemt_connections_bad_total 186
telemt_handshake_timeouts_total 59
telemt_upstream_connect_attempt_total 17921
telemt_upstream_connect_success_total 17884
telemt_upstream_connect_fail_total 37
telemt_upstream_connect_attempts_per_request{bucket="1"} 17921
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16480
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1318
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 78
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 37
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 17880
telemt_user_connections_current{user="hello"} 41
telemt_user_octets_from_client{user="hello"} 1057638416 (1008.64 MB)
telemt_user_octets_to_client{user="hello"} 6287680854 (5.86 GB)
telemt_user_msgs_from_client{user="hello"} 557538
telemt_user_msgs_to_client{user="hello"} 1413663
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 45868.4 (12h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 27069
telemt_connections_bad_total 8659
telemt_handshake_timeouts_total 237
telemt_upstream_connect_attempt_total 17753
telemt_upstream_connect_success_total 17746
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 17753
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14636
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3077
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 17740
telemt_user_connections_current{user="hello"} 32
telemt_user_octets_from_client{user="hello"} 334742949 (319.24 MB)
telemt_user_octets_to_client{user="hello"} 15243386394 (14.20 GB)
telemt_user_msgs_from_client{user="hello"} 459141
telemt_user_msgs_to_client{user="hello"} 1983112
telemt_user_unique_ips_current{user="hello"} 11
telemt_user_unique_ips_recent_window{user="hello"} 2
```