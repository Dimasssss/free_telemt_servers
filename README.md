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

# Server Metrics 2026-03-22 05:50:10 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 31419.6 (8h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 554710
telemt_connections_bad_total 36408
telemt_connections_current 1240
telemt_connections_me_current 1240
telemt_handshake_timeouts_total 28825
telemt_upstream_connect_attempt_total 12875
telemt_upstream_connect_success_total 12874
telemt_upstream_connect_attempts_per_request{bucket="1"} 12874
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4506
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8337
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 20
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_me_reconnect_attempts_total 336
telemt_me_reconnect_success_total 203
telemt_me_reader_eof_total 199
telemt_me_idle_close_by_peer_total 199
telemt_me_route_drop_no_conn_total 121078
telemt_me_route_drop_channel_closed_total 41
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 458959
telemt_me_endpoint_quarantine_total 234
telemt_me_single_endpoint_shadow_rotate_total 259
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 6
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
telemt_desync_total 4043
telemt_desync_full_logged_total 1123
telemt_desync_suppressed_total 2920
telemt_desync_frames_bucket_total{bucket="1_2"} 1351
telemt_desync_frames_bucket_total{bucket="3_10"} 1531
telemt_desync_frames_bucket_total{bucket="gt_10"} 1161
telemt_pool_swap_total 34
telemt_pool_force_close_total 908
telemt_me_writer_close_signal_drop_total 82
telemt_me_draining_writers_reap_progress_total 11639
telemt_me_writer_removed_unexpected_total 196
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 802
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 11021
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 898
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 10731
telemt_me_writer_teardown_success_total{mode="normal"} 11823
telemt_me_writer_teardown_noop_total 11640
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 22533
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 22938
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 23127
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 23313
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 23424
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 23463
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 23463
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 23463
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 23463
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 23463
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 23463
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 23463
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 23463
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 12.386336
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 23463
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 82
telemt_me_refill_failed_total 7
telemt_me_writer_restored_same_endpoint_total 185
telemt_me_writer_removed_unexpected_minus_restored_total 11
telemt_user_connections_total{user="hello"} 457953
telemt_user_connections_current{user="hello"} 1240
telemt_user_octets_from_client{user="hello"} 6139355620 (5.72 GB)
telemt_user_octets_to_client{user="hello"} 164881611488 (153.56 GB)
telemt_user_unique_ips_current{user="hello"} 520
telemt_user_unique_ips_recent_window{user="hello"} 170
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 44785.8 (12h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1018734
telemt_connections_bad_total 85567
telemt_connections_current 1105
telemt_connections_me_current 1105
telemt_handshake_timeouts_total 34275
telemt_upstream_connect_attempt_total 23748
telemt_upstream_connect_success_total 23423
telemt_upstream_connect_fail_total 294
telemt_upstream_connect_attempts_per_request{bucket="1"} 23717
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11940
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11432
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 51
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 294
telemt_me_reconnect_attempts_total 1794
telemt_me_reconnect_success_total 641
telemt_me_reader_eof_total 565
telemt_me_idle_close_by_peer_total 565
telemt_me_route_drop_no_conn_total 383457
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 784251
telemt_me_endpoint_quarantine_total 417
telemt_me_single_endpoint_outage_enter_total 21
telemt_me_single_endpoint_outage_exit_total 21
telemt_me_single_endpoint_outage_reconnect_attempt_total 21
telemt_me_single_endpoint_outage_reconnect_success_total 21
telemt_me_single_endpoint_quarantine_bypass_total 21
telemt_me_single_endpoint_shadow_rotate_total 364
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 23
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
telemt_desync_total 3341
telemt_desync_full_logged_total 1937
telemt_desync_suppressed_total 1404
telemt_desync_frames_bucket_total{bucket="1_2"} 700
telemt_desync_frames_bucket_total{bucket="3_10"} 1284
telemt_desync_frames_bucket_total{bucket="gt_10"} 1357
telemt_pool_swap_total 48
telemt_pool_force_close_total 1259
telemt_me_writer_close_signal_drop_total 96
telemt_me_draining_writers_reap_progress_total 18465
telemt_me_writer_removed_unexpected_total 539
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1572
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17445
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1237
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 22
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17206
telemt_me_writer_teardown_success_total{mode="normal"} 19017
telemt_me_writer_teardown_noop_total 18465
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 36889
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 37242
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 37366
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 37468
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 37480
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 37482
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 37482
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 37482
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 37482
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 37482
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 37482
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 37482
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 37482
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.182369
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 37482
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 96
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 480
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 785938
telemt_user_connections_current{user="hello"} 1105
telemt_user_octets_from_client{user="hello"} 12404209619 (11.55 GB)
telemt_user_octets_to_client{user="hello"} 290163989838 (270.24 GB)
telemt_user_msgs_from_client{user="hello"} 6021
telemt_user_msgs_to_client{user="hello"} 9976
telemt_user_unique_ips_current{user="hello"} 719
telemt_user_unique_ips_recent_window{user="hello"} 292
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 119645.9 (33h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8365028
telemt_connections_bad_total 733131
telemt_connections_current 3630
telemt_connections_me_current 3630
telemt_handshake_timeouts_total 271334
telemt_upstream_connect_attempt_total 44513
telemt_upstream_connect_success_total 44435
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 44443
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20123
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24121
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 185
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1655
telemt_me_reconnect_success_total 869
telemt_me_reader_eof_total 877
telemt_me_idle_close_by_peer_total 877
telemt_me_route_drop_no_conn_total 4659600
telemt_me_route_drop_channel_closed_total 68
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6694167
telemt_me_endpoint_quarantine_total 759
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 899
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 28
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
telemt_desync_total 28270
telemt_desync_full_logged_total 9424
telemt_desync_suppressed_total 18846
telemt_desync_frames_bucket_total{bucket="1_2"} 6126
telemt_desync_frames_bucket_total{bucket="3_10"} 11040
telemt_desync_frames_bucket_total{bucket="gt_10"} 11104
telemt_pool_swap_total 129
telemt_pool_force_close_total 4263
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 645
telemt_me_draining_writers_reap_progress_total 40650
telemt_me_writer_removed_unexpected_total 845
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3353
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 37646
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4016
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 247
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 36387
telemt_me_writer_teardown_success_total{mode="normal"} 40999
telemt_me_writer_teardown_noop_total 40694
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 74981
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 76973
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 78063
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 79675
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 80791
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 81388
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 81682
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 81693
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 81693
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 81693
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 81693
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 81693
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 81693
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 169.415995
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 81693
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 645
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 776
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 64
telemt_user_connections_total{user="hello"} 6685453
telemt_user_connections_current{user="hello"} 3630
telemt_user_octets_from_client{user="hello"} 113755678816 (105.94 GB)
telemt_user_octets_to_client{user="hello"} 2277564080164 (2.07 TB)
telemt_user_unique_ips_current{user="hello"} 1539
telemt_user_unique_ips_recent_window{user="hello"} 454
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 119647.1 (33h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6875467
telemt_connections_bad_total 610119
telemt_connections_current 3002
telemt_connections_me_current 3002
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 230908
telemt_upstream_connect_attempt_total 48449
telemt_upstream_connect_success_total 48048
telemt_upstream_connect_fail_total 204
telemt_upstream_connect_attempts_per_request{bucket="1"} 48252
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23720
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23737
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 558
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 204
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 2056
telemt_me_reconnect_success_total 932
telemt_me_reader_eof_total 910
telemt_me_idle_close_by_peer_total 910
telemt_me_route_drop_no_conn_total 2356114
telemt_me_route_drop_channel_closed_total 289
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5144311
telemt_me_endpoint_quarantine_total 756
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 920
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
telemt_me_writers_active_current 44
telemt_desync_total 23827
telemt_desync_full_logged_total 8182
telemt_desync_suppressed_total 15645
telemt_desync_frames_bucket_total{bucket="1_2"} 5707
telemt_desync_frames_bucket_total{bucket="3_10"} 9262
telemt_desync_frames_bucket_total{bucket="gt_10"} 8858
telemt_pool_swap_total 130
telemt_pool_force_close_total 3853
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 394
telemt_me_draining_writers_reap_progress_total 39038
telemt_me_writer_removed_unexpected_total 889
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3220
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 36650
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3635
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 218
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 35185
telemt_me_writer_teardown_success_total{mode="normal"} 39870
telemt_me_writer_teardown_noop_total 39044
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 75362
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 77044
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 77687
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 78290
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 78709
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 78894
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 78914
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 78914
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 78914
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 78914
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 78914
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 78914
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 78914
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 49.967890
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 78914
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 394
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 813
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 66
telemt_user_connections_total{user="hello"} 5065750
telemt_user_connections_current{user="hello"} 3002
telemt_user_octets_from_client{user="hello"} 147363705329 (137.24 GB)
telemt_user_octets_to_client{user="hello"} 2427248250471 (2.21 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1300
telemt_user_unique_ips_recent_window{user="hello"} 380
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 119620.6 (33h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6716271
telemt_connections_bad_total 565415
telemt_connections_current 2782
telemt_connections_me_current 2782
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 224602
telemt_upstream_connect_attempt_total 54867
telemt_upstream_connect_success_total 54299
telemt_upstream_connect_fail_total 143
telemt_upstream_connect_attempts_per_request{bucket="1"} 54442
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27070
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25265
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 765
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1199
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 143
telemt_me_keepalive_timeout_total 73
telemt_me_reconnect_attempts_total 2469
telemt_me_reconnect_success_total 1075
telemt_me_reader_eof_total 1013
telemt_me_idle_close_by_peer_total 1013
telemt_me_route_drop_no_conn_total 2369797
telemt_me_route_drop_channel_closed_total 147
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4995762
telemt_me_endpoint_quarantine_total 851
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 888
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
telemt_desync_total 23696
telemt_desync_full_logged_total 8048
telemt_desync_suppressed_total 15648
telemt_desync_frames_bucket_total{bucket="1_2"} 5759
telemt_desync_frames_bucket_total{bucket="3_10"} 9093
telemt_desync_frames_bucket_total{bucket="gt_10"} 8844
telemt_pool_swap_total 128
telemt_pool_force_close_total 3730
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 417
telemt_me_draining_writers_reap_progress_total 40043
telemt_me_writer_removed_unexpected_total 1003
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3456
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 37606
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 12
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3488
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 242
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 36313
telemt_me_writer_teardown_success_total{mode="normal"} 41062
telemt_me_writer_teardown_noop_total 40055
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 78131
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 79656
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 80168
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 80742
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 81013
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 81073
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 81117
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 81117
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 81117
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 81117
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 81117
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 81117
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 81117
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 36.996583
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 81117
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 417
telemt_me_refill_failed_total 77
telemt_me_writer_restored_same_endpoint_total 940
telemt_me_writer_restored_fallback_total 6
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 57
telemt_user_connections_total{user="hello"} 4990166
telemt_user_connections_current{user="hello"} 2782
telemt_user_octets_from_client{user="hello"} 138226340127 (128.73 GB)
telemt_user_octets_to_client{user="hello"} 2282504585835 (2.08 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 1112
telemt_user_unique_ips_recent_window{user="hello"} 364
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 119650.5 (33h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 21467664
telemt_connections_bad_total 1819395
telemt_connections_current 4220
telemt_connections_me_current 4220
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 654188
telemt_upstream_connect_attempt_total 210722
telemt_upstream_connect_success_total 192047
telemt_upstream_connect_fail_total 16760
telemt_upstream_connect_attempts_per_request{bucket="1"} 208807
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 133197
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 47020
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1954
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9876
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16760
telemt_me_keepalive_timeout_total 398
telemt_me_reconnect_attempts_total 65498
telemt_me_reconnect_success_total 2546
telemt_me_reader_eof_total 1591
telemt_me_idle_close_by_peer_total 1590
telemt_me_route_drop_no_conn_total 40549358
telemt_me_route_drop_channel_closed_total 130
telemt_me_route_drop_queue_full_total 13
telemt_me_route_drop_queue_full_profile_total{profile="high"} 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 17252823
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 5
telemt_me_endpoint_quarantine_total 929
telemt_me_single_endpoint_outage_enter_total 153
telemt_me_single_endpoint_outage_exit_total 153
telemt_me_single_endpoint_outage_reconnect_attempt_total 322
telemt_me_single_endpoint_outage_reconnect_success_total 80
telemt_me_single_endpoint_quarantine_bypass_total 322
telemt_me_single_endpoint_shadow_rotate_total 939
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
telemt_me_writers_active_current 45
telemt_desync_total 33245
telemt_desync_full_logged_total 10038
telemt_desync_suppressed_total 23207
telemt_desync_frames_bucket_total{bucket="1_2"} 7267
telemt_desync_frames_bucket_total{bucket="3_10"} 14755
telemt_desync_frames_bucket_total{bucket="gt_10"} 11223
telemt_pool_swap_total 123
telemt_pool_force_close_total 3948
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 872
telemt_me_draining_writers_reap_progress_total 37618
telemt_me_writer_removed_unexpected_total 2369
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5086
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 34650
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 24
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3389
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 559
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 33670
telemt_me_writer_teardown_success_total{mode="normal"} 39736
telemt_me_writer_teardown_noop_total 37645
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 70210
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 72853
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 74205
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 75948
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 76935
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 77277
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 77362
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 77364
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 77367
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 77372
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 77372
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 77376
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 77381
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 219.158639
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 77381
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 872
telemt_me_refill_failed_total 3814
telemt_me_writer_restored_same_endpoint_total 1729
telemt_me_writer_restored_fallback_total 22
telemt_me_no_writer_failfast_total 666
telemt_me_async_recovery_trigger_total 14678
telemt_me_writer_removed_unexpected_minus_restored_total 618
telemt_user_connections_total{user="hello"} 17392182
telemt_user_connections_current{user="hello"} 4220
telemt_user_octets_from_client{user="hello"} 255853867073 (238.28 GB)
telemt_user_octets_to_client{user="hello"} 1343861479487 (1.22 TB)
telemt_user_msgs_from_client{user="hello"} 409002
telemt_user_msgs_to_client{user="hello"} 794272
telemt_user_unique_ips_current{user="hello"} 1613
telemt_user_unique_ips_recent_window{user="hello"} 717
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 119618.0 (33h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6481840
telemt_connections_bad_total 615725
telemt_connections_current 2998
telemt_connections_me_current 2998
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 136357
telemt_upstream_connect_attempt_total 63467
telemt_upstream_connect_success_total 62730
telemt_upstream_connect_fail_total 631
telemt_upstream_connect_attempts_per_request{bucket="1"} 63361
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36117
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26251
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 361
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 631
telemt_me_reconnect_attempts_total 69942
telemt_me_reconnect_success_total 1895
telemt_me_reader_eof_total 1670
telemt_me_idle_close_by_peer_total 1669
telemt_me_route_drop_no_conn_total 2492125
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 39
telemt_me_route_drop_queue_full_profile_total{profile="high"} 39
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5047444
telemt_me_endpoint_quarantine_total 807
telemt_me_single_endpoint_outage_enter_total 24
telemt_me_single_endpoint_outage_exit_total 24
telemt_me_single_endpoint_outage_reconnect_attempt_total 25
telemt_me_single_endpoint_outage_reconnect_success_total 24
telemt_me_single_endpoint_quarantine_bypass_total 25
telemt_me_single_endpoint_shadow_rotate_total 910
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 34
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
telemt_desync_total 25102
telemt_desync_full_logged_total 8798
telemt_desync_suppressed_total 16304
telemt_desync_frames_bucket_total{bucket="1_2"} 4970
telemt_desync_frames_bucket_total{bucket="3_10"} 9688
telemt_desync_frames_bucket_total{bucket="gt_10"} 10444
telemt_pool_swap_total 124
telemt_pool_force_close_total 3550
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 418
telemt_me_draining_writers_reap_progress_total 42164
telemt_me_writer_removed_unexpected_total 1704
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4251
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 39651
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3144
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 406
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 38614
telemt_me_writer_teardown_success_total{mode="normal"} 43902
telemt_me_writer_teardown_noop_total 42165
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 84660
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 85549
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 85841
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 86033
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 86064
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 86067
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 86067
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 86067
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 86067
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 86067
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 86067
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 86067
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 86067
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 9.586607
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 86067
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 418
telemt_me_refill_failed_total 4215
telemt_me_writer_restored_same_endpoint_total 1582
telemt_me_writer_restored_fallback_total 38
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7313
telemt_me_writer_removed_unexpected_minus_restored_total 84
telemt_user_connections_total{user="hello"} 5039435
telemt_user_connections_current{user="hello"} 2998
telemt_user_octets_from_client{user="hello"} 130285898152 (121.34 GB)
telemt_user_octets_to_client{user="hello"} 2099219138398 (1.91 TB)
telemt_user_msgs_from_client{user="hello"} 77823
telemt_user_msgs_to_client{user="hello"} 338392
telemt_user_unique_ips_current{user="hello"} 1274
telemt_user_unique_ips_recent_window{user="hello"} 397
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 56453.9 (15h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4524130
telemt_connections_bad_total 185826
telemt_connections_current 2460
telemt_connections_me_current 2460
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 1791386
telemt_upstream_connect_attempt_total 32309
telemt_upstream_connect_success_total 32093
telemt_upstream_connect_fail_total 209
telemt_upstream_connect_attempts_per_request{bucket="1"} 32302
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19454
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12555
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 84
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 209
telemt_me_reconnect_attempts_total 46101
telemt_me_reconnect_success_total 1036
telemt_me_reader_eof_total 727
telemt_me_idle_close_by_peer_total 727
telemt_me_route_drop_no_conn_total 1128199
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2239815
telemt_me_endpoint_quarantine_total 402
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 50
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 50
telemt_me_single_endpoint_shadow_rotate_total 437
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
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 11989
telemt_desync_full_logged_total 4123
telemt_desync_suppressed_total 7866
telemt_desync_frames_bucket_total{bucket="1_2"} 2311
telemt_desync_frames_bucket_total{bucket="3_10"} 4583
telemt_desync_frames_bucket_total{bucket="gt_10"} 5095
telemt_pool_swap_total 61
telemt_pool_force_close_total 1788
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 159
telemt_me_draining_writers_reap_progress_total 20896
telemt_me_writer_removed_unexpected_total 797
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1778
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19945
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1578
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 210
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19108
telemt_me_writer_teardown_success_total{mode="normal"} 21723
telemt_me_writer_teardown_noop_total 20898
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 42059
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 42358
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 42515
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 42621
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 42621
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 42621
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 42621
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 42621
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 42621
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 42621
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 42621
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 42621
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 42621
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.703631
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 42621
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 159
telemt_me_refill_failed_total 2618
telemt_me_writer_restored_same_endpoint_total 924
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4264
telemt_user_connections_total{user="hello"} 2242074
telemt_user_connections_current{user="hello"} 2460
telemt_user_octets_from_client{user="hello"} 59603795956 (55.51 GB)
telemt_user_octets_to_client{user="hello"} 989645813790 (921.68 GB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 1112
telemt_user_unique_ips_recent_window{user="hello"} 365
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 37424.6 (10h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 268514
telemt_connections_bad_total 1996
telemt_connections_current 555
telemt_connections_me_current 555
telemt_handshake_timeouts_total 6769
telemt_upstream_connect_attempt_total 18061
telemt_upstream_connect_success_total 18017
telemt_upstream_connect_fail_total 40
telemt_upstream_connect_attempts_per_request{bucket="1"} 18057
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7562
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10358
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 97
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 40
telemt_me_reconnect_attempts_total 427
telemt_me_reconnect_success_total 248
telemt_me_reader_eof_total 248
telemt_me_idle_close_by_peer_total 248
telemt_me_route_drop_no_conn_total 76140
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 240219
telemt_me_endpoint_quarantine_total 357
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 325
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 5
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
telemt_desync_total 1257
telemt_desync_full_logged_total 344
telemt_desync_suppressed_total 913
telemt_desync_frames_bucket_total{bucket="1_2"} 434
telemt_desync_frames_bucket_total{bucket="3_10"} 483
telemt_desync_frames_bucket_total{bucket="gt_10"} 340
telemt_pool_swap_total 41
telemt_pool_force_close_total 913
telemt_me_writer_close_signal_drop_total 35
telemt_me_draining_writers_reap_progress_total 16349
telemt_me_writer_removed_unexpected_total 237
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1048
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15549
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 911
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15436
telemt_me_writer_teardown_success_total{mode="normal"} 16597
telemt_me_writer_teardown_noop_total 16349
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 32682
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 32918
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 32936
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 32946
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 32946
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 32946
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 32946
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 32946
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 32946
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 32946
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 32946
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 32946
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 32946
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.272661
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 32946
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 35
telemt_me_refill_failed_total 10
telemt_me_writer_restored_same_endpoint_total 216
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 239819
telemt_user_connections_current{user="hello"} 555
telemt_user_octets_from_client{user="hello"} 4021368280 (3.75 GB)
telemt_user_octets_to_client{user="hello"} 146778053008 (136.70 GB)
telemt_user_unique_ips_current{user="hello"} 243
telemt_user_unique_ips_recent_window{user="hello"} 82
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 119622.3 (33h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7860612
telemt_connections_bad_total 789109
telemt_connections_current 3278
telemt_connections_me_current 3278
telemt_handshake_timeouts_total 223695
telemt_upstream_connect_attempt_total 47081
telemt_upstream_connect_success_total 46910
telemt_upstream_connect_fail_total 134
telemt_upstream_connect_attempts_per_request{bucket="1"} 47044
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23195
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23674
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 134
telemt_me_reconnect_attempts_total 1698
telemt_me_reconnect_success_total 914
telemt_me_reader_eof_total 908
telemt_me_idle_close_by_peer_total 908
telemt_me_route_drop_no_conn_total 2225730
telemt_me_route_drop_channel_closed_total 52
telemt_me_route_drop_queue_full_total 23
telemt_me_route_drop_queue_full_profile_total{profile="high"} 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5859073
telemt_me_endpoint_quarantine_total 850
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 917
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
telemt_me_writers_active_current 44
telemt_desync_total 22902
telemt_desync_full_logged_total 7551
telemt_desync_suppressed_total 15351
telemt_desync_frames_bucket_total{bucket="1_2"} 5723
telemt_desync_frames_bucket_total{bucket="3_10"} 8333
telemt_desync_frames_bucket_total{bucket="gt_10"} 8846
telemt_pool_swap_total 132
telemt_pool_force_close_total 3517
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 414
telemt_me_draining_writers_reap_progress_total 42497
telemt_me_writer_removed_unexpected_total 871
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3319
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 40076
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3429
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 38980
telemt_me_writer_teardown_success_total{mode="normal"} 43395
telemt_me_writer_teardown_noop_total 42499
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 84465
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 85414
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 85601
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 85806
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 85894
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 85894
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 85894
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 85894
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 85894
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 85894
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 85894
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 85894
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 85894
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 11.019344
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 85894
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 414
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 818
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 45
telemt_user_connections_total{user="hello"} 5833565
telemt_user_connections_current{user="hello"} 3278
telemt_user_octets_from_client{user="hello"} 114954018120 (107.06 GB)
telemt_user_octets_to_client{user="hello"} 2732363330540 (2.49 TB)
telemt_user_unique_ips_current{user="hello"} 1345
telemt_user_unique_ips_recent_window{user="hello"} 431
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 119619.0 (33h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6829227
telemt_connections_bad_total 665297
telemt_connections_current 3098
telemt_connections_me_current 3098
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 184209
telemt_upstream_connect_attempt_total 62925
telemt_upstream_connect_success_total 62451
telemt_upstream_connect_fail_total 414
telemt_upstream_connect_attempts_per_request{bucket="1"} 62865
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36028
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25289
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 616
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 414
telemt_me_reconnect_attempts_total 5812
telemt_me_reconnect_success_total 1292
telemt_me_reader_eof_total 1159
telemt_me_idle_close_by_peer_total 1159
telemt_me_seq_mismatch_total 56
telemt_me_route_drop_no_conn_total 2281926
telemt_me_route_drop_channel_closed_total 191
telemt_me_route_drop_queue_full_total 13
telemt_me_route_drop_queue_full_profile_total{profile="high"} 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5226642
telemt_me_endpoint_quarantine_total 941
telemt_me_single_endpoint_outage_enter_total 30
telemt_me_single_endpoint_outage_exit_total 30
telemt_me_single_endpoint_outage_reconnect_attempt_total 30
telemt_me_single_endpoint_outage_reconnect_success_total 28
telemt_me_single_endpoint_quarantine_bypass_total 30
telemt_me_single_endpoint_shadow_rotate_total 916
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
telemt_me_writers_active_current 45
telemt_desync_total 21864
telemt_desync_full_logged_total 7272
telemt_desync_suppressed_total 14592
telemt_desync_frames_bucket_total{bucket="1_2"} 5483
telemt_desync_frames_bucket_total{bucket="3_10"} 7990
telemt_desync_frames_bucket_total{bucket="gt_10"} 8391
telemt_pool_swap_total 130
telemt_pool_force_close_total 3463
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 416
telemt_me_draining_writers_reap_progress_total 41061
telemt_me_writer_removed_unexpected_total 1171
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3874
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 38417
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3240
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 223
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 37598
telemt_me_writer_teardown_success_total{mode="normal"} 42291
telemt_me_writer_teardown_noop_total 41065
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 81600
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 82716
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 83118
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 83318
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 83356
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 83356
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 83356
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 83356
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 83356
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 83356
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 83356
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 83356
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 83356
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 11.714491
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 83356
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 416
telemt_me_refill_failed_total 260
telemt_me_writer_restored_same_endpoint_total 1009
telemt_me_writer_restored_fallback_total 74
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 82
telemt_me_writer_removed_unexpected_minus_restored_total 88
telemt_user_connections_total{user="hello"} 5229193
telemt_user_connections_current{user="hello"} 3098
telemt_user_octets_from_client{user="hello"} 97927455049 (91.20 GB)
telemt_user_octets_to_client{user="hello"} 2267770168072 (2.06 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1289
telemt_user_unique_ips_recent_window{user="hello"} 393
```