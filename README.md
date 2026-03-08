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

# Server Metrics 2026-03-08 19:32:38 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 44636.8 (12h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 102532
telemt_connections_bad_total 5057
telemt_handshake_timeouts_total 1261
telemt_upstream_connect_attempt_total 92904
telemt_upstream_connect_success_total 92872
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 92904
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 87464
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5347
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 92866
telemt_user_connections_current{user="hello"} 202
telemt_user_octets_from_client{user="hello"} 2243597323 (2.09 GB)
telemt_user_octets_to_client{user="hello"} 57971890506 (53.99 GB)
telemt_user_msgs_from_client{user="hello"} 2252970
telemt_user_msgs_to_client{user="hello"} 3161702
telemt_user_unique_ips_current{user="hello"} 41
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 44636.1 (12h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 23706
telemt_connections_bad_total 230
telemt_handshake_timeouts_total 127
telemt_upstream_connect_attempt_total 22940
telemt_upstream_connect_success_total 22935
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 22940
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21323
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1484
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 128
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 22931
telemt_user_connections_current{user="hello"} 43
telemt_user_octets_from_client{user="hello"} 751347473 (716.54 MB)
telemt_user_octets_to_client{user="hello"} 21105131746 (19.66 GB)
telemt_user_msgs_from_client{user="hello"} 891256
telemt_user_msgs_to_client{user="hello"} 5741488
telemt_user_unique_ips_current{user="hello"} 11
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 44635.8 (12h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14111
telemt_connections_bad_total 176
telemt_handshake_timeouts_total 686
telemt_upstream_connect_attempt_total 12775
telemt_upstream_connect_success_total 12699
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 12775
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11693
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 933
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 73
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 12695
telemt_user_connections_current{user="hello"} 20
telemt_user_octets_from_client{user="hello"} 265449920 (253.15 MB)
telemt_user_octets_to_client{user="hello"} 4845773420 (4.51 GB)
telemt_user_msgs_from_client{user="hello"} 225764
telemt_user_msgs_to_client{user="hello"} 841661
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 44635.5 (12h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 18176
telemt_connections_bad_total 184
telemt_handshake_timeouts_total 59
telemt_upstream_connect_attempt_total 17409
telemt_upstream_connect_success_total 17372
telemt_upstream_connect_fail_total 37
telemt_upstream_connect_attempts_per_request{bucket="1"} 17409
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15998
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1290
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 77
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 37
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 17368
telemt_user_connections_current{user="hello"} 64
telemt_user_octets_from_client{user="hello"} 1041566973 (993.32 MB)
telemt_user_octets_to_client{user="hello"} 6244752957 (5.82 GB)
telemt_user_msgs_from_client{user="hello"} 548603
telemt_user_msgs_to_client{user="hello"} 1400676
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 44635.8 (12h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 26365
telemt_connections_bad_total 8431
telemt_handshake_timeouts_total 236
telemt_upstream_connect_attempt_total 17285
telemt_upstream_connect_success_total 17278
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 17285
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14284
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2965
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 17272
telemt_user_connections_current{user="hello"} 25
telemt_user_octets_from_client{user="hello"} 321656640 (306.76 MB)
telemt_user_octets_to_client{user="hello"} 13560294555 (12.63 GB)
telemt_user_msgs_from_client{user="hello"} 428176
telemt_user_msgs_to_client{user="hello"} 1776181
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 2
```