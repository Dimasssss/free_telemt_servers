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

# Server Metrics 2026-03-21 08:55:34 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 44378.7 (12h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1161864
telemt_connections_bad_total 58127
telemt_connections_current 1536
telemt_connections_me_current 1536
telemt_handshake_timeouts_total 50391
telemt_upstream_connect_attempt_total 17571
telemt_upstream_connect_success_total 17490
telemt_upstream_connect_fail_total 57
telemt_upstream_connect_attempts_per_request{bucket="1"} 17547
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6267
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11174
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 12
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 57
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 27
telemt_me_reconnect_attempts_total 755
telemt_me_reconnect_success_total 314
telemt_me_reader_eof_total 320
telemt_me_idle_close_by_peer_total 320
telemt_me_route_drop_no_conn_total 487388
telemt_me_route_drop_channel_closed_total 169
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 862476
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_endpoint_quarantine_total 317
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 360
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
telemt_me_writers_active_current 43
telemt_desync_total 3715
telemt_desync_full_logged_total 1311
telemt_desync_suppressed_total 2404
telemt_desync_frames_bucket_total{bucket="1_2"} 777
telemt_desync_frames_bucket_total{bucket="3_10"} 1417
telemt_desync_frames_bucket_total{bucket="gt_10"} 1521
telemt_pool_swap_total 49
telemt_pool_force_close_total 1343
telemt_pool_stale_pick_total 5
telemt_me_writer_close_signal_drop_total 176
telemt_me_draining_writers_reap_progress_total 15713
telemt_me_writer_removed_unexpected_total 300
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1232
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14713
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1322
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 21
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14370
telemt_me_writer_teardown_success_total{mode="normal"} 15945
telemt_me_writer_teardown_noop_total 15714
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 29148
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 29781
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 30155
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 30784
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 31335
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 31574
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 31654
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 31659
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 31659
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 31659
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 31659
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 31659
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 31659
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 65.444559
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 31659
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 176
telemt_me_refill_failed_total 25
telemt_me_writer_restored_same_endpoint_total 274
telemt_me_writer_restored_fallback_total 3
telemt_me_async_recovery_trigger_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 23
telemt_user_connections_total{user="hello"} 861785
telemt_user_connections_current{user="hello"} 1536
telemt_user_octets_from_client{user="hello"} 12633310895 (11.77 GB)
telemt_user_octets_to_client{user="hello"} 250032251299 (232.86 GB)
telemt_user_msgs_from_client{user="hello"} 295
telemt_user_msgs_to_client{user="hello"} 249
telemt_user_unique_ips_current{user="hello"} 539
telemt_user_unique_ips_recent_window{user="hello"} 245
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 44380.3 (12h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2884670
telemt_connections_bad_total 331904
telemt_connections_current 4367
telemt_connections_me_current 4367
telemt_handshake_timeouts_total 85369
telemt_upstream_connect_attempt_total 16166
telemt_upstream_connect_success_total 16091
telemt_upstream_connect_fail_total 51
telemt_upstream_connect_attempts_per_request{bucket="1"} 16142
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6688
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9350
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 51
telemt_me_reconnect_attempts_total 968
telemt_me_reconnect_success_total 362
telemt_me_reader_eof_total 357
telemt_me_idle_close_by_peer_total 356
telemt_me_route_drop_no_conn_total 820316
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1866236
telemt_me_endpoint_quarantine_total 290
telemt_me_single_endpoint_outage_enter_total 4
telemt_me_single_endpoint_outage_exit_total 4
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 347
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
telemt_me_writers_active_current 42
telemt_desync_total 8338
telemt_desync_full_logged_total 2832
telemt_desync_suppressed_total 5506
telemt_desync_frames_bucket_total{bucket="1_2"} 1692
telemt_desync_frames_bucket_total{bucket="3_10"} 3254
telemt_desync_frames_bucket_total{bucket="gt_10"} 3392
telemt_pool_swap_total 48
telemt_pool_force_close_total 1448
telemt_me_writer_close_signal_drop_total 170
telemt_me_draining_writers_reap_progress_total 14475
telemt_me_writer_removed_unexpected_total 334
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1331
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 13474
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1366
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 82
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13027
telemt_me_writer_teardown_success_total{mode="normal"} 14805
telemt_me_writer_teardown_noop_total 14475
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 28015
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 28539
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 28801
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 29159
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 29274
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 29280
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 29280
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 29280
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 29280
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 29280
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 29280
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 29280
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 29280
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 13.938916
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 29280
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 170
telemt_me_refill_failed_total 34
telemt_me_writer_restored_same_endpoint_total 290
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 6
telemt_me_writer_removed_unexpected_minus_restored_total 38
telemt_user_connections_total{user="hello"} 1862644
telemt_user_connections_current{user="hello"} 4367
telemt_user_octets_from_client{user="hello"} 27624762724 (25.73 GB)
telemt_user_octets_to_client{user="hello"} 707020223360 (658.46 GB)
telemt_user_unique_ips_current{user="hello"} 1596
telemt_user_unique_ips_recent_window{user="hello"} 621
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 44376.7 (12h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2103248
telemt_connections_bad_total 255397
telemt_connections_current 3782
telemt_connections_me_current 3782
telemt_handshake_timeouts_total 75659
telemt_upstream_connect_attempt_total 17556
telemt_upstream_connect_success_total 17546
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 17547
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7958
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9538
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 581
telemt_me_reconnect_success_total 330
telemt_me_reader_eof_total 342
telemt_me_idle_close_by_peer_total 342
telemt_me_route_drop_no_conn_total 699930
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1627753
telemt_me_endpoint_quarantine_total 300
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 351
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 15
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
telemt_desync_total 6884
telemt_desync_full_logged_total 2405
telemt_desync_suppressed_total 4479
telemt_desync_frames_bucket_total{bucket="1_2"} 1506
telemt_desync_frames_bucket_total{bucket="3_10"} 2689
telemt_desync_frames_bucket_total{bucket="gt_10"} 2689
telemt_pool_swap_total 48
telemt_pool_force_close_total 1415
telemt_pool_stale_pick_total 16
telemt_me_writer_close_signal_drop_total 177
telemt_me_draining_writers_reap_progress_total 15975
telemt_me_writer_removed_unexpected_total 322
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1301
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14893
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1341
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 74
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14560
telemt_me_writer_teardown_success_total{mode="normal"} 16194
telemt_me_writer_teardown_noop_total 15985
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 30299
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 30989
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 31350
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 31828
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 32066
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 32156
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 32179
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 32179
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 32179
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 32179
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 32179
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 32179
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 32179
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 30.608090
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 32179
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 177
telemt_me_refill_failed_total 12
telemt_me_writer_restored_same_endpoint_total 293
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 24
telemt_user_connections_total{user="hello"} 1624971
telemt_user_connections_current{user="hello"} 3782
telemt_user_octets_from_client{user="hello"} 22986561196 (21.41 GB)
telemt_user_octets_to_client{user="hello"} 658517554048 (613.29 GB)
telemt_user_unique_ips_current{user="hello"} 1408
telemt_user_unique_ips_recent_window{user="hello"} 575
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 44378.0 (12h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1767821
telemt_connections_bad_total 213458
telemt_connections_current 3375
telemt_connections_me_current 3375
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 71372
telemt_upstream_connect_attempt_total 22450
telemt_upstream_connect_success_total 22219
telemt_upstream_connect_fail_total 123
telemt_upstream_connect_attempts_per_request{bucket="1"} 22342
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11854
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9957
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 381
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 123
telemt_me_keepalive_timeout_total 16
telemt_me_reconnect_attempts_total 910
telemt_me_reconnect_success_total 414
telemt_me_reader_eof_total 384
telemt_me_idle_close_by_peer_total 384
telemt_me_route_drop_no_conn_total 498553
telemt_me_route_drop_channel_closed_total 36
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1218089
telemt_me_endpoint_quarantine_total 319
telemt_me_single_endpoint_outage_enter_total 4
telemt_me_single_endpoint_outage_exit_total 4
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 353
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
telemt_me_writers_active_current 47
telemt_desync_total 5718
telemt_desync_full_logged_total 1975
telemt_desync_suppressed_total 3743
telemt_desync_frames_bucket_total{bucket="1_2"} 1397
telemt_desync_frames_bucket_total{bucket="3_10"} 2296
telemt_desync_frames_bucket_total{bucket="gt_10"} 2025
telemt_pool_swap_total 48
telemt_pool_force_close_total 1295
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 85
telemt_me_draining_writers_reap_progress_total 15830
telemt_me_writer_removed_unexpected_total 377
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1265
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14956
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1222
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 73
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14535
telemt_me_writer_teardown_success_total{mode="normal"} 16221
telemt_me_writer_teardown_noop_total 15831
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 31494
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 31846
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 31923
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 31989
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 32032
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 32050
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 32052
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 32052
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 32052
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 32052
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 32052
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 32052
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 32052
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.652469
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 32052
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 85
telemt_me_refill_failed_total 26
telemt_me_writer_restored_same_endpoint_total 350
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 23
telemt_user_connections_total{user="hello"} 1220348
telemt_user_connections_current{user="hello"} 3375
telemt_user_octets_from_client{user="hello"} 24201148129 (22.54 GB)
telemt_user_octets_to_client{user="hello"} 588397295231 (547.99 GB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1203
telemt_user_unique_ips_recent_window{user="hello"} 527
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 44345.1 (12h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1692899
telemt_connections_bad_total 209196
telemt_connections_current 2553
telemt_connections_me_current 2553
telemt_handshake_timeouts_total 52496
telemt_upstream_connect_attempt_total 18441
telemt_upstream_connect_success_total 18425
telemt_upstream_connect_attempts_per_request{bucket="1"} 18425
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8242
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10154
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_me_reconnect_attempts_total 466
telemt_me_reconnect_success_total 355
telemt_me_reader_eof_total 340
telemt_me_idle_close_by_peer_total 340
telemt_me_route_drop_no_conn_total 435317
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1217351
telemt_me_endpoint_quarantine_total 350
telemt_me_single_endpoint_shadow_rotate_total 346
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
telemt_me_writers_active_current 50
telemt_desync_total 5775
telemt_desync_full_logged_total 2022
telemt_desync_suppressed_total 3753
telemt_desync_frames_bucket_total{bucket="1_2"} 1495
telemt_desync_frames_bucket_total{bucket="3_10"} 2248
telemt_desync_frames_bucket_total{bucket="gt_10"} 2032
telemt_pool_swap_total 48
telemt_pool_force_close_total 1255
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 107
telemt_me_draining_writers_reap_progress_total 16630
telemt_me_writer_removed_unexpected_total 314
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1209
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15763
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1206
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 49
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15375
telemt_me_writer_teardown_success_total{mode="normal"} 16972
telemt_me_writer_teardown_noop_total 16633
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 33111
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 33438
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 33508
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 33586
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 33605
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 33605
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 33605
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 33605
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 33605
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 33605
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 33605
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 33605
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 33605
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.398438
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 33605
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 107
telemt_me_refill_failed_total 6
telemt_me_writer_restored_same_endpoint_total 312
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 6
telemt_user_connections_total{user="hello"} 1215193
telemt_user_connections_current{user="hello"} 2553
telemt_user_octets_from_client{user="hello"} 30180027868 (28.11 GB)
telemt_user_octets_to_client{user="hello"} 616785918952 (574.43 GB)
telemt_user_unique_ips_current{user="hello"} 1028
telemt_user_unique_ips_recent_window{user="hello"} 624
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 44381.3 (12h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4738007
telemt_connections_bad_total 263946
telemt_connections_current 5073
telemt_connections_me_current 5073
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 208312
telemt_upstream_connect_attempt_total 44016
telemt_upstream_connect_success_total 42024
telemt_upstream_connect_fail_total 1375
telemt_upstream_connect_attempts_per_request{bucket="1"} 43399
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29260
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11485
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1279
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1375
telemt_me_keepalive_timeout_total 31
telemt_me_reconnect_attempts_total 2290
telemt_me_reconnect_success_total 826
telemt_me_reader_eof_total 556
telemt_me_idle_close_by_peer_total 555
telemt_me_route_drop_no_conn_total 7242372
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3964255
telemt_me_endpoint_quarantine_total 353
telemt_me_single_endpoint_outage_enter_total 43
telemt_me_single_endpoint_outage_exit_total 43
telemt_me_single_endpoint_outage_reconnect_attempt_total 85
telemt_me_single_endpoint_outage_reconnect_success_total 20
telemt_me_single_endpoint_quarantine_bypass_total 85
telemt_me_single_endpoint_shadow_rotate_total 351
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 25
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
telemt_me_writers_active_current 89
telemt_desync_total 8409
telemt_desync_full_logged_total 2837
telemt_desync_suppressed_total 5572
telemt_desync_frames_bucket_total{bucket="1_2"} 1869
telemt_desync_frames_bucket_total{bucket="3_10"} 3620
telemt_desync_frames_bucket_total{bucket="gt_10"} 2920
telemt_pool_swap_total 46
telemt_pool_force_close_total 1353
telemt_me_writer_close_signal_drop_total 233
telemt_me_draining_writers_reap_progress_total 14895
telemt_me_writer_removed_unexpected_total 782
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1803
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 13829
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1228
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 125
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13542
telemt_me_writer_teardown_success_total{mode="normal"} 15632
telemt_me_writer_teardown_noop_total 14901
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 28451
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 29121
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 29628
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 30143
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 30425
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 30526
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 30533
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 30533
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 30533
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 30533
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 30533
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 30533
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 30533
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 31.270122
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 30533
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 233
telemt_me_refill_failed_total 57
telemt_me_writer_restored_same_endpoint_total 557
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 217
telemt_user_connections_total{user="hello"} 3986332
telemt_user_connections_current{user="hello"} 5073
telemt_user_octets_from_client{user="hello"} 43099730854 (40.14 GB)
telemt_user_octets_to_client{user="hello"} 539886209090 (502.81 GB)
telemt_user_msgs_from_client{user="hello"} 103363
telemt_user_msgs_to_client{user="hello"} 429893
telemt_user_unique_ips_current{user="hello"} 1824
telemt_user_unique_ips_recent_window{user="hello"} 898
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 44348.7 (12h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1762644
telemt_connections_bad_total 233150
telemt_connections_current 3051
telemt_connections_me_current 3051
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 34282
telemt_upstream_connect_attempt_total 19918
telemt_upstream_connect_success_total 19732
telemt_upstream_connect_fail_total 167
telemt_upstream_connect_attempts_per_request{bucket="1"} 19899
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9606
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10084
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 42
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 167
telemt_me_reconnect_attempts_total 1786
telemt_me_reconnect_success_total 547
telemt_me_reader_eof_total 562
telemt_me_idle_close_by_peer_total 562
telemt_me_route_drop_no_conn_total 483448
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1303324
telemt_me_endpoint_quarantine_total 273
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 350
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
telemt_me_writers_active_current 43
telemt_desync_total 5890
telemt_desync_full_logged_total 2152
telemt_desync_suppressed_total 3738
telemt_desync_frames_bucket_total{bucket="1_2"} 1141
telemt_desync_frames_bucket_total{bucket="3_10"} 2396
telemt_desync_frames_bucket_total{bucket="gt_10"} 2353
telemt_pool_swap_total 47
telemt_pool_force_close_total 1217
telemt_me_writer_close_signal_drop_total 82
telemt_me_draining_writers_reap_progress_total 16491
telemt_me_writer_removed_unexpected_total 540
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1438
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15615
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1143
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 74
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15274
telemt_me_writer_teardown_success_total{mode="normal"} 17053
telemt_me_writer_teardown_noop_total 16491
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 33274
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 33433
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 33535
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 33544
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 33544
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 33544
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 33544
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 33544
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 33544
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 33544
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 33544
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 33544
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 33544
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.458807
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 33544
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 82
telemt_me_refill_failed_total 68
telemt_me_writer_restored_same_endpoint_total 459
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 75
telemt_user_connections_total{user="hello"} 1300165
telemt_user_connections_current{user="hello"} 3051
telemt_user_octets_from_client{user="hello"} 22740033640 (21.18 GB)
telemt_user_octets_to_client{user="hello"} 608541705690 (566.75 GB)
telemt_user_msgs_from_client{user="hello"} 7339
telemt_user_msgs_to_client{user="hello"} 11522
telemt_user_unique_ips_current{user="hello"} 1165
telemt_user_unique_ips_recent_window{user="hello"} 494
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 44343.2 (12h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2339635
telemt_connections_bad_total 142217
telemt_connections_current 3040
telemt_connections_me_current 3040
telemt_handshake_timeouts_total 898426
telemt_upstream_connect_attempt_total 18795
telemt_upstream_connect_success_total 18761
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 18764
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8448
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10036
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 277
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 466
telemt_me_reconnect_success_total 285
telemt_me_reader_eof_total 286
telemt_me_idle_close_by_peer_total 286
telemt_me_route_drop_no_conn_total 437091
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1149778
telemt_me_endpoint_quarantine_total 355
telemt_me_single_endpoint_shadow_rotate_total 354
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
telemt_desync_total 5664
telemt_desync_full_logged_total 2003
telemt_desync_suppressed_total 3661
telemt_desync_frames_bucket_total{bucket="1_2"} 986
telemt_desync_frames_bucket_total{bucket="3_10"} 2278
telemt_desync_frames_bucket_total{bucket="gt_10"} 2400
telemt_pool_swap_total 49
telemt_pool_force_close_total 1180
telemt_me_writer_close_signal_drop_total 87
telemt_me_draining_writers_reap_progress_total 16841
telemt_me_writer_removed_unexpected_total 276
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1054
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16082
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1163
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 17
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15661
telemt_me_writer_teardown_success_total{mode="normal"} 17136
telemt_me_writer_teardown_noop_total 16841
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 33848
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 33935
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 33970
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 33977
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 33977
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 33977
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 33977
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 33977
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 33977
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 33977
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 33977
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 33977
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 33977
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.773824
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 33977
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 87
telemt_me_refill_failed_total 9
telemt_me_writer_restored_same_endpoint_total 254
telemt_me_writer_restored_fallback_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 1145733
telemt_user_connections_current{user="hello"} 3040
telemt_user_octets_from_client{user="hello"} 20025025640 (18.65 GB)
telemt_user_octets_to_client{user="hello"} 577397474432 (537.74 GB)
telemt_user_unique_ips_current{user="hello"} 1143
telemt_user_unique_ips_recent_window{user="hello"} 447
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 42334.6 (11h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 493597
telemt_connections_bad_total 18797
telemt_connections_current 646
telemt_connections_me_current 646
telemt_handshake_timeouts_total 167802
telemt_upstream_connect_attempt_total 20877
telemt_upstream_connect_success_total 20875
telemt_upstream_connect_attempts_per_request{bucket="1"} 20875
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8709
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12120
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 775
telemt_me_reconnect_success_total 329
telemt_me_reader_eof_total 328
telemt_me_idle_close_by_peer_total 328
telemt_me_route_drop_no_conn_total 108219
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 270580
telemt_me_endpoint_quarantine_total 408
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 362
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 7
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
telemt_me_writers_warm_current 7
telemt_desync_total 1698
telemt_desync_full_logged_total 697
telemt_desync_suppressed_total 1001
telemt_desync_frames_bucket_total{bucket="1_2"} 339
telemt_desync_frames_bucket_total{bucket="3_10"} 697
telemt_desync_frames_bucket_total{bucket="gt_10"} 662
telemt_pool_swap_total 46
telemt_pool_force_close_total 984
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 59
telemt_me_draining_writers_reap_progress_total 18649
telemt_me_writer_removed_unexpected_total 310
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1321
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17641
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 982
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17665
telemt_me_writer_teardown_success_total{mode="normal"} 18962
telemt_me_writer_teardown_noop_total 18649
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 37323
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 37555
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 37602
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 37611
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 37611
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 37611
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 37611
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 37611
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 37611
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 37611
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 37611
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 37611
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 37611
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.520883
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 37611
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 59
telemt_me_refill_failed_total 23
telemt_me_writer_restored_same_endpoint_total 272
telemt_me_writer_restored_fallback_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 34
telemt_user_connections_total{user="hello"} 270760
telemt_user_connections_current{user="hello"} 646
telemt_user_octets_from_client{user="hello"} 3872978151 (3.61 GB)
telemt_user_octets_to_client{user="hello"} 107972038481 (100.56 GB)
telemt_user_msgs_from_client{user="hello"} 804
telemt_user_msgs_to_client{user="hello"} 1943
telemt_user_unique_ips_current{user="hello"} 260
telemt_user_unique_ips_recent_window{user="hello"} 115
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 44353.1 (12h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1798746
telemt_connections_bad_total 157738
telemt_connections_current 3846
telemt_connections_me_current 3846
telemt_handshake_timeouts_total 46122
telemt_upstream_connect_attempt_total 19453
telemt_upstream_connect_success_total 19367
telemt_upstream_connect_fail_total 57
telemt_upstream_connect_attempts_per_request{bucket="1"} 19424
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9723
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9619
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 57
telemt_me_reconnect_attempts_total 728
telemt_me_reconnect_success_total 419
telemt_me_reader_eof_total 387
telemt_me_idle_close_by_peer_total 387
telemt_me_route_drop_no_conn_total 430660
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1415338
telemt_me_endpoint_quarantine_total 356
telemt_me_single_endpoint_outage_enter_total 4
telemt_me_single_endpoint_outage_exit_total 4
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 355
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 15
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
telemt_desync_total 5685
telemt_desync_full_logged_total 1906
telemt_desync_suppressed_total 3779
telemt_desync_frames_bucket_total{bucket="1_2"} 1385
telemt_desync_frames_bucket_total{bucket="3_10"} 2146
telemt_desync_frames_bucket_total{bucket="gt_10"} 2154
telemt_pool_swap_total 49
telemt_pool_force_close_total 1195
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 107
telemt_me_draining_writers_reap_progress_total 17528
telemt_me_writer_removed_unexpected_total 386
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1290
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16633
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1173
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 22
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16333
telemt_me_writer_teardown_success_total{mode="normal"} 17923
telemt_me_writer_teardown_noop_total 17528
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 35162
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 35337
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 35378
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 35451
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 35451
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 35451
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 35451
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 35451
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 35451
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 35451
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 35451
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 35451
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 35451
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.236066
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 35451
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 107
telemt_me_refill_failed_total 16
telemt_me_writer_restored_same_endpoint_total 375
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 1410083
telemt_user_connections_current{user="hello"} 3846
telemt_user_octets_from_client{user="hello"} 31611146040 (29.44 GB)
telemt_user_octets_to_client{user="hello"} 655327727920 (610.32 GB)
telemt_user_unique_ips_current{user="hello"} 1297
telemt_user_unique_ips_recent_window{user="hello"} 568
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 44349.9 (12h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1718662
telemt_connections_bad_total 143525
telemt_connections_current 3369
telemt_connections_me_current 3369
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 42688
telemt_upstream_connect_attempt_total 27858
telemt_upstream_connect_success_total 27658
telemt_upstream_connect_fail_total 159
telemt_upstream_connect_attempts_per_request{bucket="1"} 27817
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17609
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10019
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 159
telemt_me_reconnect_attempts_total 2795
telemt_me_reconnect_success_total 550
telemt_me_reader_eof_total 469
telemt_me_idle_close_by_peer_total 469
telemt_me_seq_mismatch_total 24
telemt_me_route_drop_no_conn_total 440032
telemt_me_route_drop_channel_closed_total 24
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1368285
telemt_me_endpoint_quarantine_total 409
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 351
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
telemt_me_writers_active_current 47
telemt_desync_total 5340
telemt_desync_full_logged_total 1764
telemt_desync_suppressed_total 3576
telemt_desync_frames_bucket_total{bucket="1_2"} 1482
telemt_desync_frames_bucket_total{bucket="3_10"} 1961
telemt_desync_frames_bucket_total{bucket="gt_10"} 1897
telemt_pool_swap_total 49
telemt_pool_force_close_total 1177
telemt_me_writer_close_signal_drop_total 99
telemt_me_draining_writers_reap_progress_total 16597
telemt_me_writer_removed_unexpected_total 478
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1503
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15597
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1124
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 53
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15420
telemt_me_writer_teardown_success_total{mode="normal"} 17100
telemt_me_writer_teardown_noop_total 16598
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 33315
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 33516
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 33630
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 33695
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 33698
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 33698
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 33698
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 33698
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 33698
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 33698
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 33698
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 33698
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 33698
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.960991
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 33698
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 99
telemt_me_refill_failed_total 127
telemt_me_writer_restored_same_endpoint_total 415
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 45
telemt_me_writer_removed_unexpected_minus_restored_total 33
telemt_user_connections_total{user="hello"} 1372300
telemt_user_connections_current{user="hello"} 3369
telemt_user_octets_from_client{user="hello"} 20991909015 (19.55 GB)
telemt_user_octets_to_client{user="hello"} 611315195243 (569.33 GB)
telemt_user_msgs_from_client{user="hello"} 40992
telemt_user_msgs_to_client{user="hello"} 110751
telemt_user_unique_ips_current{user="hello"} 1205
telemt_user_unique_ips_recent_window{user="hello"} 492
```