# Server Metrics 2026-03-20 10:45:26 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.27

telemt_uptime_seconds 1683.6 (0h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 146478
telemt_connections_bad_total 4250
telemt_connections_current 1518
telemt_connections_me_current 1518
telemt_handshake_timeouts_total 1260
telemt_upstream_connect_attempt_total 567
telemt_upstream_connect_success_total 557
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 566
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 227
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 329
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_reconnect_attempts_total 65
telemt_me_reconnect_success_total 12
telemt_me_reader_eof_total 12
telemt_me_idle_close_by_peer_total 12
telemt_me_route_drop_no_conn_total 247510
telemt_me_route_drop_channel_closed_total 53
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 125096
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
telemt_desync_total 235
telemt_desync_full_logged_total 82
telemt_desync_suppressed_total 153
telemt_desync_frames_bucket_total{bucket="1_2"} 62
telemt_desync_frames_bucket_total{bucket="3_10"} 89
telemt_desync_frames_bucket_total{bucket="gt_10"} 84
telemt_pool_swap_total 1
telemt_pool_force_close_total 27
telemt_me_writer_close_signal_drop_total 26
telemt_me_draining_writers_reap_progress_total 421
telemt_me_writer_removed_unexpected_total 12
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 36
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 393
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 27
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 394
telemt_me_writer_teardown_success_total{mode="normal"} 429
telemt_me_writer_teardown_noop_total 421
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 387
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 470
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 583
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 716
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 815
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 844
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 850
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 850
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 850
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 850
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 850
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 850
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 850
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 9.616516
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 850
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 26
telemt_me_refill_failed_total 3
telemt_me_writer_restored_same_endpoint_total 9
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 124785
telemt_user_connections_current{user="hello"} 1518
telemt_user_octets_from_client{user="hello"} 765908164 (730.43 MB)
telemt_user_octets_to_client{user="hello"} 10188248328 (9.49 GB)
telemt_user_unique_ips_current{user="hello"} 543
telemt_user_unique_ips_recent_window{user="hello"} 263
```

## psb.hosting №1

```
telemt 3.3.27

telemt_uptime_seconds 1666.2 (0h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 205402
telemt_connections_bad_total 23627
telemt_connections_current 4338
telemt_connections_me_current 4338
telemt_handshake_timeouts_total 5528
telemt_upstream_connect_attempt_total 660
telemt_upstream_connect_success_total 657
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 659
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 285
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 370
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 54
telemt_me_reconnect_success_total 50
telemt_me_reader_eof_total 50
telemt_me_idle_close_by_peer_total 50
telemt_me_route_drop_no_conn_total 164069
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 156860
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
telemt_desync_total 478
telemt_desync_full_logged_total 179
telemt_desync_suppressed_total 299
telemt_desync_frames_bucket_total{bucket="1_2"} 90
telemt_desync_frames_bucket_total{bucket="3_10"} 220
telemt_desync_frames_bucket_total{bucket="gt_10"} 168
telemt_me_writer_close_signal_drop_total 3
telemt_me_draining_writers_reap_progress_total 436
telemt_me_writer_removed_unexpected_total 51
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 69
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 418
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 436
telemt_me_writer_teardown_success_total{mode="normal"} 487
telemt_me_writer_teardown_noop_total 436
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 922
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 923
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 923
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 923
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 923
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 923
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 923
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 923
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 923
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 923
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 923
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 923
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 923
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.025123
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 923
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 3
telemt_me_writer_restored_same_endpoint_total 50
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 156888
telemt_user_connections_current{user="hello"} 4338
telemt_user_octets_from_client{user="hello"} 2197588320 (2.05 GB)
telemt_user_octets_to_client{user="hello"} 40659970624 (37.87 GB)
telemt_user_unique_ips_current{user="hello"} 1511
telemt_user_unique_ips_recent_window{user="hello"} 596
```

## psb.hosting №2

```
telemt 3.3.27

telemt_uptime_seconds 1655.7 (0h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 152427
telemt_connections_bad_total 22746
telemt_connections_current 3621
telemt_connections_me_current 3621
telemt_handshake_timeouts_total 1777
telemt_upstream_connect_attempt_total 536
telemt_upstream_connect_success_total 536
telemt_upstream_connect_attempts_per_request{bucket="1"} 536
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 298
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 238
telemt_me_reconnect_attempts_total 59
telemt_me_reconnect_success_total 9
telemt_me_reader_eof_total 11
telemt_me_idle_close_by_peer_total 11
telemt_me_route_drop_no_conn_total 52337
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 114868
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
telemt_desync_total 312
telemt_desync_full_logged_total 103
telemt_desync_suppressed_total 209
telemt_desync_frames_bucket_total{bucket="1_2"} 64
telemt_desync_frames_bucket_total{bucket="3_10"} 112
telemt_desync_frames_bucket_total{bucket="gt_10"} 136
telemt_pool_swap_total 1
telemt_pool_force_close_total 27
telemt_me_writer_close_signal_drop_total 1
telemt_me_draining_writers_reap_progress_total 402
telemt_me_writer_removed_unexpected_total 10
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 35
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 378
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 27
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 375
telemt_me_writer_teardown_success_total{mode="normal"} 413
telemt_me_writer_teardown_noop_total 402
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 810
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 814
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 815
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 815
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 815
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 815
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 815
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 815
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 815
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 815
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 815
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 815
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 815
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.054614
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 815
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1
telemt_me_refill_failed_total 3
telemt_me_writer_restored_same_endpoint_total 7
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 114892
telemt_user_connections_current{user="hello"} 3621
telemt_user_octets_from_client{user="hello"} 1665022088 (1.55 GB)
telemt_user_octets_to_client{user="hello"} 41223590696 (38.39 GB)
telemt_user_unique_ips_current{user="hello"} 1416
telemt_user_unique_ips_recent_window{user="hello"} 555
```

## koara.io

```
telemt 3.3.27

telemt_uptime_seconds 1462.0 (0h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 216971
telemt_connections_bad_total 19372
telemt_connections_current 5552
telemt_connections_me_current 5552
telemt_handshake_timeouts_total 3977
telemt_upstream_connect_attempt_total 430
telemt_upstream_connect_success_total 429
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 430
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 193
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 235
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 4
telemt_me_reconnect_success_total 4
telemt_me_reader_eof_total 3
telemt_me_idle_close_by_peer_total 3
telemt_me_route_drop_no_conn_total 112085
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 180542
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
telemt_desync_total 258
telemt_desync_full_logged_total 105
telemt_desync_suppressed_total 153
telemt_desync_frames_bucket_total{bucket="1_2"} 61
telemt_desync_frames_bucket_total{bucket="3_10"} 91
telemt_desync_frames_bucket_total{bucket="gt_10"} 106
telemt_pool_swap_total 1
telemt_pool_force_close_total 34
telemt_me_writer_close_signal_drop_total 1
telemt_me_draining_writers_reap_progress_total 315
telemt_me_writer_removed_unexpected_total 3
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 21
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 297
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 32
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 281
telemt_me_writer_teardown_success_total{mode="normal"} 318
telemt_me_writer_teardown_noop_total 315
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 575
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 583
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 589
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 591
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 605
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 607
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 633
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 633
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 633
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 633
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 633
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 633
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 633
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.780332
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 633
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1
telemt_me_writer_restored_same_endpoint_total 3
telemt_user_connections_total{user="hello"} 179891
telemt_user_connections_current{user="hello"} 5552
telemt_user_octets_from_client{user="hello"} 1894012816 (1.76 GB)
telemt_user_octets_to_client{user="hello"} 57874096508 (53.90 GB)
telemt_user_unique_ips_current{user="hello"} 1746
telemt_user_unique_ips_recent_window{user="hello"} 816
```

## landvps.ru

```
telemt 3.3.27

telemt_uptime_seconds 1445.3 (0h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 561020
telemt_connections_bad_total 7931
telemt_connections_current 5769
telemt_connections_me_current 5769
telemt_handshake_timeouts_total 4481
telemt_upstream_connect_attempt_total 595
telemt_upstream_connect_success_total 534
telemt_upstream_connect_fail_total 22
telemt_upstream_connect_attempts_per_request{bucket="1"} 556
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 219
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 287
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 22
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 58
telemt_me_reconnect_success_total 55
telemt_me_reader_eof_total 52
telemt_me_idle_close_by_peer_total 52
telemt_me_route_drop_no_conn_total 1127771
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 516820
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
telemt_desync_total 294
telemt_desync_full_logged_total 87
telemt_desync_suppressed_total 207
telemt_desync_frames_bucket_total{bucket="1_2"} 82
telemt_desync_frames_bucket_total{bucket="3_10"} 129
telemt_desync_frames_bucket_total{bucket="gt_10"} 83
telemt_me_writer_close_signal_drop_total 5
telemt_me_draining_writers_reap_progress_total 307
telemt_me_writer_removed_unexpected_total 54
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 66
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 295
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 307
telemt_me_writer_teardown_success_total{mode="normal"} 361
telemt_me_writer_teardown_noop_total 307
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 615
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 656
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 664
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 668
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 668
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 668
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 668
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 668
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 668
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 668
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 668
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 668
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 668
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.248030
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 668
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 5
telemt_me_writer_restored_same_endpoint_total 53
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 516781
telemt_user_connections_current{user="hello"} 5769
telemt_user_octets_from_client{user="hello"} 1909694532 (1.78 GB)
telemt_user_octets_to_client{user="hello"} 16564791348 (15.43 GB)
telemt_user_unique_ips_current{user="hello"} 1715
telemt_user_unique_ips_recent_window{user="hello"} 1011
```

## rdp-onedash.ru

```
telemt 3.3.27

telemt_uptime_seconds 1438.7 (0h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 459648
telemt_connections_bad_total 9849
telemt_connections_current 7068
telemt_connections_me_current 7068
telemt_handshake_timeouts_total 5667
telemt_upstream_connect_attempt_total 401
telemt_upstream_connect_success_total 396
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 401
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 197
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 196
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_reconnect_attempts_total 6
telemt_me_reconnect_success_total 8
telemt_me_reader_eof_total 6
telemt_me_idle_close_by_peer_total 6
telemt_me_route_drop_no_conn_total 711223
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 408579
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
telemt_desync_total 902
telemt_desync_full_logged_total 254
telemt_desync_suppressed_total 648
telemt_desync_frames_bucket_total{bucket="1_2"} 208
telemt_desync_frames_bucket_total{bucket="3_10"} 384
telemt_desync_frames_bucket_total{bucket="gt_10"} 310
telemt_pool_swap_total 1
telemt_pool_force_close_total 33
telemt_me_writer_close_signal_drop_total 6
telemt_me_draining_writers_reap_progress_total 285
telemt_me_writer_removed_unexpected_total 6
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 26
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 265
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 30
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 252
telemt_me_writer_teardown_success_total{mode="normal"} 291
telemt_me_writer_teardown_noop_total 285
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 532
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 552
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 552
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
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.606614
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 576
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 6
telemt_me_writer_restored_same_endpoint_total 6
telemt_user_connections_total{user="hello"} 408528
telemt_user_connections_current{user="hello"} 7068
telemt_user_octets_from_client{user="hello"} 2398941260 (2.23 GB)
telemt_user_octets_to_client{user="hello"} 29867253044 (27.82 GB)
telemt_user_unique_ips_current{user="hello"} 2122
telemt_user_unique_ips_recent_window{user="hello"} 957
```

## hostvds.com

```
telemt 3.3.27

telemt_uptime_seconds 1437.7 (0h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 35507
telemt_connections_bad_total 6405
telemt_connections_current 870
telemt_connections_me_current 870
telemt_handshake_timeouts_total 527
telemt_upstream_connect_attempt_total 680
telemt_upstream_connect_success_total 680
telemt_upstream_connect_attempts_per_request{bucket="1"} 680
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 219
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 456
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_me_reconnect_attempts_total 95
telemt_me_reconnect_success_total 46
telemt_me_reader_eof_total 48
telemt_me_idle_close_by_peer_total 48
telemt_me_route_drop_no_conn_total 17557
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 25569
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
telemt_desync_total 49
telemt_desync_full_logged_total 21
telemt_desync_suppressed_total 28
telemt_desync_frames_bucket_total{bucket="1_2"} 7
telemt_desync_frames_bucket_total{bucket="3_10"} 19
telemt_desync_frames_bucket_total{bucket="gt_10"} 23
telemt_pool_force_close_total 1
telemt_me_writer_close_signal_drop_total 5
telemt_me_draining_writers_reap_progress_total 457
telemt_me_writer_removed_unexpected_total 48
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 67
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 439
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 456
telemt_me_writer_teardown_success_total{mode="normal"} 506
telemt_me_writer_teardown_noop_total 457
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 943
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 953
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 955
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 959
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 961
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 963
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 963
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 963
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 963
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 963
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 963
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 963
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 963
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.311524
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 963
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 5
telemt_me_refill_failed_total 3
telemt_me_writer_restored_same_endpoint_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 4
telemt_user_connections_total{user="hello"} 25570
telemt_user_connections_current{user="hello"} 870
telemt_user_octets_from_client{user="hello"} 326202012 (311.09 MB)
telemt_user_octets_to_client{user="hello"} 4466512428 (4.16 GB)
telemt_user_unique_ips_current{user="hello"} 305
telemt_user_unique_ips_recent_window{user="hello"} 127
```

## 4vps.su

```
telemt 3.3.27

telemt_uptime_seconds 1429.2 (0h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 263524
telemt_connections_bad_total 55782
telemt_connections_current 7043
telemt_connections_me_current 7043
telemt_handshake_timeouts_total 4014
telemt_upstream_connect_attempt_total 520
telemt_upstream_connect_success_total 504
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 518
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 258
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 246
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_reconnect_attempts_total 51
telemt_me_reconnect_success_total 51
telemt_me_reader_eof_total 48
telemt_me_idle_close_by_peer_total 48
telemt_me_route_drop_no_conn_total 115322
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 194653
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
telemt_desync_total 663
telemt_desync_full_logged_total 207
telemt_desync_suppressed_total 456
telemt_desync_frames_bucket_total{bucket="1_2"} 161
telemt_desync_frames_bucket_total{bucket="3_10"} 232
telemt_desync_frames_bucket_total{bucket="gt_10"} 270
telemt_me_writer_close_signal_drop_total 2
telemt_me_draining_writers_reap_progress_total 305
telemt_me_writer_removed_unexpected_total 48
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 56
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 297
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 305
telemt_me_writer_teardown_success_total{mode="normal"} 353
telemt_me_writer_teardown_noop_total 305
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 656
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 658
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 658
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 658
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 658
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 658
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 658
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 658
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 658
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 658
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 658
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 658
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 658
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.017056
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 658
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 2
telemt_me_writer_restored_same_endpoint_total 48
telemt_user_connections_total{user="hello"} 194651
telemt_user_connections_current{user="hello"} 7043
telemt_user_octets_from_client{user="hello"} 5033559980 (4.69 GB)
telemt_user_octets_to_client{user="hello"} 65451581612 (60.96 GB)
telemt_user_unique_ips_current{user="hello"} 2158
telemt_user_unique_ips_recent_window{user="hello"} 934
```