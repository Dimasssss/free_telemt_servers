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

# Server Metrics 2026-03-21 08:45:22 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 43769.9 (12h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1138548
telemt_connections_bad_total 57087
telemt_connections_current 1556
telemt_connections_me_current 1556
telemt_handshake_timeouts_total 49697
telemt_upstream_connect_attempt_total 17352
telemt_upstream_connect_success_total 17274
telemt_upstream_connect_fail_total 54
telemt_upstream_connect_attempts_per_request{bucket="1"} 17328
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6176
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11050
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 12
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 54
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 27
telemt_me_reconnect_attempts_total 723
telemt_me_reconnect_success_total 314
telemt_me_reader_eof_total 317
telemt_me_idle_close_by_peer_total 317
telemt_me_route_drop_no_conn_total 479727
telemt_me_route_drop_channel_closed_total 164
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 842304
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_endpoint_quarantine_total 311
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 354
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
telemt_desync_total 3623
telemt_desync_full_logged_total 1276
telemt_desync_suppressed_total 2347
telemt_desync_frames_bucket_total{bucket="1_2"} 760
telemt_desync_frames_bucket_total{bucket="3_10"} 1377
telemt_desync_frames_bucket_total{bucket="gt_10"} 1486
telemt_pool_swap_total 48
telemt_pool_force_close_total 1314
telemt_pool_stale_pick_total 5
telemt_me_writer_close_signal_drop_total 175
telemt_me_draining_writers_reap_progress_total 15504
telemt_me_writer_removed_unexpected_total 298
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1212
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14521
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1293
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 21
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14190
telemt_me_writer_teardown_success_total{mode="normal"} 15733
telemt_me_writer_teardown_noop_total 15505
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 28761
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 29382
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 29750
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 30365
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 30914
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 31153
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 31233
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 31238
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 31238
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 31238
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 31238
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 31238
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 31238
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 65.052202
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 31238
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 175
telemt_me_refill_failed_total 23
telemt_me_writer_restored_same_endpoint_total 274
telemt_me_writer_restored_fallback_total 3
telemt_me_async_recovery_trigger_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 21
telemt_user_connections_total{user="hello"} 841601
telemt_user_connections_current{user="hello"} 1556
telemt_user_octets_from_client{user="hello"} 12052787303 (11.23 GB)
telemt_user_octets_to_client{user="hello"} 243113331123 (226.42 GB)
telemt_user_msgs_from_client{user="hello"} 295
telemt_user_msgs_to_client{user="hello"} 249
telemt_user_unique_ips_current{user="hello"} 569
telemt_user_unique_ips_recent_window{user="hello"} 215
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 43771.3 (12h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2803642
telemt_connections_bad_total 318206
telemt_connections_current 4723
telemt_connections_me_current 4723
telemt_handshake_timeouts_total 78244
telemt_upstream_connect_attempt_total 15961
telemt_upstream_connect_success_total 15886
telemt_upstream_connect_fail_total 51
telemt_upstream_connect_attempts_per_request{bucket="1"} 15937
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6605
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9229
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 52
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 51
telemt_me_reconnect_attempts_total 948
telemt_me_reconnect_success_total 358
telemt_me_reader_eof_total 352
telemt_me_idle_close_by_peer_total 351
telemt_me_route_drop_no_conn_total 776254
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1808102
telemt_me_endpoint_quarantine_total 281
telemt_me_single_endpoint_outage_enter_total 4
telemt_me_single_endpoint_outage_exit_total 4
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 343
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
telemt_me_writers_active_current 45
telemt_desync_total 8071
telemt_desync_full_logged_total 2747
telemt_desync_suppressed_total 5324
telemt_desync_frames_bucket_total{bucket="1_2"} 1646
telemt_desync_frames_bucket_total{bucket="3_10"} 3159
telemt_desync_frames_bucket_total{bucket="gt_10"} 3266
telemt_pool_swap_total 47
telemt_pool_force_close_total 1414
telemt_me_writer_close_signal_drop_total 163
telemt_me_draining_writers_reap_progress_total 14289
telemt_me_writer_removed_unexpected_total 330
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1307
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 13307
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1335
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 79
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 12875
telemt_me_writer_teardown_success_total{mode="normal"} 14614
telemt_me_writer_teardown_noop_total 14289
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 27704
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 28213
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 28460
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 28796
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 28897
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 28903
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 28903
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 28903
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 28903
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 28903
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 28903
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 28903
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 28903
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 12.898676
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 28903
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 163
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 287
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 6
telemt_me_writer_removed_unexpected_minus_restored_total 37
telemt_user_connections_total{user="hello"} 1804578
telemt_user_connections_current{user="hello"} 4723
telemt_user_octets_from_client{user="hello"} 26666217140 (24.83 GB)
telemt_user_octets_to_client{user="hello"} 690544504840 (643.12 GB)
telemt_user_unique_ips_current{user="hello"} 1709
telemt_user_unique_ips_recent_window{user="hello"} 616
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 43767.5 (12h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2039365
telemt_connections_bad_total 252685
telemt_connections_current 4211
telemt_connections_me_current 4211
telemt_handshake_timeouts_total 75142
telemt_upstream_connect_attempt_total 17343
telemt_upstream_connect_success_total 17333
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 17334
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7858
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9425
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 575
telemt_me_reconnect_success_total 324
telemt_me_reader_eof_total 336
telemt_me_idle_close_by_peer_total 336
telemt_me_route_drop_no_conn_total 658109
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1572036
telemt_me_endpoint_quarantine_total 298
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 344
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
telemt_me_writers_active_current 45
telemt_desync_total 6569
telemt_desync_full_logged_total 2323
telemt_desync_suppressed_total 4246
telemt_desync_frames_bucket_total{bucket="1_2"} 1465
telemt_desync_frames_bucket_total{bucket="3_10"} 2545
telemt_desync_frames_bucket_total{bucket="gt_10"} 2559
telemt_pool_swap_total 47
telemt_pool_force_close_total 1383
telemt_pool_stale_pick_total 16
telemt_me_writer_close_signal_drop_total 175
telemt_me_draining_writers_reap_progress_total 15774
telemt_me_writer_removed_unexpected_total 316
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1282
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14711
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1309
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 74
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14391
telemt_me_writer_teardown_success_total{mode="normal"} 15993
telemt_me_writer_teardown_noop_total 15783
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 29954
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 30639
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 30997
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 31464
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 31673
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 31757
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 31776
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 31776
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 31776
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 31776
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 31776
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 31776
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 31776
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 28.400648
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 31776
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 175
telemt_me_refill_failed_total 12
telemt_me_writer_restored_same_endpoint_total 287
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 24
telemt_user_connections_total{user="hello"} 1569325
telemt_user_connections_current{user="hello"} 4211
telemt_user_octets_from_client{user="hello"} 22118654636 (20.60 GB)
telemt_user_octets_to_client{user="hello"} 643898058600 (599.68 GB)
telemt_user_unique_ips_current{user="hello"} 1507
telemt_user_unique_ips_recent_window{user="hello"} 565
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 43769.0 (12h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1713121
telemt_connections_bad_total 209787
telemt_connections_current 4076
telemt_connections_me_current 4076
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 68626
telemt_upstream_connect_attempt_total 22108
telemt_upstream_connect_success_total 21877
telemt_upstream_connect_fail_total 123
telemt_upstream_connect_attempts_per_request{bucket="1"} 22000
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11695
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9775
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 380
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 123
telemt_me_keepalive_timeout_total 16
telemt_me_reconnect_attempts_total 872
telemt_me_reconnect_success_total 397
telemt_me_reader_eof_total 372
telemt_me_idle_close_by_peer_total 372
telemt_me_route_drop_no_conn_total 483673
telemt_me_route_drop_channel_closed_total 36
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1179424
telemt_me_endpoint_quarantine_total 308
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 3
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 348
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
telemt_me_writers_active_current 88
telemt_desync_total 5586
telemt_desync_full_logged_total 1922
telemt_desync_suppressed_total 3664
telemt_desync_frames_bucket_total{bucket="1_2"} 1364
telemt_desync_frames_bucket_total{bucket="3_10"} 2250
telemt_desync_frames_bucket_total{bucket="gt_10"} 1972
telemt_pool_swap_total 47
telemt_pool_force_close_total 1237
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 76
telemt_me_draining_writers_reap_progress_total 15479
telemt_me_writer_removed_unexpected_total 365
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1228
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14630
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1195
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 42
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14242
telemt_me_writer_teardown_success_total{mode="normal"} 15858
telemt_me_writer_teardown_noop_total 15480
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 30833
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 31142
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 31213
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 31275
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 31318
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 31336
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 31338
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 31338
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 31338
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 31338
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 31338
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 31338
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 31338
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.397430
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 31338
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 76
telemt_me_refill_failed_total 25
telemt_me_writer_restored_same_endpoint_total 339
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 22
telemt_user_connections_total{user="hello"} 1181819
telemt_user_connections_current{user="hello"} 4076
telemt_user_octets_from_client{user="hello"} 21480510105 (20.01 GB)
telemt_user_octets_to_client{user="hello"} 569723695767 (530.60 GB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1537
telemt_user_unique_ips_recent_window{user="hello"} 464
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 43732.7 (12h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1649582
telemt_connections_bad_total 207499
telemt_connections_current 2729
telemt_connections_me_current 2729
telemt_handshake_timeouts_total 51692
telemt_upstream_connect_attempt_total 18206
telemt_upstream_connect_success_total 18191
telemt_upstream_connect_attempts_per_request{bucket="1"} 18191
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8124
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10043
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_me_reconnect_attempts_total 439
telemt_me_reconnect_success_total 318
telemt_me_reader_eof_total 319
telemt_me_idle_close_by_peer_total 319
telemt_me_route_drop_no_conn_total 419272
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1179696
telemt_me_endpoint_quarantine_total 342
telemt_me_single_endpoint_shadow_rotate_total 339
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
telemt_desync_total 5615
telemt_desync_full_logged_total 1983
telemt_desync_suppressed_total 3632
telemt_desync_frames_bucket_total{bucket="1_2"} 1456
telemt_desync_frames_bucket_total{bucket="3_10"} 2185
telemt_desync_frames_bucket_total{bucket="gt_10"} 1974
telemt_pool_swap_total 47
telemt_pool_force_close_total 1221
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 102
telemt_me_draining_writers_reap_progress_total 16443
telemt_me_writer_removed_unexpected_total 295
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1163
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15601
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1182
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 39
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15222
telemt_me_writer_teardown_success_total{mode="normal"} 16764
telemt_me_writer_teardown_noop_total 16446
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 32751
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 33065
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 33129
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 33197
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 33210
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 33210
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 33210
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 33210
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 33210
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 33210
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 33210
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 33210
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 33210
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.007612
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 33210
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 102
telemt_me_refill_failed_total 6
telemt_me_writer_restored_same_endpoint_total 286
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 8
telemt_user_connections_total{user="hello"} 1177707
telemt_user_connections_current{user="hello"} 2729
telemt_user_octets_from_client{user="hello"} 29600547316 (27.57 GB)
telemt_user_octets_to_client{user="hello"} 601912063128 (560.57 GB)
telemt_user_unique_ips_current{user="hello"} 1012
telemt_user_unique_ips_recent_window{user="hello"} 462
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 43772.0 (12h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4574037
telemt_connections_bad_total 256319
telemt_connections_current 5168
telemt_connections_me_current 5168
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 204207
telemt_upstream_connect_attempt_total 43759
telemt_upstream_connect_success_total 41774
telemt_upstream_connect_fail_total 1369
telemt_upstream_connect_attempts_per_request{bucket="1"} 43143
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29146
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11351
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1277
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1369
telemt_me_keepalive_timeout_total 31
telemt_me_reconnect_attempts_total 2242
telemt_me_reconnect_success_total 783
telemt_me_reader_eof_total 512
telemt_me_idle_close_by_peer_total 511
telemt_me_route_drop_no_conn_total 6892879
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3820019
telemt_me_endpoint_quarantine_total 353
telemt_me_single_endpoint_outage_enter_total 43
telemt_me_single_endpoint_outage_exit_total 43
telemt_me_single_endpoint_outage_reconnect_attempt_total 85
telemt_me_single_endpoint_outage_reconnect_success_total 20
telemt_me_single_endpoint_quarantine_bypass_total 85
telemt_me_single_endpoint_shadow_rotate_total 347
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
telemt_me_writers_active_current 46
telemt_desync_total 8078
telemt_desync_full_logged_total 2709
telemt_desync_suppressed_total 5369
telemt_desync_frames_bucket_total{bucket="1_2"} 1780
telemt_desync_frames_bucket_total{bucket="3_10"} 3489
telemt_desync_frames_bucket_total{bucket="gt_10"} 2809
telemt_pool_swap_total 46
telemt_pool_force_close_total 1353
telemt_me_writer_close_signal_drop_total 233
telemt_me_draining_writers_reap_progress_total 14750
telemt_me_writer_removed_unexpected_total 738
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1751
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 13692
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1228
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 125
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13397
telemt_me_writer_teardown_success_total{mode="normal"} 15443
telemt_me_writer_teardown_noop_total 14756
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 28130
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 28787
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 29294
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 29809
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 30091
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 30192
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 30199
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 30199
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 30199
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 30199
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 30199
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 30199
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 30199
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 31.234373
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 30199
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 233
telemt_me_refill_failed_total 57
telemt_me_writer_restored_same_endpoint_total 514
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 216
telemt_user_connections_total{user="hello"} 3842096
telemt_user_connections_current{user="hello"} 5168
telemt_user_octets_from_client{user="hello"} 42049538410 (39.16 GB)
telemt_user_octets_to_client{user="hello"} 533127811462 (496.51 GB)
telemt_user_msgs_from_client{user="hello"} 103363
telemt_user_msgs_to_client{user="hello"} 429893
telemt_user_unique_ips_current{user="hello"} 1806
telemt_user_unique_ips_recent_window{user="hello"} 951
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 43739.7 (12h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1707681
telemt_connections_bad_total 228682
telemt_connections_current 3430
telemt_connections_me_current 3430
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 33229
telemt_upstream_connect_attempt_total 19708
telemt_upstream_connect_success_total 19526
telemt_upstream_connect_fail_total 163
telemt_upstream_connect_attempts_per_request{bucket="1"} 19689
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9510
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9974
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 42
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 163
telemt_me_reconnect_attempts_total 1708
telemt_me_reconnect_success_total 543
telemt_me_reader_eof_total 557
telemt_me_idle_close_by_peer_total 557
telemt_me_route_drop_no_conn_total 459866
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1265578
telemt_me_endpoint_quarantine_total 269
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 347
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
telemt_me_writers_active_current 46
telemt_desync_total 5633
telemt_desync_full_logged_total 2083
telemt_desync_suppressed_total 3550
telemt_desync_frames_bucket_total{bucket="1_2"} 1083
telemt_desync_frames_bucket_total{bucket="3_10"} 2281
telemt_desync_frames_bucket_total{bucket="gt_10"} 2269
telemt_pool_swap_total 46
telemt_pool_force_close_total 1186
telemt_me_writer_close_signal_drop_total 77
telemt_me_draining_writers_reap_progress_total 16308
telemt_me_writer_removed_unexpected_total 535
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1414
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15451
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1116
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 70
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15122
telemt_me_writer_teardown_success_total{mode="normal"} 16865
telemt_me_writer_teardown_noop_total 16308
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 32926
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 33075
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 33173
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 33173
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 33173
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 33173
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 33173
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 33173
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 33173
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 33173
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 33173
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 33173
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 33173
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.265251
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 33173
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 77
telemt_me_refill_failed_total 64
telemt_me_writer_restored_same_endpoint_total 459
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 70
telemt_user_connections_total{user="hello"} 1262576
telemt_user_connections_current{user="hello"} 3430
telemt_user_octets_from_client{user="hello"} 22151011108 (20.63 GB)
telemt_user_octets_to_client{user="hello"} 591631165406 (551.00 GB)
telemt_user_msgs_from_client{user="hello"} 7339
telemt_user_msgs_to_client{user="hello"} 11522
telemt_user_unique_ips_current{user="hello"} 1300
telemt_user_unique_ips_recent_window{user="hello"} 480
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 43734.1 (12h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2254832
telemt_connections_bad_total 137343
telemt_connections_current 3288
telemt_connections_me_current 3288
telemt_handshake_timeouts_total 855643
telemt_upstream_connect_attempt_total 18567
telemt_upstream_connect_success_total 18533
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 18536
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8346
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9911
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 276
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 464
telemt_me_reconnect_success_total 284
telemt_me_reader_eof_total 285
telemt_me_idle_close_by_peer_total 285
telemt_me_route_drop_no_conn_total 420288
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1115159
telemt_me_endpoint_quarantine_total 352
telemt_me_single_endpoint_shadow_rotate_total 350
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
telemt_me_writers_active_current 46
telemt_desync_total 5557
telemt_desync_full_logged_total 1964
telemt_desync_suppressed_total 3593
telemt_desync_frames_bucket_total{bucket="1_2"} 963
telemt_desync_frames_bucket_total{bucket="3_10"} 2246
telemt_desync_frames_bucket_total{bucket="gt_10"} 2348
telemt_pool_swap_total 48
telemt_pool_force_close_total 1151
telemt_me_writer_close_signal_drop_total 82
telemt_me_draining_writers_reap_progress_total 16629
telemt_me_writer_removed_unexpected_total 275
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1040
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15883
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1134
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 17
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15478
telemt_me_writer_teardown_success_total{mode="normal"} 16923
telemt_me_writer_teardown_noop_total 16629
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 33437
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 33518
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 33552
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 33552
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 33552
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 33552
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 33552
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 33552
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 33552
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 33552
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 33552
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 33552
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 33552
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.672116
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 33552
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 82
telemt_me_refill_failed_total 9
telemt_me_writer_restored_same_endpoint_total 253
telemt_me_writer_restored_fallback_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 1111142
telemt_user_connections_current{user="hello"} 3288
telemt_user_octets_from_client{user="hello"} 19550227548 (18.21 GB)
telemt_user_octets_to_client{user="hello"} 562046269360 (523.45 GB)
telemt_user_unique_ips_current{user="hello"} 1237
telemt_user_unique_ips_recent_window{user="hello"} 465
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 41725.3 (11h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 472318
telemt_connections_bad_total 16763
telemt_connections_current 547
telemt_connections_me_current 547
telemt_handshake_timeouts_total 158316
telemt_upstream_connect_attempt_total 20665
telemt_upstream_connect_success_total 20663
telemt_upstream_connect_attempts_per_request{bucket="1"} 20663
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8640
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11978
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 45
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 773
telemt_me_reconnect_success_total 327
telemt_me_reader_eof_total 326
telemt_me_idle_close_by_peer_total 326
telemt_me_route_drop_no_conn_total 104870
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 263604
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
telemt_desync_total 1691
telemt_desync_full_logged_total 694
telemt_desync_suppressed_total 997
telemt_desync_frames_bucket_total{bucket="1_2"} 339
telemt_desync_frames_bucket_total{bucket="3_10"} 695
telemt_desync_frames_bucket_total{bucket="gt_10"} 657
telemt_pool_swap_total 46
telemt_pool_force_close_total 984
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 59
telemt_me_draining_writers_reap_progress_total 18471
telemt_me_writer_removed_unexpected_total 308
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1315
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17467
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 982
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17487
telemt_me_writer_teardown_success_total{mode="normal"} 18782
telemt_me_writer_teardown_noop_total 18471
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 36965
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 37197
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 37244
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 37253
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 37253
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 37253
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 37253
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 37253
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 37253
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 37253
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 37253
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 37253
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 37253
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.515423
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 37253
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 59
telemt_me_refill_failed_total 23
telemt_me_writer_restored_same_endpoint_total 270
telemt_me_writer_restored_fallback_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 34
telemt_user_connections_total{user="hello"} 263782
telemt_user_connections_current{user="hello"} 547
telemt_user_octets_from_client{user="hello"} 3782263331 (3.52 GB)
telemt_user_octets_to_client{user="hello"} 106490533613 (99.18 GB)
telemt_user_msgs_from_client{user="hello"} 804
telemt_user_msgs_to_client{user="hello"} 1943
telemt_user_unique_ips_current{user="hello"} 254
telemt_user_unique_ips_recent_window{user="hello"} 107
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 43743.9 (12h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1749047
telemt_connections_bad_total 154007
telemt_connections_current 3688
telemt_connections_me_current 3688
telemt_handshake_timeouts_total 44790
telemt_upstream_connect_attempt_total 19199
telemt_upstream_connect_success_total 19114
telemt_upstream_connect_fail_total 56
telemt_upstream_connect_attempts_per_request{bucket="1"} 19170
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9592
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9498
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 56
telemt_me_reconnect_attempts_total 688
telemt_me_reconnect_success_total 411
telemt_me_reader_eof_total 378
telemt_me_idle_close_by_peer_total 378
telemt_me_route_drop_no_conn_total 417044
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1373954
telemt_me_endpoint_quarantine_total 350
telemt_me_single_endpoint_outage_enter_total 4
telemt_me_single_endpoint_outage_exit_total 4
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 350
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
telemt_me_writers_active_current 45
telemt_desync_total 5527
telemt_desync_full_logged_total 1856
telemt_desync_suppressed_total 3671
telemt_desync_frames_bucket_total{bucket="1_2"} 1347
telemt_desync_frames_bucket_total{bucket="3_10"} 2071
telemt_desync_frames_bucket_total{bucket="gt_10"} 2109
telemt_pool_swap_total 48
telemt_pool_force_close_total 1170
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 105
telemt_me_draining_writers_reap_progress_total 17304
telemt_me_writer_removed_unexpected_total 377
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1269
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16421
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1148
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 22
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16134
telemt_me_writer_teardown_success_total{mode="normal"} 17690
telemt_me_writer_teardown_noop_total 17304
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 34712
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 34880
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 34921
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 34994
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 34994
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 34994
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 34994
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 34994
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 34994
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 34994
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 34994
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 34994
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 34994
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.210162
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 34994
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 105
telemt_me_refill_failed_total 14
telemt_me_writer_restored_same_endpoint_total 368
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 4
telemt_user_connections_total{user="hello"} 1368765
telemt_user_connections_current{user="hello"} 3688
telemt_user_octets_from_client{user="hello"} 30877657824 (28.76 GB)
telemt_user_octets_to_client{user="hello"} 637523915652 (593.74 GB)
telemt_user_unique_ips_current{user="hello"} 1362
telemt_user_unique_ips_recent_window{user="hello"} 513
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 43740.9 (12h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1672631
telemt_connections_bad_total 140729
telemt_connections_current 3468
telemt_connections_me_current 3468
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 41236
telemt_upstream_connect_attempt_total 27636
telemt_upstream_connect_success_total 27441
telemt_upstream_connect_fail_total 154
telemt_upstream_connect_attempts_per_request{bucket="1"} 27595
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17504
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9907
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 154
telemt_me_reconnect_attempts_total 2786
telemt_me_reconnect_success_total 540
telemt_me_reader_eof_total 460
telemt_me_idle_close_by_peer_total 460
telemt_me_seq_mismatch_total 24
telemt_me_route_drop_no_conn_total 424345
telemt_me_route_drop_channel_closed_total 22
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1328809
telemt_me_endpoint_quarantine_total 406
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
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
telemt_me_writers_active_current 45
telemt_desync_total 5207
telemt_desync_full_logged_total 1706
telemt_desync_suppressed_total 3501
telemt_desync_frames_bucket_total{bucket="1_2"} 1435
telemt_desync_frames_bucket_total{bucket="3_10"} 1911
telemt_desync_frames_bucket_total{bucket="gt_10"} 1861
telemt_pool_swap_total 48
telemt_pool_force_close_total 1146
telemt_me_writer_close_signal_drop_total 98
telemt_me_draining_writers_reap_progress_total 16411
telemt_me_writer_removed_unexpected_total 469
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1476
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15429
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1095
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 51
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15265
telemt_me_writer_teardown_success_total{mode="normal"} 16905
telemt_me_writer_teardown_noop_total 16412
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 32959
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 33154
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 33266
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 33314
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 33317
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 33317
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 33317
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 33317
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 33317
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 33317
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 33317
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 33317
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 33317
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.576779
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 33317
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 98
telemt_me_refill_failed_total 127
telemt_me_writer_restored_same_endpoint_total 408
telemt_me_writer_restored_fallback_total 28
telemt_me_async_recovery_trigger_total 45
telemt_me_writer_removed_unexpected_minus_restored_total 33
telemt_user_connections_total{user="hello"} 1332859
telemt_user_connections_current{user="hello"} 3468
telemt_user_octets_from_client{user="hello"} 20408776263 (19.01 GB)
telemt_user_octets_to_client{user="hello"} 593760768123 (552.98 GB)
telemt_user_msgs_from_client{user="hello"} 40992
telemt_user_msgs_to_client{user="hello"} 110751
telemt_user_unique_ips_current{user="hello"} 1263
telemt_user_unique_ips_recent_window{user="hello"} 471
```