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

# Server Metrics 2026-03-21 06:48:16 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 36743.7 (10h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 791197
telemt_connections_bad_total 43101
telemt_connections_current 1339
telemt_connections_me_current 1339
telemt_handshake_timeouts_total 39133
telemt_upstream_connect_attempt_total 14853
telemt_upstream_connect_success_total 14786
telemt_upstream_connect_fail_total 44
telemt_upstream_connect_attempts_per_request{bucket="1"} 14830
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5130
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9611
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 44
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 461
telemt_me_reconnect_success_total 239
telemt_me_reader_eof_total 251
telemt_me_idle_close_by_peer_total 251
telemt_me_route_drop_no_conn_total 261275
telemt_me_route_drop_channel_closed_total 74
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 589755
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_endpoint_quarantine_total 258
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 303
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
telemt_me_writers_active_current 44
telemt_desync_total 2580
telemt_desync_full_logged_total 935
telemt_desync_suppressed_total 1645
telemt_desync_frames_bucket_total{bucket="1_2"} 533
telemt_desync_frames_bucket_total{bucket="3_10"} 1018
telemt_desync_frames_bucket_total{bucket="gt_10"} 1029
telemt_pool_swap_total 40
telemt_pool_force_close_total 1096
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 100
telemt_me_draining_writers_reap_progress_total 13382
telemt_me_writer_removed_unexpected_total 236
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 986
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 12590
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1092
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 12286
telemt_me_writer_teardown_success_total{mode="normal"} 13576
telemt_me_writer_teardown_noop_total 13383
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 25474
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 25914
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 26080
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 26388
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 26753
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 26897
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 26954
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 26959
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 26959
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 26959
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 26959
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 26959
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 26959
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 41.741649
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 26959
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 100
telemt_me_refill_failed_total 12
telemt_me_writer_restored_same_endpoint_total 216
telemt_me_writer_restored_fallback_total 3
telemt_me_writer_removed_unexpected_minus_restored_total 17
telemt_user_connections_total{user="hello"} 589028
telemt_user_connections_current{user="hello"} 1339
telemt_user_octets_from_client{user="hello"} 6998888432 (6.52 GB)
telemt_user_octets_to_client{user="hello"} 185134070352 (172.42 GB)
telemt_user_unique_ips_current{user="hello"} 506
telemt_user_unique_ips_recent_window{user="hello"} 198
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 36745.5 (10h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1998103
telemt_connections_bad_total 224316
telemt_connections_current 3822
telemt_connections_me_current 3822
telemt_handshake_timeouts_total 62032
telemt_upstream_connect_attempt_total 13835
telemt_upstream_connect_success_total 13771
telemt_upstream_connect_fail_total 44
telemt_upstream_connect_attempts_per_request{bucket="1"} 13815
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5642
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8089
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 44
telemt_me_reconnect_attempts_total 774
telemt_me_reconnect_success_total 279
telemt_me_reader_eof_total 288
telemt_me_idle_close_by_peer_total 288
telemt_me_route_drop_no_conn_total 393263
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1194826
telemt_me_endpoint_quarantine_total 241
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 295
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
telemt_me_writers_active_current 43
telemt_desync_total 5054
telemt_desync_full_logged_total 1765
telemt_desync_suppressed_total 3289
telemt_desync_frames_bucket_total{bucket="1_2"} 1033
telemt_desync_frames_bucket_total{bucket="3_10"} 2011
telemt_desync_frames_bucket_total{bucket="gt_10"} 2010
telemt_pool_swap_total 39
telemt_pool_force_close_total 1160
telemt_me_writer_close_signal_drop_total 118
telemt_me_draining_writers_reap_progress_total 12411
telemt_me_writer_removed_unexpected_total 269
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1090
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 11582
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1107
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 53
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 11251
telemt_me_writer_teardown_success_total{mode="normal"} 12672
telemt_me_writer_teardown_noop_total 12411
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 24224
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 24573
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 24766
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 25018
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 25081
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 25083
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 25083
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 25083
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 25083
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 25083
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 25083
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 25083
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 25083
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.940533
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 25083
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 118
telemt_me_refill_failed_total 27
telemt_me_writer_restored_same_endpoint_total 236
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 32
telemt_user_connections_total{user="hello"} 1191845
telemt_user_connections_current{user="hello"} 3822
telemt_user_octets_from_client{user="hello"} 16535701944 (15.40 GB)
telemt_user_octets_to_client{user="hello"} 492455730920 (458.64 GB)
telemt_user_unique_ips_current{user="hello"} 1421
telemt_user_unique_ips_recent_window{user="hello"} 504
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 36742.2 (10h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1323335
telemt_connections_bad_total 159557
telemt_connections_current 3338
telemt_connections_me_current 3338
telemt_handshake_timeouts_total 61181
telemt_upstream_connect_attempt_total 14952
telemt_upstream_connect_success_total 14942
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 14943
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6799
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8099
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 44
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 413
telemt_me_reconnect_success_total 241
telemt_me_reader_eof_total 251
telemt_me_idle_close_by_peer_total 251
telemt_me_route_drop_no_conn_total 322489
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1025655
telemt_me_endpoint_quarantine_total 259
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 294
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 11
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
telemt_desync_total 4100
telemt_desync_full_logged_total 1488
telemt_desync_suppressed_total 2612
telemt_desync_frames_bucket_total{bucket="1_2"} 919
telemt_desync_frames_bucket_total{bucket="3_10"} 1582
telemt_desync_frames_bucket_total{bucket="gt_10"} 1599
telemt_pool_swap_total 40
telemt_pool_force_close_total 1095
telemt_pool_stale_pick_total 16
telemt_me_writer_close_signal_drop_total 124
telemt_me_draining_writers_reap_progress_total 13614
telemt_me_writer_removed_unexpected_total 232
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1052
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 12731
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1089
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 12519
telemt_me_writer_teardown_success_total{mode="normal"} 13783
telemt_me_writer_teardown_noop_total 13617
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 26093
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 26603
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 26874
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 27244
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 27371
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 27392
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 27400
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 27400
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 27400
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 27400
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 27400
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 27400
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 27400
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 16.924459
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 27400
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 124
telemt_me_refill_failed_total 8
telemt_me_writer_restored_same_endpoint_total 207
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 1023448
telemt_user_connections_current{user="hello"} 3338
telemt_user_octets_from_client{user="hello"} 14169854028 (13.20 GB)
telemt_user_octets_to_client{user="hello"} 452934739164 (421.83 GB)
telemt_user_unique_ips_current{user="hello"} 1263
telemt_user_unique_ips_recent_window{user="hello"} 428
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 36743.6 (10h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1147889
telemt_connections_bad_total 154920
telemt_connections_current 2690
telemt_connections_me_current 2690
telemt_handshake_timeouts_total 56116
telemt_upstream_connect_attempt_total 15070
telemt_upstream_connect_success_total 14974
telemt_upstream_connect_fail_total 41
telemt_upstream_connect_attempts_per_request{bucket="1"} 15015
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6589
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8353
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 16
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 41
telemt_me_reconnect_attempts_total 656
telemt_me_reconnect_success_total 271
telemt_me_reader_eof_total 269
telemt_me_idle_close_by_peer_total 269
telemt_me_route_drop_no_conn_total 253294
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 776564
telemt_me_endpoint_quarantine_total 260
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 297
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 8
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
telemt_desync_total 3498
telemt_desync_full_logged_total 1290
telemt_desync_suppressed_total 2208
telemt_desync_frames_bucket_total{bucket="1_2"} 764
telemt_desync_frames_bucket_total{bucket="3_10"} 1499
telemt_desync_frames_bucket_total{bucket="gt_10"} 1235
telemt_pool_swap_total 40
telemt_pool_force_close_total 1040
telemt_me_writer_close_signal_drop_total 51
telemt_me_draining_writers_reap_progress_total 13511
telemt_me_writer_removed_unexpected_total 259
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 978
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 12806
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1022
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 18
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 12471
telemt_me_writer_teardown_success_total{mode="normal"} 13784
telemt_me_writer_teardown_noop_total 13512
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 27038
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 27214
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 27252
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 27266
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 27296
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 27296
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 27296
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 27296
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 27296
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 27296
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 27296
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 27296
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 27296
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.162517
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 27296
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 51
telemt_me_refill_failed_total 21
telemt_me_writer_restored_same_endpoint_total 232
telemt_me_writer_restored_fallback_total 3
telemt_me_async_recovery_trigger_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 24
telemt_user_connections_total{user="hello"} 775191
telemt_user_connections_current{user="hello"} 2690
telemt_user_octets_from_client{user="hello"} 14025907616 (13.06 GB)
telemt_user_octets_to_client{user="hello"} 375032518512 (349.28 GB)
telemt_user_unique_ips_current{user="hello"} 999
telemt_user_unique_ips_recent_window{user="hello"} 370
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 36707.5 (10h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1093032
telemt_connections_bad_total 135798
telemt_connections_current 2579
telemt_connections_me_current 2579
telemt_handshake_timeouts_total 40199
telemt_upstream_connect_attempt_total 15598
telemt_upstream_connect_success_total 15589
telemt_upstream_connect_attempts_per_request{bucket="1"} 15589
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6914
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8660
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_me_reconnect_attempts_total 276
telemt_me_reconnect_success_total 232
telemt_me_reader_eof_total 229
telemt_me_idle_close_by_peer_total 229
telemt_me_route_drop_no_conn_total 222309
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 772077
telemt_me_endpoint_quarantine_total 305
telemt_me_single_endpoint_shadow_rotate_total 293
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 11
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
telemt_desync_total 3660
telemt_desync_full_logged_total 1352
telemt_desync_suppressed_total 2308
telemt_desync_frames_bucket_total{bucket="1_2"} 914
telemt_desync_frames_bucket_total{bucket="3_10"} 1431
telemt_desync_frames_bucket_total{bucket="gt_10"} 1315
telemt_pool_swap_total 40
telemt_pool_force_close_total 996
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 61
telemt_me_draining_writers_reap_progress_total 14133
telemt_me_writer_removed_unexpected_total 210
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 929
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 13434
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 986
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13137
telemt_me_writer_teardown_success_total{mode="normal"} 14363
telemt_me_writer_teardown_noop_total 14134
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 28285
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 28422
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 28458
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 28497
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 28497
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 28497
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 28497
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 28497
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 28497
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 28497
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 28497
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 28497
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 28497
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.457565
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 28497
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 61
telemt_me_refill_failed_total 2
telemt_me_writer_restored_same_endpoint_total 206
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 770572
telemt_user_connections_current{user="hello"} 2579
telemt_user_octets_from_client{user="hello"} 19512505256 (18.17 GB)
telemt_user_octets_to_client{user="hello"} 401101830704 (373.56 GB)
telemt_user_unique_ips_current{user="hello"} 993
telemt_user_unique_ips_recent_window{user="hello"} 348
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 36746.2 (10h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2312645
telemt_connections_bad_total 169297
telemt_connections_current 4448
telemt_connections_me_current 4448
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 150843
telemt_upstream_connect_attempt_total 41081
telemt_upstream_connect_success_total 39238
telemt_upstream_connect_fail_total 1324
telemt_upstream_connect_attempts_per_request{bucket="1"} 40562
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28028
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9984
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1226
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1324
telemt_me_reconnect_attempts_total 1780
telemt_me_reconnect_success_total 578
telemt_me_reader_eof_total 387
telemt_me_idle_close_by_peer_total 386
telemt_me_route_drop_no_conn_total 1892799
telemt_me_route_drop_channel_closed_total 24
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1823005
telemt_me_endpoint_quarantine_total 294
telemt_me_single_endpoint_outage_enter_total 36
telemt_me_single_endpoint_outage_exit_total 36
telemt_me_single_endpoint_outage_reconnect_attempt_total 78
telemt_me_single_endpoint_outage_reconnect_success_total 16
telemt_me_single_endpoint_quarantine_bypass_total 78
telemt_me_single_endpoint_shadow_rotate_total 295
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
telemt_me_writers_active_current 44
telemt_desync_total 4553
telemt_desync_full_logged_total 1689
telemt_desync_suppressed_total 2864
telemt_desync_frames_bucket_total{bucket="1_2"} 1039
telemt_desync_frames_bucket_total{bucket="3_10"} 1923
telemt_desync_frames_bucket_total{bucket="gt_10"} 1591
telemt_pool_swap_total 39
telemt_pool_force_close_total 1084
telemt_me_writer_close_signal_drop_total 158
telemt_me_draining_writers_reap_progress_total 12575
telemt_me_writer_removed_unexpected_total 558
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1417
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 11685
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1018
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 66
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 11491
telemt_me_writer_teardown_success_total{mode="normal"} 13102
telemt_me_writer_teardown_noop_total 12579
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 24313
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 24741
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 25112
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 25441
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 25588
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 25674
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 25681
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 25681
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 25681
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 25681
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 25681
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 25681
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 25681
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 20.974031
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 25681
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 158
telemt_me_refill_failed_total 44
telemt_me_writer_restored_same_endpoint_total 372
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 6
telemt_me_writer_removed_unexpected_minus_restored_total 178
telemt_user_connections_total{user="hello"} 1846216
telemt_user_connections_current{user="hello"} 4448
telemt_user_octets_from_client{user="hello"} 33005454478 (30.74 GB)
telemt_user_octets_to_client{user="hello"} 454184956526 (422.99 GB)
telemt_user_msgs_from_client{user="hello"} 103363
telemt_user_msgs_to_client{user="hello"} 429893
telemt_user_unique_ips_current{user="hello"} 1558
telemt_user_unique_ips_recent_window{user="hello"} 712
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 36713.7 (10h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1173055
telemt_connections_bad_total 164975
telemt_connections_current 2563
telemt_connections_me_current 2563
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 24931
telemt_upstream_connect_attempt_total 17062
telemt_upstream_connect_success_total 16911
telemt_upstream_connect_fail_total 136
telemt_upstream_connect_attempts_per_request{bucket="1"} 17047
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8333
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8544
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 34
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 136
telemt_me_reconnect_attempts_total 1397
telemt_me_reconnect_success_total 337
telemt_me_reader_eof_total 347
telemt_me_idle_close_by_peer_total 347
telemt_me_route_drop_no_conn_total 280031
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 844571
telemt_me_endpoint_quarantine_total 245
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 296
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 17
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
telemt_desync_total 3460
telemt_desync_full_logged_total 1311
telemt_desync_suppressed_total 2149
telemt_desync_frames_bucket_total{bucket="1_2"} 668
telemt_desync_frames_bucket_total{bucket="3_10"} 1418
telemt_desync_frames_bucket_total{bucket="gt_10"} 1374
telemt_pool_swap_total 40
telemt_pool_force_close_total 956
telemt_me_writer_close_signal_drop_total 59
telemt_me_draining_writers_reap_progress_total 14062
telemt_me_writer_removed_unexpected_total 327
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1058
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 13351
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 949
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13106
telemt_me_writer_teardown_success_total{mode="normal"} 14409
telemt_me_writer_teardown_noop_total 14062
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 28270
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 28380
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 28471
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 28471
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 28471
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 28471
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 28471
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 28471
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 28471
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 28471
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 28471
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 28471
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 28471
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.060343
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 28471
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 59
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 258
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 63
telemt_user_connections_total{user="hello"} 842183
telemt_user_connections_current{user="hello"} 2563
telemt_user_octets_from_client{user="hello"} 13999555508 (13.04 GB)
telemt_user_octets_to_client{user="hello"} 420063930382 (391.22 GB)
telemt_user_msgs_from_client{user="hello"} 7339
telemt_user_msgs_to_client{user="hello"} 11522
telemt_user_unique_ips_current{user="hello"} 1017
telemt_user_unique_ips_recent_window{user="hello"} 340
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 36707.9 (10h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1485215
telemt_connections_bad_total 92967
telemt_connections_current 2416
telemt_connections_me_current 2416
telemt_handshake_timeouts_total 530910
telemt_upstream_connect_attempt_total 16275
telemt_upstream_connect_success_total 16248
telemt_upstream_connect_attempts_per_request{bucket="1"} 16248
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7284
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8705
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 259
telemt_me_reconnect_attempts_total 348
telemt_me_reconnect_success_total 243
telemt_me_reader_eof_total 251
telemt_me_idle_close_by_peer_total 251
telemt_me_route_drop_no_conn_total 246440
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 751082
telemt_me_endpoint_quarantine_total 313
telemt_me_single_endpoint_shadow_rotate_total 301
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
telemt_me_writers_active_current 45
telemt_desync_total 3365
telemt_desync_full_logged_total 1193
telemt_desync_suppressed_total 2172
telemt_desync_frames_bucket_total{bucket="1_2"} 611
telemt_desync_frames_bucket_total{bucket="3_10"} 1365
telemt_desync_frames_bucket_total{bucket="gt_10"} 1389
telemt_pool_swap_total 40
telemt_pool_force_close_total 918
telemt_me_writer_close_signal_drop_total 53
telemt_me_draining_writers_reap_progress_total 14578
telemt_me_writer_removed_unexpected_total 235
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 860
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 13970
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 910
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13660
telemt_me_writer_teardown_success_total{mode="normal"} 14830
telemt_me_writer_teardown_noop_total 14578
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 29318
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 29381
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 29408
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 29408
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 29408
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 29408
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 29408
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 29408
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 29408
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 29408
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 29408
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 29408
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 29408
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.516468
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 29408
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 53
telemt_me_refill_failed_total 5
telemt_me_writer_restored_same_endpoint_total 218
telemt_me_writer_restored_fallback_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 15
telemt_user_connections_total{user="hello"} 748141
telemt_user_connections_current{user="hello"} 2416
telemt_user_octets_from_client{user="hello"} 12130954576 (11.30 GB)
telemt_user_octets_to_client{user="hello"} 387754090868 (361.12 GB)
telemt_user_unique_ips_current{user="hello"} 1001
telemt_user_unique_ips_recent_window{user="hello"} 359
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 34699.2 (9h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 286860
telemt_connections_bad_total 11215
telemt_connections_current 546
telemt_connections_me_current 546
telemt_handshake_timeouts_total 77910
telemt_upstream_connect_attempt_total 17675
telemt_upstream_connect_success_total 17674
telemt_upstream_connect_attempts_per_request{bucket="1"} 17674
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7460
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10178
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 539
telemt_me_reconnect_success_total 251
telemt_me_reader_eof_total 264
telemt_me_idle_close_by_peer_total 264
telemt_me_route_drop_no_conn_total 68317
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 183617
telemt_me_endpoint_quarantine_total 340
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 301
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 4
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
telemt_desync_total 1106
telemt_desync_full_logged_total 529
telemt_desync_suppressed_total 577
telemt_desync_frames_bucket_total{bucket="1_2"} 210
telemt_desync_frames_bucket_total{bucket="3_10"} 460
telemt_desync_frames_bucket_total{bucket="gt_10"} 436
telemt_pool_swap_total 38
telemt_pool_force_close_total 778
telemt_me_writer_close_signal_drop_total 47
telemt_me_draining_writers_reap_progress_total 15784
telemt_me_writer_removed_unexpected_total 248
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1087
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14946
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 778
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15006
telemt_me_writer_teardown_success_total{mode="normal"} 16033
telemt_me_writer_teardown_noop_total 15784
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 31631
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 31785
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 31815
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 31817
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 31817
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 31817
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 31817
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 31817
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 31817
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 31817
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 31817
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 31817
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 31817
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.997556
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 31817
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 47
telemt_me_refill_failed_total 16
telemt_me_writer_restored_same_endpoint_total 220
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 27
telemt_user_connections_total{user="hello"} 183845
telemt_user_connections_current{user="hello"} 546
telemt_user_octets_from_client{user="hello"} 1994440723 (1.86 GB)
telemt_user_octets_to_client{user="hello"} 77265216509 (71.96 GB)
telemt_user_msgs_from_client{user="hello"} 804
telemt_user_msgs_to_client{user="hello"} 1943
telemt_user_unique_ips_current{user="hello"} 224
telemt_user_unique_ips_recent_window{user="hello"} 83
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 36718.3 (10h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1194026
telemt_connections_bad_total 88431
telemt_connections_current 3405
telemt_connections_me_current 3405
telemt_handshake_timeouts_total 31705
telemt_upstream_connect_attempt_total 16718
telemt_upstream_connect_success_total 16643
telemt_upstream_connect_fail_total 46
telemt_upstream_connect_attempts_per_request{bucket="1"} 16689
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8334
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8285
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 46
telemt_me_reconnect_attempts_total 580
telemt_me_reconnect_success_total 334
telemt_me_reader_eof_total 319
telemt_me_idle_close_by_peer_total 319
telemt_me_route_drop_no_conn_total 257228
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 929144
telemt_me_endpoint_quarantine_total 305
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 295
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 9
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
telemt_desync_total 3705
telemt_desync_full_logged_total 1236
telemt_desync_suppressed_total 2469
telemt_desync_frames_bucket_total{bucket="1_2"} 982
telemt_desync_frames_bucket_total{bucket="3_10"} 1398
telemt_desync_frames_bucket_total{bucket="gt_10"} 1325
telemt_pool_swap_total 40
telemt_pool_force_close_total 934
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 70
telemt_me_draining_writers_reap_progress_total 15088
telemt_me_writer_removed_unexpected_total 320
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1053
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14362
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 933
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14154
telemt_me_writer_teardown_success_total{mode="normal"} 15415
telemt_me_writer_teardown_noop_total 15088
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 30352
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 30459
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 30477
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 30503
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 30503
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 30503
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 30503
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 30503
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 30503
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 30503
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 30503
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 30503
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 30503
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.007444
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 30503
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 70
telemt_me_refill_failed_total 12
telemt_me_writer_restored_same_endpoint_total 306
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 10
telemt_user_connections_total{user="hello"} 924849
telemt_user_connections_current{user="hello"} 3405
telemt_user_octets_from_client{user="hello"} 14085721136 (13.12 GB)
telemt_user_octets_to_client{user="hello"} 419267326536 (390.47 GB)
telemt_user_unique_ips_current{user="hello"} 1212
telemt_user_unique_ips_recent_window{user="hello"} 392
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 36715.0 (10h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1138405
telemt_connections_bad_total 73505
telemt_connections_current 2650
telemt_connections_me_current 2650
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 29999
telemt_upstream_connect_attempt_total 25275
telemt_upstream_connect_success_total 25097
telemt_upstream_connect_fail_total 138
telemt_upstream_connect_attempts_per_request{bucket="1"} 25235
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16351
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8722
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 138
telemt_me_reconnect_attempts_total 2482
telemt_me_reconnect_success_total 459
telemt_me_reader_eof_total 397
telemt_me_idle_close_by_peer_total 397
telemt_me_seq_mismatch_total 24
telemt_me_route_drop_no_conn_total 263519
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 906088
telemt_me_endpoint_quarantine_total 372
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 295
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
telemt_desync_total 3520
telemt_desync_full_logged_total 1112
telemt_desync_suppressed_total 2408
telemt_desync_frames_bucket_total{bucket="1_2"} 1059
telemt_desync_frames_bucket_total{bucket="3_10"} 1288
telemt_desync_frames_bucket_total{bucket="gt_10"} 1173
telemt_pool_swap_total 40
telemt_pool_force_close_total 904
telemt_me_writer_close_signal_drop_total 76
telemt_me_draining_writers_reap_progress_total 14305
telemt_me_writer_removed_unexpected_total 409
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1256
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 13480
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 884
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 20
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13401
telemt_me_writer_teardown_success_total{mode="normal"} 14736
telemt_me_writer_teardown_noop_total 14305
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 28834
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 28947
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 29012
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 29041
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 29041
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 29041
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 29041
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 29041
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 29041
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 29041
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 29041
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 29041
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 29041
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.454659
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 29041
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 76
telemt_me_refill_failed_total 115
telemt_me_writer_restored_same_endpoint_total 340
telemt_me_writer_restored_fallback_total 28
telemt_me_async_recovery_trigger_total 39
telemt_me_writer_removed_unexpected_minus_restored_total 41
telemt_user_connections_total{user="hello"} 910744
telemt_user_connections_current{user="hello"} 2650
telemt_user_octets_from_client{user="hello"} 11659830723 (10.86 GB)
telemt_user_octets_to_client{user="hello"} 400935448459 (373.40 GB)
telemt_user_msgs_from_client{user="hello"} 40992
telemt_user_msgs_to_client{user="hello"} 110751
telemt_user_unique_ips_current{user="hello"} 1039
telemt_user_unique_ips_recent_window{user="hello"} 392
```