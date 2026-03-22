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

# Server Metrics 2026-03-22 02:51:13 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 20690.7 (5h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 301701
telemt_connections_bad_total 20493
telemt_connections_current 818
telemt_connections_me_current 818
telemt_handshake_timeouts_total 17564
telemt_upstream_connect_attempt_total 8660
telemt_upstream_connect_success_total 8659
telemt_upstream_connect_attempts_per_request{bucket="1"} 8659
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3097
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5543
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_me_reconnect_attempts_total 262
telemt_me_reconnect_success_total 138
telemt_me_reader_eof_total 133
telemt_me_idle_close_by_peer_total 133
telemt_me_route_drop_no_conn_total 57785
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 247746
telemt_me_endpoint_quarantine_total 169
telemt_me_single_endpoint_shadow_rotate_total 172
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
telemt_me_writers_active_current 50
telemt_desync_total 2197
telemt_desync_full_logged_total 598
telemt_desync_suppressed_total 1599
telemt_desync_frames_bucket_total{bucket="1_2"} 734
telemt_desync_frames_bucket_total{bucket="3_10"} 817
telemt_desync_frames_bucket_total{bucket="gt_10"} 646
telemt_pool_swap_total 22
telemt_pool_force_close_total 575
telemt_me_writer_close_signal_drop_total 39
telemt_me_draining_writers_reap_progress_total 7794
telemt_me_writer_removed_unexpected_total 133
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 531
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 7386
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 570
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 7219
telemt_me_writer_teardown_success_total{mode="normal"} 7917
telemt_me_writer_teardown_noop_total 7795
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 15248
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 15523
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 15619
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 15678
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 15710
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 15712
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 15712
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 15712
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 15712
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 15712
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 15712
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 15712
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 15712
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.909450
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 15712
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 39
telemt_me_refill_failed_total 7
telemt_me_writer_restored_same_endpoint_total 124
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 247270
telemt_user_connections_current{user="hello"} 818
telemt_user_octets_from_client{user="hello"} 2815418536 (2.62 GB)
telemt_user_octets_to_client{user="hello"} 91020774452 (84.77 GB)
telemt_user_unique_ips_current{user="hello"} 379
telemt_user_unique_ips_recent_window{user="hello"} 107
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 34057.0 (9h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 797587
telemt_connections_bad_total 49608
telemt_connections_current 635
telemt_connections_me_current 635
telemt_handshake_timeouts_total 29476
telemt_upstream_connect_attempt_total 15839
telemt_upstream_connect_success_total 15590
telemt_upstream_connect_fail_total 226
telemt_upstream_connect_attempts_per_request{bucket="1"} 15816
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6858
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8687
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 45
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 226
telemt_me_reconnect_attempts_total 1359
telemt_me_reconnect_success_total 497
telemt_me_reader_eof_total 437
telemt_me_idle_close_by_peer_total 437
telemt_me_route_drop_no_conn_total 342054
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 630407
telemt_me_endpoint_quarantine_total 320
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 19
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 19
telemt_me_single_endpoint_shadow_rotate_total 275
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 21
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
telemt_me_writers_active_current 45
telemt_desync_total 2723
telemt_desync_full_logged_total 1566
telemt_desync_suppressed_total 1157
telemt_desync_frames_bucket_total{bucket="1_2"} 580
telemt_desync_frames_bucket_total{bucket="3_10"} 1035
telemt_desync_frames_bucket_total{bucket="gt_10"} 1108
telemt_pool_swap_total 36
telemt_pool_force_close_total 983
telemt_me_writer_close_signal_drop_total 66
telemt_me_draining_writers_reap_progress_total 14035
telemt_me_writer_removed_unexpected_total 414
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1175
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 13284
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 961
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 22
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13052
telemt_me_writer_teardown_success_total{mode="normal"} 14459
telemt_me_writer_teardown_noop_total 14035
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 27966
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 28273
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 28388
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 28480
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 28492
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 28494
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 28494
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 28494
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 28494
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 28494
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 28494
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 28494
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 28494
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.746535
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 28494
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 66
telemt_me_refill_failed_total 45
telemt_me_writer_restored_same_endpoint_total 364
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 38
telemt_user_connections_total{user="hello"} 629502
telemt_user_connections_current{user="hello"} 635
telemt_user_octets_from_client{user="hello"} 10264270344 (9.56 GB)
telemt_user_octets_to_client{user="hello"} 224177617868 (208.78 GB)
telemt_user_unique_ips_current{user="hello"} 445
telemt_user_unique_ips_recent_window{user="hello"} 106
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 108917.0 (30h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7764175
telemt_connections_bad_total 631340
telemt_connections_current 2017
telemt_connections_me_current 2017
telemt_handshake_timeouts_total 255052
telemt_upstream_connect_attempt_total 40405
telemt_upstream_connect_success_total 40331
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 40338
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18247
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21908
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 170
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1578
telemt_me_reconnect_success_total 817
telemt_me_reader_eof_total 826
telemt_me_idle_close_by_peer_total 826
telemt_me_route_drop_no_conn_total 4538400
telemt_me_route_drop_channel_closed_total 66
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6280328
telemt_me_endpoint_quarantine_total 697
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 814
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
telemt_me_writers_active_current 47
telemt_desync_total 26498
telemt_desync_full_logged_total 8769
telemt_desync_suppressed_total 17729
telemt_desync_frames_bucket_total{bucket="1_2"} 5711
telemt_desync_frames_bucket_total{bucket="3_10"} 10355
telemt_desync_frames_bucket_total{bucket="gt_10"} 10432
telemt_pool_swap_total 117
telemt_pool_force_close_total 3891
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 603
telemt_me_draining_writers_reap_progress_total 36876
telemt_me_writer_removed_unexpected_total 795
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3071
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 34134
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3652
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 239
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 32985
telemt_me_writer_teardown_success_total{mode="normal"} 37205
telemt_me_writer_teardown_noop_total 36920
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 67854
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 69716
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 70723
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 72249
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 73269
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 73824
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 74114
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 74125
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 74125
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 74125
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 74125
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 74125
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 74125
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 159.877163
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 74125
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 603
telemt_me_refill_failed_total 40
telemt_me_writer_restored_same_endpoint_total 727
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 63
telemt_user_connections_total{user="hello"} 6272450
telemt_user_connections_current{user="hello"} 2017
telemt_user_octets_from_client{user="hello"} 106419116292 (99.11 GB)
telemt_user_octets_to_client{user="hello"} 2087574820456 (1.90 TB)
telemt_user_unique_ips_current{user="hello"} 999
telemt_user_unique_ips_recent_window{user="hello"} 188
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 108918.3 (30h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6410036
telemt_connections_bad_total 587605
telemt_connections_current 1563
telemt_connections_me_current 1563
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 212200
telemt_upstream_connect_attempt_total 44441
telemt_upstream_connect_success_total 44053
telemt_upstream_connect_fail_total 191
telemt_upstream_connect_attempts_per_request{bucket="1"} 44244
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21854
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21609
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 557
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 191
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 1943
telemt_me_reconnect_success_total 873
telemt_me_reader_eof_total 845
telemt_me_idle_close_by_peer_total 845
telemt_me_route_drop_no_conn_total 2259517
telemt_me_route_drop_channel_closed_total 263
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4788626
telemt_me_endpoint_quarantine_total 679
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 836
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 29
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
telemt_desync_total 22614
telemt_desync_full_logged_total 7702
telemt_desync_suppressed_total 14912
telemt_desync_frames_bucket_total{bucket="1_2"} 5440
telemt_desync_frames_bucket_total{bucket="3_10"} 8778
telemt_desync_frames_bucket_total{bucket="gt_10"} 8396
telemt_pool_swap_total 118
telemt_pool_force_close_total 3518
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 361
telemt_me_draining_writers_reap_progress_total 35410
telemt_me_writer_removed_unexpected_total 830
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2949
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 33228
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3305
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 213
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 31892
telemt_me_writer_teardown_success_total{mode="normal"} 36177
telemt_me_writer_teardown_noop_total 35416
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 68291
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 69829
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 70400
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 70977
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 71388
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 71573
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 71593
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 71593
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 71593
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 71593
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 71593
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 71593
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 71593
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 48.308023
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 71593
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 361
telemt_me_refill_failed_total 57
telemt_me_writer_restored_same_endpoint_total 764
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 58
telemt_user_connections_total{user="hello"} 4710775
telemt_user_connections_current{user="hello"} 1563
telemt_user_octets_from_client{user="hello"} 140482496753 (130.83 GB)
telemt_user_octets_to_client{user="hello"} 2223527949527 (2.02 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 755
telemt_user_unique_ips_recent_window{user="hello"} 156
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 108882.5 (30h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6287111
telemt_connections_bad_total 548529
telemt_connections_current 1547
telemt_connections_me_current 1547
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 203626
telemt_upstream_connect_attempt_total 50549
telemt_upstream_connect_success_total 50177
telemt_upstream_connect_fail_total 136
telemt_upstream_connect_attempts_per_request{bucket="1"} 50313
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25631
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22993
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 480
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1073
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 136
telemt_me_keepalive_timeout_total 58
telemt_me_reconnect_attempts_total 2051
telemt_me_reconnect_success_total 910
telemt_me_reader_eof_total 855
telemt_me_idle_close_by_peer_total 855
telemt_me_route_drop_no_conn_total 2152831
telemt_me_route_drop_channel_closed_total 121
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4677197
telemt_me_endpoint_quarantine_total 758
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 812
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 40
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
telemt_desync_total 22541
telemt_desync_full_logged_total 7581
telemt_desync_suppressed_total 14960
telemt_desync_frames_bucket_total{bucket="1_2"} 5502
telemt_desync_frames_bucket_total{bucket="3_10"} 8638
telemt_desync_frames_bucket_total{bucket="gt_10"} 8401
telemt_pool_swap_total 117
telemt_pool_force_close_total 3403
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 386
telemt_me_draining_writers_reap_progress_total 36533
telemt_me_writer_removed_unexpected_total 827
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3025
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 34349
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 12
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3188
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 215
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 33130
telemt_me_writer_teardown_success_total{mode="normal"} 37374
telemt_me_writer_teardown_noop_total 36545
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 71309
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 72707
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 73168
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 73659
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 73874
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 73901
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 73919
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 73919
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 73919
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 73919
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 73919
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 73919
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 73919
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 27.050418
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 73919
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 386
telemt_me_refill_failed_total 63
telemt_me_writer_restored_same_endpoint_total 789
telemt_me_writer_restored_fallback_total 5
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 33
telemt_user_connections_total{user="hello"} 4672799
telemt_user_connections_current{user="hello"} 1547
telemt_user_octets_from_client{user="hello"} 133813380103 (124.62 GB)
telemt_user_octets_to_client{user="hello"} 2141390295139 (1.95 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 760
telemt_user_unique_ips_recent_window{user="hello"} 177
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 108922.2 (30h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20438371
telemt_connections_bad_total 1629349
telemt_connections_current 2385
telemt_connections_me_current 2385
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 608932
telemt_upstream_connect_attempt_total 199459
telemt_upstream_connect_success_total 181363
telemt_upstream_connect_fail_total 16338
telemt_upstream_connect_attempts_per_request{bucket="1"} 197701
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 128330
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 42883
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1221
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8929
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16338
telemt_me_keepalive_timeout_total 398
telemt_me_reconnect_attempts_total 64902
telemt_me_reconnect_success_total 2329
telemt_me_reader_eof_total 1459
telemt_me_idle_close_by_peer_total 1458
telemt_me_route_drop_no_conn_total 39512508
telemt_me_route_drop_channel_closed_total 124
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 16513202
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 5
telemt_me_endpoint_quarantine_total 855
telemt_me_single_endpoint_outage_enter_total 135
telemt_me_single_endpoint_outage_exit_total 135
telemt_me_single_endpoint_outage_reconnect_attempt_total 285
telemt_me_single_endpoint_outage_reconnect_success_total 70
telemt_me_single_endpoint_quarantine_bypass_total 285
telemt_me_single_endpoint_shadow_rotate_total 851
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 64
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
telemt_desync_total 31978
telemt_desync_full_logged_total 9597
telemt_desync_suppressed_total 22381
telemt_desync_frames_bucket_total{bucket="1_2"} 6929
telemt_desync_frames_bucket_total{bucket="3_10"} 14194
telemt_desync_frames_bucket_total{bucket="gt_10"} 10855
telemt_pool_swap_total 112
telemt_pool_force_close_total 3626
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 794
telemt_me_draining_writers_reap_progress_total 34156
telemt_me_writer_removed_unexpected_total 2157
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4607
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 31447
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 23
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3103
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 523
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 30530
telemt_me_writer_teardown_success_total{mode="normal"} 36054
telemt_me_writer_teardown_noop_total 34182
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 63464
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 65931
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 67204
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 68849
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 69792
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 70134
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 70217
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 70219
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 70222
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 70227
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 70227
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 70231
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 70236
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 214.681239
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 70236
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 794
telemt_me_refill_failed_total 3802
telemt_me_writer_restored_same_endpoint_total 1597
telemt_me_writer_restored_fallback_total 21
telemt_me_no_writer_failfast_total 666
telemt_me_async_recovery_trigger_total 14678
telemt_me_writer_removed_unexpected_minus_restored_total 539
telemt_user_connections_total{user="hello"} 16646368
telemt_user_connections_current{user="hello"} 2385
telemt_user_octets_from_client{user="hello"} 220578877844 (205.43 GB)
telemt_user_octets_to_client{user="hello"} 1205387860221 (1.10 TB)
telemt_user_msgs_from_client{user="hello"} 395497
telemt_user_msgs_to_client{user="hello"} 785476
telemt_user_unique_ips_current{user="hello"} 1081
telemt_user_unique_ips_recent_window{user="hello"} 259
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 108889.2 (30h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6040874
telemt_connections_bad_total 569477
telemt_connections_current 1551
telemt_connections_me_current 1551
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 126936
telemt_upstream_connect_attempt_total 59174
telemt_upstream_connect_success_total 58495
telemt_upstream_connect_fail_total 582
telemt_upstream_connect_attempts_per_request{bucket="1"} 59077
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34165
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23979
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 350
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 582
telemt_me_reconnect_attempts_total 69653
telemt_me_reconnect_success_total 1789
telemt_me_reader_eof_total 1568
telemt_me_idle_close_by_peer_total 1567
telemt_me_route_drop_no_conn_total 2391312
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 39
telemt_me_route_drop_queue_full_profile_total{profile="high"} 39
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4708655
telemt_me_endpoint_quarantine_total 736
telemt_me_single_endpoint_outage_enter_total 23
telemt_me_single_endpoint_outage_exit_total 23
telemt_me_single_endpoint_outage_reconnect_attempt_total 24
telemt_me_single_endpoint_outage_reconnect_success_total 23
telemt_me_single_endpoint_quarantine_bypass_total 24
telemt_me_single_endpoint_shadow_rotate_total 824
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
telemt_me_writers_active_current 45
telemt_desync_total 23406
telemt_desync_full_logged_total 8246
telemt_desync_suppressed_total 15160
telemt_desync_frames_bucket_total{bucket="1_2"} 4469
telemt_desync_frames_bucket_total{bucket="3_10"} 9061
telemt_desync_frames_bucket_total{bucket="gt_10"} 9876
telemt_pool_swap_total 112
telemt_pool_force_close_total 3223
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 395
telemt_me_draining_writers_reap_progress_total 38363
telemt_me_writer_removed_unexpected_total 1606
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3928
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 36072
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2822
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 401
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 35140
telemt_me_writer_teardown_success_total{mode="normal"} 40000
telemt_me_writer_teardown_noop_total 38364
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 77106
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 77933
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 78212
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 78332
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 78361
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 78364
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 78364
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 78364
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 78364
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 78364
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 78364
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 78364
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 78364
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.126222
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 78364
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 395
telemt_me_refill_failed_total 4206
telemt_me_writer_restored_same_endpoint_total 1500
telemt_me_writer_restored_fallback_total 34
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7305
telemt_me_writer_removed_unexpected_minus_restored_total 72
telemt_user_connections_total{user="hello"} 4701457
telemt_user_connections_current{user="hello"} 1551
telemt_user_octets_from_client{user="hello"} 124719825544 (116.15 GB)
telemt_user_octets_to_client{user="hello"} 1917324423454 (1.74 TB)
telemt_user_msgs_from_client{user="hello"} 77823
telemt_user_msgs_to_client{user="hello"} 338392
telemt_user_unique_ips_current{user="hello"} 797
telemt_user_unique_ips_recent_window{user="hello"} 148
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 45725.2 (12h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3945354
telemt_connections_bad_total 145006
telemt_connections_current 1312
telemt_connections_me_current 1312
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 1609677
telemt_upstream_connect_attempt_total 27774
telemt_upstream_connect_success_total 27597
telemt_upstream_connect_fail_total 170
telemt_upstream_connect_attempts_per_request{bucket="1"} 27767
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17372
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10149
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 76
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 170
telemt_me_reconnect_attempts_total 45825
telemt_me_reconnect_success_total 972
telemt_me_reader_eof_total 654
telemt_me_idle_close_by_peer_total 654
telemt_me_route_drop_no_conn_total 1023686
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1933612
telemt_me_endpoint_quarantine_total 338
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 50
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 50
telemt_me_single_endpoint_shadow_rotate_total 350
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 9
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
telemt_me_writers_active_current 45
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 10492
telemt_desync_full_logged_total 3616
telemt_desync_suppressed_total 6876
telemt_desync_frames_bucket_total{bucket="1_2"} 1896
telemt_desync_frames_bucket_total{bucket="3_10"} 4020
telemt_desync_frames_bucket_total{bucket="gt_10"} 4576
telemt_pool_swap_total 49
telemt_pool_force_close_total 1492
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 135
telemt_me_draining_writers_reap_progress_total 16789
telemt_me_writer_removed_unexpected_total 728
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1533
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16010
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1286
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 206
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15297
telemt_me_writer_teardown_success_total{mode="normal"} 17543
telemt_me_writer_teardown_noop_total 16791
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 33815
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 34096
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 34228
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 34334
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 34334
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 34334
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 34334
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 34334
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 34334
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 34334
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 34334
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 34334
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 34334
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.443405
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 34334
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 135
telemt_me_refill_failed_total 2606
telemt_me_writer_restored_same_endpoint_total 871
telemt_me_writer_restored_fallback_total 12
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4264
telemt_user_connections_total{user="hello"} 1937211
telemt_user_connections_current{user="hello"} 1312
telemt_user_octets_from_client{user="hello"} 54134900904 (50.42 GB)
telemt_user_octets_to_client{user="hello"} 822811482574 (766.30 GB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 684
telemt_user_unique_ips_recent_window{user="hello"} 179
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 26695.9 (7h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 198629
telemt_connections_bad_total 1696
telemt_connections_current 343
telemt_connections_me_current 343
telemt_handshake_timeouts_total 5470
telemt_upstream_connect_attempt_total 12890
telemt_upstream_connect_success_total 12858
telemt_upstream_connect_fail_total 30
telemt_upstream_connect_attempts_per_request{bucket="1"} 12888
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5426
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7353
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 79
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 30
telemt_me_reconnect_attempts_total 292
telemt_me_reconnect_success_total 170
telemt_me_reader_eof_total 175
telemt_me_idle_close_by_peer_total 175
telemt_me_route_drop_no_conn_total 54651
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 175065
telemt_me_endpoint_quarantine_total 262
telemt_me_single_endpoint_shadow_rotate_total 233
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 35
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 45
telemt_desync_total 1031
telemt_desync_full_logged_total 261
telemt_desync_suppressed_total 770
telemt_desync_frames_bucket_total{bucket="1_2"} 390
telemt_desync_frames_bucket_total{bucket="3_10"} 384
telemt_desync_frames_bucket_total{bucket="gt_10"} 257
telemt_pool_swap_total 29
telemt_pool_force_close_total 647
telemt_me_writer_close_signal_drop_total 23
telemt_me_draining_writers_reap_progress_total 11623
telemt_me_writer_removed_unexpected_total 168
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 752
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 11046
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 645
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 10976
telemt_me_writer_teardown_success_total{mode="normal"} 11798
telemt_me_writer_teardown_noop_total 11623
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 23225
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 23393
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 23411
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 23421
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 23421
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 23421
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 23421
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 23421
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 23421
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 23421
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 23421
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 23421
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 23421
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.984224
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 23421
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 23
telemt_me_refill_failed_total 7
telemt_me_writer_restored_same_endpoint_total 154
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 13
telemt_user_connections_total{user="hello"} 174750
telemt_user_connections_current{user="hello"} 343
telemt_user_octets_from_client{user="hello"} 3106325740 (2.89 GB)
telemt_user_octets_to_client{user="hello"} 107909479516 (100.50 GB)
telemt_user_unique_ips_current{user="hello"} 150
telemt_user_unique_ips_recent_window{user="hello"} 38
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 108893.6 (30h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7357203
telemt_connections_bad_total 742623
telemt_connections_current 1664
telemt_connections_me_current 1664
telemt_handshake_timeouts_total 209450
telemt_upstream_connect_attempt_total 42678
telemt_upstream_connect_success_total 42521
telemt_upstream_connect_fail_total 120
telemt_upstream_connect_attempts_per_request{bucket="1"} 42641
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21073
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21407
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 120
telemt_me_reconnect_attempts_total 1588
telemt_me_reconnect_success_total 853
telemt_me_reader_eof_total 836
telemt_me_idle_close_by_peer_total 836
telemt_me_route_drop_no_conn_total 2129299
telemt_me_route_drop_channel_closed_total 52
telemt_me_route_drop_queue_full_total 23
telemt_me_route_drop_queue_full_profile_total{profile="high"} 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5492249
telemt_me_endpoint_quarantine_total 763
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 839
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
telemt_me_writers_active_current 43
telemt_desync_total 21507
telemt_desync_full_logged_total 7058
telemt_desync_suppressed_total 14449
telemt_desync_frames_bucket_total{bucket="1_2"} 5411
telemt_desync_frames_bucket_total{bucket="3_10"} 7772
telemt_desync_frames_bucket_total{bucket="gt_10"} 8324
telemt_pool_swap_total 120
telemt_pool_force_close_total 3213
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 388
telemt_me_draining_writers_reap_progress_total 38482
telemt_me_writer_removed_unexpected_total 807
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3020
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 36288
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3125
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 35269
telemt_me_writer_teardown_success_total{mode="normal"} 39308
telemt_me_writer_teardown_noop_total 38484
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 76437
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 77326
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 77504
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 77704
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 77792
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 77792
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 77792
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 77792
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 77792
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 77792
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 77792
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 77792
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 77792
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.646335
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 77792
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 388
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 763
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 36
telemt_user_connections_total{user="hello"} 5467275
telemt_user_connections_current{user="hello"} 1664
telemt_user_octets_from_client{user="hello"} 109712758856 (102.18 GB)
telemt_user_octets_to_client{user="hello"} 2547065967800 (2.32 TB)
telemt_user_unique_ips_current{user="hello"} 759
telemt_user_unique_ips_recent_window{user="hello"} 179
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 108890.2 (30h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6343134
telemt_connections_bad_total 627276
telemt_connections_current 1649
telemt_connections_me_current 1649
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 173152
telemt_upstream_connect_attempt_total 58480
telemt_upstream_connect_success_total 58041
telemt_upstream_connect_fail_total 379
telemt_upstream_connect_attempts_per_request{bucket="1"} 58420
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33789
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23118
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 616
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 379
telemt_me_reconnect_attempts_total 5578
telemt_me_reconnect_success_total 1179
telemt_me_reader_eof_total 1065
telemt_me_idle_close_by_peer_total 1065
telemt_me_seq_mismatch_total 48
telemt_me_route_drop_no_conn_total 2181730
telemt_me_route_drop_channel_closed_total 189
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4859127
telemt_me_endpoint_quarantine_total 859
telemt_me_single_endpoint_outage_enter_total 28
telemt_me_single_endpoint_outage_exit_total 28
telemt_me_single_endpoint_outage_reconnect_attempt_total 28
telemt_me_single_endpoint_outage_reconnect_success_total 26
telemt_me_single_endpoint_quarantine_bypass_total 28
telemt_me_single_endpoint_shadow_rotate_total 835
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
telemt_me_writers_active_current 46
telemt_desync_total 20165
telemt_desync_full_logged_total 6713
telemt_desync_suppressed_total 13452
telemt_desync_frames_bucket_total{bucket="1_2"} 5167
telemt_desync_frames_bucket_total{bucket="3_10"} 7351
telemt_desync_frames_bucket_total{bucket="gt_10"} 7647
telemt_pool_swap_total 118
telemt_pool_force_close_total 3174
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 381
telemt_me_draining_writers_reap_progress_total 37047
telemt_me_writer_removed_unexpected_total 1075
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3551
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 34624
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2951
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 223
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 33873
telemt_me_writer_teardown_success_total{mode="normal"} 38175
telemt_me_writer_teardown_noop_total 37051
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 73584
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 74638
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 74993
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 75188
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 75226
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 75226
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 75226
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 75226
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 75226
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 75226
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 75226
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 75226
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 75226
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 11.086072
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 75226
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 381
telemt_me_refill_failed_total 254
telemt_me_writer_restored_same_endpoint_total 922
telemt_me_writer_restored_fallback_total 63
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 76
telemt_me_writer_removed_unexpected_minus_restored_total 90
telemt_user_connections_total{user="hello"} 4862147
telemt_user_connections_current{user="hello"} 1649
telemt_user_octets_from_client{user="hello"} 91814129589 (85.51 GB)
telemt_user_octets_to_client{user="hello"} 2076771139416 (1.89 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 758
telemt_user_unique_ips_recent_window{user="hello"} 167
```