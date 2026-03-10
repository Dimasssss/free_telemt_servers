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

# Server Metrics 2026-03-10 03:38:55 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.14

telemt_uptime_seconds 101943.7 (28h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 185662
telemt_connections_bad_total 2368
telemt_handshake_timeouts_total 1800
telemt_upstream_connect_attempt_total 174107
telemt_upstream_connect_success_total 174052
telemt_upstream_connect_fail_total 55
telemt_upstream_connect_attempts_per_request{bucket="1"} 174107
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 160259
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13729
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 64
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 55
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 174042
telemt_user_connections_current{user="hello"} 169
telemt_user_octets_from_client{user="hello"} 4998154243 (4.65 GB)
telemt_user_octets_to_client{user="hello"} 104641678459 (97.46 GB)
telemt_user_msgs_from_client{user="hello"} 4536660
telemt_user_msgs_to_client{user="hello"} 6617255
telemt_user_unique_ips_current{user="hello"} 41
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## psb.hosting

```
telemt 3.3.14

telemt_uptime_seconds 101942.6 (28h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 57481
telemt_connections_bad_total 3072
telemt_handshake_timeouts_total 878
telemt_upstream_connect_attempt_total 50599
telemt_upstream_connect_success_total 50558
telemt_upstream_connect_fail_total 41
telemt_upstream_connect_attempts_per_request{bucket="1"} 50599
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 45220
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4975
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 363
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 41
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 50548
telemt_user_connections_current{user="hello"} 16
telemt_user_octets_from_client{user="hello"} 2149645601 (2.00 GB)
telemt_user_octets_to_client{user="hello"} 24350310066 (22.68 GB)
telemt_user_msgs_from_client{user="hello"} 1575080
telemt_user_msgs_to_client{user="hello"} 6975191
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## koara.io

```
telemt 3.3.14

telemt_uptime_seconds 101943.1 (28h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 74114
telemt_connections_bad_total 965
telemt_handshake_timeouts_total 3964
telemt_upstream_connect_attempt_total 54607
telemt_upstream_connect_success_total 54605
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 54607
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 48049
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6543
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 54595
telemt_user_connections_current{user="hello"} 31
telemt_user_octets_from_client{user="hello"} 6057596365 (5.64 GB)
telemt_user_octets_to_client{user="hello"} 55009909510 (51.23 GB)
telemt_user_msgs_from_client{user="hello"} 3488927
telemt_user_msgs_to_client{user="hello"} 8197883
telemt_user_unique_ips_current{user="hello"} 16
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## landvps.ru

```
telemt 3.3.14

telemt_uptime_seconds 101937.9 (28h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 77478
telemt_connections_bad_total 534
telemt_handshake_timeouts_total 1059
telemt_upstream_connect_attempt_total 71724
telemt_upstream_connect_success_total 71558
telemt_upstream_connect_fail_total 166
telemt_upstream_connect_attempts_per_request{bucket="1"} 71724
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 62828
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8519
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 39
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 172
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 166
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 71548
telemt_user_connections_current{user="hello"} 87
telemt_user_octets_from_client{user="hello"} 2316343501 (2.16 GB)
telemt_user_octets_to_client{user="hello"} 49044221367 (45.68 GB)
telemt_user_msgs_from_client{user="hello"} 1926164
telemt_user_msgs_to_client{user="hello"} 11755645
telemt_user_unique_ips_current{user="hello"} 25
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## rdp-onedash.ru

```
telemt 3.3.14

telemt_uptime_seconds 101943.3 (28h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 128068
telemt_connections_bad_total 22574
telemt_handshake_timeouts_total 3043
telemt_upstream_connect_attempt_total 97219
telemt_upstream_connect_success_total 97202
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 97219
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 83108
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13944
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 150
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 97192
telemt_user_connections_current{user="hello"} 86
telemt_user_octets_from_client{user="hello"} 1619277832 (1.51 GB)
telemt_user_octets_to_client{user="hello"} 89178439287 (83.05 GB)
telemt_user_msgs_from_client{user="hello"} 2204327
telemt_user_msgs_to_client{user="hello"} 11790940
telemt_user_unique_ips_current{user="hello"} 30
telemt_user_unique_ips_recent_window{user="hello"} 13
```