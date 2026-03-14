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

# Server Metrics 2026-03-14 08:39:25 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 176765.5 (49h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 680961
telemt_connections_bad_total 32563
telemt_handshake_timeouts_total 13278
telemt_upstream_connect_attempt_total 44905
telemt_upstream_connect_success_total 44676
telemt_upstream_connect_fail_total 229
telemt_upstream_connect_attempts_per_request{bucket="1"} 44905
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20465
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24059
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 152
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 229
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 5780
telemt_me_reconnect_attempts_total 40181
telemt_me_reconnect_success_total 35483
telemt_me_reader_eof_total 37939
telemt_me_idle_close_by_peer_total 37938
telemt_me_route_drop_no_conn_total 225202
telemt_me_route_drop_channel_closed_total 32
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 581445
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2240
telemt_desync_full_logged_total 760
telemt_desync_suppressed_total 1480
telemt_desync_frames_bucket_total{bucket="1_2"} 484
telemt_desync_frames_bucket_total{bucket="3_10"} 821
telemt_desync_frames_bucket_total{bucket="gt_10"} 935
telemt_pool_swap_total 163
telemt_me_writer_removed_unexpected_total 36009
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 35463
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 526
telemt_user_connections_total{user="hello"} 581328
telemt_user_connections_current{user="hello"} 367
telemt_user_octets_from_client{user="hello"} 16975478566 (15.81 GB)
telemt_user_octets_to_client{user="hello"} 279201845064 (260.03 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 110
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 176659.4 (49h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 342850
telemt_connections_bad_total 2784
telemt_handshake_timeouts_total 3017
telemt_upstream_connect_attempt_total 152336
telemt_upstream_connect_success_total 151018
telemt_upstream_connect_fail_total 1318
telemt_upstream_connect_attempts_per_request{bucket="1"} 152336
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 110743
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 37836
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2438
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1318
telemt_me_keepalive_timeout_total 5332
telemt_me_reconnect_attempts_total 180367
telemt_me_reconnect_success_total 38898
telemt_me_reader_eof_total 44370
telemt_me_idle_close_by_peer_total 44370
telemt_me_route_drop_no_conn_total 115335
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 220328
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 43
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 33
telemt_desync_full_logged_total 11
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 19
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 43696
telemt_me_refill_failed_total 4414
telemt_me_writer_restored_same_endpoint_total 38881
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 4798
telemt_user_connections_total{user="hello"} 323434
telemt_user_connections_current{user="hello"} 139
telemt_user_octets_from_client{user="hello"} 3331383171 (3.10 GB)
telemt_user_octets_to_client{user="hello"} 104767719787 (97.57 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 45
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 176623.1 (49h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 400625
telemt_connections_bad_total 3197
telemt_handshake_timeouts_total 35576
telemt_upstream_connect_attempt_total 46753
telemt_upstream_connect_success_total 46744
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 46753
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21397
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25279
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3511
telemt_me_reconnect_attempts_total 39181
telemt_me_reconnect_success_total 37887
telemt_me_reader_eof_total 40716
telemt_me_idle_close_by_peer_total 40716
telemt_me_route_drop_no_conn_total 144771
telemt_me_route_drop_channel_closed_total 22
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 347753
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 123
telemt_desync_full_logged_total 55
telemt_desync_suppressed_total 68
telemt_desync_frames_bucket_total{bucket="1_2"} 13
telemt_desync_frames_bucket_total{bucket="3_10"} 41
telemt_desync_frames_bucket_total{bucket="gt_10"} 69
telemt_pool_swap_total 166
telemt_me_writer_removed_unexpected_total 38349
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 37866
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 462
telemt_user_connections_total{user="hello"} 347515
telemt_user_connections_current{user="hello"} 117
telemt_user_octets_from_client{user="hello"} 13664271676 (12.73 GB)
telemt_user_octets_to_client{user="hello"} 145135535728 (135.17 GB)
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 176598.5 (49h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 502790
telemt_connections_bad_total 16285
telemt_handshake_timeouts_total 4583
telemt_upstream_connect_attempt_total 77089
telemt_upstream_connect_success_total 66452
telemt_upstream_connect_fail_total 10637
telemt_upstream_connect_attempts_per_request{bucket="1"} 77089
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 39021
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27077
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 345
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10637
telemt_me_keepalive_timeout_total 5484
telemt_me_reconnect_attempts_total 149122
telemt_me_reconnect_success_total 38610
telemt_me_reader_eof_total 43294
telemt_me_idle_close_by_peer_total 43286
telemt_me_route_drop_no_conn_total 182275
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 429400
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 34
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1877
telemt_desync_full_logged_total 556
telemt_desync_suppressed_total 1321
telemt_desync_frames_bucket_total{bucket="1_2"} 442
telemt_desync_frames_bucket_total{bucket="3_10"} 727
telemt_desync_frames_bucket_total{bucket="gt_10"} 708
telemt_pool_swap_total 50
telemt_me_writer_removed_unexpected_total 42503
telemt_me_refill_failed_total 3446
telemt_me_writer_restored_same_endpoint_total 38600
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3893
telemt_user_connections_total{user="hello"} 448281
telemt_user_connections_current{user="hello"} 190
telemt_user_octets_from_client{user="hello"} 9680427999 (9.02 GB)
telemt_user_octets_to_client{user="hello"} 185772075540 (173.01 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 126770.1 (35h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 208433
telemt_connections_bad_total 31833
telemt_handshake_timeouts_total 1769
telemt_upstream_connect_attempt_total 44690
telemt_upstream_connect_success_total 44260
telemt_upstream_connect_fail_total 430
telemt_upstream_connect_attempts_per_request{bucket="1"} 44690
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22136
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21980
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 144
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 430
telemt_me_keepalive_timeout_total 2569
telemt_me_reconnect_attempts_total 47795
telemt_me_reconnect_success_total 33077
telemt_me_reader_eof_total 35385
telemt_me_idle_close_by_peer_total 35385
telemt_me_route_drop_no_conn_total 62548
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 164259
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 709
telemt_desync_full_logged_total 172
telemt_desync_suppressed_total 537
telemt_desync_frames_bucket_total{bucket="1_2"} 118
telemt_desync_frames_bucket_total{bucket="3_10"} 338
telemt_desync_frames_bucket_total{bucket="gt_10"} 253
telemt_pool_swap_total 96
telemt_me_writer_removed_unexpected_total 33838
telemt_me_refill_failed_total 456
telemt_me_writer_restored_same_endpoint_total 33059
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 761
telemt_user_connections_total{user="hello"} 169021
telemt_user_connections_current{user="hello"} 73
telemt_user_octets_from_client{user="hello"} 2484084333 (2.31 GB)
telemt_user_octets_to_client{user="hello"} 80918354383 (75.36 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 176554.9 (49h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1016101
telemt_connections_bad_total 36341
telemt_handshake_timeouts_total 26356
telemt_upstream_connect_attempt_total 36822
telemt_upstream_connect_success_total 36626
telemt_upstream_connect_fail_total 196
telemt_upstream_connect_attempts_per_request{bucket="1"} 36822
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17252
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19333
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 196
telemt_me_keepalive_timeout_total 4759
telemt_me_reconnect_attempts_total 32561
telemt_me_reconnect_success_total 27878
telemt_me_reader_eof_total 29899
telemt_me_idle_close_by_peer_total 29896
telemt_me_route_drop_no_conn_total 477575
telemt_me_route_drop_channel_closed_total 25
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 941825
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 792
telemt_desync_full_logged_total 259
telemt_desync_suppressed_total 533
telemt_desync_frames_bucket_total{bucket="1_2"} 260
telemt_desync_frames_bucket_total{bucket="3_10"} 264
telemt_desync_frames_bucket_total{bucket="gt_10"} 268
telemt_pool_swap_total 167
telemt_me_writer_removed_unexpected_total 28374
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 27871
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 496
telemt_user_connections_total{user="hello"} 914454
telemt_user_connections_current{user="hello"} 385
telemt_user_octets_from_client{user="hello"} 15491911116 (14.43 GB)
telemt_user_octets_to_client{user="hello"} 456537598092 (425.18 GB)
telemt_user_unique_ips_current{user="hello"} 157
telemt_user_unique_ips_recent_window{user="hello"} 60
```