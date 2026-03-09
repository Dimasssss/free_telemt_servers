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

# Server Metrics 2026-03-09 15:58:24 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 59913.4 (16h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 108580
telemt_connections_bad_total 1655
telemt_handshake_timeouts_total 967
telemt_upstream_connect_attempt_total 101458
telemt_upstream_connect_success_total 101419
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 101458
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 93584
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7776
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 101413
telemt_user_connections_current{user="hello"} 231
telemt_user_octets_from_client{user="hello"} 2602644272 (2.42 GB)
telemt_user_octets_to_client{user="hello"} 52955078993 (49.32 GB)
telemt_user_msgs_from_client{user="hello"} 2459487
telemt_user_msgs_to_client{user="hello"} 3530734
telemt_user_unique_ips_current{user="hello"} 50
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 59912.3 (16h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 27870
telemt_connections_bad_total 219
telemt_handshake_timeouts_total 343
telemt_upstream_connect_attempt_total 26237
telemt_upstream_connect_success_total 26220
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 26237
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23974
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2055
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 191
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 26214
telemt_user_connections_current{user="hello"} 78
telemt_user_octets_from_client{user="hello"} 832721737 (794.15 MB)
telemt_user_octets_to_client{user="hello"} 15049231551 (14.02 GB)
telemt_user_msgs_from_client{user="hello"} 750591
telemt_user_msgs_to_client{user="hello"} 4115253
telemt_user_unique_ips_current{user="hello"} 15
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 59912.8 (16h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 35309
telemt_connections_bad_total 644
telemt_handshake_timeouts_total 1619
telemt_upstream_connect_attempt_total 26263
telemt_upstream_connect_success_total 26262
telemt_upstream_connect_attempts_per_request{bucket="1"} 26262
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23590
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2667
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 26256
telemt_user_connections_current{user="hello"} 60
telemt_user_octets_from_client{user="hello"} 4400744594 (4.10 GB)
telemt_user_octets_to_client{user="hello"} 16568637078 (15.43 GB)
telemt_user_msgs_from_client{user="hello"} 1911938
telemt_user_msgs_to_client{user="hello"} 2216390
telemt_user_unique_ips_current{user="hello"} 27
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 59907.4 (16h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 39516
telemt_connections_bad_total 191
telemt_handshake_timeouts_total 852
telemt_upstream_connect_attempt_total 36332
telemt_upstream_connect_success_total 36240
telemt_upstream_connect_fail_total 92
telemt_upstream_connect_attempts_per_request{bucket="1"} 36332
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31219
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4917
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 16
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 88
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 92
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 36234
telemt_user_connections_current{user="hello"} 108
telemt_user_octets_from_client{user="hello"} 1903752091 (1.77 GB)
telemt_user_octets_to_client{user="hello"} 28925746915 (26.94 GB)
telemt_user_msgs_from_client{user="hello"} 1214514
telemt_user_msgs_to_client{user="hello"} 7489062
telemt_user_unique_ips_current{user="hello"} 25
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 59912.9 (16h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 66958
telemt_connections_bad_total 14367
telemt_handshake_timeouts_total 1577
telemt_upstream_connect_attempt_total 47886
telemt_upstream_connect_success_total 47884
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 47886
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40382
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7458
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 44
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 47878
telemt_user_connections_current{user="hello"} 131
telemt_user_octets_from_client{user="hello"} 806016624 (768.68 MB)
telemt_user_octets_to_client{user="hello"} 49524666310 (46.12 GB)
telemt_user_msgs_from_client{user="hello"} 1102085
telemt_user_msgs_to_client{user="hello"} 6086115
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 19
```