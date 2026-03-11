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

# Server Metrics 2026-03-11 19:44:58 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 9879.3 (2h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 37538
telemt_connections_bad_total 2100
telemt_handshake_timeouts_total 146
telemt_upstream_connect_attempt_total 33882
telemt_upstream_connect_success_total 33873
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 33882
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30633
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3176
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 64
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 33871
telemt_user_connections_current{user="hello"} 298
telemt_user_octets_from_client{user="hello"} 829586829 (791.16 MB)
telemt_user_octets_to_client{user="hello"} 19600776046 (18.25 GB)
telemt_user_msgs_from_client{user="hello"} 843727
telemt_user_msgs_to_client{user="hello"} 1630330
telemt_user_unique_ips_current{user="hello"} 85
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 9867.7 (2h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 18109
telemt_connections_bad_total 37
telemt_handshake_timeouts_total 250
telemt_upstream_connect_attempt_total 16627
telemt_upstream_connect_success_total 16608
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 16627
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14174
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2116
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 318
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 16606
telemt_user_connections_current{user="hello"} 129
telemt_user_octets_from_client{user="hello"} 211457902 (201.66 MB)
telemt_user_octets_to_client{user="hello"} 8711151663 (8.11 GB)
telemt_user_msgs_from_client{user="hello"} 351002
telemt_user_msgs_to_client{user="hello"} 3362634
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 9887.6 (2h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20972
telemt_connections_bad_total 25
telemt_handshake_timeouts_total 177
telemt_upstream_connect_attempt_total 19567
telemt_upstream_connect_success_total 19565
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 19567
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17783
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1764
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 19563
telemt_user_connections_current{user="hello"} 86
telemt_user_octets_from_client{user="hello"} 200964727 (191.65 MB)
telemt_user_octets_to_client{user="hello"} 8931731854 (8.32 GB)
telemt_user_msgs_from_client{user="hello"} 398200
telemt_user_msgs_to_client{user="hello"} 2209953
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 9882.9 (2h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 22740
telemt_connections_bad_total 1754
telemt_handshake_timeouts_total 376
telemt_upstream_connect_attempt_total 19657
telemt_upstream_connect_success_total 19596
telemt_upstream_connect_fail_total 61
telemt_upstream_connect_attempts_per_request{bucket="1"} 19657
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17733
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1800
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 61
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 19594
telemt_user_connections_current{user="hello"} 93
telemt_user_octets_from_client{user="hello"} 602561425 (574.65 MB)
telemt_user_octets_to_client{user="hello"} 11059260640 (10.30 GB)
telemt_user_msgs_from_client{user="hello"} 485949
telemt_user_msgs_to_client{user="hello"} 3005896
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 9891.1 (2h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 24114
telemt_connections_bad_total 1899
telemt_handshake_timeouts_total 160
telemt_upstream_connect_attempt_total 21233
telemt_upstream_connect_success_total 21232
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 21233
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18526
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2681
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 21230
telemt_user_connections_current{user="hello"} 172
telemt_user_octets_from_client{user="hello"} 370910203 (353.73 MB)
telemt_user_octets_to_client{user="hello"} 7891980177 (7.35 GB)
telemt_user_msgs_from_client{user="hello"} 469562
telemt_user_msgs_to_client{user="hello"} 2718288
telemt_user_unique_ips_current{user="hello"} 67
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 84497.5 (23h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 567
telemt_connections_bad_total 491
telemt_handshake_timeouts_total 17
telemt_upstream_connect_attempt_total 59
telemt_upstream_connect_success_total 59
telemt_upstream_connect_attempts_per_request{bucket="1"} 59
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 47
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 51
telemt_user_octets_from_client{user="hello"} 201572 (196.85 KB)
telemt_user_octets_to_client{user="hello"} 1307210 (1.25 MB)
telemt_user_msgs_from_client{user="hello"} 250
telemt_user_msgs_to_client{user="hello"} 389
```