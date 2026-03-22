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

# Server Metrics 2026-03-22 20:25:24 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 83937.7 (23h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3112070
telemt_connections_bad_total 214754
telemt_connections_current 990
telemt_connections_me_current 990
telemt_handshake_timeouts_total 99450
telemt_upstream_connect_attempt_total 30775
telemt_upstream_connect_success_total 30774
telemt_upstream_connect_attempts_per_request{bucket="1"} 30774
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10617
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20043
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 83
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 31
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 225
telemt_me_reconnect_attempts_total 1236
telemt_me_reconnect_success_total 517
telemt_me_reader_eof_total 525
telemt_me_idle_close_by_peer_total 525
telemt_me_route_drop_no_conn_total 2793391
telemt_me_route_drop_channel_closed_total 1112
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2632024
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_endpoint_quarantine_total 570
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 650
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
telemt_me_writers_active_current 42
telemt_desync_total 11256
telemt_desync_full_logged_total 3561
telemt_desync_suppressed_total 7695
telemt_desync_frames_bucket_total{bucket="1_2"} 3014
telemt_desync_frames_bucket_total{bucket="3_10"} 4156
telemt_desync_frames_bucket_total{bucket="gt_10"} 4086
telemt_pool_swap_total 93
telemt_pool_force_close_total 2907
telemt_pool_stale_pick_total 22
telemt_me_writer_close_signal_drop_total 597
telemt_me_draining_writers_reap_progress_total 28164
telemt_me_writer_removed_unexpected_total 509
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2053
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 26324
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2853
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 54
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 25257
telemt_me_writer_teardown_success_total{mode="normal"} 28377
telemt_me_writer_teardown_noop_total 28175
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 44410
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 46505
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 48519
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 52196
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 54793
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 56119
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 56547
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 56552
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 56552
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 56552
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 56552
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 56552
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 56552
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 325.500906
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 56552
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 597
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 458
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 50
telemt_user_connections_total{user="hello"} 2623465
telemt_user_connections_current{user="hello"} 990
telemt_user_octets_from_client{user="hello"} 38462489100 (35.82 GB)
telemt_user_octets_to_client{user="hello"} 693602604272 (645.97 GB)
telemt_user_unique_ips_current{user="hello"} 404
telemt_user_unique_ips_recent_window{user="hello"} 129
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 97303.8 (27h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3854046
telemt_connections_bad_total 340931
telemt_connections_current 936
telemt_connections_me_current 936
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 98303
telemt_upstream_connect_attempt_total 58870
telemt_upstream_connect_success_total 58146
telemt_upstream_connect_fail_total 640
telemt_upstream_connect_attempts_per_request{bucket="1"} 58786
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32568
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25390
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 188
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 640
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 6819
telemt_me_reconnect_success_total 2659
telemt_me_reader_eof_total 2610
telemt_me_idle_close_by_peer_total 2610
telemt_me_route_drop_no_conn_total 3612084
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3070783
telemt_me_endpoint_quarantine_total 739
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 39
telemt_me_single_endpoint_outage_exit_total 39
telemt_me_single_endpoint_outage_reconnect_attempt_total 39
telemt_me_single_endpoint_outage_reconnect_success_total 38
telemt_me_single_endpoint_quarantine_bypass_total 39
telemt_me_single_endpoint_shadow_rotate_total 748
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
telemt_me_writers_active_current 46
telemt_me_writers_warm_current 32
telemt_desync_total 12333
telemt_desync_full_logged_total 6897
telemt_desync_suppressed_total 5436
telemt_desync_frames_bucket_total{bucket="1_2"} 2813
telemt_desync_frames_bucket_total{bucket="3_10"} 4832
telemt_desync_frames_bucket_total{bucket="gt_10"} 4688
telemt_pool_swap_total 90
telemt_pool_force_close_total 2746
telemt_pool_stale_pick_total 6
telemt_me_writer_close_signal_drop_total 232
telemt_me_draining_writers_reap_progress_total 38744
telemt_me_writer_removed_unexpected_total 2554
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4756
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 36561
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2321
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 425
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 35998
telemt_me_writer_teardown_success_total{mode="normal"} 41317
telemt_me_writer_teardown_noop_total 38745
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 78142
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 79364
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 79676
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 79984
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 80047
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 80060
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 80062
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 80062
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 80062
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 80062
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 80062
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 80062
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 80062
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.256770
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 80062
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 232
telemt_me_refill_failed_total 166
telemt_me_writer_restored_same_endpoint_total 2346
telemt_me_writer_restored_fallback_total 25
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 183
telemt_user_connections_total{user="hello"} 3081538
telemt_user_connections_current{user="hello"} 936
telemt_user_octets_from_client{user="hello"} 40472334123 (37.69 GB)
telemt_user_octets_to_client{user="hello"} 740340897974 (689.50 GB)
telemt_user_msgs_from_client{user="hello"} 42816
telemt_user_msgs_to_client{user="hello"} 172415
telemt_user_unique_ips_current{user="hello"} 561
telemt_user_unique_ips_recent_window{user="hello"} 142
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 172163.6 (47h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15994548
telemt_connections_bad_total 1550269
telemt_connections_current 1463
telemt_connections_me_current 1463
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 393175
telemt_upstream_connect_attempt_total 76442
telemt_upstream_connect_success_total 76344
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 76361
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37988
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36660
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1689
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2810
telemt_me_reconnect_success_total 1447
telemt_me_reader_eof_total 1390
telemt_me_idle_close_by_peer_total 1388
telemt_me_route_drop_no_conn_total 13988296
telemt_me_route_drop_channel_closed_total 144
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12746194
telemt_me_endpoint_quarantine_total 1092
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 1284
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
telemt_me_writers_active_current 43
telemt_desync_total 52638
telemt_desync_full_logged_total 16576
telemt_desync_suppressed_total 36062
telemt_desync_frames_bucket_total{bucket="1_2"} 11729
telemt_desync_frames_bucket_total{bucket="3_10"} 20493
telemt_desync_frames_bucket_total{bucket="gt_10"} 20416
telemt_pool_swap_total 186
telemt_pool_force_close_total 6280
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 1019
telemt_me_draining_writers_reap_progress_total 56582
telemt_me_writer_removed_unexpected_total 1342
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4956
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 52245
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 43
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5810
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 470
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 50302
telemt_me_writer_teardown_success_total{mode="normal"} 57201
telemt_me_writer_teardown_noop_total 56633
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 103055
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 106542
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 108232
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 110527
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 112181
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 113229
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 113795
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 113825
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 113826
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 113830
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 113832
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 113834
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 113834
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 313.740865
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 113834
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1019
telemt_me_refill_failed_total 75
telemt_me_writer_restored_same_endpoint_total 1249
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 86
telemt_user_connections_total{user="hello"} 12746634
telemt_user_connections_current{user="hello"} 1463
telemt_user_octets_from_client{user="hello"} 186591966581 (173.78 GB)
telemt_user_octets_to_client{user="hello"} 3398690963439 (3.09 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 610
telemt_user_unique_ips_recent_window{user="hello"} 219
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 172165.0 (47h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11575426
telemt_connections_bad_total 1160268
telemt_connections_current 1301
telemt_connections_me_current 1301
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 343195
telemt_upstream_connect_attempt_total 88977
telemt_upstream_connect_success_total 87708
telemt_upstream_connect_fail_total 850
telemt_upstream_connect_attempts_per_request{bucket="1"} 88558
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 47295
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36498
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 187
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3728
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 850
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 187
telemt_me_reconnect_attempts_total 4160
telemt_me_reconnect_success_total 1740
telemt_me_reader_eof_total 1606
telemt_me_idle_close_by_peer_total 1606
telemt_me_route_drop_no_conn_total 4508010
telemt_me_route_drop_channel_closed_total 496
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8624434
telemt_me_endpoint_quarantine_total 1090
telemt_me_single_endpoint_outage_enter_total 27
telemt_me_single_endpoint_outage_exit_total 27
telemt_me_single_endpoint_outage_reconnect_attempt_total 32
telemt_me_single_endpoint_outage_reconnect_success_total 25
telemt_me_single_endpoint_quarantine_bypass_total 32
telemt_me_single_endpoint_shadow_rotate_total 1305
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 46
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
telemt_me_writers_active_current 43
telemt_desync_total 38246
telemt_desync_full_logged_total 12863
telemt_desync_suppressed_total 25383
telemt_desync_frames_bucket_total{bucket="1_2"} 9433
telemt_desync_frames_bucket_total{bucket="3_10"} 14715
telemt_desync_frames_bucket_total{bucket="gt_10"} 14098
telemt_pool_swap_total 183
telemt_pool_force_close_total 5670
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 704
telemt_me_draining_writers_reap_progress_total 54984
telemt_me_writer_removed_unexpected_total 1644
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5078
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 51397
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5161
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 509
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 49314
telemt_me_writer_teardown_success_total{mode="normal"} 56475
telemt_me_writer_teardown_noop_total 55009
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 104815
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 107979
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 109119
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 110305
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 111060
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 111399
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 111474
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 111476
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 111482
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 111484
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 111484
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 111484
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 111484
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 103.755121
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 111484
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 704
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 1486
telemt_me_writer_restored_fallback_total 18
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 140
telemt_user_connections_total{user="hello"} 8562511
telemt_user_connections_current{user="hello"} 1301
telemt_user_octets_from_client{user="hello"} 215429525837 (200.63 GB)
telemt_user_octets_to_client{user="hello"} 3869664701854 (3.52 TB)
telemt_user_msgs_from_client{user="hello"} 113340
telemt_user_msgs_to_client{user="hello"} 116189
telemt_user_unique_ips_current{user="hello"} 439
telemt_user_unique_ips_recent_window{user="hello"} 233
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 172133.4 (47h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10853229
telemt_connections_bad_total 940632
telemt_connections_current 1043
telemt_connections_me_current 1043
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 344150
telemt_upstream_connect_attempt_total 74146
telemt_upstream_connect_success_total 72962
telemt_upstream_connect_fail_total 187
telemt_upstream_connect_attempts_per_request{bucket="1"} 73149
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34153
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34956
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1646
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2207
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 187
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 1386
telemt_me_reconnect_attempts_total 5105
telemt_me_reconnect_success_total 2051
telemt_me_reader_eof_total 1789
telemt_me_idle_close_by_peer_total 1788
telemt_me_route_drop_no_conn_total 5274102
telemt_me_route_drop_channel_closed_total 376
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8209212
telemt_me_endpoint_quarantine_total 1175
telemt_me_single_endpoint_outage_enter_total 36
telemt_me_single_endpoint_outage_exit_total 36
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 31
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 1262
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 64
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 41
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_desync_total 37583
telemt_desync_full_logged_total 12441
telemt_desync_suppressed_total 25142
telemt_desync_frames_bucket_total{bucket="1_2"} 9503
telemt_desync_frames_bucket_total{bucket="3_10"} 14363
telemt_desync_frames_bucket_total{bucket="gt_10"} 13717
telemt_pool_swap_total 181
telemt_pool_force_close_total 5609
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 716
telemt_me_draining_writers_reap_progress_total 55078
telemt_me_writer_removed_unexpected_total 1932
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5562
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 51368
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5058
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 551
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 49469
telemt_me_writer_teardown_success_total{mode="normal"} 56930
telemt_me_writer_teardown_noop_total 55149
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 106335
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 108999
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 109942
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 111003
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 111598
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 111812
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 111940
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 111971
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 111979
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 111992
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 112025
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 112028
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 112079
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3174.018899
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 112079
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 716
telemt_me_refill_failed_total 162
telemt_me_writer_restored_same_endpoint_total 1759
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 159
telemt_user_connections_total{user="hello"} 8201337
telemt_user_connections_current{user="hello"} 1043
telemt_user_octets_from_client{user="hello"} 191197758553 (178.07 GB)
telemt_user_octets_to_client{user="hello"} 3414304204345 (3.11 TB)
telemt_user_msgs_from_client{user="hello"} 46485
telemt_user_msgs_to_client{user="hello"} 113805
telemt_user_unique_ips_current{user="hello"} 355
telemt_user_unique_ips_recent_window{user="hello"} 239
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 42409.1 (11h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10868278
telemt_connections_bad_total 659862
telemt_connections_current 1726
telemt_connections_me_current 1726
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 236464
telemt_upstream_connect_attempt_total 45807
telemt_upstream_connect_success_total 43520
telemt_upstream_connect_fail_total 1562
telemt_upstream_connect_attempts_per_request{bucket="1"} 45082
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22172
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13925
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1460
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5963
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1562
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 6599
telemt_me_reconnect_success_total 931
telemt_me_reader_eof_total 585
telemt_me_idle_close_by_peer_total 585
telemt_me_route_drop_no_conn_total 25214024
telemt_me_route_drop_channel_closed_total 54
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9027609
telemt_me_endpoint_quarantine_total 280
telemt_me_single_endpoint_outage_enter_total 66
telemt_me_single_endpoint_outage_exit_total 66
telemt_me_single_endpoint_outage_reconnect_attempt_total 118
telemt_me_single_endpoint_outage_reconnect_success_total 37
telemt_me_single_endpoint_quarantine_bypass_total 118
telemt_me_single_endpoint_shadow_rotate_total 328
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
telemt_me_writers_active_current 42
telemt_desync_total 14774
telemt_desync_full_logged_total 3895
telemt_desync_suppressed_total 10879
telemt_desync_frames_bucket_total{bucket="1_2"} 2763
telemt_desync_frames_bucket_total{bucket="3_10"} 5993
telemt_desync_frames_bucket_total{bucket="gt_10"} 6018
telemt_pool_swap_total 43
telemt_pool_force_close_total 1536
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 436
telemt_me_draining_writers_reap_progress_total 12137
telemt_me_writer_removed_unexpected_total 828
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1797
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 11118
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1234
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 302
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 10601
telemt_me_writer_teardown_success_total{mode="normal"} 12915
telemt_me_writer_teardown_noop_total 12156
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 21513
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 23089
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 23720
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 24540
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 24897
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 25015
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 25071
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 25071
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 25071
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 25071
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 25071
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 25071
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 25071
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 50.964041
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 25071
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 436
telemt_me_refill_failed_total 313
telemt_me_writer_restored_same_endpoint_total 626
telemt_me_writer_restored_fallback_total 5
telemt_me_no_writer_failfast_total 96
telemt_me_async_recovery_trigger_total 3149
telemt_me_writer_removed_unexpected_minus_restored_total 197
telemt_user_connections_total{user="hello"} 9049690
telemt_user_connections_current{user="hello"} 1726
telemt_user_octets_from_client{user="hello"} 82852833851 (77.16 GB)
telemt_user_octets_to_client{user="hello"} 508640909111 (473.71 GB)
telemt_user_msgs_from_client{user="hello"} 58278
telemt_user_msgs_to_client{user="hello"} 46361
telemt_user_unique_ips_current{user="hello"} 685
telemt_user_unique_ips_recent_window{user="hello"} 217
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 172135.8 (47h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10741649
telemt_connections_bad_total 908039
telemt_connections_current 1053
telemt_connections_me_current 1053
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 236465
telemt_upstream_connect_attempt_total 103567
telemt_upstream_connect_success_total 102479
telemt_upstream_connect_fail_total 929
telemt_upstream_connect_attempts_per_request{bucket="1"} 103408
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 62279
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 38621
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1341
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 929
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 72414
telemt_me_reconnect_success_total 2837
telemt_me_reader_eof_total 2528
telemt_me_idle_close_by_peer_total 2526
telemt_me_route_drop_no_conn_total 5207455
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8484674
telemt_me_endpoint_quarantine_total 1139
telemt_me_single_endpoint_outage_enter_total 39
telemt_me_single_endpoint_outage_exit_total 39
telemt_me_single_endpoint_outage_reconnect_attempt_total 41
telemt_me_single_endpoint_outage_reconnect_success_total 39
telemt_me_single_endpoint_quarantine_bypass_total 41
telemt_me_single_endpoint_shadow_rotate_total 1287
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
telemt_me_writers_active_current 46
telemt_desync_total 45178
telemt_desync_full_logged_total 15394
telemt_desync_suppressed_total 29784
telemt_desync_frames_bucket_total{bucket="1_2"} 9150
telemt_desync_frames_bucket_total{bucket="3_10"} 17315
telemt_desync_frames_bucket_total{bucket="gt_10"} 18713
telemt_pool_swap_total 176
telemt_pool_force_close_total 5255
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 642
telemt_me_draining_writers_reap_progress_total 59053
telemt_me_writer_removed_unexpected_total 2566
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6267
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 55378
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4528
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 727
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 53798
telemt_me_writer_teardown_success_total{mode="normal"} 61645
telemt_me_writer_teardown_noop_total 59054
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 118589
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 119964
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 120382
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 120655
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 120689
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 120692
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 120692
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 120695
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 120699
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 120699
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 120699
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 120699
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 120699
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.062667
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 120699
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 642
telemt_me_refill_failed_total 4286
telemt_me_writer_restored_same_endpoint_total 2386
telemt_me_writer_restored_fallback_total 48
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7367
telemt_me_writer_removed_unexpected_minus_restored_total 132
telemt_user_connections_total{user="hello"} 8487908
telemt_user_connections_current{user="hello"} 1053
telemt_user_octets_from_client{user="hello"} 192075153701 (178.88 GB)
telemt_user_octets_to_client{user="hello"} 3229053767304 (2.94 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 414
telemt_user_unique_ips_recent_window{user="hello"} 160
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 108971.9 (30h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11336688
telemt_connections_bad_total 454794
telemt_connections_current 1460
telemt_connections_me_current 1460
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4657829
telemt_upstream_connect_attempt_total 51599
telemt_upstream_connect_success_total 51216
telemt_upstream_connect_fail_total 374
telemt_upstream_connect_attempts_per_request{bucket="1"} 51590
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28033
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22984
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 199
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 374
telemt_me_reconnect_attempts_total 48550
telemt_me_reconnect_success_total 1678
telemt_me_reader_eof_total 1336
telemt_me_idle_close_by_peer_total 1335
telemt_me_route_drop_no_conn_total 4044638
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5462949
telemt_me_endpoint_quarantine_total 702
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 59
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 59
telemt_me_single_endpoint_shadow_rotate_total 820
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
telemt_me_writers_active_current 46
telemt_me_writers_warm_current 28
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 30726
telemt_desync_full_logged_total 10417
telemt_desync_suppressed_total 20309
telemt_desync_frames_bucket_total{bucket="1_2"} 6116
telemt_desync_frames_bucket_total{bucket="3_10"} 12161
telemt_desync_frames_bucket_total{bucket="gt_10"} 12449
telemt_pool_swap_total 114
telemt_pool_force_close_total 3485
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 353
telemt_me_draining_writers_reap_progress_total 37932
telemt_me_writer_removed_unexpected_total 1396
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3344
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 36018
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3044
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 441
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 34447
telemt_me_writer_teardown_success_total{mode="normal"} 39362
telemt_me_writer_teardown_noop_total 37939
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 76049
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 76770
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 77074
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 77301
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 77301
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 77301
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 77301
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 77301
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 77301
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 77301
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 77301
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 77301
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 77301
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.480155
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 77301
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 353
telemt_me_refill_failed_total 2724
telemt_me_writer_restored_same_endpoint_total 1492
telemt_me_writer_restored_fallback_total 19
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4332
telemt_user_connections_total{user="hello"} 5455768
telemt_user_connections_current{user="hello"} 1460
telemt_user_octets_from_client{user="hello"} 117375252648 (109.31 GB)
telemt_user_octets_to_client{user="hello"} 2091622061230 (1.90 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 592
telemt_user_unique_ips_recent_window{user="hello"} 141
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 89942.7 (24h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1357789
telemt_connections_bad_total 30805
telemt_connections_current 989
telemt_connections_me_current 989
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 25362
telemt_upstream_connect_attempt_total 42480
telemt_upstream_connect_success_total 42350
telemt_upstream_connect_fail_total 103
telemt_upstream_connect_attempts_per_request{bucket="1"} 42453
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19104
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 728
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 103
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2002
telemt_me_reconnect_success_total 822
telemt_me_reader_eof_total 800
telemt_me_idle_close_by_peer_total 800
telemt_me_route_drop_no_conn_total 475281
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1205825
telemt_me_endpoint_quarantine_total 742
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 739
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
telemt_desync_total 7264
telemt_desync_full_logged_total 2255
telemt_desync_suppressed_total 5009
telemt_desync_frames_bucket_total{bucket="1_2"} 1590
telemt_desync_frames_bucket_total{bucket="3_10"} 2851
telemt_desync_frames_bucket_total{bucket="gt_10"} 2823
telemt_pool_swap_total 96
telemt_pool_force_close_total 2492
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 144
telemt_me_draining_writers_reap_progress_total 35391
telemt_me_writer_removed_unexpected_total 772
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2795
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 33399
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2405
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 87
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 32899
telemt_me_writer_teardown_success_total{mode="normal"} 36194
telemt_me_writer_teardown_noop_total 35395
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 70765
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 71363
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 71552
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 71589
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 71589
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 71589
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 71589
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 71589
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 71589
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 71589
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 71589
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 71589
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 71589
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.533632
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 71589
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 144
telemt_me_refill_failed_total 65
telemt_me_writer_restored_same_endpoint_total 696
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 58
telemt_user_connections_total{user="hello"} 1201887
telemt_user_connections_current{user="hello"} 989
telemt_user_octets_from_client{user="hello"} 23117716849 (21.53 GB)
telemt_user_octets_to_client{user="hello"} 508562748039 (473.64 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 354
telemt_user_unique_ips_recent_window{user="hello"} 133
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 172140.2 (47h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13058667
telemt_connections_bad_total 1528169
telemt_connections_current 1340
telemt_connections_me_current 1340
telemt_handshake_timeouts_total 374513
telemt_upstream_connect_attempt_total 65123
telemt_upstream_connect_success_total 64791
telemt_upstream_connect_fail_total 197
telemt_upstream_connect_attempts_per_request{bucket="1"} 64988
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32072
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32619
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 197
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2561
telemt_me_reconnect_success_total 1337
telemt_me_reader_eof_total 1304
telemt_me_idle_close_by_peer_total 1304
telemt_me_route_drop_no_conn_total 4426818
telemt_me_route_drop_channel_closed_total 123
telemt_me_route_drop_queue_full_total 39
telemt_me_route_drop_queue_full_profile_total{profile="high"} 39
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9880816
telemt_me_endpoint_quarantine_total 1161
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 1288
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
telemt_me_writers_active_current 44
telemt_desync_total 40941
telemt_desync_full_logged_total 13352
telemt_desync_suppressed_total 27589
telemt_desync_frames_bucket_total{bucket="1_2"} 9777
telemt_desync_frames_bucket_total{bucket="3_10"} 15099
telemt_desync_frames_bucket_total{bucket="gt_10"} 16065
telemt_pool_swap_total 191
telemt_pool_force_close_total 5248
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 653
telemt_me_draining_writers_reap_progress_total 58682
telemt_me_writer_removed_unexpected_total 1255
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4790
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 55186
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5074
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 53434
telemt_me_writer_teardown_success_total{mode="normal"} 59976
telemt_me_writer_teardown_noop_total 58684
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 116117
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 117772
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 118151
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 118527
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 118647
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 118660
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 118660
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 118660
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 118660
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 118660
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 118660
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 118660
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 118660
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.469426
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 118660
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 653
telemt_me_refill_failed_total 65
telemt_me_writer_restored_same_endpoint_total 1170
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 71
telemt_user_connections_total{user="hello"} 9848452
telemt_user_connections_current{user="hello"} 1340
telemt_user_octets_from_client{user="hello"} 192368418052 (179.16 GB)
telemt_user_octets_to_client{user="hello"} 4352307713164 (3.96 TB)
telemt_user_unique_ips_current{user="hello"} 450
telemt_user_unique_ips_recent_window{user="hello"} 246
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 172136.9 (47h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11359412
telemt_connections_bad_total 1286653
telemt_connections_current 1162
telemt_connections_me_current 1162
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 298980
telemt_upstream_connect_attempt_total 91597
telemt_upstream_connect_success_total 90768
telemt_upstream_connect_fail_total 622
telemt_upstream_connect_attempts_per_request{bucket="1"} 91390
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 49624
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 38166
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2065
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 622
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 9861
telemt_me_reconnect_success_total 2374
telemt_me_reader_eof_total 2215
telemt_me_idle_close_by_peer_total 2214
telemt_me_seq_mismatch_total 79
telemt_me_route_drop_no_conn_total 5602018
telemt_me_route_drop_channel_closed_total 354
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8783752
telemt_me_endpoint_quarantine_total 1322
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 48
telemt_me_single_endpoint_outage_exit_total 48
telemt_me_single_endpoint_outage_reconnect_attempt_total 48
telemt_me_single_endpoint_outage_reconnect_success_total 46
telemt_me_single_endpoint_quarantine_bypass_total 48
telemt_me_single_endpoint_shadow_rotate_total 1289
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 54
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
telemt_desync_total 40160
telemt_desync_full_logged_total 12975
telemt_desync_suppressed_total 27185
telemt_desync_frames_bucket_total{bucket="1_2"} 10021
telemt_desync_frames_bucket_total{bucket="3_10"} 14915
telemt_desync_frames_bucket_total{bucket="gt_10"} 15224
telemt_pool_swap_total 181
telemt_pool_force_close_total 5046
telemt_pool_stale_pick_total 360
telemt_me_writer_close_signal_drop_total 638
telemt_me_draining_writers_reap_progress_total 58467
telemt_me_writer_removed_unexpected_total 2247
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6139
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 54651
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4575
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 471
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 53421
telemt_me_writer_teardown_success_total{mode="normal"} 60790
telemt_me_writer_teardown_noop_total 58472
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 116622
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 118357
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 118893
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 119212
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 119262
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 119262
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 119262
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 119262
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 119262
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 119262
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 119262
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 119262
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 119262
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.185782
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 119262
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 638
telemt_me_refill_failed_total 386
telemt_me_writer_restored_same_endpoint_total 1932
telemt_me_writer_restored_fallback_total 109
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 133
telemt_me_writer_removed_unexpected_minus_restored_total 206
telemt_user_connections_total{user="hello"} 8789275
telemt_user_connections_current{user="hello"} 1162
telemt_user_octets_from_client{user="hello"} 155551438525 (144.87 GB)
telemt_user_octets_to_client{user="hello"} 3403030210719 (3.10 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 437
telemt_user_unique_ips_recent_window{user="hello"} 331
```