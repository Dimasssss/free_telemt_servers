# Server Metrics 2026-03-20 11:06:30 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.27

telemt_uptime_seconds 2948.3 (0h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 211273
telemt_connections_bad_total 6485
telemt_connections_current 1716
telemt_connections_me_current 1716
telemt_handshake_timeouts_total 1921
telemt_upstream_connect_attempt_total 1043
telemt_upstream_connect_success_total 1027
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 1042
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 420
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 606
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_reconnect_attempts_total 197
telemt_me_reconnect_success_total 41
telemt_me_reader_eof_total 44
telemt_me_idle_close_by_peer_total 44
telemt_me_route_drop_no_conn_total 266944
telemt_me_route_drop_channel_closed_total 67
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 170798
telemt_me_writer_pick_total{mode="p2c",result="full"} 1
telemt_me_endpoint_quarantine_total 17
telemt_me_single_endpoint_shadow_rotate_total 27
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
telemt_me_writers_active_current 70
telemt_me_writers_warm_current 17
telemt_desync_total 417
telemt_desync_full_logged_total 147
telemt_desync_suppressed_total 270
telemt_desync_frames_bucket_total{bucket="1_2"} 106
telemt_desync_frames_bucket_total{bucket="3_10"} 148
telemt_desync_frames_bucket_total{bucket="gt_10"} 163
telemt_pool_swap_total 2
telemt_pool_force_close_total 59
telemt_me_writer_close_signal_drop_total 30
telemt_me_draining_writers_reap_progress_total 788
telemt_me_writer_removed_unexpected_total 44
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 79
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 749
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 58
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 729
telemt_me_writer_teardown_success_total{mode="normal"} 828
telemt_me_writer_teardown_noop_total 788
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 1061
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 1169
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 1300
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 1454
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 1565
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 1609
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 1616
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 1616
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 1616
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 1616
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 1616
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 1616
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 1616
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 11.708595
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 1616
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 30
telemt_me_refill_failed_total 9
telemt_me_writer_restored_same_endpoint_total 35
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 170469
telemt_user_connections_current{user="hello"} 1716
telemt_user_octets_from_client{user="hello"} 1525193368 (1.42 GB)
telemt_user_octets_to_client{user="hello"} 22460506112 (20.92 GB)
telemt_user_unique_ips_current{user="hello"} 592
telemt_user_unique_ips_recent_window{user="hello"} 257
```

## psb.hosting №1

```
telemt 3.3.27

telemt_uptime_seconds 2930.3 (0h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 362174
telemt_connections_bad_total 58854
telemt_connections_current 4036
telemt_connections_me_current 4036
telemt_handshake_timeouts_total 8824
telemt_upstream_connect_attempt_total 1248
telemt_upstream_connect_success_total 1241
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 1247
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 570
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 665
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_reconnect_attempts_total 473
telemt_me_reconnect_success_total 306
telemt_me_reader_eof_total 315
telemt_me_idle_close_by_peer_total 315
telemt_me_route_drop_no_conn_total 227389
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 263478
telemt_me_endpoint_quarantine_total 8
telemt_me_single_endpoint_shadow_rotate_total 24
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
telemt_me_writers_active_current 44
telemt_desync_total 899
telemt_desync_full_logged_total 307
telemt_desync_suppressed_total 592
telemt_desync_frames_bucket_total{bucket="1_2"} 175
telemt_desync_frames_bucket_total{bucket="3_10"} 405
telemt_desync_frames_bucket_total{bucket="gt_10"} 319
telemt_pool_swap_total 1
telemt_pool_force_close_total 83
telemt_me_writer_close_signal_drop_total 28
telemt_me_draining_writers_reap_progress_total 784
telemt_me_writer_removed_unexpected_total 315
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 375
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 726
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 58
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 701
telemt_me_writer_teardown_success_total{mode="normal"} 1101
telemt_me_writer_teardown_noop_total 784
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 1814
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 1854
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 1870
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 1885
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 1885
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 1885
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 1885
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 1885
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 1885
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 1885
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 1885
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 1885
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 1885
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.470401
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 1885
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 28
telemt_me_refill_failed_total 7
telemt_me_writer_restored_same_endpoint_total 304
telemt_me_writer_removed_unexpected_minus_restored_total 11
telemt_user_connections_total{user="hello"} 263466
telemt_user_connections_current{user="hello"} 4036
telemt_user_octets_from_client{user="hello"} 3807198204 (3.55 GB)
telemt_user_octets_to_client{user="hello"} 79764184344 (74.29 GB)
telemt_user_unique_ips_current{user="hello"} 1318
telemt_user_unique_ips_recent_window{user="hello"} 920
```

## psb.hosting №2

```
telemt 3.3.27

telemt_uptime_seconds 2918.7 (0h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 270862
telemt_connections_bad_total 37515
telemt_connections_current 4135
telemt_connections_me_current 4135
telemt_handshake_timeouts_total 3566
telemt_upstream_connect_attempt_total 1166
telemt_upstream_connect_success_total 1164
telemt_upstream_connect_attempts_per_request{bucket="1"} 1164
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 612
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 548
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_reconnect_attempts_total 120
telemt_me_reconnect_success_total 65
telemt_me_reader_eof_total 72
telemt_me_idle_close_by_peer_total 72
telemt_me_route_drop_no_conn_total 87524
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 204671
telemt_me_endpoint_quarantine_total 3
telemt_me_single_endpoint_shadow_rotate_total 21
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
telemt_me_writers_active_current 95
telemt_me_writers_warm_current 27
telemt_desync_total 574
telemt_desync_full_logged_total 189
telemt_desync_suppressed_total 385
telemt_desync_frames_bucket_total{bucket="1_2"} 114
telemt_desync_frames_bucket_total{bucket="3_10"} 219
telemt_desync_frames_bucket_total{bucket="gt_10"} 241
telemt_pool_swap_total 1
telemt_pool_force_close_total 27
telemt_me_writer_close_signal_drop_total 3
telemt_me_draining_writers_reap_progress_total 858
telemt_me_writer_removed_unexpected_total 71
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 112
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 818
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 27
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 831
telemt_me_writer_teardown_success_total{mode="normal"} 930
telemt_me_writer_teardown_noop_total 858
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 1772
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 1787
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 1788
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 1788
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 1788
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 1788
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 1788
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 1788
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 1788
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 1788
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 1788
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 1788
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 1788
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.113576
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 1788
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 3
telemt_me_refill_failed_total 3
telemt_me_writer_restored_same_endpoint_total 63
telemt_me_writer_removed_unexpected_minus_restored_total 8
telemt_user_connections_total{user="hello"} 204713
telemt_user_connections_current{user="hello"} 4135
telemt_user_octets_from_client{user="hello"} 2631091332 (2.45 GB)
telemt_user_octets_to_client{user="hello"} 75267029032 (70.10 GB)
telemt_user_unique_ips_current{user="hello"} 1589
telemt_user_unique_ips_recent_window{user="hello"} 569
```

## koara.io

```
telemt 3.3.27

telemt_uptime_seconds 2725.9 (0h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 438472
telemt_connections_bad_total 46125
telemt_connections_current 5523
telemt_connections_me_current 5523
telemt_handshake_timeouts_total 6903
telemt_upstream_connect_attempt_total 904
telemt_upstream_connect_success_total 903
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 904
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 385
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 513
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 52
telemt_me_reconnect_success_total 48
telemt_me_reader_eof_total 49
telemt_me_idle_close_by_peer_total 49
telemt_me_route_drop_no_conn_total 223544
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 358139
telemt_me_endpoint_quarantine_total 10
telemt_me_single_endpoint_shadow_rotate_total 21
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
telemt_me_writers_active_current 84
telemt_me_writers_warm_current 1
telemt_desync_total 605
telemt_desync_full_logged_total 209
telemt_desync_suppressed_total 396
telemt_desync_frames_bucket_total{bucket="1_2"} 161
telemt_desync_frames_bucket_total{bucket="3_10"} 226
telemt_desync_frames_bucket_total{bucket="gt_10"} 218
telemt_pool_swap_total 1
telemt_pool_force_close_total 34
telemt_me_writer_close_signal_drop_total 8
telemt_me_draining_writers_reap_progress_total 674
telemt_me_writer_removed_unexpected_total 49
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 77
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 647
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 32
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 640
telemt_me_writer_teardown_success_total{mode="normal"} 724
telemt_me_writer_teardown_noop_total 674
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 1295
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 1342
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 1352
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 1356
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 1370
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 1372
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 1398
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 1398
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 1398
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 1398
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 1398
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 1398
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 1398
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.959002
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 1398
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 8
telemt_me_writer_restored_same_endpoint_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 357474
telemt_user_connections_current{user="hello"} 5523
telemt_user_octets_from_client{user="hello"} 3929493552 (3.66 GB)
telemt_user_octets_to_client{user="hello"} 108351193180 (100.91 GB)
telemt_user_unique_ips_current{user="hello"} 1796
telemt_user_unique_ips_recent_window{user="hello"} 714
```

## landvps.ru

```
telemt 3.3.27

telemt_uptime_seconds 2710.0 (0h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1049592
telemt_connections_bad_total 18655
telemt_connections_current 5795
telemt_connections_me_current 5795
telemt_handshake_timeouts_total 7589
telemt_upstream_connect_attempt_total 1167
telemt_upstream_connect_success_total 1077
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 1108
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 466
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 577
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 34
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_keepalive_timeout_total 51
telemt_me_reconnect_attempts_total 424
telemt_me_reconnect_success_total 225
telemt_me_reader_eof_total 231
telemt_me_idle_close_by_peer_total 231
telemt_me_route_drop_no_conn_total 2215249
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 968789
telemt_me_endpoint_quarantine_total 4
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
telemt_me_writers_active_current 126
telemt_desync_total 866
telemt_desync_full_logged_total 237
telemt_desync_suppressed_total 629
telemt_desync_frames_bucket_total{bucket="1_2"} 224
telemt_desync_frames_bucket_total{bucket="3_10"} 343
telemt_desync_frames_bucket_total{bucket="gt_10"} 299
telemt_me_writer_close_signal_drop_total 17
telemt_me_draining_writers_reap_progress_total 624
telemt_me_writer_removed_unexpected_total 233
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 256
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 601
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 624
telemt_me_writer_teardown_success_total{mode="normal"} 857
telemt_me_writer_teardown_noop_total 624
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 1387
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 1464
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 1475
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 1481
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 1481
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 1481
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 1481
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 1481
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 1481
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 1481
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 1481
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 1481
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 1481
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.415258
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 1481
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 17
telemt_me_refill_failed_total 6
telemt_me_writer_restored_same_endpoint_total 223
telemt_me_writer_removed_unexpected_minus_restored_total 10
telemt_user_connections_total{user="hello"} 968742
telemt_user_connections_current{user="hello"} 5795
telemt_user_octets_from_client{user="hello"} 3658396868 (3.41 GB)
telemt_user_octets_to_client{user="hello"} 31495588832 (29.33 GB)
telemt_user_unique_ips_current{user="hello"} 1813
telemt_user_unique_ips_recent_window{user="hello"} 1117
```

## rdp-onedash.ru

```
telemt 3.3.27

telemt_uptime_seconds 2702.2 (0h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 790477
telemt_connections_bad_total 24906
telemt_connections_current 7347
telemt_connections_me_current 7347
telemt_handshake_timeouts_total 9535
telemt_upstream_connect_attempt_total 888
telemt_upstream_connect_success_total 876
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 888
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 427
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 442
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_reconnect_attempts_total 54
telemt_me_reconnect_success_total 55
telemt_me_reader_eof_total 53
telemt_me_idle_close_by_peer_total 53
telemt_me_route_drop_no_conn_total 1219770
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 701674
telemt_me_endpoint_quarantine_total 10
telemt_me_single_endpoint_shadow_rotate_total 20
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
telemt_me_writers_active_current 88
telemt_desync_total 1528
telemt_desync_full_logged_total 453
telemt_desync_suppressed_total 1075
telemt_desync_frames_bucket_total{bucket="1_2"} 340
telemt_desync_frames_bucket_total{bucket="3_10"} 637
telemt_desync_frames_bucket_total{bucket="gt_10"} 551
telemt_pool_swap_total 1
telemt_pool_force_close_total 33
telemt_me_writer_close_signal_drop_total 10
telemt_me_draining_writers_reap_progress_total 646
telemt_me_writer_removed_unexpected_total 53
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 84
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 615
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 30
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 613
telemt_me_writer_teardown_success_total{mode="normal"} 699
telemt_me_writer_teardown_noop_total 646
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 1297
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 1321
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 1321
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 1345
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 1345
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 1345
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 1345
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 1345
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 1345
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 1345
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 1345
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 1345
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 1345
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.626255
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 1345
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 10
telemt_me_writer_restored_same_endpoint_total 53
telemt_user_connections_total{user="hello"} 701567
telemt_user_connections_current{user="hello"} 7347
telemt_user_octets_from_client{user="hello"} 5704002724 (5.31 GB)
telemt_user_octets_to_client{user="hello"} 57774205204 (53.81 GB)
telemt_user_unique_ips_current{user="hello"} 2214
telemt_user_unique_ips_recent_window{user="hello"} 1221
```

## hostvds.com

```
telemt 3.3.27

telemt_uptime_seconds 2701.7 (0h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 60983
telemt_connections_bad_total 8972
telemt_connections_current 868
telemt_connections_me_current 868
telemt_handshake_timeouts_total 686
telemt_upstream_connect_attempt_total 1572
telemt_upstream_connect_success_total 1572
telemt_upstream_connect_attempts_per_request{bucket="1"} 1572
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 490
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1074
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 386
telemt_me_reconnect_success_total 207
telemt_me_reader_eof_total 221
telemt_me_idle_close_by_peer_total 221
telemt_me_route_drop_no_conn_total 31373
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 46552
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
telemt_desync_total 109
telemt_desync_full_logged_total 38
telemt_desync_suppressed_total 71
telemt_desync_frames_bucket_total{bucket="1_2"} 34
telemt_desync_frames_bucket_total{bucket="3_10"} 31
telemt_desync_frames_bucket_total{bucket="gt_10"} 44
telemt_pool_force_close_total 1
telemt_me_writer_close_signal_drop_total 6
telemt_me_draining_writers_reap_progress_total 1115
telemt_me_writer_removed_unexpected_total 218
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 256
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 1081
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 1114
telemt_me_writer_teardown_success_total{mode="normal"} 1337
telemt_me_writer_teardown_noop_total 1115
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 2383
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 2426
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 2435
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 2444
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 2450
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 2452
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 2452
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 2452
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 2452
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 2452
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 2452
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 2452
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 2452
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.736403
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 2452
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 6
telemt_me_refill_failed_total 7
telemt_me_writer_restored_same_endpoint_total 205
telemt_me_writer_removed_unexpected_minus_restored_total 13
telemt_user_connections_total{user="hello"} 46562
telemt_user_connections_current{user="hello"} 868
telemt_user_octets_from_client{user="hello"} 593981272 (566.46 MB)
telemt_user_octets_to_client{user="hello"} 7871668348 (7.33 GB)
telemt_user_unique_ips_current{user="hello"} 303
telemt_user_unique_ips_recent_window{user="hello"} 145
```

## 4vps.su

```
telemt 3.3.27

telemt_uptime_seconds 2692.8 (0h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 445325
telemt_connections_bad_total 72306
telemt_connections_current 7005
telemt_connections_me_current 7005
telemt_handshake_timeouts_total 9099
telemt_upstream_connect_attempt_total 1245
telemt_upstream_connect_success_total 1223
telemt_upstream_connect_fail_total 20
telemt_upstream_connect_attempts_per_request{bucket="1"} 1243
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 647
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 575
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 20
telemt_me_reconnect_attempts_total 317
telemt_me_reconnect_success_total 124
telemt_me_reader_eof_total 130
telemt_me_idle_close_by_peer_total 130
telemt_me_route_drop_no_conn_total 192230
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 349579
telemt_me_endpoint_quarantine_total 6
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
telemt_me_writers_active_current 127
telemt_desync_total 1161
telemt_desync_full_logged_total 382
telemt_desync_suppressed_total 779
telemt_desync_frames_bucket_total{bucket="1_2"} 264
telemt_desync_frames_bucket_total{bucket="3_10"} 414
telemt_desync_frames_bucket_total{bucket="gt_10"} 483
telemt_me_writer_close_signal_drop_total 6
telemt_me_draining_writers_reap_progress_total 890
telemt_me_writer_removed_unexpected_total 128
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 157
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 864
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 890
telemt_me_writer_teardown_success_total{mode="normal"} 1021
telemt_me_writer_teardown_noop_total 890
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 1907
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 1911
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 1911
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 1911
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 1911
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 1911
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 1911
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 1911
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 1911
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 1911
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 1911
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 1911
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 1911
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.064722
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 1911
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 6
telemt_me_refill_failed_total 6
telemt_me_writer_restored_same_endpoint_total 121
telemt_me_writer_removed_unexpected_minus_restored_total 7
telemt_user_connections_total{user="hello"} 349538
telemt_user_connections_current{user="hello"} 7005
telemt_user_octets_from_client{user="hello"} 9572292232 (8.91 GB)
telemt_user_octets_to_client{user="hello"} 128762564576 (119.92 GB)
telemt_user_unique_ips_current{user="hello"} 2175
telemt_user_unique_ips_recent_window{user="hello"} 897
```