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

# Server Metrics 2026-03-12 05:48:33 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 29007.6 (8h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 73929
telemt_connections_bad_total 2109
telemt_handshake_timeouts_total 2196
telemt_upstream_connect_attempt_total 66176
telemt_upstream_connect_success_total 66158
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 66176
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 55763
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10351
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 44
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 66154
telemt_user_connections_current{user="hello"} 280
telemt_user_octets_from_client{user="hello"} 663895535 (633.14 MB)
telemt_user_octets_to_client{user="hello"} 20869024665 (19.44 GB)
telemt_user_msgs_from_client{user="hello"} 990982
telemt_user_msgs_to_client{user="hello"} 2383125
telemt_user_unique_ips_current{user="hello"} 85
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 28995.7 (8h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 29207
telemt_connections_bad_total 209
telemt_handshake_timeouts_total 149
telemt_upstream_connect_attempt_total 27836
telemt_upstream_connect_success_total 27829
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 27836
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24129
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3682
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 27825
telemt_user_connections_current{user="hello"} 113
telemt_user_octets_from_client{user="hello"} 252028206 (240.35 MB)
telemt_user_octets_to_client{user="hello"} 14769489960 (13.76 GB)
telemt_user_msgs_from_client{user="hello"} 519817
telemt_user_msgs_to_client{user="hello"} 4497907
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 28969.4 (8h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 45426
telemt_connections_bad_total 671
telemt_handshake_timeouts_total 1039
telemt_upstream_connect_attempt_total 40786
telemt_upstream_connect_success_total 40785
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 40786
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33954
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6814
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 40781
telemt_user_connections_current{user="hello"} 168
telemt_user_octets_from_client{user="hello"} 5355869020 (4.99 GB)
telemt_user_octets_to_client{user="hello"} 25142385934 (23.42 GB)
telemt_user_msgs_from_client{user="hello"} 2569161
telemt_user_msgs_to_client{user="hello"} 4636655
telemt_user_unique_ips_current{user="hello"} 55
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 28994.6 (8h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 49675
telemt_connections_bad_total 11922
telemt_handshake_timeouts_total 835
telemt_upstream_connect_attempt_total 35067
telemt_upstream_connect_success_total 33366
telemt_upstream_connect_fail_total 1701
telemt_upstream_connect_attempts_per_request{bucket="1"} 35067
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27848
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5447
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 62
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1701
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 33362
telemt_user_connections_current{user="hello"} 107
telemt_user_octets_from_client{user="hello"} 919166309 (876.59 MB)
telemt_user_octets_to_client{user="hello"} 22442937801 (20.90 GB)
telemt_user_msgs_from_client{user="hello"} 806165
telemt_user_msgs_to_client{user="hello"} 9275573
telemt_user_unique_ips_current{user="hello"} 33
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## rdp-onedash.ru

Не удалось получить метрики для этого сервера.

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 28995.4 (8h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 44012
telemt_connections_bad_total 762
telemt_handshake_timeouts_total 219
telemt_upstream_connect_attempt_total 40844
telemt_upstream_connect_success_total 40843
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 40844
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33904
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6929
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 40839
telemt_user_connections_current{user="hello"} 145
telemt_user_octets_from_client{user="hello"} 764816574 (729.39 MB)
telemt_user_octets_to_client{user="hello"} 38113898842 (35.50 GB)
telemt_user_msgs_from_client{user="hello"} 1087237
telemt_user_msgs_to_client{user="hello"} 5142451
telemt_user_unique_ips_current{user="hello"} 60
telemt_user_unique_ips_recent_window{user="hello"} 31
```