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

# Server Metrics 2026-03-11 04:54:07 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 52078.8 (14h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 132231
telemt_connections_bad_total 3386
telemt_handshake_timeouts_total 2815
telemt_upstream_connect_attempt_total 119995
telemt_upstream_connect_success_total 119951
telemt_upstream_connect_fail_total 44
telemt_upstream_connect_attempts_per_request{bucket="1"} 119995
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 109440
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10456
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 55
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 44
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 119945
telemt_user_connections_current{user="hello"} 186
telemt_user_octets_from_client{user="hello"} 3051077213 (2.84 GB)
telemt_user_octets_to_client{user="hello"} 86119840862 (80.21 GB)
telemt_user_msgs_from_client{user="hello"} 3160196
telemt_user_msgs_to_client{user="hello"} 5981854
telemt_user_unique_ips_current{user="hello"} 60
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 52078.2 (14h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 54332
telemt_connections_bad_total 414
telemt_handshake_timeouts_total 2955
telemt_upstream_connect_attempt_total 48132
telemt_upstream_connect_success_total 48122
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 48132
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40646
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7248
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 228
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 48116
telemt_user_connections_current{user="hello"} 55
telemt_user_octets_from_client{user="hello"} 4445984828 (4.14 GB)
telemt_user_octets_to_client{user="hello"} 44698125297 (41.63 GB)
telemt_user_msgs_from_client{user="hello"} 2605446
telemt_user_msgs_to_client{user="hello"} 10703264
telemt_user_unique_ips_current{user="hello"} 18
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 52078.0 (14h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 75315
telemt_connections_bad_total 682
telemt_handshake_timeouts_total 4308
telemt_upstream_connect_attempt_total 66033
telemt_upstream_connect_success_total 66030
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 66033
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 58532
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7446
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 51
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 66024
telemt_user_connections_current{user="hello"} 45
telemt_user_octets_from_client{user="hello"} 11778097727 (10.97 GB)
telemt_user_octets_to_client{user="hello"} 71148142720 (66.26 GB)
telemt_user_msgs_from_client{user="hello"} 5184907
telemt_user_msgs_to_client{user="hello"} 13365410
telemt_user_unique_ips_current{user="hello"} 24
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 52077.0 (14h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 77665
telemt_connections_bad_total 156
telemt_handshake_timeouts_total 571
telemt_upstream_connect_attempt_total 74385
telemt_upstream_connect_success_total 74221
telemt_upstream_connect_fail_total 164
telemt_upstream_connect_attempts_per_request{bucket="1"} 74385
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 64358
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9631
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 35
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 197
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 164
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 74215
telemt_user_connections_current{user="hello"} 49
telemt_user_octets_from_client{user="hello"} 1814787765 (1.69 GB)
telemt_user_octets_to_client{user="hello"} 48535282579 (45.20 GB)
telemt_user_msgs_from_client{user="hello"} 1716528
telemt_user_msgs_to_client{user="hello"} 10684070
telemt_user_unique_ips_current{user="hello"} 24
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 52078.2 (14h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 123666
telemt_connections_bad_total 11750
telemt_handshake_timeouts_total 1682
telemt_upstream_connect_attempt_total 105199
telemt_upstream_connect_success_total 104950
telemt_upstream_connect_fail_total 249
telemt_upstream_connect_attempts_per_request{bucket="1"} 105199
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 91687
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13033
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 230
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 249
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 104944
telemt_user_connections_current{user="hello"} 143
telemt_user_octets_from_client{user="hello"} 2379616375 (2.22 GB)
telemt_user_octets_to_client{user="hello"} 99375766078 (92.55 GB)
telemt_user_msgs_from_client{user="hello"} 2567692
telemt_user_msgs_to_client{user="hello"} 12842129
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 31047.6 (8h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 129
telemt_connections_bad_total 120
telemt_handshake_timeouts_total 7
telemt_upstream_connect_attempt_total 4
telemt_upstream_connect_success_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 4
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
```