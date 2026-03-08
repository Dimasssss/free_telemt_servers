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

# Server Metrics 2026-03-08 18:15:37 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 40015.8 (11h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 94477
telemt_connections_bad_total 5046
telemt_handshake_timeouts_total 1241
telemt_upstream_connect_attempt_total 85037
telemt_upstream_connect_success_total 85008
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 85037
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 80031
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4929
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 85002
telemt_user_connections_current{user="hello"} 175
telemt_user_octets_from_client{user="hello"} 2046739419 (1.91 GB)
telemt_user_octets_to_client{user="hello"} 53336289062 (49.67 GB)
telemt_user_msgs_from_client{user="hello"} 2044608
telemt_user_msgs_to_client{user="hello"} 2911674
telemt_user_unique_ips_current{user="hello"} 33
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 40015.0 (11h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 21100
telemt_connections_bad_total 188
telemt_handshake_timeouts_total 127
telemt_upstream_connect_attempt_total 20406
telemt_upstream_connect_success_total 20402
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 20406
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18927
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1360
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 115
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 20398
telemt_user_connections_current{user="hello"} 68
telemt_user_octets_from_client{user="hello"} 721969378 (688.52 MB)
telemt_user_octets_to_client{user="hello"} 19408808515 (18.08 GB)
telemt_user_msgs_from_client{user="hello"} 829328
telemt_user_msgs_to_client{user="hello"} 5317410
telemt_user_unique_ips_current{user="hello"} 16
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 40014.7 (11h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13029
telemt_connections_bad_total 164
telemt_handshake_timeouts_total 686
telemt_upstream_connect_attempt_total 11714
telemt_upstream_connect_success_total 11638
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 11714
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10723
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 843
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 72
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11634
telemt_user_connections_current{user="hello"} 6
telemt_user_octets_from_client{user="hello"} 235459631 (224.55 MB)
telemt_user_octets_to_client{user="hello"} 4183187302 (3.90 GB)
telemt_user_msgs_from_client{user="hello"} 201871
telemt_user_msgs_to_client{user="hello"} 742347
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 40014.6 (11h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16675
telemt_connections_bad_total 173
telemt_handshake_timeouts_total 56
telemt_upstream_connect_attempt_total 15945
telemt_upstream_connect_success_total 15911
telemt_upstream_connect_fail_total 34
telemt_upstream_connect_attempts_per_request{bucket="1"} 15945
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14666
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1167
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 71
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 34
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 15907
telemt_user_connections_current{user="hello"} 26
telemt_user_octets_from_client{user="hello"} 1020907284 (973.61 MB)
telemt_user_octets_to_client{user="hello"} 5761480113 (5.37 GB)
telemt_user_msgs_from_client{user="hello"} 531258
telemt_user_msgs_to_client{user="hello"} 1305024
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 40014.9 (11h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 23608
telemt_connections_bad_total 7591
telemt_handshake_timeouts_total 229
telemt_upstream_connect_attempt_total 15425
telemt_upstream_connect_success_total 15420
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 15425
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12880
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2519
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 15416
telemt_user_connections_current{user="hello"} 50
telemt_user_octets_from_client{user="hello"} 269397668 (256.92 MB)
telemt_user_octets_to_client{user="hello"} 11652417586 (10.85 GB)
telemt_user_msgs_from_client{user="hello"} 364840
telemt_user_msgs_to_client{user="hello"} 1544320
telemt_user_unique_ips_current{user="hello"} 13
telemt_user_unique_ips_recent_window{user="hello"} 8
```