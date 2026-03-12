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

# Server Metrics 2026-03-12 05:26:56 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 27710.8 (7h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 67885
telemt_connections_bad_total 2104
telemt_handshake_timeouts_total 1817
telemt_upstream_connect_attempt_total 61012
telemt_upstream_connect_success_total 60994
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 61012
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 51678
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9272
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 44
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 60990
telemt_user_connections_current{user="hello"} 271
telemt_user_octets_from_client{user="hello"} 623835197 (594.94 MB)
telemt_user_octets_to_client{user="hello"} 20046715676 (18.67 GB)
telemt_user_msgs_from_client{user="hello"} 935324
telemt_user_msgs_to_client{user="hello"} 2263984
telemt_user_unique_ips_current{user="hello"} 78
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 27699.2 (7h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 26758
telemt_connections_bad_total 208
telemt_handshake_timeouts_total 143
telemt_upstream_connect_attempt_total 25464
telemt_upstream_connect_success_total 25458
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 25464
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22177
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3266
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 25454
telemt_user_connections_current{user="hello"} 151
telemt_user_octets_from_client{user="hello"} 232102428 (221.35 MB)
telemt_user_octets_to_client{user="hello"} 13921225688 (12.97 GB)
telemt_user_msgs_from_client{user="hello"} 477315
telemt_user_msgs_to_client{user="hello"} 4058883
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 27672.7 (7h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 42050
telemt_connections_bad_total 558
telemt_handshake_timeouts_total 1027
telemt_upstream_connect_attempt_total 37653
telemt_upstream_connect_success_total 37652
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 37653
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31390
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6252
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 37648
telemt_user_connections_current{user="hello"} 125
telemt_user_octets_from_client{user="hello"} 5334935620 (4.97 GB)
telemt_user_octets_to_client{user="hello"} 22992612731 (21.41 GB)
telemt_user_msgs_from_client{user="hello"} 2510905
telemt_user_msgs_to_client{user="hello"} 4137688
telemt_user_unique_ips_current{user="hello"} 45
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 27698.0 (7h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 46797
telemt_connections_bad_total 11617
telemt_handshake_timeouts_total 822
telemt_upstream_connect_attempt_total 32622
telemt_upstream_connect_success_total 30922
telemt_upstream_connect_fail_total 1700
telemt_upstream_connect_attempts_per_request{bucket="1"} 32622
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25827
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5025
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1700
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 30918
telemt_user_connections_current{user="hello"} 85
telemt_user_octets_from_client{user="hello"} 282772262 (269.67 MB)
telemt_user_octets_to_client{user="hello"} 22090772576 (20.57 GB)
telemt_user_msgs_from_client{user="hello"} 561913
telemt_user_msgs_to_client{user="hello"} 9140167
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## rdp-onedash.ru

Не удалось получить метрики для этого сервера.

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 27698.8 (7h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 40208
telemt_connections_bad_total 761
telemt_handshake_timeouts_total 200
telemt_upstream_connect_attempt_total 37148
telemt_upstream_connect_success_total 37147
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 37148
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30860
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6277
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 37143
telemt_user_connections_current{user="hello"} 158
telemt_user_octets_from_client{user="hello"} 711555354 (678.59 MB)
telemt_user_octets_to_client{user="hello"} 35493468217 (33.06 GB)
telemt_user_msgs_from_client{user="hello"} 989570
telemt_user_msgs_to_client{user="hello"} 4810189
telemt_user_unique_ips_current{user="hello"} 57
telemt_user_unique_ips_recent_window{user="hello"} 27
```