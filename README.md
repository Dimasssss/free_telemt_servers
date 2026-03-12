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

# Server Metrics 2026-03-12 02:39:25 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 17660.4 (4h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 35352
telemt_connections_bad_total 1920
telemt_handshake_timeouts_total 299
telemt_upstream_connect_attempt_total 31575
telemt_upstream_connect_success_total 31568
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 31575
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28156
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3392
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 31566
telemt_user_connections_current{user="hello"} 217
telemt_user_octets_from_client{user="hello"} 298937736 (285.09 MB)
telemt_user_octets_to_client{user="hello"} 9878497802 (9.20 GB)
telemt_user_msgs_from_client{user="hello"} 512306
telemt_user_msgs_to_client{user="hello"} 1243368
telemt_user_unique_ips_current{user="hello"} 64
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 17648.7 (4h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14526
telemt_connections_bad_total 91
telemt_handshake_timeouts_total 69
telemt_upstream_connect_attempt_total 13904
telemt_upstream_connect_success_total 13904
telemt_upstream_connect_attempts_per_request{bucket="1"} 13904
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12316
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1583
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 13902
telemt_user_connections_current{user="hello"} 71
telemt_user_octets_from_client{user="hello"} 99631386 (95.02 MB)
telemt_user_octets_to_client{user="hello"} 6702346609 (6.24 GB)
telemt_user_msgs_from_client{user="hello"} 242319
telemt_user_msgs_to_client{user="hello"} 1856160
telemt_user_unique_ips_current{user="hello"} 27
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 17622.4 (4h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 24327
telemt_connections_bad_total 362
telemt_handshake_timeouts_total 900
telemt_upstream_connect_attempt_total 21008
telemt_upstream_connect_success_total 21008
telemt_upstream_connect_attempts_per_request{bucket="1"} 21008
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17860
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3143
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 21004
telemt_user_connections_current{user="hello"} 112
telemt_user_octets_from_client{user="hello"} 5204943827 (4.85 GB)
telemt_user_octets_to_client{user="hello"} 12631997768 (11.76 GB)
telemt_user_msgs_from_client{user="hello"} 2171777
telemt_user_msgs_to_client{user="hello"} 2591456
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 17647.8 (4h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 27701
telemt_connections_bad_total 8461
telemt_handshake_timeouts_total 702
telemt_upstream_connect_attempt_total 17777
telemt_upstream_connect_success_total 16079
telemt_upstream_connect_fail_total 1698
telemt_upstream_connect_attempts_per_request{bucket="1"} 17777
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13719
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2300
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 51
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1698
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 16075
telemt_user_connections_current{user="hello"} 145
telemt_user_octets_from_client{user="hello"} 133789106 (127.59 MB)
telemt_user_octets_to_client{user="hello"} 9443044924 (8.79 GB)
telemt_user_msgs_from_client{user="hello"} 274581
telemt_user_msgs_to_client{user="hello"} 3654161
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## rdp-onedash.ru

Не удалось получить метрики для этого сервера.

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 17648.4 (4h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19250
telemt_connections_bad_total 139
telemt_handshake_timeouts_total 133
telemt_upstream_connect_attempt_total 17697
telemt_upstream_connect_success_total 17697
telemt_upstream_connect_attempts_per_request{bucket="1"} 17697
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14973
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2720
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 17695
telemt_user_connections_current{user="hello"} 115
telemt_user_octets_from_client{user="hello"} 429898765 (409.98 MB)
telemt_user_octets_to_client{user="hello"} 23185416995 (21.59 GB)
telemt_user_msgs_from_client{user="hello"} 556416
telemt_user_msgs_to_client{user="hello"} 2716130
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 17
```