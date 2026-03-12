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

# Server Metrics 2026-03-12 06:19:35 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 30886.9 (8h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 81944
telemt_connections_bad_total 2117
telemt_handshake_timeouts_total 2280
telemt_upstream_connect_attempt_total 73858
telemt_upstream_connect_success_total 73803
telemt_upstream_connect_fail_total 55
telemt_upstream_connect_attempts_per_request{bucket="1"} 73858
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 62330
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11371
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 102
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 55
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 73799
telemt_user_connections_current{user="hello"} 330
telemt_user_octets_from_client{user="hello"} 759605808 (724.42 MB)
telemt_user_octets_to_client{user="hello"} 22024234029 (20.51 GB)
telemt_user_msgs_from_client{user="hello"} 1119954
telemt_user_msgs_to_client{user="hello"} 2562544
telemt_user_unique_ips_current{user="hello"} 87
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 30875.2 (8h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 33009
telemt_connections_bad_total 210
telemt_handshake_timeouts_total 168
telemt_upstream_connect_attempt_total 31465
telemt_upstream_connect_success_total 31449
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 31465
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27192
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4216
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 31445
telemt_user_connections_current{user="hello"} 128
telemt_user_octets_from_client{user="hello"} 288149928 (274.80 MB)
telemt_user_octets_to_client{user="hello"} 15456834663 (14.40 GB)
telemt_user_msgs_from_client{user="hello"} 573464
telemt_user_msgs_to_client{user="hello"} 4861965
telemt_user_unique_ips_current{user="hello"} 44
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 30848.8 (8h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 50230
telemt_connections_bad_total 675
telemt_handshake_timeouts_total 1075
telemt_upstream_connect_attempt_total 45351
telemt_upstream_connect_success_total 45333
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 45351
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37673
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7622
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 45329
telemt_user_connections_current{user="hello"} 164
telemt_user_octets_from_client{user="hello"} 5383252792 (5.01 GB)
telemt_user_octets_to_client{user="hello"} 27775993567 (25.87 GB)
telemt_user_msgs_from_client{user="hello"} 2647855
telemt_user_msgs_to_client{user="hello"} 4979142
telemt_user_unique_ips_current{user="hello"} 57
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 30874.0 (8h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 55035
telemt_connections_bad_total 12927
telemt_handshake_timeouts_total 861
telemt_upstream_connect_attempt_total 39118
telemt_upstream_connect_success_total 37399
telemt_upstream_connect_fail_total 1719
telemt_upstream_connect_attempts_per_request{bucket="1"} 39118
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31104
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6190
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1719
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 37395
telemt_user_connections_current{user="hello"} 188
telemt_user_octets_from_client{user="hello"} 1289291853 (1.20 GB)
telemt_user_octets_to_client{user="hello"} 25273440575 (23.54 GB)
telemt_user_msgs_from_client{user="hello"} 1003308
telemt_user_msgs_to_client{user="hello"} 10464567
telemt_user_unique_ips_current{user="hello"} 50
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 1066.5 (0h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1768
telemt_connections_bad_total 191
telemt_handshake_timeouts_total 60
telemt_upstream_connect_attempt_total 1433
telemt_upstream_connect_success_total 1421
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 1433
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1241
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 171
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1419
telemt_user_connections_current{user="hello"} 56
telemt_user_octets_from_client{user="hello"} 100905015 (96.23 MB)
telemt_user_octets_to_client{user="hello"} 581511576 (554.57 MB)
telemt_user_msgs_from_client{user="hello"} 49541
telemt_user_msgs_to_client{user="hello"} 75647
telemt_user_unique_ips_current{user="hello"} 22
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 30874.9 (8h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 50437
telemt_connections_bad_total 766
telemt_handshake_timeouts_total 251
telemt_upstream_connect_attempt_total 47049
telemt_upstream_connect_success_total 47021
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 47049
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 39100
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7868
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 47017
telemt_user_connections_current{user="hello"} 162
telemt_user_octets_from_client{user="hello"} 843549125 (804.47 MB)
telemt_user_octets_to_client{user="hello"} 42726965899 (39.79 GB)
telemt_user_msgs_from_client{user="hello"} 1232470
telemt_user_msgs_to_client{user="hello"} 5683674
telemt_user_unique_ips_current{user="hello"} 61
telemt_user_unique_ips_recent_window{user="hello"} 30
```