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

# Server Metrics 2026-03-11 12:54:21 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 80892.5 (22h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 258398
telemt_connections_bad_total 3637
telemt_handshake_timeouts_total 4645
telemt_upstream_connect_attempt_total 238623
telemt_upstream_connect_success_total 238549
telemt_upstream_connect_fail_total 74
telemt_upstream_connect_attempts_per_request{bucket="1"} 238623
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 218421
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20071
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 74
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 238541
telemt_user_connections_current{user="hello"} 375
telemt_user_octets_from_client{user="hello"} 4778933321 (4.45 GB)
telemt_user_octets_to_client{user="hello"} 126501904170 (117.81 GB)
telemt_user_msgs_from_client{user="hello"} 5380814
telemt_user_msgs_to_client{user="hello"} 9878000
telemt_user_unique_ips_current{user="hello"} 94
telemt_user_unique_ips_recent_window{user="hello"} 49
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 80891.7 (22h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 100669
telemt_connections_bad_total 906
telemt_handshake_timeouts_total 3326
telemt_upstream_connect_attempt_total 92003
telemt_upstream_connect_success_total 91986
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 92003
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 79750
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11944
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 292
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 91978
telemt_user_connections_current{user="hello"} 142
telemt_user_octets_from_client{user="hello"} 5204224447 (4.85 GB)
telemt_user_octets_to_client{user="hello"} 61783237430 (57.54 GB)
telemt_user_msgs_from_client{user="hello"} 3491316
telemt_user_msgs_to_client{user="hello"} 17211092
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 80891.5 (22h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 139390
telemt_connections_bad_total 1103
telemt_handshake_timeouts_total 6709
telemt_upstream_connect_attempt_total 123884
telemt_upstream_connect_success_total 123870
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 123884
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 109892
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13883
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 94
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 123862
telemt_user_connections_current{user="hello"} 127
telemt_user_octets_from_client{user="hello"} 12495021882 (11.64 GB)
telemt_user_octets_to_client{user="hello"} 98227674457 (91.48 GB)
telemt_user_msgs_from_client{user="hello"} 6285554
telemt_user_msgs_to_client{user="hello"} 20341309
telemt_user_unique_ips_current{user="hello"} 52
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 80890.6 (22h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 152976
telemt_connections_bad_total 941
telemt_handshake_timeouts_total 1891
telemt_upstream_connect_attempt_total 143847
telemt_upstream_connect_success_total 143510
telemt_upstream_connect_fail_total 337
telemt_upstream_connect_attempts_per_request{bucket="1"} 143847
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 124555
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18505
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 75
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 375
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 337
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 143502
telemt_user_connections_current{user="hello"} 156
telemt_user_octets_from_client{user="hello"} 8220340217 (7.66 GB)
telemt_user_octets_to_client{user="hello"} 107800742652 (100.40 GB)
telemt_user_msgs_from_client{user="hello"} 5011696
telemt_user_msgs_to_client{user="hello"} 31726554
telemt_user_unique_ips_current{user="hello"} 53
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 80891.6 (22h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 229076
telemt_connections_bad_total 18038
telemt_handshake_timeouts_total 4645
telemt_upstream_connect_attempt_total 185184
telemt_upstream_connect_success_total 184684
telemt_upstream_connect_fail_total 500
telemt_upstream_connect_attempts_per_request{bucket="1"} 185184
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 159594
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24755
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 335
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 500
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 184676
telemt_user_connections_current{user="hello"} 267
telemt_user_octets_from_client{user="hello"} 4716259013 (4.39 GB)
telemt_user_octets_to_client{user="hello"} 150342743604 (140.02 GB)
telemt_user_msgs_from_client{user="hello"} 4421035
telemt_user_msgs_to_client{user="hello"} 20756190
telemt_user_unique_ips_current{user="hello"} 64
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 59861.0 (16h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 429
telemt_connections_bad_total 407
telemt_handshake_timeouts_total 10
telemt_upstream_connect_attempt_total 17
telemt_upstream_connect_success_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 17
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11
telemt_user_octets_from_client{user="hello"} 7489 (7.31 KB)
telemt_user_octets_to_client{user="hello"} 2462 (2.40 KB)
telemt_user_msgs_from_client{user="hello"} 23
telemt_user_msgs_to_client{user="hello"} 15
```