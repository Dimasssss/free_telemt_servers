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

# Server Metrics 2026-03-21 20:13:19 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 85045.7 (23h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3047902
telemt_connections_bad_total 177823
telemt_connections_current 1081
telemt_connections_me_current 1081
telemt_relay_adaptive_promotions_total 3
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 93508
telemt_upstream_connect_attempt_total 34793
telemt_upstream_connect_success_total 34649
telemt_upstream_connect_fail_total 101
telemt_upstream_connect_attempts_per_request{bucket="1"} 34750
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13953
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20573
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 55
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 68
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 101
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 107
telemt_me_reconnect_attempts_total 1887
telemt_me_reconnect_success_total 760
telemt_me_reader_eof_total 728
telemt_me_idle_close_by_peer_total 728
telemt_me_route_drop_no_conn_total 2615297
telemt_me_route_drop_channel_closed_total 841
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2465707
telemt_me_writer_pick_total{mode="p2c",result="full"} 26
telemt_me_endpoint_quarantine_total 575
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 663
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 26
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
telemt_me_writers_active_current 46
telemt_desync_total 9845
telemt_desync_full_logged_total 3435
telemt_desync_suppressed_total 6410
telemt_desync_frames_bucket_total{bucket="1_2"} 2152
telemt_desync_frames_bucket_total{bucket="3_10"} 3714
telemt_desync_frames_bucket_total{bucket="gt_10"} 3979
telemt_pool_swap_total 92
telemt_pool_force_close_total 2788
telemt_pool_stale_pick_total 31
telemt_me_writer_close_signal_drop_total 640
telemt_me_draining_writers_reap_progress_total 28474
telemt_me_writer_removed_unexpected_total 710
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2399
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 26525
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2649
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 139
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 25686
telemt_me_writer_teardown_success_total{mode="normal"} 28924
telemt_me_writer_teardown_noop_total 28482
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 46942
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 48833
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 50456
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 53403
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 55827
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 57029
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 57376
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 57401
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 57405
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 57406
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 57406
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 57406
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 57406
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 297.820642
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 57406
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 640
telemt_me_refill_failed_total 62
telemt_me_writer_restored_same_endpoint_total 653
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 49
telemt_user_connections_total{user="hello"} 2465360
telemt_user_connections_current{user="hello"} 1081
telemt_user_octets_from_client{user="hello"} 36472746945 (33.97 GB)
telemt_user_octets_to_client{user="hello"} 624437384494 (581.55 GB)
telemt_user_msgs_from_client{user="hello"} 7227
telemt_user_msgs_to_client{user="hello"} 6949
telemt_user_unique_ips_current{user="hello"} 424
telemt_user_unique_ips_recent_window{user="hello"} 154
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 10183.3 (2h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 415811
telemt_connections_bad_total 18677
telemt_connections_current 887
telemt_connections_me_current 887
telemt_handshake_timeouts_total 14515
telemt_upstream_connect_attempt_total 4084
telemt_upstream_connect_success_total 3996
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 4072
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1751
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2230
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_reconnect_attempts_total 218
telemt_me_reconnect_success_total 134
telemt_me_reader_eof_total 110
telemt_me_idle_close_by_peer_total 110
telemt_me_route_drop_no_conn_total 259129
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 341746
telemt_me_endpoint_quarantine_total 79
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 84
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
telemt_me_writers_active_current 44
telemt_desync_total 1475
telemt_desync_full_logged_total 829
telemt_desync_suppressed_total 646
telemt_desync_frames_bucket_total{bucket="1_2"} 298
telemt_desync_frames_bucket_total{bucket="3_10"} 555
telemt_desync_frames_bucket_total{bucket="gt_10"} 622
telemt_pool_swap_total 11
telemt_pool_force_close_total 335
telemt_me_writer_close_signal_drop_total 30
telemt_me_draining_writers_reap_progress_total 3534
telemt_me_writer_removed_unexpected_total 104
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 311
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 3320
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 328
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 3199
telemt_me_writer_teardown_success_total{mode="normal"} 3631
telemt_me_writer_teardown_noop_total 3534
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 6894
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 7045
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 7088
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 7159
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 7165
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 7165
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 7165
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 7165
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 7165
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 7165
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 7165
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 7165
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 7165
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.035158
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 7165
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 30
telemt_me_refill_failed_total 4
telemt_me_writer_restored_same_endpoint_total 92
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 7
telemt_user_connections_total{user="hello"} 341350
telemt_user_connections_current{user="hello"} 887
telemt_user_octets_from_client{user="hello"} 5433420500 (5.06 GB)
telemt_user_octets_to_client{user="hello"} 98173968076 (91.43 GB)
telemt_user_unique_ips_current{user="hello"} 528
telemt_user_unique_ips_recent_window{user="hello"} 341
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 85043.2 (23h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6767059
telemt_connections_bad_total 521694
telemt_connections_current 3289
telemt_connections_me_current 3289
telemt_handshake_timeouts_total 212326
telemt_upstream_connect_attempt_total 30593
telemt_upstream_connect_success_total 30531
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 30537
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13752
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16648
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 125
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1282
telemt_me_reconnect_success_total 659
telemt_me_reader_eof_total 669
telemt_me_idle_close_by_peer_total 669
telemt_me_route_drop_no_conn_total 4316447
telemt_me_route_drop_channel_closed_total 62
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5549029
telemt_me_endpoint_quarantine_total 527
telemt_me_single_endpoint_outage_enter_total 4
telemt_me_single_endpoint_outage_exit_total 4
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 632
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
telemt_desync_total 22706
telemt_desync_full_logged_total 7558
telemt_desync_suppressed_total 15148
telemt_desync_frames_bucket_total{bucket="1_2"} 4754
telemt_desync_frames_bucket_total{bucket="3_10"} 9043
telemt_desync_frames_bucket_total{bucket="gt_10"} 8909
telemt_pool_swap_total 91
telemt_pool_force_close_total 3043
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 495
telemt_me_draining_writers_reap_progress_total 27835
telemt_me_writer_removed_unexpected_total 643
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2399
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 25730
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 37
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2813
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 230
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 24792
telemt_me_writer_teardown_success_total{mode="normal"} 28129
telemt_me_writer_teardown_noop_total 27872
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 50865
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 52468
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 53292
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 54471
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 55254
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 55719
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 55990
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 56001
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 56001
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 56001
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 56001
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 56001
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 56001
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 135.166534
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 56001
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 495
telemt_me_refill_failed_total 32
telemt_me_writer_restored_same_endpoint_total 593
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 45
telemt_user_connections_total{user="hello"} 5542343
telemt_user_connections_current{user="hello"} 3289
telemt_user_octets_from_client{user="hello"} 92606860080 (86.25 GB)
telemt_user_octets_to_client{user="hello"} 1731995073260 (1.58 TB)
telemt_user_unique_ips_current{user="hello"} 1348
telemt_user_unique_ips_recent_window{user="hello"} 476
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 85044.7 (23h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5461671
telemt_connections_bad_total 521284
telemt_connections_current 3501
telemt_connections_me_current 3501
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 180914
telemt_upstream_connect_attempt_total 34730
telemt_upstream_connect_success_total 34414
telemt_upstream_connect_fail_total 162
telemt_upstream_connect_attempts_per_request{bucket="1"} 34576
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17432
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16414
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 541
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 162
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 1649
telemt_me_reconnect_success_total 692
telemt_me_reader_eof_total 664
telemt_me_idle_close_by_peer_total 664
telemt_me_route_drop_no_conn_total 1889209
telemt_me_route_drop_channel_closed_total 216
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4092736
telemt_me_endpoint_quarantine_total 522
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 649
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
telemt_me_writers_active_current 44
telemt_desync_total 19350
telemt_desync_full_logged_total 6409
telemt_desync_suppressed_total 12941
telemt_desync_frames_bucket_total{bucket="1_2"} 4713
telemt_desync_frames_bucket_total{bucket="3_10"} 7492
telemt_desync_frames_bucket_total{bucket="gt_10"} 7145
telemt_pool_swap_total 93
telemt_pool_force_close_total 2820
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 318
telemt_me_draining_writers_reap_progress_total 26654
telemt_me_writer_removed_unexpected_total 644
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2325
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 24901
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2628
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 192
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 23834
telemt_me_writer_teardown_success_total{mode="normal"} 27226
telemt_me_writer_teardown_noop_total 26659
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 50982
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 52339
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 52824
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 53346
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 53701
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 53872
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 53885
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 53885
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 53885
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 53885
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 53885
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 53885
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 53885
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 42.000989
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 53885
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 318
telemt_me_refill_failed_total 51
telemt_me_writer_restored_same_endpoint_total 592
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 44
telemt_user_connections_total{user="hello"} 4089440
telemt_user_connections_current{user="hello"} 3501
telemt_user_octets_from_client{user="hello"} 123603354033 (115.11 GB)
telemt_user_octets_to_client{user="hello"} 1860006805251 (1.69 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1334
telemt_user_unique_ips_recent_window{user="hello"} 403
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 85008.6 (23h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5395018
telemt_connections_bad_total 489200
telemt_connections_current 3419
telemt_connections_me_current 3419
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 163233
telemt_upstream_connect_attempt_total 41124
telemt_upstream_connect_success_total 40860
telemt_upstream_connect_fail_total 134
telemt_upstream_connect_attempts_per_request{bucket="1"} 40994
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21635
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17861
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 328
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1036
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 134
telemt_me_keepalive_timeout_total 58
telemt_me_reconnect_attempts_total 1710
telemt_me_reconnect_success_total 746
telemt_me_reader_eof_total 690
telemt_me_idle_close_by_peer_total 690
telemt_me_route_drop_no_conn_total 1951008
telemt_me_route_drop_channel_closed_total 93
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4076599
telemt_me_endpoint_quarantine_total 574
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 635
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 32
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
telemt_desync_total 19031
telemt_desync_full_logged_total 6214
telemt_desync_suppressed_total 12817
telemt_desync_frames_bucket_total{bucket="1_2"} 4720
telemt_desync_frames_bucket_total{bucket="3_10"} 7218
telemt_desync_frames_bucket_total{bucket="gt_10"} 7093
telemt_pool_swap_total 91
telemt_pool_force_close_total 2682
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 332
telemt_me_draining_writers_reap_progress_total 28079
telemt_me_writer_removed_unexpected_total 660
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2397
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 26363
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2472
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 210
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 25397
telemt_me_writer_teardown_success_total{mode="normal"} 28760
telemt_me_writer_teardown_noop_total 28089
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 54660
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 55854
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 56229
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 56645
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 56826
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 56846
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 56849
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 56849
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 56849
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 56849
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 56849
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 56849
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 56849
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 21.099639
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 56849
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 332
telemt_me_refill_failed_total 53
telemt_me_writer_restored_same_endpoint_total 642
telemt_me_writer_restored_fallback_total 4
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 14
telemt_user_connections_total{user="hello"} 4078933
telemt_user_connections_current{user="hello"} 3419
telemt_user_octets_from_client{user="hello"} 119241782519 (111.05 GB)
telemt_user_octets_to_client{user="hello"} 1860199903683 (1.69 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 1310
telemt_user_unique_ips_recent_window{user="hello"} 409
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 85047.9 (23h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 18757527
telemt_connections_bad_total 1198686
telemt_connections_current 4343
telemt_connections_me_current 4343
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 524349
telemt_upstream_connect_attempt_total 174189
telemt_upstream_connect_success_total 157319
telemt_upstream_connect_fail_total 15497
telemt_upstream_connect_attempts_per_request{bucket="1"} 172816
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 112135
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35338
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1024
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8822
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15497
telemt_me_keepalive_timeout_total 398
telemt_me_reconnect_attempts_total 4643
telemt_me_reconnect_success_total 1730
telemt_me_reader_eof_total 1187
telemt_me_idle_close_by_peer_total 1186
telemt_me_route_drop_no_conn_total 38380951
telemt_me_route_drop_channel_closed_total 111
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 15443579
telemt_me_endpoint_quarantine_total 621
telemt_me_single_endpoint_outage_enter_total 98
telemt_me_single_endpoint_outage_exit_total 98
telemt_me_single_endpoint_outage_reconnect_attempt_total 216
telemt_me_single_endpoint_outage_reconnect_success_total 47
telemt_me_single_endpoint_quarantine_bypass_total 216
telemt_me_single_endpoint_shadow_rotate_total 658
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 49
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
telemt_desync_total 28700
telemt_desync_full_logged_total 8469
telemt_desync_suppressed_total 20231
telemt_desync_frames_bucket_total{bucket="1_2"} 6206
telemt_desync_frames_bucket_total{bucket="3_10"} 12759
telemt_desync_frames_bucket_total{bucket="gt_10"} 9735
telemt_pool_swap_total 87
telemt_pool_force_close_total 2906
telemt_pool_stale_pick_total 5
telemt_me_writer_close_signal_drop_total 655
telemt_me_draining_writers_reap_progress_total 26217
telemt_me_writer_removed_unexpected_total 1639
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3498
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 24100
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 16
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2458
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 448
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 23311
telemt_me_writer_teardown_success_total{mode="normal"} 27598
telemt_me_writer_teardown_noop_total 26234
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 48031
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 50093
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 51227
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 52615
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 53426
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 53744
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 53813
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 53815
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 53818
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 53823
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 53823
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 53827
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 53832
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 200.389742
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 53832
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 655
telemt_me_refill_failed_total 100
telemt_me_writer_restored_same_endpoint_total 1199
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 160
telemt_me_writer_removed_unexpected_minus_restored_total 429
telemt_user_connections_total{user="hello"} 15562481
telemt_user_connections_current{user="hello"} 4343
telemt_user_octets_from_client{user="hello"} 143365888707 (133.52 GB)
telemt_user_octets_to_client{user="hello"} 952609932207 (887.19 GB)
telemt_user_msgs_from_client{user="hello"} 352315
telemt_user_msgs_to_client{user="hello"} 633668
telemt_user_unique_ips_current{user="hello"} 1637
telemt_user_unique_ips_recent_window{user="hello"} 733
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 85015.3 (23h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5315650
telemt_connections_bad_total 514511
telemt_connections_current 3373
telemt_connections_me_current 3373
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 109649
telemt_upstream_connect_attempt_total 44178
telemt_upstream_connect_success_total 43714
telemt_upstream_connect_fail_total 382
telemt_upstream_connect_attempts_per_request{bucket="1"} 44096
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25302
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18087
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 324
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 382
telemt_me_reconnect_attempts_total 3495
telemt_me_reconnect_success_total 1212
telemt_me_reader_eof_total 1189
telemt_me_idle_close_by_peer_total 1189
telemt_me_route_drop_no_conn_total 2233623
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 36
telemt_me_route_drop_queue_full_profile_total{profile="high"} 36
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4121760
telemt_me_endpoint_quarantine_total 512
telemt_me_single_endpoint_outage_enter_total 13
telemt_me_single_endpoint_outage_exit_total 13
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 13
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 633
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 27
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
telemt_desync_total 20356
telemt_desync_full_logged_total 7073
telemt_desync_suppressed_total 13283
telemt_desync_frames_bucket_total{bucket="1_2"} 3910
telemt_desync_frames_bucket_total{bucket="3_10"} 7963
telemt_desync_frames_bucket_total{bucket="gt_10"} 8483
telemt_pool_swap_total 86
telemt_pool_force_close_total 2532
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 312
telemt_me_draining_writers_reap_progress_total 28860
telemt_me_writer_removed_unexpected_total 1151
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2929
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 27095
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2185
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 347
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26328
telemt_me_writer_teardown_success_total{mode="normal"} 30024
telemt_me_writer_teardown_noop_total 28861
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 57848
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 58528
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 58754
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 58853
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 58882
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 58885
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 58885
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 58885
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 58885
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 58885
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 58885
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 58885
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 58885
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 6.896410
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 58885
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 312
telemt_me_refill_failed_total 123
telemt_me_writer_restored_same_endpoint_total 1030
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 106
telemt_user_connections_total{user="hello"} 4112134
telemt_user_connections_current{user="hello"} 3373
telemt_user_octets_from_client{user="hello"} 109594214049 (102.07 GB)
telemt_user_octets_to_client{user="hello"} 1661504871871 (1.51 TB)
telemt_user_msgs_from_client{user="hello"} 59697
telemt_user_msgs_to_client{user="hello"} 266554
telemt_user_unique_ips_current{user="hello"} 1334
telemt_user_unique_ips_recent_window{user="hello"} 406
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 21851.2 (6h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2956614
telemt_connections_bad_total 110201
telemt_connections_current 2815
telemt_connections_me_current 2815
telemt_handshake_timeouts_total 1271843
telemt_upstream_connect_attempt_total 7042
telemt_upstream_connect_success_total 6941
telemt_upstream_connect_fail_total 95
telemt_upstream_connect_attempts_per_request{bucket="1"} 7036
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3061
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3832
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 95
telemt_me_reconnect_attempts_total 703
telemt_me_reconnect_success_total 203
telemt_me_reader_eof_total 190
telemt_me_idle_close_by_peer_total 190
telemt_me_route_drop_no_conn_total 879742
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1400489
telemt_me_endpoint_quarantine_total 108
telemt_me_single_endpoint_outage_enter_total 4
telemt_me_single_endpoint_outage_exit_total 4
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 165
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
telemt_me_writers_active_current 42
telemt_desync_total 7683
telemt_desync_full_logged_total 2527
telemt_desync_suppressed_total 5156
telemt_desync_frames_bucket_total{bucket="1_2"} 1361
telemt_desync_frames_bucket_total{bucket="3_10"} 2882
telemt_desync_frames_bucket_total{bucket="gt_10"} 3440
telemt_pool_swap_total 23
telemt_pool_force_close_total 738
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 70
telemt_me_draining_writers_reap_progress_total 6140
telemt_me_writer_removed_unexpected_total 187
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 574
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 5758
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 649
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 89
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 5402
telemt_me_writer_teardown_success_total{mode="normal"} 6332
telemt_me_writer_teardown_noop_total 6140
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 12224
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 12353
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 12396
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 12472
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 12472
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 12472
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 12472
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 12472
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 12472
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 12472
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 12472
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 12472
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 12472
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.958773
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 12472
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 70
telemt_me_refill_failed_total 29
telemt_me_writer_restored_same_endpoint_total 168
telemt_me_async_recovery_trigger_total 6
telemt_me_writer_removed_unexpected_minus_restored_total 19
telemt_user_connections_total{user="hello"} 1396771
telemt_user_connections_current{user="hello"} 2815
telemt_user_octets_from_client{user="hello"} 42836636704 (39.89 GB)
telemt_user_octets_to_client{user="hello"} 570114426984 (530.96 GB)
telemt_user_unique_ips_current{user="hello"} 1103
telemt_user_unique_ips_recent_window{user="hello"} 436
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 2822.8 (0h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 29945
telemt_connections_bad_total 104
telemt_connections_current 783
telemt_connections_me_current 783
telemt_handshake_timeouts_total 653
telemt_upstream_connect_attempt_total 1244
telemt_upstream_connect_success_total 1240
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 1244
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 501
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 718
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_reconnect_attempts_total 45
telemt_me_reconnect_success_total 15
telemt_me_reader_eof_total 15
telemt_me_idle_close_by_peer_total 15
telemt_me_route_drop_no_conn_total 8635
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 27780
telemt_me_endpoint_quarantine_total 17
telemt_me_single_endpoint_shadow_rotate_total 28
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
telemt_desync_total 151
telemt_desync_full_logged_total 40
telemt_desync_suppressed_total 111
telemt_desync_frames_bucket_total{bucket="1_2"} 65
telemt_desync_frames_bucket_total{bucket="3_10"} 51
telemt_desync_frames_bucket_total{bucket="gt_10"} 35
telemt_pool_swap_total 3
telemt_pool_force_close_total 58
telemt_me_writer_close_signal_drop_total 1
telemt_me_draining_writers_reap_progress_total 1019
telemt_me_writer_removed_unexpected_total 15
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 67
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 967
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 58
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 961
telemt_me_writer_teardown_success_total{mode="normal"} 1034
telemt_me_writer_teardown_noop_total 1019
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 2048
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 2053
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 2053
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 2053
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 2053
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 2053
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 2053
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 2053
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 2053
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 2053
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 2053
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 2053
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 2053
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.053192
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 2053
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1
telemt_me_refill_failed_total 2
telemt_me_writer_restored_same_endpoint_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 27752
telemt_user_connections_current{user="hello"} 783
telemt_user_octets_from_client{user="hello"} 873650064 (833.18 MB)
telemt_user_octets_to_client{user="hello"} 22720482444 (21.16 GB)
telemt_user_unique_ips_current{user="hello"} 285
telemt_user_unique_ips_recent_window{user="hello"} 101
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 85019.7 (23h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6300231
telemt_connections_bad_total 647183
telemt_connections_current 4363
telemt_connections_me_current 4363
telemt_handshake_timeouts_total 183593
telemt_upstream_connect_attempt_total 32382
telemt_upstream_connect_success_total 32252
telemt_upstream_connect_fail_total 93
telemt_upstream_connect_attempts_per_request{bucket="1"} 32345
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15954
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16259
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 93
telemt_me_reconnect_attempts_total 1359
telemt_me_reconnect_success_total 697
telemt_me_reader_eof_total 670
telemt_me_idle_close_by_peer_total 670
telemt_me_route_drop_no_conn_total 1952661
telemt_me_route_drop_channel_closed_total 51
telemt_me_route_drop_queue_full_total 21
telemt_me_route_drop_queue_full_profile_total{profile="high"} 21
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4833697
telemt_me_endpoint_quarantine_total 567
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 647
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 27
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
telemt_desync_total 18211
telemt_desync_full_logged_total 6036
telemt_desync_suppressed_total 12175
telemt_desync_frames_bucket_total{bucket="1_2"} 4453
telemt_desync_frames_bucket_total{bucket="3_10"} 6658
telemt_desync_frames_bucket_total{bucket="gt_10"} 7100
telemt_pool_swap_total 94
telemt_pool_force_close_total 2560
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 321
telemt_me_draining_writers_reap_progress_total 29061
telemt_me_writer_removed_unexpected_total 654
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2360
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 27361
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2485
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 75
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26501
telemt_me_writer_teardown_success_total{mode="normal"} 29721
telemt_me_writer_teardown_noop_total 29063
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 57613
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 58374
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 58517
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 58696
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 58784
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 58784
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 58784
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 58784
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 58784
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 58784
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 58784
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 58784
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 58784
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 9.493786
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 58784
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 321
telemt_me_refill_failed_total 34
telemt_me_writer_restored_same_endpoint_total 623
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 26
telemt_user_connections_total{user="hello"} 4809841
telemt_user_connections_current{user="hello"} 4363
telemt_user_octets_from_client{user="hello"} 95888625900 (89.30 GB)
telemt_user_octets_to_client{user="hello"} 2230149117640 (2.03 TB)
telemt_user_unique_ips_current{user="hello"} 1493
telemt_user_unique_ips_recent_window{user="hello"} 482
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 85016.4 (23h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5318531
telemt_connections_bad_total 495100
telemt_connections_current 3371
telemt_connections_me_current 3371
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 153390
telemt_upstream_connect_attempt_total 48743
telemt_upstream_connect_success_total 48384
telemt_upstream_connect_fail_total 300
telemt_upstream_connect_attempts_per_request{bucket="1"} 48684
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29162
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18090
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 614
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 300
telemt_me_reconnect_attempts_total 4473
telemt_me_reconnect_success_total 982
telemt_me_reader_eof_total 871
telemt_me_idle_close_by_peer_total 871
telemt_me_seq_mismatch_total 36
telemt_me_route_drop_no_conn_total 2005454
telemt_me_route_drop_channel_closed_total 186
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4206439
telemt_me_endpoint_quarantine_total 678
telemt_me_single_endpoint_outage_enter_total 25
telemt_me_single_endpoint_outage_exit_total 25
telemt_me_single_endpoint_outage_reconnect_attempt_total 25
telemt_me_single_endpoint_outage_reconnect_success_total 24
telemt_me_single_endpoint_quarantine_bypass_total 25
telemt_me_single_endpoint_shadow_rotate_total 648
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 28
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
telemt_me_writers_active_current 44
telemt_desync_total 16912
telemt_desync_full_logged_total 5726
telemt_desync_suppressed_total 11186
telemt_desync_frames_bucket_total{bucket="1_2"} 4168
telemt_desync_frames_bucket_total{bucket="3_10"} 6225
telemt_desync_frames_bucket_total{bucket="gt_10"} 6519
telemt_pool_swap_total 92
telemt_pool_force_close_total 2490
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 320
telemt_me_draining_writers_reap_progress_total 28263
telemt_me_writer_removed_unexpected_total 882
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2838
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 26346
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2298
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 192
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 25773
telemt_me_writer_teardown_success_total{mode="normal"} 29184
telemt_me_writer_teardown_noop_total 28265
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 56075
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 56971
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 57236
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 57417
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 57449
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 57449
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 57449
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 57449
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 57449
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 57449
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 57449
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 57449
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 57449
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 9.354197
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 57449
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 320
telemt_me_refill_failed_total 199
telemt_me_writer_restored_same_endpoint_total 758
telemt_me_writer_restored_fallback_total 46
telemt_me_async_recovery_trigger_total 59
telemt_me_writer_removed_unexpected_minus_restored_total 78
telemt_user_connections_total{user="hello"} 4211243
telemt_user_connections_current{user="hello"} 3371
telemt_user_octets_from_client{user="hello"} 79554891133 (74.09 GB)
telemt_user_octets_to_client{user="hello"} 1758625065768 (1.60 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1289
telemt_user_unique_ips_recent_window{user="hello"} 456
```