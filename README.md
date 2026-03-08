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

# Server Metrics 2026-03-08 18:00:13 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 39091.7 (10h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 92576
telemt_connections_bad_total 5045
telemt_handshake_timeouts_total 1239
telemt_upstream_connect_attempt_total 83194
telemt_upstream_connect_success_total 83165
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 83194
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 78250
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4869
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 83159
telemt_user_connections_current{user="hello"} 247
telemt_user_octets_from_client{user="hello"} 2028040031 (1.89 GB)
telemt_user_octets_to_client{user="hello"} 51502797584 (47.97 GB)
telemt_user_msgs_from_client{user="hello"} 2001395
telemt_user_msgs_to_client{user="hello"} 2841914
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 39091.1 (10h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20599
telemt_connections_bad_total 188
telemt_handshake_timeouts_total 127
telemt_upstream_connect_attempt_total 19906
telemt_upstream_connect_success_total 19902
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 19906
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18439
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1349
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 114
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 19898
telemt_user_connections_current{user="hello"} 56
telemt_user_octets_from_client{user="hello"} 714272716 (681.18 MB)
telemt_user_octets_to_client{user="hello"} 19072831478 (17.76 GB)
telemt_user_msgs_from_client{user="hello"} 815669
telemt_user_msgs_to_client{user="hello"} 5232337
telemt_user_unique_ips_current{user="hello"} 14
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 39090.4 (10h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12925
telemt_connections_bad_total 164
telemt_handshake_timeouts_total 686
telemt_upstream_connect_attempt_total 11610
telemt_upstream_connect_success_total 11534
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 11610
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10625
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 837
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 72
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11530
telemt_user_connections_current{user="hello"} 6
telemt_user_octets_from_client{user="hello"} 235095307 (224.20 MB)
telemt_user_octets_to_client{user="hello"} 4172430632 (3.89 GB)
telemt_user_msgs_from_client{user="hello"} 200907
telemt_user_msgs_to_client{user="hello"} 739178
telemt_user_unique_ips_current{user="hello"} 3
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 39090.4 (10h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16345
telemt_connections_bad_total 173
telemt_handshake_timeouts_total 56
telemt_upstream_connect_attempt_total 15620
telemt_upstream_connect_success_total 15586
telemt_upstream_connect_fail_total 34
telemt_upstream_connect_attempts_per_request{bucket="1"} 15620
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14379
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1130
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 70
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 34
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 15582
telemt_user_connections_current{user="hello"} 44
telemt_user_octets_from_client{user="hello"} 1018271167 (971.10 MB)
telemt_user_octets_to_client{user="hello"} 5728467447 (5.34 GB)
telemt_user_msgs_from_client{user="hello"} 528182
telemt_user_msgs_to_client{user="hello"} 1292443
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 39090.7 (10h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 22939
telemt_connections_bad_total 7421
telemt_handshake_timeouts_total 228
telemt_upstream_connect_attempt_total 14936
telemt_upstream_connect_success_total 14931
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 14936
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12504
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2406
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 14927
telemt_user_connections_current{user="hello"} 25
telemt_user_octets_from_client{user="hello"} 265282276 (252.99 MB)
telemt_user_octets_to_client{user="hello"} 11433874461 (10.65 GB)
telemt_user_msgs_from_client{user="hello"} 356631
telemt_user_msgs_to_client{user="hello"} 1512500
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 3
```