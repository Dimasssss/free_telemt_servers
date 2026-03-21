# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

### **Принимаю донаты криптой для добавления и продления серверов:**
- TON (Можно отправлять TON и USDT в сети TON):
```
UQAyIvWts4-gC0b5ouoy_JNDfBEe337c7oOBqpGXFB8fJUzB
```
### **Спасибо:**
- Ivan Morozov - 20$

_Можете писать свой ник в коментарии к переводу_

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-60
- Краткое описание тарифа: 4 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 26 апреля
- Ссылка:
```bash
tg://proxy?server=s1.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## psb.hosting (2 сервера)
- Локация: Finland
- Тариф: FI-200
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 12$
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

## rdp-onedash.ru (2 сервера)
- Локация: Нидерланды
- Тариф: Mini
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 1 Gbit/s
- Цена в месяц: 844 RUB
- Ссылка:
```bash
tg://proxy?server=s5.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## hostvds.com
- Локация: Франция, Париж
- Тариф: Highload-2
- Краткое описание тарифа: 2 vCore, 8 Gb ram, 10 Gbit/s
- Цена в месяц: €12.57
- Ссылка:
```bash
tg://proxy?server=s6.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## 4vps.su (2 сервера)
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

# Server Metrics 2026-03-21 22:11:08 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 3885.8 (1h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 76103
telemt_connections_bad_total 5897
telemt_connections_current 703
telemt_connections_me_current 703
telemt_handshake_timeouts_total 3499
telemt_upstream_connect_attempt_total 1594
telemt_upstream_connect_success_total 1593
telemt_upstream_connect_attempts_per_request{bucket="1"} 1593
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 588
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 993
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_me_reconnect_attempts_total 41
telemt_me_reconnect_success_total 23
telemt_me_reader_eof_total 24
telemt_me_idle_close_by_peer_total 24
telemt_me_route_drop_no_conn_total 16454
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 60953
telemt_me_endpoint_quarantine_total 25
telemt_me_single_endpoint_shadow_rotate_total 38
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
telemt_me_writers_active_current 47
telemt_desync_total 466
telemt_desync_full_logged_total 144
telemt_desync_suppressed_total 322
telemt_desync_frames_bucket_total{bucket="1_2"} 89
telemt_desync_frames_bucket_total{bucket="3_10"} 153
telemt_desync_frames_bucket_total{bucket="gt_10"} 224
telemt_pool_swap_total 4
telemt_pool_force_close_total 102
telemt_me_writer_close_signal_drop_total 9
telemt_me_draining_writers_reap_progress_total 1360
telemt_me_writer_removed_unexpected_total 22
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 93
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 1291
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 102
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 1258
telemt_me_writer_teardown_success_total{mode="normal"} 1384
telemt_me_writer_teardown_noop_total 1360
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 2638
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 2694
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 2714
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 2732
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 2742
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 2744
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 2744
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 2744
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 2744
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 2744
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 2744
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 2744
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 2744
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.102288
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 2744
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 9
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 21
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 60895
telemt_user_connections_current{user="hello"} 703
telemt_user_octets_from_client{user="hello"} 836821824 (798.06 MB)
telemt_user_octets_to_client{user="hello"} 20720794852 (19.30 GB)
telemt_user_unique_ips_current{user="hello"} 299
telemt_user_unique_ips_recent_window{user="hello"} 98
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 17252.5 (4h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 588252
telemt_connections_bad_total 27808
telemt_connections_current 1133
telemt_connections_me_current 1133
telemt_handshake_timeouts_total 21001
telemt_upstream_connect_attempt_total 7018
telemt_upstream_connect_success_total 6880
telemt_upstream_connect_fail_total 122
telemt_upstream_connect_attempts_per_request{bucket="1"} 7002
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3047
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3809
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 122
telemt_me_reconnect_attempts_total 619
telemt_me_reconnect_success_total 221
telemt_me_reader_eof_total 189
telemt_me_idle_close_by_peer_total 189
telemt_me_route_drop_no_conn_total 308623
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 477258
telemt_me_endpoint_quarantine_total 144
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 137
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 13
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
telemt_desync_total 2123
telemt_desync_full_logged_total 1205
telemt_desync_suppressed_total 918
telemt_desync_frames_bucket_total{bucket="1_2"} 445
telemt_desync_frames_bucket_total{bucket="3_10"} 807
telemt_desync_frames_bucket_total{bucket="gt_10"} 871
telemt_pool_swap_total 19
telemt_pool_force_close_total 528
telemt_me_writer_close_signal_drop_total 40
telemt_me_draining_writers_reap_progress_total 6130
telemt_me_writer_removed_unexpected_total 178
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 539
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 5767
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 521
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 5602
telemt_me_writer_teardown_success_total{mode="normal"} 6306
telemt_me_writer_teardown_noop_total 6130
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 12051
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 12275
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 12338
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 12422
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 12434
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 12436
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 12436
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 12436
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 12436
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 12436
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 12436
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 12436
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 12436
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.920241
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 12436
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 40
telemt_me_refill_failed_total 21
telemt_me_writer_restored_same_endpoint_total 152
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 6
telemt_me_writer_removed_unexpected_minus_restored_total 21
telemt_user_connections_total{user="hello"} 476626
telemt_user_connections_current{user="hello"} 1133
telemt_user_octets_from_client{user="hello"} 8299747476 (7.73 GB)
telemt_user_octets_to_client{user="hello"} 159978614504 (148.99 GB)
telemt_user_unique_ips_current{user="hello"} 707
telemt_user_unique_ips_recent_window{user="hello"} 191
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 92112.5 (25h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7209368
telemt_connections_bad_total 554545
telemt_connections_current 2200
telemt_connections_me_current 2200
telemt_handshake_timeouts_total 225510
telemt_upstream_connect_attempt_total 33141
telemt_upstream_connect_success_total 33073
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 33080
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14913
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18004
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 150
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1450
telemt_me_reconnect_success_total 701
telemt_me_reader_eof_total 713
telemt_me_idle_close_by_peer_total 713
telemt_me_route_drop_no_conn_total 4451949
telemt_me_route_drop_channel_closed_total 66
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5898578
telemt_me_endpoint_quarantine_total 578
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 680
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 23
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
telemt_desync_total 24907
telemt_desync_full_logged_total 8192
telemt_desync_suppressed_total 16715
telemt_desync_frames_bucket_total{bucket="1_2"} 5355
telemt_desync_frames_bucket_total{bucket="3_10"} 9761
telemt_desync_frames_bucket_total{bucket="gt_10"} 9791
telemt_pool_swap_total 99
telemt_pool_force_close_total 3345
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 553
telemt_me_draining_writers_reap_progress_total 30177
telemt_me_writer_removed_unexpected_total 685
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2591
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 27864
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3106
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 239
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26832
telemt_me_writer_teardown_success_total{mode="normal"} 30455
telemt_me_writer_teardown_noop_total 30221
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 55014
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 56711
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 57612
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 58958
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 59850
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 60375
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 60665
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 60676
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 60676
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 60676
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 60676
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 60676
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 60676
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 149.156648
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 60676
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 553
telemt_me_refill_failed_total 39
telemt_me_writer_restored_same_endpoint_total 627
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 53
telemt_user_connections_total{user="hello"} 5891376
telemt_user_connections_current{user="hello"} 2200
telemt_user_octets_from_client{user="hello"} 101221400952 (94.27 GB)
telemt_user_octets_to_client{user="hello"} 1903674025136 (1.73 TB)
telemt_user_unique_ips_current{user="hello"} 909
telemt_user_unique_ips_recent_window{user="hello"} 306
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 92114.2 (25h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5907900
telemt_connections_bad_total 572415
telemt_connections_current 2104
telemt_connections_me_current 2104
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 192860
telemt_upstream_connect_attempt_total 37102
telemt_upstream_connect_success_total 36769
telemt_upstream_connect_fail_total 173
telemt_upstream_connect_attempts_per_request{bucket="1"} 36942
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18544
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17656
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 542
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 173
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 1727
telemt_me_reconnect_success_total 732
telemt_me_reader_eof_total 706
telemt_me_idle_close_by_peer_total 706
telemt_me_route_drop_no_conn_total 2066667
telemt_me_route_drop_channel_closed_total 236
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4411147
telemt_me_endpoint_quarantine_total 560
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 704
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 28
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
telemt_desync_total 21260
telemt_desync_full_logged_total 7101
telemt_desync_suppressed_total 14159
telemt_desync_frames_bucket_total{bucket="1_2"} 5137
telemt_desync_frames_bucket_total{bucket="3_10"} 8220
telemt_desync_frames_bucket_total{bucket="gt_10"} 7903
telemt_pool_swap_total 101
telemt_pool_force_close_total 3065
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 339
telemt_me_draining_writers_reap_progress_total 28797
telemt_me_writer_removed_unexpected_total 684
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2484
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 26928
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2866
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 199
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 25732
telemt_me_writer_teardown_success_total{mode="normal"} 29412
telemt_me_writer_teardown_noop_total 28803
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 55050
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 56516
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 57066
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 57630
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 58010
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 58195
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 58215
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 58215
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 58215
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 58215
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 58215
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 58215
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 58215
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 46.438480
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 58215
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 339
telemt_me_refill_failed_total 53
telemt_me_writer_restored_same_endpoint_total 630
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 4382039
telemt_user_connections_current{user="hello"} 2104
telemt_user_octets_from_client{user="hello"} 135818024821 (126.49 GB)
telemt_user_octets_to_client{user="hello"} 2036678481935 (1.85 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 900
telemt_user_unique_ips_recent_window{user="hello"} 236
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 92077.7 (25h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5831516
telemt_connections_bad_total 531014
telemt_connections_current 1773
telemt_connections_me_current 1773
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 181803
telemt_upstream_connect_attempt_total 43522
telemt_upstream_connect_success_total 43228
telemt_upstream_connect_fail_total 135
telemt_upstream_connect_attempts_per_request{bucket="1"} 43363
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22751
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19088
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 345
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1044
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 135
telemt_me_keepalive_timeout_total 58
telemt_me_reconnect_attempts_total 1776
telemt_me_reconnect_success_total 793
telemt_me_reader_eof_total 740
telemt_me_idle_close_by_peer_total 740
telemt_me_route_drop_no_conn_total 2063538
telemt_me_route_drop_channel_closed_total 108
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4369473
telemt_me_endpoint_quarantine_total 616
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 687
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 33
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
telemt_me_writers_active_current 42
telemt_desync_total 21071
telemt_desync_full_logged_total 6924
telemt_desync_suppressed_total 14147
telemt_desync_frames_bucket_total{bucket="1_2"} 5217
telemt_desync_frames_bucket_total{bucket="3_10"} 7988
telemt_desync_frames_bucket_total{bucket="gt_10"} 7866
telemt_pool_swap_total 99
telemt_pool_force_close_total 2941
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 353
telemt_me_draining_writers_reap_progress_total 30230
telemt_me_writer_removed_unexpected_total 709
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2571
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 28373
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2726
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 215
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 27289
telemt_me_writer_teardown_success_total{mode="normal"} 30944
telemt_me_writer_teardown_noop_total 30241
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 58817
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 60114
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 60525
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 60955
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 61160
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 61182
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 61185
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 61185
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 61185
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 61185
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 61185
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 61185
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 61185
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 22.841672
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 61185
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 353
telemt_me_refill_failed_total 54
telemt_me_writer_restored_same_endpoint_total 687
telemt_me_writer_restored_fallback_total 4
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 18
telemt_user_connections_total{user="hello"} 4371168
telemt_user_connections_current{user="hello"} 1773
telemt_user_octets_from_client{user="hello"} 128455695811 (119.63 GB)
telemt_user_octets_to_client{user="hello"} 1997386530903 (1.82 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 840
telemt_user_unique_ips_recent_window{user="hello"} 211
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 92117.1 (25h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19602554
telemt_connections_bad_total 1357577
telemt_connections_current 2902
telemt_connections_me_current 2902
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 556250
telemt_upstream_connect_attempt_total 183194
telemt_upstream_connect_success_total 165879
telemt_upstream_connect_fail_total 15820
telemt_upstream_connect_attempts_per_request{bucket="1"} 181699
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 117963
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 37905
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1154
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8857
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15820
telemt_me_keepalive_timeout_total 398
telemt_me_reconnect_attempts_total 59724
telemt_me_reconnect_success_total 1955
telemt_me_reader_eof_total 1286
telemt_me_idle_close_by_peer_total 1285
telemt_me_route_drop_no_conn_total 39390273
telemt_me_route_drop_channel_closed_total 120
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 16046999
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 5
telemt_me_endpoint_quarantine_total 672
telemt_me_single_endpoint_outage_enter_total 111
telemt_me_single_endpoint_outage_exit_total 111
telemt_me_single_endpoint_outage_reconnect_attempt_total 239
telemt_me_single_endpoint_outage_reconnect_success_total 53
telemt_me_single_endpoint_quarantine_bypass_total 239
telemt_me_single_endpoint_shadow_rotate_total 713
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 53
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
telemt_desync_total 30622
telemt_desync_full_logged_total 9063
telemt_desync_suppressed_total 21559
telemt_desync_frames_bucket_total{bucket="1_2"} 6692
telemt_desync_frames_bucket_total{bucket="3_10"} 13575
telemt_desync_frames_bucket_total{bucket="gt_10"} 10355
telemt_pool_swap_total 94
telemt_pool_force_close_total 3179
telemt_pool_stale_pick_total 5
telemt_me_writer_close_signal_drop_total 721
telemt_me_draining_writers_reap_progress_total 28479
telemt_me_writer_removed_unexpected_total 1836
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3869
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 26173
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 23
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2671
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 508
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 25300
telemt_me_writer_teardown_success_total{mode="normal"} 30042
telemt_me_writer_teardown_noop_total 28505
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 52320
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 54521
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 55712
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 57223
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 58115
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 58446
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 58528
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 58530
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 58533
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 58538
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 58538
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 58542
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 58547
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 208.442986
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 58547
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 721
telemt_me_refill_failed_total 3520
telemt_me_writer_restored_same_endpoint_total 1374
telemt_me_writer_restored_fallback_total 12
telemt_me_no_writer_failfast_total 666
telemt_me_async_recovery_trigger_total 14245
telemt_me_writer_removed_unexpected_minus_restored_total 450
telemt_user_connections_total{user="hello"} 16171984
telemt_user_connections_current{user="hello"} 2902
telemt_user_octets_from_client{user="hello"} 168125140270 (156.58 GB)
telemt_user_octets_to_client{user="hello"} 1040788594090 (969.31 GB)
telemt_user_msgs_from_client{user="hello"} 361669
telemt_user_msgs_to_client{user="hello"} 643484
telemt_user_unique_ips_current{user="hello"} 1205
telemt_user_unique_ips_recent_window{user="hello"} 347
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 92084.5 (25h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5660513
telemt_connections_bad_total 532171
telemt_connections_current 1542
telemt_connections_me_current 1542
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 117293
telemt_upstream_connect_attempt_total 50926
telemt_upstream_connect_success_total 50397
telemt_upstream_connect_fail_total 443
telemt_upstream_connect_attempts_per_request{bucket="1"} 50840
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30452
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19610
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 334
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 443
telemt_me_reconnect_attempts_total 11325
telemt_me_reconnect_success_total 1321
telemt_me_reader_eof_total 1234
telemt_me_idle_close_by_peer_total 1234
telemt_me_route_drop_no_conn_total 2323356
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 39
telemt_me_route_drop_queue_full_profile_total{profile="high"} 39
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4405138
telemt_me_endpoint_quarantine_total 572
telemt_me_single_endpoint_outage_enter_total 15
telemt_me_single_endpoint_outage_exit_total 15
telemt_me_single_endpoint_outage_reconnect_attempt_total 15
telemt_me_single_endpoint_outage_reconnect_success_total 15
telemt_me_single_endpoint_quarantine_bypass_total 15
telemt_me_single_endpoint_shadow_rotate_total 688
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 31
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
telemt_desync_total 22146
telemt_desync_full_logged_total 7694
telemt_desync_suppressed_total 14452
telemt_desync_frames_bucket_total{bucket="1_2"} 4231
telemt_desync_frames_bucket_total{bucket="3_10"} 8600
telemt_desync_frames_bucket_total{bucket="gt_10"} 9315
telemt_pool_swap_total 94
telemt_pool_force_close_total 2760
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 356
telemt_me_draining_writers_reap_progress_total 31180
telemt_me_writer_removed_unexpected_total 1225
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3177
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 29242
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2392
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 368
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 28420
telemt_me_writer_teardown_success_total{mode="normal"} 32419
telemt_me_writer_teardown_noop_total 31181
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 62448
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 63197
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 63448
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 63568
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 63597
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 63600
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 63600
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 63600
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 63600
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 63600
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 63600
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 63600
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 63600
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.618854
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 63600
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 356
telemt_me_refill_failed_total 601
telemt_me_writer_restored_same_endpoint_total 1106
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 1516
telemt_me_writer_removed_unexpected_minus_restored_total 99
telemt_user_connections_total{user="hello"} 4398463
telemt_user_connections_current{user="hello"} 1542
telemt_user_octets_from_client{user="hello"} 117043470444 (109.01 GB)
telemt_user_octets_to_client{user="hello"} 1786838844994 (1.63 TB)
telemt_user_msgs_from_client{user="hello"} 77823
telemt_user_msgs_to_client{user="hello"} 338392
telemt_user_unique_ips_current{user="hello"} 700
telemt_user_unique_ips_recent_window{user="hello"} 271
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 28920.3 (8h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3467148
telemt_connections_bad_total 124166
telemt_connections_current 2368
telemt_connections_me_current 2368
telemt_handshake_timeouts_total 1466179
telemt_upstream_connect_attempt_total 9815
telemt_upstream_connect_success_total 9691
telemt_upstream_connect_fail_total 118
telemt_upstream_connect_attempts_per_request{bucket="1"} 9809
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4338
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5300
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 118
telemt_me_reconnect_attempts_total 2361
telemt_me_reconnect_success_total 328
telemt_me_reader_eof_total 246
telemt_me_idle_close_by_peer_total 246
telemt_me_route_drop_no_conn_total 967235
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1660105
telemt_me_endpoint_quarantine_total 150
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 214
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 6
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
telemt_me_writers_active_current 42
telemt_desync_total 9140
telemt_desync_full_logged_total 3077
telemt_desync_suppressed_total 6063
telemt_desync_frames_bucket_total{bucket="1_2"} 1637
telemt_desync_frames_bucket_total{bucket="3_10"} 3492
telemt_desync_frames_bucket_total{bucket="gt_10"} 4011
telemt_pool_swap_total 31
telemt_pool_force_close_total 971
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 91
telemt_me_draining_writers_reap_progress_total 8567
telemt_me_writer_removed_unexpected_total 267
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 769
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 8076
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 852
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 119
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 7596
telemt_me_writer_teardown_success_total{mode="normal"} 8845
telemt_me_writer_teardown_noop_total 8568
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 17066
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 17258
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 17307
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 17413
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 17413
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 17413
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 17413
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 17413
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 17413
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 17413
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 17413
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 17413
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 17413
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.560063
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 17413
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 91
telemt_me_refill_failed_total 124
telemt_me_writer_restored_same_endpoint_total 269
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 690
telemt_user_connections_total{user="hello"} 1655316
telemt_user_connections_current{user="hello"} 2368
telemt_user_octets_from_client{user="hello"} 47897041320 (44.61 GB)
telemt_user_octets_to_client{user="hello"} 711135689144 (662.30 GB)
telemt_user_unique_ips_current{user="hello"} 1061
telemt_user_unique_ips_recent_window{user="hello"} 211
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 9891.2 (2h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 122646
telemt_connections_bad_total 1315
telemt_connections_current 506
telemt_connections_me_current 506
telemt_handshake_timeouts_total 3249
telemt_upstream_connect_attempt_total 4220
telemt_upstream_connect_success_total 4208
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 4219
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1745
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2409
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_reconnect_attempts_total 79
telemt_me_reconnect_success_total 47
telemt_me_reader_eof_total 47
telemt_me_idle_close_by_peer_total 47
telemt_me_route_drop_no_conn_total 34660
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 105747
telemt_me_endpoint_quarantine_total 71
telemt_me_single_endpoint_shadow_rotate_total 85
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
telemt_me_writers_active_current 46
telemt_desync_total 887
telemt_desync_full_logged_total 212
telemt_desync_suppressed_total 675
telemt_desync_frames_bucket_total{bucket="1_2"} 374
telemt_desync_frames_bucket_total{bucket="3_10"} 308
telemt_desync_frames_bucket_total{bucket="gt_10"} 205
telemt_pool_swap_total 10
telemt_pool_force_close_total 262
telemt_me_writer_close_signal_drop_total 12
telemt_me_draining_writers_reap_progress_total 3713
telemt_me_writer_removed_unexpected_total 47
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 231
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 3529
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 260
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 3451
telemt_me_writer_teardown_success_total{mode="normal"} 3760
telemt_me_writer_teardown_noop_total 3713
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 7389
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 7448
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 7463
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 7473
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 7473
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 7473
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 7473
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 7473
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 7473
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 7473
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 7473
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 7473
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 7473
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.531465
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 7473
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 12
telemt_me_refill_failed_total 2
telemt_me_writer_restored_same_endpoint_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 105600
telemt_user_connections_current{user="hello"} 506
telemt_user_octets_from_client{user="hello"} 2198176488 (2.05 GB)
telemt_user_octets_to_client{user="hello"} 65568757084 (61.07 GB)
telemt_user_unique_ips_current{user="hello"} 203
telemt_user_unique_ips_recent_window{user="hello"} 59
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 92089.0 (25h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6749949
telemt_connections_bad_total 681197
telemt_connections_current 2552
telemt_connections_me_current 2552
telemt_handshake_timeouts_total 194098
telemt_upstream_connect_attempt_total 34848
telemt_upstream_connect_success_total 34708
telemt_upstream_connect_fail_total 103
telemt_upstream_connect_attempts_per_request{bucket="1"} 34811
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17188
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17479
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 103
telemt_me_reconnect_attempts_total 1424
telemt_me_reconnect_success_total 728
telemt_me_reader_eof_total 704
telemt_me_idle_close_by_peer_total 704
telemt_me_route_drop_no_conn_total 2059101
telemt_me_route_drop_channel_closed_total 52
telemt_me_route_drop_queue_full_total 22
telemt_me_route_drop_queue_full_profile_total{profile="high"} 22
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5160031
telemt_me_endpoint_quarantine_total 615
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 704
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 28
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
telemt_me_writers_active_current 48
telemt_desync_total 19755
telemt_desync_full_logged_total 6595
telemt_desync_suppressed_total 13160
telemt_desync_frames_bucket_total{bucket="1_2"} 4806
telemt_desync_frames_bucket_total{bucket="3_10"} 7205
telemt_desync_frames_bucket_total{bucket="gt_10"} 7744
telemt_pool_swap_total 102
telemt_pool_force_close_total 2794
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 346
telemt_me_draining_writers_reap_progress_total 31312
telemt_me_writer_removed_unexpected_total 685
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2534
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 29472
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2709
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 85
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 28518
telemt_me_writer_teardown_success_total{mode="normal"} 32006
telemt_me_writer_teardown_noop_total 31314
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 62037
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 62877
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 63032
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 63232
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 63320
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 63320
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 63320
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 63320
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 63320
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 63320
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 63320
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 63320
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 63320
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.202513
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 63320
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 346
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 651
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 29
telemt_user_connections_total{user="hello"} 5135521
telemt_user_connections_current{user="hello"} 2552
telemt_user_octets_from_client{user="hello"} 103676171236 (96.56 GB)
telemt_user_octets_to_client{user="hello"} 2410121365912 (2.19 TB)
telemt_user_unique_ips_current{user="hello"} 950
telemt_user_unique_ips_recent_window{user="hello"} 282
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 92085.5 (25h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5756312
telemt_connections_bad_total 546138
telemt_connections_current 2349
telemt_connections_me_current 2349
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 162548
telemt_upstream_connect_attempt_total 51042
telemt_upstream_connect_success_total 50657
telemt_upstream_connect_fail_total 326
telemt_upstream_connect_attempts_per_request{bucket="1"} 50983
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30259
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19266
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 614
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 326
telemt_me_reconnect_attempts_total 5211
telemt_me_reconnect_success_total 1036
telemt_me_reader_eof_total 912
telemt_me_idle_close_by_peer_total 912
telemt_me_seq_mismatch_total 38
telemt_me_route_drop_no_conn_total 2111634
telemt_me_route_drop_channel_closed_total 188
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4524033
telemt_me_endpoint_quarantine_total 723
telemt_me_single_endpoint_outage_enter_total 27
telemt_me_single_endpoint_outage_exit_total 27
telemt_me_single_endpoint_outage_reconnect_attempt_total 27
telemt_me_single_endpoint_outage_reconnect_success_total 25
telemt_me_single_endpoint_quarantine_bypass_total 27
telemt_me_single_endpoint_shadow_rotate_total 698
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 30
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
telemt_desync_total 18397
telemt_desync_full_logged_total 6217
telemt_desync_suppressed_total 12180
telemt_desync_frames_bucket_total{bucket="1_2"} 4571
telemt_desync_frames_bucket_total{bucket="3_10"} 6718
telemt_desync_frames_bucket_total{bucket="gt_10"} 7108
telemt_pool_swap_total 100
telemt_pool_force_close_total 2749
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 353
telemt_me_draining_writers_reap_progress_total 30322
telemt_me_writer_removed_unexpected_total 923
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3041
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 28246
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2528
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 221
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 27573
telemt_me_writer_teardown_success_total{mode="normal"} 31287
telemt_me_writer_teardown_noop_total 30326
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 60089
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 61085
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 61380
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 61575
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 61613
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 61613
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 61613
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 61613
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 61613
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 61613
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 61613
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 61613
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 61613
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.352238
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 61613
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 353
telemt_me_refill_failed_total 241
telemt_me_writer_restored_same_endpoint_total 799
telemt_me_writer_restored_fallback_total 49
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 76
telemt_me_writer_removed_unexpected_minus_restored_total 75
telemt_user_connections_total{user="hello"} 4527628
telemt_user_connections_current{user="hello"} 2349
telemt_user_octets_from_client{user="hello"} 87070667805 (81.09 GB)
telemt_user_octets_to_client{user="hello"} 1935823559260 (1.76 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 982
telemt_user_unique_ips_recent_window{user="hello"} 266
```