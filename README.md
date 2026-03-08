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

# Server Metrics 2026-03-08 02:04:36 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.10

telemt_uptime_seconds 33566.7 (9h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 48360
telemt_connections_bad_total 4955
telemt_handshake_timeouts_total 272
telemt_upstream_connect_attempt_total 41195
telemt_upstream_connect_success_total 41188
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 41195
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 39073
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2095
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 41184
telemt_user_connections_current{user="hello"} 90
telemt_user_octets_from_client{user="hello"} 2259109187 (2.10 GB)
telemt_user_octets_to_client{user="hello"} 30719878643 (28.61 GB)
telemt_user_msgs_from_client{user="hello"} 1391981
telemt_user_msgs_to_client{user="hello"} 4764914
telemt_user_unique_ips_current{user="hello"} 25
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## psb.hosting

```
telemt 3.3.10

telemt_uptime_seconds 33565.9 (9h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7324
telemt_connections_bad_total 272
telemt_handshake_timeouts_total 18
telemt_upstream_connect_attempt_total 6919
telemt_upstream_connect_success_total 6912
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 6919
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6295
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 567
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 6908
telemt_user_connections_current{user="hello"} 6
telemt_user_octets_from_client{user="hello"} 176051224 (167.90 MB)
telemt_user_octets_to_client{user="hello"} 10536683859 (9.81 GB)
telemt_user_msgs_from_client{user="hello"} 329786
telemt_user_msgs_to_client{user="hello"} 2449282
telemt_user_unique_ips_current{user="hello"} 4
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## koara.io

```
telemt 3.3.10

telemt_uptime_seconds 33565.7 (9h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4449
telemt_connections_bad_total 219
telemt_handshake_timeouts_total 7
telemt_upstream_connect_attempt_total 4151
telemt_upstream_connect_success_total 4151
telemt_upstream_connect_attempts_per_request{bucket="1"} 4151
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3525
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 624
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4147
telemt_user_connections_current{user="hello"} 5
telemt_user_octets_from_client{user="hello"} 117066185 (111.64 MB)
telemt_user_octets_to_client{user="hello"} 13899677256 (12.95 GB)
telemt_user_msgs_from_client{user="hello"} 208920
telemt_user_msgs_to_client{user="hello"} 2936721
telemt_user_unique_ips_current{user="hello"} 2
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## landvps.ru

```
telemt 3.3.10

telemt_uptime_seconds 33394.1 (9h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12367
telemt_connections_bad_total 171
telemt_handshake_timeouts_total 42
telemt_upstream_connect_attempt_total 11872
telemt_upstream_connect_success_total 11846
telemt_upstream_connect_fail_total 26
telemt_upstream_connect_attempts_per_request{bucket="1"} 11872
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9935
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1843
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 60
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 26
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11842
telemt_user_connections_current{user="hello"} 37
telemt_user_octets_from_client{user="hello"} 308585895 (294.29 MB)
telemt_user_octets_to_client{user="hello"} 10610772769 (9.88 GB)
telemt_user_msgs_from_client{user="hello"} 330863
telemt_user_msgs_to_client{user="hello"} 3115090
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## rdp-onedash.ru

```
telemt 3.3.10

telemt_uptime_seconds 33565.9 (9h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14172
telemt_connections_bad_total 6187
telemt_handshake_timeouts_total 35
telemt_upstream_connect_attempt_total 7753
telemt_upstream_connect_success_total 7745
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 7753
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5988
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1696
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 7741
telemt_user_connections_current{user="hello"} 3
telemt_user_octets_from_client{user="hello"} 1618787290 (1.51 GB)
telemt_user_octets_to_client{user="hello"} 7689920208 (7.16 GB)
telemt_user_msgs_from_client{user="hello"} 800568
telemt_user_msgs_to_client{user="hello"} 1714045
telemt_user_unique_ips_current{user="hello"} 3
```