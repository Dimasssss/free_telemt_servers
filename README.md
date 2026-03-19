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

# Server Metrics 2026-03-19 04:36:31 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 24483.6 (6h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 339033
telemt_connections_bad_total 35876
telemt_connections_current 904
telemt_connections_me_current 904
telemt_handshake_timeouts_total 19854
telemt_upstream_connect_attempt_total 4809
telemt_upstream_connect_success_total 4729
telemt_upstream_connect_fail_total 80
telemt_upstream_connect_attempts_per_request{bucket="1"} 4809
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2314
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2412
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 80
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 3501
telemt_me_reconnect_success_total 3485
telemt_me_reader_eof_total 3672
telemt_me_idle_close_by_peer_total 3671
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 86498
telemt_me_route_drop_channel_closed_total 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 247046
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 27
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1754
telemt_desync_full_logged_total 474
telemt_desync_suppressed_total 1280
telemt_desync_frames_bucket_total{bucket="1_2"} 655
telemt_desync_frames_bucket_total{bucket="3_10"} 710
telemt_desync_frames_bucket_total{bucket="gt_10"} 389
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 3513
telemt_me_writer_restored_same_endpoint_total 3468
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 28
telemt_user_connections_total{user="hello"} 244299
telemt_user_connections_current{user="hello"} 904
telemt_user_octets_from_client{user="hello"} 2740875920 (2.55 GB)
telemt_user_octets_to_client{user="hello"} 73520397136 (68.47 GB)
telemt_user_unique_ips_current{user="hello"} 351
telemt_user_unique_ips_recent_window{user="hello"} 114
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 24487.7 (6h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 627213
telemt_connections_bad_total 39308
telemt_connections_current 2434
telemt_connections_me_current 2434
telemt_handshake_timeouts_total 18127
telemt_upstream_connect_attempt_total 4634
telemt_upstream_connect_success_total 4549
telemt_upstream_connect_fail_total 85
telemt_upstream_connect_attempts_per_request{bucket="1"} 4634
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2189
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2350
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 85
telemt_me_reconnect_attempts_total 3313
telemt_me_reconnect_success_total 3296
telemt_me_reader_eof_total 3476
telemt_me_idle_close_by_peer_total 3476
telemt_me_seq_mismatch_total 8
telemt_me_route_drop_no_conn_total 188431
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 518864
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 30
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1970
telemt_desync_full_logged_total 671
telemt_desync_suppressed_total 1299
telemt_desync_frames_bucket_total{bucket="1_2"} 393
telemt_desync_frames_bucket_total{bucket="3_10"} 719
telemt_desync_frames_bucket_total{bucket="gt_10"} 858
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 3353
telemt_me_writer_restored_same_endpoint_total 3278
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 57
telemt_user_connections_total{user="hello"} 518810
telemt_user_connections_current{user="hello"} 2434
telemt_user_octets_from_client{user="hello"} 14724267132 (13.71 GB)
telemt_user_octets_to_client{user="hello"} 226381905980 (210.83 GB)
telemt_user_unique_ips_current{user="hello"} 933
telemt_user_unique_ips_recent_window{user="hello"} 301
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 24484.7 (6h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 530551
telemt_connections_bad_total 105923
telemt_connections_current 2004
telemt_connections_me_current 2004
telemt_handshake_timeouts_total 17178
telemt_upstream_connect_attempt_total 4543
telemt_upstream_connect_success_total 4543
telemt_upstream_connect_attempts_per_request{bucket="1"} 4543
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2303
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2233
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 3303
telemt_me_reconnect_success_total 3292
telemt_me_reader_eof_total 3486
telemt_me_idle_close_by_peer_total 3486
telemt_me_route_drop_no_conn_total 156130
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 379435
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1794
telemt_desync_full_logged_total 667
telemt_desync_suppressed_total 1127
telemt_desync_frames_bucket_total{bucket="1_2"} 308
telemt_desync_frames_bucket_total{bucket="3_10"} 730
telemt_desync_frames_bucket_total{bucket="gt_10"} 756
telemt_pool_swap_total 27
telemt_me_writer_removed_unexpected_total 3345
telemt_me_writer_restored_same_endpoint_total 3276
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 53
telemt_user_connections_total{user="hello"} 379434
telemt_user_connections_current{user="hello"} 2004
telemt_user_octets_from_client{user="hello"} 8367600408 (7.79 GB)
telemt_user_octets_to_client{user="hello"} 238874289324 (222.47 GB)
telemt_user_unique_ips_current{user="hello"} 730
telemt_user_unique_ips_recent_window{user="hello"} 239
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 24538.0 (6h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 622396
telemt_connections_bad_total 72388
telemt_connections_current 1621
telemt_connections_me_current 1621
telemt_handshake_timeouts_total 13277
telemt_upstream_connect_attempt_total 4418
telemt_upstream_connect_success_total 4418
telemt_upstream_connect_attempts_per_request{bucket="1"} 4418
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2228
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2181
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_me_reconnect_attempts_total 3184
telemt_me_reconnect_success_total 3170
telemt_me_reader_eof_total 3343
telemt_me_idle_close_by_peer_total 3342
telemt_me_route_drop_no_conn_total 157075
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 377058
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1150
telemt_desync_full_logged_total 415
telemt_desync_suppressed_total 735
telemt_desync_frames_bucket_total{bucket="1_2"} 221
telemt_desync_frames_bucket_total{bucket="3_10"} 493
telemt_desync_frames_bucket_total{bucket="gt_10"} 436
telemt_pool_swap_total 27
telemt_me_writer_removed_unexpected_total 3206
telemt_me_writer_restored_same_endpoint_total 3146
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 272
telemt_me_writer_removed_unexpected_minus_restored_total 36
telemt_user_connections_total{user="hello"} 376820
telemt_user_connections_current{user="hello"} 1621
telemt_user_octets_from_client{user="hello"} 4520226172 (4.21 GB)
telemt_user_octets_to_client{user="hello"} 145952330008 (135.93 GB)
telemt_user_unique_ips_current{user="hello"} 618
telemt_user_unique_ips_recent_window{user="hello"} 226
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 24481.4 (6h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 693817
telemt_connections_bad_total 190705
telemt_connections_current 2017
telemt_connections_me_current 2017
telemt_handshake_timeouts_total 19612
telemt_upstream_connect_attempt_total 4554
telemt_upstream_connect_success_total 4525
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 4554
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2258
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2252
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_reconnect_attempts_total 3289
telemt_me_reconnect_success_total 3270
telemt_me_reader_eof_total 3456
telemt_me_idle_close_by_peer_total 3456
telemt_me_route_drop_no_conn_total 170790
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 409139
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1793
telemt_desync_full_logged_total 689
telemt_desync_suppressed_total 1104
telemt_desync_frames_bucket_total{bucket="1_2"} 426
telemt_desync_frames_bucket_total{bucket="3_10"} 752
telemt_desync_frames_bucket_total{bucket="gt_10"} 615
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 3300
telemt_me_writer_restored_same_endpoint_total 3246
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 30
telemt_user_connections_total{user="hello"} 409054
telemt_user_connections_current{user="hello"} 2017
telemt_user_octets_from_client{user="hello"} 11735254368 (10.93 GB)
telemt_user_octets_to_client{user="hello"} 239679744672 (223.22 GB)
telemt_user_unique_ips_current{user="hello"} 787
telemt_user_unique_ips_recent_window{user="hello"} 276
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 24493.2 (6h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 122903
telemt_connections_bad_total 10274
telemt_connections_current 549
telemt_connections_me_current 549
telemt_handshake_timeouts_total 559
telemt_upstream_connect_attempt_total 6819
telemt_upstream_connect_success_total 6636
telemt_upstream_connect_fail_total 183
telemt_upstream_connect_attempts_per_request{bucket="1"} 6819
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3135
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3501
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 183
telemt_me_reconnect_attempts_total 7228
telemt_me_reconnect_success_total 5385
telemt_me_reader_eof_total 5660
telemt_me_idle_close_by_peer_total 5660
telemt_me_route_drop_no_conn_total 50487
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 107765
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 112
telemt_desync_full_logged_total 39
telemt_desync_suppressed_total 73
telemt_desync_frames_bucket_total{bucket="1_2"} 37
telemt_desync_frames_bucket_total{bucket="3_10"} 50
telemt_desync_frames_bucket_total{bucket="gt_10"} 25
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 5458
telemt_me_refill_failed_total 57
telemt_me_writer_restored_same_endpoint_total 5355
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 73
telemt_user_connections_total{user="hello"} 107757
telemt_user_connections_current{user="hello"} 549
telemt_user_octets_from_client{user="hello"} 1973648284 (1.84 GB)
telemt_user_octets_to_client{user="hello"} 68796762180 (64.07 GB)
telemt_user_unique_ips_current{user="hello"} 218
telemt_user_unique_ips_recent_window{user="hello"} 81
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 24483.8 (6h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 403486
telemt_connections_bad_total 45546
telemt_connections_current 1808
telemt_connections_me_current 1808
telemt_handshake_timeouts_total 20817
telemt_upstream_connect_attempt_total 5106
telemt_upstream_connect_success_total 5106
telemt_upstream_connect_attempts_per_request{bucket="1"} 5106
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2706
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2397
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 3871
telemt_me_reconnect_success_total 3860
telemt_me_reader_eof_total 4075
telemt_me_idle_close_by_peer_total 4075
telemt_me_route_drop_no_conn_total 113312
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 324634
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1646
telemt_desync_full_logged_total 628
telemt_desync_suppressed_total 1018
telemt_desync_frames_bucket_total{bucket="1_2"} 336
telemt_desync_frames_bucket_total{bucket="3_10"} 639
telemt_desync_frames_bucket_total{bucket="gt_10"} 671
telemt_pool_swap_total 27
telemt_me_writer_removed_unexpected_total 3901
telemt_me_writer_restored_same_endpoint_total 3845
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 41
telemt_user_connections_total{user="hello"} 324650
telemt_user_connections_current{user="hello"} 1808
telemt_user_octets_from_client{user="hello"} 3956765000 (3.69 GB)
telemt_user_octets_to_client{user="hello"} 186963930448 (174.12 GB)
telemt_user_unique_ips_current{user="hello"} 636
telemt_user_unique_ips_recent_window{user="hello"} 214
```