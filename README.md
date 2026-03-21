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

# Server Metrics 2026-03-21 13:56:38 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 62445.1 (17h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2088628
telemt_connections_bad_total 103617
telemt_connections_current 1606
telemt_connections_me_current 1606
telemt_handshake_timeouts_total 74019
telemt_upstream_connect_attempt_total 23952
telemt_upstream_connect_success_total 23831
telemt_upstream_connect_fail_total 78
telemt_upstream_connect_attempts_per_request{bucket="1"} 23909
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8400
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15347
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 31
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 78
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 92
telemt_me_reconnect_attempts_total 1350
telemt_me_reconnect_success_total 567
telemt_me_reader_eof_total 539
telemt_me_idle_close_by_peer_total 539
telemt_me_route_drop_no_conn_total 1596240
telemt_me_route_drop_channel_closed_total 528
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1654663
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_endpoint_quarantine_total 443
telemt_me_single_endpoint_outage_enter_total 6
telemt_me_single_endpoint_outage_exit_total 6
telemt_me_single_endpoint_outage_reconnect_attempt_total 6
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 6
telemt_me_single_endpoint_shadow_rotate_total 494
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 20
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
telemt_desync_total 6529
telemt_desync_full_logged_total 2256
telemt_desync_suppressed_total 4273
telemt_desync_frames_bucket_total{bucket="1_2"} 1465
telemt_desync_frames_bucket_total{bucket="3_10"} 2474
telemt_desync_frames_bucket_total{bucket="gt_10"} 2590
telemt_pool_swap_total 68
telemt_pool_force_close_total 2060
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 414
telemt_me_draining_writers_reap_progress_total 21431
telemt_me_writer_removed_unexpected_total 521
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1781
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19965
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1983
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 77
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19371
telemt_me_writer_teardown_success_total{mode="normal"} 21746
telemt_me_writer_teardown_noop_total 21437
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 36716
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 37967
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 39037
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 40850
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 42272
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 42954
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 43161
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 43182
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 43182
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 43183
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 43183
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 43183
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 43183
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 179.419271
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 43183
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 414
telemt_me_refill_failed_total 42
telemt_me_writer_restored_same_endpoint_total 491
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 26
telemt_user_connections_total{user="hello"} 1653390
telemt_user_connections_current{user="hello"} 1606
telemt_user_octets_from_client{user="hello"} 24655849139 (22.96 GB)
telemt_user_octets_to_client{user="hello"} 426637181451 (397.34 GB)
telemt_user_msgs_from_client{user="hello"} 295
telemt_user_msgs_to_client{user="hello"} 249
telemt_user_unique_ips_current{user="hello"} 597
telemt_user_unique_ips_recent_window{user="hello"} 254
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 1999.1 (0h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 188994
telemt_connections_bad_total 6717
telemt_connections_current 3314
telemt_connections_me_current 3314
telemt_handshake_timeouts_total 5626
telemt_upstream_connect_attempt_total 689
telemt_upstream_connect_success_total 688
telemt_upstream_connect_attempts_per_request{bucket="1"} 688
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 298
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 375
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_me_reconnect_attempts_total 97
telemt_me_reconnect_success_total 17
telemt_me_reader_eof_total 16
telemt_me_idle_close_by_peer_total 16
telemt_me_route_drop_no_conn_total 99339
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 165892
telemt_me_endpoint_quarantine_total 19
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
telemt_me_writers_active_current 42
telemt_desync_total 648
telemt_desync_full_logged_total 243
telemt_desync_suppressed_total 405
telemt_desync_frames_bucket_total{bucket="1_2"} 120
telemt_desync_frames_bucket_total{bucket="3_10"} 238
telemt_desync_frames_bucket_total{bucket="gt_10"} 290
telemt_pool_swap_total 2
telemt_pool_force_close_total 23
telemt_me_writer_close_signal_drop_total 8
telemt_me_draining_writers_reap_progress_total 518
telemt_me_writer_removed_unexpected_total 15
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 37
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 497
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 21
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 495
telemt_me_writer_teardown_success_total{mode="normal"} 534
telemt_me_writer_teardown_noop_total 518
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 1040
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 1051
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 1052
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 1052
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 1052
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 1052
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 1052
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 1052
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 1052
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 1052
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 1052
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 1052
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 1052
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.058004
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 1052
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 8
telemt_me_refill_failed_total 5
telemt_me_writer_restored_same_endpoint_total 9
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 164148
telemt_user_connections_current{user="hello"} 3314
telemt_user_octets_from_client{user="hello"} 3566848336 (3.32 GB)
telemt_user_octets_to_client{user="hello"} 39228026512 (36.53 GB)
telemt_user_unique_ips_current{user="hello"} 1578
telemt_user_unique_ips_recent_window{user="hello"} 551
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 62443.1 (17h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4141446
telemt_connections_bad_total 397221
telemt_connections_current 3745
telemt_connections_me_current 3745
telemt_handshake_timeouts_total 159481
telemt_upstream_connect_attempt_total 23683
telemt_upstream_connect_success_total 23643
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 23648
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10690
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12865
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 82
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 911
telemt_me_reconnect_success_total 538
telemt_me_reader_eof_total 536
telemt_me_idle_close_by_peer_total 536
telemt_me_route_drop_no_conn_total 2099462
telemt_me_route_drop_channel_closed_total 39
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3349759
telemt_me_endpoint_quarantine_total 397
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 3
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 476
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
telemt_me_writers_active_current 46
telemt_desync_total 14100
telemt_desync_full_logged_total 4760
telemt_desync_suppressed_total 9340
telemt_desync_frames_bucket_total{bucket="1_2"} 2981
telemt_desync_frames_bucket_total{bucket="3_10"} 5550
telemt_desync_frames_bucket_total{bucket="gt_10"} 5569
telemt_pool_swap_total 66
telemt_pool_force_close_total 2121
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 326
telemt_me_draining_writers_reap_progress_total 21494
telemt_me_writer_removed_unexpected_total 517
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1866
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19945
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 29
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1935
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 186
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19373
telemt_me_writer_teardown_success_total{mode="normal"} 21811
telemt_me_writer_teardown_noop_total 21523
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 39964
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 41109
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 41721
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 42505
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 42985
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 43250
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 43334
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 43334
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 43334
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 43334
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 43334
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 43334
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 43334
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 68.871652
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 43334
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 326
telemt_me_refill_failed_total 18
telemt_me_writer_restored_same_endpoint_total 489
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 23
telemt_user_connections_total{user="hello"} 3345564
telemt_user_connections_current{user="hello"} 3746
telemt_user_octets_from_client{user="hello"} 55812017364 (51.98 GB)
telemt_user_octets_to_client{user="hello"} 1146894346684 (1.04 TB)
telemt_user_unique_ips_current{user="hello"} 1428
telemt_user_unique_ips_recent_window{user="hello"} 576
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 62444.4 (17h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3393161
telemt_connections_bad_total 376789
telemt_connections_current 3806
telemt_connections_me_current 3806
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 126549
telemt_upstream_connect_attempt_total 28024
telemt_upstream_connect_success_total 27748
telemt_upstream_connect_fail_total 135
telemt_upstream_connect_attempts_per_request{bucket="1"} 27883
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14409
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12835
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 477
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 135
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 76
telemt_me_reconnect_attempts_total 1167
telemt_me_reconnect_success_total 551
telemt_me_reader_eof_total 516
telemt_me_idle_close_by_peer_total 516
telemt_me_route_drop_no_conn_total 1059673
telemt_me_route_drop_channel_closed_total 84
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2456299
telemt_me_endpoint_quarantine_total 407
telemt_me_single_endpoint_outage_enter_total 6
telemt_me_single_endpoint_outage_exit_total 6
telemt_me_single_endpoint_outage_reconnect_attempt_total 6
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 6
telemt_me_single_endpoint_shadow_rotate_total 480
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
telemt_desync_total 11194
telemt_desync_full_logged_total 3800
telemt_desync_suppressed_total 7394
telemt_desync_frames_bucket_total{bucket="1_2"} 2800
telemt_desync_frames_bucket_total{bucket="3_10"} 4306
telemt_desync_frames_bucket_total{bucket="gt_10"} 4088
telemt_pool_swap_total 68
telemt_pool_force_close_total 1941
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 175
telemt_me_draining_writers_reap_progress_total 20671
telemt_me_writer_removed_unexpected_total 501
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1750
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19428
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1812
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 129
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18730
telemt_me_writer_teardown_success_total{mode="normal"} 21178
telemt_me_writer_teardown_noop_total 20672
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 40367
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 41139
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 41365
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 41636
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 41791
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 41848
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 41850
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 41850
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 41850
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 41850
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 41850
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 41850
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 41850
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.951967
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 41850
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 175
telemt_me_refill_failed_total 32
telemt_me_writer_restored_same_endpoint_total 465
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 30
telemt_user_connections_total{user="hello"} 2456716
telemt_user_connections_current{user="hello"} 3806
telemt_user_octets_from_client{user="hello"} 45797830581 (42.65 GB)
telemt_user_octets_to_client{user="hello"} 1152760720211 (1.05 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1455
telemt_user_unique_ips_recent_window{user="hello"} 512
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 62408.2 (17h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3300607
telemt_connections_bad_total 352368
telemt_connections_current 3345
telemt_connections_me_current 3345
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 95345
telemt_upstream_connect_attempt_total 33192
telemt_upstream_connect_success_total 32963
telemt_upstream_connect_fail_total 133
telemt_upstream_connect_attempts_per_request{bucket="1"} 33096
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17651
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14187
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 280
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 845
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 133
telemt_me_keepalive_timeout_total 50
telemt_me_reconnect_attempts_total 1283
telemt_me_reconnect_success_total 624
telemt_me_reader_eof_total 568
telemt_me_idle_close_by_peer_total 568
telemt_me_route_drop_no_conn_total 1012887
telemt_me_route_drop_channel_closed_total 32
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2417572
telemt_me_endpoint_quarantine_total 457
telemt_me_single_endpoint_outage_enter_total 4
telemt_me_single_endpoint_outage_exit_total 4
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 3
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 468
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 20
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
telemt_desync_total 11288
telemt_desync_full_logged_total 3744
telemt_desync_suppressed_total 7544
telemt_desync_frames_bucket_total{bucket="1_2"} 2863
telemt_desync_frames_bucket_total{bucket="3_10"} 4244
telemt_desync_frames_bucket_total{bucket="gt_10"} 4181
telemt_pool_swap_total 66
telemt_pool_force_close_total 1876
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 215
telemt_me_draining_writers_reap_progress_total 22000
telemt_me_writer_removed_unexpected_total 541
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1858
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20718
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1707
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 169
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20124
telemt_me_writer_teardown_success_total{mode="normal"} 22576
telemt_me_writer_teardown_noop_total 22005
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 43476
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 44166
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 44346
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 44517
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 44580
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 44581
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 44581
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 44581
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 44581
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 44581
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 44581
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 44581
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 44581
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.343713
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 44581
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 215
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 543
telemt_me_writer_restored_fallback_total 3
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_user_connections_total{user="hello"} 2422250
telemt_user_connections_current{user="hello"} 3345
telemt_user_octets_from_client{user="hello"} 52882842853 (49.25 GB)
telemt_user_octets_to_client{user="hello"} 1146587195564 (1.04 TB)
telemt_user_msgs_from_client{user="hello"} 42436
telemt_user_msgs_to_client{user="hello"} 111361
telemt_user_unique_ips_current{user="hello"} 1280
telemt_user_unique_ips_recent_window{user="hello"} 509
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 62447.5 (17h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11263056
telemt_connections_bad_total 766183
telemt_connections_current 5041
telemt_connections_me_current 5041
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 353779
telemt_upstream_connect_attempt_total 112438
telemt_upstream_connect_success_total 102767
telemt_upstream_connect_fail_total 8708
telemt_upstream_connect_attempts_per_request{bucket="1"} 111475
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 72938
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24145
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 527
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5157
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8708
telemt_me_keepalive_timeout_total 74
telemt_me_reconnect_attempts_total 3651
telemt_me_reconnect_success_total 1295
telemt_me_reader_eof_total 934
telemt_me_idle_close_by_peer_total 933
telemt_me_route_drop_no_conn_total 20857436
telemt_me_route_drop_channel_closed_total 71
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9227447
telemt_me_endpoint_quarantine_total 483
telemt_me_single_endpoint_outage_enter_total 69
telemt_me_single_endpoint_outage_exit_total 69
telemt_me_single_endpoint_outage_reconnect_attempt_total 154
telemt_me_single_endpoint_outage_reconnect_success_total 30
telemt_me_single_endpoint_quarantine_bypass_total 154
telemt_me_single_endpoint_shadow_rotate_total 489
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 37
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
telemt_desync_total 17058
telemt_desync_full_logged_total 5421
telemt_desync_suppressed_total 11637
telemt_desync_frames_bucket_total{bucket="1_2"} 3687
telemt_desync_frames_bucket_total{bucket="3_10"} 7477
telemt_desync_frames_bucket_total{bucket="gt_10"} 5894
telemt_pool_swap_total 63
telemt_pool_force_close_total 2026
telemt_pool_stale_pick_total 5
telemt_me_writer_close_signal_drop_total 423
telemt_me_draining_writers_reap_progress_total 20324
telemt_me_writer_removed_unexpected_total 1245
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2673
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18724
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1686
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 340
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18298
telemt_me_writer_teardown_success_total{mode="normal"} 21397
telemt_me_writer_teardown_noop_total 20334
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 37929
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 39292
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 40118
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 41010
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 41523
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 41688
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 41712
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 41714
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 41717
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 41722
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 41722
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 41726
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 41731
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 161.575881
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 41731
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 423
telemt_me_refill_failed_total 85
telemt_me_writer_restored_same_endpoint_total 913
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 63
telemt_me_writer_removed_unexpected_minus_restored_total 323
telemt_user_connections_total{user="hello"} 9302198
telemt_user_connections_current{user="hello"} 5041
telemt_user_octets_from_client{user="hello"} 69470542855 (64.70 GB)
telemt_user_octets_to_client{user="hello"} 739640142547 (688.84 GB)
telemt_user_msgs_from_client{user="hello"} 228562
telemt_user_msgs_to_client{user="hello"} 540142
telemt_user_unique_ips_current{user="hello"} 1859
telemt_user_unique_ips_recent_window{user="hello"} 859
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 62415.1 (17h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3315866
telemt_connections_bad_total 374835
telemt_connections_current 3548
telemt_connections_me_current 3548
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 73386
telemt_upstream_connect_attempt_total 26885
telemt_upstream_connect_success_total 26598
telemt_upstream_connect_fail_total 255
telemt_upstream_connect_attempts_per_request{bucket="1"} 26853
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12734
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13797
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 67
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 255
telemt_me_reconnect_attempts_total 2582
telemt_me_reconnect_success_total 952
telemt_me_reader_eof_total 945
telemt_me_idle_close_by_peer_total 945
telemt_me_route_drop_no_conn_total 1307881
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 33
telemt_me_route_drop_queue_full_profile_total{profile="high"} 33
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2538976
telemt_me_endpoint_quarantine_total 396
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 473
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 24
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
telemt_desync_total 11956
telemt_desync_full_logged_total 4157
telemt_desync_suppressed_total 7799
telemt_desync_frames_bucket_total{bucket="1_2"} 2307
telemt_desync_frames_bucket_total{bucket="3_10"} 4775
telemt_desync_frames_bucket_total{bucket="gt_10"} 4874
telemt_pool_swap_total 62
telemt_pool_force_close_total 1797
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 173
telemt_me_draining_writers_reap_progress_total 22510
telemt_me_writer_removed_unexpected_total 916
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2213
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21243
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1554
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 243
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20713
telemt_me_writer_teardown_success_total{mode="normal"} 23456
telemt_me_writer_teardown_noop_total 22511
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 45436
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 45768
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 45937
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 45967
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 45967
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 45967
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 45967
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 45967
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 45967
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 45967
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 45967
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 45967
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 45967
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.940220
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 45967
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 173
telemt_me_refill_failed_total 89
telemt_me_writer_restored_same_endpoint_total 816
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 90
telemt_user_connections_total{user="hello"} 2523481
telemt_user_connections_current{user="hello"} 3548
telemt_user_octets_from_client{user="hello"} 53717018768 (50.03 GB)
telemt_user_octets_to_client{user="hello"} 1090172376918 (1015.30 GB)
telemt_user_msgs_from_client{user="hello"} 7339
telemt_user_msgs_to_client{user="hello"} 11522
telemt_user_unique_ips_current{user="hello"} 1397
telemt_user_unique_ips_recent_window{user="hello"} 491
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 62409.7 (17h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5088853
telemt_connections_bad_total 246960
telemt_connections_current 3176
telemt_connections_me_current 3176
telemt_handshake_timeouts_total 2247575
telemt_upstream_connect_attempt_total 24622
telemt_upstream_connect_success_total 24588
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 24591
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11002
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13295
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 291
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 1062
telemt_me_reconnect_success_total 462
telemt_me_reader_eof_total 461
telemt_me_idle_close_by_peer_total 461
telemt_me_route_drop_no_conn_total 1185307
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 13
telemt_me_route_drop_queue_full_profile_total{profile="high"} 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2294136
telemt_me_endpoint_quarantine_total 465
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 485
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
telemt_me_writers_active_current 46
telemt_desync_total 10911
telemt_desync_full_logged_total 3840
telemt_desync_suppressed_total 7071
telemt_desync_frames_bucket_total{bucket="1_2"} 2028
telemt_desync_frames_bucket_total{bucket="3_10"} 4288
telemt_desync_frames_bucket_total{bucket="gt_10"} 4595
telemt_pool_swap_total 68
telemt_pool_force_close_total 1750
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 152
telemt_me_draining_writers_reap_progress_total 22034
telemt_me_writer_removed_unexpected_total 443
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1535
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20969
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1680
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 70
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20284
telemt_me_writer_teardown_success_total{mode="normal"} 22504
telemt_me_writer_teardown_noop_total 22034
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 44213
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 44422
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 44516
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 44538
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 44538
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 44538
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 44538
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 44538
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 44538
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 44538
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 44538
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 44538
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 44538
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.880783
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 44538
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 152
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 400
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 41
telemt_user_connections_total{user="hello"} 2287095
telemt_user_connections_current{user="hello"} 3176
telemt_user_octets_from_client{user="hello"} 48759900292 (45.41 GB)
telemt_user_octets_to_client{user="hello"} 1057555427068 (984.93 GB)
telemt_user_unique_ips_current{user="hello"} 1292
telemt_user_unique_ips_recent_window{user="hello"} 495
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 60401.1 (16h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1090502
telemt_connections_bad_total 135238
telemt_connections_current 767
telemt_connections_me_current 767
telemt_handshake_timeouts_total 383682
telemt_upstream_connect_attempt_total 28320
telemt_upstream_connect_success_total 28317
telemt_upstream_connect_attempts_per_request{bucket="1"} 28317
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11633
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16599
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 85
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 1193
telemt_me_reconnect_success_total 463
telemt_me_reader_eof_total 461
telemt_me_idle_close_by_peer_total 461
telemt_me_route_drop_no_conn_total 227946
telemt_me_route_drop_channel_closed_total 16
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 501150
telemt_me_endpoint_quarantine_total 559
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 508
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
telemt_me_writers_active_current 43
telemt_desync_total 3262
telemt_desync_full_logged_total 1211
telemt_desync_suppressed_total 2051
telemt_desync_frames_bucket_total{bucket="1_2"} 580
telemt_desync_frames_bucket_total{bucket="3_10"} 1164
telemt_desync_frames_bucket_total{bucket="gt_10"} 1518
telemt_pool_swap_total 67
telemt_pool_force_close_total 1499
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 103
telemt_me_draining_writers_reap_progress_total 25371
telemt_me_writer_removed_unexpected_total 435
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1854
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 23963
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1496
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 23872
telemt_me_writer_teardown_success_total{mode="normal"} 25817
telemt_me_writer_teardown_noop_total 25371
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 50624
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 51042
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 51150
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 51180
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 51188
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 51188
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 51188
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 51188
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 51188
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 51188
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 51188
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 51188
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 51188
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.357633
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 51188
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 103
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 376
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 54
telemt_user_connections_total{user="hello"} 500929
telemt_user_connections_current{user="hello"} 767
telemt_user_octets_from_client{user="hello"} 9510907179 (8.86 GB)
telemt_user_octets_to_client{user="hello"} 189566992625 (176.55 GB)
telemt_user_msgs_from_client{user="hello"} 804
telemt_user_msgs_to_client{user="hello"} 1943
telemt_user_unique_ips_current{user="hello"} 305
telemt_user_unique_ips_recent_window{user="hello"} 109
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 62419.5 (17h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3610142
telemt_connections_bad_total 332610
telemt_connections_current 4477
telemt_connections_me_current 4477
telemt_handshake_timeouts_total 111277
telemt_upstream_connect_attempt_total 25416
telemt_upstream_connect_success_total 25312
telemt_upstream_connect_fail_total 72
telemt_upstream_connect_attempts_per_request{bucket="1"} 25384
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12598
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12683
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 72
telemt_me_reconnect_attempts_total 1029
telemt_me_reconnect_success_total 581
telemt_me_reader_eof_total 541
telemt_me_idle_close_by_peer_total 541
telemt_me_route_drop_no_conn_total 1054110
telemt_me_route_drop_channel_closed_total 28
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2860859
telemt_me_endpoint_quarantine_total 468
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 481
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 24
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
telemt_desync_total 11414
telemt_desync_full_logged_total 3758
telemt_desync_suppressed_total 7656
telemt_desync_frames_bucket_total{bucket="1_2"} 2710
telemt_desync_frames_bucket_total{bucket="3_10"} 4243
telemt_desync_frames_bucket_total{bucket="gt_10"} 4461
telemt_pool_swap_total 69
telemt_pool_force_close_total 1790
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 193
telemt_me_draining_writers_reap_progress_total 22827
telemt_me_writer_removed_unexpected_total 531
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1789
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21568
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1755
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 35
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21037
telemt_me_writer_teardown_success_total{mode="normal"} 23357
telemt_me_writer_teardown_noop_total 22827
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 45548
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 45947
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 46030
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 46140
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 46184
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 46184
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 46184
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 46184
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 46184
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 46184
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 46184
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 46184
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 46184
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.252343
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 46184
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 193
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 513
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 13
telemt_user_connections_total{user="hello"} 2853159
telemt_user_connections_current{user="hello"} 4477
telemt_user_octets_from_client{user="hello"} 60310794632 (56.17 GB)
telemt_user_octets_to_client{user="hello"} 1346186304280 (1.22 TB)
telemt_user_unique_ips_current{user="hello"} 1571
telemt_user_unique_ips_recent_window{user="hello"} 609
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 62416.1 (17h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3256238
telemt_connections_bad_total 288709
telemt_connections_current 3864
telemt_connections_me_current 3864
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 94836
telemt_upstream_connect_attempt_total 41597
telemt_upstream_connect_success_total 41328
telemt_upstream_connect_fail_total 223
telemt_upstream_connect_attempts_per_request{bucket="1"} 41551
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25849
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14375
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 516
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 588
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 223
telemt_me_reconnect_attempts_total 3536
telemt_me_reconnect_success_total 750
telemt_me_reader_eof_total 658
telemt_me_idle_close_by_peer_total 658
telemt_me_seq_mismatch_total 31
telemt_me_route_drop_no_conn_total 1095807
telemt_me_route_drop_channel_closed_total 81
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2611617
telemt_me_endpoint_quarantine_total 531
telemt_me_single_endpoint_outage_enter_total 16
telemt_me_single_endpoint_outage_exit_total 16
telemt_me_single_endpoint_outage_reconnect_attempt_total 16
telemt_me_single_endpoint_outage_reconnect_success_total 16
telemt_me_single_endpoint_quarantine_bypass_total 16
telemt_me_single_endpoint_shadow_rotate_total 482
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 19
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
telemt_desync_total 10068
telemt_desync_full_logged_total 3441
telemt_desync_suppressed_total 6627
telemt_desync_frames_bucket_total{bucket="1_2"} 2546
telemt_desync_frames_bucket_total{bucket="3_10"} 3722
telemt_desync_frames_bucket_total{bucket="gt_10"} 3800
telemt_pool_swap_total 68
telemt_pool_force_close_total 1736
telemt_me_writer_close_signal_drop_total 186
telemt_me_draining_writers_reap_progress_total 21974
telemt_me_writer_removed_unexpected_total 670
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2096
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20579
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1621
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 115
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20238
telemt_me_writer_teardown_success_total{mode="normal"} 22675
telemt_me_writer_teardown_noop_total 21975
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 43924
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 44362
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 44520
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 44641
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 44650
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 44650
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 44650
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 44650
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 44650
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 44650
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 44650
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 44650
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 44650
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.303828
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 44650
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 186
telemt_me_refill_failed_total 158
telemt_me_writer_restored_same_endpoint_total 573
telemt_me_writer_restored_fallback_total 40
telemt_me_async_recovery_trigger_total 53
telemt_me_writer_removed_unexpected_minus_restored_total 57
telemt_user_connections_total{user="hello"} 2620691
telemt_user_connections_current{user="hello"} 3864
telemt_user_octets_from_client{user="hello"} 47721485401 (44.44 GB)
telemt_user_octets_to_client{user="hello"} 1138522326216 (1.04 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1381
telemt_user_unique_ips_recent_window{user="hello"} 519
```