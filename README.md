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

# Server Metrics 2026-03-15 01:28:52 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 11664.6 (3h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 24374
telemt_connections_bad_total 366
telemt_handshake_timeouts_total 267
telemt_upstream_connect_attempt_total 2967
telemt_upstream_connect_success_total 2951
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 2967
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1340
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1607
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_reconnect_attempts_total 2371
telemt_me_reconnect_success_total 2360
telemt_me_reader_eof_total 2489
telemt_me_idle_close_by_peer_total 2489
telemt_me_route_drop_no_conn_total 6824
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 22992
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 132
telemt_desync_full_logged_total 60
telemt_desync_suppressed_total 72
telemt_desync_frames_bucket_total{bucket="1_2"} 23
telemt_desync_frames_bucket_total{bucket="3_10"} 44
telemt_desync_frames_bucket_total{bucket="gt_10"} 65
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 2363
telemt_me_writer_restored_same_endpoint_total 2329
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 22990
telemt_user_connections_current{user="hello"} 230
telemt_user_octets_from_client{user="hello"} 245097732 (233.74 MB)
telemt_user_octets_to_client{user="hello"} 9180703832 (8.55 GB)
telemt_user_unique_ips_current{user="hello"} 68
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 11670.9 (3h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11167
telemt_connections_bad_total 16
telemt_handshake_timeouts_total 31
telemt_upstream_connect_attempt_total 3214
telemt_upstream_connect_success_total 3214
telemt_upstream_connect_attempts_per_request{bucket="1"} 3214
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1418
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1796
telemt_me_reconnect_attempts_total 2628
telemt_me_reconnect_success_total 2619
telemt_me_reader_eof_total 2782
telemt_me_idle_close_by_peer_total 2782
telemt_me_route_drop_no_conn_total 3905
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10553
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 2634
telemt_me_writer_restored_same_endpoint_total 2603
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 15
telemt_user_connections_total{user="hello"} 10556
telemt_user_connections_current{user="hello"} 110
telemt_user_octets_from_client{user="hello"} 145493096 (138.75 MB)
telemt_user_octets_to_client{user="hello"} 1830900704 (1.71 GB)
telemt_user_unique_ips_current{user="hello"} 26
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 11663.5 (3h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11470
telemt_connections_bad_total 84
telemt_handshake_timeouts_total 216
telemt_upstream_connect_attempt_total 3073
telemt_upstream_connect_success_total 3072
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 3073
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1357
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1711
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 2490
telemt_me_reconnect_success_total 2476
telemt_me_reader_eof_total 2658
telemt_me_idle_close_by_peer_total 2658
telemt_me_route_drop_no_conn_total 3829
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10832
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 2491
telemt_me_writer_restored_same_endpoint_total 2472
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 15
telemt_user_connections_total{user="hello"} 10794
telemt_user_connections_current{user="hello"} 71
telemt_user_octets_from_client{user="hello"} 5397241880 (5.03 GB)
telemt_user_octets_to_client{user="hello"} 11997910168 (11.17 GB)
telemt_user_unique_ips_current{user="hello"} 26
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 11663.3 (3h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11738
telemt_connections_bad_total 75
telemt_handshake_timeouts_total 39
telemt_upstream_connect_attempt_total 2814
telemt_upstream_connect_success_total 2813
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 2814
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1279
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1526
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 2235
telemt_me_reconnect_success_total 2224
telemt_me_reader_eof_total 2355
telemt_me_idle_close_by_peer_total 2355
telemt_me_route_drop_no_conn_total 4632
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 11308
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 54
telemt_desync_full_logged_total 10
telemt_desync_suppressed_total 44
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 25
telemt_desync_frames_bucket_total{bucket="gt_10"} 23
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 2241
telemt_me_writer_restored_same_endpoint_total 2213
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 17
telemt_user_connections_total{user="hello"} 11306
telemt_user_connections_current{user="hello"} 129
telemt_user_octets_from_client{user="hello"} 316612808 (301.95 MB)
telemt_user_octets_to_client{user="hello"} 8795125036 (8.19 GB)
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 11663.4 (3h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14746
telemt_connections_bad_total 2389
telemt_handshake_timeouts_total 385
telemt_upstream_connect_attempt_total 3783
telemt_upstream_connect_success_total 3735
telemt_upstream_connect_fail_total 48
telemt_upstream_connect_attempts_per_request{bucket="1"} 3783
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1738
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1987
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 48
telemt_me_reconnect_attempts_total 3221
telemt_me_reconnect_success_total 3142
telemt_me_reader_eof_total 3279
telemt_me_idle_close_by_peer_total 3279
telemt_me_route_drop_no_conn_total 4056
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 11687
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 3152
telemt_me_refill_failed_total 2
telemt_me_writer_restored_same_endpoint_total 3130
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 29
telemt_me_writer_removed_unexpected_minus_restored_total 10
telemt_user_connections_total{user="hello"} 11675
telemt_user_connections_current{user="hello"} 43
telemt_user_octets_from_client{user="hello"} 174197796 (166.13 MB)
telemt_user_octets_to_client{user="hello"} 6444723512 (6.00 GB)
telemt_user_unique_ips_current{user="hello"} 22
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 11662.6 (3h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 37284
telemt_connections_bad_total 1004
telemt_handshake_timeouts_total 147
telemt_upstream_connect_attempt_total 2554
telemt_upstream_connect_success_total 2537
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 2554
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1271
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1266
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_reconnect_attempts_total 1954
telemt_me_reconnect_success_total 1947
telemt_me_reader_eof_total 2036
telemt_me_idle_close_by_peer_total 2036
telemt_me_route_drop_no_conn_total 21026
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 36589
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16
telemt_desync_full_logged_total 5
telemt_desync_suppressed_total 11
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 4
telemt_desync_frames_bucket_total{bucket="gt_10"} 6
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 1938
telemt_me_writer_restored_same_endpoint_total 1920
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_user_connections_total{user="hello"} 35158
telemt_user_connections_current{user="hello"} 262
telemt_user_octets_from_client{user="hello"} 789190328 (752.63 MB)
telemt_user_octets_to_client{user="hello"} 23821132136 (22.19 GB)
telemt_user_unique_ips_current{user="hello"} 115
telemt_user_unique_ips_recent_window{user="hello"} 32
```