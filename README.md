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

# Server Metrics 2026-03-06 15:35:49 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.4

telemt_uptime_seconds 18832.2 (5h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 44585
telemt_connections_bad_total 3097
telemt_handshake_timeouts_total 173
telemt_upstream_connect_attempt_total 37895
telemt_upstream_connect_success_total 37885
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 37895
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35842
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2035
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 37883
telemt_user_connections_current{user="hello"} 130
telemt_user_octets_from_client{user="hello"} 2067958256 (1.93 GB)
telemt_user_octets_to_client{user="hello"} 23903135225 (22.26 GB)
telemt_user_msgs_from_client{user="hello"} 1365219
telemt_user_msgs_to_client{user="hello"} 3792176
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## psb.hosting

```
telemt 3.3.4

telemt_uptime_seconds 18831.3 (5h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8297
telemt_connections_bad_total 167
telemt_handshake_timeouts_total 94
telemt_upstream_connect_attempt_total 7817
telemt_upstream_connect_success_total 7799
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 7817
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7266
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 451
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 80
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 7797
telemt_user_connections_current{user="hello"} 53
telemt_user_octets_from_client{user="hello"} 89393697 (85.25 MB)
telemt_user_octets_to_client{user="hello"} 4736902680 (4.41 GB)
telemt_user_msgs_from_client{user="hello"} 164036
telemt_user_msgs_to_client{user="hello"} 1482685
telemt_user_unique_ips_current{user="hello"} 7
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## koara.io

```
telemt 3.3.4

telemt_uptime_seconds 18830.5 (5h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6961
telemt_connections_bad_total 69
telemt_handshake_timeouts_total 15
telemt_upstream_connect_attempt_total 6748
telemt_upstream_connect_success_total 6747
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 6748
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6372
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 370
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 6745
telemt_user_connections_current{user="hello"} 8
telemt_user_octets_from_client{user="hello"} 102095178 (97.37 MB)
telemt_user_octets_to_client{user="hello"} 4189077282 (3.90 GB)
telemt_user_msgs_from_client{user="hello"} 149852
telemt_user_msgs_to_client{user="hello"} 982949
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## landvps.ru

```
telemt 3.3.4

telemt_uptime_seconds 18829.9 (5h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9978
telemt_connections_bad_total 112
telemt_handshake_timeouts_total 50
telemt_upstream_connect_attempt_total 9224
telemt_upstream_connect_success_total 9194
telemt_upstream_connect_fail_total 30
telemt_upstream_connect_attempts_per_request{bucket="1"} 9224
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8623
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 532
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 34
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 30
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 9192
telemt_user_connections_current{user="hello"} 31
telemt_user_octets_from_client{user="hello"} 138423819 (132.01 MB)
telemt_user_octets_to_client{user="hello"} 3140023339 (2.92 GB)
telemt_user_msgs_from_client{user="hello"} 165520
telemt_user_msgs_to_client{user="hello"} 808816
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## rdp-onedash.ru

```
telemt 3.3.4

telemt_uptime_seconds 18831.1 (5h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14002
telemt_connections_bad_total 4930
telemt_handshake_timeouts_total 544
telemt_upstream_connect_attempt_total 8307
telemt_upstream_connect_success_total 8307
telemt_upstream_connect_attempts_per_request{bucket="1"} 8307
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7221
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1079
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 8305
telemt_user_connections_current{user="hello"} 34
telemt_user_octets_from_client{user="hello"} 216468817 (206.44 MB)
telemt_user_octets_to_client{user="hello"} 19872417282 (18.51 GB)
telemt_user_msgs_from_client{user="hello"} 350368
telemt_user_msgs_to_client{user="hello"} 3557610
telemt_user_unique_ips_current{user="hello"} 11
telemt_user_unique_ips_recent_window{user="hello"} 4
```