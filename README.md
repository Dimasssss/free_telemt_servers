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

# Server Metrics 2026-03-08 15:05:36 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 28614.7 (7h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 69529
telemt_connections_bad_total 5023
telemt_handshake_timeouts_total 1028
telemt_upstream_connect_attempt_total 60973
telemt_upstream_connect_success_total 60951
telemt_upstream_connect_fail_total 22
telemt_upstream_connect_attempts_per_request{bucket="1"} 60973
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 57428
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3493
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 60947
telemt_user_connections_current{user="hello"} 183
telemt_user_octets_from_client{user="hello"} 1655268769 (1.54 GB)
telemt_user_octets_to_client{user="hello"} 32222220286 (30.01 GB)
telemt_user_msgs_from_client{user="hello"} 1458053
telemt_user_msgs_to_client{user="hello"} 1932273
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 28613.9 (7h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15022
telemt_connections_bad_total 117
telemt_handshake_timeouts_total 118
telemt_upstream_connect_attempt_total 14515
telemt_upstream_connect_success_total 14514
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 14515
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13403
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1031
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 80
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 14510
telemt_user_connections_current{user="hello"} 47
telemt_user_octets_from_client{user="hello"} 562544083 (536.48 MB)
telemt_user_octets_to_client{user="hello"} 12748639772 (11.87 GB)
telemt_user_msgs_from_client{user="hello"} 565058
telemt_user_msgs_to_client{user="hello"} 3344612
telemt_user_unique_ips_current{user="hello"} 12
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 28613.7 (7h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9632
telemt_connections_bad_total 145
telemt_handshake_timeouts_total 36
telemt_upstream_connect_attempt_total 9006
telemt_upstream_connect_success_total 8930
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 9006
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8241
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 617
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 72
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 8926
telemt_user_connections_current{user="hello"} 9
telemt_user_octets_from_client{user="hello"} 205691688 (196.16 MB)
telemt_user_octets_to_client{user="hello"} 3009171875 (2.80 GB)
telemt_user_msgs_from_client{user="hello"} 151112
telemt_user_msgs_to_client{user="hello"} 518781
telemt_user_unique_ips_current{user="hello"} 3
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 28613.5 (7h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12398
telemt_connections_bad_total 154
telemt_handshake_timeouts_total 46
telemt_upstream_connect_attempt_total 11826
telemt_upstream_connect_success_total 11798
telemt_upstream_connect_fail_total 27
telemt_upstream_connect_attempts_per_request{bucket="1"} 11825
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10880
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 865
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 49
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 27
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11794
telemt_user_connections_current{user="hello"} 48
telemt_user_octets_from_client{user="hello"} 943733673 (900.01 MB)
telemt_user_octets_to_client{user="hello"} 4488913788 (4.18 GB)
telemt_user_msgs_from_client{user="hello"} 460036
telemt_user_msgs_to_client{user="hello"} 1009204
telemt_user_unique_ips_current{user="hello"} 9
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 28613.7 (7h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16200
telemt_connections_bad_total 5271
telemt_handshake_timeouts_total 116
telemt_upstream_connect_attempt_total 10574
telemt_upstream_connect_success_total 10570
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 10574
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8748
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1814
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 10566
telemt_user_connections_current{user="hello"} 18
telemt_user_octets_from_client{user="hello"} 230340292 (219.67 MB)
telemt_user_octets_to_client{user="hello"} 8300458799 (7.73 GB)
telemt_user_msgs_from_client{user="hello"} 275719
telemt_user_msgs_to_client{user="hello"} 1160558
telemt_user_unique_ips_current{user="hello"} 9
telemt_user_unique_ips_recent_window{user="hello"} 5
```