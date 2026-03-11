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

# Server Metrics 2026-03-11 09:14:14 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 67685.3 (18h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 195659
telemt_connections_bad_total 3558
telemt_handshake_timeouts_total 4213
telemt_upstream_connect_attempt_total 178753
telemt_upstream_connect_success_total 178698
telemt_upstream_connect_fail_total 55
telemt_upstream_connect_attempts_per_request{bucket="1"} 178753
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 163087
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15554
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 55
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 178690
telemt_user_connections_current{user="hello"} 383
telemt_user_octets_from_client{user="hello"} 3925759463 (3.66 GB)
telemt_user_octets_to_client{user="hello"} 108236303260 (100.80 GB)
telemt_user_msgs_from_client{user="hello"} 4260139
telemt_user_msgs_to_client{user="hello"} 7983458
telemt_user_unique_ips_current{user="hello"} 97
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 67684.5 (18h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 75905
telemt_connections_bad_total 640
telemt_handshake_timeouts_total 3137
telemt_upstream_connect_attempt_total 68588
telemt_upstream_connect_success_total 68573
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 68588
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 58981
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9345
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 247
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 68567
telemt_user_connections_current{user="hello"} 96
telemt_user_octets_from_client{user="hello"} 4929782191 (4.59 GB)
telemt_user_octets_to_client{user="hello"} 53937867099 (50.23 GB)
telemt_user_msgs_from_client{user="hello"} 3105741
telemt_user_msgs_to_client{user="hello"} 13878802
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 67684.8 (18h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 105278
telemt_connections_bad_total 929
telemt_handshake_timeouts_total 5208
telemt_upstream_connect_attempt_total 93109
telemt_upstream_connect_success_total 93105
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 93109
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 82618
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10425
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 93097
telemt_user_connections_current{user="hello"} 151
telemt_user_octets_from_client{user="hello"} 11967498266 (11.15 GB)
telemt_user_octets_to_client{user="hello"} 78432748665 (73.05 GB)
telemt_user_msgs_from_client{user="hello"} 5567897
telemt_user_msgs_to_client{user="hello"} 15299454
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 67683.2 (18h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 116387
telemt_connections_bad_total 227
telemt_handshake_timeouts_total 1050
telemt_upstream_connect_attempt_total 110567
telemt_upstream_connect_success_total 110317
telemt_upstream_connect_fail_total 250
telemt_upstream_connect_attempts_per_request{bucket="1"} 110567
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 95144
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14816
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 57
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 300
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 250
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 110309
telemt_user_connections_current{user="hello"} 170
telemt_user_octets_from_client{user="hello"} 4776516613 (4.45 GB)
telemt_user_octets_to_client{user="hello"} 79468305273 (74.01 GB)
telemt_user_msgs_from_client{user="hello"} 3293054
telemt_user_msgs_to_client{user="hello"} 20442915
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 67684.4 (18h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 185391
telemt_connections_bad_total 14821
telemt_handshake_timeouts_total 3101
telemt_upstream_connect_attempt_total 148084
telemt_upstream_connect_success_total 147682
telemt_upstream_connect_fail_total 402
telemt_upstream_connect_attempts_per_request{bucket="1"} 148084
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 126590
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20814
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 278
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 402
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 147676
telemt_user_connections_current{user="hello"} 216
telemt_user_octets_from_client{user="hello"} 2895557548 (2.70 GB)
telemt_user_octets_to_client{user="hello"} 133808889038 (124.62 GB)
telemt_user_msgs_from_client{user="hello"} 3308985
telemt_user_msgs_to_client{user="hello"} 17407393
telemt_user_unique_ips_current{user="hello"} 68
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 46653.9 (12h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 420
telemt_connections_bad_total 398
telemt_handshake_timeouts_total 9
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