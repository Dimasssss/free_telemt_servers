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

# Server Metrics 2026-03-12 05:43:08 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 28683.5 (7h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 72643
telemt_connections_bad_total 2108
telemt_handshake_timeouts_total 2191
telemt_upstream_connect_attempt_total 65033
telemt_upstream_connect_success_total 65015
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 65033
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 54801
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10170
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 44
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 65011
telemt_user_connections_current{user="hello"} 295
telemt_user_octets_from_client{user="hello"} 659165933 (628.63 MB)
telemt_user_octets_to_client{user="hello"} 20745166694 (19.32 GB)
telemt_user_msgs_from_client{user="hello"} 980606
telemt_user_msgs_to_client{user="hello"} 2363639
telemt_user_unique_ips_current{user="hello"} 87
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 28671.6 (7h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 28681
telemt_connections_bad_total 208
telemt_handshake_timeouts_total 149
telemt_upstream_connect_attempt_total 27329
telemt_upstream_connect_success_total 27322
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 27329
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23700
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3605
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 27318
telemt_user_connections_current{user="hello"} 134
telemt_user_octets_from_client{user="hello"} 244377515 (233.06 MB)
telemt_user_octets_to_client{user="hello"} 14651681642 (13.65 GB)
telemt_user_msgs_from_client{user="hello"} 509944
telemt_user_msgs_to_client{user="hello"} 4443201
telemt_user_unique_ips_current{user="hello"} 41
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 28645.4 (7h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 44524
telemt_connections_bad_total 662
telemt_handshake_timeouts_total 1034
telemt_upstream_connect_attempt_total 39928
telemt_upstream_connect_success_total 39927
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 39928
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33234
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6676
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 39923
telemt_user_connections_current{user="hello"} 142
telemt_user_octets_from_client{user="hello"} 5349946457 (4.98 GB)
telemt_user_octets_to_client{user="hello"} 24532680907 (22.85 GB)
telemt_user_msgs_from_client{user="hello"} 2553800
telemt_user_msgs_to_client{user="hello"} 4477252
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 28670.5 (7h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 48681
telemt_connections_bad_total 11618
telemt_handshake_timeouts_total 831
telemt_upstream_connect_attempt_total 34414
telemt_upstream_connect_success_total 32714
telemt_upstream_connect_fail_total 1700
telemt_upstream_connect_attempts_per_request{bucket="1"} 34414
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27302
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5341
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 62
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1700
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 32710
telemt_user_connections_current{user="hello"} 108
telemt_user_octets_from_client{user="hello"} 692413316 (660.34 MB)
telemt_user_octets_to_client{user="hello"} 22283377095 (20.75 GB)
telemt_user_msgs_from_client{user="hello"} 720663
telemt_user_msgs_to_client{user="hello"} 9227359
telemt_user_unique_ips_current{user="hello"} 44
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## rdp-onedash.ru

Не удалось получить метрики для этого сервера.

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 28671.3 (7h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 43093
telemt_connections_bad_total 761
telemt_handshake_timeouts_total 215
telemt_upstream_connect_attempt_total 39941
telemt_upstream_connect_success_total 39940
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 39941
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33139
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6791
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 39936
telemt_user_connections_current{user="hello"} 152
telemt_user_octets_from_client{user="hello"} 755311861 (720.32 MB)
telemt_user_octets_to_client{user="hello"} 37058678481 (34.51 GB)
telemt_user_msgs_from_client{user="hello"} 1062194
telemt_user_msgs_to_client{user="hello"} 5015793
telemt_user_unique_ips_current{user="hello"} 57
telemt_user_unique_ips_recent_window{user="hello"} 29
```