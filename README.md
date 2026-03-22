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

# Server Metrics 2026-03-22 00:13:11 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 11209.6 (3h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 172384
telemt_connections_bad_total 11520
telemt_connections_current 783
telemt_connections_me_current 783
telemt_handshake_timeouts_total 9611
telemt_upstream_connect_attempt_total 4564
telemt_upstream_connect_success_total 4563
telemt_upstream_connect_attempts_per_request{bucket="1"} 4563
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1697
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2852
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_me_reconnect_attempts_total 144
telemt_me_reconnect_success_total 72
telemt_me_reader_eof_total 73
telemt_me_idle_close_by_peer_total 73
telemt_me_route_drop_no_conn_total 35196
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 141424
telemt_me_endpoint_quarantine_total 74
telemt_me_single_endpoint_shadow_rotate_total 97
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 2
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
telemt_desync_total 946
telemt_desync_full_logged_total 282
telemt_desync_suppressed_total 664
telemt_desync_frames_bucket_total{bucket="1_2"} 227
telemt_desync_frames_bucket_total{bucket="3_10"} 316
telemt_desync_frames_bucket_total{bucket="gt_10"} 403
telemt_pool_swap_total 12
telemt_pool_force_close_total 326
telemt_me_writer_close_signal_drop_total 22
telemt_me_draining_writers_reap_progress_total 4083
telemt_me_writer_removed_unexpected_total 69
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 303
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 3837
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 322
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 3757
telemt_me_writer_teardown_success_total{mode="normal"} 4140
telemt_me_writer_teardown_noop_total 4084
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 7922
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 8099
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 8153
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 8198
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 8222
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 8224
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 8224
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 8224
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 8224
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 8224
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 8224
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 8224
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 8224
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.646965
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 8224
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 22
telemt_me_refill_failed_total 4
telemt_me_writer_restored_same_endpoint_total 65
telemt_me_writer_removed_unexpected_minus_restored_total 4
telemt_user_connections_total{user="hello"} 141243
telemt_user_connections_current{user="hello"} 783
telemt_user_octets_from_client{user="hello"} 1652656640 (1.54 GB)
telemt_user_octets_to_client{user="hello"} 50012777856 (46.58 GB)
telemt_user_unique_ips_current{user="hello"} 325
telemt_user_unique_ips_recent_window{user="hello"} 94
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 24576.2 (6h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 683644
telemt_connections_bad_total 38283
telemt_connections_current 401
telemt_connections_me_current 401
telemt_handshake_timeouts_total 25903
telemt_upstream_connect_attempt_total 10560
telemt_upstream_connect_success_total 10373
telemt_upstream_connect_fail_total 169
telemt_upstream_connect_attempts_per_request{bucket="1"} 10542
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4673
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5665
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 169
telemt_me_reconnect_attempts_total 926
telemt_me_reconnect_success_total 322
telemt_me_reader_eof_total 276
telemt_me_idle_close_by_peer_total 276
telemt_me_route_drop_no_conn_total 327956
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 553069
telemt_me_endpoint_quarantine_total 225
telemt_me_single_endpoint_outage_enter_total 14
telemt_me_single_endpoint_outage_exit_total 14
telemt_me_single_endpoint_outage_reconnect_attempt_total 14
telemt_me_single_endpoint_outage_reconnect_success_total 14
telemt_me_single_endpoint_quarantine_bypass_total 14
telemt_me_single_endpoint_shadow_rotate_total 199
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 16
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
telemt_desync_total 2413
telemt_desync_full_logged_total 1386
telemt_desync_suppressed_total 1027
telemt_desync_frames_bucket_total{bucket="1_2"} 517
telemt_desync_frames_bucket_total{bucket="3_10"} 903
telemt_desync_frames_bucket_total{bucket="gt_10"} 993
telemt_pool_swap_total 27
telemt_pool_force_close_total 748
telemt_me_writer_close_signal_drop_total 57
telemt_me_draining_writers_reap_progress_total 9306
telemt_me_writer_removed_unexpected_total 259
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 822
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 8747
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 741
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 8558
telemt_me_writer_teardown_success_total{mode="normal"} 9569
telemt_me_writer_teardown_noop_total 9306
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 18414
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 18683
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 18769
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 18861
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 18873
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 18875
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 18875
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 18875
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 18875
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 18875
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 18875
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 18875
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 18875
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.385812
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 18875
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 57
telemt_me_refill_failed_total 32
telemt_me_writer_restored_same_endpoint_total 221
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 29
telemt_user_connections_total{user="hello"} 552287
telemt_user_connections_current{user="hello"} 401
telemt_user_octets_from_client{user="hello"} 9224139164 (8.59 GB)
telemt_user_octets_to_client{user="hello"} 192196356052 (179.00 GB)
telemt_user_unique_ips_current{user="hello"} 249
telemt_user_unique_ips_recent_window{user="hello"} 105
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 99435.7 (27h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7473942
telemt_connections_bad_total 595004
telemt_connections_current 1540
telemt_connections_me_current 1540
telemt_handshake_timeouts_total 243117
telemt_upstream_connect_attempt_total 36111
telemt_upstream_connect_success_total 36041
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 36048
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16312
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19565
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 158
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1493
telemt_me_reconnect_success_total 746
telemt_me_reader_eof_total 755
telemt_me_idle_close_by_peer_total 755
telemt_me_route_drop_no_conn_total 4502991
telemt_me_route_drop_channel_closed_total 66
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6091354
telemt_me_endpoint_quarantine_total 630
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 739
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
telemt_desync_total 25838
telemt_desync_full_logged_total 8543
telemt_desync_suppressed_total 17295
telemt_desync_frames_bucket_total{bucket="1_2"} 5560
telemt_desync_frames_bucket_total{bucket="3_10"} 10081
telemt_desync_frames_bucket_total{bucket="gt_10"} 10197
telemt_pool_swap_total 107
telemt_pool_force_close_total 3608
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 576
telemt_me_draining_writers_reap_progress_total 32933
telemt_me_writer_removed_unexpected_total 726
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2785
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 30432
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3369
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 239
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 29325
telemt_me_writer_teardown_success_total{mode="normal"} 33217
telemt_me_writer_teardown_noop_total 32977
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 60283
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 62054
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 62998
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 64408
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 65356
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 65893
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 66183
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 66194
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 66194
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 66194
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 66194
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 66194
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 66194
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 153.639545
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 66194
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 576
telemt_me_refill_failed_total 39
telemt_me_writer_restored_same_endpoint_total 666
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 55
telemt_user_connections_total{user="hello"} 6083722
telemt_user_connections_current{user="hello"} 1540
telemt_user_octets_from_client{user="hello"} 104155125392 (97.00 GB)
telemt_user_octets_to_client{user="hello"} 2004154856060 (1.82 TB)
telemt_user_unique_ips_current{user="hello"} 780
telemt_user_unique_ips_recent_window{user="hello"} 158
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 99437.1 (27h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6147834
telemt_connections_bad_total 579158
telemt_connections_current 1834
telemt_connections_me_current 1834
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 202967
telemt_upstream_connect_attempt_total 40104
telemt_upstream_connect_success_total 39724
telemt_upstream_connect_fail_total 184
telemt_upstream_connect_attempts_per_request{bucket="1"} 39908
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19889
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19247
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 555
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 184
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 1845
telemt_me_reconnect_success_total 809
telemt_me_reader_eof_total 785
telemt_me_idle_close_by_peer_total 785
telemt_me_route_drop_no_conn_total 2189645
telemt_me_route_drop_channel_closed_total 255
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4608249
telemt_me_endpoint_quarantine_total 606
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 761
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
telemt_me_writers_active_current 84
telemt_desync_total 22133
telemt_desync_full_logged_total 7490
telemt_desync_suppressed_total 14643
telemt_desync_frames_bucket_total{bucket="1_2"} 5330
telemt_desync_frames_bucket_total{bucket="3_10"} 8586
telemt_desync_frames_bucket_total{bucket="gt_10"} 8217
telemt_pool_swap_total 108
telemt_pool_force_close_total 3246
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 346
telemt_me_draining_writers_reap_progress_total 31413
telemt_me_writer_removed_unexpected_total 764
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2701
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 29411
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3047
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 199
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 28167
telemt_me_writer_teardown_success_total{mode="normal"} 32112
telemt_me_writer_teardown_noop_total 31419
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 60272
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 61777
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 62345
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 62915
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 63326
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 63511
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 63531
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 63531
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 63531
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 63531
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 63531
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 63531
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 63531
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 47.999148
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 63531
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 346
telemt_me_refill_failed_total 55
telemt_me_writer_restored_same_endpoint_total 705
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 51
telemt_user_connections_total{user="hello"} 4546798
telemt_user_connections_current{user="hello"} 1834
telemt_user_octets_from_client{user="hello"} 138245875149 (128.75 GB)
telemt_user_octets_to_client{user="hello"} 2128346325515 (1.94 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 854
telemt_user_unique_ips_recent_window{user="hello"} 129
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 99401.1 (27h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6057847
telemt_connections_bad_total 540453
telemt_connections_current 1232
telemt_connections_me_current 1232
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 193976
telemt_upstream_connect_attempt_total 46510
telemt_upstream_connect_success_total 46200
telemt_upstream_connect_fail_total 135
telemt_upstream_connect_attempts_per_request{bucket="1"} 46335
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24079
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20710
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 365
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1046
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 135
telemt_me_keepalive_timeout_total 58
telemt_me_reconnect_attempts_total 1815
telemt_me_reconnect_success_total 827
telemt_me_reader_eof_total 775
telemt_me_idle_close_by_peer_total 775
telemt_me_route_drop_no_conn_total 2108666
telemt_me_route_drop_channel_closed_total 109
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4522558
telemt_me_endpoint_quarantine_total 674
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 745
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 35
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
telemt_desync_total 21962
telemt_desync_full_logged_total 7329
telemt_desync_suppressed_total 14633
telemt_desync_frames_bucket_total{bucket="1_2"} 5372
telemt_desync_frames_bucket_total{bucket="3_10"} 8410
telemt_desync_frames_bucket_total{bucket="gt_10"} 8180
telemt_pool_swap_total 107
telemt_pool_force_close_total 3150
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 369
telemt_me_draining_writers_reap_progress_total 32957
telemt_me_writer_removed_unexpected_total 741
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2754
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 30953
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2935
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 215
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 29807
telemt_me_writer_teardown_success_total{mode="normal"} 33707
telemt_me_writer_teardown_noop_total 32968
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 64190
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 65538
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 65968
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 66425
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 66632
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 66657
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 66675
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 66675
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 66675
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 66675
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 66675
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 66675
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 66675
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 25.536636
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 66675
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 369
telemt_me_refill_failed_total 54
telemt_me_writer_restored_same_endpoint_total 717
telemt_me_writer_restored_fallback_total 4
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 4523518
telemt_user_connections_current{user="hello"} 1232
telemt_user_octets_from_client{user="hello"} 131859222075 (122.80 GB)
telemt_user_octets_to_client{user="hello"} 2074376273935 (1.89 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 630
telemt_user_unique_ips_recent_window{user="hello"} 121
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 99440.5 (27h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20021963
telemt_connections_bad_total 1489280
telemt_connections_current 2182
telemt_connections_me_current 2182
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 579533
telemt_upstream_connect_attempt_total 189604
telemt_upstream_connect_success_total 171961
telemt_upstream_connect_fail_total 16038
telemt_upstream_connect_attempts_per_request{bucket="1"} 187999
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 121583
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 40272
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1221
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8885
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16038
telemt_me_keepalive_timeout_total 398
telemt_me_reconnect_attempts_total 64366
telemt_me_reconnect_success_total 2170
telemt_me_reader_eof_total 1357
telemt_me_idle_close_by_peer_total 1356
telemt_me_route_drop_no_conn_total 39456354
telemt_me_route_drop_channel_closed_total 122
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 16285320
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 5
telemt_me_endpoint_quarantine_total 766
telemt_me_single_endpoint_outage_enter_total 123
telemt_me_single_endpoint_outage_exit_total 123
telemt_me_single_endpoint_outage_reconnect_attempt_total 259
telemt_me_single_endpoint_outage_reconnect_success_total 62
telemt_me_single_endpoint_quarantine_bypass_total 259
telemt_me_single_endpoint_shadow_rotate_total 777
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
telemt_me_writers_active_current 45
telemt_desync_total 31349
telemt_desync_full_logged_total 9335
telemt_desync_suppressed_total 22014
telemt_desync_frames_bucket_total{bucket="1_2"} 6831
telemt_desync_frames_bucket_total{bucket="3_10"} 13881
telemt_desync_frames_bucket_total{bucket="gt_10"} 10637
telemt_pool_swap_total 102
telemt_pool_force_close_total 3377
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 762
telemt_me_draining_writers_reap_progress_total 30907
telemt_me_writer_removed_unexpected_total 2016
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4234
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 28425
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 23
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2861
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 516
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 27530
telemt_me_writer_teardown_success_total{mode="normal"} 32659
telemt_me_writer_teardown_noop_total 30933
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 57048
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 59389
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 60638
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 62228
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 63156
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 63491
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 63573
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 63575
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 63578
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 63583
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 63583
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 63587
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 63592
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 212.163288
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 63592
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 762
telemt_me_refill_failed_total 3789
telemt_me_writer_restored_same_endpoint_total 1503
telemt_me_writer_restored_fallback_total 21
telemt_me_no_writer_failfast_total 666
telemt_me_async_recovery_trigger_total 14678
telemt_me_writer_removed_unexpected_minus_restored_total 492
telemt_user_connections_total{user="hello"} 16413158
telemt_user_connections_current{user="hello"} 2182
telemt_user_octets_from_client{user="hello"} 189572787964 (176.55 GB)
telemt_user_octets_to_client{user="hello"} 1127014466806 (1.03 TB)
telemt_user_msgs_from_client{user="hello"} 367794
telemt_user_msgs_to_client{user="hello"} 650852
telemt_user_unique_ips_current{user="hello"} 1031
telemt_user_unique_ips_recent_window{user="hello"} 228
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 99407.9 (27h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5851059
telemt_connections_bad_total 552199
telemt_connections_current 1639
telemt_connections_me_current 1639
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 120949
telemt_upstream_connect_attempt_total 54682
telemt_upstream_connect_success_total 54057
telemt_upstream_connect_fail_total 534
telemt_upstream_connect_attempts_per_request{bucket="1"} 54591
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32104
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21611
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 341
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 534
telemt_me_reconnect_attempts_total 68111
telemt_me_reconnect_success_total 1694
telemt_me_reader_eof_total 1472
telemt_me_idle_close_by_peer_total 1471
telemt_me_route_drop_no_conn_total 2360755
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 39
telemt_me_route_drop_queue_full_profile_total{profile="high"} 39
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4560196
telemt_me_endpoint_quarantine_total 663
telemt_me_single_endpoint_outage_enter_total 20
telemt_me_single_endpoint_outage_exit_total 20
telemt_me_single_endpoint_outage_reconnect_attempt_total 21
telemt_me_single_endpoint_outage_reconnect_success_total 20
telemt_me_single_endpoint_quarantine_bypass_total 21
telemt_me_single_endpoint_shadow_rotate_total 747
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
telemt_desync_total 23008
telemt_desync_full_logged_total 8066
telemt_desync_suppressed_total 14942
telemt_desync_frames_bucket_total{bucket="1_2"} 4363
telemt_desync_frames_bucket_total{bucket="3_10"} 8914
telemt_desync_frames_bucket_total{bucket="gt_10"} 9731
telemt_pool_swap_total 102
telemt_pool_force_close_total 2996
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 379
telemt_me_draining_writers_reap_progress_total 34364
telemt_me_writer_removed_unexpected_total 1517
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3646
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 32259
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2595
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 401
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 31368
telemt_me_writer_teardown_success_total{mode="normal"} 35905
telemt_me_writer_teardown_noop_total 34365
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 69041
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 69845
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 70118
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 70238
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 70267
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 70270
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 70270
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 70270
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 70270
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 70270
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 70270
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 70270
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 70270
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.971351
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 70270
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 379
telemt_me_refill_failed_total 4119
telemt_me_writer_restored_same_endpoint_total 1429
telemt_me_writer_restored_fallback_total 30
telemt_me_no_writer_failfast_total 223
telemt_me_async_recovery_trigger_total 7257
telemt_me_writer_removed_unexpected_minus_restored_total 58
telemt_user_connections_total{user="hello"} 4553288
telemt_user_connections_current{user="hello"} 1639
telemt_user_octets_from_client{user="hello"} 122164689320 (113.77 GB)
telemt_user_octets_to_client{user="hello"} 1861484352090 (1.69 TB)
telemt_user_msgs_from_client{user="hello"} 77823
telemt_user_msgs_to_client{user="hello"} 338392
telemt_user_unique_ips_current{user="hello"} 799
telemt_user_unique_ips_recent_window{user="hello"} 154
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 36243.8 (10h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3721807
telemt_connections_bad_total 131824
telemt_connections_current 972
telemt_connections_me_current 972
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 1545405
telemt_upstream_connect_attempt_total 22971
telemt_upstream_connect_success_total 22824
telemt_upstream_connect_fail_total 140
telemt_upstream_connect_attempts_per_request{bucket="1"} 22964
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15178
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7580
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 66
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 140
telemt_me_reconnect_attempts_total 45597
telemt_me_reconnect_success_total 895
telemt_me_reader_eof_total 567
telemt_me_idle_close_by_peer_total 567
telemt_me_route_drop_no_conn_total 998521
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1802855
telemt_me_endpoint_quarantine_total 263
telemt_me_single_endpoint_outage_enter_total 10
telemt_me_single_endpoint_outage_exit_total 10
telemt_me_single_endpoint_outage_reconnect_attempt_total 49
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 49
telemt_me_single_endpoint_shadow_rotate_total 275
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 7
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
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 10001
telemt_desync_full_logged_total 3429
telemt_desync_suppressed_total 6572
telemt_desync_frames_bucket_total{bucket="1_2"} 1765
telemt_desync_frames_bucket_total{bucket="3_10"} 3831
telemt_desync_frames_bucket_total{bucket="gt_10"} 4405
telemt_pool_swap_total 39
telemt_pool_force_close_total 1273
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 121
telemt_me_draining_writers_reap_progress_total 12412
telemt_me_writer_removed_unexpected_total 647
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1319
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 11760
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1067
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 206
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 11139
telemt_me_writer_teardown_success_total{mode="normal"} 13079
telemt_me_writer_teardown_noop_total 12414
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 25035
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 25299
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 25387
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 25493
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 25493
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 25493
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 25493
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 25493
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 25493
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 25493
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 25493
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 25493
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 25493
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.093056
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 25493
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 121
telemt_me_refill_failed_total 2597
telemt_me_writer_restored_same_endpoint_total 803
telemt_me_writer_restored_fallback_total 11
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4264
telemt_user_connections_total{user="hello"} 1806602
telemt_user_connections_current{user="hello"} 972
telemt_user_octets_from_client{user="hello"} 52725631716 (49.10 GB)
telemt_user_octets_to_client{user="hello"} 773045363950 (719.95 GB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 486
telemt_user_unique_ips_recent_window{user="hello"} 142
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 17214.6 (4h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 162557
telemt_connections_bad_total 1399
telemt_connections_current 294
telemt_connections_me_current 294
telemt_handshake_timeouts_total 3874
telemt_upstream_connect_attempt_total 7927
telemt_upstream_connect_success_total 7907
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 7926
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3403
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4436
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 68
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_reconnect_attempts_total 164
telemt_me_reconnect_success_total 102
telemt_me_reader_eof_total 102
telemt_me_idle_close_by_peer_total 102
telemt_me_route_drop_no_conn_total 46135
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 143033
telemt_me_endpoint_quarantine_total 161
telemt_me_single_endpoint_shadow_rotate_total 152
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
telemt_me_writers_active_current 43
telemt_desync_total 973
telemt_desync_full_logged_total 242
telemt_desync_suppressed_total 731
telemt_desync_frames_bucket_total{bucket="1_2"} 384
telemt_desync_frames_bucket_total{bucket="3_10"} 351
telemt_desync_frames_bucket_total{bucket="gt_10"} 238
telemt_pool_swap_total 19
telemt_pool_force_close_total 421
telemt_me_writer_close_signal_drop_total 18
telemt_me_draining_writers_reap_progress_total 7096
telemt_me_writer_removed_unexpected_total 100
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 464
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 6734
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 419
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 6675
telemt_me_writer_teardown_success_total{mode="normal"} 7198
telemt_me_writer_teardown_noop_total 7096
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 14150
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 14266
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 14284
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 14294
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 14294
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 14294
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 14294
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 14294
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 14294
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 14294
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 14294
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 14294
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 14294
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.791436
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 14294
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 18
telemt_me_refill_failed_total 4
telemt_me_writer_restored_same_endpoint_total 94
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 142772
telemt_user_connections_current{user="hello"} 294
telemt_user_octets_from_client{user="hello"} 2617195952 (2.44 GB)
telemt_user_octets_to_client{user="hello"} 82728558992 (77.05 GB)
telemt_user_unique_ips_current{user="hello"} 146
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 99412.4 (27h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7060539
telemt_connections_bad_total 715514
telemt_connections_current 1774
telemt_connections_me_current 1774
telemt_handshake_timeouts_total 201131
telemt_upstream_connect_attempt_total 38139
telemt_upstream_connect_success_total 37992
telemt_upstream_connect_fail_total 110
telemt_upstream_connect_attempts_per_request{bucket="1"} 38102
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18876
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19075
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 110
telemt_me_reconnect_attempts_total 1500
telemt_me_reconnect_success_total 787
telemt_me_reader_eof_total 767
telemt_me_idle_close_by_peer_total 767
telemt_me_route_drop_no_conn_total 2099645
telemt_me_route_drop_channel_closed_total 52
telemt_me_route_drop_queue_full_total 23
telemt_me_route_drop_queue_full_profile_total{profile="high"} 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5325878
telemt_me_endpoint_quarantine_total 685
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 763
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 29
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
telemt_desync_total 20562
telemt_desync_full_logged_total 6869
telemt_desync_suppressed_total 13693
telemt_desync_frames_bucket_total{bucket="1_2"} 5010
telemt_desync_frames_bucket_total{bucket="3_10"} 7455
telemt_desync_frames_bucket_total{bucket="gt_10"} 8097
telemt_pool_swap_total 110
telemt_pool_force_close_total 2996
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 372
telemt_me_draining_writers_reap_progress_total 34331
telemt_me_writer_removed_unexpected_total 740
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2771
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 32317
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2908
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 31335
telemt_me_writer_teardown_success_total{mode="normal"} 35088
telemt_me_writer_teardown_noop_total 34333
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 68076
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 68955
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 69133
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 69333
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 69421
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 69421
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 69421
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 69421
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 69421
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 69421
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 69421
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 69421
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 69421
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.570653
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 69421
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 372
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 702
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 33
telemt_user_connections_total{user="hello"} 5301056
telemt_user_connections_current{user="hello"} 1774
telemt_user_octets_from_client{user="hello"} 107827017492 (100.42 GB)
telemt_user_octets_to_client{user="hello"} 2489527733184 (2.26 TB)
telemt_user_unique_ips_current{user="hello"} 758
telemt_user_unique_ips_recent_window{user="hello"} 143
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 99409.0 (27h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6048040
telemt_connections_bad_total 594491
telemt_connections_current 1575
telemt_connections_me_current 1575
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 167720
telemt_upstream_connect_attempt_total 54086
telemt_upstream_connect_success_total 53675
telemt_upstream_connect_fail_total 352
telemt_upstream_connect_attempts_per_request{bucket="1"} 54027
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31705
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20837
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 615
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 352
telemt_me_reconnect_attempts_total 5383
telemt_me_reconnect_success_total 1093
telemt_me_reader_eof_total 974
telemt_me_idle_close_by_peer_total 974
telemt_me_seq_mismatch_total 42
telemt_me_route_drop_no_conn_total 2153420
telemt_me_route_drop_channel_closed_total 189
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4696287
telemt_me_endpoint_quarantine_total 790
telemt_me_single_endpoint_outage_enter_total 27
telemt_me_single_endpoint_outage_exit_total 27
telemt_me_single_endpoint_outage_reconnect_attempt_total 27
telemt_me_single_endpoint_outage_reconnect_success_total 25
telemt_me_single_endpoint_quarantine_bypass_total 27
telemt_me_single_endpoint_shadow_rotate_total 758
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 31
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
telemt_me_writers_active_current 42
telemt_desync_total 19359
telemt_desync_full_logged_total 6501
telemt_desync_suppressed_total 12858
telemt_desync_frames_bucket_total{bucket="1_2"} 4872
telemt_desync_frames_bucket_total{bucket="3_10"} 7043
telemt_desync_frames_bucket_total{bucket="gt_10"} 7444
telemt_pool_swap_total 108
telemt_pool_force_close_total 2954
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 367
telemt_me_draining_writers_reap_progress_total 33069
telemt_me_writer_removed_unexpected_total 987
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3252
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 30848
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2731
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 223
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 30115
telemt_me_writer_teardown_success_total{mode="normal"} 34100
telemt_me_writer_teardown_noop_total 33073
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 65565
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 66599
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 66940
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 67135
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 67173
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 67173
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 67173
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 67173
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 67173
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 67173
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 67173
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 67173
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 67173
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.902230
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 67173
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 367
telemt_me_refill_failed_total 248
telemt_me_writer_restored_same_endpoint_total 848
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 76
telemt_me_writer_removed_unexpected_minus_restored_total 84
telemt_user_connections_total{user="hello"} 4699535
telemt_user_connections_current{user="hello"} 1575
telemt_user_octets_from_client{user="hello"} 88843434021 (82.74 GB)
telemt_user_octets_to_client{user="hello"} 2015718188856 (1.83 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 747
telemt_user_unique_ips_recent_window{user="hello"} 155
```