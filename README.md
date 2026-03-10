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

# Server Metrics 2026-03-10 09:37:37 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 123465.1 (34h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 256059
telemt_connections_bad_total 3443
telemt_handshake_timeouts_total 2617
telemt_upstream_connect_attempt_total 239807
telemt_upstream_connect_success_total 239727
telemt_upstream_connect_fail_total 80
telemt_upstream_connect_attempts_per_request{bucket="1"} 239807
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 221292
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18364
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 71
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 80
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 239715
telemt_user_connections_current{user="hello"} 276
telemt_user_octets_from_client{user="hello"} 5988038885 (5.58 GB)
telemt_user_octets_to_client{user="hello"} 145049160254 (135.09 GB)
telemt_user_msgs_from_client{user="hello"} 5832921
telemt_user_msgs_to_client{user="hello"} 9165340
telemt_user_unique_ips_current{user="hello"} 67
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 123464.2 (34h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 77129
telemt_connections_bad_total 3249
telemt_handshake_timeouts_total 1031
telemt_upstream_connect_attempt_total 68881
telemt_upstream_connect_success_total 68839
telemt_upstream_connect_fail_total 42
telemt_upstream_connect_attempts_per_request{bucket="1"} 68881
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 61938
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6501
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 399
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 42
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 68827
telemt_user_connections_current{user="hello"} 94
telemt_user_octets_from_client{user="hello"} 2319891952 (2.16 GB)
telemt_user_octets_to_client{user="hello"} 32195222216 (29.98 GB)
telemt_user_msgs_from_client{user="hello"} 1896703
telemt_user_msgs_to_client{user="hello"} 9188086
telemt_user_unique_ips_current{user="hello"} 22
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 123464.7 (34h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 110827
telemt_connections_bad_total 1144
telemt_handshake_timeouts_total 5484
telemt_upstream_connect_attempt_total 78485
telemt_upstream_connect_success_total 78483
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 78485
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 69529
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8932
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 78471
telemt_user_connections_current{user="hello"} 92
telemt_user_octets_from_client{user="hello"} 6354284166 (5.92 GB)
telemt_user_octets_to_client{user="hello"} 61905232334 (57.65 GB)
telemt_user_msgs_from_client{user="hello"} 4050166
telemt_user_msgs_to_client{user="hello"} 9924981
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 123459.7 (34h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 112142
telemt_connections_bad_total 958
telemt_handshake_timeouts_total 1311
telemt_upstream_connect_attempt_total 104298
telemt_upstream_connect_success_total 104067
telemt_upstream_connect_fail_total 231
telemt_upstream_connect_attempts_per_request{bucket="1"} 104298
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 92126
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11632
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 60
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 249
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 231
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 104055
telemt_user_connections_current{user="hello"} 131
telemt_user_octets_from_client{user="hello"} 2940328393 (2.74 GB)
telemt_user_octets_to_client{user="hello"} 77547521920 (72.22 GB)
telemt_user_msgs_from_client{user="hello"} 2700277
telemt_user_msgs_to_client{user="hello"} 17686326
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 123464.8 (34h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 171349
telemt_connections_bad_total 27102
telemt_handshake_timeouts_total 4396
telemt_upstream_connect_attempt_total 132634
telemt_upstream_connect_success_total 131828
telemt_upstream_connect_fail_total 806
telemt_upstream_connect_attempts_per_request{bucket="1"} 132634
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 113908
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17729
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 191
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 806
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 131816
telemt_user_connections_current{user="hello"} 130
telemt_user_octets_from_client{user="hello"} 2019873459 (1.88 GB)
telemt_user_octets_to_client{user="hello"} 105222735928 (98.00 GB)
telemt_user_msgs_from_client{user="hello"} 2787901
telemt_user_msgs_to_client{user="hello"} 14267326
telemt_user_unique_ips_current{user="hello"} 45
telemt_user_unique_ips_recent_window{user="hello"} 19
```