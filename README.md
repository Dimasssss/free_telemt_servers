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

# Server Metrics 2026-03-11 06:46:13 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 58804.8 (16h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 158599
telemt_connections_bad_total 3502
telemt_handshake_timeouts_total 3939
telemt_upstream_connect_attempt_total 143157
telemt_upstream_connect_success_total 143113
telemt_upstream_connect_fail_total 44
telemt_upstream_connect_attempts_per_request{bucket="1"} 143157
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 130569
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12488
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 56
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 44
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 143107
telemt_user_connections_current{user="hello"} 295
telemt_user_octets_from_client{user="hello"} 3442527599 (3.21 GB)
telemt_user_octets_to_client{user="hello"} 94817795082 (88.31 GB)
telemt_user_msgs_from_client{user="hello"} 3620362
telemt_user_msgs_to_client{user="hello"} 6739494
telemt_user_unique_ips_current{user="hello"} 74
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 58804.0 (16h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 62588
telemt_connections_bad_total 448
telemt_handshake_timeouts_total 3034
telemt_upstream_connect_attempt_total 55992
telemt_upstream_connect_success_total 55980
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 55992
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 47758
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7991
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 231
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 55974
telemt_user_connections_current{user="hello"} 88
telemt_user_octets_from_client{user="hello"} 4635245005 (4.32 GB)
telemt_user_octets_to_client{user="hello"} 49286152323 (45.90 GB)
telemt_user_msgs_from_client{user="hello"} 2847635
telemt_user_msgs_to_client{user="hello"} 11842817
telemt_user_unique_ips_current{user="hello"} 28
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 58803.9 (16h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 84168
telemt_connections_bad_total 740
telemt_handshake_timeouts_total 4413
telemt_upstream_connect_attempt_total 74320
telemt_upstream_connect_success_total 74317
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 74320
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 65947
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8310
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 74311
telemt_user_connections_current{user="hello"} 69
telemt_user_octets_from_client{user="hello"} 11839313457 (11.03 GB)
telemt_user_octets_to_client{user="hello"} 73091815350 (68.07 GB)
telemt_user_msgs_from_client{user="hello"} 5286827
telemt_user_msgs_to_client{user="hello"} 13886333
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 58802.6 (16h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 90906
telemt_connections_bad_total 199
telemt_handshake_timeouts_total 640
telemt_upstream_connect_attempt_total 87062
telemt_upstream_connect_success_total 86870
telemt_upstream_connect_fail_total 192
telemt_upstream_connect_attempts_per_request{bucket="1"} 87062
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 75225
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11357
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 43
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 245
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 192
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 86864
telemt_user_connections_current{user="hello"} 175
telemt_user_octets_from_client{user="hello"} 1964446104 (1.83 GB)
telemt_user_octets_to_client{user="hello"} 59019998151 (54.97 GB)
telemt_user_msgs_from_client{user="hello"} 1965975
telemt_user_msgs_to_client{user="hello"} 14469158
telemt_user_unique_ips_current{user="hello"} 51
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 58804.0 (16h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 154726
telemt_connections_bad_total 13046
telemt_handshake_timeouts_total 1813
telemt_upstream_connect_attempt_total 122224
telemt_upstream_connect_success_total 121975
telemt_upstream_connect_fail_total 249
telemt_upstream_connect_attempts_per_request{bucket="1"} 122224
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 104500
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 237
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 249
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 121969
telemt_user_connections_current{user="hello"} 193
telemt_user_octets_from_client{user="hello"} 2513076839 (2.34 GB)
telemt_user_octets_to_client{user="hello"} 117422525371 (109.36 GB)
telemt_user_msgs_from_client{user="hello"} 2860555
telemt_user_msgs_to_client{user="hello"} 15245275
telemt_user_unique_ips_current{user="hello"} 62
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 37773.4 (10h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 167
telemt_connections_bad_total 147
telemt_handshake_timeouts_total 8
telemt_upstream_connect_attempt_total 15
telemt_upstream_connect_success_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 15
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11
telemt_user_octets_from_client{user="hello"} 7489 (7.31 KB)
telemt_user_octets_to_client{user="hello"} 2462 (2.40 KB)
telemt_user_msgs_from_client{user="hello"} 23
telemt_user_msgs_to_client{user="hello"} 15
```