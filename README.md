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

## 4vps.su
- Локация: Польша, Варшава
- Тариф: PL-cx21
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 2 Gbit/s
- Цена в месяц: 770 RUB
- Оплачен до: 16 апреля
- Ссылка:
```bash
tg://proxy?server=s7.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

# Server Metrics 2026-03-19 01:27:23 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 13136.1 (3h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 149900
telemt_connections_bad_total 18607
telemt_connections_current 606
telemt_connections_me_current 606
telemt_handshake_timeouts_total 2261
telemt_upstream_connect_attempt_total 2653
telemt_upstream_connect_success_total 2608
telemt_upstream_connect_fail_total 45
telemt_upstream_connect_attempts_per_request{bucket="1"} 2653
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1243
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1363
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 45
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 1943
telemt_me_reconnect_success_total 1937
telemt_me_reader_eof_total 2013
telemt_me_idle_close_by_peer_total 2013
telemt_me_seq_mismatch_total 4
telemt_me_route_drop_no_conn_total 45323
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 122535
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 24
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 767
telemt_desync_full_logged_total 204
telemt_desync_suppressed_total 563
telemt_desync_frames_bucket_total{bucket="1_2"} 279
telemt_desync_frames_bucket_total{bucket="3_10"} 320
telemt_desync_frames_bucket_total{bucket="gt_10"} 168
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 1942
telemt_me_writer_restored_same_endpoint_total 1923
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 119767
telemt_user_connections_current{user="hello"} 606
telemt_user_octets_from_client{user="hello"} 1197564200 (1.12 GB)
telemt_user_octets_to_client{user="hello"} 40187439156 (37.43 GB)
telemt_user_unique_ips_current{user="hello"} 260
telemt_user_unique_ips_recent_window{user="hello"} 77
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 13139.8 (3h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 296743
telemt_connections_bad_total 20585
telemt_connections_current 1445
telemt_connections_me_current 1445
telemt_handshake_timeouts_total 4791
telemt_upstream_connect_attempt_total 2497
telemt_upstream_connect_success_total 2448
telemt_upstream_connect_fail_total 49
telemt_upstream_connect_attempts_per_request{bucket="1"} 2497
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1158
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1284
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 49
telemt_me_reconnect_attempts_total 1777
telemt_me_reconnect_success_total 1771
telemt_me_reader_eof_total 1865
telemt_me_idle_close_by_peer_total 1865
telemt_me_seq_mismatch_total 3
telemt_me_route_drop_no_conn_total 92484
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 254162
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 25
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 921
telemt_desync_full_logged_total 316
telemt_desync_suppressed_total 605
telemt_desync_frames_bucket_total{bucket="1_2"} 215
telemt_desync_frames_bucket_total{bucket="3_10"} 333
telemt_desync_frames_bucket_total{bucket="gt_10"} 373
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 1801
telemt_me_writer_restored_same_endpoint_total 1758
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 30
telemt_user_connections_total{user="hello"} 254204
telemt_user_connections_current{user="hello"} 1445
telemt_user_octets_from_client{user="hello"} 11131968860 (10.37 GB)
telemt_user_octets_to_client{user="hello"} 97047489136 (90.38 GB)
telemt_user_unique_ips_current{user="hello"} 584
telemt_user_unique_ips_recent_window{user="hello"} 131
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 13137.1 (3h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 237403
telemt_connections_bad_total 42085
telemt_connections_current 1077
telemt_connections_me_current 1077
telemt_handshake_timeouts_total 6058
telemt_upstream_connect_attempt_total 2572
telemt_upstream_connect_success_total 2572
telemt_upstream_connect_attempts_per_request{bucket="1"} 2572
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1288
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1280
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 1900
telemt_me_reconnect_success_total 1895
telemt_me_reader_eof_total 1993
telemt_me_idle_close_by_peer_total 1993
telemt_me_route_drop_no_conn_total 75224
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 182174
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 874
telemt_desync_full_logged_total 321
telemt_desync_suppressed_total 553
telemt_desync_frames_bucket_total{bucket="1_2"} 166
telemt_desync_frames_bucket_total{bucket="3_10"} 349
telemt_desync_frames_bucket_total{bucket="gt_10"} 359
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 1923
telemt_me_writer_restored_same_endpoint_total 1879
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 28
telemt_user_connections_total{user="hello"} 182170
telemt_user_connections_current{user="hello"} 1077
telemt_user_octets_from_client{user="hello"} 2246859284 (2.09 GB)
telemt_user_octets_to_client{user="hello"} 108673113400 (101.21 GB)
telemt_user_unique_ips_current{user="hello"} 485
telemt_user_unique_ips_recent_window{user="hello"} 114
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 13190.4 (3h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 261346
telemt_connections_bad_total 27721
telemt_connections_current 898
telemt_connections_me_current 898
telemt_handshake_timeouts_total 4611
telemt_upstream_connect_attempt_total 2418
telemt_upstream_connect_success_total 2418
telemt_upstream_connect_attempts_per_request{bucket="1"} 2418
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1245
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1165
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_reconnect_attempts_total 1747
telemt_me_reconnect_success_total 1741
telemt_me_reader_eof_total 1820
telemt_me_idle_close_by_peer_total 1820
telemt_me_route_drop_no_conn_total 79812
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 184085
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 515
telemt_desync_full_logged_total 189
telemt_desync_suppressed_total 326
telemt_desync_frames_bucket_total{bucket="1_2"} 101
telemt_desync_frames_bucket_total{bucket="3_10"} 208
telemt_desync_frames_bucket_total{bucket="gt_10"} 206
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 1761
telemt_me_writer_restored_same_endpoint_total 1717
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 268
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 184002
telemt_user_connections_current{user="hello"} 898
telemt_user_octets_from_client{user="hello"} 1774842940 (1.65 GB)
telemt_user_octets_to_client{user="hello"} 62458346808 (58.17 GB)
telemt_user_unique_ips_current{user="hello"} 401
telemt_user_unique_ips_recent_window{user="hello"} 98
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 13133.7 (3h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 260443
telemt_connections_bad_total 15713
telemt_connections_current 1112
telemt_connections_me_current 1112
telemt_handshake_timeouts_total 8558
telemt_upstream_connect_attempt_total 2468
telemt_upstream_connect_success_total 2455
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 2468
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1192
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1255
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_reconnect_attempts_total 1784
telemt_me_reconnect_success_total 1774
telemt_me_reader_eof_total 1858
telemt_me_idle_close_by_peer_total 1858
telemt_me_route_drop_no_conn_total 80832
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 198505
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 806
telemt_desync_full_logged_total 308
telemt_desync_suppressed_total 498
telemt_desync_frames_bucket_total{bucket="1_2"} 215
telemt_desync_frames_bucket_total{bucket="3_10"} 285
telemt_desync_frames_bucket_total{bucket="gt_10"} 306
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 1783
telemt_me_writer_restored_same_endpoint_total 1750
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 198428
telemt_user_connections_current{user="hello"} 1112
telemt_user_octets_from_client{user="hello"} 5169705220 (4.81 GB)
telemt_user_octets_to_client{user="hello"} 113053888184 (105.29 GB)
telemt_user_unique_ips_current{user="hello"} 494
telemt_user_unique_ips_recent_window{user="hello"} 112
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 13145.2 (3h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 65325
telemt_connections_bad_total 9146
telemt_connections_current 304
telemt_connections_me_current 304
telemt_handshake_timeouts_total 231
telemt_upstream_connect_attempt_total 3786
telemt_upstream_connect_success_total 3671
telemt_upstream_connect_fail_total 115
telemt_upstream_connect_attempts_per_request{bucket="1"} 3786
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1731
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1940
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 115
telemt_me_reconnect_attempts_total 4829
telemt_me_reconnect_success_total 3001
telemt_me_reader_eof_total 3139
telemt_me_idle_close_by_peer_total 3139
telemt_me_route_drop_no_conn_total 25091
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 54260
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 27
telemt_desync_full_logged_total 7
telemt_desync_suppressed_total 20
telemt_desync_frames_bucket_total{bucket="1_2"} 16
telemt_desync_frames_bucket_total{bucket="3_10"} 10
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 3049
telemt_me_refill_failed_total 57
telemt_me_writer_restored_same_endpoint_total 2971
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 48
telemt_user_connections_total{user="hello"} 54260
telemt_user_connections_current{user="hello"} 304
telemt_user_octets_from_client{user="hello"} 781942720 (745.72 MB)
telemt_user_octets_to_client{user="hello"} 34087730668 (31.75 GB)
telemt_user_unique_ips_current{user="hello"} 136
telemt_user_unique_ips_recent_window{user="hello"} 42
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 13135.9 (3h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 184373
telemt_connections_bad_total 21316
telemt_connections_current 978
telemt_connections_me_current 978
telemt_handshake_timeouts_total 8358
telemt_upstream_connect_attempt_total 2803
telemt_upstream_connect_success_total 2803
telemt_upstream_connect_attempts_per_request{bucket="1"} 2803
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1468
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1333
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 2132
telemt_me_reconnect_success_total 2126
telemt_me_reader_eof_total 2228
telemt_me_idle_close_by_peer_total 2228
telemt_me_route_drop_no_conn_total 54901
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 150420
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 966
telemt_desync_full_logged_total 386
telemt_desync_suppressed_total 580
telemt_desync_frames_bucket_total{bucket="1_2"} 173
telemt_desync_frames_bucket_total{bucket="3_10"} 387
telemt_desync_frames_bucket_total{bucket="gt_10"} 406
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 2149
telemt_me_writer_restored_same_endpoint_total 2111
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 23
telemt_user_connections_total{user="hello"} 150443
telemt_user_connections_current{user="hello"} 978
telemt_user_octets_from_client{user="hello"} 1556374616 (1.45 GB)
telemt_user_octets_to_client{user="hello"} 78262584408 (72.89 GB)
telemt_user_unique_ips_current{user="hello"} 428
telemt_user_unique_ips_recent_window{user="hello"} 81
```