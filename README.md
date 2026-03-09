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

# Server Metrics 2026-03-09 16:13:43 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 60832.1 (16h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 111146
telemt_connections_bad_total 1656
telemt_handshake_timeouts_total 972
telemt_upstream_connect_attempt_total 103928
telemt_upstream_connect_success_total 103889
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 103928
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 95884
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7946
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 103883
telemt_user_connections_current{user="hello"} 235
telemt_user_octets_from_client{user="hello"} 2669579182 (2.49 GB)
telemt_user_octets_to_client{user="hello"} 54302866863 (50.57 GB)
telemt_user_msgs_from_client{user="hello"} 2523548
telemt_user_msgs_to_client{user="hello"} 3618204
telemt_user_unique_ips_current{user="hello"} 53
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 60831.2 (16h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 28895
telemt_connections_bad_total 220
telemt_handshake_timeouts_total 347
telemt_upstream_connect_attempt_total 27228
telemt_upstream_connect_success_total 27211
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 27228
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24800
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2201
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 210
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 27205
telemt_user_connections_current{user="hello"} 41
telemt_user_octets_from_client{user="hello"} 849532378 (810.18 MB)
telemt_user_octets_to_client{user="hello"} 15374082474 (14.32 GB)
telemt_user_msgs_from_client{user="hello"} 770016
telemt_user_msgs_to_client{user="hello"} 4215523
telemt_user_unique_ips_current{user="hello"} 12
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 60831.9 (16h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 36411
telemt_connections_bad_total 652
telemt_handshake_timeouts_total 1641
telemt_upstream_connect_attempt_total 27286
telemt_upstream_connect_success_total 27286
telemt_upstream_connect_attempts_per_request{bucket="1"} 27286
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24433
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2848
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 27280
telemt_user_connections_current{user="hello"} 48
telemt_user_octets_from_client{user="hello"} 4408059421 (4.11 GB)
telemt_user_octets_to_client{user="hello"} 17459635385 (16.26 GB)
telemt_user_msgs_from_client{user="hello"} 1930302
telemt_user_msgs_to_client{user="hello"} 2304555
telemt_user_unique_ips_current{user="hello"} 21
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 60826.4 (16h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 41307
telemt_connections_bad_total 197
telemt_handshake_timeouts_total 858
telemt_upstream_connect_attempt_total 37934
telemt_upstream_connect_success_total 37839
telemt_upstream_connect_fail_total 95
telemt_upstream_connect_attempts_per_request{bucket="1"} 37934
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32420
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5308
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 18
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 93
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 95
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 37833
telemt_user_connections_current{user="hello"} 94
telemt_user_octets_from_client{user="hello"} 1932830736 (1.80 GB)
telemt_user_octets_to_client{user="hello"} 29737625869 (27.70 GB)
telemt_user_msgs_from_client{user="hello"} 1244394
telemt_user_msgs_to_client{user="hello"} 7651933
telemt_user_unique_ips_current{user="hello"} 26
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 60831.7 (16h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 68942
telemt_connections_bad_total 14722
telemt_handshake_timeouts_total 1590
telemt_upstream_connect_attempt_total 49418
telemt_upstream_connect_success_total 49416
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 49418
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 41687
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7681
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 49410
telemt_user_connections_current{user="hello"} 136
telemt_user_octets_from_client{user="hello"} 831281342 (792.77 MB)
telemt_user_octets_to_client{user="hello"} 51426763271 (47.89 GB)
telemt_user_msgs_from_client{user="hello"} 1144870
telemt_user_msgs_to_client{user="hello"} 6317138
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 12
```