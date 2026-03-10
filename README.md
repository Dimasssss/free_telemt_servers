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

# Server Metrics 2026-03-10 14:24:12 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 140659.8 (39h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 325304
telemt_connections_bad_total 3736
telemt_handshake_timeouts_total 3424
telemt_upstream_connect_attempt_total 304493
telemt_upstream_connect_success_total 304331
telemt_upstream_connect_fail_total 162
telemt_upstream_connect_attempts_per_request{bucket="1"} 304493
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 281298
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22932
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 101
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 162
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 304317
telemt_user_connections_current{user="hello"} 340
telemt_user_octets_from_client{user="hello"} 6912264546 (6.44 GB)
telemt_user_octets_to_client{user="hello"} 199715300452 (186.00 GB)
telemt_user_msgs_from_client{user="hello"} 7242027
telemt_user_msgs_to_client{user="hello"} 11925316
telemt_user_unique_ips_current{user="hello"} 80
telemt_user_unique_ips_recent_window{user="hello"} 36
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 140658.7 (39h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 101270
telemt_connections_bad_total 3278
telemt_handshake_timeouts_total 1446
telemt_upstream_connect_attempt_total 91270
telemt_upstream_connect_success_total 91224
telemt_upstream_connect_fail_total 46
telemt_upstream_connect_attempts_per_request{bucket="1"} 91270
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 81970
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8816
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 437
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 46
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 91210
telemt_user_connections_current{user="hello"} 114
telemt_user_octets_from_client{user="hello"} 2906603058 (2.71 GB)
telemt_user_octets_to_client{user="hello"} 38882653653 (36.21 GB)
telemt_user_msgs_from_client{user="hello"} 2382667
telemt_user_msgs_to_client{user="hello"} 11262605
telemt_user_unique_ips_current{user="hello"} 23
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 140659.1 (39h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 145067
telemt_connections_bad_total 1244
telemt_handshake_timeouts_total 7143
telemt_upstream_connect_attempt_total 109174
telemt_upstream_connect_success_total 109171
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 109174
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 96594
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12536
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 109157
telemt_user_connections_current{user="hello"} 85
telemt_user_octets_from_client{user="hello"} 6735124015 (6.27 GB)
telemt_user_octets_to_client{user="hello"} 70191252148 (65.37 GB)
telemt_user_msgs_from_client{user="hello"} 4633764
telemt_user_msgs_to_client{user="hello"} 11952415
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 140654.1 (39h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 148549
telemt_connections_bad_total 1090
telemt_handshake_timeouts_total 3075
telemt_upstream_connect_attempt_total 137363
telemt_upstream_connect_success_total 137052
telemt_upstream_connect_fail_total 311
telemt_upstream_connect_attempts_per_request{bucket="1"} 137363
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 121818
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14796
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 86
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 352
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 311
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 137038
telemt_user_connections_current{user="hello"} 137
telemt_user_octets_from_client{user="hello"} 5090625700 (4.74 GB)
telemt_user_octets_to_client{user="hello"} 96038672794 (89.44 GB)
telemt_user_msgs_from_client{user="hello"} 3951451
telemt_user_msgs_to_client{user="hello"} 21738881
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 140659.2 (39h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 219633
telemt_connections_bad_total 31406
telemt_handshake_timeouts_total 6288
telemt_upstream_connect_attempt_total 172861
telemt_upstream_connect_success_total 171898
telemt_upstream_connect_fail_total 963
telemt_upstream_connect_attempts_per_request{bucket="1"} 172861
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 148600
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23070
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 228
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 963
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 171884
telemt_user_connections_current{user="hello"} 257
telemt_user_octets_from_client{user="hello"} 3670261288 (3.42 GB)
telemt_user_octets_to_client{user="hello"} 121398180330 (113.06 GB)
telemt_user_msgs_from_client{user="hello"} 3918306
telemt_user_msgs_to_client{user="hello"} 16780130
telemt_user_unique_ips_current{user="hello"} 63
telemt_user_unique_ips_recent_window{user="hello"} 24
```