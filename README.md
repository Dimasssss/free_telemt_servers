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

# Server Metrics 2026-03-11 05:45:05 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 55136.4 (15h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 143069
telemt_connections_bad_total 3469
telemt_handshake_timeouts_total 3636
telemt_upstream_connect_attempt_total 129598
telemt_upstream_connect_success_total 129554
telemt_upstream_connect_fail_total 44
telemt_upstream_connect_attempts_per_request{bucket="1"} 129598
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 118181
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11318
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 55
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 44
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 129548
telemt_user_connections_current{user="hello"} 263
telemt_user_octets_from_client{user="hello"} 3144986097 (2.93 GB)
telemt_user_octets_to_client{user="hello"} 89470991408 (83.33 GB)
telemt_user_msgs_from_client{user="hello"} 3325992
telemt_user_msgs_to_client{user="hello"} 6306343
telemt_user_unique_ips_current{user="hello"} 69
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 55135.7 (15h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 57646
telemt_connections_bad_total 447
telemt_handshake_timeouts_total 2978
telemt_upstream_connect_attempt_total 51282
telemt_upstream_connect_success_total 51270
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 51282
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 43448
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7593
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 229
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 51264
telemt_user_connections_current{user="hello"} 38
telemt_user_octets_from_client{user="hello"} 4527875287 (4.22 GB)
telemt_user_octets_to_client{user="hello"} 47489958032 (44.23 GB)
telemt_user_msgs_from_client{user="hello"} 2726753
telemt_user_msgs_to_client{user="hello"} 11221760
telemt_user_unique_ips_current{user="hello"} 18
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 55135.4 (15h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 78593
telemt_connections_bad_total 726
telemt_handshake_timeouts_total 4338
telemt_upstream_connect_attempt_total 69102
telemt_upstream_connect_success_total 69099
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 69102
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 61264
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7783
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 51
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 69093
telemt_user_connections_current{user="hello"} 83
telemt_user_octets_from_client{user="hello"} 11797303387 (10.99 GB)
telemt_user_octets_to_client{user="hello"} 71500138765 (66.59 GB)
telemt_user_msgs_from_client{user="hello"} 5216480
telemt_user_msgs_to_client{user="hello"} 13475739
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 55134.6 (15h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 83066
telemt_connections_bad_total 170
telemt_handshake_timeouts_total 620
telemt_upstream_connect_attempt_total 79509
telemt_upstream_connect_success_total 79336
telemt_upstream_connect_fail_total 172
telemt_upstream_connect_attempts_per_request{bucket="1"} 79508
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 68649
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10430
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 38
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 219
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 172
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 79330
telemt_user_connections_current{user="hello"} 104
telemt_user_octets_from_client{user="hello"} 1863899567 (1.74 GB)
telemt_user_octets_to_client{user="hello"} 51752221214 (48.20 GB)
telemt_user_msgs_from_client{user="hello"} 1800447
telemt_user_msgs_to_client{user="hello"} 11678841
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 55135.7 (15h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 136516
telemt_connections_bad_total 12337
telemt_handshake_timeouts_total 1743
telemt_upstream_connect_attempt_total 112361
telemt_upstream_connect_success_total 112112
telemt_upstream_connect_fail_total 249
telemt_upstream_connect_attempts_per_request{bucket="1"} 112361
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 96437
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15442
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 233
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 249
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 112106
telemt_user_connections_current{user="hello"} 145
telemt_user_octets_from_client{user="hello"} 2438698747 (2.27 GB)
telemt_user_octets_to_client{user="hello"} 107731515435 (100.33 GB)
telemt_user_msgs_from_client{user="hello"} 2700700
telemt_user_msgs_to_client{user="hello"} 14130761
telemt_user_unique_ips_current{user="hello"} 51
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 34105.1 (9h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 153
telemt_connections_bad_total 144
telemt_handshake_timeouts_total 7
telemt_upstream_connect_attempt_total 4
telemt_upstream_connect_success_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 4
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4
telemt_me_floor_mode{mode="adaptive"} 1
```