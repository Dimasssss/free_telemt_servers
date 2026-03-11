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

# Server Metrics 2026-03-11 16:29:57 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 932.9 (0h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4728
telemt_connections_bad_total 261
telemt_handshake_timeouts_total 40
telemt_upstream_connect_attempt_total 4133
telemt_upstream_connect_success_total 4132
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 4133
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3797
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 335
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 4130
telemt_user_connections_current{user="hello"} 306
telemt_user_octets_from_client{user="hello"} 34623137 (33.02 MB)
telemt_user_octets_to_client{user="hello"} 921918035 (879.21 MB)
telemt_user_msgs_from_client{user="hello"} 58602
telemt_user_msgs_to_client{user="hello"} 105179
telemt_user_unique_ips_current{user="hello"} 87
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 93824.0 (26h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 128751
telemt_connections_bad_total 974
telemt_handshake_timeouts_total 3459
telemt_upstream_connect_attempt_total 118888
telemt_upstream_connect_success_total 118865
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 118888
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 103559
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14705
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 601
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 118855
telemt_user_connections_current{user="hello"} 185
telemt_user_octets_from_client{user="hello"} 6114127579 (5.69 GB)
telemt_user_octets_to_client{user="hello"} 72859180177 (67.86 GB)
telemt_user_msgs_from_client{user="hello"} 4175223
telemt_user_msgs_to_client{user="hello"} 21356595
telemt_user_unique_ips_current{user="hello"} 48
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 93823.8 (26h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 174535
telemt_connections_bad_total 1446
telemt_handshake_timeouts_total 7856
telemt_upstream_connect_attempt_total 155770
telemt_upstream_connect_success_total 155756
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 155770
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 138158
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17489
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 108
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 155746
telemt_user_connections_current{user="hello"} 154
telemt_user_octets_from_client{user="hello"} 12789449373 (11.91 GB)
telemt_user_octets_to_client{user="hello"} 134849277671 (125.59 GB)
telemt_user_msgs_from_client{user="hello"} 7000236
telemt_user_msgs_to_client{user="hello"} 30610180
telemt_user_unique_ips_current{user="hello"} 60
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 93822.8 (26h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 197395
telemt_connections_bad_total 9903
telemt_handshake_timeouts_total 3175
telemt_upstream_connect_attempt_total 176440
telemt_upstream_connect_success_total 176012
telemt_upstream_connect_fail_total 428
telemt_upstream_connect_attempts_per_request{bucket="1"} 176440
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 153604
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21828
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 97
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 483
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 428
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 176002
telemt_user_connections_current{user="hello"} 161
telemt_user_octets_from_client{user="hello"} 10452210461 (9.73 GB)
telemt_user_octets_to_client{user="hello"} 121125815684 (112.81 GB)
telemt_user_msgs_from_client{user="hello"} 6224992
telemt_user_msgs_to_client{user="hello"} 36222464
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## rdp-onedash.ru

Не удалось получить метрики для этого сервера.

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 72793.4 (20h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 473
telemt_connections_bad_total 450
telemt_handshake_timeouts_total 12
telemt_upstream_connect_attempt_total 19
telemt_upstream_connect_success_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 19
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11
telemt_user_octets_from_client{user="hello"} 7489 (7.31 KB)
telemt_user_octets_to_client{user="hello"} 2462 (2.40 KB)
telemt_user_msgs_from_client{user="hello"} 23
telemt_user_msgs_to_client{user="hello"} 15
```