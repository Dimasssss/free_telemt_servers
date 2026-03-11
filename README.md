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

# Server Metrics 2026-03-11 20:46:21 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 13561.7 (3h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 47967
telemt_connections_bad_total 2484
telemt_handshake_timeouts_total 220
telemt_upstream_connect_attempt_total 43269
telemt_upstream_connect_success_total 43259
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 43269
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 39098
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4046
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 115
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 43257
telemt_user_connections_current{user="hello"} 266
telemt_user_octets_from_client{user="hello"} 1436044569 (1.34 GB)
telemt_user_octets_to_client{user="hello"} 25048957818 (23.33 GB)
telemt_user_msgs_from_client{user="hello"} 1195993
telemt_user_msgs_to_client{user="hello"} 2143885
telemt_user_unique_ips_current{user="hello"} 71
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 13550.0 (3h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 22061
telemt_connections_bad_total 39
telemt_handshake_timeouts_total 257
telemt_upstream_connect_attempt_total 20373
telemt_upstream_connect_success_total 20334
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 20373
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17569
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2439
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 326
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 20332
telemt_user_connections_current{user="hello"} 107
telemt_user_octets_from_client{user="hello"} 235517358 (224.61 MB)
telemt_user_octets_to_client{user="hello"} 10594874153 (9.87 GB)
telemt_user_msgs_from_client{user="hello"} 415755
telemt_user_msgs_to_client{user="hello"} 4294627
telemt_user_unique_ips_current{user="hello"} 33
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 13570.0 (3h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 26955
telemt_connections_bad_total 41
telemt_handshake_timeouts_total 248
telemt_upstream_connect_attempt_total 25214
telemt_upstream_connect_success_total 25212
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 25214
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22945
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2247
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 25210
telemt_user_connections_current{user="hello"} 77
telemt_user_octets_from_client{user="hello"} 303416271 (289.36 MB)
telemt_user_octets_to_client{user="hello"} 9705881876 (9.04 GB)
telemt_user_msgs_from_client{user="hello"} 486644
telemt_user_msgs_to_client{user="hello"} 2427134
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 13565.4 (3h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 29120
telemt_connections_bad_total 1803
telemt_handshake_timeouts_total 413
telemt_upstream_connect_attempt_total 25581
telemt_upstream_connect_success_total 25504
telemt_upstream_connect_fail_total 77
telemt_upstream_connect_attempts_per_request{bucket="1"} 25581
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22988
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2433
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 16
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 67
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 77
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 25502
telemt_user_connections_current{user="hello"} 118
telemt_user_octets_from_client{user="hello"} 696264766 (664.01 MB)
telemt_user_octets_to_client{user="hello"} 13997300673 (13.04 GB)
telemt_user_msgs_from_client{user="hello"} 600011
telemt_user_msgs_to_client{user="hello"} 4133764
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 13573.6 (3h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 32193
telemt_connections_bad_total 2594
telemt_handshake_timeouts_total 181
telemt_upstream_connect_attempt_total 28456
telemt_upstream_connect_success_total 28455
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 28456
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25006
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3402
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 47
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 28453
telemt_user_connections_current{user="hello"} 127
telemt_user_octets_from_client{user="hello"} 505363096 (481.95 MB)
telemt_user_octets_to_client{user="hello"} 10860810209 (10.11 GB)
telemt_user_msgs_from_client{user="hello"} 646821
telemt_user_msgs_to_client{user="hello"} 3964517
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 88180.0 (24h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1402
telemt_connections_bad_total 493
telemt_handshake_timeouts_total 20
telemt_upstream_connect_attempt_total 865
telemt_upstream_connect_success_total 865
telemt_upstream_connect_attempts_per_request{bucket="1"} 865
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 727
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 138
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 855
telemt_user_connections_current{user="hello"} 65
telemt_user_octets_from_client{user="hello"} 7377165 (7.04 MB)
telemt_user_octets_to_client{user="hello"} 518729510 (494.70 MB)
telemt_user_msgs_from_client{user="hello"} 18302
telemt_user_msgs_to_client{user="hello"} 61316
telemt_user_unique_ips_current{user="hello"} 15
telemt_user_unique_ips_recent_window{user="hello"} 9
```