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

# Server Metrics 2026-03-23 04:14:05 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 112061.5 (31h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3818790
telemt_connections_bad_total 374248
telemt_connections_current 1303
telemt_connections_me_current 1303
telemt_handshake_timeouts_total 127185
telemt_upstream_connect_attempt_total 41771
telemt_upstream_connect_success_total 41770
telemt_upstream_connect_attempts_per_request{bucket="1"} 41770
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14514
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27120
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 93
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 451
telemt_me_reconnect_attempts_total 1453
telemt_me_reconnect_success_total 651
telemt_me_reader_eof_total 667
telemt_me_idle_close_by_peer_total 667
telemt_me_route_drop_no_conn_total 3030543
telemt_me_route_drop_channel_closed_total 1241
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3110854
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_endpoint_quarantine_total 795
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 877
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
telemt_me_writers_active_current 48
telemt_desync_total 13332
telemt_desync_full_logged_total 4245
telemt_desync_suppressed_total 9087
telemt_desync_frames_bucket_total{bucket="1_2"} 3513
telemt_desync_frames_bucket_total{bucket="3_10"} 4897
telemt_desync_frames_bucket_total{bucket="gt_10"} 4922
telemt_pool_swap_total 124
telemt_pool_force_close_total 3770
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 685
telemt_me_draining_writers_reap_progress_total 38246
telemt_me_writer_removed_unexpected_total 644
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2732
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 35806
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3714
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 56
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 34476
telemt_me_writer_teardown_success_total{mode="normal"} 38538
telemt_me_writer_teardown_noop_total 38257
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 62927
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 65375
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 67572
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 71617
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 74596
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 76289
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 76790
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 76795
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 76795
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 76795
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 76795
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 76795
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 76795
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 382.300419
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 76795
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 685
telemt_me_refill_failed_total 42
telemt_me_writer_restored_same_endpoint_total 584
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 59
telemt_user_connections_total{user="hello"} 3099582
telemt_user_connections_current{user="hello"} 1303
telemt_user_octets_from_client{user="hello"} 43726501784 (40.72 GB)
telemt_user_octets_to_client{user="hello"} 843630535560 (785.69 GB)
telemt_user_unique_ips_current{user="hello"} 559
telemt_user_unique_ips_recent_window{user="hello"} 203
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 125427.4 (34h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4084129
telemt_connections_bad_total 380965
telemt_connections_current 364
telemt_connections_me_current 364
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 103074
telemt_upstream_connect_attempt_total 78603
telemt_upstream_connect_success_total 77668
telemt_upstream_connect_fail_total 828
telemt_upstream_connect_attempts_per_request{bucket="1"} 78496
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 43185
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34263
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 220
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 828
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 10647
telemt_me_reconnect_success_total 3784
telemt_me_reader_eof_total 3765
telemt_me_idle_close_by_peer_total 3765
telemt_me_route_drop_no_conn_total 3654458
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3241863
telemt_me_endpoint_quarantine_total 1015
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_outage_enter_total 51
telemt_me_single_endpoint_outage_exit_total 51
telemt_me_single_endpoint_outage_reconnect_attempt_total 52
telemt_me_single_endpoint_outage_reconnect_success_total 50
telemt_me_single_endpoint_quarantine_bypass_total 52
telemt_me_single_endpoint_shadow_rotate_total 988
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
telemt_desync_total 13270
telemt_desync_full_logged_total 7468
telemt_desync_suppressed_total 5802
telemt_desync_frames_bucket_total{bucket="1_2"} 3018
telemt_desync_frames_bucket_total{bucket="3_10"} 5211
telemt_desync_frames_bucket_total{bucket="gt_10"} 5041
telemt_pool_swap_total 119
telemt_pool_force_close_total 3292
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 258
telemt_me_draining_writers_reap_progress_total 52350
telemt_me_writer_removed_unexpected_total 3688
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6650
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 49428
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2834
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 458
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 49058
telemt_me_writer_teardown_success_total{mode="normal"} 56078
telemt_me_writer_teardown_noop_total 52351
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 106455
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 107707
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 108043
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 108351
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 108414
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 108427
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 108429
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 108429
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 108429
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 108429
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 108429
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 108429
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 108429
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.754618
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 108429
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 258
telemt_me_refill_failed_total 270
telemt_me_writer_restored_same_endpoint_total 3350
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 307
telemt_user_connections_total{user="hello"} 3256335
telemt_user_connections_current{user="hello"} 364
telemt_user_octets_from_client{user="hello"} 43770096563 (40.76 GB)
telemt_user_octets_to_client{user="hello"} 813801193929 (757.91 GB)
telemt_user_msgs_from_client{user="hello"} 52128
telemt_user_msgs_to_client{user="hello"} 188269
telemt_user_unique_ips_current{user="hello"} 245
telemt_user_unique_ips_recent_window{user="hello"} 137
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 200287.3 (55h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16521254
telemt_connections_bad_total 1674464
telemt_connections_current 1334
telemt_connections_me_current 1334
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 402202
telemt_upstream_connect_attempt_total 90249
telemt_upstream_connect_success_total 90142
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 90159
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 43950
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 44456
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1729
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 3116
telemt_me_reconnect_success_total 1657
telemt_me_reader_eof_total 1612
telemt_me_idle_close_by_peer_total 1610
telemt_me_route_drop_no_conn_total 14079331
telemt_me_route_drop_channel_closed_total 145
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 13119942
telemt_me_endpoint_quarantine_total 1352
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 1514
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
telemt_desync_total 54610
telemt_desync_full_logged_total 17405
telemt_desync_suppressed_total 37205
telemt_desync_frames_bucket_total{bucket="1_2"} 12184
telemt_desync_frames_bucket_total{bucket="3_10"} 21361
telemt_desync_frames_bucket_total{bucket="gt_10"} 21065
telemt_pool_swap_total 217
telemt_pool_force_close_total 6994
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 1081
telemt_me_draining_writers_reap_progress_total 69229
telemt_me_writer_removed_unexpected_total 1548
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5805
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 64255
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 45
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 6524
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 470
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 62235
telemt_me_writer_teardown_success_total{mode="normal"} 70060
telemt_me_writer_teardown_noop_total 69282
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 128085
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 131827
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 133618
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 136014
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 137681
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 138732
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 139303
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 139333
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 139334
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 139338
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 139340
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 139342
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 139342
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 318.246068
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 139342
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1081
telemt_me_refill_failed_total 80
telemt_me_writer_restored_same_endpoint_total 1439
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 101
telemt_user_connections_total{user="hello"} 13119903
telemt_user_connections_current{user="hello"} 1334
telemt_user_octets_from_client{user="hello"} 198704352661 (185.06 GB)
telemt_user_octets_to_client{user="hello"} 3550695184147 (3.23 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 566
telemt_user_unique_ips_recent_window{user="hello"} 167
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 200288.8 (55h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12063980
telemt_connections_bad_total 1275788
telemt_connections_current 916
telemt_connections_me_current 916
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 347243
telemt_upstream_connect_attempt_total 104486
telemt_upstream_connect_success_total 103142
telemt_upstream_connect_fail_total 890
telemt_upstream_connect_attempts_per_request{bucket="1"} 104032
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 54838
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 44312
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 188
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3804
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 890
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 226
telemt_me_reconnect_attempts_total 4569
telemt_me_reconnect_success_total 1965
telemt_me_reader_eof_total 1832
telemt_me_idle_close_by_peer_total 1832
telemt_me_route_drop_no_conn_total 4579387
telemt_me_route_drop_channel_closed_total 498
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8926299
telemt_me_endpoint_quarantine_total 1367
telemt_me_single_endpoint_outage_enter_total 29
telemt_me_single_endpoint_outage_exit_total 29
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 27
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 1537
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
telemt_me_writers_active_current 46
telemt_desync_total 39260
telemt_desync_full_logged_total 13220
telemt_desync_suppressed_total 26040
telemt_desync_frames_bucket_total{bucket="1_2"} 9730
telemt_desync_frames_bucket_total{bucket="3_10"} 15090
telemt_desync_frames_bucket_total{bucket="gt_10"} 14440
telemt_pool_swap_total 214
telemt_pool_force_close_total 6338
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 717
telemt_me_draining_writers_reap_progress_total 67284
telemt_me_writer_removed_unexpected_total 1859
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5897
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 63105
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5826
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 512
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 60946
telemt_me_writer_teardown_success_total{mode="normal"} 69002
telemt_me_writer_teardown_noop_total 67309
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 129540
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 132787
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 133936
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 135127
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 135886
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 136226
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 136301
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 136303
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 136309
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 136311
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 136311
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 136311
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 136311
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 104.589486
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 136311
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 717
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 1682
telemt_me_writer_restored_fallback_total 20
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 157
telemt_user_connections_total{user="hello"} 8863966
telemt_user_connections_current{user="hello"} 916
telemt_user_octets_from_client{user="hello"} 218755306476 (203.73 GB)
telemt_user_octets_to_client{user="hello"} 3999038081847 (3.64 TB)
telemt_user_msgs_from_client{user="hello"} 124042
telemt_user_msgs_to_client{user="hello"} 140191
telemt_user_unique_ips_current{user="hello"} 381
telemt_user_unique_ips_recent_window{user="hello"} 113
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 200252.8 (55h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11204101
telemt_connections_bad_total 1009258
telemt_connections_current 844
telemt_connections_me_current 844
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 348804
telemt_upstream_connect_attempt_total 88994
telemt_upstream_connect_success_total 87423
telemt_upstream_connect_fail_total 205
telemt_upstream_connect_attempts_per_request{bucket="1"} 87628
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40096
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 42900
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2059
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2368
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 205
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 1420
telemt_me_reconnect_attempts_total 5850
telemt_me_reconnect_success_total 2456
telemt_me_reader_eof_total 2202
telemt_me_idle_close_by_peer_total 2201
telemt_me_route_drop_no_conn_total 5357864
telemt_me_route_drop_channel_closed_total 384
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8442576
telemt_me_endpoint_quarantine_total 1415
telemt_me_single_endpoint_outage_enter_total 37
telemt_me_single_endpoint_outage_exit_total 37
telemt_me_single_endpoint_outage_reconnect_attempt_total 38
telemt_me_single_endpoint_outage_reconnect_success_total 32
telemt_me_single_endpoint_quarantine_bypass_total 38
telemt_me_single_endpoint_shadow_rotate_total 1493
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 70
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
telemt_desync_total 38475
telemt_desync_full_logged_total 12765
telemt_desync_suppressed_total 25710
telemt_desync_frames_bucket_total{bucket="1_2"} 9716
telemt_desync_frames_bucket_total{bucket="3_10"} 14737
telemt_desync_frames_bucket_total{bucket="gt_10"} 14022
telemt_pool_swap_total 210
telemt_pool_force_close_total 6232
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 755
telemt_me_draining_writers_reap_progress_total 67857
telemt_me_writer_removed_unexpected_total 2348
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6648
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 63493
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5661
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 571
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 61625
telemt_me_writer_teardown_success_total{mode="normal"} 70141
telemt_me_writer_teardown_noop_total 67928
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 132222
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 134951
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 135914
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 136987
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 137588
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 137802
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 137930
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 137961
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 137969
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 137982
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 138015
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 138018
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 138069
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3174.910505
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 138069
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 755
telemt_me_refill_failed_total 180
telemt_me_writer_restored_same_endpoint_total 2138
telemt_me_writer_restored_fallback_total 17
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 193
telemt_user_connections_total{user="hello"} 8434465
telemt_user_connections_current{user="hello"} 844
telemt_user_octets_from_client{user="hello"} 193471585871 (180.18 GB)
telemt_user_octets_to_client{user="hello"} 3503587561145 (3.19 TB)
telemt_user_msgs_from_client{user="hello"} 46587
telemt_user_msgs_to_client{user="hello"} 113900
telemt_user_unique_ips_current{user="hello"} 356
telemt_user_unique_ips_recent_window{user="hello"} 120
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 70532.9 (19h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11477051
telemt_connections_bad_total 674364
telemt_connections_current 1567
telemt_connections_me_current 1567
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 299817
telemt_upstream_connect_attempt_total 64242
telemt_upstream_connect_success_total 60844
telemt_upstream_connect_fail_total 2204
telemt_upstream_connect_attempts_per_request{bucket="1"} 63048
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31346
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21948
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6033
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2204
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 8245
telemt_me_reconnect_success_total 1443
telemt_me_reader_eof_total 926
telemt_me_idle_close_by_peer_total 925
telemt_me_route_drop_no_conn_total 25330617
telemt_me_route_drop_channel_closed_total 59
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9512382
telemt_me_endpoint_quarantine_total 547
telemt_me_single_endpoint_outage_enter_total 102
telemt_me_single_endpoint_outage_exit_total 102
telemt_me_single_endpoint_outage_reconnect_attempt_total 200
telemt_me_single_endpoint_outage_reconnect_success_total 50
telemt_me_single_endpoint_quarantine_bypass_total 200
telemt_me_single_endpoint_shadow_rotate_total 569
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
telemt_desync_total 16936
telemt_desync_full_logged_total 4675
telemt_desync_suppressed_total 12261
telemt_desync_frames_bucket_total{bucket="1_2"} 3265
telemt_desync_frames_bucket_total{bucket="3_10"} 6910
telemt_desync_frames_bucket_total{bucket="gt_10"} 6761
telemt_pool_swap_total 73
telemt_pool_force_close_total 2286
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 511
telemt_me_draining_writers_reap_progress_total 23309
telemt_me_writer_removed_unexpected_total 1320
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3020
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21560
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1964
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 322
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21023
telemt_me_writer_teardown_success_total{mode="normal"} 24580
telemt_me_writer_teardown_noop_total 23328
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 43822
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 45717
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 46471
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 47363
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 47729
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 47852
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 47908
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 47908
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 47908
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 47908
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 47908
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 47908
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 47908
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 54.599162
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 47908
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 511
telemt_me_refill_failed_total 348
telemt_me_writer_restored_same_endpoint_total 934
telemt_me_writer_restored_fallback_total 16
telemt_me_no_writer_failfast_total 96
telemt_me_async_recovery_trigger_total 3153
telemt_me_writer_removed_unexpected_minus_restored_total 370
telemt_user_connections_total{user="hello"} 9538828
telemt_user_connections_current{user="hello"} 1567
telemt_user_octets_from_client{user="hello"} 89415205906 (83.27 GB)
telemt_user_octets_to_client{user="hello"} 669529223969 (623.55 GB)
telemt_user_msgs_from_client{user="hello"} 69581
telemt_user_msgs_to_client{user="hello"} 60103
telemt_user_unique_ips_current{user="hello"} 597
telemt_user_unique_ips_recent_window{user="hello"} 190
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 200259.5 (55h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11168521
telemt_connections_bad_total 985569
telemt_connections_current 1157
telemt_connections_me_current 1157
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 246179
telemt_upstream_connect_attempt_total 117837
telemt_upstream_connect_success_total 116613
telemt_upstream_connect_fail_total 1048
telemt_upstream_connect_attempts_per_request{bucket="1"} 117661
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 68593
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 46408
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1374
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1048
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 73418
telemt_me_reconnect_success_total 3220
telemt_me_reader_eof_total 2912
telemt_me_idle_close_by_peer_total 2909
telemt_me_route_drop_no_conn_total 5291571
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8793136
telemt_me_endpoint_quarantine_total 1363
telemt_me_single_endpoint_outage_enter_total 44
telemt_me_single_endpoint_outage_exit_total 44
telemt_me_single_endpoint_outage_reconnect_attempt_total 46
telemt_me_single_endpoint_outage_reconnect_success_total 44
telemt_me_single_endpoint_quarantine_bypass_total 46
telemt_me_single_endpoint_shadow_rotate_total 1524
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 55
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
telemt_desync_total 46850
telemt_desync_full_logged_total 16086
telemt_desync_suppressed_total 30764
telemt_desync_frames_bucket_total{bucket="1_2"} 9513
telemt_desync_frames_bucket_total{bucket="3_10"} 17958
telemt_desync_frames_bucket_total{bucket="gt_10"} 19379
telemt_pool_swap_total 206
telemt_pool_force_close_total 5958
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 677
telemt_me_draining_writers_reap_progress_total 71866
telemt_me_writer_removed_unexpected_total 2931
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 7197
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 67645
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5209
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 749
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 65908
telemt_me_writer_teardown_success_total{mode="normal"} 74842
telemt_me_writer_teardown_noop_total 71867
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 144554
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 145973
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 146392
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 146665
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 146699
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 146702
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 146702
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 146705
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 146709
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 146709
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 146709
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 146709
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 146709
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.337406
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 146709
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 677
telemt_me_refill_failed_total 4318
telemt_me_writer_restored_same_endpoint_total 2712
telemt_me_writer_restored_fallback_total 54
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7369
telemt_me_writer_removed_unexpected_minus_restored_total 165
telemt_user_connections_total{user="hello"} 8795943
telemt_user_connections_current{user="hello"} 1157
telemt_user_octets_from_client{user="hello"} 197427983977 (183.87 GB)
telemt_user_octets_to_client{user="hello"} 3363549424776 (3.06 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 487
telemt_user_unique_ips_recent_window{user="hello"} 148
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 137095.7 (38h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11904170
telemt_connections_bad_total 488100
telemt_connections_current 937
telemt_connections_me_current 937
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4808736
telemt_upstream_connect_attempt_total 66728
telemt_upstream_connect_success_total 66251
telemt_upstream_connect_fail_total 464
telemt_upstream_connect_attempts_per_request{bucket="1"} 66715
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34971
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31042
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 238
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 464
telemt_me_reconnect_attempts_total 49237
telemt_me_reconnect_success_total 1936
telemt_me_reader_eof_total 1617
telemt_me_idle_close_by_peer_total 1616
telemt_me_route_drop_no_conn_total 4118460
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5723186
telemt_me_endpoint_quarantine_total 950
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 59
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 59
telemt_me_single_endpoint_shadow_rotate_total 1058
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
telemt_me_writers_active_current 43
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 32173
telemt_desync_full_logged_total 10995
telemt_desync_suppressed_total 21178
telemt_desync_frames_bucket_total{bucket="1_2"} 6451
telemt_desync_frames_bucket_total{bucket="3_10"} 12682
telemt_desync_frames_bucket_total{bucket="gt_10"} 13040
telemt_pool_swap_total 146
telemt_pool_force_close_total 4151
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 389
telemt_me_draining_writers_reap_progress_total 51728
telemt_me_writer_removed_unexpected_total 1657
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4121
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 49318
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3707
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 444
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 47577
telemt_me_writer_teardown_success_total{mode="normal"} 53439
telemt_me_writer_teardown_noop_total 51735
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 103873
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 104637
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 104947
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 105174
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 105174
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 105174
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 105174
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 105174
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 105174
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 105174
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 105174
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 105174
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 105174
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.768345
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 105174
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 389
telemt_me_refill_failed_total 2748
telemt_me_writer_restored_same_endpoint_total 1712
telemt_me_writer_restored_fallback_total 30
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4332
telemt_user_connections_total{user="hello"} 5715186
telemt_user_connections_current{user="hello"} 937
telemt_user_octets_from_client{user="hello"} 120981557004 (112.67 GB)
telemt_user_octets_to_client{user="hello"} 2227770382054 (2.03 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 385
telemt_user_unique_ips_recent_window{user="hello"} 162
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 118066.8 (32h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1619205
telemt_connections_bad_total 37120
telemt_connections_current 613
telemt_connections_me_current 613
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 33094
telemt_upstream_connect_attempt_total 55808
telemt_upstream_connect_success_total 55634
telemt_upstream_connect_fail_total 146
telemt_upstream_connect_attempts_per_request{bucket="1"} 55780
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26223
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28592
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 819
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 146
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2414
telemt_me_reconnect_success_total 978
telemt_me_reader_eof_total 972
telemt_me_idle_close_by_peer_total 972
telemt_me_route_drop_no_conn_total 540637
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1439225
telemt_me_endpoint_quarantine_total 1001
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 976
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
telemt_me_writers_active_current 44
telemt_desync_total 10103
telemt_desync_full_logged_total 2842
telemt_desync_suppressed_total 7261
telemt_desync_frames_bucket_total{bucket="1_2"} 3204
telemt_desync_frames_bucket_total{bucket="3_10"} 3806
telemt_desync_frames_bucket_total{bucket="gt_10"} 3093
telemt_pool_swap_total 128
telemt_pool_force_close_total 3197
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 175
telemt_me_draining_writers_reap_progress_total 47539
telemt_me_writer_removed_unexpected_total 936
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3586
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 44932
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3109
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 44342
telemt_me_writer_teardown_success_total{mode="normal"} 48518
telemt_me_writer_teardown_noop_total 47543
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 95045
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 95794
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 96024
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 96061
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 96061
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 96061
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 96061
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 96061
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 96061
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 96061
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 96061
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 96061
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 96061
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.548357
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 96061
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 175
telemt_me_refill_failed_total 80
telemt_me_writer_restored_same_endpoint_total 836
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 78
telemt_user_connections_total{user="hello"} 1434906
telemt_user_connections_current{user="hello"} 613
telemt_user_octets_from_client{user="hello"} 26902596973 (25.05 GB)
telemt_user_octets_to_client{user="hello"} 599434318051 (558.27 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 280
telemt_user_unique_ips_recent_window{user="hello"} 97
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 200264.0 (55h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13463564
telemt_connections_bad_total 1627749
telemt_connections_current 1147
telemt_connections_me_current 1147
telemt_handshake_timeouts_total 393517
telemt_upstream_connect_attempt_total 80559
telemt_upstream_connect_success_total 80199
telemt_upstream_connect_fail_total 223
telemt_upstream_connect_attempts_per_request{bucket="1"} 80422
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 39643
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 40452
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 100
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 223
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 3156
telemt_me_reconnect_success_total 1590
telemt_me_reader_eof_total 1578
telemt_me_idle_close_by_peer_total 1578
telemt_me_route_drop_no_conn_total 4504684
telemt_me_route_drop_channel_closed_total 123
telemt_me_route_drop_queue_full_total 42
telemt_me_route_drop_queue_full_profile_total{profile="high"} 42
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10146007
telemt_me_endpoint_quarantine_total 1475
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 13
telemt_me_single_endpoint_outage_exit_total 13
telemt_me_single_endpoint_outage_reconnect_attempt_total 14
telemt_me_single_endpoint_outage_reconnect_success_total 12
telemt_me_single_endpoint_quarantine_bypass_total 14
telemt_me_single_endpoint_shadow_rotate_total 1521
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
telemt_me_writers_active_current 41
telemt_desync_total 42573
telemt_desync_full_logged_total 13899
telemt_desync_suppressed_total 28674
telemt_desync_frames_bucket_total{bucket="1_2"} 10363
telemt_desync_frames_bucket_total{bucket="3_10"} 15639
telemt_desync_frames_bucket_total{bucket="gt_10"} 16571
telemt_pool_swap_total 222
telemt_pool_force_close_total 5810
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 690
telemt_me_draining_writers_reap_progress_total 72937
telemt_me_writer_removed_unexpected_total 1511
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5623
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 68882
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5636
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 67127
telemt_me_writer_teardown_success_total{mode="normal"} 74505
telemt_me_writer_teardown_noop_total 72939
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 144823
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 146552
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 146935
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 147311
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 147431
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 147444
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 147444
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 147444
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 147444
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 147444
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 147444
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 147444
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 147444
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.897653
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 147444
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 690
telemt_me_refill_failed_total 84
telemt_me_writer_restored_same_endpoint_total 1399
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 95
telemt_user_connections_total{user="hello"} 10112578
telemt_user_connections_current{user="hello"} 1147
telemt_user_octets_from_client{user="hello"} 195909943148 (182.46 GB)
telemt_user_octets_to_client{user="hello"} 4500513993476 (4.09 TB)
telemt_user_unique_ips_current{user="hello"} 426
telemt_user_unique_ips_recent_window{user="hello"} 125
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 200260.6 (55h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11782198
telemt_connections_bad_total 1381631
telemt_connections_current 962
telemt_connections_me_current 962
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 316087
telemt_upstream_connect_attempt_total 108319
telemt_upstream_connect_success_total 107388
telemt_upstream_connect_fail_total 723
telemt_upstream_connect_attempts_per_request{bucket="1"} 108111
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 58334
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 46071
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2070
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 723
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 10971
telemt_me_reconnect_success_total 2720
telemt_me_reader_eof_total 2522
telemt_me_idle_close_by_peer_total 2521
telemt_me_seq_mismatch_total 104
telemt_me_route_drop_no_conn_total 5672660
telemt_me_route_drop_channel_closed_total 354
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9064860
telemt_me_endpoint_quarantine_total 1649
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 56
telemt_me_single_endpoint_outage_exit_total 56
telemt_me_single_endpoint_outage_reconnect_attempt_total 56
telemt_me_single_endpoint_outage_reconnect_success_total 54
telemt_me_single_endpoint_quarantine_bypass_total 56
telemt_me_single_endpoint_shadow_rotate_total 1526
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 58
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
telemt_desync_total 42206
telemt_desync_full_logged_total 13594
telemt_desync_suppressed_total 28612
telemt_desync_frames_bucket_total{bucket="1_2"} 10969
telemt_desync_frames_bucket_total{bucket="3_10"} 15508
telemt_desync_frames_bucket_total{bucket="gt_10"} 15729
telemt_pool_swap_total 212
telemt_pool_force_close_total 5573
telemt_pool_stale_pick_total 390
telemt_me_writer_close_signal_drop_total 678
telemt_me_draining_writers_reap_progress_total 73186
telemt_me_writer_removed_unexpected_total 2558
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 7018
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 68823
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5102
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 471
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 67613
telemt_me_writer_teardown_success_total{mode="normal"} 75841
telemt_me_writer_teardown_noop_total 73191
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 146326
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 148124
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 148663
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 148982
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 149032
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 149032
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 149032
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 149032
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 149032
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 149032
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 149032
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 149032
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 149032
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.607911
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 149032
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 678
telemt_me_refill_failed_total 428
telemt_me_writer_restored_same_endpoint_total 2171
telemt_me_writer_restored_fallback_total 140
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 135
telemt_me_writer_removed_unexpected_minus_restored_total 247
telemt_user_connections_total{user="hello"} 9069386
telemt_user_connections_current{user="hello"} 962
telemt_user_octets_from_client{user="hello"} 158466678844 (147.58 GB)
telemt_user_octets_to_client{user="hello"} 3543971899278 (3.22 TB)
telemt_user_msgs_from_client{user="hello"} 103592
telemt_user_msgs_to_client{user="hello"} 254638
telemt_user_unique_ips_current{user="hello"} 409
telemt_user_unique_ips_recent_window{user="hello"} 130
```