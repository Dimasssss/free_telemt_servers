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

# Server Metrics 2026-03-22 11:17:00 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 51036.6 (14h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1424205
telemt_connections_bad_total 71256
telemt_connections_current 1791
telemt_connections_me_current 1791
telemt_handshake_timeouts_total 64862
telemt_upstream_connect_attempt_total 19609
telemt_upstream_connect_success_total 19608
telemt_upstream_connect_attempts_per_request{bucket="1"} 19608
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6756
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12792
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 49
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 672
telemt_me_reconnect_success_total 323
telemt_me_reader_eof_total 318
telemt_me_idle_close_by_peer_total 318
telemt_me_route_drop_no_conn_total 855228
telemt_me_route_drop_channel_closed_total 419
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1197472
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_endpoint_quarantine_total 361
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 410
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 12
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
telemt_desync_total 7565
telemt_desync_full_logged_total 2254
telemt_desync_suppressed_total 5311
telemt_desync_frames_bucket_total{bucket="1_2"} 2178
telemt_desync_frames_bucket_total{bucket="3_10"} 2837
telemt_desync_frames_bucket_total{bucket="gt_10"} 2550
telemt_pool_swap_total 56
telemt_pool_force_close_total 1630
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 240
telemt_me_draining_writers_reap_progress_total 17834
telemt_me_writer_removed_unexpected_total 313
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1259
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16808
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1595
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 35
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16204
telemt_me_writer_teardown_success_total{mode="normal"} 18067
telemt_me_writer_teardown_noop_total 17836
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 31361
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 32366
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 33179
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 34460
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 35367
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 35807
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 35903
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 35903
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 35903
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 35903
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 35903
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 35903
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 35903
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 106.816749
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 35903
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 240
telemt_me_refill_failed_total 18
telemt_me_writer_restored_same_endpoint_total 289
telemt_me_writer_removed_unexpected_minus_restored_total 24
telemt_user_connections_total{user="hello"} 1195057
telemt_user_connections_current{user="hello"} 1791
telemt_user_octets_from_client{user="hello"} 19195206636 (17.88 GB)
telemt_user_octets_to_client{user="hello"} 370068100464 (344.65 GB)
telemt_user_unique_ips_current{user="hello"} 695
telemt_user_unique_ips_recent_window{user="hello"} 391
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 64402.8 (17h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2295911
telemt_connections_bad_total 190440
telemt_connections_current 1863
telemt_connections_me_current 1863
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 53599
telemt_upstream_connect_attempt_total 43316
telemt_upstream_connect_success_total 42811
telemt_upstream_connect_fail_total 445
telemt_upstream_connect_attempts_per_request{bucket="1"} 43256
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26375
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16327
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 109
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 445
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 3325
telemt_me_reconnect_success_total 1458
telemt_me_reader_eof_total 1339
telemt_me_idle_close_by_peer_total 1339
telemt_me_route_drop_no_conn_total 1850612
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1805033
telemt_me_endpoint_quarantine_total 555
telemt_me_single_endpoint_outage_enter_total 30
telemt_me_single_endpoint_outage_exit_total 30
telemt_me_single_endpoint_outage_reconnect_attempt_total 30
telemt_me_single_endpoint_outage_reconnect_success_total 30
telemt_me_single_endpoint_quarantine_bypass_total 30
telemt_me_single_endpoint_shadow_rotate_total 509
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
telemt_me_writers_active_current 45
telemt_desync_total 7295
telemt_desync_full_logged_total 4120
telemt_desync_suppressed_total 3175
telemt_desync_frames_bucket_total{bucket="1_2"} 1667
telemt_desync_frames_bucket_total{bucket="3_10"} 2868
telemt_desync_frames_bucket_total{bucket="gt_10"} 2760
telemt_pool_swap_total 65
telemt_pool_force_close_total 1814
telemt_me_writer_close_signal_drop_total 150
telemt_me_draining_writers_reap_progress_total 25681
telemt_me_writer_removed_unexpected_total 1302
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2830
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 24150
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1626
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 188
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 23867
telemt_me_writer_teardown_success_total{mode="normal"} 26980
telemt_me_writer_teardown_noop_total 25681
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 51531
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 52206
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 52424
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 52641
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 52659
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 52661
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 52661
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 52661
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 52661
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 52661
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 52661
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 52661
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 52661
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.886677
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 52661
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 150
telemt_me_refill_failed_total 84
telemt_me_writer_restored_same_endpoint_total 1205
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 21
telemt_me_writer_removed_unexpected_minus_restored_total 75
telemt_user_connections_total{user="hello"} 1816944
telemt_user_connections_current{user="hello"} 1863
telemt_user_octets_from_client{user="hello"} 23571581327 (21.95 GB)
telemt_user_octets_to_client{user="hello"} 470584512678 (438.27 GB)
telemt_user_msgs_from_client{user="hello"} 42816
telemt_user_msgs_to_client{user="hello"} 172415
telemt_user_unique_ips_current{user="hello"} 1155
telemt_user_unique_ips_recent_window{user="hello"} 989
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 139262.8 (38h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12002589
telemt_connections_bad_total 1028970
telemt_connections_current 5500
telemt_connections_me_current 5500
telemt_handshake_timeouts_total 318720
telemt_upstream_connect_attempt_total 50669
telemt_upstream_connect_success_total 50589
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 50597
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22876
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27499
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2170
telemt_me_reconnect_success_total 1113
telemt_me_reader_eof_total 1094
telemt_me_idle_close_by_peer_total 1093
telemt_me_route_drop_no_conn_total 9330033
telemt_me_route_drop_channel_closed_total 104
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9583403
telemt_me_endpoint_quarantine_total 886
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 1036
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 38
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
telemt_desync_total 39407
telemt_desync_full_logged_total 12672
telemt_desync_suppressed_total 26735
telemt_desync_frames_bucket_total{bucket="1_2"} 8872
telemt_desync_frames_bucket_total{bucket="3_10"} 15375
telemt_desync_frames_bucket_total{bucket="gt_10"} 15160
telemt_pool_swap_total 150
telemt_pool_force_close_total 5043
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 785
telemt_me_draining_writers_reap_progress_total 46206
telemt_me_writer_removed_unexpected_total 1054
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3962
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 42710
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4709
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 334
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 41163
telemt_me_writer_teardown_success_total{mode="normal"} 46672
telemt_me_writer_teardown_noop_total 46250
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 84621
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 87230
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 88555
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 90440
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 91777
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 92512
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 92910
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 92922
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 92922
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 92922
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 92922
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 92922
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 92922
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 212.322377
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 92922
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 785
telemt_me_refill_failed_total 57
telemt_me_writer_restored_same_endpoint_total 969
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 78
telemt_user_connections_total{user="hello"} 9572490
telemt_user_connections_current{user="hello"} 5500
telemt_user_octets_from_client{user="hello"} 144471474312 (134.55 GB)
telemt_user_octets_to_client{user="hello"} 2755163051844 (2.51 TB)
telemt_user_unique_ips_current{user="hello"} 2056
telemt_user_unique_ips_recent_window{user="hello"} 1221
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 139264.0 (38h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9149794
telemt_connections_bad_total 819096
telemt_connections_current 4068
telemt_connections_me_current 4068
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 279425
telemt_upstream_connect_attempt_total 57296
telemt_upstream_connect_success_total 56718
telemt_upstream_connect_fail_total 264
telemt_upstream_connect_attempts_per_request{bucket="1"} 56982
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27546
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27872
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 131
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1169
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 264
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 182
telemt_me_reconnect_attempts_total 3190
telemt_me_reconnect_success_total 1298
telemt_me_reader_eof_total 1190
telemt_me_idle_close_by_peer_total 1190
telemt_me_route_drop_no_conn_total 3712152
telemt_me_route_drop_channel_closed_total 381
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6821603
telemt_me_endpoint_quarantine_total 881
telemt_me_single_endpoint_outage_enter_total 21
telemt_me_single_endpoint_outage_exit_total 21
telemt_me_single_endpoint_outage_reconnect_attempt_total 26
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 26
telemt_me_single_endpoint_shadow_rotate_total 1066
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
telemt_me_writers_active_current 43
telemt_desync_total 30965
telemt_desync_full_logged_total 10457
telemt_desync_suppressed_total 20508
telemt_desync_frames_bucket_total{bucket="1_2"} 7599
telemt_desync_frames_bucket_total{bucket="3_10"} 11928
telemt_desync_frames_bucket_total{bucket="gt_10"} 11438
telemt_pool_swap_total 149
telemt_pool_force_close_total 4570
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 522
telemt_me_draining_writers_reap_progress_total 44799
telemt_me_writer_removed_unexpected_total 1223
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3945
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 41973
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4210
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 360
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 40229
telemt_me_writer_teardown_success_total{mode="normal"} 45918
telemt_me_writer_teardown_noop_total 44807
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 85753
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 88109
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 88969
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 89845
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 90446
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 90698
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 90725
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 90725
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 90725
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 90725
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 90725
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 90725
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 90725
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 69.536212
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 90725
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 522
telemt_me_refill_failed_total 103
telemt_me_writer_restored_same_endpoint_total 1114
telemt_me_writer_restored_fallback_total 12
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 212
telemt_me_writer_removed_unexpected_minus_restored_total 97
telemt_user_connections_total{user="hello"} 6743113
telemt_user_connections_current{user="hello"} 4068
telemt_user_octets_from_client{user="hello"} 176677328775 (164.54 GB)
telemt_user_octets_to_client{user="hello"} 3104327109242 (2.82 TB)
telemt_user_msgs_from_client{user="hello"} 42822
telemt_user_msgs_to_client{user="hello"} 51589
telemt_user_unique_ips_current{user="hello"} 1554
telemt_user_unique_ips_recent_window{user="hello"} 630
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 139229.8 (38h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8684286
telemt_connections_bad_total 720749
telemt_connections_current 4394
telemt_connections_me_current 4394
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 278098
telemt_upstream_connect_attempt_total 61464
telemt_upstream_connect_success_total 60753
telemt_upstream_connect_fail_total 147
telemt_upstream_connect_attempts_per_request{bucket="1"} 60900
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29692
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28663
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1008
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1390
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 147
telemt_me_keepalive_timeout_total 238
telemt_me_reconnect_attempts_total 3724
telemt_me_reconnect_success_total 1539
telemt_me_reader_eof_total 1428
telemt_me_idle_close_by_peer_total 1428
telemt_me_route_drop_no_conn_total 3675277
telemt_me_route_drop_channel_closed_total 249
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6527082
telemt_me_endpoint_quarantine_total 954
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 19
telemt_me_single_endpoint_outage_reconnect_success_total 15
telemt_me_single_endpoint_quarantine_bypass_total 19
telemt_me_single_endpoint_shadow_rotate_total 1019
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
telemt_me_writers_active_current 84
telemt_desync_total 30101
telemt_desync_full_logged_total 10249
telemt_desync_suppressed_total 19852
telemt_desync_frames_bucket_total{bucket="1_2"} 7314
telemt_desync_frames_bucket_total{bucket="3_10"} 11614
telemt_desync_frames_bucket_total{bucket="gt_10"} 11173
telemt_pool_swap_total 146
telemt_pool_force_close_total 4462
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 531
telemt_me_draining_writers_reap_progress_total 45412
telemt_me_writer_removed_unexpected_total 1454
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4311
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 42493
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 17
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4061
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 401
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 40950
telemt_me_writer_teardown_success_total{mode="normal"} 46804
telemt_me_writer_teardown_noop_total 45429
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 88041
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 90103
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 90850
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 91651
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 92044
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 92170
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 92229
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 92231
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 92233
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 92233
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 92233
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 92233
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 92233
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 56.077756
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 92233
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 531
telemt_me_refill_failed_total 113
telemt_me_writer_restored_same_endpoint_total 1358
telemt_me_writer_restored_fallback_total 7
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 50
telemt_me_writer_removed_unexpected_minus_restored_total 89
telemt_user_connections_total{user="hello"} 6518465
telemt_user_connections_current{user="hello"} 4394
telemt_user_octets_from_client{user="hello"} 160757757115 (149.72 GB)
telemt_user_octets_to_client{user="hello"} 2829742426847 (2.57 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 1915
telemt_user_unique_ips_recent_window{user="hello"} 585
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 9507.9 (2h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4050744
telemt_connections_bad_total 261821
telemt_connections_current 6446
telemt_connections_me_current 6446
telemt_relay_adaptive_promotions_total 7
telemt_relay_adaptive_hard_promotions_total 7
telemt_handshake_timeouts_total 61116
telemt_upstream_connect_attempt_total 22806
telemt_upstream_connect_success_total 21777
telemt_upstream_connect_fail_total 829
telemt_upstream_connect_attempts_per_request{bucket="1"} 22606
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12683
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4221
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 262
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4611
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 829
telemt_me_keepalive_timeout_total 415
telemt_me_reconnect_attempts_total 703
telemt_me_reconnect_success_total 312
telemt_me_reader_eof_total 190
telemt_me_idle_close_by_peer_total 190
telemt_me_route_drop_no_conn_total 9212106
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3376009
telemt_me_endpoint_quarantine_total 69
telemt_me_single_endpoint_outage_enter_total 21
telemt_me_single_endpoint_outage_exit_total 21
telemt_me_single_endpoint_outage_reconnect_attempt_total 38
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 38
telemt_me_single_endpoint_shadow_rotate_total 80
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
telemt_desync_total 4936
telemt_desync_full_logged_total 1292
telemt_desync_suppressed_total 3644
telemt_desync_frames_bucket_total{bucket="1_2"} 910
telemt_desync_frames_bucket_total{bucket="3_10"} 1979
telemt_desync_frames_bucket_total{bucket="gt_10"} 2047
telemt_pool_swap_total 8
telemt_pool_force_close_total 366
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 146
telemt_me_draining_writers_reap_progress_total 2504
telemt_me_writer_removed_unexpected_total 279
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 481
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 2265
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 243
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 123
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 2138
telemt_me_writer_teardown_success_total{mode="normal"} 2746
telemt_me_writer_teardown_noop_total 2507
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 4241
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 4707
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 4919
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 5144
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 5225
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 5252
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 5253
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 5253
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 5253
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 5253
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 5253
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 5253
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 5253
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 11.468887
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 5253
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 146
telemt_me_refill_failed_total 12
telemt_me_writer_restored_same_endpoint_total 205
telemt_me_writer_restored_fallback_total 3
telemt_me_async_recovery_trigger_total 58
telemt_me_writer_removed_unexpected_minus_restored_total 71
telemt_user_connections_total{user="hello"} 3391497
telemt_user_connections_current{user="hello"} 6446
telemt_user_octets_from_client{user="hello"} 18373095990 (17.11 GB)
telemt_user_octets_to_client{user="hello"} 99492850495 (92.66 GB)
telemt_user_msgs_from_client{user="hello"} 33078
telemt_user_msgs_to_client{user="hello"} 29827
telemt_user_unique_ips_current{user="hello"} 2345
telemt_user_unique_ips_recent_window{user="hello"} 1382
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 139234.6 (38h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8411150
telemt_connections_bad_total 732223
telemt_connections_current 5311
telemt_connections_me_current 5311
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 174433
telemt_upstream_connect_attempt_total 86754
telemt_upstream_connect_success_total 85896
telemt_upstream_connect_fail_total 738
telemt_upstream_connect_attempts_per_request{bucket="1"} 86634
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 53764
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30681
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 208
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1243
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 738
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 70675
telemt_me_reconnect_success_total 2185
telemt_me_reader_eof_total 1922
telemt_me_idle_close_by_peer_total 1921
telemt_me_route_drop_no_conn_total 3755457
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 45
telemt_me_route_drop_queue_full_profile_total{profile="high"} 45
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6641319
telemt_me_endpoint_quarantine_total 933
telemt_me_single_endpoint_outage_enter_total 28
telemt_me_single_endpoint_outage_exit_total 28
telemt_me_single_endpoint_outage_reconnect_attempt_total 30
telemt_me_single_endpoint_outage_reconnect_success_total 28
telemt_me_single_endpoint_quarantine_bypass_total 30
telemt_me_single_endpoint_shadow_rotate_total 1046
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
telemt_me_writers_active_current 43
telemt_desync_total 33866
telemt_desync_full_logged_total 11662
telemt_desync_suppressed_total 22204
telemt_desync_frames_bucket_total{bucket="1_2"} 6962
telemt_desync_frames_bucket_total{bucket="3_10"} 12998
telemt_desync_frames_bucket_total{bucket="gt_10"} 13906
telemt_pool_swap_total 144
telemt_pool_force_close_total 4191
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 505
telemt_me_draining_writers_reap_progress_total 47893
telemt_me_writer_removed_unexpected_total 1951
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4934
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 44935
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3651
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 540
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 43702
telemt_me_writer_teardown_success_total{mode="normal"} 49869
telemt_me_writer_teardown_noop_total 47894
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 96097
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 97153
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 97479
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 97722
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 97753
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 97756
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 97756
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 97759
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 97763
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 97763
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 97763
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 97763
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 97763
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.745762
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 97763
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 505
telemt_me_refill_failed_total 4235
telemt_me_writer_restored_same_endpoint_total 1816
telemt_me_writer_restored_fallback_total 41
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7333
telemt_me_writer_removed_unexpected_minus_restored_total 94
telemt_user_connections_total{user="hello"} 6644516
telemt_user_connections_current{user="hello"} 5311
telemt_user_octets_from_client{user="hello"} 158945042483 (148.03 GB)
telemt_user_octets_to_client{user="hello"} 2613223046397 (2.38 TB)
telemt_user_msgs_from_client{user="hello"} 146235
telemt_user_msgs_to_client{user="hello"} 572261
telemt_user_unique_ips_current{user="hello"} 2016
telemt_user_unique_ips_recent_window{user="hello"} 724
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 76070.6 (21h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7604139
telemt_connections_bad_total 280705
telemt_connections_current 4169
telemt_connections_me_current 4169
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 3147227
telemt_upstream_connect_attempt_total 39264
telemt_upstream_connect_success_total 38978
telemt_upstream_connect_fail_total 279
telemt_upstream_connect_attempts_per_request{bucket="1"} 39257
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22681
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16192
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 105
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 279
telemt_me_reconnect_attempts_total 47703
telemt_me_reconnect_success_total 1341
telemt_me_reader_eof_total 1004
telemt_me_idle_close_by_peer_total 1004
telemt_me_route_drop_no_conn_total 2433294
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3735909
telemt_me_endpoint_quarantine_total 516
telemt_me_single_endpoint_outage_enter_total 17
telemt_me_single_endpoint_outage_exit_total 17
telemt_me_single_endpoint_outage_reconnect_attempt_total 57
telemt_me_single_endpoint_outage_reconnect_success_total 17
telemt_me_single_endpoint_quarantine_bypass_total 57
telemt_me_single_endpoint_shadow_rotate_total 578
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
telemt_me_writers_active_current 47
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 20272
telemt_desync_full_logged_total 6783
telemt_desync_suppressed_total 13489
telemt_desync_frames_bucket_total{bucket="1_2"} 4111
telemt_desync_frames_bucket_total{bucket="3_10"} 7841
telemt_desync_frames_bucket_total{bucket="gt_10"} 8320
telemt_pool_swap_total 80
telemt_pool_force_close_total 2456
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 245
telemt_me_draining_writers_reap_progress_total 26980
telemt_me_writer_removed_unexpected_total 1072
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2407
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 25670
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2098
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 358
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 24524
telemt_me_writer_teardown_success_total{mode="normal"} 28077
telemt_me_writer_teardown_noop_total 26987
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 54226
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 54702
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 54913
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 55064
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 55064
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 55064
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 55064
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 55064
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 55064
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 55064
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 55064
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 55064
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 55064
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.389681
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 55064
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 245
telemt_me_refill_failed_total 2695
telemt_me_writer_restored_same_endpoint_total 1194
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4328
telemt_user_connections_total{user="hello"} 3734350
telemt_user_connections_current{user="hello"} 4169
telemt_user_octets_from_client{user="hello"} 87475904432 (81.47 GB)
telemt_user_octets_to_client{user="hello"} 1504216425966 (1.37 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 1595
telemt_user_unique_ips_recent_window{user="hello"} 625
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 57041.4 (15h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 602939
telemt_connections_bad_total 5112
telemt_connections_current 955
telemt_connections_me_current 955
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 11482
telemt_upstream_connect_attempt_total 29744
telemt_upstream_connect_success_total 29676
telemt_upstream_connect_fail_total 60
telemt_upstream_connect_attempts_per_request{bucket="1"} 29736
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13772
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15587
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 317
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 60
telemt_me_reconnect_attempts_total 1319
telemt_me_reconnect_success_total 557
telemt_me_reader_eof_total 542
telemt_me_idle_close_by_peer_total 542
telemt_me_route_drop_no_conn_total 199396
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 545034
telemt_me_endpoint_quarantine_total 521
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 484
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 12
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
telemt_desync_total 2946
telemt_desync_full_logged_total 838
telemt_desync_suppressed_total 2108
telemt_desync_frames_bucket_total{bucket="1_2"} 783
telemt_desync_frames_bucket_total{bucket="3_10"} 1151
telemt_desync_frames_bucket_total{bucket="gt_10"} 1012
telemt_pool_swap_total 60
telemt_pool_force_close_total 1464
telemt_me_writer_close_signal_drop_total 79
telemt_me_draining_writers_reap_progress_total 24232
telemt_me_writer_removed_unexpected_total 525
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1819
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 22956
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1388
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 76
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 22768
telemt_me_writer_teardown_success_total{mode="normal"} 24775
telemt_me_writer_teardown_noop_total 24232
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 48522
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 48883
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 48982
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 49007
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 49007
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 49007
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 49007
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 49007
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 49007
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 49007
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 49007
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 49007
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 49007
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.666823
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 49007
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 79
telemt_me_refill_failed_total 42
telemt_me_writer_restored_same_endpoint_total 488
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 35
telemt_user_connections_total{user="hello"} 546931
telemt_user_connections_current{user="hello"} 955
telemt_user_octets_from_client{user="hello"} 10427002617 (9.71 GB)
telemt_user_octets_to_client{user="hello"} 257307177507 (239.64 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 356
telemt_user_unique_ips_recent_window{user="hello"} 145
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 139239.1 (38h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10192279
telemt_connections_bad_total 1187925
telemt_connections_current 5867
telemt_connections_me_current 5867
telemt_handshake_timeouts_total 270011
telemt_upstream_connect_attempt_total 53245
telemt_upstream_connect_success_total 53041
telemt_upstream_connect_fail_total 157
telemt_upstream_connect_attempts_per_request{bucket="1"} 53198
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26194
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26804
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 42
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 157
telemt_me_reconnect_attempts_total 2052
telemt_me_reconnect_success_total 1099
telemt_me_reader_eof_total 1064
telemt_me_idle_close_by_peer_total 1064
telemt_me_route_drop_no_conn_total 2960237
telemt_me_route_drop_channel_closed_total 81
telemt_me_route_drop_queue_full_total 29
telemt_me_route_drop_queue_full_profile_total{profile="high"} 29
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7611818
telemt_me_endpoint_quarantine_total 976
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 12
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 12
telemt_me_single_endpoint_shadow_rotate_total 1049
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
telemt_me_writers_active_current 44
telemt_desync_total 31056
telemt_desync_full_logged_total 10217
telemt_desync_suppressed_total 20839
telemt_desync_frames_bucket_total{bucket="1_2"} 7539
telemt_desync_frames_bucket_total{bucket="3_10"} 11376
telemt_desync_frames_bucket_total{bucket="gt_10"} 12141
telemt_pool_swap_total 154
telemt_pool_force_close_total 4183
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 512
telemt_me_draining_writers_reap_progress_total 48008
telemt_me_writer_removed_unexpected_total 1022
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3885
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 45178
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4057
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 126
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 43825
telemt_me_writer_teardown_success_total{mode="normal"} 49063
telemt_me_writer_teardown_noop_total 48010
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 95264
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 96502
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 96733
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 96973
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 97070
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 97073
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 97073
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 97073
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 97073
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 97073
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 97073
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 97073
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 97073
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 13.503295
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 97073
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 512
telemt_me_refill_failed_total 49
telemt_me_writer_restored_same_endpoint_total 959
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 52
telemt_user_connections_total{user="hello"} 7583466
telemt_user_connections_current{user="hello"} 5867
telemt_user_octets_from_client{user="hello"} 147013715544 (136.92 GB)
telemt_user_octets_to_client{user="hello"} 3517203101356 (3.20 TB)
telemt_user_unique_ips_current{user="hello"} 2123
telemt_user_unique_ips_recent_window{user="hello"} 735
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 139235.6 (38h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8908871
telemt_connections_bad_total 1009834
telemt_connections_current 5522
telemt_connections_me_current 5522
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 226908
telemt_upstream_connect_attempt_total 77743
telemt_upstream_connect_success_total 77187
telemt_upstream_connect_fail_total 486
telemt_upstream_connect_attempts_per_request{bucket="1"} 77673
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 43039
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31270
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 909
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1969
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 486
telemt_me_reconnect_attempts_total 6638
telemt_me_reconnect_success_total 1570
telemt_me_reader_eof_total 1394
telemt_me_idle_close_by_peer_total 1394
telemt_me_seq_mismatch_total 66
telemt_me_route_drop_no_conn_total 3354243
telemt_me_route_drop_channel_closed_total 275
telemt_me_route_drop_queue_full_total 15
telemt_me_route_drop_queue_full_profile_total{profile="high"} 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6818268
telemt_me_endpoint_quarantine_total 1082
telemt_me_single_endpoint_outage_enter_total 35
telemt_me_single_endpoint_outage_exit_total 35
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 33
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 1054
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
telemt_me_writers_active_current 43
telemt_desync_total 30345
telemt_desync_full_logged_total 9967
telemt_desync_suppressed_total 20378
telemt_desync_frames_bucket_total{bucket="1_2"} 7493
telemt_desync_frames_bucket_total{bucket="3_10"} 11252
telemt_desync_frames_bucket_total{bucket="gt_10"} 11600
telemt_pool_swap_total 151
telemt_pool_force_close_total 4116
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 512
telemt_me_draining_writers_reap_progress_total 46681
telemt_me_writer_removed_unexpected_total 1412
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4545
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 43612
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3811
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 305
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 42565
telemt_me_writer_teardown_success_total{mode="normal"} 48157
telemt_me_writer_teardown_noop_total 46685
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 92727
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 94089
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 94549
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 94804
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 94842
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 94842
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 94842
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 94842
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 94842
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 94842
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 94842
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 94842
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 94842
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 13.846176
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 94842
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 512
telemt_me_refill_failed_total 291
telemt_me_writer_restored_same_endpoint_total 1223
telemt_me_writer_restored_fallback_total 90
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 128
telemt_me_writer_removed_unexpected_minus_restored_total 99
telemt_user_connections_total{user="hello"} 6826135
telemt_user_connections_current{user="hello"} 5522
telemt_user_octets_from_client{user="hello"} 122710749253 (114.28 GB)
telemt_user_octets_to_client{user="hello"} 2823115283615 (2.57 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 1964
telemt_user_unique_ips_recent_window{user="hello"} 672
```