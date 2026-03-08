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

# Server Metrics 2026-03-08 13:53:40 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 24298.2 (6h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 54372
telemt_connections_bad_total 2664
telemt_handshake_timeouts_total 325
telemt_upstream_connect_attempt_total 49246
telemt_upstream_connect_success_total 49224
telemt_upstream_connect_fail_total 22
telemt_upstream_connect_attempts_per_request{bucket="1"} 49246
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 46387
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2816
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 49220
telemt_user_connections_current{user="hello"} 189
telemt_user_octets_from_client{user="hello"} 1433783273 (1.34 GB)
telemt_user_octets_to_client{user="hello"} 23228604809 (21.63 GB)
telemt_user_msgs_from_client{user="hello"} 1181427
telemt_user_msgs_to_client{user="hello"} 1443795
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 24297.5 (6h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12253
telemt_connections_bad_total 89
telemt_handshake_timeouts_total 110
telemt_upstream_connect_attempt_total 11811
telemt_upstream_connect_success_total 11810
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 11811
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10966
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 774
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 70
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11806
telemt_user_connections_current{user="hello"} 19
telemt_user_octets_from_client{user="hello"} 465261226 (443.71 MB)
telemt_user_octets_to_client{user="hello"} 7825242736 (7.29 GB)
telemt_user_msgs_from_client{user="hello"} 408784
telemt_user_msgs_to_client{user="hello"} 2006611
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 24297.3 (6h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8303
telemt_connections_bad_total 137
telemt_handshake_timeouts_total 34
telemt_upstream_connect_attempt_total 7843
telemt_upstream_connect_success_total 7768
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 7843
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7238
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 466
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 64
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 7764
telemt_user_connections_current{user="hello"} 8
telemt_user_octets_from_client{user="hello"} 196451276 (187.35 MB)
telemt_user_octets_to_client{user="hello"} 2178315553 (2.03 GB)
telemt_user_msgs_from_client{user="hello"} 129488
telemt_user_msgs_to_client{user="hello"} 382254
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 24297.2 (6h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10697
telemt_connections_bad_total 146
telemt_handshake_timeouts_total 45
telemt_upstream_connect_attempt_total 10237
telemt_upstream_connect_success_total 10216
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 10237
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9473
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 696
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 10214
telemt_user_connections_current{user="hello"} 34
telemt_user_octets_from_client{user="hello"} 920438945 (877.80 MB)
telemt_user_octets_to_client{user="hello"} 4139314764 (3.86 GB)
telemt_user_msgs_from_client{user="hello"} 431937
telemt_user_msgs_to_client{user="hello"} 912279
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 24297.3 (6h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13866
telemt_connections_bad_total 4500
telemt_handshake_timeouts_total 40
telemt_upstream_connect_attempt_total 9111
telemt_upstream_connect_success_total 9107
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 9111
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7431
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1668
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 9103
telemt_user_connections_current{user="hello"} 13
telemt_user_octets_from_client{user="hello"} 217414235 (207.34 MB)
telemt_user_octets_to_client{user="hello"} 7753489734 (7.22 GB)
telemt_user_msgs_from_client{user="hello"} 248380
telemt_user_msgs_to_client{user="hello"} 1064307
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 2
```