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

# Server Metrics 2026-03-11 01:04:55 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 38327.2 (10h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 106165
telemt_connections_bad_total 3344
telemt_handshake_timeouts_total 2509
telemt_upstream_connect_attempt_total 95637
telemt_upstream_connect_success_total 95603
telemt_upstream_connect_fail_total 34
telemt_upstream_connect_attempts_per_request{bucket="1"} 95637
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 86930
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8619
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 34
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 95599
telemt_user_connections_current{user="hello"} 182
telemt_user_octets_from_client{user="hello"} 2715304618 (2.53 GB)
telemt_user_octets_to_client{user="hello"} 77523030871 (72.20 GB)
telemt_user_msgs_from_client{user="hello"} 2752954
telemt_user_msgs_to_client{user="hello"} 5285387
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 38326.5 (10h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 42357
telemt_connections_bad_total 351
telemt_handshake_timeouts_total 981
telemt_upstream_connect_attempt_total 38569
telemt_upstream_connect_success_total 38560
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 38569
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32620
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5717
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 223
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 38556
telemt_user_connections_current{user="hello"} 47
telemt_user_octets_from_client{user="hello"} 2017180726 (1.88 GB)
telemt_user_octets_to_client{user="hello"} 38575377967 (35.93 GB)
telemt_user_msgs_from_client{user="hello"} 1603457
telemt_user_msgs_to_client{user="hello"} 9560670
telemt_user_unique_ips_current{user="hello"} 23
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 38326.3 (10h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 65287
telemt_connections_bad_total 571
telemt_handshake_timeouts_total 4113
telemt_upstream_connect_attempt_total 56919
telemt_upstream_connect_success_total 56917
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 56919
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 50908
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5960
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 56913
telemt_user_connections_current{user="hello"} 54
telemt_user_octets_from_client{user="hello"} 8257334645 (7.69 GB)
telemt_user_octets_to_client{user="hello"} 61995004104 (57.74 GB)
telemt_user_msgs_from_client{user="hello"} 3831005
telemt_user_msgs_to_client{user="hello"} 10061703
telemt_user_unique_ips_current{user="hello"} 26
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 38325.1 (10h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 62714
telemt_connections_bad_total 114
telemt_handshake_timeouts_total 529
telemt_upstream_connect_attempt_total 60001
telemt_upstream_connect_success_total 59846
telemt_upstream_connect_fail_total 155
telemt_upstream_connect_attempts_per_request{bucket="1"} 60001
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 52353
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7306
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 24
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 163
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 155
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 59842
telemt_user_connections_current{user="hello"} 124
telemt_user_octets_from_client{user="hello"} 857255395 (817.54 MB)
telemt_user_octets_to_client{user="hello"} 39065986106 (36.38 GB)
telemt_user_msgs_from_client{user="hello"} 1201959
telemt_user_msgs_to_client{user="hello"} 7576484
telemt_user_unique_ips_current{user="hello"} 31
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 38326.5 (10h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 90834
telemt_connections_bad_total 9019
telemt_handshake_timeouts_total 1486
telemt_upstream_connect_attempt_total 76979
telemt_upstream_connect_success_total 76731
telemt_upstream_connect_fail_total 248
telemt_upstream_connect_attempts_per_request{bucket="1"} 76979
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 66483
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10031
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 217
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 248
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 76727
telemt_user_connections_current{user="hello"} 106
telemt_user_octets_from_client{user="hello"} 2123145967 (1.98 GB)
telemt_user_octets_to_client{user="hello"} 62040400769 (57.78 GB)
telemt_user_msgs_from_client{user="hello"} 2076507
telemt_user_msgs_to_client{user="hello"} 9019620
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 17295.8 (4h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 51
telemt_connections_bad_total 47
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 2
telemt_upstream_connect_success_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
```