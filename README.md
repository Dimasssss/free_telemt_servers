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

# Server Metrics 2026-03-10 12:21:21 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 133289.4 (37h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 295097
telemt_connections_bad_total 3464
telemt_handshake_timeouts_total 3082
telemt_upstream_connect_attempt_total 276219
telemt_upstream_connect_success_total 276067
telemt_upstream_connect_fail_total 152
telemt_upstream_connect_attempts_per_request{bucket="1"} 276219
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 255199
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20781
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 87
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 152
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 276055
telemt_user_connections_current{user="hello"} 311
telemt_user_octets_from_client{user="hello"} 6559287286 (6.11 GB)
telemt_user_octets_to_client{user="hello"} 184227374494 (171.58 GB)
telemt_user_msgs_from_client{user="hello"} 6705008
telemt_user_msgs_to_client{user="hello"} 10854267
telemt_user_unique_ips_current{user="hello"} 72
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 133288.0 (37h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 90229
telemt_connections_bad_total 3270
telemt_handshake_timeouts_total 1266
telemt_upstream_connect_attempt_total 80997
telemt_upstream_connect_success_total 80953
telemt_upstream_connect_fail_total 44
telemt_upstream_connect_attempts_per_request{bucket="1"} 80997
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 72916
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7617
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 419
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 44
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 80939
telemt_user_connections_current{user="hello"} 112
telemt_user_octets_from_client{user="hello"} 2770077854 (2.58 GB)
telemt_user_octets_to_client{user="hello"} 34975992898 (32.57 GB)
telemt_user_msgs_from_client{user="hello"} 2190763
telemt_user_msgs_to_client{user="hello"} 10083767
telemt_user_unique_ips_current{user="hello"} 25
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 133288.4 (37h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 128217
telemt_connections_bad_total 1217
telemt_handshake_timeouts_total 6291
telemt_upstream_connect_attempt_total 94175
telemt_upstream_connect_success_total 94173
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 94175
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 83457
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10689
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 94161
telemt_user_connections_current{user="hello"} 67
telemt_user_octets_from_client{user="hello"} 6600869112 (6.15 GB)
telemt_user_octets_to_client{user="hello"} 66743047752 (62.16 GB)
telemt_user_msgs_from_client{user="hello"} 4367933
telemt_user_msgs_to_client{user="hello"} 11099218
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 133283.2 (37h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 133329
telemt_connections_bad_total 1052
telemt_handshake_timeouts_total 2903
telemt_upstream_connect_attempt_total 122804
telemt_upstream_connect_success_total 122542
telemt_upstream_connect_fail_total 262
telemt_upstream_connect_attempts_per_request{bucket="1"} 122804
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 108826
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13321
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 79
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 316
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 262
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 122528
telemt_user_connections_current{user="hello"} 122
telemt_user_octets_from_client{user="hello"} 3982062771 (3.71 GB)
telemt_user_octets_to_client{user="hello"} 85451105301 (79.58 GB)
telemt_user_msgs_from_client{user="hello"} 3313882
telemt_user_msgs_to_client{user="hello"} 19436728
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 133288.5 (37h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 198023
telemt_connections_bad_total 28924
telemt_handshake_timeouts_total 5290
telemt_upstream_connect_attempt_total 155438
telemt_upstream_connect_success_total 154477
telemt_upstream_connect_fail_total 961
telemt_upstream_connect_attempts_per_request{bucket="1"} 155438
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 133753
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20505
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 219
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 961
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 154463
telemt_user_connections_current{user="hello"} 179
telemt_user_octets_from_client{user="hello"} 3415377102 (3.18 GB)
telemt_user_octets_to_client{user="hello"} 114665418321 (106.79 GB)
telemt_user_msgs_from_client{user="hello"} 3575883
telemt_user_msgs_to_client{user="hello"} 15610027
telemt_user_unique_ips_current{user="hello"} 60
telemt_user_unique_ips_recent_window{user="hello"} 27
```