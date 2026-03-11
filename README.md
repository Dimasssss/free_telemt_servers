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

# Server Metrics 2026-03-11 19:55:11 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 10492.5 (2h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 39706
telemt_connections_bad_total 2308
telemt_handshake_timeouts_total 196
telemt_upstream_connect_attempt_total 35620
telemt_upstream_connect_success_total 35611
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 35620
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32226
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3309
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 76
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 35609
telemt_user_connections_current{user="hello"} 296
telemt_user_octets_from_client{user="hello"} 859885139 (820.05 MB)
telemt_user_octets_to_client{user="hello"} 20099355745 (18.72 GB)
telemt_user_msgs_from_client{user="hello"} 877546
telemt_user_msgs_to_client{user="hello"} 1685962
telemt_user_unique_ips_current{user="hello"} 78
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 10480.8 (2h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 18880
telemt_connections_bad_total 38
telemt_handshake_timeouts_total 253
telemt_upstream_connect_attempt_total 17365
telemt_upstream_connect_success_total 17326
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 17365
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14813
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2191
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 322
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 17324
telemt_user_connections_current{user="hello"} 125
telemt_user_octets_from_client{user="hello"} 215139907 (205.17 MB)
telemt_user_octets_to_client{user="hello"} 8796386585 (8.19 GB)
telemt_user_msgs_from_client{user="hello"} 360200
telemt_user_msgs_to_client{user="hello"} 3408068
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 10500.5 (2h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 21877
telemt_connections_bad_total 25
telemt_handshake_timeouts_total 181
telemt_upstream_connect_attempt_total 20432
telemt_upstream_connect_success_total 20430
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 20432
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18566
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1846
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 20428
telemt_user_connections_current{user="hello"} 88
telemt_user_octets_from_client{user="hello"} 204550941 (195.07 MB)
telemt_user_octets_to_client{user="hello"} 8983133112 (8.37 GB)
telemt_user_msgs_from_client{user="hello"} 410315
telemt_user_msgs_to_client{user="hello"} 2235519
telemt_user_unique_ips_current{user="hello"} 45
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 10496.0 (2h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 23978
telemt_connections_bad_total 1791
telemt_handshake_timeouts_total 376
telemt_upstream_connect_attempt_total 20825
telemt_upstream_connect_success_total 20763
telemt_upstream_connect_fail_total 62
telemt_upstream_connect_attempts_per_request{bucket="1"} 20825
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18815
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1883
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 55
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 62
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 20761
telemt_user_connections_current{user="hello"} 114
telemt_user_octets_from_client{user="hello"} 619158034 (590.48 MB)
telemt_user_octets_to_client{user="hello"} 11354253586 (10.57 GB)
telemt_user_msgs_from_client{user="hello"} 505949
telemt_user_msgs_to_client{user="hello"} 3125455
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 10504.3 (2h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 26066
telemt_connections_bad_total 2009
telemt_handshake_timeouts_total 162
telemt_upstream_connect_attempt_total 23058
telemt_upstream_connect_success_total 23057
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 23058
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20200
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2827
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 23055
telemt_user_connections_current{user="hello"} 131
telemt_user_octets_from_client{user="hello"} 441531362 (421.08 MB)
telemt_user_octets_to_client{user="hello"} 8248108752 (7.68 GB)
telemt_user_msgs_from_client{user="hello"} 520339
telemt_user_msgs_to_client{user="hello"} 2851428
telemt_user_unique_ips_current{user="hello"} 62
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 85110.6 (23h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 576
telemt_connections_bad_total 492
telemt_handshake_timeouts_total 17
telemt_upstream_connect_attempt_total 66
telemt_upstream_connect_success_total 66
telemt_upstream_connect_attempts_per_request{bucket="1"} 66
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 54
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 58
telemt_user_octets_from_client{user="hello"} 206954 (202.10 KB)
telemt_user_octets_to_client{user="hello"} 1309386 (1.25 MB)
telemt_user_msgs_from_client{user="hello"} 266
telemt_user_msgs_to_client{user="hello"} 404
```