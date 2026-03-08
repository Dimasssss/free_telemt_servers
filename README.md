# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt  
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

-----

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

# Server Metrics 2026-03-08 08:19:22 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.13

telemt_uptime_seconds 4240.2 (1h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7669
telemt_connections_bad_total 391
telemt_handshake_timeouts_total 15
telemt_upstream_connect_attempt_total 7031
telemt_upstream_connect_success_total 7026
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 7031
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6630
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 390
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 7024
telemt_user_connections_current{user="hello"} 143
telemt_user_octets_from_client{user="hello"} 212391457 (202.55 MB)
telemt_user_octets_to_client{user="hello"} 2873413049 (2.68 GB)
telemt_user_msgs_from_client{user="hello"} 154820
telemt_user_msgs_to_client{user="hello"} 197975
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## psb.hosting

```
telemt 3.3.13

telemt_uptime_seconds 4238.8 (1h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1871
telemt_connections_bad_total 46
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 1767
telemt_upstream_connect_success_total 1767
telemt_upstream_connect_attempts_per_request{bucket="1"} 1767
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1652
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 105
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1765
telemt_user_connections_current{user="hello"} 31
telemt_user_octets_from_client{user="hello"} 23290587 (22.21 MB)
telemt_user_octets_to_client{user="hello"} 958867559 (914.45 MB)
telemt_user_msgs_from_client{user="hello"} 38350
telemt_user_msgs_to_client{user="hello"} 234897
telemt_user_unique_ips_current{user="hello"} 9
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## koara.io

```
telemt 3.3.13

telemt_uptime_seconds 4238.6 (1h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1476
telemt_connections_bad_total 7
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 1438
telemt_upstream_connect_success_total 1438
telemt_upstream_connect_attempts_per_request{bucket="1"} 1438
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1301
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 136
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1436
telemt_user_connections_current{user="hello"} 22
telemt_user_octets_from_client{user="hello"} 21043214 (20.07 MB)
telemt_user_octets_to_client{user="hello"} 353541803 (337.16 MB)
telemt_user_msgs_from_client{user="hello"} 13647
telemt_user_msgs_to_client{user="hello"} 60072
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## landvps.ru

```
telemt 3.3.13

telemt_uptime_seconds 4238.5 (1h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1549
telemt_connections_bad_total 11
telemt_handshake_timeouts_total 15
telemt_upstream_connect_attempt_total 1489
telemt_upstream_connect_success_total 1486
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 1489
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1386
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 90
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1484
telemt_user_connections_current{user="hello"} 22
telemt_user_octets_from_client{user="hello"} 38093675 (36.33 MB)
telemt_user_octets_to_client{user="hello"} 410283420 (391.28 MB)
telemt_user_msgs_from_client{user="hello"} 23987
telemt_user_msgs_to_client{user="hello"} 112260
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## rdp-onedash.ru

```
telemt 3.3.13

telemt_uptime_seconds 4238.9 (1h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2807
telemt_connections_bad_total 759
telemt_handshake_timeouts_total 1
telemt_upstream_connect_attempt_total 2020
telemt_upstream_connect_success_total 2020
telemt_upstream_connect_attempts_per_request{bucket="1"} 2020
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1644
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 375
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2018
telemt_user_connections_current{user="hello"} 24
telemt_user_octets_from_client{user="hello"} 19561954 (18.66 MB)
telemt_user_octets_to_client{user="hello"} 555469767 (529.74 MB)
telemt_user_msgs_from_client{user="hello"} 30526
telemt_user_msgs_to_client{user="hello"} 102400
telemt_user_unique_ips_current{user="hello"} 9
telemt_user_unique_ips_recent_window{user="hello"} 3
```