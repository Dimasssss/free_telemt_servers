# Server Metrics 2026-03-20 10:56:13 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.27

telemt_uptime_seconds 2332.6 (0h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 176711
telemt_connections_bad_total 5442
telemt_connections_current 1671
telemt_connections_me_current 1671
telemt_handshake_timeouts_total 1688
telemt_upstream_connect_attempt_total 804
telemt_upstream_connect_success_total 792
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 803
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 321
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 470
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_reconnect_attempts_total 108
telemt_me_reconnect_success_total 17
telemt_me_reader_eof_total 16
telemt_me_idle_close_by_peer_total 16
telemt_me_route_drop_no_conn_total 255197
telemt_me_route_drop_channel_closed_total 58
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 148138
telemt_me_writer_pick_total{mode="p2c",result="full"} 1
telemt_me_endpoint_quarantine_total 16
telemt_me_single_endpoint_shadow_rotate_total 21
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 37
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 47
telemt_desync_total 320
telemt_desync_full_logged_total 111
telemt_desync_suppressed_total 209
telemt_desync_frames_bucket_total{bucket="1_2"} 84
telemt_desync_frames_bucket_total{bucket="3_10"} 122
telemt_desync_frames_bucket_total{bucket="gt_10"} 114
telemt_pool_swap_total 2
telemt_pool_force_close_total 59
telemt_me_writer_close_signal_drop_total 28
telemt_me_draining_writers_reap_progress_total 646
telemt_me_writer_removed_unexpected_total 16
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 50
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 608
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 58
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 587
telemt_me_writer_teardown_success_total{mode="normal"} 658
telemt_me_writer_teardown_noop_total 646
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 768
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 868
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 997
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 1145
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 1255
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 1297
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 1304
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 1304
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 1304
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 1304
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 1304
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 1304
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 1304
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 11.392092
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 1304
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 28
telemt_me_refill_failed_total 5
telemt_me_writer_restored_same_endpoint_total 11
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 147789
telemt_user_connections_current{user="hello"} 1671
telemt_user_octets_from_client{user="hello"} 1120241448 (1.04 GB)
telemt_user_octets_to_client{user="hello"} 16510453176 (15.38 GB)
telemt_user_unique_ips_current{user="hello"} 560
telemt_user_unique_ips_recent_window{user="hello"} 254
```

## psb.hosting №1

```
telemt 3.3.27

telemt_uptime_seconds 2314.4 (0h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 281658
telemt_connections_bad_total 40554
telemt_connections_current 4385
telemt_connections_me_current 4385
telemt_handshake_timeouts_total 6998
telemt_upstream_connect_attempt_total 999
telemt_upstream_connect_success_total 993
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 998
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 440
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 548
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_reconnect_attempts_total 243
telemt_me_reconnect_success_total 174
telemt_me_reader_eof_total 176
telemt_me_idle_close_by_peer_total 176
telemt_me_route_drop_no_conn_total 191482
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 208287
telemt_me_endpoint_quarantine_total 5
telemt_me_single_endpoint_shadow_rotate_total 18
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 128
telemt_desync_total 678
telemt_desync_full_logged_total 244
telemt_desync_suppressed_total 434
telemt_desync_frames_bucket_total{bucket="1_2"} 130
telemt_desync_frames_bucket_total{bucket="3_10"} 320
telemt_desync_frames_bucket_total{bucket="gt_10"} 228
telemt_me_writer_close_signal_drop_total 4
telemt_me_draining_writers_reap_progress_total 598
telemt_me_writer_removed_unexpected_total 177
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 203
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 572
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 598
telemt_me_writer_teardown_success_total{mode="normal"} 775
telemt_me_writer_teardown_noop_total 598
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 1371
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 1373
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 1373
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 1373
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 1373
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 1373
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 1373
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 1373
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 1373
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 1373
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 1373
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 1373
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 1373
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.042604
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 1373
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 4
telemt_me_refill_failed_total 2
telemt_me_writer_restored_same_endpoint_total 174
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 208330
telemt_user_connections_current{user="hello"} 4385
telemt_user_octets_from_client{user="hello"} 3070592596 (2.86 GB)
telemt_user_octets_to_client{user="hello"} 60525266680 (56.37 GB)
telemt_user_unique_ips_current{user="hello"} 1565
telemt_user_unique_ips_recent_window{user="hello"} 607
```

## psb.hosting №2

```
telemt 3.3.27

telemt_uptime_seconds 2302.7 (0h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 212126
telemt_connections_bad_total 32329
telemt_connections_current 3411
telemt_connections_me_current 3411
telemt_handshake_timeouts_total 2833
telemt_upstream_connect_attempt_total 842
telemt_upstream_connect_success_total 842
telemt_upstream_connect_attempts_per_request{bucket="1"} 842
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 458
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 383
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 102
telemt_me_reconnect_success_total 49
telemt_me_reader_eof_total 54
telemt_me_idle_close_by_peer_total 54
telemt_me_route_drop_no_conn_total 69133
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 159471
telemt_me_endpoint_quarantine_total 3
telemt_me_single_endpoint_shadow_rotate_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 81
telemt_desync_total 403
telemt_desync_full_logged_total 136
telemt_desync_suppressed_total 267
telemt_desync_frames_bucket_total{bucket="1_2"} 86
telemt_desync_frames_bucket_total{bucket="3_10"} 134
telemt_desync_frames_bucket_total{bucket="gt_10"} 183
telemt_pool_swap_total 1
telemt_pool_force_close_total 27
telemt_me_writer_close_signal_drop_total 3
telemt_me_draining_writers_reap_progress_total 621
telemt_me_writer_removed_unexpected_total 53
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 90
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 585
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 27
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 594
telemt_me_writer_teardown_success_total{mode="normal"} 675
telemt_me_writer_teardown_noop_total 621
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 1285
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 1295
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 1296
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 1296
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 1296
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 1296
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 1296
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 1296
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 1296
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 1296
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 1296
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 1296
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 1296
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.082770
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 1296
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 3
telemt_me_refill_failed_total 3
telemt_me_writer_restored_same_endpoint_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 159507
telemt_user_connections_current{user="hello"} 3411
telemt_user_octets_from_client{user="hello"} 2099949360 (1.96 GB)
telemt_user_octets_to_client{user="hello"} 58295597560 (54.29 GB)
telemt_user_unique_ips_current{user="hello"} 1412
telemt_user_unique_ips_recent_window{user="hello"} 517
```

## koara.io

Не удалось получить метрики для этого сервера.

## landvps.ru

```
telemt 3.3.27

telemt_uptime_seconds 2094.2 (0h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 814201
telemt_connections_bad_total 11250
telemt_connections_current 5960
telemt_connections_me_current 5960
telemt_handshake_timeouts_total 6215
telemt_upstream_connect_attempt_total 978
telemt_upstream_connect_success_total 893
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 921
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 372
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 490
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 31
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_keepalive_timeout_total 31
telemt_me_reconnect_attempts_total 309
telemt_me_reconnect_success_total 113
telemt_me_reader_eof_total 117
telemt_me_idle_close_by_peer_total 117
telemt_me_route_drop_no_conn_total 1699379
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 751861
telemt_me_endpoint_quarantine_total 4
telemt_me_single_endpoint_shadow_rotate_total 17
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 128
telemt_desync_total 614
telemt_desync_full_logged_total 165
telemt_desync_suppressed_total 449
telemt_desync_frames_bucket_total{bucket="1_2"} 157
telemt_desync_frames_bucket_total{bucket="3_10"} 259
telemt_desync_frames_bucket_total{bucket="gt_10"} 198
telemt_me_writer_close_signal_drop_total 7
telemt_me_draining_writers_reap_progress_total 562
telemt_me_writer_removed_unexpected_total 119
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 137
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 544
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 562
telemt_me_writer_teardown_success_total{mode="normal"} 681
telemt_me_writer_teardown_noop_total 562
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 1166
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 1231
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 1239
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 1243
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 1243
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 1243
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 1243
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 1243
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 1243
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 1243
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 1243
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 1243
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 1243
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.331085
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 1243
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 7
telemt_me_refill_failed_total 6
telemt_me_writer_restored_same_endpoint_total 111
telemt_me_writer_removed_unexpected_minus_restored_total 8
telemt_user_connections_total{user="hello"} 751822
telemt_user_connections_current{user="hello"} 5960
telemt_user_octets_from_client{user="hello"} 2883987852 (2.69 GB)
telemt_user_octets_to_client{user="hello"} 23917962860 (22.28 GB)
telemt_user_unique_ips_current{user="hello"} 1775
telemt_user_unique_ips_recent_window{user="hello"} 1007
```

## rdp-onedash.ru

```
telemt 3.3.27

telemt_uptime_seconds 2086.3 (0h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 607683
telemt_connections_bad_total 16600
telemt_connections_current 7010
telemt_connections_me_current 7010
telemt_handshake_timeouts_total 7923
telemt_upstream_connect_attempt_total 632
telemt_upstream_connect_success_total 620
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 632
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 309
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 305
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_reconnect_attempts_total 49
telemt_me_reconnect_success_total 51
telemt_me_reader_eof_total 49
telemt_me_idle_close_by_peer_total 49
telemt_me_route_drop_no_conn_total 875858
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 538669
telemt_me_endpoint_quarantine_total 9
telemt_me_single_endpoint_shadow_rotate_total 19
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 87
telemt_desync_total 1234
telemt_desync_full_logged_total 355
telemt_desync_suppressed_total 879
telemt_desync_frames_bucket_total{bucket="1_2"} 272
telemt_desync_frames_bucket_total{bucket="3_10"} 537
telemt_desync_frames_bucket_total{bucket="gt_10"} 425
telemt_pool_swap_total 1
telemt_pool_force_close_total 33
telemt_me_writer_close_signal_drop_total 8
telemt_me_draining_writers_reap_progress_total 418
telemt_me_writer_removed_unexpected_total 49
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 76
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 391
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 30
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 385
telemt_me_writer_teardown_success_total{mode="normal"} 467
telemt_me_writer_teardown_noop_total 418
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 838
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 861
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 861
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 885
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 885
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 885
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 885
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 885
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 885
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 885
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 885
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 885
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 885
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.617324
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 885
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 8
telemt_me_writer_restored_same_endpoint_total 49
telemt_user_connections_total{user="hello"} 538600
telemt_user_connections_current{user="hello"} 7010
telemt_user_octets_from_client{user="hello"} 4085990624 (3.81 GB)
telemt_user_octets_to_client{user="hello"} 44494595952 (41.44 GB)
telemt_user_unique_ips_current{user="hello"} 2159
telemt_user_unique_ips_recent_window{user="hello"} 1072
```

## hostvds.com

```
telemt 3.3.27

telemt_uptime_seconds 2084.6 (0h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 47294
telemt_connections_bad_total 7430
telemt_connections_current 775
telemt_connections_me_current 775
telemt_handshake_timeouts_total 620
telemt_upstream_connect_attempt_total 1164
telemt_upstream_connect_success_total 1164
telemt_upstream_connect_attempts_per_request{bucket="1"} 1164
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 375
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 782
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 258
telemt_me_reconnect_success_total 112
telemt_me_reader_eof_total 122
telemt_me_idle_close_by_peer_total 122
telemt_me_route_drop_no_conn_total 22836
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 35382
telemt_me_endpoint_quarantine_total 7
telemt_me_single_endpoint_shadow_rotate_total 21
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 127
telemt_desync_total 75
telemt_desync_full_logged_total 29
telemt_desync_suppressed_total 46
telemt_desync_frames_bucket_total{bucket="1_2"} 16
telemt_desync_frames_bucket_total{bucket="3_10"} 25
telemt_desync_frames_bucket_total{bucket="gt_10"} 34
telemt_pool_force_close_total 1
telemt_me_writer_close_signal_drop_total 6
telemt_me_draining_writers_reap_progress_total 819
telemt_me_writer_removed_unexpected_total 120
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 147
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 795
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 818
telemt_me_writer_teardown_success_total{mode="normal"} 942
telemt_me_writer_teardown_noop_total 819
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 1709
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 1741
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 1746
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 1753
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 1759
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 1761
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 1761
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 1761
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 1761
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 1761
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 1761
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 1761
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 1761
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.640441
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 1761
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 6
telemt_me_refill_failed_total 6
telemt_me_writer_restored_same_endpoint_total 110
telemt_me_writer_removed_unexpected_minus_restored_total 10
telemt_user_connections_total{user="hello"} 35391
telemt_user_connections_current{user="hello"} 775
telemt_user_octets_from_client{user="hello"} 469820792 (448.06 MB)
telemt_user_octets_to_client{user="hello"} 5807642292 (5.41 GB)
telemt_user_unique_ips_current{user="hello"} 279
telemt_user_unique_ips_recent_window{user="hello"} 124
```

## 4vps.su

```
telemt 3.3.27

telemt_uptime_seconds 2076.8 (0h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 356815
telemt_connections_bad_total 67695
telemt_connections_current 6842
telemt_connections_me_current 6842
telemt_handshake_timeouts_total 6607
telemt_upstream_connect_attempt_total 871
telemt_upstream_connect_success_total 849
telemt_upstream_connect_fail_total 20
telemt_upstream_connect_attempts_per_request{bucket="1"} 869
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 441
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 407
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 20
telemt_me_reconnect_attempts_total 298
telemt_me_reconnect_success_total 106
telemt_me_reader_eof_total 109
telemt_me_idle_close_by_peer_total 109
telemt_me_route_drop_no_conn_total 147369
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 270923
telemt_me_endpoint_quarantine_total 6
telemt_me_single_endpoint_shadow_rotate_total 16
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 127
telemt_desync_total 931
telemt_desync_full_logged_total 297
telemt_desync_suppressed_total 634
telemt_desync_frames_bucket_total{bucket="1_2"} 219
telemt_desync_frames_bucket_total{bucket="3_10"} 331
telemt_desync_frames_bucket_total{bucket="gt_10"} 381
telemt_me_writer_close_signal_drop_total 3
telemt_me_draining_writers_reap_progress_total 549
telemt_me_writer_removed_unexpected_total 109
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 121
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 537
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 549
telemt_me_writer_teardown_success_total{mode="normal"} 658
telemt_me_writer_teardown_noop_total 549
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 1205
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 1207
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 1207
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 1207
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 1207
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 1207
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 1207
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 1207
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 1207
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 1207
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 1207
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 1207
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 1207
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.038648
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 1207
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 3
telemt_me_refill_failed_total 6
telemt_me_writer_restored_same_endpoint_total 103
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 270922
telemt_user_connections_current{user="hello"} 6842
telemt_user_octets_from_client{user="hello"} 7580428828 (7.06 GB)
telemt_user_octets_to_client{user="hello"} 98969403064 (92.17 GB)
telemt_user_unique_ips_current{user="hello"} 2194
telemt_user_unique_ips_recent_window{user="hello"} 845
```