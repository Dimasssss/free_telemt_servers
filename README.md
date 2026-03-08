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

# Server Metrics 2026-03-08 01:59:28 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.10

telemt_uptime_seconds 33258.8 (9h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 47992
telemt_connections_bad_total 4955
telemt_handshake_timeouts_total 271
telemt_upstream_connect_attempt_total 40838
telemt_upstream_connect_success_total 40831
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 40838
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 38726
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2085
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 40827
telemt_user_connections_current{user="hello"} 93
telemt_user_octets_from_client{user="hello"} 2256582203 (2.10 GB)
telemt_user_octets_to_client{user="hello"} 30504923514 (28.41 GB)
telemt_user_msgs_from_client{user="hello"} 1387263
telemt_user_msgs_to_client{user="hello"} 4734488
telemt_user_unique_ips_current{user="hello"} 26
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## psb.hosting

```
telemt 3.3.10

telemt_uptime_seconds 33257.8 (9h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7310
telemt_connections_bad_total 272
telemt_handshake_timeouts_total 18
telemt_upstream_connect_attempt_total 6905
telemt_upstream_connect_success_total 6898
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 6905
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6289
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 559
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 6894
telemt_user_connections_current{user="hello"} 13
telemt_user_octets_from_client{user="hello"} 175762939 (167.62 MB)
telemt_user_octets_to_client{user="hello"} 10528835153 (9.81 GB)
telemt_user_msgs_from_client{user="hello"} 328871
telemt_user_msgs_to_client{user="hello"} 2445594
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## koara.io

```
telemt 3.3.10

telemt_uptime_seconds 33257.6 (9h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4437
telemt_connections_bad_total 219
telemt_handshake_timeouts_total 7
telemt_upstream_connect_attempt_total 4139
telemt_upstream_connect_success_total 4139
telemt_upstream_connect_attempts_per_request{bucket="1"} 4139
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3515
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 622
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4135
telemt_user_connections_current{user="hello"} 3
telemt_user_octets_from_client{user="hello"} 117041360 (111.62 MB)
telemt_user_octets_to_client{user="hello"} 13899550332 (12.94 GB)
telemt_user_msgs_from_client{user="hello"} 208849
telemt_user_msgs_to_client{user="hello"} 2936627
telemt_user_unique_ips_current{user="hello"} 3
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## landvps.ru

```
telemt 3.3.10

telemt_uptime_seconds 33086.0 (9h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12314
telemt_connections_bad_total 171
telemt_handshake_timeouts_total 42
telemt_upstream_connect_attempt_total 11821
telemt_upstream_connect_success_total 11795
telemt_upstream_connect_fail_total 26
telemt_upstream_connect_attempts_per_request{bucket="1"} 11821
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9895
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1832
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 60
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 26
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11791
telemt_user_connections_current{user="hello"} 42
telemt_user_octets_from_client{user="hello"} 308205635 (293.93 MB)
telemt_user_octets_to_client{user="hello"} 10600513960 (9.87 GB)
telemt_user_msgs_from_client{user="hello"} 329931
telemt_user_msgs_to_client{user="hello"} 3110684
telemt_user_unique_ips_current{user="hello"} 8
```

## rdp-onedash.ru

```
telemt 3.3.10

telemt_uptime_seconds 33257.8 (9h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14090
telemt_connections_bad_total 6131
telemt_handshake_timeouts_total 34
telemt_upstream_connect_attempt_total 7728
telemt_upstream_connect_success_total 7720
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 7728
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5963
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1696
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 7716
telemt_user_connections_current{user="hello"} 3
telemt_user_octets_from_client{user="hello"} 1618685899 (1.51 GB)
telemt_user_octets_to_client{user="hello"} 7686876184 (7.16 GB)
telemt_user_msgs_from_client{user="hello"} 800426
telemt_user_msgs_to_client{user="hello"} 1713329
telemt_user_unique_ips_current{user="hello"} 3
```