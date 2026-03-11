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

# Server Metrics 2026-03-11 03:27:32 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 46883.6 (13h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 120670
telemt_connections_bad_total 3365
telemt_handshake_timeouts_total 2584
telemt_upstream_connect_attempt_total 109221
telemt_upstream_connect_success_total 109182
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 109221
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 99441
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9687
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 109176
telemt_user_connections_current{user="hello"} 171
telemt_user_octets_from_client{user="hello"} 2940680151 (2.74 GB)
telemt_user_octets_to_client{user="hello"} 82584512200 (76.91 GB)
telemt_user_msgs_from_client{user="hello"} 2991984
telemt_user_msgs_to_client{user="hello"} 5716123
telemt_user_unique_ips_current{user="hello"} 59
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 46882.9 (13h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 50339
telemt_connections_bad_total 395
telemt_handshake_timeouts_total 2922
telemt_upstream_connect_attempt_total 44347
telemt_upstream_connect_success_total 44338
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 44347
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37342
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6770
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 226
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 44332
telemt_user_connections_current{user="hello"} 36
telemt_user_octets_from_client{user="hello"} 2315131207 (2.16 GB)
telemt_user_octets_to_client{user="hello"} 44013659415 (40.99 GB)
telemt_user_msgs_from_client{user="hello"} 1799205
telemt_user_msgs_to_client{user="hello"} 10449892
telemt_user_unique_ips_current{user="hello"} 18
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 46882.7 (13h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 70784
telemt_connections_bad_total 662
telemt_handshake_timeouts_total 4219
telemt_upstream_connect_attempt_total 61942
telemt_upstream_connect_success_total 61940
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 61942
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 54936
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6955
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 61934
telemt_user_connections_current{user="hello"} 59
telemt_user_octets_from_client{user="hello"} 11746488342 (10.94 GB)
telemt_user_octets_to_client{user="hello"} 70586668512 (65.74 GB)
telemt_user_msgs_from_client{user="hello"} 5138065
telemt_user_msgs_to_client{user="hello"} 13212141
telemt_user_unique_ips_current{user="hello"} 31
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 46881.6 (13h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 70914
telemt_connections_bad_total 151
telemt_handshake_timeouts_total 554
telemt_upstream_connect_attempt_total 67847
telemt_upstream_connect_success_total 67690
telemt_upstream_connect_fail_total 157
telemt_upstream_connect_attempts_per_request{bucket="1"} 67847
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 58902
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8576
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 32
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 180
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 157
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 67684
telemt_user_connections_current{user="hello"} 80
telemt_user_octets_from_client{user="hello"} 1771937583 (1.65 GB)
telemt_user_octets_to_client{user="hello"} 42777271872 (39.84 GB)
telemt_user_msgs_from_client{user="hello"} 1611585
telemt_user_msgs_to_client{user="hello"} 8411636
telemt_user_unique_ips_current{user="hello"} 28
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 46883.0 (13h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 110076
telemt_connections_bad_total 10695
telemt_handshake_timeouts_total 1545
telemt_upstream_connect_attempt_total 93794
telemt_upstream_connect_success_total 93546
telemt_upstream_connect_fail_total 248
telemt_upstream_connect_attempts_per_request{bucket="1"} 93794
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 81646
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11672
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 228
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 248
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 93542
telemt_user_connections_current{user="hello"} 149
telemt_user_octets_from_client{user="hello"} 2247025380 (2.09 GB)
telemt_user_octets_to_client{user="hello"} 85133466549 (79.29 GB)
telemt_user_msgs_from_client{user="hello"} 2345549
telemt_user_msgs_to_client{user="hello"} 11303661
telemt_user_unique_ips_current{user="hello"} 50
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 25852.4 (7h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 86
telemt_connections_bad_total 82
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 4
telemt_upstream_connect_success_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 4
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
```