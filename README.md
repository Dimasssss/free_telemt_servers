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

# Server Metrics 2026-03-17 13:58:30 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 69194.4 (19h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 708077
telemt_connections_bad_total 5678
telemt_handshake_timeouts_total 20645
telemt_upstream_connect_attempt_total 16939
telemt_upstream_connect_success_total 16485
telemt_upstream_connect_fail_total 454
telemt_upstream_connect_attempts_per_request{bucket="1"} 16939
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8620
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7715
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 150
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 454
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 121
telemt_me_reconnect_attempts_total 18655
telemt_me_reconnect_success_total 10746
telemt_me_reader_eof_total 11548
telemt_me_idle_close_by_peer_total 11547
telemt_me_route_drop_no_conn_total 259198
telemt_me_route_drop_channel_closed_total 72
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 642505
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4570
telemt_desync_full_logged_total 1276
telemt_desync_suppressed_total 3294
telemt_desync_frames_bucket_total{bucket="1_2"} 1286
telemt_desync_frames_bucket_total{bucket="3_10"} 1877
telemt_desync_frames_bucket_total{bucket="gt_10"} 1407
telemt_pool_swap_total 57
telemt_me_writer_removed_unexpected_total 11145
telemt_me_refill_failed_total 242
telemt_me_writer_restored_same_endpoint_total 10724
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 399
telemt_user_connections_total{user="hello"} 644391
telemt_user_connections_current{user="hello"} 889
telemt_user_octets_from_client{user="hello"} 10486058407 (9.77 GB)
telemt_user_octets_to_client{user="hello"} 221089435639 (205.91 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 328
telemt_user_unique_ips_recent_window{user="hello"} 161
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 69446.4 (19h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 439353
telemt_connections_bad_total 27134
telemt_handshake_timeouts_total 22072
telemt_upstream_connect_attempt_total 28731
telemt_upstream_connect_success_total 28390
telemt_upstream_connect_fail_total 341
telemt_upstream_connect_attempts_per_request{bucket="1"} 28731
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17065
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9731
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1594
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 341
telemt_me_keepalive_timeout_total 314
telemt_me_reconnect_attempts_total 30612
telemt_me_reconnect_success_total 13332
telemt_me_reader_eof_total 14439
telemt_me_idle_close_by_peer_total 14439
telemt_me_route_drop_no_conn_total 185195
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 356744
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1424
telemt_desync_full_logged_total 449
telemt_desync_suppressed_total 975
telemt_desync_frames_bucket_total{bucket="1_2"} 315
telemt_desync_frames_bucket_total{bucket="3_10"} 623
telemt_desync_frames_bucket_total{bucket="gt_10"} 486
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 14035
telemt_me_refill_failed_total 536
telemt_me_writer_restored_same_endpoint_total 13316
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 703
telemt_user_connections_total{user="hello"} 368234
telemt_user_connections_current{user="hello"} 620
telemt_user_octets_from_client{user="hello"} 3984548187 (3.71 GB)
telemt_user_octets_to_client{user="hello"} 119467797983 (111.26 GB)
telemt_user_msgs_from_client{user="hello"} 167103
telemt_user_msgs_to_client{user="hello"} 482744
telemt_user_unique_ips_current{user="hello"} 160
telemt_user_unique_ips_recent_window{user="hello"} 83
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 69222.0 (19h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 231905
telemt_connections_bad_total 7806
telemt_handshake_timeouts_total 16807
telemt_upstream_connect_attempt_total 18310
telemt_upstream_connect_success_total 18218
telemt_upstream_connect_fail_total 92
telemt_upstream_connect_attempts_per_request{bucket="1"} 18310
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8097
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10045
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 71
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 92
telemt_me_keepalive_timeout_total 31
telemt_me_reconnect_attempts_total 20318
telemt_me_reconnect_success_total 14725
telemt_me_reader_eof_total 15774
telemt_me_idle_close_by_peer_total 15774
telemt_me_route_drop_no_conn_total 88131
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 195134
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 744
telemt_desync_full_logged_total 210
telemt_desync_suppressed_total 534
telemt_desync_frames_bucket_total{bucket="1_2"} 274
telemt_desync_frames_bucket_total{bucket="3_10"} 329
telemt_desync_frames_bucket_total{bucket="gt_10"} 141
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 15106
telemt_me_refill_failed_total 172
telemt_me_writer_restored_same_endpoint_total 14714
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 381
telemt_user_connections_total{user="hello"} 195010
telemt_user_connections_current{user="hello"} 284
telemt_user_octets_from_client{user="hello"} 15345460860 (14.29 GB)
telemt_user_octets_to_client{user="hello"} 52664922248 (49.05 GB)
telemt_user_unique_ips_current{user="hello"} 106
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 69281.5 (19h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 531987
telemt_connections_bad_total 8080
telemt_handshake_timeouts_total 12867
telemt_upstream_connect_attempt_total 16402
telemt_upstream_connect_success_total 16252
telemt_upstream_connect_fail_total 150
telemt_upstream_connect_attempts_per_request{bucket="1"} 16402
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8126
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8010
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 107
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 150
telemt_me_keepalive_timeout_total 14
telemt_me_reconnect_attempts_total 19745
telemt_me_reconnect_success_total 11750
telemt_me_reader_eof_total 12661
telemt_me_idle_close_by_peer_total 12661
telemt_me_route_drop_no_conn_total 165264
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 453189
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1582
telemt_desync_full_logged_total 547
telemt_desync_suppressed_total 1035
telemt_desync_frames_bucket_total{bucket="1_2"} 389
telemt_desync_frames_bucket_total{bucket="3_10"} 710
telemt_desync_frames_bucket_total{bucket="gt_10"} 483
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 12205
telemt_me_refill_failed_total 245
telemt_me_writer_restored_same_endpoint_total 11741
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 455
telemt_user_connections_total{user="hello"} 454060
telemt_user_connections_current{user="hello"} 812
telemt_user_octets_from_client{user="hello"} 5706770366 (5.31 GB)
telemt_user_octets_to_client{user="hello"} 152578284911 (142.10 GB)
telemt_user_msgs_from_client{user="hello"} 4070
telemt_user_msgs_to_client{user="hello"} 5224
telemt_user_unique_ips_current{user="hello"} 203
telemt_user_unique_ips_recent_window{user="hello"} 109
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 69253.4 (19h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 262651
telemt_connections_bad_total 56505
telemt_handshake_timeouts_total 3306
telemt_upstream_connect_attempt_total 20193
telemt_upstream_connect_success_total 19742
telemt_upstream_connect_fail_total 451
telemt_upstream_connect_attempts_per_request{bucket="1"} 20193
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8909
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10559
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 274
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 451
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 35897
telemt_me_reconnect_success_total 15884
telemt_me_reader_eof_total 17093
telemt_me_idle_close_by_peer_total 17091
telemt_me_route_drop_no_conn_total 70826
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 192290
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1092
telemt_desync_full_logged_total 228
telemt_desync_suppressed_total 864
telemt_desync_frames_bucket_total{bucket="1_2"} 545
telemt_desync_frames_bucket_total{bucket="3_10"} 418
telemt_desync_frames_bucket_total{bucket="gt_10"} 129
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 16774
telemt_me_refill_failed_total 621
telemt_me_writer_restored_same_endpoint_total 15876
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 890
telemt_user_connections_total{user="hello"} 192741
telemt_user_connections_current{user="hello"} 231
telemt_user_octets_from_client{user="hello"} 2540533731 (2.37 GB)
telemt_user_octets_to_client{user="hello"} 72047378283 (67.10 GB)
telemt_user_msgs_from_client{user="hello"} 1159
telemt_user_msgs_to_client{user="hello"} 2341
telemt_user_unique_ips_current{user="hello"} 85
telemt_user_unique_ips_recent_window{user="hello"} 61
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 69415.4 (19h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 629596
telemt_connections_bad_total 53474
telemt_handshake_timeouts_total 6168
telemt_upstream_connect_attempt_total 14015
telemt_upstream_connect_success_total 13940
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 14015
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6881
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7036
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_keepalive_timeout_total 39
telemt_me_reconnect_attempts_total 18202
telemt_me_reconnect_success_total 10450
telemt_me_reader_eof_total 11333
telemt_me_idle_close_by_peer_total 11333
telemt_me_route_drop_no_conn_total 437115
telemt_me_route_drop_channel_closed_total 35
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 633086
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 843
telemt_desync_full_logged_total 311
telemt_desync_suppressed_total 532
telemt_desync_frames_bucket_total{bucket="1_2"} 210
telemt_desync_frames_bucket_total{bucket="3_10"} 326
telemt_desync_frames_bucket_total{bucket="gt_10"} 307
telemt_pool_swap_total 60
telemt_me_writer_removed_unexpected_total 10851
telemt_me_refill_failed_total 240
telemt_me_writer_restored_same_endpoint_total 10436
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 401
telemt_user_connections_total{user="hello"} 537570
telemt_user_connections_current{user="hello"} 871
telemt_user_octets_from_client{user="hello"} 8195236712 (7.63 GB)
telemt_user_octets_to_client{user="hello"} 250240956116 (233.06 GB)
telemt_user_unique_ips_current{user="hello"} 316
telemt_user_unique_ips_recent_window{user="hello"} 148
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 17181.6 (4h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13768
telemt_connections_bad_total 61
telemt_handshake_timeouts_total 77
telemt_upstream_connect_attempt_total 9745
telemt_upstream_connect_success_total 9664
telemt_upstream_connect_fail_total 81
telemt_upstream_connect_attempts_per_request{bucket="1"} 9745
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5253
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4402
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 81
telemt_me_keepalive_timeout_total 12
telemt_me_reconnect_attempts_total 16366
telemt_me_reconnect_success_total 8631
telemt_me_reader_eof_total 9071
telemt_me_idle_close_by_peer_total 9071
telemt_me_seq_mismatch_total 10
telemt_me_route_drop_no_conn_total 4684
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 13271
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 8956
telemt_me_refill_failed_total 240
telemt_me_writer_restored_same_endpoint_total 8616
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 325
telemt_user_connections_total{user="hello"} 13372
telemt_user_connections_current{user="hello"} 87
telemt_user_octets_from_client{user="hello"} 369321489 (352.21 MB)
telemt_user_octets_to_client{user="hello"} 22278716938 (20.75 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 19
telemt_user_unique_ips_recent_window{user="hello"} 5
```