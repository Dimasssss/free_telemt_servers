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

# Server Metrics 2026-03-22 20:51:09 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 85484.4 (23h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3154963
telemt_connections_bad_total 222012
telemt_connections_current 1099
telemt_connections_me_current 1099
telemt_handshake_timeouts_total 100697
telemt_upstream_connect_attempt_total 31286
telemt_upstream_connect_success_total 31285
telemt_upstream_connect_attempts_per_request{bucket="1"} 31285
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10766
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20398
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 86
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 225
telemt_me_reconnect_attempts_total 1274
telemt_me_reconnect_success_total 522
telemt_me_reader_eof_total 531
telemt_me_idle_close_by_peer_total 531
telemt_me_route_drop_no_conn_total 2812620
telemt_me_route_drop_channel_closed_total 1130
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2663902
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_endpoint_quarantine_total 576
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 661
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
telemt_me_writers_active_current 47
telemt_desync_total 11515
telemt_desync_full_logged_total 3608
telemt_desync_suppressed_total 7907
telemt_desync_frames_bucket_total{bucket="1_2"} 3108
telemt_desync_frames_bucket_total{bucket="3_10"} 4219
telemt_desync_frames_bucket_total{bucket="gt_10"} 4188
telemt_pool_swap_total 94
telemt_pool_force_close_total 2936
telemt_pool_stale_pick_total 22
telemt_me_writer_close_signal_drop_total 601
telemt_me_draining_writers_reap_progress_total 28616
telemt_me_writer_removed_unexpected_total 516
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2081
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 26755
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2882
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 54
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 25680
telemt_me_writer_teardown_success_total{mode="normal"} 28836
telemt_me_writer_teardown_noop_total 28627
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 45184
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 47302
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 49323
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 53047
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 55682
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 57028
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 57458
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 57463
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 57463
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 57463
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 57463
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 57463
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 57463
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 329.482030
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 57463
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 601
telemt_me_refill_failed_total 40
telemt_me_writer_restored_same_endpoint_total 463
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 52
telemt_user_connections_total{user="hello"} 2654865
telemt_user_connections_current{user="hello"} 1099
telemt_user_octets_from_client{user="hello"} 38834890260 (36.17 GB)
telemt_user_octets_to_client{user="hello"} 709644576108 (660.91 GB)
telemt_user_unique_ips_current{user="hello"} 445
telemt_user_unique_ips_recent_window{user="hello"} 140
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 98850.7 (27h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3876498
telemt_connections_bad_total 342582
telemt_connections_current 868
telemt_connections_me_current 868
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 98616
telemt_upstream_connect_attempt_total 59530
telemt_upstream_connect_success_total 58803
telemt_upstream_connect_fail_total 642
telemt_upstream_connect_attempts_per_request{bucket="1"} 59445
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32868
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25747
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 188
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 642
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 6850
telemt_me_reconnect_success_total 2677
telemt_me_reader_eof_total 2625
telemt_me_idle_close_by_peer_total 2625
telemt_me_route_drop_no_conn_total 3618107
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3090117
telemt_me_endpoint_quarantine_total 752
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 39
telemt_me_single_endpoint_outage_exit_total 39
telemt_me_single_endpoint_outage_reconnect_attempt_total 39
telemt_me_single_endpoint_outage_reconnect_success_total 38
telemt_me_single_endpoint_quarantine_bypass_total 39
telemt_me_single_endpoint_shadow_rotate_total 760
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
telemt_me_writers_active_current 44
telemt_desync_total 12465
telemt_desync_full_logged_total 6979
telemt_desync_suppressed_total 5486
telemt_desync_frames_bucket_total{bucket="1_2"} 2832
telemt_desync_frames_bucket_total{bucket="3_10"} 4888
telemt_desync_frames_bucket_total{bucket="gt_10"} 4745
telemt_pool_swap_total 92
telemt_pool_force_close_total 2802
telemt_pool_stale_pick_total 6
telemt_me_writer_close_signal_drop_total 234
telemt_me_draining_writers_reap_progress_total 39379
telemt_me_writer_removed_unexpected_total 2568
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4812
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 37155
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2375
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 427
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 36577
telemt_me_writer_teardown_success_total{mode="normal"} 41967
telemt_me_writer_teardown_noop_total 39380
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 79409
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 80636
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 80961
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 81269
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 81332
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 81345
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 81347
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 81347
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 81347
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 81347
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 81347
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 81347
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 81347
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.350835
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 81347
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 234
telemt_me_refill_failed_total 166
telemt_me_writer_restored_same_endpoint_total 2359
telemt_me_writer_restored_fallback_total 25
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 184
telemt_user_connections_total{user="hello"} 3100826
telemt_user_connections_current{user="hello"} 868
telemt_user_octets_from_client{user="hello"} 40706995371 (37.91 GB)
telemt_user_octets_to_client{user="hello"} 751434832822 (699.83 GB)
telemt_user_msgs_from_client{user="hello"} 42816
telemt_user_msgs_to_client{user="hello"} 172415
telemt_user_unique_ips_current{user="hello"} 501
telemt_user_unique_ips_recent_window{user="hello"} 149
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 173710.6 (48h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16037425
telemt_connections_bad_total 1554262
telemt_connections_current 1582
telemt_connections_me_current 1582
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 393968
telemt_upstream_connect_attempt_total 77012
telemt_upstream_connect_success_total 76912
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 76929
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 38223
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36991
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1691
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2823
telemt_me_reconnect_success_total 1459
telemt_me_reader_eof_total 1403
telemt_me_idle_close_by_peer_total 1401
telemt_me_route_drop_no_conn_total 14000447
telemt_me_route_drop_channel_closed_total 144
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12781963
telemt_me_endpoint_quarantine_total 1098
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 1293
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
telemt_me_writers_active_current 46
telemt_desync_total 52756
telemt_desync_full_logged_total 16634
telemt_desync_suppressed_total 36122
telemt_desync_frames_bucket_total{bucket="1_2"} 11743
telemt_desync_frames_bucket_total{bucket="3_10"} 20544
telemt_desync_frames_bucket_total{bucket="gt_10"} 20469
telemt_pool_swap_total 187
telemt_pool_force_close_total 6303
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 1020
telemt_me_draining_writers_reap_progress_total 57078
telemt_me_writer_removed_unexpected_total 1354
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4992
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 52718
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 43
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5833
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 470
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 50775
telemt_me_writer_teardown_success_total{mode="normal"} 57710
telemt_me_writer_teardown_noop_total 57129
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 104058
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 107547
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 109237
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 111532
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 113186
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 114234
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 114800
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 114830
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 114831
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 114835
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 114837
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 114839
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 114839
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 313.767145
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 114839
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1020
telemt_me_refill_failed_total 75
telemt_me_writer_restored_same_endpoint_total 1259
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 88
telemt_user_connections_total{user="hello"} 12782356
telemt_user_connections_current{user="hello"} 1582
telemt_user_octets_from_client{user="hello"} 187440700889 (174.57 GB)
telemt_user_octets_to_client{user="hello"} 3414763155239 (3.11 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 736
telemt_user_unique_ips_recent_window{user="hello"} 160
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 173712.1 (48h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11617383
telemt_connections_bad_total 1168464
telemt_connections_current 1097
telemt_connections_me_current 1097
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 343350
telemt_upstream_connect_attempt_total 91488
telemt_upstream_connect_success_total 90201
telemt_upstream_connect_fail_total 857
telemt_upstream_connect_attempts_per_request{bucket="1"} 91058
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 49240
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36997
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 187
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3777
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 857
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 187
telemt_me_reconnect_attempts_total 4264
telemt_me_reconnect_success_total 1774
telemt_me_reader_eof_total 1631
telemt_me_idle_close_by_peer_total 1631
telemt_me_route_drop_no_conn_total 4516941
telemt_me_route_drop_channel_closed_total 496
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8653249
telemt_me_endpoint_quarantine_total 1101
telemt_me_single_endpoint_outage_enter_total 29
telemt_me_single_endpoint_outage_exit_total 29
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 27
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 1314
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 46
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
telemt_desync_total 38324
telemt_desync_full_logged_total 12892
telemt_desync_suppressed_total 25432
telemt_desync_frames_bucket_total{bucket="1_2"} 9456
telemt_desync_frames_bucket_total{bucket="3_10"} 14739
telemt_desync_frames_bucket_total{bucket="gt_10"} 14129
telemt_pool_swap_total 184
telemt_pool_force_close_total 5673
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 704
telemt_me_draining_writers_reap_progress_total 55450
telemt_me_writer_removed_unexpected_total 1670
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5146
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 51821
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5161
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 512
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 49777
telemt_me_writer_teardown_success_total{mode="normal"} 56967
telemt_me_writer_teardown_noop_total 55475
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 105772
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 108937
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 110077
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 111263
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 112018
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 112357
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 112432
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 112434
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 112440
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 112442
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 112442
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 112442
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 112442
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 103.769515
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 112442
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 704
telemt_me_refill_failed_total 134
telemt_me_writer_restored_same_endpoint_total 1507
telemt_me_writer_restored_fallback_total 20
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 143
telemt_user_connections_total{user="hello"} 8593223
telemt_user_connections_current{user="hello"} 1097
telemt_user_octets_from_client{user="hello"} 216080291152 (201.24 GB)
telemt_user_octets_to_client{user="hello"} 3886729758431 (3.53 TB)
telemt_user_msgs_from_client{user="hello"} 124042
telemt_user_msgs_to_client{user="hello"} 140191
telemt_user_unique_ips_current{user="hello"} 454
telemt_user_unique_ips_recent_window{user="hello"} 142
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 173677.6 (48h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10882587
telemt_connections_bad_total 943352
telemt_connections_current 1092
telemt_connections_me_current 1092
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 344409
telemt_upstream_connect_attempt_total 75083
telemt_upstream_connect_success_total 73802
telemt_upstream_connect_fail_total 191
telemt_upstream_connect_attempts_per_request{bucket="1"} 73993
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34462
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35367
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1718
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2255
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 191
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 1411
telemt_me_reconnect_attempts_total 5202
telemt_me_reconnect_success_total 2141
telemt_me_reader_eof_total 1879
telemt_me_idle_close_by_peer_total 1878
telemt_me_route_drop_no_conn_total 5296448
telemt_me_route_drop_channel_closed_total 379
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8233887
telemt_me_endpoint_quarantine_total 1176
telemt_me_single_endpoint_outage_enter_total 36
telemt_me_single_endpoint_outage_exit_total 36
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 31
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 1270
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 65
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
telemt_me_writers_active_current 93
telemt_desync_total 37775
telemt_desync_full_logged_total 12513
telemt_desync_suppressed_total 25262
telemt_desync_frames_bucket_total{bucket="1_2"} 9543
telemt_desync_frames_bucket_total{bucket="3_10"} 14446
telemt_desync_frames_bucket_total{bucket="gt_10"} 13786
telemt_pool_swap_total 181
telemt_pool_force_close_total 5609
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 716
telemt_me_draining_writers_reap_progress_total 55662
telemt_me_writer_removed_unexpected_total 2025
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5687
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 51922
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5058
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 551
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 50053
telemt_me_writer_teardown_success_total{mode="normal"} 57609
telemt_me_writer_teardown_noop_total 55733
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 107590
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 110262
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 111205
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 112266
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 112861
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 113075
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 113203
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 113234
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 113242
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 113255
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 113288
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 113291
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 113342
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3174.045750
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 113342
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 716
telemt_me_refill_failed_total 162
telemt_me_writer_restored_same_endpoint_total 1849
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 162
telemt_user_connections_total{user="hello"} 8225996
telemt_user_connections_current{user="hello"} 1092
telemt_user_octets_from_client{user="hello"} 191580380497 (178.42 GB)
telemt_user_octets_to_client{user="hello"} 3422404921409 (3.11 TB)
telemt_user_msgs_from_client{user="hello"} 46485
telemt_user_msgs_to_client{user="hello"} 113805
telemt_user_unique_ips_current{user="hello"} 448
telemt_user_unique_ips_recent_window{user="hello"} 103
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 43956.0 (12h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10922096
telemt_connections_bad_total 661574
telemt_connections_current 1646
telemt_connections_me_current 1646
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 239899
telemt_upstream_connect_attempt_total 49321
telemt_upstream_connect_success_total 46823
telemt_upstream_connect_fail_total 1726
telemt_upstream_connect_attempts_per_request{bucket="1"} 48549
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24133
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15192
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1516
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5982
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1726
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 6875
telemt_me_reconnect_success_total 989
telemt_me_reader_eof_total 601
telemt_me_idle_close_by_peer_total 601
telemt_me_route_drop_no_conn_total 25227877
telemt_me_route_drop_channel_closed_total 54
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9070683
telemt_me_endpoint_quarantine_total 299
telemt_me_single_endpoint_outage_enter_total 75
telemt_me_single_endpoint_outage_exit_total 75
telemt_me_single_endpoint_outage_reconnect_attempt_total 134
telemt_me_single_endpoint_outage_reconnect_success_total 40
telemt_me_single_endpoint_quarantine_bypass_total 134
telemt_me_single_endpoint_shadow_rotate_total 349
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
telemt_me_writers_active_current 43
telemt_desync_total 14979
telemt_desync_full_logged_total 3973
telemt_desync_suppressed_total 11006
telemt_desync_frames_bucket_total{bucket="1_2"} 2820
telemt_desync_frames_bucket_total{bucket="3_10"} 6076
telemt_desync_frames_bucket_total{bucket="gt_10"} 6083
telemt_pool_swap_total 44
telemt_pool_force_close_total 1587
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 445
telemt_me_draining_writers_reap_progress_total 12661
telemt_me_writer_removed_unexpected_total 884
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1902
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 11595
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1285
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 302
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 11074
telemt_me_writer_teardown_success_total{mode="normal"} 13497
telemt_me_writer_teardown_noop_total 12680
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 22558
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 24159
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 24800
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 25632
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 25998
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 26121
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 26177
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 26177
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 26177
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 26177
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 26177
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 26177
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 26177
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 51.958738
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 26177
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 445
telemt_me_refill_failed_total 320
telemt_me_writer_restored_same_endpoint_total 644
telemt_me_writer_restored_fallback_total 6
telemt_me_no_writer_failfast_total 96
telemt_me_async_recovery_trigger_total 3149
telemt_me_writer_removed_unexpected_minus_restored_total 234
telemt_user_connections_total{user="hello"} 9095457
telemt_user_connections_current{user="hello"} 1646
telemt_user_octets_from_client{user="hello"} 84312213924 (78.52 GB)
telemt_user_octets_to_client{user="hello"} 523638001698 (487.68 GB)
telemt_user_msgs_from_client{user="hello"} 65206
telemt_user_msgs_to_client{user="hello"} 53386
telemt_user_unique_ips_current{user="hello"} 614
telemt_user_unique_ips_recent_window{user="hello"} 201
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 173682.6 (48h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10775485
telemt_connections_bad_total 909472
telemt_connections_current 1326
telemt_connections_me_current 1326
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 237407
telemt_upstream_connect_attempt_total 104114
telemt_upstream_connect_success_total 103023
telemt_upstream_connect_fail_total 930
telemt_upstream_connect_attempts_per_request{bucket="1"} 103953
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 62527
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 38912
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1346
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 930
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 72440
telemt_me_reconnect_success_total 2845
telemt_me_reader_eof_total 2538
telemt_me_idle_close_by_peer_total 2536
telemt_me_route_drop_no_conn_total 5217573
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8514403
telemt_me_endpoint_quarantine_total 1144
telemt_me_single_endpoint_outage_enter_total 39
telemt_me_single_endpoint_outage_exit_total 39
telemt_me_single_endpoint_outage_reconnect_attempt_total 41
telemt_me_single_endpoint_outage_reconnect_success_total 39
telemt_me_single_endpoint_quarantine_bypass_total 41
telemt_me_single_endpoint_shadow_rotate_total 1297
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 51
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
telemt_desync_total 45407
telemt_desync_full_logged_total 15491
telemt_desync_suppressed_total 29916
telemt_desync_frames_bucket_total{bucket="1_2"} 9213
telemt_desync_frames_bucket_total{bucket="3_10"} 17394
telemt_desync_frames_bucket_total{bucket="gt_10"} 18800
telemt_pool_swap_total 177
telemt_pool_force_close_total 5287
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 643
telemt_me_draining_writers_reap_progress_total 59541
telemt_me_writer_removed_unexpected_total 2575
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6296
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 55847
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4557
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 730
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 54254
telemt_me_writer_teardown_success_total{mode="normal"} 62143
telemt_me_writer_teardown_noop_total 59542
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 119575
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 120950
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 121368
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 121641
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 121675
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 121678
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 121678
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 121681
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 121685
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 121685
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 121685
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 121685
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 121685
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.066525
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 121685
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 643
telemt_me_refill_failed_total 4287
telemt_me_writer_restored_same_endpoint_total 2394
telemt_me_writer_restored_fallback_total 48
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7367
telemt_me_writer_removed_unexpected_minus_restored_total 133
telemt_user_connections_total{user="hello"} 8517612
telemt_user_connections_current{user="hello"} 1326
telemt_user_octets_from_client{user="hello"} 192837884553 (179.59 GB)
telemt_user_octets_to_client{user="hello"} 3243755799036 (2.95 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 558
telemt_user_unique_ips_recent_window{user="hello"} 145
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 110518.8 (30h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11383555
telemt_connections_bad_total 455814
telemt_connections_current 1105
telemt_connections_me_current 1105
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4670112
telemt_upstream_connect_attempt_total 52258
telemt_upstream_connect_success_total 51867
telemt_upstream_connect_fail_total 381
telemt_upstream_connect_attempts_per_request{bucket="1"} 52248
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28333
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23334
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 200
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 381
telemt_me_reconnect_attempts_total 48601
telemt_me_reconnect_success_total 1690
telemt_me_reader_eof_total 1348
telemt_me_idle_close_by_peer_total 1347
telemt_me_route_drop_no_conn_total 4052108
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5488150
telemt_me_endpoint_quarantine_total 713
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 59
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 59
telemt_me_single_endpoint_shadow_rotate_total 833
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
telemt_me_writers_active_current 45
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 30857
telemt_desync_full_logged_total 10483
telemt_desync_suppressed_total 20374
telemt_desync_frames_bucket_total{bucket="1_2"} 6133
telemt_desync_frames_bucket_total{bucket="3_10"} 12209
telemt_desync_frames_bucket_total{bucket="gt_10"} 12515
telemt_pool_swap_total 116
telemt_pool_force_close_total 3534
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 356
telemt_me_draining_writers_reap_progress_total 38532
telemt_me_writer_removed_unexpected_total 1408
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3382
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 36592
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3093
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 441
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 34998
telemt_me_writer_teardown_success_total{mode="normal"} 39974
telemt_me_writer_teardown_noop_total 38539
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 77248
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 77982
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 78286
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 78513
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 78513
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 78513
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 78513
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 78513
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 78513
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 78513
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 78513
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 78513
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 78513
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.532209
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 78513
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 356
telemt_me_refill_failed_total 2726
telemt_me_writer_restored_same_endpoint_total 1502
telemt_me_writer_restored_fallback_total 19
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4332
telemt_user_connections_total{user="hello"} 5480910
telemt_user_connections_current{user="hello"} 1105
telemt_user_octets_from_client{user="hello"} 117685270516 (109.60 GB)
telemt_user_octets_to_client{user="hello"} 2102121204394 (1.91 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 459
telemt_user_unique_ips_recent_window{user="hello"} 155
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 91489.7 (25h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1387503
telemt_connections_bad_total 34381
telemt_connections_current 860
telemt_connections_me_current 860
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 25785
telemt_upstream_connect_attempt_total 43073
telemt_upstream_connect_success_total 42941
telemt_upstream_connect_fail_total 105
telemt_upstream_connect_attempts_per_request{bucket="1"} 43046
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19367
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22834
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 740
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 105
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2040
telemt_me_reconnect_success_total 827
telemt_me_reader_eof_total 809
telemt_me_idle_close_by_peer_total 809
telemt_me_route_drop_no_conn_total 483994
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1230504
telemt_me_endpoint_quarantine_total 753
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 753
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 16
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
telemt_desync_total 7520
telemt_desync_full_logged_total 2321
telemt_desync_suppressed_total 5199
telemt_desync_frames_bucket_total{bucket="1_2"} 1695
telemt_desync_frames_bucket_total{bucket="3_10"} 2914
telemt_desync_frames_bucket_total{bucket="gt_10"} 2911
telemt_pool_swap_total 98
telemt_pool_force_close_total 2549
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 147
telemt_me_draining_writers_reap_progress_total 35919
telemt_me_writer_removed_unexpected_total 779
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2839
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 33892
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2462
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 87
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 33370
telemt_me_writer_teardown_success_total{mode="normal"} 36731
telemt_me_writer_teardown_noop_total 35923
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 71828
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 72427
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 72617
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 72654
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 72654
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 72654
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 72654
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 72654
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 72654
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 72654
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 72654
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 72654
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 72654
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.555858
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 72654
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 147
telemt_me_refill_failed_total 67
telemt_me_writer_restored_same_endpoint_total 701
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 60
telemt_user_connections_total{user="hello"} 1226524
telemt_user_connections_current{user="hello"} 860
telemt_user_octets_from_client{user="hello"} 23871636789 (22.23 GB)
telemt_user_octets_to_client{user="hello"} 519415673667 (483.74 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 311
telemt_user_unique_ips_recent_window{user="hello"} 121
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 173687.1 (48h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13099989
telemt_connections_bad_total 1538954
telemt_connections_current 1302
telemt_connections_me_current 1302
telemt_handshake_timeouts_total 375672
telemt_upstream_connect_attempt_total 65812
telemt_upstream_connect_success_total 65480
telemt_upstream_connect_fail_total 197
telemt_upstream_connect_attempts_per_request{bucket="1"} 65677
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32442
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32938
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 197
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2575
telemt_me_reconnect_success_total 1352
telemt_me_reader_eof_total 1319
telemt_me_idle_close_by_peer_total 1319
telemt_me_route_drop_no_conn_total 4449825
telemt_me_route_drop_channel_closed_total 123
telemt_me_route_drop_queue_full_total 41
telemt_me_route_drop_queue_full_profile_total{profile="high"} 41
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9910100
telemt_me_endpoint_quarantine_total 1168
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 1300
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 42
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
telemt_desync_total 41179
telemt_desync_full_logged_total 13425
telemt_desync_suppressed_total 27754
telemt_desync_frames_bucket_total{bucket="1_2"} 9857
telemt_desync_frames_bucket_total{bucket="3_10"} 15187
telemt_desync_frames_bucket_total{bucket="gt_10"} 16135
telemt_pool_swap_total 192
telemt_pool_force_close_total 5272
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 654
telemt_me_draining_writers_reap_progress_total 59313
telemt_me_writer_removed_unexpected_total 1269
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4823
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 55799
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5098
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 54041
telemt_me_writer_teardown_success_total{mode="normal"} 60622
telemt_me_writer_teardown_noop_total 59315
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 117380
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 119045
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 119428
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 119804
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 119924
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 119937
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 119937
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 119937
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 119937
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 119937
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 119937
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 119937
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 119937
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.525101
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 119937
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 654
telemt_me_refill_failed_total 65
telemt_me_writer_restored_same_endpoint_total 1183
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 71
telemt_user_connections_total{user="hello"} 9877031
telemt_user_connections_current{user="hello"} 1302
telemt_user_octets_from_client{user="hello"} 192959567912 (179.71 GB)
telemt_user_octets_to_client{user="hello"} 4367977067352 (3.97 TB)
telemt_user_unique_ips_current{user="hello"} 488
telemt_user_unique_ips_recent_window{user="hello"} 150
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 173683.9 (48h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11393477
telemt_connections_bad_total 1289275
telemt_connections_current 1136
telemt_connections_me_current 1136
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 299936
telemt_upstream_connect_attempt_total 92255
telemt_upstream_connect_success_total 91424
telemt_upstream_connect_fail_total 624
telemt_upstream_connect_attempts_per_request{bucket="1"} 92048
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 49974
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 38472
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2065
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 624
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 9921
telemt_me_reconnect_success_total 2385
telemt_me_reader_eof_total 2229
telemt_me_idle_close_by_peer_total 2228
telemt_me_seq_mismatch_total 79
telemt_me_route_drop_no_conn_total 5611064
telemt_me_route_drop_channel_closed_total 354
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8812919
telemt_me_endpoint_quarantine_total 1328
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 48
telemt_me_single_endpoint_outage_exit_total 48
telemt_me_single_endpoint_outage_reconnect_attempt_total 48
telemt_me_single_endpoint_outage_reconnect_success_total 46
telemt_me_single_endpoint_quarantine_bypass_total 48
telemt_me_single_endpoint_shadow_rotate_total 1299
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 54
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
telemt_me_writers_active_current 41
telemt_desync_total 40372
telemt_desync_full_logged_total 13045
telemt_desync_suppressed_total 27327
telemt_desync_frames_bucket_total{bucket="1_2"} 10089
telemt_desync_frames_bucket_total{bucket="3_10"} 14986
telemt_desync_frames_bucket_total{bucket="gt_10"} 15297
telemt_pool_swap_total 182
telemt_pool_force_close_total 5069
telemt_pool_stale_pick_total 360
telemt_me_writer_close_signal_drop_total 640
telemt_me_draining_writers_reap_progress_total 59072
telemt_me_writer_removed_unexpected_total 2261
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6168
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 55241
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4598
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 471
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 54003
telemt_me_writer_teardown_success_total{mode="normal"} 61409
telemt_me_writer_teardown_noop_total 59077
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 117831
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 119581
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 120117
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 120436
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 120486
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 120486
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 120486
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 120486
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 120486
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 120486
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 120486
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 120486
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 120486
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.232557
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 120486
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 640
telemt_me_refill_failed_total 389
telemt_me_writer_restored_same_endpoint_total 1943
telemt_me_writer_restored_fallback_total 109
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 133
telemt_me_writer_removed_unexpected_minus_restored_total 209
telemt_user_connections_total{user="hello"} 8818426
telemt_user_connections_current{user="hello"} 1136
telemt_user_octets_from_client{user="hello"} 156022406901 (145.31 GB)
telemt_user_octets_to_client{user="hello"} 3419126205987 (3.11 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 449
telemt_user_unique_ips_recent_window{user="hello"} 152
```