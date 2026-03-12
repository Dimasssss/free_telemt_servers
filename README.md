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

# Server Metrics 2026-03-12 04:16:42 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 23496.7 (6h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 50322
telemt_connections_bad_total 1983
telemt_handshake_timeouts_total 369
telemt_upstream_connect_attempt_total 45778
telemt_upstream_connect_success_total 45764
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 45778
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 39945
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5781
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 45760
telemt_user_connections_current{user="hello"} 267
telemt_user_octets_from_client{user="hello"} 501339587 (478.11 MB)
telemt_user_octets_to_client{user="hello"} 14790366898 (13.77 GB)
telemt_user_msgs_from_client{user="hello"} 739394
telemt_user_msgs_to_client{user="hello"} 1779306
telemt_user_unique_ips_current{user="hello"} 79
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 23485.1 (6h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19849
telemt_connections_bad_total 136
telemt_handshake_timeouts_total 99
telemt_upstream_connect_attempt_total 18873
telemt_upstream_connect_success_total 18870
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 18873
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16583
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2281
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 18866
telemt_user_connections_current{user="hello"} 103
telemt_user_octets_from_client{user="hello"} 170094399 (162.21 MB)
telemt_user_octets_to_client{user="hello"} 11078233916 (10.32 GB)
telemt_user_msgs_from_client{user="hello"} 358551
telemt_user_msgs_to_client{user="hello"} 2983024
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 23458.5 (6h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 33891
telemt_connections_bad_total 418
telemt_handshake_timeouts_total 929
telemt_upstream_connect_attempt_total 30056
telemt_upstream_connect_success_total 30056
telemt_upstream_connect_attempts_per_request{bucket="1"} 30056
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24975
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5074
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 30052
telemt_user_connections_current{user="hello"} 120
telemt_user_octets_from_client{user="hello"} 5276692686 (4.91 GB)
telemt_user_octets_to_client{user="hello"} 20085411141 (18.71 GB)
telemt_user_msgs_from_client{user="hello"} 2378973
telemt_user_msgs_to_client{user="hello"} 3684935
telemt_user_unique_ips_current{user="hello"} 49
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 23484.0 (6h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 34927
telemt_connections_bad_total 8655
telemt_handshake_timeouts_total 741
telemt_upstream_connect_attempt_total 24455
telemt_upstream_connect_success_total 22756
telemt_upstream_connect_fail_total 1699
telemt_upstream_connect_attempts_per_request{bucket="1"} 24455
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19119
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3573
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 55
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1699
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 22752
telemt_user_connections_current{user="hello"} 99
telemt_user_octets_from_client{user="hello"} 207871807 (198.24 MB)
telemt_user_octets_to_client{user="hello"} 19120505370 (17.81 GB)
telemt_user_msgs_from_client{user="hello"} 434767
telemt_user_msgs_to_client{user="hello"} 8027789
telemt_user_unique_ips_current{user="hello"} 33
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## rdp-onedash.ru

Не удалось получить метрики для этого сервера.

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 23484.7 (6h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 29538
telemt_connections_bad_total 160
telemt_handshake_timeouts_total 165
telemt_upstream_connect_attempt_total 27485
telemt_upstream_connect_success_total 27484
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 27485
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22935
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4545
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 27482
telemt_user_connections_current{user="hello"} 93
telemt_user_octets_from_client{user="hello"} 604321117 (576.33 MB)
telemt_user_octets_to_client{user="hello"} 32094575398 (29.89 GB)
telemt_user_msgs_from_client{user="hello"} 827331
telemt_user_msgs_to_client{user="hello"} 4153965
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 13
```