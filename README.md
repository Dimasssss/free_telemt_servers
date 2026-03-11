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

# Server Metrics 2026-03-11 03:58:06 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 48717.4 (13h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 124050
telemt_connections_bad_total 3381
telemt_handshake_timeouts_total 2636
telemt_upstream_connect_attempt_total 112424
telemt_upstream_connect_success_total 112384
telemt_upstream_connect_fail_total 40
telemt_upstream_connect_attempts_per_request{bucket="1"} 112424
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 102425
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9905
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 40
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 112378
telemt_user_connections_current{user="hello"} 190
telemt_user_octets_from_client{user="hello"} 2979817896 (2.78 GB)
telemt_user_octets_to_client{user="hello"} 83406702475 (77.68 GB)
telemt_user_msgs_from_client{user="hello"} 3037601
telemt_user_msgs_to_client{user="hello"} 5795510
telemt_user_unique_ips_current{user="hello"} 60
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 48716.7 (13h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 51433
telemt_connections_bad_total 399
telemt_handshake_timeouts_total 2930
telemt_upstream_connect_attempt_total 45381
telemt_upstream_connect_success_total 45371
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 45381
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 38254
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6891
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 226
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 45365
telemt_user_connections_current{user="hello"} 40
telemt_user_octets_from_client{user="hello"} 2327449625 (2.17 GB)
telemt_user_octets_to_client{user="hello"} 44102653607 (41.07 GB)
telemt_user_msgs_from_client{user="hello"} 1816787
telemt_user_msgs_to_client{user="hello"} 10491140
telemt_user_unique_ips_current{user="hello"} 19
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 48716.4 (13h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 71959
telemt_connections_bad_total 667
telemt_handshake_timeouts_total 4232
telemt_upstream_connect_attempt_total 63057
telemt_upstream_connect_success_total 63055
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 63057
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 55884
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7121
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 49
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 63049
telemt_user_connections_current{user="hello"} 44
telemt_user_octets_from_client{user="hello"} 11751245191 (10.94 GB)
telemt_user_octets_to_client{user="hello"} 70707527761 (65.85 GB)
telemt_user_msgs_from_client{user="hello"} 5148127
telemt_user_msgs_to_client{user="hello"} 13249729
telemt_user_unique_ips_current{user="hello"} 26
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 48715.5 (13h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 73081
telemt_connections_bad_total 152
telemt_handshake_timeouts_total 561
telemt_upstream_connect_attempt_total 69938
telemt_upstream_connect_success_total 69779
telemt_upstream_connect_fail_total 159
telemt_upstream_connect_attempts_per_request{bucket="1"} 69938
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 60627
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8936
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 34
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 182
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 159
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 69773
telemt_user_connections_current{user="hello"} 86
telemt_user_octets_from_client{user="hello"} 1784475114 (1.66 GB)
telemt_user_octets_to_client{user="hello"} 43247574507 (40.28 GB)
telemt_user_msgs_from_client{user="hello"} 1636789
telemt_user_msgs_to_client{user="hello"} 8509960
telemt_user_unique_ips_current{user="hello"} 26
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 48716.7 (13h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 115852
telemt_connections_bad_total 11052
telemt_handshake_timeouts_total 1654
telemt_upstream_connect_attempt_total 98686
telemt_upstream_connect_success_total 98438
telemt_upstream_connect_fail_total 248
telemt_upstream_connect_attempts_per_request{bucket="1"} 98686
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 86178
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12031
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 229
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 248
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 98432
telemt_user_connections_current{user="hello"} 127
telemt_user_octets_from_client{user="hello"} 2281651576 (2.12 GB)
telemt_user_octets_to_client{user="hello"} 91610010173 (85.32 GB)
telemt_user_msgs_from_client{user="hello"} 2420909
telemt_user_msgs_to_client{user="hello"} 11820391
telemt_user_unique_ips_current{user="hello"} 52
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 27686.1 (7h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 118
telemt_connections_bad_total 109
telemt_handshake_timeouts_total 7
telemt_upstream_connect_attempt_total 4
telemt_upstream_connect_success_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 4
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
```