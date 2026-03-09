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

# Server Metrics 2026-03-09 15:43:06 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 58995.6 (16h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 106335
telemt_connections_bad_total 1655
telemt_handshake_timeouts_total 957
telemt_upstream_connect_attempt_total 99268
telemt_upstream_connect_success_total 99230
telemt_upstream_connect_fail_total 38
telemt_upstream_connect_attempts_per_request{bucket="1"} 99268
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 91575
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7596
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 38
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 99224
telemt_user_connections_current{user="hello"} 238
telemt_user_octets_from_client{user="hello"} 2575848781 (2.40 GB)
telemt_user_octets_to_client{user="hello"} 51828535276 (48.27 GB)
telemt_user_msgs_from_client{user="hello"} 2409258
telemt_user_msgs_to_client{user="hello"} 3449800
telemt_user_unique_ips_current{user="hello"} 47
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 58994.1 (16h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 27235
telemt_connections_bad_total 213
telemt_handshake_timeouts_total 330
telemt_upstream_connect_attempt_total 25630
telemt_upstream_connect_success_total 25613
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 25630
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23449
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1982
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 182
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 25607
telemt_user_connections_current{user="hello"} 55
telemt_user_octets_from_client{user="hello"} 827964391 (789.61 MB)
telemt_user_octets_to_client{user="hello"} 14701747785 (13.69 GB)
telemt_user_msgs_from_client{user="hello"} 737926
telemt_user_msgs_to_client{user="hello"} 4014886
telemt_user_unique_ips_current{user="hello"} 11
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 58995.6 (16h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 33937
telemt_connections_bad_total 644
telemt_handshake_timeouts_total 1591
telemt_upstream_connect_attempt_total 24981
telemt_upstream_connect_success_total 24981
telemt_upstream_connect_attempts_per_request{bucket="1"} 24981
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22479
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2497
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 24975
telemt_user_connections_current{user="hello"} 45
telemt_user_octets_from_client{user="hello"} 4393290061 (4.09 GB)
telemt_user_octets_to_client{user="hello"} 15775277088 (14.69 GB)
telemt_user_msgs_from_client{user="hello"} 1894949
telemt_user_msgs_to_client{user="hello"} 2153399
telemt_user_unique_ips_current{user="hello"} 21
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 58989.6 (16h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 38143
telemt_connections_bad_total 191
telemt_handshake_timeouts_total 835
telemt_upstream_connect_attempt_total 35032
telemt_upstream_connect_success_total 34941
telemt_upstream_connect_fail_total 91
telemt_upstream_connect_attempts_per_request{bucket="1"} 35032
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30219
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4619
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 16
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 87
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 91
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 34935
telemt_user_connections_current{user="hello"} 110
telemt_user_octets_from_client{user="hello"} 1875858769 (1.75 GB)
telemt_user_octets_to_client{user="hello"} 27554387909 (25.66 GB)
telemt_user_msgs_from_client{user="hello"} 1177150
telemt_user_msgs_to_client{user="hello"} 7180782
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 58994.9 (16h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 65410
telemt_connections_bad_total 14202
telemt_handshake_timeouts_total 1565
telemt_upstream_connect_attempt_total 46582
telemt_upstream_connect_success_total 46580
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 46582
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 39320
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7218
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 42
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 46574
telemt_user_connections_current{user="hello"} 105
telemt_user_octets_from_client{user="hello"} 790423859 (753.81 MB)
telemt_user_octets_to_client{user="hello"} 48869428854 (45.51 GB)
telemt_user_msgs_from_client{user="hello"} 1069525
telemt_user_msgs_to_client{user="hello"} 5921657
telemt_user_unique_ips_current{user="hello"} 29
telemt_user_unique_ips_recent_window{user="hello"} 11
```