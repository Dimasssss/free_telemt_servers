# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt  
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

### [Итог по хостингам](Reviews.md)

---

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

## hostvds.com
- Локация: Нидерланды, Амстердам
- Тариф: Burstable
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 10 Gbit/s
- Цена в месяц: €7.98
- Оплачен до: 13 апреля
- Ссылка:
```bash
tg://proxy?server=s6.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

# Server Metrics 2026-03-11 21:37:30 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 16631.1 (4h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 54402
telemt_connections_bad_total 2712
telemt_handshake_timeouts_total 237
telemt_upstream_connect_attempt_total 49315
telemt_upstream_connect_success_total 49302
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 49315
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 44386
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4799
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 117
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 49300
telemt_user_connections_current{user="hello"} 216
telemt_user_octets_from_client{user="hello"} 1503382848 (1.40 GB)
telemt_user_octets_to_client{user="hello"} 28539130153 (26.58 GB)
telemt_user_msgs_from_client{user="hello"} 1333773
telemt_user_msgs_to_client{user="hello"} 2802009
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 16619.2 (4h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 25116
telemt_connections_bad_total 42
telemt_handshake_timeouts_total 263
telemt_upstream_connect_attempt_total 23293
telemt_upstream_connect_success_total 23253
telemt_upstream_connect_fail_total 40
telemt_upstream_connect_attempts_per_request{bucket="1"} 23293
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20114
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2813
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 326
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 40
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 23251
telemt_user_connections_current{user="hello"} 84
telemt_user_octets_from_client{user="hello"} 272332996 (259.72 MB)
telemt_user_octets_to_client{user="hello"} 11902037002 (11.08 GB)
telemt_user_msgs_from_client{user="hello"} 482954
telemt_user_msgs_to_client{user="hello"} 4848635
telemt_user_unique_ips_current{user="hello"} 24
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 16639.1 (4h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 30982
telemt_connections_bad_total 57
telemt_handshake_timeouts_total 255
telemt_upstream_connect_attempt_total 29074
telemt_upstream_connect_success_total 29072
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 29074
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26365
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2687
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 29070
telemt_user_connections_current{user="hello"} 109
telemt_user_octets_from_client{user="hello"} 336287593 (320.71 MB)
telemt_user_octets_to_client{user="hello"} 12501329552 (11.64 GB)
telemt_user_msgs_from_client{user="hello"} 579032
telemt_user_msgs_to_client{user="hello"} 3002385
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 16634.6 (4h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 32792
telemt_connections_bad_total 1823
telemt_handshake_timeouts_total 482
telemt_upstream_connect_attempt_total 29066
telemt_upstream_connect_success_total 28983
telemt_upstream_connect_fail_total 83
telemt_upstream_connect_attempts_per_request{bucket="1"} 29066
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26042
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2849
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 73
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 83
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 28981
telemt_user_connections_current{user="hello"} 115
telemt_user_octets_from_client{user="hello"} 730525179 (696.68 MB)
telemt_user_octets_to_client{user="hello"} 18312901945 (17.06 GB)
telemt_user_msgs_from_client{user="hello"} 683766
telemt_user_msgs_to_client{user="hello"} 5920017
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 16642.7 (4h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 36428
telemt_connections_bad_total 3184
telemt_handshake_timeouts_total 186
telemt_upstream_connect_attempt_total 32017
telemt_upstream_connect_success_total 31859
telemt_upstream_connect_fail_total 158
telemt_upstream_connect_attempts_per_request{bucket="1"} 32017
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28078
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3715
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 66
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 158
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 31857
telemt_user_connections_current{user="hello"} 109
telemt_user_octets_from_client{user="hello"} 550998220 (525.47 MB)
telemt_user_octets_to_client{user="hello"} 11651084884 (10.85 GB)
telemt_user_msgs_from_client{user="hello"} 698908
telemt_user_msgs_to_client{user="hello"} 4248218
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 91249.0 (25h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4086
telemt_connections_bad_total 647
telemt_handshake_timeouts_total 23
telemt_upstream_connect_attempt_total 3332
telemt_upstream_connect_success_total 3332
telemt_upstream_connect_attempts_per_request{bucket="1"} 3332
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2825
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 507
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 3322
telemt_user_connections_current{user="hello"} 58
telemt_user_octets_from_client{user="hello"} 32777966 (31.26 MB)
telemt_user_octets_to_client{user="hello"} 2757704074 (2.57 GB)
telemt_user_msgs_from_client{user="hello"} 87366
telemt_user_msgs_to_client{user="hello"} 342425
telemt_user_unique_ips_current{user="hello"} 18
telemt_user_unique_ips_recent_window{user="hello"} 12
```