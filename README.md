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

# Server Metrics 2026-03-12 02:23:12 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 16687.0 (4h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 32732
telemt_connections_bad_total 1907
telemt_handshake_timeouts_total 260
telemt_upstream_connect_attempt_total 29084
telemt_upstream_connect_success_total 29077
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 29084
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25977
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3081
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 29075
telemt_user_connections_current{user="hello"} 235
telemt_user_octets_from_client{user="hello"} 283959071 (270.80 MB)
telemt_user_octets_to_client{user="hello"} 9498230907 (8.85 GB)
telemt_user_msgs_from_client{user="hello"} 488856
telemt_user_msgs_to_client{user="hello"} 1183472
telemt_user_unique_ips_current{user="hello"} 70
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 16675.2 (4h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13679
telemt_connections_bad_total 77
telemt_handshake_timeouts_total 58
telemt_upstream_connect_attempt_total 13100
telemt_upstream_connect_success_total 13100
telemt_upstream_connect_attempts_per_request{bucket="1"} 13100
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11628
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1467
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 13098
telemt_user_connections_current{user="hello"} 90
telemt_user_octets_from_client{user="hello"} 91118289 (86.90 MB)
telemt_user_octets_to_client{user="hello"} 5821689417 (5.42 GB)
telemt_user_msgs_from_client{user="hello"} 223298
telemt_user_msgs_to_client{user="hello"} 1677952
telemt_user_unique_ips_current{user="hello"} 29
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 16648.7 (4h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 22747
telemt_connections_bad_total 350
telemt_handshake_timeouts_total 886
telemt_upstream_connect_attempt_total 19491
telemt_upstream_connect_success_total 19491
telemt_upstream_connect_attempts_per_request{bucket="1"} 19491
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16669
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2817
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 19489
telemt_user_connections_current{user="hello"} 112
telemt_user_octets_from_client{user="hello"} 4336408569 (4.04 GB)
telemt_user_octets_to_client{user="hello"} 12214396678 (11.38 GB)
telemt_user_msgs_from_client{user="hello"} 1848329
telemt_user_msgs_to_client{user="hello"} 2426284
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 16674.1 (4h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 25091
telemt_connections_bad_total 8405
telemt_handshake_timeouts_total 700
telemt_upstream_connect_attempt_total 15276
telemt_upstream_connect_success_total 15237
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 15276
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13109
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2082
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 15233
telemt_user_connections_current{user="hello"} 109
telemt_user_octets_from_client{user="hello"} 125734715 (119.91 MB)
telemt_user_octets_to_client{user="hello"} 7929778050 (7.39 GB)
telemt_user_msgs_from_client{user="hello"} 252562
telemt_user_msgs_to_client{user="hello"} 2991336
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## rdp-onedash.ru

Не удалось получить метрики для этого сервера.

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 16674.9 (4h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 18113
telemt_connections_bad_total 137
telemt_handshake_timeouts_total 128
telemt_upstream_connect_attempt_total 16600
telemt_upstream_connect_success_total 16600
telemt_upstream_connect_attempts_per_request{bucket="1"} 16600
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14073
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2523
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 16598
telemt_user_connections_current{user="hello"} 87
telemt_user_octets_from_client{user="hello"} 416675430 (397.37 MB)
telemt_user_octets_to_client{user="hello"} 21919313998 (20.41 GB)
telemt_user_msgs_from_client{user="hello"} 522504
telemt_user_msgs_to_client{user="hello"} 2441726
telemt_user_unique_ips_current{user="hello"} 24
telemt_user_unique_ips_recent_window{user="hello"} 10
```