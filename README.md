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

# Server Metrics 2026-03-21 10:27:23 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 49890.6 (13h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1442072
telemt_connections_bad_total 74419
telemt_connections_current 1542
telemt_connections_me_current 1542
telemt_handshake_timeouts_total 58206
telemt_upstream_connect_attempt_total 19670
telemt_upstream_connect_success_total 19583
telemt_upstream_connect_fail_total 63
telemt_upstream_connect_attempts_per_request{bucket="1"} 19646
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7038
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12494
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 14
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 63
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 55
telemt_me_reconnect_attempts_total 927
telemt_me_reconnect_success_total 401
telemt_me_reader_eof_total 404
telemt_me_idle_close_by_peer_total 404
telemt_me_route_drop_no_conn_total 778577
telemt_me_route_drop_channel_closed_total 296
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1097152
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_endpoint_quarantine_total 349
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 401
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
telemt_me_writers_active_current 50
telemt_desync_total 4623
telemt_desync_full_logged_total 1609
telemt_desync_suppressed_total 3014
telemt_desync_frames_bucket_total{bucket="1_2"} 966
telemt_desync_frames_bucket_total{bucket="3_10"} 1786
telemt_desync_frames_bucket_total{bucket="gt_10"} 1871
telemt_pool_swap_total 54
telemt_pool_force_close_total 1541
telemt_pool_stale_pick_total 12
telemt_me_writer_close_signal_drop_total 247
telemt_me_draining_writers_reap_progress_total 17606
telemt_me_writer_removed_unexpected_total 382
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1416
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16468
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1485
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 56
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16065
telemt_me_writer_teardown_success_total{mode="normal"} 17884
telemt_me_writer_teardown_noop_total 17608
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 31742
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 32570
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 33186
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 34231
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 35043
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 35369
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 35485
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 35492
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 35492
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 35492
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 35492
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 35492
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 35492
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 95.269248
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 35492
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 247
telemt_me_refill_failed_total 30
telemt_me_writer_restored_same_endpoint_total 356
telemt_me_writer_restored_fallback_total 3
telemt_me_async_recovery_trigger_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 23
telemt_user_connections_total{user="hello"} 1096289
telemt_user_connections_current{user="hello"} 1542
telemt_user_octets_from_client{user="hello"} 15386321763 (14.33 GB)
telemt_user_octets_to_client{user="hello"} 312060831159 (290.63 GB)
telemt_user_msgs_from_client{user="hello"} 295
telemt_user_msgs_to_client{user="hello"} 249
telemt_user_unique_ips_current{user="hello"} 560
telemt_user_unique_ips_recent_window{user="hello"} 251
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 49891.8 (13h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3686393
telemt_connections_bad_total 376840
telemt_connections_current 4724
telemt_connections_me_current 4724
telemt_handshake_timeouts_total 107125
telemt_upstream_connect_attempt_total 17817
telemt_upstream_connect_success_total 17733
telemt_upstream_connect_fail_total 57
telemt_upstream_connect_attempts_per_request{bucket="1"} 17790
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7392
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10284
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 57
telemt_me_reconnect_attempts_total 1097
telemt_me_reconnect_success_total 410
telemt_me_reader_eof_total 403
telemt_me_idle_close_by_peer_total 402
telemt_me_route_drop_no_conn_total 1606178
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2521397
telemt_me_endpoint_quarantine_total 316
telemt_me_single_endpoint_outage_enter_total 6
telemt_me_single_endpoint_outage_exit_total 6
telemt_me_single_endpoint_outage_reconnect_attempt_total 6
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 6
telemt_me_single_endpoint_shadow_rotate_total 385
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
telemt_desync_total 10890
telemt_desync_full_logged_total 3652
telemt_desync_suppressed_total 7238
telemt_desync_frames_bucket_total{bucket="1_2"} 2222
telemt_desync_frames_bucket_total{bucket="3_10"} 4301
telemt_desync_frames_bucket_total{bucket="gt_10"} 4367
telemt_pool_swap_total 54
telemt_pool_force_close_total 1657
telemt_me_writer_close_signal_drop_total 206
telemt_me_draining_writers_reap_progress_total 15935
telemt_me_writer_removed_unexpected_total 377
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1486
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14812
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1559
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 98
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14278
telemt_me_writer_teardown_success_total{mode="normal"} 16298
telemt_me_writer_teardown_noop_total 15935
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 30647
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 31287
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 31610
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 32063
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 32219
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 32233
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 32233
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 32233
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 32233
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 32233
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 32233
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 32233
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 32233
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 18.228785
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 32233
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 206
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 327
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 6
telemt_me_writer_removed_unexpected_minus_restored_total 44
telemt_user_connections_total{user="hello"} 2516727
telemt_user_connections_current{user="hello"} 4724
telemt_user_octets_from_client{user="hello"} 35359465836 (32.93 GB)
telemt_user_octets_to_client{user="hello"} 846548270312 (788.41 GB)
telemt_user_unique_ips_current{user="hello"} 1653
telemt_user_unique_ips_recent_window{user="hello"} 678
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 49888.3 (13h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2731850
telemt_connections_bad_total 315475
telemt_connections_current 4347
telemt_connections_me_current 4347
telemt_handshake_timeouts_total 101553
telemt_upstream_connect_attempt_total 19257
telemt_upstream_connect_success_total 19244
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 19245
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8719
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10470
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 55
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 630
telemt_me_reconnect_success_total 359
telemt_me_reader_eof_total 373
telemt_me_idle_close_by_peer_total 373
telemt_me_route_drop_no_conn_total 1120501
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2147457
telemt_me_endpoint_quarantine_total 328
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 390
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
telemt_me_writers_active_current 44
telemt_desync_total 9324
telemt_desync_full_logged_total 3205
telemt_desync_suppressed_total 6119
telemt_desync_frames_bucket_total{bucket="1_2"} 1934
telemt_desync_frames_bucket_total{bucket="3_10"} 3715
telemt_desync_frames_bucket_total{bucket="gt_10"} 3675
telemt_pool_swap_total 54
telemt_pool_force_close_total 1652
telemt_pool_stale_pick_total 16
telemt_me_writer_close_signal_drop_total 222
telemt_me_draining_writers_reap_progress_total 17553
telemt_me_writer_removed_unexpected_total 352
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1433
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16330
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 12
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1565
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 87
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15901
telemt_me_writer_teardown_success_total{mode="normal"} 17763
telemt_me_writer_teardown_noop_total 17565
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 32981
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 33780
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 34231
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 34819
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 35155
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 35292
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 35328
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 35328
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 35328
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 35328
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 35328
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 35328
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 35328
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 41.811797
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 35328
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 222
telemt_me_refill_failed_total 13
telemt_me_writer_restored_same_endpoint_total 322
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 25
telemt_user_connections_total{user="hello"} 2144170
telemt_user_connections_current{user="hello"} 4347
telemt_user_octets_from_client{user="hello"} 35092613012 (32.68 GB)
telemt_user_octets_to_client{user="hello"} 805591646788 (750.27 GB)
telemt_user_unique_ips_current{user="hello"} 1545
telemt_user_unique_ips_recent_window{user="hello"} 593
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 49889.5 (13h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2254765
telemt_connections_bad_total 252481
telemt_connections_current 3236
telemt_connections_me_current 3236
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 95629
telemt_upstream_connect_attempt_total 24269
telemt_upstream_connect_success_total 24022
telemt_upstream_connect_fail_total 127
telemt_upstream_connect_attempts_per_request{bucket="1"} 24149
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12726
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10855
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 414
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 127
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 1030
telemt_me_reconnect_success_total 459
telemt_me_reader_eof_total 424
telemt_me_idle_close_by_peer_total 424
telemt_me_route_drop_no_conn_total 660709
telemt_me_route_drop_channel_closed_total 51
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1578621
telemt_me_endpoint_quarantine_total 344
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 390
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
telemt_desync_total 7334
telemt_desync_full_logged_total 2515
telemt_desync_suppressed_total 4819
telemt_desync_frames_bucket_total{bucket="1_2"} 1826
telemt_desync_frames_bucket_total{bucket="3_10"} 2887
telemt_desync_frames_bucket_total{bucket="gt_10"} 2621
telemt_pool_swap_total 54
telemt_pool_force_close_total 1480
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 99
telemt_me_draining_writers_reap_progress_total 17413
telemt_me_writer_removed_unexpected_total 417
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1421
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16423
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1393
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 87
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15933
telemt_me_writer_teardown_success_total{mode="normal"} 17844
telemt_me_writer_teardown_noop_total 17414
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 34552
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 34983
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 35085
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 35184
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 35236
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 35256
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 35258
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 35258
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 35258
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 35258
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 35258
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 35258
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 35258
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 6.992351
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 35258
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 99
telemt_me_refill_failed_total 30
telemt_me_writer_restored_same_endpoint_total 384
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 27
telemt_user_connections_total{user="hello"} 1580414
telemt_user_connections_current{user="hello"} 3236
telemt_user_octets_from_client{user="hello"} 31240510021 (29.09 GB)
telemt_user_octets_to_client{user="hello"} 760628942739 (708.39 GB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1207
telemt_user_unique_ips_recent_window{user="hello"} 467
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 49853.5 (13h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2194499
telemt_connections_bad_total 246156
telemt_connections_current 3451
telemt_connections_me_current 3451
telemt_handshake_timeouts_total 67245
telemt_upstream_connect_attempt_total 20636
telemt_upstream_connect_success_total 20590
telemt_upstream_connect_attempts_per_request{bucket="1"} 20590
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9273
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11228
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 21
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 68
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 716
telemt_me_reconnect_success_total 468
telemt_me_reader_eof_total 433
telemt_me_idle_close_by_peer_total 433
telemt_me_route_drop_no_conn_total 616529
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1576950
telemt_me_endpoint_quarantine_total 378
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 384
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
telemt_desync_total 7446
telemt_desync_full_logged_total 2543
telemt_desync_suppressed_total 4903
telemt_desync_frames_bucket_total{bucket="1_2"} 1973
telemt_desync_frames_bucket_total{bucket="3_10"} 2853
telemt_desync_frames_bucket_total{bucket="gt_10"} 2620
telemt_pool_swap_total 53
telemt_pool_force_close_total 1457
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 136
telemt_me_draining_writers_reap_progress_total 18525
telemt_me_writer_removed_unexpected_total 408
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1427
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17537
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1347
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 110
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17068
telemt_me_writer_teardown_success_total{mode="normal"} 18964
telemt_me_writer_teardown_noop_total 18528
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 36854
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 37264
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 37374
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 37473
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 37492
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 37492
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 37492
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 37492
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 37492
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 37492
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 37492
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 37492
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 37492
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.300537
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 37492
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 136
telemt_me_refill_failed_total 14
telemt_me_writer_restored_same_endpoint_total 418
telemt_me_writer_restored_fallback_total 3
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 33
telemt_user_connections_total{user="hello"} 1574420
telemt_user_connections_current{user="hello"} 3451
telemt_user_octets_from_client{user="hello"} 36917451800 (34.38 GB)
telemt_user_octets_to_client{user="hello"} 770671934692 (717.74 GB)
telemt_user_unique_ips_current{user="hello"} 1255
telemt_user_unique_ips_recent_window{user="hello"} 441
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 49892.7 (13h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6667428
telemt_connections_bad_total 382475
telemt_connections_current 5145
telemt_connections_me_current 5145
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 247883
telemt_upstream_connect_attempt_total 59691
telemt_upstream_connect_success_total 57067
telemt_upstream_connect_fail_total 1925
telemt_upstream_connect_attempts_per_request{bucket="1"} 58992
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40347
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14698
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2022
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1925
telemt_me_keepalive_timeout_total 59
telemt_me_reconnect_attempts_total 2931
telemt_me_reconnect_success_total 1008
telemt_me_reader_eof_total 706
telemt_me_idle_close_by_peer_total 705
telemt_me_route_drop_no_conn_total 11119323
telemt_me_route_drop_channel_closed_total 43
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5604625
telemt_me_endpoint_quarantine_total 392
telemt_me_single_endpoint_outage_enter_total 55
telemt_me_single_endpoint_outage_exit_total 55
telemt_me_single_endpoint_outage_reconnect_attempt_total 117
telemt_me_single_endpoint_outage_reconnect_success_total 25
telemt_me_single_endpoint_quarantine_bypass_total 117
telemt_me_single_endpoint_shadow_rotate_total 397
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
telemt_me_writers_active_current 44
telemt_desync_total 11039
telemt_desync_full_logged_total 3555
telemt_desync_suppressed_total 7484
telemt_desync_frames_bucket_total{bucket="1_2"} 2431
telemt_desync_frames_bucket_total{bucket="3_10"} 4800
telemt_desync_frames_bucket_total{bucket="gt_10"} 3808
telemt_pool_swap_total 51
telemt_pool_force_close_total 1607
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 320
telemt_me_draining_writers_reap_progress_total 16767
telemt_me_writer_removed_unexpected_total 970
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2132
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15516
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1387
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 220
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15160
telemt_me_writer_teardown_success_total{mode="normal"} 17648
telemt_me_writer_teardown_noop_total 16776
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 31675
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 32627
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 33243
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 33891
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 34270
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 34408
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 34424
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 34424
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 34424
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 34424
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 34424
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 34424
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 34424
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 42.158381
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 34424
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 320
telemt_me_refill_failed_total 71
telemt_me_writer_restored_same_endpoint_total 698
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 264
telemt_user_connections_total{user="hello"} 5638989
telemt_user_connections_current{user="hello"} 5145
telemt_user_octets_from_client{user="hello"} 50657432504 (47.18 GB)
telemt_user_octets_to_client{user="hello"} 601909492759 (560.57 GB)
telemt_user_msgs_from_client{user="hello"} 126757
telemt_user_msgs_to_client{user="hello"} 447030
telemt_user_unique_ips_current{user="hello"} 1812
telemt_user_unique_ips_recent_window{user="hello"} 1013
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 49860.2 (13h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2197873
telemt_connections_bad_total 267776
telemt_connections_current 3259
telemt_connections_me_current 3259
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 42688
telemt_upstream_connect_attempt_total 22044
telemt_upstream_connect_success_total 21817
telemt_upstream_connect_fail_total 205
telemt_upstream_connect_attempts_per_request{bucket="1"} 22022
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10532
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11240
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 45
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 205
telemt_me_reconnect_attempts_total 2104
telemt_me_reconnect_success_total 694
telemt_me_reader_eof_total 704
telemt_me_idle_close_by_peer_total 704
telemt_me_route_drop_no_conn_total 740238
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1664148
telemt_me_endpoint_quarantine_total 308
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 386
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
telemt_me_writers_active_current 45
telemt_desync_total 7646
telemt_desync_full_logged_total 2779
telemt_desync_suppressed_total 4867
telemt_desync_frames_bucket_total{bucket="1_2"} 1450
telemt_desync_frames_bucket_total{bucket="3_10"} 3099
telemt_desync_frames_bucket_total{bucket="gt_10"} 3097
telemt_pool_swap_total 51
telemt_pool_force_close_total 1391
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 115
telemt_me_draining_writers_reap_progress_total 18305
telemt_me_writer_removed_unexpected_total 681
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1694
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17315
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1250
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 141
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16914
telemt_me_writer_teardown_success_total{mode="normal"} 19009
telemt_me_writer_teardown_noop_total 18305
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 36995
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 37195
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 37302
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 37314
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 37314
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 37314
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 37314
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 37314
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 37314
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 37314
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 37314
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 37314
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 37314
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.704855
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 37314
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 115
telemt_me_refill_failed_total 77
telemt_me_writer_restored_same_endpoint_total 592
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 81
telemt_user_connections_total{user="hello"} 1652145
telemt_user_connections_current{user="hello"} 3259
telemt_user_octets_from_client{user="hello"} 29859506644 (27.81 GB)
telemt_user_octets_to_client{user="hello"} 757389433330 (705.37 GB)
telemt_user_msgs_from_client{user="hello"} 7339
telemt_user_msgs_to_client{user="hello"} 11522
telemt_user_unique_ips_current{user="hello"} 1311
telemt_user_unique_ips_recent_window{user="hello"} 487
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 49854.6 (13h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3163308
telemt_connections_bad_total 173443
telemt_connections_current 3312
telemt_connections_me_current 3312
telemt_handshake_timeouts_total 1317443
telemt_upstream_connect_attempt_total 20499
telemt_upstream_connect_success_total 20465
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 20468
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9191
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10991
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 283
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 543
telemt_me_reconnect_success_total 306
telemt_me_reader_eof_total 310
telemt_me_idle_close_by_peer_total 310
telemt_me_route_drop_no_conn_total 590207
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1481510
telemt_me_endpoint_quarantine_total 378
telemt_me_single_endpoint_shadow_rotate_total 394
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
telemt_desync_total 7291
telemt_desync_full_logged_total 2576
telemt_desync_suppressed_total 4715
telemt_desync_frames_bucket_total{bucket="1_2"} 1296
telemt_desync_frames_bucket_total{bucket="3_10"} 2899
telemt_desync_frames_bucket_total{bucket="gt_10"} 3096
telemt_pool_swap_total 55
telemt_pool_force_close_total 1349
telemt_me_writer_close_signal_drop_total 105
telemt_me_draining_writers_reap_progress_total 18383
telemt_me_writer_removed_unexpected_total 298
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1167
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17535
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1331
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 18
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17034
telemt_me_writer_teardown_success_total{mode="normal"} 18702
telemt_me_writer_teardown_noop_total 18383
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 36907
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 37040
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 37075
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 37085
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 37085
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 37085
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 37085
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 37085
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 37085
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 37085
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 37085
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 37085
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 37085
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.957818
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 37085
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 105
telemt_me_refill_failed_total 12
telemt_me_writer_restored_same_endpoint_total 273
telemt_me_writer_restored_fallback_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 23
telemt_user_connections_total{user="hello"} 1477008
telemt_user_connections_current{user="hello"} 3312
telemt_user_octets_from_client{user="hello"} 26487470852 (24.67 GB)
telemt_user_octets_to_client{user="hello"} 725100621528 (675.30 GB)
telemt_user_unique_ips_current{user="hello"} 1260
telemt_user_unique_ips_recent_window{user="hello"} 522
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 47846.3 (13h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 657781
telemt_connections_bad_total 22268
telemt_connections_current 660
telemt_connections_me_current 660
telemt_handshake_timeouts_total 246248
telemt_upstream_connect_attempt_total 23279
telemt_upstream_connect_success_total 23277
telemt_upstream_connect_attempts_per_request{bucket="1"} 23277
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9638
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13579
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 60
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 1032
telemt_me_reconnect_success_total 379
telemt_me_reader_eof_total 380
telemt_me_idle_close_by_peer_total 380
telemt_me_route_drop_no_conn_total 139930
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 337795
telemt_me_endpoint_quarantine_total 459
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 407
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
telemt_me_writers_active_current 43
telemt_desync_total 2200
telemt_desync_full_logged_total 874
telemt_desync_suppressed_total 1326
telemt_desync_frames_bucket_total{bucket="1_2"} 378
telemt_desync_frames_bucket_total{bucket="3_10"} 823
telemt_desync_frames_bucket_total{bucket="gt_10"} 999
telemt_pool_swap_total 53
telemt_pool_force_close_total 1137
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 78
telemt_me_draining_writers_reap_progress_total 20791
telemt_me_writer_removed_unexpected_total 361
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1514
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19642
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1134
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19654
telemt_me_writer_teardown_success_total{mode="normal"} 21156
telemt_me_writer_teardown_noop_total 20791
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 41581
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 41867
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 41919
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 41942
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 41947
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 41947
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 41947
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 41947
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 41947
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 41947
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 41947
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 41947
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 41947
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.215490
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 41947
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 78
telemt_me_refill_failed_total 34
telemt_me_writer_restored_same_endpoint_total 309
telemt_me_writer_restored_fallback_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 48
telemt_user_connections_total{user="hello"} 337931
telemt_user_connections_current{user="hello"} 660
telemt_user_octets_from_client{user="hello"} 5001366187 (4.66 GB)
telemt_user_octets_to_client{user="hello"} 130667538717 (121.69 GB)
telemt_user_msgs_from_client{user="hello"} 804
telemt_user_msgs_to_client{user="hello"} 1943
telemt_user_unique_ips_current{user="hello"} 277
telemt_user_unique_ips_recent_window{user="hello"} 108
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 49864.7 (13h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2324499
telemt_connections_bad_total 213627
telemt_connections_current 3921
telemt_connections_me_current 3921
telemt_handshake_timeouts_total 56759
telemt_upstream_connect_attempt_total 21310
telemt_upstream_connect_success_total 21218
telemt_upstream_connect_fail_total 62
telemt_upstream_connect_attempts_per_request{bucket="1"} 21280
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10625
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10568
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 62
telemt_me_reconnect_attempts_total 851
telemt_me_reconnect_success_total 477
telemt_me_reader_eof_total 442
telemt_me_idle_close_by_peer_total 442
telemt_me_route_drop_no_conn_total 602388
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1835143
telemt_me_endpoint_quarantine_total 397
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 393
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
telemt_me_writers_active_current 43
telemt_desync_total 7183
telemt_desync_full_logged_total 2397
telemt_desync_suppressed_total 4786
telemt_desync_frames_bucket_total{bucket="1_2"} 1737
telemt_desync_frames_bucket_total{bucket="3_10"} 2695
telemt_desync_frames_bucket_total{bucket="gt_10"} 2751
telemt_pool_swap_total 55
telemt_pool_force_close_total 1374
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 137
telemt_me_draining_writers_reap_progress_total 19178
telemt_me_writer_removed_unexpected_total 436
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1444
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18184
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1350
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 24
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17804
telemt_me_writer_teardown_success_total{mode="normal"} 19628
telemt_me_writer_teardown_noop_total 19178
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 38419
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 38651
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 38710
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 38799
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 38806
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 38806
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 38806
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 38806
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 38806
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 38806
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 38806
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 38806
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 38806
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.088930
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 38806
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 137
telemt_me_refill_failed_total 19
telemt_me_writer_restored_same_endpoint_total 426
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 1829088
telemt_user_connections_current{user="hello"} 3921
telemt_user_octets_from_client{user="hello"} 40044327952 (37.29 GB)
telemt_user_octets_to_client{user="hello"} 859354753512 (800.34 GB)
telemt_user_unique_ips_current{user="hello"} 1413
telemt_user_unique_ips_recent_window{user="hello"} 513
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 49861.4 (13h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2150760
telemt_connections_bad_total 173973
telemt_connections_current 3731
telemt_connections_me_current 3731
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 52741
telemt_upstream_connect_attempt_total 37510
telemt_upstream_connect_success_total 37289
telemt_upstream_connect_fail_total 178
telemt_upstream_connect_attempts_per_request{bucket="1"} 37467
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23956
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12240
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 514
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 579
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 178
telemt_me_reconnect_attempts_total 3071
telemt_me_reconnect_success_total 621
telemt_me_reader_eof_total 548
telemt_me_idle_close_by_peer_total 548
telemt_me_seq_mismatch_total 25
telemt_me_route_drop_no_conn_total 598457
telemt_me_route_drop_channel_closed_total 37
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1729637
telemt_me_endpoint_quarantine_total 437
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 392
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
telemt_desync_total 6591
telemt_desync_full_logged_total 2228
telemt_desync_suppressed_total 4363
telemt_desync_frames_bucket_total{bucket="1_2"} 1762
telemt_desync_frames_bucket_total{bucket="3_10"} 2457
telemt_desync_frames_bucket_total{bucket="gt_10"} 2372
telemt_pool_swap_total 54
telemt_pool_force_close_total 1319
telemt_me_writer_close_signal_drop_total 121
telemt_me_draining_writers_reap_progress_total 18383
telemt_me_writer_removed_unexpected_total 557
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1698
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17269
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1238
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 81
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17064
telemt_me_writer_teardown_success_total{mode="normal"} 18967
telemt_me_writer_teardown_noop_total 18384
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 36894
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 37142
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 37276
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 37345
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 37351
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 37351
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 37351
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 37351
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 37351
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 37351
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 37351
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 37351
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 37351
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.518093
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 37351
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 121
telemt_me_refill_failed_total 139
telemt_me_writer_restored_same_endpoint_total 480
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 45
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 1740852
telemt_user_connections_current{user="hello"} 3731
telemt_user_octets_from_client{user="hello"} 28901298357 (26.92 GB)
telemt_user_octets_to_client{user="hello"} 772389142440 (719.34 GB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1333
telemt_user_unique_ips_recent_window{user="hello"} 511
```