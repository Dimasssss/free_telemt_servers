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

# Server Metrics 2026-03-22 16:39:44 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 70399.6 (19h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2502192
telemt_connections_bad_total 134058
telemt_connections_current 1547
telemt_connections_me_current 1547
telemt_handshake_timeouts_total 88427
telemt_upstream_connect_attempt_total 26007
telemt_upstream_connect_success_total 26006
telemt_upstream_connect_attempts_per_request{bucket="1"} 26006
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9055
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16882
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 56
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 150
telemt_me_reconnect_attempts_total 1039
telemt_me_reconnect_success_total 445
telemt_me_reader_eof_total 448
telemt_me_idle_close_by_peer_total 448
telemt_me_route_drop_no_conn_total 2030244
telemt_me_route_drop_channel_closed_total 843
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2132309
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_endpoint_quarantine_total 479
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 550
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
telemt_me_writers_active_current 43
telemt_desync_total 10184
telemt_desync_full_logged_total 3201
telemt_desync_suppressed_total 6983
telemt_desync_frames_bucket_total{bucket="1_2"} 2721
telemt_desync_frames_bucket_total{bucket="3_10"} 3812
telemt_desync_frames_bucket_total{bucket="gt_10"} 3651
telemt_pool_swap_total 78
telemt_pool_force_close_total 2425
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 471
telemt_me_draining_writers_reap_progress_total 23770
telemt_me_writer_removed_unexpected_total 434
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1735
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 22246
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2374
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 51
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21345
telemt_me_writer_teardown_success_total{mode="normal"} 23981
telemt_me_writer_teardown_noop_total 23776
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 38673
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 40400
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 42037
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 44784
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 46635
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 47492
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 47753
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 47757
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 47757
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 47757
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 47757
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 47757
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 47757
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 225.336291
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 47757
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 471
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 395
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 2128820
telemt_user_connections_current{user="hello"} 1547
telemt_user_octets_from_client{user="hello"} 32135546920 (29.93 GB)
telemt_user_octets_to_client{user="hello"} 566571260900 (527.66 GB)
telemt_user_unique_ips_current{user="hello"} 576
telemt_user_unique_ips_recent_window{user="hello"} 531
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 83766.1 (23h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3614030
telemt_connections_bad_total 328115
telemt_connections_current 1262
telemt_connections_me_current 1262
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 90001
telemt_upstream_connect_attempt_total 52540
telemt_upstream_connect_success_total 51902
telemt_upstream_connect_fail_total 566
telemt_upstream_connect_attempts_per_request{bucket="1"} 52468
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30072
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21660
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 170
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 566
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 6072
telemt_me_reconnect_success_total 2210
telemt_me_reader_eof_total 2146
telemt_me_idle_close_by_peer_total 2146
telemt_me_route_drop_no_conn_total 3536095
telemt_me_route_drop_channel_closed_total 36
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2864872
telemt_me_endpoint_quarantine_total 665
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 37
telemt_me_single_endpoint_outage_exit_total 37
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 37
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 645
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 35
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
telemt_me_writers_active_current 54
telemt_me_writers_warm_current 20
telemt_desync_total 11207
telemt_desync_full_logged_total 6251
telemt_desync_suppressed_total 4956
telemt_desync_frames_bucket_total{bucket="1_2"} 2607
telemt_desync_frames_bucket_total{bucket="3_10"} 4395
telemt_desync_frames_bucket_total{bucket="gt_10"} 4205
telemt_pool_swap_total 78
telemt_pool_force_close_total 2346
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 198
telemt_me_draining_writers_reap_progress_total 33406
telemt_me_writer_removed_unexpected_total 2100
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4002
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 31511
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1990
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 356
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 31060
telemt_me_writer_teardown_success_total{mode="normal"} 35513
telemt_me_writer_teardown_noop_total 33406
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 67230
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 68280
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 68549
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 68853
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 68904
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 68917
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 68919
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 68919
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 68919
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 68919
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 68919
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 68919
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 68919
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 12.959625
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 68919
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 198
telemt_me_refill_failed_total 151
telemt_me_writer_restored_same_endpoint_total 1917
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 159
telemt_user_connections_total{user="hello"} 2876143
telemt_user_connections_current{user="hello"} 1262
telemt_user_octets_from_client{user="hello"} 35794391735 (33.34 GB)
telemt_user_octets_to_client{user="hello"} 645450934398 (601.12 GB)
telemt_user_msgs_from_client{user="hello"} 42816
telemt_user_msgs_to_client{user="hello"} 172415
telemt_user_unique_ips_current{user="hello"} 714
telemt_user_unique_ips_recent_window{user="hello"} 229
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 158625.9 (44h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15359186
telemt_connections_bad_total 1435028
telemt_connections_current 1969
telemt_connections_me_current 1969
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 373819
telemt_upstream_connect_attempt_total 71627
telemt_upstream_connect_success_total 71531
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 71548
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35964
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33886
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1674
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2667
telemt_me_reconnect_success_total 1360
telemt_me_reader_eof_total 1299
telemt_me_idle_close_by_peer_total 1297
telemt_me_route_drop_no_conn_total 13815816
telemt_me_route_drop_channel_closed_total 139
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12271974
telemt_me_endpoint_quarantine_total 1002
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 1185
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 40
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
telemt_desync_total 50023
telemt_desync_full_logged_total 15704
telemt_desync_suppressed_total 34319
telemt_desync_frames_bucket_total{bucket="1_2"} 11186
telemt_desync_frames_bucket_total{bucket="3_10"} 19549
telemt_desync_frames_bucket_total{bucket="gt_10"} 19288
telemt_pool_swap_total 171
telemt_pool_force_close_total 5823
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 941
telemt_me_draining_writers_reap_progress_total 52219
telemt_me_writer_removed_unexpected_total 1253
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4547
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 48216
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 42
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5363
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 460
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 46396
telemt_me_writer_teardown_success_total{mode="normal"} 52763
telemt_me_writer_teardown_noop_total 52269
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 94850
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 98122
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 99726
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 101893
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 103449
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 104435
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 104993
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 105023
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 105024
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 105028
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 105030
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 105032
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 105032
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 301.783438
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 105032
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 941
telemt_me_refill_failed_total 72
telemt_me_writer_restored_same_endpoint_total 1167
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 79
telemt_user_connections_total{user="hello"} 12273104
telemt_user_connections_current{user="hello"} 1969
telemt_user_octets_from_client{user="hello"} 175041967273 (163.02 GB)
telemt_user_octets_to_client{user="hello"} 3178314116859 (2.89 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 727
telemt_user_unique_ips_recent_window{user="hello"} 290
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 158627.2 (44h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11081784
telemt_connections_bad_total 1076784
telemt_connections_current 1323
telemt_connections_me_current 1323
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 329018
telemt_upstream_connect_attempt_total 83794
telemt_upstream_connect_success_total 82637
telemt_upstream_connect_fail_total 833
telemt_upstream_connect_attempts_per_request{bucket="1"} 83470
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 45069
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33716
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 157
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3695
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 833
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 182
telemt_me_reconnect_attempts_total 3942
telemt_me_reconnect_success_total 1606
telemt_me_reader_eof_total 1478
telemt_me_idle_close_by_peer_total 1478
telemt_me_route_drop_no_conn_total 4366507
telemt_me_route_drop_channel_closed_total 478
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8265381
telemt_me_endpoint_quarantine_total 1001
telemt_me_single_endpoint_outage_enter_total 27
telemt_me_single_endpoint_outage_exit_total 27
telemt_me_single_endpoint_outage_reconnect_attempt_total 32
telemt_me_single_endpoint_outage_reconnect_success_total 25
telemt_me_single_endpoint_quarantine_bypass_total 32
telemt_me_single_endpoint_shadow_rotate_total 1201
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 43
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
telemt_desync_total 36745
telemt_desync_full_logged_total 12354
telemt_desync_suppressed_total 24391
telemt_desync_frames_bucket_total{bucket="1_2"} 9018
telemt_desync_frames_bucket_total{bucket="3_10"} 14155
telemt_desync_frames_bucket_total{bucket="gt_10"} 13572
telemt_pool_swap_total 169
telemt_pool_force_close_total 5241
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 666
telemt_me_draining_writers_reap_progress_total 50474
telemt_me_writer_removed_unexpected_total 1506
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4654
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 47187
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 18
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4765
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 476
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 45233
telemt_me_writer_teardown_success_total{mode="normal"} 51841
telemt_me_writer_teardown_noop_total 50492
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 96080
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 99032
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 100109
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 101203
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 101917
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 102248
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 102323
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 102325
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 102331
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 102333
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 102333
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 102333
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 102333
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 99.276468
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 102333
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 666
telemt_me_refill_failed_total 126
telemt_me_writer_restored_same_endpoint_total 1368
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 124
telemt_user_connections_total{user="hello"} 8204010
telemt_user_connections_current{user="hello"} 1323
telemt_user_octets_from_client{user="hello"} 205214351213 (191.12 GB)
telemt_user_octets_to_client{user="hello"} 3698733612870 (3.36 TB)
telemt_user_msgs_from_client{user="hello"} 113340
telemt_user_msgs_to_client{user="hello"} 116189
telemt_user_unique_ips_current{user="hello"} 482
telemt_user_unique_ips_recent_window{user="hello"} 210
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 158593.1 (44h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10476169
telemt_connections_bad_total 902439
telemt_connections_current 1432
telemt_connections_me_current 1432
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 334902
telemt_upstream_connect_attempt_total 68992
telemt_upstream_connect_success_total 68027
telemt_upstream_connect_fail_total 182
telemt_upstream_connect_attempts_per_request{bucket="1"} 68209
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32377
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32247
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1323
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2080
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 182
telemt_me_keepalive_timeout_total 1383
telemt_me_reconnect_attempts_total 4725
telemt_me_reconnect_success_total 1907
telemt_me_reader_eof_total 1659
telemt_me_idle_close_by_peer_total 1658
telemt_me_route_drop_no_conn_total 5138902
telemt_me_route_drop_channel_closed_total 360
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7908243
telemt_me_endpoint_quarantine_total 1090
telemt_me_single_endpoint_outage_enter_total 32
telemt_me_single_endpoint_outage_exit_total 32
telemt_me_single_endpoint_outage_reconnect_attempt_total 33
telemt_me_single_endpoint_outage_reconnect_success_total 27
telemt_me_single_endpoint_quarantine_bypass_total 33
telemt_me_single_endpoint_shadow_rotate_total 1166
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 56
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
telemt_desync_total 36198
telemt_desync_full_logged_total 11993
telemt_desync_suppressed_total 24205
telemt_desync_frames_bucket_total{bucket="1_2"} 9163
telemt_desync_frames_bucket_total{bucket="3_10"} 13832
telemt_desync_frames_bucket_total{bucket="gt_10"} 13203
telemt_pool_swap_total 166
telemt_pool_force_close_total 5161
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 685
telemt_me_draining_writers_reap_progress_total 50800
telemt_me_writer_removed_unexpected_total 1799
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5096
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 47416
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4619
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 542
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 45639
telemt_me_writer_teardown_success_total{mode="normal"} 52512
telemt_me_writer_teardown_noop_total 50871
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 97914
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 100416
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 101316
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 102339
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 102909
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 103119
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 103247
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 103275
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 103283
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 103296
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 103329
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 103332
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 103383
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3170.569030
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 103383
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 685
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 1646
telemt_me_writer_restored_fallback_total 10
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 143
telemt_user_connections_total{user="hello"} 7901191
telemt_user_connections_current{user="hello"} 1432
telemt_user_octets_from_client{user="hello"} 182007574273 (169.51 GB)
telemt_user_octets_to_client{user="hello"} 3285204453133 (2.99 TB)
telemt_user_msgs_from_client{user="hello"} 46485
telemt_user_msgs_to_client{user="hello"} 113805
telemt_user_unique_ips_current{user="hello"} 588
telemt_user_unique_ips_recent_window{user="hello"} 167
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 28871.4 (8h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10193860
telemt_connections_bad_total 622713
telemt_connections_current 2288
telemt_connections_me_current 2288
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 191219
telemt_upstream_connect_attempt_total 36043
telemt_upstream_connect_success_total 34244
telemt_upstream_connect_fail_total 1256
telemt_upstream_connect_attempts_per_request{bucket="1"} 35500
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18513
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9439
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 988
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5304
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1256
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 5895
telemt_me_reconnect_success_total 716
telemt_me_reader_eof_total 459
telemt_me_idle_close_by_peer_total 459
telemt_me_route_drop_no_conn_total 24948708
telemt_me_route_drop_channel_closed_total 47
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8485030
telemt_me_endpoint_quarantine_total 175
telemt_me_single_endpoint_outage_enter_total 50
telemt_me_single_endpoint_outage_exit_total 50
telemt_me_single_endpoint_outage_reconnect_attempt_total 85
telemt_me_single_endpoint_outage_reconnect_success_total 28
telemt_me_single_endpoint_quarantine_bypass_total 85
telemt_me_single_endpoint_shadow_rotate_total 223
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
telemt_me_writers_active_current 46
telemt_me_writers_warm_current 26
telemt_desync_total 13280
telemt_desync_full_logged_total 3431
telemt_desync_suppressed_total 9849
telemt_desync_frames_bucket_total{bucket="1_2"} 2366
telemt_desync_frames_bucket_total{bucket="3_10"} 5402
telemt_desync_frames_bucket_total{bucket="gt_10"} 5512
telemt_pool_swap_total 27
telemt_pool_force_close_total 1067
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 366
telemt_me_draining_writers_reap_progress_total 7886
telemt_me_writer_removed_unexpected_total 619
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1289
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 7181
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 787
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 280
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 6819
telemt_me_writer_teardown_success_total{mode="normal"} 8470
telemt_me_writer_teardown_noop_total 7891
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 13609
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 14934
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 15394
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 15966
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 16236
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 16334
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 16361
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 16361
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 16361
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 16361
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 16361
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 16361
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 16361
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 36.832621
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 16361
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 366
telemt_me_refill_failed_total 293
telemt_me_writer_restored_same_endpoint_total 491
telemt_me_writer_restored_fallback_total 4
telemt_me_no_writer_failfast_total 86
telemt_me_async_recovery_trigger_total 3059
telemt_me_writer_removed_unexpected_minus_restored_total 124
telemt_user_connections_total{user="hello"} 8503094
telemt_user_connections_current{user="hello"} 2288
telemt_user_octets_from_client{user="hello"} 64381008842 (59.96 GB)
telemt_user_octets_to_client{user="hello"} 314218288612 (292.64 GB)
telemt_user_msgs_from_client{user="hello"} 48912
telemt_user_msgs_to_client{user="hello"} 39981
telemt_user_unique_ips_current{user="hello"} 830
telemt_user_unique_ips_recent_window{user="hello"} 308
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 158598.0 (44h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10271099
telemt_connections_bad_total 862011
telemt_connections_current 1809
telemt_connections_me_current 1809
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 228289
telemt_upstream_connect_attempt_total 97769
telemt_upstream_connect_success_total 96758
telemt_upstream_connect_fail_total 863
telemt_upstream_connect_attempts_per_request{bucket="1"} 97621
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 59738
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35475
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1307
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 863
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 72045
telemt_me_reconnect_success_total 2627
telemt_me_reader_eof_total 2330
telemt_me_idle_close_by_peer_total 2328
telemt_me_route_drop_no_conn_total 5069266
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8099184
telemt_me_endpoint_quarantine_total 1072
telemt_me_single_endpoint_outage_enter_total 37
telemt_me_single_endpoint_outage_exit_total 37
telemt_me_single_endpoint_outage_reconnect_attempt_total 39
telemt_me_single_endpoint_outage_reconnect_success_total 37
telemt_me_single_endpoint_quarantine_bypass_total 39
telemt_me_single_endpoint_shadow_rotate_total 1183
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
telemt_desync_total 42272
telemt_desync_full_logged_total 14418
telemt_desync_suppressed_total 27854
telemt_desync_frames_bucket_total{bucket="1_2"} 8587
telemt_desync_frames_bucket_total{bucket="3_10"} 16347
telemt_desync_frames_bucket_total{bucket="gt_10"} 17338
telemt_pool_swap_total 162
telemt_pool_force_close_total 4795
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 603
telemt_me_draining_writers_reap_progress_total 53940
telemt_me_writer_removed_unexpected_total 2373
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5769
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 50565
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4110
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 685
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 49145
telemt_me_writer_teardown_success_total{mode="normal"} 56334
telemt_me_writer_teardown_noop_total 53941
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 108294
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 109577
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 109959
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 110231
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 110265
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 110268
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 110268
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 110271
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 110275
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 110275
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 110275
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 110275
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 110275
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 16.455032
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 110275
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 603
telemt_me_refill_failed_total 4279
telemt_me_writer_restored_same_endpoint_total 2199
telemt_me_writer_restored_fallback_total 45
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7365
telemt_me_writer_removed_unexpected_minus_restored_total 129
telemt_user_connections_total{user="hello"} 8103116
telemt_user_connections_current{user="hello"} 1809
telemt_user_octets_from_client{user="hello"} 183403238501 (170.81 GB)
telemt_user_octets_to_client{user="hello"} 3052054879272 (2.78 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 726
telemt_user_unique_ips_recent_window{user="hello"} 237
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 95434.1 (26h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10695469
telemt_connections_bad_total 401733
telemt_connections_current 1404
telemt_connections_me_current 1404
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4488794
telemt_upstream_connect_attempt_total 45898
telemt_upstream_connect_success_total 45566
telemt_upstream_connect_fail_total 323
telemt_upstream_connect_attempts_per_request{bucket="1"} 45889
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25533
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19878
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 155
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 323
telemt_me_reconnect_attempts_total 48089
telemt_me_reconnect_success_total 1519
telemt_me_reader_eof_total 1184
telemt_me_idle_close_by_peer_total 1183
telemt_me_route_drop_no_conn_total 3923873
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5126453
telemt_me_endpoint_quarantine_total 619
telemt_me_single_endpoint_outage_enter_total 18
telemt_me_single_endpoint_outage_exit_total 18
telemt_me_single_endpoint_outage_reconnect_attempt_total 58
telemt_me_single_endpoint_outage_reconnect_success_total 18
telemt_me_single_endpoint_quarantine_bypass_total 58
telemt_me_single_endpoint_shadow_rotate_total 716
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
telemt_me_writers_active_current 50
telemt_me_writers_warm_current 6
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 28126
telemt_desync_full_logged_total 9510
telemt_desync_suppressed_total 18616
telemt_desync_frames_bucket_total{bucket="1_2"} 5673
telemt_desync_frames_bucket_total{bucket="3_10"} 11099
telemt_desync_frames_bucket_total{bucket="gt_10"} 11354
telemt_pool_swap_total 100
telemt_pool_force_close_total 3081
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 313
telemt_me_draining_writers_reap_progress_total 32857
telemt_me_writer_removed_unexpected_total 1247
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2943
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 31191
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2662
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 419
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 29776
telemt_me_writer_teardown_success_total{mode="normal"} 34134
telemt_me_writer_teardown_noop_total 32864
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 65870
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 66509
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 66774
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 66998
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 66998
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 66998
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 66998
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 66998
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 66998
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 66998
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 66998
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 66998
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 66998
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.886872
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 66998
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 313
telemt_me_refill_failed_total 2707
telemt_me_writer_restored_same_endpoint_total 1352
telemt_me_writer_restored_fallback_total 15
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4328
telemt_user_connections_total{user="hello"} 5119959
telemt_user_connections_current{user="hello"} 1404
telemt_user_octets_from_client{user="hello"} 110111465052 (102.55 GB)
telemt_user_octets_to_client{user="hello"} 1935215177174 (1.76 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 596
telemt_user_unique_ips_recent_window{user="hello"} 178
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 76404.8 (21h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1036554
telemt_connections_bad_total 15454
telemt_connections_current 1205
telemt_connections_me_current 1205
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 19978
telemt_upstream_connect_attempt_total 37425
telemt_upstream_connect_success_total 37327
telemt_upstream_connect_fail_total 80
telemt_upstream_connect_attempts_per_request{bucket="1"} 37407
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16921
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19866
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 540
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 80
telemt_me_reconnect_attempts_total 1725
telemt_me_reconnect_success_total 717
telemt_me_reader_eof_total 692
telemt_me_idle_close_by_peer_total 692
telemt_me_route_drop_no_conn_total 362964
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 922759
telemt_me_endpoint_quarantine_total 652
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 630
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 15
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
telemt_desync_total 5228
telemt_desync_full_logged_total 1598
telemt_desync_suppressed_total 3630
telemt_desync_frames_bucket_total{bucket="1_2"} 1226
telemt_desync_frames_bucket_total{bucket="3_10"} 2067
telemt_desync_frames_bucket_total{bucket="gt_10"} 1935
telemt_pool_swap_total 81
telemt_pool_force_close_total 2053
telemt_me_writer_close_signal_drop_total 119
telemt_me_draining_writers_reap_progress_total 31001
telemt_me_writer_removed_unexpected_total 668
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2398
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 29297
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1972
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 81
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 28948
telemt_me_writer_teardown_success_total{mode="normal"} 31695
telemt_me_writer_teardown_noop_total 31004
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 62022
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 62504
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 62668
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 62699
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 62699
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 62699
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 62699
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 62699
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 62699
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 62699
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 62699
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 62699
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 62699
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.757215
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 62699
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 119
telemt_me_refill_failed_total 55
telemt_me_writer_restored_same_endpoint_total 610
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 919293
telemt_user_connections_current{user="hello"} 1205
telemt_user_octets_from_client{user="hello"} 16549738293 (15.41 GB)
telemt_user_octets_to_client{user="hello"} 404554748279 (376.77 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 424
telemt_user_unique_ips_recent_window{user="hello"} 192
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 158602.5 (44h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12544624
telemt_connections_bad_total 1453335
telemt_connections_current 1278
telemt_connections_me_current 1278
telemt_handshake_timeouts_total 346696
telemt_upstream_connect_attempt_total 59591
telemt_upstream_connect_success_total 59348
telemt_upstream_connect_fail_total 182
telemt_upstream_connect_attempts_per_request{bucket="1"} 59530
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29305
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29972
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 70
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 182
telemt_me_reconnect_attempts_total 2345
telemt_me_reconnect_success_total 1241
telemt_me_reader_eof_total 1205
telemt_me_idle_close_by_peer_total 1205
telemt_me_route_drop_no_conn_total 4187044
telemt_me_route_drop_channel_closed_total 121
telemt_me_route_drop_queue_full_total 37
telemt_me_route_drop_queue_full_profile_total{profile="high"} 37
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9487584
telemt_me_endpoint_quarantine_total 1070
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 1186
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 41
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
telemt_desync_total 38945
telemt_desync_full_logged_total 12712
telemt_desync_suppressed_total 26233
telemt_desync_frames_bucket_total{bucket="1_2"} 9259
telemt_desync_frames_bucket_total{bucket="3_10"} 14432
telemt_desync_frames_bucket_total{bucket="gt_10"} 15254
telemt_pool_swap_total 176
telemt_pool_force_close_total 4862
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 621
telemt_me_draining_writers_reap_progress_total 53663
telemt_me_writer_removed_unexpected_total 1158
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4408
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 50446
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4688
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 48801
telemt_me_writer_teardown_success_total{mode="normal"} 54854
telemt_me_writer_teardown_noop_total 53665
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 106115
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 107714
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 108062
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 108386
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 108506
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 108519
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 108519
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 108519
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 108519
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 108519
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 108519
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 108519
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 108519
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 18.261788
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 108519
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 621
telemt_me_refill_failed_total 58
telemt_me_writer_restored_same_endpoint_total 1085
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 61
telemt_user_connections_total{user="hello"} 9456787
telemt_user_connections_current{user="hello"} 1278
telemt_user_octets_from_client{user="hello"} 185690064152 (172.94 GB)
telemt_user_octets_to_client{user="hello"} 4176892497212 (3.80 TB)
telemt_user_unique_ips_current{user="hello"} 399
telemt_user_unique_ips_recent_window{user="hello"} 388
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 158599.1 (44h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10873789
telemt_connections_bad_total 1215191
telemt_connections_current 1732
telemt_connections_me_current 1732
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 280527
telemt_upstream_connect_attempt_total 85388
telemt_upstream_connect_success_total 84733
telemt_upstream_connect_fail_total 561
telemt_upstream_connect_attempts_per_request{bucket="1"} 85294
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 46585
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35209
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 910
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2029
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 561
telemt_me_reconnect_attempts_total 9003
telemt_me_reconnect_success_total 2069
telemt_me_reader_eof_total 1928
telemt_me_idle_close_by_peer_total 1928
telemt_me_seq_mismatch_total 75
telemt_me_route_drop_no_conn_total 5426496
telemt_me_route_drop_channel_closed_total 348
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8408324
telemt_me_endpoint_quarantine_total 1211
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 41
telemt_me_single_endpoint_outage_exit_total 41
telemt_me_single_endpoint_outage_reconnect_attempt_total 41
telemt_me_single_endpoint_outage_reconnect_success_total 39
telemt_me_single_endpoint_quarantine_bypass_total 41
telemt_me_single_endpoint_shadow_rotate_total 1188
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
telemt_desync_total 38363
telemt_desync_full_logged_total 12391
telemt_desync_suppressed_total 25972
telemt_desync_frames_bucket_total{bucket="1_2"} 9538
telemt_desync_frames_bucket_total{bucket="3_10"} 14295
telemt_desync_frames_bucket_total{bucket="gt_10"} 14530
telemt_pool_swap_total 168
telemt_pool_force_close_total 4672
telemt_pool_stale_pick_total 360
telemt_me_writer_close_signal_drop_total 607
telemt_me_draining_writers_reap_progress_total 53127
telemt_me_writer_removed_unexpected_total 1954
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5498
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 49652
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4233
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 439
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 48455
telemt_me_writer_teardown_success_total{mode="normal"} 55150
telemt_me_writer_teardown_noop_total 53132
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 105759
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 107403
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 107915
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 108232
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 108282
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 108282
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 108282
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 108282
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 108282
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 108282
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 108282
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 108282
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 108282
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 16.597751
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 108282
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 607
telemt_me_refill_failed_total 356
telemt_me_writer_restored_same_endpoint_total 1676
telemt_me_writer_restored_fallback_total 100
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 128
telemt_me_writer_removed_unexpected_minus_restored_total 178
telemt_user_connections_total{user="hello"} 8414292
telemt_user_connections_current{user="hello"} 1732
telemt_user_octets_from_client{user="hello"} 148072794141 (137.90 GB)
telemt_user_octets_to_client{user="hello"} 3215270439947 (2.92 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 604
telemt_user_unique_ips_recent_window{user="hello"} 283
```