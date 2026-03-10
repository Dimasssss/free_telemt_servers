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

# Server Metrics 2026-03-10 09:06:54 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 121622.2 (33h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 248063
telemt_connections_bad_total 3427
telemt_handshake_timeouts_total 2133
telemt_upstream_connect_attempt_total 232690
telemt_upstream_connect_success_total 232618
telemt_upstream_connect_fail_total 72
telemt_upstream_connect_attempts_per_request{bucket="1"} 232690
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 214609
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17943
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 66
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 72
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 232606
telemt_user_connections_current{user="hello"} 288
telemt_user_octets_from_client{user="hello"} 5781700479 (5.38 GB)
telemt_user_octets_to_client{user="hello"} 138156602636 (128.67 GB)
telemt_user_msgs_from_client{user="hello"} 5624061
telemt_user_msgs_to_client{user="hello"} 8745067
telemt_user_unique_ips_current{user="hello"} 66
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 121621.2 (33h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 74789
telemt_connections_bad_total 3227
telemt_handshake_timeouts_total 1019
telemt_upstream_connect_attempt_total 66683
telemt_upstream_connect_success_total 66641
telemt_upstream_connect_fail_total 42
telemt_upstream_connect_attempts_per_request{bucket="1"} 66683
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 59965
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6279
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 396
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 42
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 66629
telemt_user_connections_current{user="hello"} 61
telemt_user_octets_from_client{user="hello"} 2306552465 (2.15 GB)
telemt_user_octets_to_client{user="hello"} 31542545619 (29.38 GB)
telemt_user_msgs_from_client{user="hello"} 1867907
telemt_user_msgs_to_client{user="hello"} 9004149
telemt_user_unique_ips_current{user="hello"} 23
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 121621.8 (33h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 108119
telemt_connections_bad_total 1141
telemt_handshake_timeouts_total 5086
telemt_upstream_connect_attempt_total 76281
telemt_upstream_connect_success_total 76279
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 76281
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 67559
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8698
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 76267
telemt_user_connections_current{user="hello"} 58
telemt_user_octets_from_client{user="hello"} 6335021360 (5.90 GB)
telemt_user_octets_to_client{user="hello"} 60662026730 (56.50 GB)
telemt_user_msgs_from_client{user="hello"} 3997312
telemt_user_msgs_to_client{user="hello"} 9667716
telemt_user_unique_ips_current{user="hello"} 31
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 121616.6 (33h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 108771
telemt_connections_bad_total 949
telemt_handshake_timeouts_total 1298
telemt_upstream_connect_attempt_total 101060
telemt_upstream_connect_success_total 100837
telemt_upstream_connect_fail_total 223
telemt_upstream_connect_attempts_per_request{bucket="1"} 101060
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 89206
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11335
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 60
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 236
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 223
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 100825
telemt_user_connections_current{user="hello"} 131
telemt_user_octets_from_client{user="hello"} 2876547166 (2.68 GB)
telemt_user_octets_to_client{user="hello"} 74513503821 (69.40 GB)
telemt_user_msgs_from_client{user="hello"} 2618791
telemt_user_msgs_to_client{user="hello"} 16901956
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 121621.9 (33h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 166849
telemt_connections_bad_total 26757
telemt_handshake_timeouts_total 4178
telemt_upstream_connect_attempt_total 128877
telemt_upstream_connect_success_total 128076
telemt_upstream_connect_fail_total 801
telemt_upstream_connect_attempts_per_request{bucket="1"} 128877
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 110513
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17381
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 182
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 801
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 128064
telemt_user_connections_current{user="hello"} 205
telemt_user_octets_from_client{user="hello"} 1987616598 (1.85 GB)
telemt_user_octets_to_client{user="hello"} 104458072953 (97.28 GB)
telemt_user_msgs_from_client{user="hello"} 2731581
telemt_user_msgs_to_client{user="hello"} 14127891
telemt_user_unique_ips_current{user="hello"} 48
telemt_user_unique_ips_recent_window{user="hello"} 23
```