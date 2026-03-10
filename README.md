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

# Server Metrics 2026-03-10 12:00:51 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 132059.1 (36h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 289802
telemt_connections_bad_total 3463
telemt_handshake_timeouts_total 3067
telemt_upstream_connect_attempt_total 271061
telemt_upstream_connect_success_total 270911
telemt_upstream_connect_fail_total 150
telemt_upstream_connect_attempts_per_request{bucket="1"} 271061
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 250356
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20468
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 87
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 150
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 270899
telemt_user_connections_current{user="hello"} 342
telemt_user_octets_from_client{user="hello"} 6440983433 (6.00 GB)
telemt_user_octets_to_client{user="hello"} 175396103699 (163.35 GB)
telemt_user_msgs_from_client{user="hello"} 6549992
telemt_user_msgs_to_client{user="hello"} 10584654
telemt_user_unique_ips_current{user="hello"} 71
telemt_user_unique_ips_recent_window{user="hello"} 36
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 132058.0 (36h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 88631
telemt_connections_bad_total 3270
telemt_handshake_timeouts_total 1249
telemt_upstream_connect_attempt_total 79502
telemt_upstream_connect_success_total 79457
telemt_upstream_connect_fail_total 44
telemt_upstream_connect_attempts_per_request{bucket="1"} 79501
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 71568
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7472
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 416
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 44
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 79443
telemt_user_connections_current{user="hello"} 98
telemt_user_octets_from_client{user="hello"} 2758242218 (2.57 GB)
telemt_user_octets_to_client{user="hello"} 34544808799 (32.17 GB)
telemt_user_msgs_from_client{user="hello"} 2166552
telemt_user_msgs_to_client{user="hello"} 9961226
telemt_user_unique_ips_current{user="hello"} 24
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 132058.3 (36h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 125866
telemt_connections_bad_total 1203
telemt_handshake_timeouts_total 6279
telemt_upstream_connect_attempt_total 91954
telemt_upstream_connect_success_total 91952
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 91954
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 81453
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10472
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 91940
telemt_user_connections_current{user="hello"} 91
telemt_user_octets_from_client{user="hello"} 6583148149 (6.13 GB)
telemt_user_octets_to_client{user="hello"} 66414542965 (61.85 GB)
telemt_user_msgs_from_client{user="hello"} 4335180
telemt_user_msgs_to_client{user="hello"} 11011008
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 132053.1 (36h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 130956
telemt_connections_bad_total 1040
telemt_handshake_timeouts_total 2897
telemt_upstream_connect_attempt_total 120595
telemt_upstream_connect_success_total 120338
telemt_upstream_connect_fail_total 257
telemt_upstream_connect_attempts_per_request{bucket="1"} 120595
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 106798
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13159
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 75
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 306
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 257
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 120324
telemt_user_connections_current{user="hello"} 164
telemt_user_octets_from_client{user="hello"} 3626273432 (3.38 GB)
telemt_user_octets_to_client{user="hello"} 83789448768 (78.04 GB)
telemt_user_msgs_from_client{user="hello"} 3152667
telemt_user_msgs_to_client{user="hello"} 19155944
telemt_user_unique_ips_current{user="hello"} 47
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 132058.6 (36h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 195036
telemt_connections_bad_total 28698
telemt_handshake_timeouts_total 5284
telemt_upstream_connect_attempt_total 152805
telemt_upstream_connect_success_total 151844
telemt_upstream_connect_fail_total 961
telemt_upstream_connect_attempts_per_request{bucket="1"} 152805
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 131350
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20280
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 214
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 961
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 151830
telemt_user_connections_current{user="hello"} 195
telemt_user_octets_from_client{user="hello"} 3376817354 (3.14 GB)
telemt_user_octets_to_client{user="hello"} 113683969782 (105.88 GB)
telemt_user_msgs_from_client{user="hello"} 3523089
telemt_user_msgs_to_client{user="hello"} 15451158
telemt_user_unique_ips_current{user="hello"} 55
telemt_user_unique_ips_recent_window{user="hello"} 24
```