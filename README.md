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

# Server Metrics 2026-03-06 04:03:00 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.2

telemt_uptime_seconds 20858.8 (5h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 71035
telemt_connections_bad_total 51933
telemt_handshake_timeouts_total 2426
telemt_upstream_connect_attempt_total 15316
telemt_upstream_connect_success_total 15314
telemt_upstream_connect_attempts_per_request{bucket="1"} 15312
telemt_upstream_connect_attempts_per_request{bucket="2"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14399
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 911
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 15312
telemt_user_connections_current{user="hello"} 101
telemt_user_octets_from_client{user="hello"} 198128255 (188.95 MB)
telemt_user_octets_to_client{user="hello"} 13831834791 (12.88 GB)
telemt_user_msgs_from_client{user="hello"} 356619
telemt_user_msgs_to_client{user="hello"} 2041223
telemt_user_unique_ips_current{user="hello"} 31
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## psb.hosting

```
telemt 3.3.2

telemt_uptime_seconds 20856.3 (5h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1961
telemt_connections_bad_total 141
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 1795
telemt_upstream_connect_success_total 1794
telemt_upstream_connect_attempts_per_request{bucket="1"} 1793
telemt_upstream_connect_attempts_per_request{bucket="2"} 1
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1726
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 65
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1792
telemt_user_connections_current{user="hello"} 26
telemt_user_octets_from_client{user="hello"} 50215270 (47.89 MB)
telemt_user_octets_to_client{user="hello"} 902172684 (860.38 MB)
telemt_user_msgs_from_client{user="hello"} 64825
telemt_user_msgs_to_client{user="hello"} 280436
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## koara.io

```
telemt 3.3.2

telemt_uptime_seconds 20856.7 (5h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1364
telemt_connections_bad_total 194
telemt_handshake_timeouts_total 5
telemt_upstream_connect_attempt_total 1161
telemt_upstream_connect_success_total 1161
telemt_upstream_connect_attempts_per_request{bucket="1"} 1161
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1001
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 160
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1157
telemt_user_connections_current{user="hello"} 7
telemt_user_octets_from_client{user="hello"} 36584497 (34.89 MB)
telemt_user_octets_to_client{user="hello"} 1730139633 (1.61 GB)
telemt_user_msgs_from_client{user="hello"} 46245
telemt_user_msgs_to_client{user="hello"} 346823
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## landvps.ru

```
telemt 3.3.2

telemt_uptime_seconds 20859.5 (5h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2678
telemt_connections_bad_total 127
telemt_handshake_timeouts_total 298
telemt_upstream_connect_attempt_total 2185
telemt_upstream_connect_success_total 2185
telemt_upstream_connect_attempts_per_request{bucket="1"} 2185
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1799
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 379
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2181
telemt_user_connections_current{user="hello"} 4
telemt_user_octets_from_client{user="hello"} 94903044 (90.51 MB)
telemt_user_octets_to_client{user="hello"} 5650119168 (5.26 GB)
telemt_user_msgs_from_client{user="hello"} 133097
telemt_user_msgs_to_client{user="hello"} 1183631
telemt_user_unique_ips_current{user="hello"} 3
telemt_user_unique_ips_recent_window{user="hello"} 1
```

## rdp-onedash.ru

```
telemt 3.3.2

telemt_uptime_seconds 20859.4 (5h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6768
telemt_connections_bad_total 3803
telemt_handshake_timeouts_total 142
telemt_upstream_connect_attempt_total 2751
telemt_upstream_connect_success_total 2751
telemt_upstream_connect_attempts_per_request{bucket="1"} 2751
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2398
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 350
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2749
telemt_user_connections_current{user="hello"} 21
telemt_user_octets_from_client{user="hello"} 50382224 (48.05 MB)
telemt_user_octets_to_client{user="hello"} 11293527230 (10.52 GB)
telemt_user_msgs_from_client{user="hello"} 133171
telemt_user_msgs_to_client{user="hello"} 2053082
telemt_user_unique_ips_current{user="hello"} 6
telemt_user_unique_ips_recent_window{user="hello"} 1
```