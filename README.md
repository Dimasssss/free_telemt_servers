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

# Server Metrics 2026-03-11 07:21:54 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 60945.7 (16h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 166234
telemt_connections_bad_total 3537
telemt_handshake_timeouts_total 4000
telemt_upstream_connect_attempt_total 150439
telemt_upstream_connect_success_total 150392
telemt_upstream_connect_fail_total 47
telemt_upstream_connect_attempts_per_request{bucket="1"} 150439
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 137158
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13178
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 56
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 47
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 150384
telemt_user_connections_current{user="hello"} 319
telemt_user_octets_from_client{user="hello"} 3547350224 (3.30 GB)
telemt_user_octets_to_client{user="hello"} 99025487045 (92.22 GB)
telemt_user_msgs_from_client{user="hello"} 3779194
telemt_user_msgs_to_client{user="hello"} 7101435
telemt_user_unique_ips_current{user="hello"} 93
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 60945.4 (16h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 65545
telemt_connections_bad_total 460
telemt_handshake_timeouts_total 3070
telemt_upstream_connect_attempt_total 58814
telemt_upstream_connect_success_total 58800
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 58814
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 50311
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8257
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 232
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 58794
telemt_user_connections_current{user="hello"} 91
telemt_user_octets_from_client{user="hello"} 4666661502 (4.35 GB)
telemt_user_octets_to_client{user="hello"} 50792567621 (47.30 GB)
telemt_user_msgs_from_client{user="hello"} 2890134
telemt_user_msgs_to_client{user="hello"} 12366490
telemt_user_unique_ips_current{user="hello"} 28
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 60945.3 (16h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 89697
telemt_connections_bad_total 746
telemt_handshake_timeouts_total 4972
telemt_upstream_connect_attempt_total 78665
telemt_upstream_connect_success_total 78662
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 78665
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 69922
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8679
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 60
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 78656
telemt_user_connections_current{user="hello"} 88
telemt_user_octets_from_client{user="hello"} 11868763222 (11.05 GB)
telemt_user_octets_to_client{user="hello"} 74515262638 (69.40 GB)
telemt_user_msgs_from_client{user="hello"} 5348012
telemt_user_msgs_to_client{user="hello"} 14317039
telemt_user_unique_ips_current{user="hello"} 45
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 60944.0 (16h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 96372
telemt_connections_bad_total 217
telemt_handshake_timeouts_total 665
telemt_upstream_connect_attempt_total 92365
telemt_upstream_connect_success_total 92160
telemt_upstream_connect_fail_total 205
telemt_upstream_connect_attempts_per_request{bucket="1"} 92365
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 79740
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12111
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 49
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 260
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 205
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 92154
telemt_user_connections_current{user="hello"} 150
telemt_user_octets_from_client{user="hello"} 2267911300 (2.11 GB)
telemt_user_octets_to_client{user="hello"} 61920625453 (57.67 GB)
telemt_user_msgs_from_client{user="hello"} 2148370
telemt_user_msgs_to_client{user="hello"} 15283928
telemt_user_unique_ips_current{user="hello"} 45
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 60945.2 (16h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 162195
telemt_connections_bad_total 13443
telemt_handshake_timeouts_total 1853
telemt_upstream_connect_attempt_total 128921
telemt_upstream_connect_success_total 128671
telemt_upstream_connect_fail_total 250
telemt_upstream_connect_attempts_per_request{bucket="1"} 128921
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 110479
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17951
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 241
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 250
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 128665
telemt_user_connections_current{user="hello"} 200
telemt_user_octets_from_client{user="hello"} 2568046908 (2.39 GB)
telemt_user_octets_to_client{user="hello"} 124720651180 (116.16 GB)
telemt_user_msgs_from_client{user="hello"} 2968485
telemt_user_msgs_to_client{user="hello"} 15890282
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 39914.5 (11h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 220
telemt_connections_bad_total 200
telemt_handshake_timeouts_total 9
telemt_upstream_connect_attempt_total 15
telemt_upstream_connect_success_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 15
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 11
telemt_user_octets_from_client{user="hello"} 7489 (7.31 KB)
telemt_user_octets_to_client{user="hello"} 2462 (2.40 KB)
telemt_user_msgs_from_client{user="hello"} 23
telemt_user_msgs_to_client{user="hello"} 15
```