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

# Server Metrics 2026-03-08 14:55:20 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 27998.3 (7h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 67974
telemt_connections_bad_total 5023
telemt_handshake_timeouts_total 1028
telemt_upstream_connect_attempt_total 59461
telemt_upstream_connect_success_total 59439
telemt_upstream_connect_fail_total 22
telemt_upstream_connect_attempts_per_request{bucket="1"} 59461
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 56003
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3408
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 59435
telemt_user_connections_current{user="hello"} 206
telemt_user_octets_from_client{user="hello"} 1641723929 (1.53 GB)
telemt_user_octets_to_client{user="hello"} 31007407648 (28.88 GB)
telemt_user_msgs_from_client{user="hello"} 1427690
telemt_user_msgs_to_client{user="hello"} 1877573
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 27997.5 (7h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14621
telemt_connections_bad_total 117
telemt_handshake_timeouts_total 118
telemt_upstream_connect_attempt_total 14115
telemt_upstream_connect_success_total 14114
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 14115
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13027
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1010
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 77
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 14110
telemt_user_connections_current{user="hello"} 53
telemt_user_octets_from_client{user="hello"} 537037578 (512.16 MB)
telemt_user_octets_to_client{user="hello"} 11161818653 (10.40 GB)
telemt_user_msgs_from_client{user="hello"} 519625
telemt_user_msgs_to_client{user="hello"} 2836138
telemt_user_unique_ips_current{user="hello"} 10
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 27997.3 (7h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9410
telemt_connections_bad_total 145
telemt_handshake_timeouts_total 36
telemt_upstream_connect_attempt_total 8787
telemt_upstream_connect_success_total 8711
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 8787
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8041
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 598
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 72
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 8707
telemt_user_connections_current{user="hello"} 14
telemt_user_octets_from_client{user="hello"} 204327049 (194.86 MB)
telemt_user_octets_to_client{user="hello"} 2958671966 (2.76 GB)
telemt_user_msgs_from_client{user="hello"} 148391
telemt_user_msgs_to_client{user="hello"} 506546
telemt_user_unique_ips_current{user="hello"} 4
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 27997.2 (7h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12038
telemt_connections_bad_total 151
telemt_handshake_timeouts_total 45
telemt_upstream_connect_attempt_total 11495
telemt_upstream_connect_success_total 11469
telemt_upstream_connect_fail_total 26
telemt_upstream_connect_attempts_per_request{bucket="1"} 11495
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10586
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 830
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 49
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 26
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11465
telemt_user_connections_current{user="hello"} 51
telemt_user_octets_from_client{user="hello"} 940898922 (897.31 MB)
telemt_user_octets_to_client{user="hello"} 4395586029 (4.09 GB)
telemt_user_msgs_from_client{user="hello"} 452729
telemt_user_msgs_to_client{user="hello"} 986728
telemt_user_unique_ips_current{user="hello"} 9
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 27997.4 (7h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15887
telemt_connections_bad_total 5160
telemt_handshake_timeouts_total 116
telemt_upstream_connect_attempt_total 10377
telemt_upstream_connect_success_total 10373
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 10377
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8587
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1778
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 10369
telemt_user_connections_current{user="hello"} 17
telemt_user_octets_from_client{user="hello"} 228942453 (218.34 MB)
telemt_user_octets_to_client{user="hello"} 8238815520 (7.67 GB)
telemt_user_msgs_from_client{user="hello"} 271997
telemt_user_msgs_to_client{user="hello"} 1143737
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 3
```