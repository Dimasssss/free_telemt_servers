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

# Server Metrics 2026-03-11 01:10:01 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 38632.6 (10h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 106590
telemt_connections_bad_total 3344
telemt_handshake_timeouts_total 2510
telemt_upstream_connect_attempt_total 96049
telemt_upstream_connect_success_total 96015
telemt_upstream_connect_fail_total 34
telemt_upstream_connect_attempts_per_request{bucket="1"} 96049
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 87325
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8636
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 34
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 96011
telemt_user_connections_current{user="hello"} 145
telemt_user_octets_from_client{user="hello"} 2718839374 (2.53 GB)
telemt_user_octets_to_client{user="hello"} 77554419490 (72.23 GB)
telemt_user_msgs_from_client{user="hello"} 2756983
telemt_user_msgs_to_client{user="hello"} 5290298
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 38632.1 (10h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 42574
telemt_connections_bad_total 352
telemt_handshake_timeouts_total 995
telemt_upstream_connect_attempt_total 38757
telemt_upstream_connect_success_total 38748
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 38757
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32795
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5730
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 223
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 38744
telemt_user_connections_current{user="hello"} 39
telemt_user_octets_from_client{user="hello"} 2017816159 (1.88 GB)
telemt_user_octets_to_client{user="hello"} 38585381640 (35.94 GB)
telemt_user_msgs_from_client{user="hello"} 1605091
telemt_user_msgs_to_client{user="hello"} 9564797
telemt_user_unique_ips_current{user="hello"} 20
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 38631.9 (10h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 65493
telemt_connections_bad_total 583
telemt_handshake_timeouts_total 4115
telemt_upstream_connect_attempt_total 57101
telemt_upstream_connect_success_total 57099
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 57101
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 51056
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5994
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 57095
telemt_user_connections_current{user="hello"} 46
telemt_user_octets_from_client{user="hello"} 8344299182 (7.77 GB)
telemt_user_octets_to_client{user="hello"} 62720686899 (58.41 GB)
telemt_user_msgs_from_client{user="hello"} 3867737
telemt_user_msgs_to_client{user="hello"} 10386037
telemt_user_unique_ips_current{user="hello"} 23
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 38631.1 (10h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 63003
telemt_connections_bad_total 121
telemt_handshake_timeouts_total 530
telemt_upstream_connect_attempt_total 60271
telemt_upstream_connect_success_total 60116
telemt_upstream_connect_fail_total 155
telemt_upstream_connect_attempts_per_request{bucket="1"} 60271
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 52556
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7373
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 24
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 163
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 155
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 60112
telemt_user_connections_current{user="hello"} 116
telemt_user_octets_from_client{user="hello"} 863156794 (823.17 MB)
telemt_user_octets_to_client{user="hello"} 40093304800 (37.34 GB)
telemt_user_msgs_from_client{user="hello"} 1218226
telemt_user_msgs_to_client{user="hello"} 7759918
telemt_user_unique_ips_current{user="hello"} 27
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 38632.0 (10h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 91228
telemt_connections_bad_total 9086
telemt_handshake_timeouts_total 1488
telemt_upstream_connect_attempt_total 77299
telemt_upstream_connect_success_total 77051
telemt_upstream_connect_fail_total 248
telemt_upstream_connect_attempts_per_request{bucket="1"} 77299
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 66772
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10061
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 218
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 248
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 77047
telemt_user_connections_current{user="hello"} 112
telemt_user_octets_from_client{user="hello"} 2125329032 (1.98 GB)
telemt_user_octets_to_client{user="hello"} 62111524631 (57.85 GB)
telemt_user_msgs_from_client{user="hello"} 2082425
telemt_user_msgs_to_client{user="hello"} 9033456
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 17601.5 (4h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 51
telemt_connections_bad_total 47
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 2
telemt_upstream_connect_success_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
```