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

# Server Metrics 2026-03-09 17:15:12 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 64521.1 (17h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 119948
telemt_connections_bad_total 1661
telemt_handshake_timeouts_total 999
telemt_upstream_connect_attempt_total 112356
telemt_upstream_connect_success_total 112316
telemt_upstream_connect_fail_total 40
telemt_upstream_connect_attempts_per_request{bucket="1"} 112356
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 103678
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8579
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 40
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 112310
telemt_user_connections_current{user="hello"} 171
telemt_user_octets_from_client{user="hello"} 2986930780 (2.78 GB)
telemt_user_octets_to_client{user="hello"} 61647176730 (57.41 GB)
telemt_user_msgs_from_client{user="hello"} 2802584
telemt_user_msgs_to_client{user="hello"} 3964865
telemt_user_unique_ips_current{user="hello"} 41
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 64520.4 (17h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 32889
telemt_connections_bad_total 224
telemt_handshake_timeouts_total 363
telemt_upstream_connect_attempt_total 31009
telemt_upstream_connect_success_total 30991
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 31009
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28021
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2719
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 251
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 30985
telemt_user_connections_current{user="hello"} 71
telemt_user_octets_from_client{user="hello"} 1014581417 (967.58 MB)
telemt_user_octets_to_client{user="hello"} 16328610679 (15.21 GB)
telemt_user_msgs_from_client{user="hello"} 874760
telemt_user_msgs_to_client{user="hello"} 4565253
telemt_user_unique_ips_current{user="hello"} 17
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 64520.9 (17h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 41955
telemt_connections_bad_total 658
telemt_handshake_timeouts_total 1895
telemt_upstream_connect_attempt_total 32255
telemt_upstream_connect_success_total 32255
telemt_upstream_connect_attempts_per_request{bucket="1"} 32255
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28709
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3540
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 32247
telemt_user_connections_current{user="hello"} 58
telemt_user_octets_from_client{user="hello"} 4489902834 (4.18 GB)
telemt_user_octets_to_client{user="hello"} 19460840351 (18.12 GB)
telemt_user_msgs_from_client{user="hello"} 2026157
telemt_user_msgs_to_client{user="hello"} 2647336
telemt_user_unique_ips_current{user="hello"} 24
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 64515.3 (17h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 47584
telemt_connections_bad_total 199
telemt_handshake_timeouts_total 891
telemt_upstream_connect_attempt_total 43468
telemt_upstream_connect_success_total 43364
telemt_upstream_connect_fail_total 104
telemt_upstream_connect_attempts_per_request{bucket="1"} 43468
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37210
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6025
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 24
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 105
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 104
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 43356
telemt_user_connections_current{user="hello"} 111
telemt_user_octets_from_client{user="hello"} 1990601077 (1.85 GB)
telemt_user_octets_to_client{user="hello"} 32409774476 (30.18 GB)
telemt_user_msgs_from_client{user="hello"} 1332487
telemt_user_msgs_to_client{user="hello"} 8189774
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 64520.8 (17h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 76806
telemt_connections_bad_total 15528
telemt_handshake_timeouts_total 1731
telemt_upstream_connect_attempt_total 56055
telemt_upstream_connect_success_total 56053
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 56055
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 47416
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8584
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 56045
telemt_user_connections_current{user="hello"} 100
telemt_user_octets_from_client{user="hello"} 937556257 (894.12 MB)
telemt_user_octets_to_client{user="hello"} 56516766945 (52.64 GB)
telemt_user_msgs_from_client{user="hello"} 1290847
telemt_user_msgs_to_client{user="hello"} 7044950
telemt_user_unique_ips_current{user="hello"} 31
telemt_user_unique_ips_recent_window{user="hello"} 17
```