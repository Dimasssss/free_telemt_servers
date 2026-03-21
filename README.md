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

Можете писать свой ник в коментарии к переводу

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-60
- Краткое описание тарифа: 4 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 26 марта
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

## rdp-onedash.ru (2 сервера)
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

# Server Metrics 2026-03-21 15:18:06 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 67319.3 (18h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2375222
telemt_connections_bad_total 117401
telemt_connections_current 1613
telemt_connections_me_current 1613
telemt_relay_adaptive_promotions_total 3
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 77418
telemt_upstream_connect_attempt_total 28761
telemt_upstream_connect_success_total 28636
telemt_upstream_connect_fail_total 82
telemt_upstream_connect_attempts_per_request{bucket="1"} 28718
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11913
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16635
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 32
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 56
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 82
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 98
telemt_me_reconnect_attempts_total 1647
telemt_me_reconnect_success_total 658
telemt_me_reader_eof_total 632
telemt_me_idle_close_by_peer_total 632
telemt_me_route_drop_no_conn_total 2073538
telemt_me_route_drop_channel_closed_total 631
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1904827
telemt_me_writer_pick_total{mode="p2c",result="full"} 26
telemt_me_endpoint_quarantine_total 472
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 524
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 22
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
telemt_desync_total 7394
telemt_desync_full_logged_total 2564
telemt_desync_suppressed_total 4830
telemt_desync_frames_bucket_total{bucket="1_2"} 1618
telemt_desync_frames_bucket_total{bucket="3_10"} 2814
telemt_desync_frames_bucket_total{bucket="gt_10"} 2962
telemt_pool_swap_total 72
telemt_pool_force_close_total 2186
telemt_pool_stale_pick_total 28
telemt_me_writer_close_signal_drop_total 499
telemt_me_draining_writers_reap_progress_total 22996
telemt_me_writer_removed_unexpected_total 610
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1973
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21417
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2070
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 116
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20810
telemt_me_writer_teardown_success_total{mode="normal"} 23390
telemt_me_writer_teardown_noop_total 23002
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 38525
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 39996
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 41291
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 43494
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 45287
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 46126
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 46364
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 46387
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 46391
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 46392
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 46392
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 46392
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 46392
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 218.679627
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 46392
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 499
telemt_me_refill_failed_total 54
telemt_me_writer_restored_same_endpoint_total 566
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 1906330
telemt_user_connections_current{user="hello"} 1613
telemt_user_octets_from_client{user="hello"} 26866808469 (25.02 GB)
telemt_user_octets_to_client{user="hello"} 469244898418 (437.02 GB)
telemt_user_msgs_from_client{user="hello"} 7227
telemt_user_msgs_to_client{user="hello"} 6949
telemt_user_unique_ips_current{user="hello"} 591
telemt_user_unique_ips_recent_window{user="hello"} 373
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 158.4 (0h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13607
telemt_connections_bad_total 1143
telemt_connections_current 3244
telemt_connections_me_current 3244
telemt_handshake_timeouts_total 363
telemt_upstream_connect_attempt_total 122
telemt_upstream_connect_success_total 119
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 121
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 68
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 51
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 1
telemt_me_reconnect_success_total 2
telemt_me_route_drop_no_conn_total 4382
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 11461
telemt_me_single_endpoint_shadow_rotate_total 6
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
telemt_desync_total 39
telemt_desync_full_logged_total 18
telemt_desync_suppressed_total 21
telemt_desync_frames_bucket_total{bucket="1_2"} 8
telemt_desync_frames_bucket_total{bucket="3_10"} 17
telemt_desync_frames_bucket_total{bucket="gt_10"} 14
telemt_me_draining_writers_reap_progress_total 36
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 36
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 36
telemt_me_writer_teardown_success_total{mode="normal"} 36
telemt_me_writer_teardown_noop_total 36
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 72
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 72
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 72
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 72
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 72
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 72
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 72
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 72
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 72
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 72
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 72
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 72
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 72
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.000420
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 72
telemt_user_connections_total{user="hello"} 11462
telemt_user_connections_current{user="hello"} 3244
telemt_user_octets_from_client{user="hello"} 115788672 (110.42 MB)
telemt_user_octets_to_client{user="hello"} 2035166192 (1.90 GB)
telemt_user_unique_ips_current{user="hello"} 1205
telemt_user_unique_ips_recent_window{user="hello"} 779
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 67317.2 (18h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4707856
telemt_connections_bad_total 413874
telemt_connections_current 5763
telemt_connections_me_current 5763
telemt_handshake_timeouts_total 170712
telemt_upstream_connect_attempt_total 24982
telemt_upstream_connect_success_total 24929
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 24934
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11239
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13585
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 99
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1146
telemt_me_reconnect_success_total 573
telemt_me_reader_eof_total 577
telemt_me_idle_close_by_peer_total 577
telemt_me_route_drop_no_conn_total 2618367
telemt_me_route_drop_channel_closed_total 45
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3858356
telemt_me_endpoint_quarantine_total 424
telemt_me_single_endpoint_outage_enter_total 4
telemt_me_single_endpoint_outage_exit_total 4
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 509
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 18
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
telemt_desync_total 15786
telemt_desync_full_logged_total 5330
telemt_desync_suppressed_total 10456
telemt_desync_frames_bucket_total{bucket="1_2"} 3373
telemt_desync_frames_bucket_total{bucket="3_10"} 6214
telemt_desync_frames_bucket_total{bucket="gt_10"} 6199
telemt_pool_swap_total 71
telemt_pool_force_close_total 2298
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 362
telemt_me_draining_writers_reap_progress_total 22654
telemt_me_writer_removed_unexpected_total 558
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1982
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21012
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 32
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2102
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 196
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20356
telemt_me_writer_teardown_success_total{mode="normal"} 22994
telemt_me_writer_teardown_noop_total 22686
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 41998
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 43219
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 43897
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 44765
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 45284
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 45574
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 45679
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 45680
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 45680
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 45680
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 45680
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 45680
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 45680
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 77.811795
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 45680
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 362
telemt_me_refill_failed_total 30
telemt_me_writer_restored_same_endpoint_total 515
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 38
telemt_user_connections_total{user="hello"} 3853656
telemt_user_connections_current{user="hello"} 5763
telemt_user_octets_from_client{user="hello"} 62416440264 (58.13 GB)
telemt_user_octets_to_client{user="hello"} 1275028793464 (1.16 TB)
telemt_user_unique_ips_current{user="hello"} 2136
telemt_user_unique_ips_recent_window{user="hello"} 641
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 67319.0 (18h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3836531
telemt_connections_bad_total 415017
telemt_connections_current 3701
telemt_connections_me_current 3701
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 137920
telemt_upstream_connect_attempt_total 29414
telemt_upstream_connect_success_total 29133
telemt_upstream_connect_fail_total 139
telemt_upstream_connect_attempts_per_request{bucket="1"} 29272
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15001
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13621
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 484
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 139
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 76
telemt_me_reconnect_attempts_total 1377
telemt_me_reconnect_success_total 598
telemt_me_reader_eof_total 558
telemt_me_idle_close_by_peer_total 558
telemt_me_route_drop_no_conn_total 1206034
telemt_me_route_drop_channel_closed_total 98
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2808463
telemt_me_endpoint_quarantine_total 435
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 511
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 22
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
telemt_desync_total 13066
telemt_desync_full_logged_total 4399
telemt_desync_suppressed_total 8667
telemt_desync_frames_bucket_total{bucket="1_2"} 3272
telemt_desync_frames_bucket_total{bucket="3_10"} 5049
telemt_desync_frames_bucket_total{bucket="gt_10"} 4745
telemt_pool_swap_total 73
telemt_pool_force_close_total 2106
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 208
telemt_me_draining_writers_reap_progress_total 21876
telemt_me_writer_removed_unexpected_total 542
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1883
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20537
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1960
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 146
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19770
telemt_me_writer_teardown_success_total{mode="normal"} 22420
telemt_me_writer_teardown_noop_total 21877
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 42605
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 43511
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 43769
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 44057
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 44217
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 44295
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 44297
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 44297
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 44297
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 44297
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 44297
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 44297
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 44297
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 20.486693
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 44297
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 208
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 502
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 32
telemt_user_connections_total{user="hello"} 2808320
telemt_user_connections_current{user="hello"} 3701
telemt_user_octets_from_client{user="hello"} 53054666517 (49.41 GB)
telemt_user_octets_to_client{user="hello"} 1309967789783 (1.19 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1466
telemt_user_unique_ips_recent_window{user="hello"} 528
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 67282.6 (18h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3765509
telemt_connections_bad_total 391740
telemt_connections_current 3831
telemt_connections_me_current 3831
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 113066
telemt_upstream_connect_attempt_total 34650
telemt_upstream_connect_success_total 34415
telemt_upstream_connect_fail_total 133
telemt_upstream_connect_attempts_per_request{bucket="1"} 34548
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18308
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14966
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 289
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 852
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 133
telemt_me_keepalive_timeout_total 50
telemt_me_reconnect_attempts_total 1382
telemt_me_reconnect_success_total 650
telemt_me_reader_eof_total 590
telemt_me_idle_close_by_peer_total 590
telemt_me_route_drop_no_conn_total 1311000
telemt_me_route_drop_channel_closed_total 36
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2792527
telemt_me_endpoint_quarantine_total 482
telemt_me_single_endpoint_outage_enter_total 6
telemt_me_single_endpoint_outage_exit_total 6
telemt_me_single_endpoint_outage_reconnect_attempt_total 6
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 6
telemt_me_single_endpoint_shadow_rotate_total 503
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 21
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
telemt_desync_total 12850
telemt_desync_full_logged_total 4285
telemt_desync_suppressed_total 8565
telemt_desync_frames_bucket_total{bucket="1_2"} 3215
telemt_desync_frames_bucket_total{bucket="3_10"} 4826
telemt_desync_frames_bucket_total{bucket="gt_10"} 4809
telemt_pool_swap_total 71
telemt_pool_force_close_total 2035
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 232
telemt_me_draining_writers_reap_progress_total 23311
telemt_me_writer_removed_unexpected_total 562
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1971
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21938
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1856
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 179
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21276
telemt_me_writer_teardown_success_total{mode="normal"} 23909
telemt_me_writer_teardown_noop_total 23316
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 45943
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 46689
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 46899
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 47114
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 47214
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 47225
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 47225
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 47225
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 47225
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 47225
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 47225
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 47225
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 47225
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 11.507130
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 47225
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 232
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 560
telemt_me_writer_restored_fallback_total 3
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_user_connections_total{user="hello"} 2796414
telemt_user_connections_current{user="hello"} 3831
telemt_user_octets_from_client{user="hello"} 59522278121 (55.43 GB)
telemt_user_octets_to_client{user="hello"} 1297098125232 (1.18 TB)
telemt_user_msgs_from_client{user="hello"} 42436
telemt_user_msgs_to_client{user="hello"} 111361
telemt_user_unique_ips_current{user="hello"} 1492
telemt_user_unique_ips_recent_window{user="hello"} 533
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 67336.5 (18h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12933055
telemt_connections_bad_total 841346
telemt_connections_current 5680
telemt_connections_me_current 5680
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 393994
telemt_upstream_connect_attempt_total 115812
telemt_upstream_connect_success_total 105925
telemt_upstream_connect_fail_total 8851
telemt_upstream_connect_attempts_per_request{bucket="1"} 114776
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 74283
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25490
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 792
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5360
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8851
telemt_me_keepalive_timeout_total 102
telemt_me_reconnect_attempts_total 3856
telemt_me_reconnect_success_total 1397
telemt_me_reader_eof_total 976
telemt_me_idle_close_by_peer_total 975
telemt_me_route_drop_no_conn_total 25031995
telemt_me_route_drop_channel_closed_total 84
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10628521
telemt_me_endpoint_quarantine_total 518
telemt_me_single_endpoint_outage_enter_total 77
telemt_me_single_endpoint_outage_exit_total 77
telemt_me_single_endpoint_outage_reconnect_attempt_total 173
telemt_me_single_endpoint_outage_reconnect_success_total 37
telemt_me_single_endpoint_quarantine_bypass_total 173
telemt_me_single_endpoint_shadow_rotate_total 526
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 44
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
telemt_desync_total 18820
telemt_desync_full_logged_total 5902
telemt_desync_suppressed_total 12918
telemt_desync_frames_bucket_total{bucket="1_2"} 4077
telemt_desync_frames_bucket_total{bucket="3_10"} 8277
telemt_desync_frames_bucket_total{bucket="gt_10"} 6466
telemt_pool_swap_total 68
telemt_pool_force_close_total 2213
telemt_pool_stale_pick_total 5
telemt_me_writer_close_signal_drop_total 482
telemt_me_draining_writers_reap_progress_total 21609
telemt_me_writer_removed_unexpected_total 1337
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2855
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19882
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1854
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 359
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19396
telemt_me_writer_teardown_success_total{mode="normal"} 22737
telemt_me_writer_teardown_noop_total 21621
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 40094
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 41595
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 42493
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 43515
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 44104
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 44306
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 44339
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 44341
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 44344
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 44349
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 44349
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 44353
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 44358
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 170.623642
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 44358
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 482
telemt_me_refill_failed_total 87
telemt_me_writer_restored_same_endpoint_total 974
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 113
telemt_me_writer_removed_unexpected_minus_restored_total 353
telemt_user_connections_total{user="hello"} 10704285
telemt_user_connections_current{user="hello"} 5680
telemt_user_octets_from_client{user="hello"} 76280750853 (71.04 GB)
telemt_user_octets_to_client{user="hello"} 794278134581 (739.73 GB)
telemt_user_msgs_from_client{user="hello"} 231133
telemt_user_msgs_to_client{user="hello"} 542131
telemt_user_unique_ips_current{user="hello"} 2051
telemt_user_unique_ips_recent_window{user="hello"} 1017
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 67289.3 (18h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3779910
telemt_connections_bad_total 421081
telemt_connections_current 4040
telemt_connections_me_current 4040
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 81883
telemt_upstream_connect_attempt_total 28327
telemt_upstream_connect_success_total 28017
telemt_upstream_connect_fail_total 266
telemt_upstream_connect_attempts_per_request{bucket="1"} 28283
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13367
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14576
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 73
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 266
telemt_me_reconnect_attempts_total 2681
telemt_me_reconnect_success_total 976
telemt_me_reader_eof_total 970
telemt_me_idle_close_by_peer_total 970
telemt_me_route_drop_no_conn_total 1593553
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 34
telemt_me_route_drop_queue_full_profile_total{profile="high"} 34
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2911500
telemt_me_endpoint_quarantine_total 415
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 504
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 25
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
telemt_desync_total 13785
telemt_desync_full_logged_total 4803
telemt_desync_suppressed_total 8982
telemt_desync_frames_bucket_total{bucket="1_2"} 2682
telemt_desync_frames_bucket_total{bucket="3_10"} 5449
telemt_desync_frames_bucket_total{bucket="gt_10"} 5654
telemt_pool_swap_total 67
telemt_pool_force_close_total 1948
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 196
telemt_me_draining_writers_reap_progress_total 23795
telemt_me_writer_removed_unexpected_total 941
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2338
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 22430
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1693
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 255
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21847
telemt_me_writer_teardown_success_total{mode="normal"} 24768
telemt_me_writer_teardown_noop_total 23796
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 47955
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 48347
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 48521
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 48564
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 48564
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 48564
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 48564
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 48564
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 48564
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 48564
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 48564
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 48564
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 48564
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.381178
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 48564
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 196
telemt_me_refill_failed_total 93
telemt_me_writer_restored_same_endpoint_total 837
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 94
telemt_user_connections_total{user="hello"} 2895078
telemt_user_connections_current{user="hello"} 4040
telemt_user_octets_from_client{user="hello"} 75850714800 (70.64 GB)
telemt_user_octets_to_client{user="hello"} 1206965562826 (1.10 TB)
telemt_user_msgs_from_client{user="hello"} 7339
telemt_user_msgs_to_client{user="hello"} 11522
telemt_user_unique_ips_current{user="hello"} 1625
telemt_user_unique_ips_recent_window{user="hello"} 527
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 4125.0 (1h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 675041
telemt_connections_bad_total 16664
telemt_connections_current 3290
telemt_connections_me_current 3290
telemt_handshake_timeouts_total 331817
telemt_upstream_connect_attempt_total 1557
telemt_upstream_connect_success_total 1524
telemt_upstream_connect_fail_total 27
telemt_upstream_connect_attempts_per_request{bucket="1"} 1551
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 693
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 816
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 27
telemt_me_reconnect_attempts_total 205
telemt_me_reconnect_success_total 75
telemt_me_reader_eof_total 66
telemt_me_idle_close_by_peer_total 66
telemt_me_route_drop_no_conn_total 334765
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 307095
telemt_me_endpoint_quarantine_total 17
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 34
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
telemt_desync_total 1432
telemt_desync_full_logged_total 464
telemt_desync_suppressed_total 968
telemt_desync_frames_bucket_total{bucket="1_2"} 233
telemt_desync_frames_bucket_total{bucket="3_10"} 552
telemt_desync_frames_bucket_total{bucket="gt_10"} 647
telemt_pool_swap_total 3
telemt_pool_force_close_total 116
telemt_me_writer_close_signal_drop_total 9
telemt_me_draining_writers_reap_progress_total 1268
telemt_me_writer_removed_unexpected_total 67
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 139
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 1196
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 78
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 38
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 1152
telemt_me_writer_teardown_success_total{mode="normal"} 1335
telemt_me_writer_teardown_noop_total 1268
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 2544
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 2561
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 2585
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 2603
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 2603
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 2603
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 2603
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 2603
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 2603
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 2603
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 2603
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 2603
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 2603
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.500120
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 2603
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 9
telemt_me_refill_failed_total 8
telemt_me_writer_restored_same_endpoint_total 66
telemt_me_async_recovery_trigger_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 306659
telemt_user_connections_current{user="hello"} 3290
telemt_user_octets_from_client{user="hello"} 9214879592 (8.58 GB)
telemt_user_octets_to_client{user="hello"} 107386832920 (100.01 GB)
telemt_user_unique_ips_current{user="hello"} 1363
telemt_user_unique_ips_recent_window{user="hello"} 497
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 65275.2 (18h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1205840
telemt_connections_bad_total 138158
telemt_connections_current 827
telemt_connections_me_current 827
telemt_handshake_timeouts_total 426765
telemt_upstream_connect_attempt_total 30634
telemt_upstream_connect_success_total 30627
telemt_upstream_connect_attempts_per_request{bucket="1"} 30627
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12552
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17976
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 99
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 1308
telemt_me_reconnect_success_total 541
telemt_me_reader_eof_total 539
telemt_me_idle_close_by_peer_total 539
telemt_me_route_drop_no_conn_total 263402
telemt_me_route_drop_channel_closed_total 24
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 565713
telemt_me_endpoint_quarantine_total 586
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 549
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 10
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
telemt_desync_total 3570
telemt_desync_full_logged_total 1301
telemt_desync_suppressed_total 2269
telemt_desync_frames_bucket_total{bucket="1_2"} 658
telemt_desync_frames_bucket_total{bucket="3_10"} 1281
telemt_desync_frames_bucket_total{bucket="gt_10"} 1631
telemt_pool_swap_total 71
telemt_pool_force_close_total 1651
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 111
telemt_me_draining_writers_reap_progress_total 27459
telemt_me_writer_removed_unexpected_total 512
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2059
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 25925
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1628
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 23
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 25808
telemt_me_writer_teardown_success_total{mode="normal"} 27984
telemt_me_writer_teardown_noop_total 27459
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 54782
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 55237
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 55384
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 55435
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 55443
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 55443
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 55443
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 55443
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 55443
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 55443
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 55443
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 55443
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 55443
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.068202
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 55443
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 111
telemt_me_refill_failed_total 40
telemt_me_writer_restored_same_endpoint_total 450
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 57
telemt_user_connections_total{user="hello"} 565381
telemt_user_connections_current{user="hello"} 827
telemt_user_octets_from_client{user="hello"} 11607450907 (10.81 GB)
telemt_user_octets_to_client{user="hello"} 215567955469 (200.76 GB)
telemt_user_msgs_from_client{user="hello"} 804
telemt_user_msgs_to_client{user="hello"} 1943
telemt_user_unique_ips_current{user="hello"} 322
telemt_user_unique_ips_recent_window{user="hello"} 134
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 67293.6 (18h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4145445
telemt_connections_bad_total 376227
telemt_connections_current 4821
telemt_connections_me_current 4821
telemt_handshake_timeouts_total 136840
telemt_upstream_connect_attempt_total 26832
telemt_upstream_connect_success_total 26720
telemt_upstream_connect_fail_total 77
telemt_upstream_connect_attempts_per_request{bucket="1"} 26797
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13245
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13438
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 77
telemt_me_reconnect_attempts_total 1144
telemt_me_reconnect_success_total 611
telemt_me_reader_eof_total 577
telemt_me_idle_close_by_peer_total 577
telemt_me_route_drop_no_conn_total 1260627
telemt_me_route_drop_channel_closed_total 34
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3300517
telemt_me_endpoint_quarantine_total 492
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 514
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 26
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
telemt_desync_total 12921
telemt_desync_full_logged_total 4266
telemt_desync_suppressed_total 8655
telemt_desync_frames_bucket_total{bucket="1_2"} 3052
telemt_desync_frames_bucket_total{bucket="3_10"} 4816
telemt_desync_frames_bucket_total{bucket="gt_10"} 5053
telemt_pool_swap_total 74
telemt_pool_force_close_total 1939
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 222
telemt_me_draining_writers_reap_progress_total 24055
telemt_me_writer_removed_unexpected_total 566
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1920
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 22702
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1896
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 43
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 22116
telemt_me_writer_teardown_success_total{mode="normal"} 24622
telemt_me_writer_teardown_noop_total 24055
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 47944
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 48425
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 48515
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 48633
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 48677
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 48677
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 48677
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 48677
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 48677
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 48677
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 48677
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 48677
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 48677
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.694852
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 48677
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 222
telemt_me_refill_failed_total 27
telemt_me_writer_restored_same_endpoint_total 542
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 19
telemt_user_connections_total{user="hello"} 3292204
telemt_user_connections_current{user="hello"} 4821
telemt_user_octets_from_client{user="hello"} 67523554036 (62.89 GB)
telemt_user_octets_to_client{user="hello"} 1551658486928 (1.41 TB)
telemt_user_unique_ips_current{user="hello"} 1755
telemt_user_unique_ips_recent_window{user="hello"} 624
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 67290.5 (18h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3693079
telemt_connections_bad_total 326838
telemt_connections_current 3791
telemt_connections_me_current 3791
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 112291
telemt_upstream_connect_attempt_total 43330
telemt_upstream_connect_success_total 43038
telemt_upstream_connect_fail_total 241
telemt_upstream_connect_attempts_per_request{bucket="1"} 43279
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26603
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15318
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 600
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 241
telemt_me_reconnect_attempts_total 3828
telemt_me_reconnect_success_total 836
telemt_me_reader_eof_total 733
telemt_me_idle_close_by_peer_total 733
telemt_me_seq_mismatch_total 31
telemt_me_route_drop_no_conn_total 1339504
telemt_me_route_drop_channel_closed_total 100
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2969040
telemt_me_endpoint_quarantine_total 559
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 19
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 19
telemt_me_single_endpoint_shadow_rotate_total 511
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 22
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
telemt_me_writers_active_current 49
telemt_desync_total 11586
telemt_desync_full_logged_total 3940
telemt_desync_suppressed_total 7646
telemt_desync_frames_bucket_total{bucket="1_2"} 2886
telemt_desync_frames_bucket_total{bucket="3_10"} 4312
telemt_desync_frames_bucket_total{bucket="gt_10"} 4388
telemt_pool_swap_total 72
telemt_pool_force_close_total 1878
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 209
telemt_me_draining_writers_reap_progress_total 23491
telemt_me_writer_removed_unexpected_total 745
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2281
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21987
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1724
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 154
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21613
telemt_me_writer_teardown_success_total{mode="normal"} 24268
telemt_me_writer_teardown_noop_total 23492
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 46902
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 47439
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 47626
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 47751
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 47760
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 47760
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 47760
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 47760
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 47760
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 47760
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 47760
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 47760
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 47760
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.960463
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 47760
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 209
telemt_me_refill_failed_total 170
telemt_me_writer_restored_same_endpoint_total 648
telemt_me_writer_restored_fallback_total 40
telemt_me_async_recovery_trigger_total 57
telemt_me_writer_removed_unexpected_minus_restored_total 57
telemt_user_connections_total{user="hello"} 2977596
telemt_user_connections_current{user="hello"} 3791
telemt_user_octets_from_client{user="hello"} 53538665057 (49.86 GB)
telemt_user_octets_to_client{user="hello"} 1276823103080 (1.16 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1556
telemt_user_unique_ips_recent_window{user="hello"} 550
```