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

# Server Metrics 2026-03-22 12:02:50 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 53787.7 (14h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1589530
telemt_connections_bad_total 75319
telemt_connections_current 1831
telemt_connections_me_current 1831
telemt_handshake_timeouts_total 71612
telemt_upstream_connect_attempt_total 20521
telemt_upstream_connect_success_total 20520
telemt_upstream_connect_attempts_per_request{bucket="1"} 20520
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7060
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13396
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 51
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 754
telemt_me_reconnect_success_total 339
telemt_me_reader_eof_total 336
telemt_me_idle_close_by_peer_total 336
telemt_me_route_drop_no_conn_total 1083886
telemt_me_route_drop_channel_closed_total 475
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1343884
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_endpoint_quarantine_total 379
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 3
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 431
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 14
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
telemt_desync_total 8037
telemt_desync_full_logged_total 2403
telemt_desync_suppressed_total 5634
telemt_desync_frames_bucket_total{bucket="1_2"} 2285
telemt_desync_frames_bucket_total{bucket="3_10"} 3025
telemt_desync_frames_bucket_total{bucket="gt_10"} 2727
telemt_pool_swap_total 59
telemt_pool_force_close_total 1762
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 275
telemt_me_draining_writers_reap_progress_total 18703
telemt_me_writer_removed_unexpected_total 331
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1314
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17598
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1727
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 35
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16941
telemt_me_writer_teardown_success_total{mode="normal"} 18912
telemt_me_writer_teardown_noop_total 18705
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 32224
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 33354
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 34310
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 35834
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 36951
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 37479
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 37614
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 37617
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 37617
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 37617
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 37617
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 37617
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 37617
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 132.453594
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 37617
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 275
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 302
telemt_me_writer_removed_unexpected_minus_restored_total 29
telemt_user_connections_total{user="hello"} 1341224
telemt_user_connections_current{user="hello"} 1831
telemt_user_octets_from_client{user="hello"} 21050463184 (19.60 GB)
telemt_user_octets_to_client{user="hello"} 397191429300 (369.91 GB)
telemt_user_unique_ips_current{user="hello"} 694
telemt_user_unique_ips_recent_window{user="hello"} 259
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 67153.9 (18h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2566090
telemt_connections_bad_total 227441
telemt_connections_current 1601
telemt_connections_me_current 1601
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 58868
telemt_upstream_connect_attempt_total 44511
telemt_upstream_connect_success_total 43994
telemt_upstream_connect_fail_total 457
telemt_upstream_connect_attempts_per_request{bucket="1"} 44451
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26874
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17004
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 116
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 457
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 3403
telemt_me_reconnect_success_total 1513
telemt_me_reader_eof_total 1396
telemt_me_idle_close_by_peer_total 1396
telemt_me_route_drop_no_conn_total 2236500
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2015946
telemt_me_endpoint_quarantine_total 573
telemt_me_single_endpoint_outage_enter_total 31
telemt_me_single_endpoint_outage_exit_total 31
telemt_me_single_endpoint_outage_reconnect_attempt_total 31
telemt_me_single_endpoint_outage_reconnect_success_total 31
telemt_me_single_endpoint_quarantine_bypass_total 31
telemt_me_single_endpoint_shadow_rotate_total 528
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
telemt_desync_total 7981
telemt_desync_full_logged_total 4499
telemt_desync_suppressed_total 3482
telemt_desync_frames_bucket_total{bucket="1_2"} 1856
telemt_desync_frames_bucket_total{bucket="3_10"} 3107
telemt_desync_frames_bucket_total{bucket="gt_10"} 3018
telemt_pool_swap_total 67
telemt_pool_force_close_total 1890
telemt_me_writer_close_signal_drop_total 157
telemt_me_draining_writers_reap_progress_total 26751
telemt_me_writer_removed_unexpected_total 1358
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2937
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 25170
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1680
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 210
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 24861
telemt_me_writer_teardown_success_total{mode="normal"} 28107
telemt_me_writer_teardown_noop_total 26751
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 53671
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 54390
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 54611
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 54837
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 54855
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 54858
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 54858
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 54858
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 54858
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 54858
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 54858
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 54858
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 54858
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.273431
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 54858
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 157
telemt_me_refill_failed_total 85
telemt_me_writer_restored_same_endpoint_total 1257
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 21
telemt_me_writer_removed_unexpected_minus_restored_total 79
telemt_user_connections_total{user="hello"} 2027737
telemt_user_connections_current{user="hello"} 1601
telemt_user_octets_from_client{user="hello"} 25278190559 (23.54 GB)
telemt_user_octets_to_client{user="hello"} 498861262654 (464.60 GB)
telemt_user_msgs_from_client{user="hello"} 42816
telemt_user_msgs_to_client{user="hello"} 172415
telemt_user_unique_ips_current{user="hello"} 983
telemt_user_unique_ips_recent_window{user="hello"} 601
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 142013.9 (39h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12615903
telemt_connections_bad_total 1094095
telemt_connections_current 5986
telemt_connections_me_current 5986
telemt_handshake_timeouts_total 328755
telemt_upstream_connect_attempt_total 51728
telemt_upstream_connect_success_total 51648
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 51656
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23371
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28056
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 215
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2255
telemt_me_reconnect_success_total 1182
telemt_me_reader_eof_total 1152
telemt_me_idle_close_by_peer_total 1151
telemt_me_route_drop_no_conn_total 10309908
telemt_me_route_drop_channel_closed_total 112
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10084243
telemt_me_endpoint_quarantine_total 894
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 1058
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 39
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
telemt_me_writers_active_current 94
telemt_desync_total 41382
telemt_desync_full_logged_total 13244
telemt_desync_suppressed_total 28138
telemt_desync_frames_bucket_total{bucket="1_2"} 9325
telemt_desync_frames_bucket_total{bucket="3_10"} 16171
telemt_desync_frames_bucket_total{bucket="gt_10"} 15886
telemt_pool_swap_total 152
telemt_pool_force_close_total 5130
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 809
telemt_me_draining_writers_reap_progress_total 47118
telemt_me_writer_removed_unexpected_total 1113
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4071
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 43555
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4787
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 343
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 41988
telemt_me_writer_teardown_success_total{mode="normal"} 47626
telemt_me_writer_teardown_noop_total 47162
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 86277
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 88975
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 90329
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 92243
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 93603
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 94363
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 94776
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 94788
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 94788
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 94788
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 94788
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 94788
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 94788
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 218.778167
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 94788
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 809
telemt_me_refill_failed_total 58
telemt_me_writer_restored_same_endpoint_total 1033
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 73
telemt_user_connections_total{user="hello"} 10073022
telemt_user_connections_current{user="hello"} 5986
telemt_user_octets_from_client{user="hello"} 149462422904 (139.20 GB)
telemt_user_octets_to_client{user="hello"} 2817645843120 (2.56 TB)
telemt_user_unique_ips_current{user="hello"} 2360
telemt_user_unique_ips_recent_window{user="hello"} 801
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 142015.2 (39h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9509194
telemt_connections_bad_total 861176
telemt_connections_current 4363
telemt_connections_me_current 4363
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 287588
telemt_upstream_connect_attempt_total 78149
telemt_upstream_connect_success_total 77025
telemt_upstream_connect_fail_total 810
telemt_upstream_connect_attempts_per_request{bucket="1"} 77835
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 42558
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30643
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 156
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3668
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 810
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 182
telemt_me_reconnect_attempts_total 3319
telemt_me_reconnect_success_total 1346
telemt_me_reader_eof_total 1229
telemt_me_idle_close_by_peer_total 1229
telemt_me_route_drop_no_conn_total 3819322
telemt_me_route_drop_channel_closed_total 391
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7084724
telemt_me_endpoint_quarantine_total 894
telemt_me_single_endpoint_outage_enter_total 22
telemt_me_single_endpoint_outage_exit_total 22
telemt_me_single_endpoint_outage_reconnect_attempt_total 27
telemt_me_single_endpoint_outage_reconnect_success_total 20
telemt_me_single_endpoint_quarantine_bypass_total 27
telemt_me_single_endpoint_shadow_rotate_total 1085
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 39
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
telemt_desync_total 32056
telemt_desync_full_logged_total 10847
telemt_desync_suppressed_total 21209
telemt_desync_frames_bucket_total{bucket="1_2"} 7886
telemt_desync_frames_bucket_total{bucket="3_10"} 12348
telemt_desync_frames_bucket_total{bucket="gt_10"} 11822
telemt_pool_swap_total 152
telemt_pool_force_close_total 4637
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 566
telemt_me_draining_writers_reap_progress_total 45541
telemt_me_writer_removed_unexpected_total 1262
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4057
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 42612
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4265
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 372
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 40904
telemt_me_writer_teardown_success_total{mode="normal"} 46669
telemt_me_writer_teardown_noop_total 45549
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 87007
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 89478
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 90386
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 91305
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 91917
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 92179
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 92208
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 92210
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 92216
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 92218
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 92218
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 92218
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 92218
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 80.092002
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 92218
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 566
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 1147
telemt_me_writer_restored_fallback_total 12
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 212
telemt_me_writer_removed_unexpected_minus_restored_total 103
telemt_user_connections_total{user="hello"} 7025424
telemt_user_connections_current{user="hello"} 4363
telemt_user_octets_from_client{user="hello"} 182283215093 (169.76 GB)
telemt_user_octets_to_client{user="hello"} 3210012667962 (2.92 TB)
telemt_user_msgs_from_client{user="hello"} 113340
telemt_user_msgs_to_client{user="hello"} 116189
telemt_user_unique_ips_current{user="hello"} 1650
telemt_user_unique_ips_recent_window{user="hello"} 725
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 141978.8 (39h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8978765
telemt_connections_bad_total 755706
telemt_connections_current 5309
telemt_connections_me_current 5309
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 284718
telemt_upstream_connect_attempt_total 62487
telemt_upstream_connect_success_total 61758
telemt_upstream_connect_fail_total 147
telemt_upstream_connect_attempts_per_request{bucket="1"} 61905
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30103
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29193
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1049
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1413
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 147
telemt_me_keepalive_timeout_total 238
telemt_me_reconnect_attempts_total 3794
telemt_me_reconnect_success_total 1599
telemt_me_reader_eof_total 1481
telemt_me_idle_close_by_peer_total 1481
telemt_me_route_drop_no_conn_total 3821899
telemt_me_route_drop_channel_closed_total 263
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6756488
telemt_me_endpoint_quarantine_total 972
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 19
telemt_me_single_endpoint_outage_reconnect_success_total 15
telemt_me_single_endpoint_quarantine_bypass_total 19
telemt_me_single_endpoint_shadow_rotate_total 1037
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 52
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
telemt_desync_total 31628
telemt_desync_full_logged_total 10611
telemt_desync_suppressed_total 21017
telemt_desync_frames_bucket_total{bucket="1_2"} 7916
telemt_desync_frames_bucket_total{bucket="3_10"} 12151
telemt_desync_frames_bucket_total{bucket="gt_10"} 11561
telemt_pool_swap_total 148
telemt_pool_force_close_total 4585
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 552
telemt_me_draining_writers_reap_progress_total 46315
telemt_me_writer_removed_unexpected_total 1513
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4440
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 43326
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 20
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4111
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 474
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 41730
telemt_me_writer_teardown_success_total{mode="normal"} 47766
telemt_me_writer_teardown_noop_total 46335
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 89708
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 91858
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 92632
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 93468
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 93890
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 94036
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 94097
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 94099
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 94101
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 94101
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 94101
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 94101
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 94101
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 59.685654
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 94101
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 552
telemt_me_refill_failed_total 113
telemt_me_writer_restored_same_endpoint_total 1416
telemt_me_writer_restored_fallback_total 7
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 50
telemt_me_writer_removed_unexpected_minus_restored_total 90
telemt_user_connections_total{user="hello"} 6747482
telemt_user_connections_current{user="hello"} 5309
telemt_user_octets_from_client{user="hello"} 164686112335 (153.38 GB)
telemt_user_octets_to_client{user="hello"} 2911977245739 (2.65 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 2003
telemt_user_unique_ips_recent_window{user="hello"} 735
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 12259.0 (3h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5201858
telemt_connections_bad_total 315361
telemt_connections_current 7099
telemt_connections_me_current 7099
telemt_relay_adaptive_promotions_total 7
telemt_relay_adaptive_hard_promotions_total 7
telemt_handshake_timeouts_total 81893
telemt_upstream_connect_attempt_total 23632
telemt_upstream_connect_success_total 22578
telemt_upstream_connect_fail_total 835
telemt_upstream_connect_attempts_per_request{bucket="1"} 23413
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13030
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4662
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 262
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4624
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 835
telemt_me_keepalive_timeout_total 474
telemt_me_reconnect_attempts_total 2286
telemt_me_reconnect_success_total 349
telemt_me_reader_eof_total 219
telemt_me_idle_close_by_peer_total 219
telemt_me_route_drop_no_conn_total 12057609
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 16
telemt_me_route_drop_queue_full_profile_total{profile="high"} 16
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4355683
telemt_me_endpoint_quarantine_total 84
telemt_me_single_endpoint_outage_enter_total 22
telemt_me_single_endpoint_outage_exit_total 22
telemt_me_single_endpoint_outage_reconnect_attempt_total 39
telemt_me_single_endpoint_outage_reconnect_success_total 12
telemt_me_single_endpoint_quarantine_bypass_total 39
telemt_me_single_endpoint_shadow_rotate_total 103
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
telemt_me_writers_active_current 45
telemt_desync_total 6472
telemt_desync_full_logged_total 1667
telemt_desync_suppressed_total 4805
telemt_desync_frames_bucket_total{bucket="1_2"} 1206
telemt_desync_frames_bucket_total{bucket="3_10"} 2571
telemt_desync_frames_bucket_total{bucket="gt_10"} 2695
telemt_pool_swap_total 11
telemt_pool_force_close_total 473
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 192
telemt_me_draining_writers_reap_progress_total 3195
telemt_me_writer_removed_unexpected_total 308
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 569
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 2890
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 335
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 138
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 2722
telemt_me_writer_teardown_success_total{mode="normal"} 3459
telemt_me_writer_teardown_noop_total 3198
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 5358
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 5950
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 6219
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 6497
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 6604
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 6656
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 6657
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 6657
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 6657
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 6657
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 6657
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 6657
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 6657
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 15.720718
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 6657
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 192
telemt_me_refill_failed_total 107
telemt_me_writer_restored_same_endpoint_total 234
telemt_me_writer_restored_fallback_total 3
telemt_me_async_recovery_trigger_total 204
telemt_me_writer_removed_unexpected_minus_restored_total 71
telemt_user_connections_total{user="hello"} 4370269
telemt_user_connections_current{user="hello"} 7099
telemt_user_octets_from_client{user="hello"} 23954548766 (22.31 GB)
telemt_user_octets_to_client{user="hello"} 127335960559 (118.59 GB)
telemt_user_msgs_from_client{user="hello"} 33078
telemt_user_msgs_to_client{user="hello"} 29827
telemt_user_unique_ips_current{user="hello"} 2523
telemt_user_unique_ips_recent_window{user="hello"} 1510
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 141986.1 (39h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8721101
telemt_connections_bad_total 744210
telemt_connections_current 5538
telemt_connections_me_current 5538
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 183780
telemt_upstream_connect_attempt_total 87687
telemt_upstream_connect_success_total 86817
telemt_upstream_connect_fail_total 748
telemt_upstream_connect_attempts_per_request{bucket="1"} 87565
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 54193
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31172
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 208
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1244
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 748
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 70766
telemt_me_reconnect_success_total 2265
telemt_me_reader_eof_total 1996
telemt_me_idle_close_by_peer_total 1995
telemt_me_route_drop_no_conn_total 3986362
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 45
telemt_me_route_drop_queue_full_profile_total{profile="high"} 45
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6894151
telemt_me_endpoint_quarantine_total 945
telemt_me_single_endpoint_outage_enter_total 30
telemt_me_single_endpoint_outage_exit_total 30
telemt_me_single_endpoint_outage_reconnect_attempt_total 32
telemt_me_single_endpoint_outage_reconnect_success_total 30
telemt_me_single_endpoint_quarantine_bypass_total 32
telemt_me_single_endpoint_shadow_rotate_total 1064
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
telemt_me_writers_active_current 90
telemt_desync_total 35249
telemt_desync_full_logged_total 12138
telemt_desync_suppressed_total 23111
telemt_desync_frames_bucket_total{bucket="1_2"} 7201
telemt_desync_frames_bucket_total{bucket="3_10"} 13542
telemt_desync_frames_bucket_total{bucket="gt_10"} 14506
telemt_pool_swap_total 146
telemt_pool_force_close_total 4253
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 516
telemt_me_draining_writers_reap_progress_total 48596
telemt_me_writer_removed_unexpected_total 2025
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5047
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 45599
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3708
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 545
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 44343
telemt_me_writer_teardown_success_total{mode="normal"} 50646
telemt_me_writer_teardown_noop_total 48597
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 97553
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 98630
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 98959
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 99202
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 99233
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 99236
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 99236
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 99239
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 99243
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 99243
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 99243
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 99243
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 99243
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.848140
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 99243
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 516
telemt_me_refill_failed_total 4235
telemt_me_writer_restored_same_endpoint_total 1888
telemt_me_writer_restored_fallback_total 41
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7333
telemt_me_writer_removed_unexpected_minus_restored_total 96
telemt_user_connections_total{user="hello"} 6896979
telemt_user_connections_current{user="hello"} 5538
telemt_user_octets_from_client{user="hello"} 164068990791 (152.80 GB)
telemt_user_octets_to_client{user="hello"} 2685657894541 (2.44 TB)
telemt_user_msgs_from_client{user="hello"} 146235
telemt_user_msgs_to_client{user="hello"} 572261
telemt_user_unique_ips_current{user="hello"} 2256
telemt_user_unique_ips_recent_window{user="hello"} 801
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 78822.0 (21h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8102996
telemt_connections_bad_total 290547
telemt_connections_current 4226
telemt_connections_me_current 4226
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 3370101
telemt_upstream_connect_attempt_total 40032
telemt_upstream_connect_success_total 39744
telemt_upstream_connect_fail_total 281
telemt_upstream_connect_attempts_per_request{bucket="1"} 40025
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23017
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16619
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 108
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 281
telemt_me_reconnect_attempts_total 47793
telemt_me_reconnect_success_total 1348
telemt_me_reader_eof_total 1016
telemt_me_idle_close_by_peer_total 1016
telemt_me_route_drop_no_conn_total 2648908
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3962343
telemt_me_endpoint_quarantine_total 533
telemt_me_single_endpoint_outage_enter_total 17
telemt_me_single_endpoint_outage_exit_total 17
telemt_me_single_endpoint_outage_reconnect_attempt_total 57
telemt_me_single_endpoint_outage_reconnect_success_total 17
telemt_me_single_endpoint_quarantine_bypass_total 57
telemt_me_single_endpoint_shadow_rotate_total 599
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
telemt_me_writers_active_current 45
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 21745
telemt_desync_full_logged_total 7284
telemt_desync_suppressed_total 14461
telemt_desync_frames_bucket_total{bucket="1_2"} 4444
telemt_desync_frames_bucket_total{bucket="3_10"} 8423
telemt_desync_frames_bucket_total{bucket="gt_10"} 8878
telemt_pool_swap_total 83
telemt_pool_force_close_total 2550
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 256
telemt_me_draining_writers_reap_progress_total 27670
telemt_me_writer_removed_unexpected_total 1083
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2467
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 26312
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2186
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 364
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 25120
telemt_me_writer_teardown_success_total{mode="normal"} 28779
telemt_me_writer_teardown_noop_total 27677
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 55567
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 56074
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 56299
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 56456
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 56456
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 56456
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 56456
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 56456
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 56456
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 56456
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 56456
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 56456
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 56456
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.732434
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 56456
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 256
telemt_me_refill_failed_total 2700
telemt_me_writer_restored_same_endpoint_total 1200
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4328
telemt_user_connections_total{user="hello"} 3959523
telemt_user_connections_current{user="hello"} 4226
telemt_user_octets_from_client{user="hello"} 90545247600 (84.33 GB)
telemt_user_octets_to_client{user="hello"} 1577441285438 (1.43 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 1637
telemt_user_unique_ips_recent_window{user="hello"} 812
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 59792.8 (16h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 654093
telemt_connections_bad_total 6915
telemt_connections_current 985
telemt_connections_me_current 985
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 12623
telemt_upstream_connect_attempt_total 30958
telemt_upstream_connect_success_total 30882
telemt_upstream_connect_fail_total 65
telemt_upstream_connect_attempts_per_request{bucket="1"} 30947
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14278
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16255
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 349
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 65
telemt_me_reconnect_attempts_total 1388
telemt_me_reconnect_success_total 598
telemt_me_reader_eof_total 578
telemt_me_idle_close_by_peer_total 578
telemt_me_route_drop_no_conn_total 217842
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 590271
telemt_me_endpoint_quarantine_total 547
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 504
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
telemt_me_writers_active_current 44
telemt_desync_total 3253
telemt_desync_full_logged_total 947
telemt_desync_suppressed_total 2306
telemt_desync_frames_bucket_total{bucket="1_2"} 829
telemt_desync_frames_bucket_total{bucket="3_10"} 1284
telemt_desync_frames_bucket_total{bucket="gt_10"} 1140
telemt_pool_swap_total 63
telemt_pool_force_close_total 1544
telemt_me_writer_close_signal_drop_total 84
telemt_me_draining_writers_reap_progress_total 25262
telemt_me_writer_removed_unexpected_total 560
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1918
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 23923
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1467
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 77
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 23718
telemt_me_writer_teardown_success_total{mode="normal"} 25841
telemt_me_writer_teardown_noop_total 25264
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 50598
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 50979
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 51080
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 51105
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 51105
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 51105
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 51105
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 51105
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 51105
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 51105
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 51105
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 51105
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 51105
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.760183
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 51105
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 84
telemt_me_refill_failed_total 43
telemt_me_writer_restored_same_endpoint_total 520
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 34
telemt_user_connections_total{user="hello"} 592081
telemt_user_connections_current{user="hello"} 985
telemt_user_octets_from_client{user="hello"} 11205704293 (10.44 GB)
telemt_user_octets_to_client{user="hello"} 278188293167 (259.08 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 371
telemt_user_unique_ips_recent_window{user="hello"} 154
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 141990.8 (39h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10568298
telemt_connections_bad_total 1237206
telemt_connections_current 5681
telemt_connections_me_current 5681
telemt_handshake_timeouts_total 281731
telemt_upstream_connect_attempt_total 54097
telemt_upstream_connect_success_total 53888
telemt_upstream_connect_fail_total 161
telemt_upstream_connect_attempts_per_request{bucket="1"} 54049
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26596
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27246
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 45
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 161
telemt_me_reconnect_attempts_total 2115
telemt_me_reconnect_success_total 1128
telemt_me_reader_eof_total 1090
telemt_me_idle_close_by_peer_total 1090
telemt_me_route_drop_no_conn_total 3111475
telemt_me_route_drop_channel_closed_total 83
telemt_me_route_drop_queue_full_total 31
telemt_me_route_drop_queue_full_profile_total{profile="high"} 31
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7903869
telemt_me_endpoint_quarantine_total 986
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 12
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 12
telemt_me_single_endpoint_shadow_rotate_total 1068
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 39
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
telemt_desync_total 32369
telemt_desync_full_logged_total 10646
telemt_desync_suppressed_total 21723
telemt_desync_frames_bucket_total{bucket="1_2"} 7817
telemt_desync_frames_bucket_total{bucket="3_10"} 11918
telemt_desync_frames_bucket_total{bucket="gt_10"} 12634
telemt_pool_swap_total 157
telemt_pool_force_close_total 4284
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 531
telemt_me_draining_writers_reap_progress_total 48765
telemt_me_writer_removed_unexpected_total 1046
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3970
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 45876
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4147
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 137
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 44481
telemt_me_writer_teardown_success_total{mode="normal"} 49846
telemt_me_writer_teardown_noop_total 48767
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 96708
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 97999
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 98254
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 98509
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 98609
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 98613
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 98613
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 98613
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 98613
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 98613
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 98613
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 98613
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 98613
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.202872
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 98613
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 531
telemt_me_refill_failed_total 51
telemt_me_writer_restored_same_endpoint_total 985
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 50
telemt_user_connections_total{user="hello"} 7875188
telemt_user_connections_current{user="hello"} 5681
telemt_user_octets_from_client{user="hello"} 152737227516 (142.25 GB)
telemt_user_octets_to_client{user="hello"} 3638221723836 (3.31 TB)
telemt_user_unique_ips_current{user="hello"} 1990
telemt_user_unique_ips_recent_window{user="hello"} 876
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 141987.7 (39h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9249159
telemt_connections_bad_total 1049466
telemt_connections_current 5779
telemt_connections_me_current 5779
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 239409
telemt_upstream_connect_attempt_total 78772
telemt_upstream_connect_success_total 78203
telemt_upstream_connect_fail_total 496
telemt_upstream_connect_attempts_per_request{bucket="1"} 78699
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 43514
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31805
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 909
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1975
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 496
telemt_me_reconnect_attempts_total 6703
telemt_me_reconnect_success_total 1634
telemt_me_reader_eof_total 1455
telemt_me_idle_close_by_peer_total 1455
telemt_me_seq_mismatch_total 68
telemt_me_route_drop_no_conn_total 3650999
telemt_me_route_drop_channel_closed_total 288
telemt_me_route_drop_queue_full_total 15
telemt_me_route_drop_queue_full_profile_total{profile="high"} 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7090992
telemt_me_endpoint_quarantine_total 1095
telemt_me_single_endpoint_outage_enter_total 35
telemt_me_single_endpoint_outage_exit_total 35
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 33
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 1075
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
telemt_me_writers_active_current 90
telemt_desync_total 31656
telemt_desync_full_logged_total 10362
telemt_desync_suppressed_total 21294
telemt_desync_frames_bucket_total{bucket="1_2"} 7799
telemt_desync_frames_bucket_total{bucket="3_10"} 11774
telemt_desync_frames_bucket_total{bucket="gt_10"} 12083
telemt_pool_swap_total 153
telemt_pool_force_close_total 4179
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 521
telemt_me_draining_writers_reap_progress_total 47515
telemt_me_writer_removed_unexpected_total 1475
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4653
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 44402
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3866
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 313
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 43336
telemt_me_writer_teardown_success_total{mode="normal"} 49055
telemt_me_writer_teardown_noop_total 47519
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 94391
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 95809
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 96276
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 96536
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 96574
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 96574
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 96574
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 96574
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 96574
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 96574
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 96574
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 96574
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 96574
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.134309
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 96574
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 521
telemt_me_refill_failed_total 291
telemt_me_writer_restored_same_endpoint_total 1283
telemt_me_writer_restored_fallback_total 92
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 128
telemt_me_writer_removed_unexpected_minus_restored_total 100
telemt_user_connections_total{user="hello"} 7098862
telemt_user_connections_current{user="hello"} 5779
telemt_user_octets_from_client{user="hello"} 126773985473 (118.07 GB)
telemt_user_octets_to_client{user="hello"} 2891289243027 (2.63 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 2214
telemt_user_unique_ips_recent_window{user="hello"} 935
```