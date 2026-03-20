# Server Metrics 2026-03-20 10:43:25 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.27

telemt_uptime_seconds 1570.3 (0h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 141139
telemt_connections_bad_total 4066
telemt_connections_current 1543
telemt_connections_me_current 1543
telemt_handshake_timeouts_total 1125
telemt_upstream_connect_attempt_total 541
telemt_upstream_connect_success_total 531
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 540
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 217
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 313
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_reconnect_attempts_total 65
telemt_me_reconnect_success_total 12
telemt_me_reader_eof_total 12
telemt_me_idle_close_by_peer_total 12
telemt_me_route_drop_no_conn_total 246153
telemt_me_route_drop_channel_closed_total 53
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 121358
telemt_me_writer_pick_total{mode="p2c",result="full"} 1
telemt_me_endpoint_quarantine_total 13
telemt_me_single_endpoint_shadow_rotate_total 14
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 1
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
telemt_me_writers_active_current 45
telemt_desync_total 226
telemt_desync_full_logged_total 75
telemt_desync_suppressed_total 151
telemt_desync_frames_bucket_total{bucket="1_2"} 61
telemt_desync_frames_bucket_total{bucket="3_10"} 86
telemt_desync_frames_bucket_total{bucket="gt_10"} 79
telemt_pool_swap_total 1
telemt_pool_force_close_total 27
telemt_me_writer_close_signal_drop_total 26
telemt_me_draining_writers_reap_progress_total 395
telemt_me_writer_removed_unexpected_total 12
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 36
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 367
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 27
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 368
telemt_me_writer_teardown_success_total{mode="normal"} 403
telemt_me_writer_teardown_noop_total 395
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 335
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 418
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 531
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 664
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 763
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 792
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 798
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 798
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 798
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 798
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 798
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 798
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 798
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 9.614297
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 798
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 26
telemt_me_refill_failed_total 3
telemt_me_writer_restored_same_endpoint_total 9
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 121047
telemt_user_connections_current{user="hello"} 1543
telemt_user_octets_from_client{user="hello"} 724125896 (690.58 MB)
telemt_user_octets_to_client{user="hello"} 9169893016 (8.54 GB)
telemt_user_unique_ips_current{user="hello"} 553
telemt_user_unique_ips_recent_window{user="hello"} 261
```

## psb.hosting №1

```
telemt 3.3.27

telemt_uptime_seconds 1553.7 (0h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 194857
telemt_connections_bad_total 22873
telemt_connections_current 4419
telemt_connections_me_current 4419
telemt_handshake_timeouts_total 5224
telemt_upstream_connect_attempt_total 611
telemt_upstream_connect_success_total 608
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 610
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 268
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 339
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 54
telemt_me_reconnect_success_total 50
telemt_me_reader_eof_total 50
telemt_me_idle_close_by_peer_total 50
telemt_me_route_drop_no_conn_total 159792
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 148553
telemt_me_endpoint_quarantine_total 5
telemt_me_single_endpoint_shadow_rotate_total 13
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
telemt_me_writers_active_current 86
telemt_desync_total 459
telemt_desync_full_logged_total 170
telemt_desync_suppressed_total 289
telemt_desync_frames_bucket_total{bucket="1_2"} 89
telemt_desync_frames_bucket_total{bucket="3_10"} 213
telemt_desync_frames_bucket_total{bucket="gt_10"} 157
telemt_me_writer_close_signal_drop_total 3
telemt_me_draining_writers_reap_progress_total 386
telemt_me_writer_removed_unexpected_total 51
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 67
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 370
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 386
telemt_me_writer_teardown_success_total{mode="normal"} 437
telemt_me_writer_teardown_noop_total 386
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 822
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 823
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 823
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 823
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 823
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 823
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 823
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 823
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 823
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 823
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 823
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 823
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 823
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.023608
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 823
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 3
telemt_me_writer_restored_same_endpoint_total 50
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 148573
telemt_user_connections_current{user="hello"} 4419
telemt_user_octets_from_client{user="hello"} 1990640604 (1.85 GB)
telemt_user_octets_to_client{user="hello"} 37349001540 (34.78 GB)
telemt_user_unique_ips_current{user="hello"} 1472
telemt_user_unique_ips_recent_window{user="hello"} 546
```

## psb.hosting №2

```
telemt 3.3.27

telemt_uptime_seconds 1542.5 (0h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 139339
telemt_connections_bad_total 18325
telemt_connections_current 3377
telemt_connections_me_current 3377
telemt_handshake_timeouts_total 1654
telemt_upstream_connect_attempt_total 515
telemt_upstream_connect_success_total 515
telemt_upstream_connect_attempts_per_request{bucket="1"} 515
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 287
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 228
telemt_me_reconnect_attempts_total 59
telemt_me_reconnect_success_total 9
telemt_me_reader_eof_total 11
telemt_me_idle_close_by_peer_total 11
telemt_me_route_drop_no_conn_total 49479
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 107222
telemt_me_endpoint_quarantine_total 3
telemt_me_single_endpoint_shadow_rotate_total 12
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
telemt_me_writers_active_current 41
telemt_desync_total 303
telemt_desync_full_logged_total 98
telemt_desync_suppressed_total 205
telemt_desync_frames_bucket_total{bucket="1_2"} 63
telemt_desync_frames_bucket_total{bucket="3_10"} 111
telemt_desync_frames_bucket_total{bucket="gt_10"} 129
telemt_pool_swap_total 1
telemt_pool_force_close_total 27
telemt_me_writer_close_signal_drop_total 1
telemt_me_draining_writers_reap_progress_total 380
telemt_me_writer_removed_unexpected_total 10
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 35
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 356
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 27
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 353
telemt_me_writer_teardown_success_total{mode="normal"} 391
telemt_me_writer_teardown_noop_total 380
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 766
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 770
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 771
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 771
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 771
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 771
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 771
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 771
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 771
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 771
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 771
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 771
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 771
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.053693
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 771
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1
telemt_me_refill_failed_total 3
telemt_me_writer_restored_same_endpoint_total 7
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 107242
telemt_user_connections_current{user="hello"} 3377
telemt_user_octets_from_client{user="hello"} 1573358668 (1.47 GB)
telemt_user_octets_to_client{user="hello"} 38413616080 (35.78 GB)
telemt_user_unique_ips_current{user="hello"} 1354
telemt_user_unique_ips_recent_window{user="hello"} 501
```

## koara.io

```
telemt 3.3.27

telemt_uptime_seconds 1348.6 (0h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 203154
telemt_connections_bad_total 18254
telemt_connections_current 5437
telemt_connections_me_current 5437
telemt_handshake_timeouts_total 3789
telemt_upstream_connect_attempt_total 409
telemt_upstream_connect_success_total 408
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 409
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 186
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 221
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 4
telemt_me_reconnect_success_total 4
telemt_me_reader_eof_total 3
telemt_me_idle_close_by_peer_total 3
telemt_me_route_drop_no_conn_total 106717
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 168906
telemt_me_endpoint_quarantine_total 8
telemt_me_single_endpoint_shadow_rotate_total 14
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 3
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
telemt_me_writers_active_current 44
telemt_desync_total 249
telemt_desync_full_logged_total 101
telemt_desync_suppressed_total 148
telemt_desync_frames_bucket_total{bucket="1_2"} 59
telemt_desync_frames_bucket_total{bucket="3_10"} 90
telemt_desync_frames_bucket_total{bucket="gt_10"} 100
telemt_pool_swap_total 1
telemt_pool_force_close_total 34
telemt_me_writer_close_signal_drop_total 1
telemt_me_draining_writers_reap_progress_total 294
telemt_me_writer_removed_unexpected_total 3
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 20
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 277
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 32
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 260
telemt_me_writer_teardown_success_total{mode="normal"} 297
telemt_me_writer_teardown_noop_total 294
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 533
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 541
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 547
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 549
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 563
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 565
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 591
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 591
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 591
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 591
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 591
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 591
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 591
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.779401
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 591
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1
telemt_me_writer_restored_same_endpoint_total 3
telemt_user_connections_total{user="hello"} 168311
telemt_user_connections_current{user="hello"} 5437
telemt_user_octets_from_client{user="hello"} 1704065156 (1.59 GB)
telemt_user_octets_to_client{user="hello"} 53541975664 (49.86 GB)
telemt_user_unique_ips_current{user="hello"} 1761
telemt_user_unique_ips_recent_window{user="hello"} 731
```

## landvps.ru

```
telemt 3.3.27

telemt_uptime_seconds 1333.0 (0h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 520746
telemt_connections_bad_total 7568
telemt_connections_current 5657
telemt_connections_me_current 5657
telemt_handshake_timeouts_total 4067
telemt_upstream_connect_attempt_total 544
telemt_upstream_connect_success_total 487
telemt_upstream_connect_fail_total 22
telemt_upstream_connect_attempts_per_request{bucket="1"} 509
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 200
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 260
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 22
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 56
telemt_me_reconnect_success_total 53
telemt_me_reader_eof_total 50
telemt_me_idle_close_by_peer_total 50
telemt_me_route_drop_no_conn_total 1055609
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 479562
telemt_me_endpoint_quarantine_total 4
telemt_me_single_endpoint_shadow_rotate_total 13
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
telemt_me_writers_active_current 91
telemt_desync_total 227
telemt_desync_full_logged_total 76
telemt_desync_suppressed_total 151
telemt_desync_frames_bucket_total{bucket="1_2"} 68
telemt_desync_frames_bucket_total{bucket="3_10"} 101
telemt_desync_frames_bucket_total{bucket="gt_10"} 58
telemt_me_writer_close_signal_drop_total 5
telemt_me_draining_writers_reap_progress_total 262
telemt_me_writer_removed_unexpected_total 52
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 63
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 251
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 262
telemt_me_writer_teardown_success_total{mode="normal"} 314
telemt_me_writer_teardown_noop_total 262
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 526
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 564
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 572
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 576
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 576
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 576
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 576
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 576
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 576
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 576
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 576
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 576
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 576
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.233517
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 576
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 5
telemt_me_writer_restored_same_endpoint_total 51
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 479522
telemt_user_connections_current{user="hello"} 5657
telemt_user_octets_from_client{user="hello"} 1759137364 (1.64 GB)
telemt_user_octets_to_client{user="hello"} 15147516756 (14.11 GB)
telemt_user_unique_ips_current{user="hello"} 1725
telemt_user_unique_ips_recent_window{user="hello"} 1029
```

## rdp-onedash.ru

```
telemt 3.3.27

telemt_uptime_seconds 1325.1 (0h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 436287
telemt_connections_bad_total 9449
telemt_connections_current 7055
telemt_connections_me_current 7055
telemt_handshake_timeouts_total 5343
telemt_upstream_connect_attempt_total 378
telemt_upstream_connect_success_total 373
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 378
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 188
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 182
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_reconnect_attempts_total 3
telemt_me_reconnect_success_total 5
telemt_me_reader_eof_total 3
telemt_me_idle_close_by_peer_total 3
telemt_me_route_drop_no_conn_total 683661
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 387093
telemt_me_endpoint_quarantine_total 8
telemt_me_single_endpoint_shadow_rotate_total 14
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
telemt_me_writers_active_current 43
telemt_desync_total 858
telemt_desync_full_logged_total 240
telemt_desync_suppressed_total 618
telemt_desync_frames_bucket_total{bucket="1_2"} 202
telemt_desync_frames_bucket_total{bucket="3_10"} 363
telemt_desync_frames_bucket_total{bucket="gt_10"} 293
telemt_pool_swap_total 1
telemt_pool_force_close_total 33
telemt_me_writer_close_signal_drop_total 6
telemt_me_draining_writers_reap_progress_total 267
telemt_me_writer_removed_unexpected_total 3
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 23
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 247
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 30
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 234
telemt_me_writer_teardown_success_total{mode="normal"} 270
telemt_me_writer_teardown_noop_total 267
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 493
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 513
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 513
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 537
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 537
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 537
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 537
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 537
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 537
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 537
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 537
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 537
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 537
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.604999
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 537
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 6
telemt_me_writer_restored_same_endpoint_total 3
telemt_user_connections_total{user="hello"} 387051
telemt_user_connections_current{user="hello"} 7055
telemt_user_octets_from_client{user="hello"} 2208182816 (2.06 GB)
telemt_user_octets_to_client{user="hello"} 27236905464 (25.37 GB)
telemt_user_unique_ips_current{user="hello"} 2122
telemt_user_unique_ips_recent_window{user="hello"} 1041
```

## hostvds.com

```
telemt 3.3.27

telemt_uptime_seconds 1322.2 (0h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 32481
telemt_connections_bad_total 5404
telemt_connections_current 891
telemt_connections_me_current 891
telemt_handshake_timeouts_total 457
telemt_upstream_connect_attempt_total 610
telemt_upstream_connect_success_total 610
telemt_upstream_connect_attempts_per_request{bucket="1"} 610
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 198
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 407
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_me_reconnect_attempts_total 95
telemt_me_reconnect_success_total 46
telemt_me_reader_eof_total 48
telemt_me_idle_close_by_peer_total 48
telemt_me_route_drop_no_conn_total 16499
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 23775
telemt_me_endpoint_quarantine_total 7
telemt_me_single_endpoint_shadow_rotate_total 14
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
telemt_me_writers_active_current 86
telemt_desync_total 42
telemt_desync_full_logged_total 19
telemt_desync_suppressed_total 23
telemt_desync_frames_bucket_total{bucket="1_2"} 5
telemt_desync_frames_bucket_total{bucket="3_10"} 17
telemt_desync_frames_bucket_total{bucket="gt_10"} 20
telemt_pool_force_close_total 1
telemt_me_writer_close_signal_drop_total 5
telemt_me_draining_writers_reap_progress_total 387
telemt_me_writer_removed_unexpected_total 48
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 66
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 370
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 386
telemt_me_writer_teardown_success_total{mode="normal"} 436
telemt_me_writer_teardown_noop_total 387
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 804
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 813
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 815
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 819
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 821
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 823
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 823
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 823
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 823
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 823
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 823
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 823
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 823
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.308097
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 823
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 5
telemt_me_refill_failed_total 3
telemt_me_writer_restored_same_endpoint_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 4
telemt_user_connections_total{user="hello"} 23776
telemt_user_connections_current{user="hello"} 891
telemt_user_octets_from_client{user="hello"} 297892684 (284.09 MB)
telemt_user_octets_to_client{user="hello"} 3989047328 (3.72 GB)
telemt_user_unique_ips_current{user="hello"} 309
telemt_user_unique_ips_recent_window{user="hello"} 142
```

## 4vps.su

```
telemt 3.3.27

telemt_uptime_seconds 1315.5 (0h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 236942
telemt_connections_bad_total 44605
telemt_connections_current 6823
telemt_connections_me_current 6823
telemt_handshake_timeouts_total 3705
telemt_upstream_connect_attempt_total 471
telemt_upstream_connect_success_total 455
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 469
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 235
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 220
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_reconnect_attempts_total 51
telemt_me_reconnect_success_total 51
telemt_me_reader_eof_total 48
telemt_me_idle_close_by_peer_total 48
telemt_me_route_drop_no_conn_total 109223
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 180179
telemt_me_endpoint_quarantine_total 6
telemt_me_single_endpoint_shadow_rotate_total 13
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
telemt_me_writers_active_current 90
telemt_desync_total 601
telemt_desync_full_logged_total 193
telemt_desync_suppressed_total 408
telemt_desync_frames_bucket_total{bucket="1_2"} 141
telemt_desync_frames_bucket_total{bucket="3_10"} 211
telemt_desync_frames_bucket_total{bucket="gt_10"} 249
telemt_me_writer_close_signal_drop_total 2
telemt_me_draining_writers_reap_progress_total 256
telemt_me_writer_removed_unexpected_total 48
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 55
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 249
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 256
telemt_me_writer_teardown_success_total{mode="normal"} 304
telemt_me_writer_teardown_noop_total 256
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 558
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 560
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 560
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 560
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 560
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 560
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 560
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 560
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 560
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 560
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 560
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 560
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 560
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.015866
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 560
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 2
telemt_me_writer_restored_same_endpoint_total 48
telemt_user_connections_total{user="hello"} 180181
telemt_user_connections_current{user="hello"} 6823
telemt_user_octets_from_client{user="hello"} 4695529136 (4.37 GB)
telemt_user_octets_to_client{user="hello"} 59738551456 (55.64 GB)
telemt_user_unique_ips_current{user="hello"} 2182
telemt_user_unique_ips_recent_window{user="hello"} 866
```