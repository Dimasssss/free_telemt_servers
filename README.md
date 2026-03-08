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

# Server Metrics 2026-03-08 18:31:01 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 40940.0 (11h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 95800
telemt_connections_bad_total 5047
telemt_handshake_timeouts_total 1251
telemt_upstream_connect_attempt_total 86334
telemt_upstream_connect_success_total 86305
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 86334
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 81263
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4993
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 49
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 86299
telemt_user_connections_current{user="hello"} 209
telemt_user_octets_from_client{user="hello"} 2059954263 (1.92 GB)
telemt_user_octets_to_client{user="hello"} 53770532287 (50.08 GB)
telemt_user_msgs_from_client{user="hello"} 2071013
telemt_user_msgs_to_client{user="hello"} 2947463
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 40939.1 (11h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 21536
telemt_connections_bad_total 188
telemt_handshake_timeouts_total 127
telemt_upstream_connect_attempt_total 20842
telemt_upstream_connect_success_total 20837
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 20842
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19348
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1372
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 117
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 20833
telemt_user_connections_current{user="hello"} 44
telemt_user_octets_from_client{user="hello"} 726562919 (692.90 MB)
telemt_user_octets_to_client{user="hello"} 19599544558 (18.25 GB)
telemt_user_msgs_from_client{user="hello"} 838975
telemt_user_msgs_to_client{user="hello"} 5370222
telemt_user_unique_ips_current{user="hello"} 11
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 40938.8 (11h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13302
telemt_connections_bad_total 164
telemt_handshake_timeouts_total 686
telemt_upstream_connect_attempt_total 11986
telemt_upstream_connect_success_total 11910
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 11986
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10984
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 854
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 72
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11906
telemt_user_connections_current{user="hello"} 6
telemt_user_octets_from_client{user="hello"} 240697034 (229.55 MB)
telemt_user_octets_to_client{user="hello"} 4211755179 (3.92 GB)
telemt_user_msgs_from_client{user="hello"} 205121
telemt_user_msgs_to_client{user="hello"} 751406
telemt_user_unique_ips_current{user="hello"} 5
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 40938.7 (11h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16924
telemt_connections_bad_total 173
telemt_handshake_timeouts_total 56
telemt_upstream_connect_attempt_total 16190
telemt_upstream_connect_success_total 16156
telemt_upstream_connect_fail_total 34
telemt_upstream_connect_attempts_per_request{bucket="1"} 16190
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14877
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1198
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 74
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 34
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 16152
telemt_user_connections_current{user="hello"} 31
telemt_user_octets_from_client{user="hello"} 1022297624 (974.94 MB)
telemt_user_octets_to_client{user="hello"} 5822889206 (5.42 GB)
telemt_user_msgs_from_client{user="hello"} 534418
telemt_user_msgs_to_client{user="hello"} 1320602
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 40939.0 (11h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 24102
telemt_connections_bad_total 7762
telemt_handshake_timeouts_total 229
telemt_upstream_connect_attempt_total 15746
telemt_upstream_connect_success_total 15740
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 15746
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13106
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2612
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 15736
telemt_user_connections_current{user="hello"} 16
telemt_user_octets_from_client{user="hello"} 284243918 (271.08 MB)
telemt_user_octets_to_client{user="hello"} 12086980190 (11.26 GB)
telemt_user_msgs_from_client{user="hello"} 379457
telemt_user_msgs_to_client{user="hello"} 1589889
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 2
```