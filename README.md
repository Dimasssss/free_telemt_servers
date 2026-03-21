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

# Server Metrics 2026-03-21 11:28:43 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 53570.6 (14h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1631991
telemt_connections_bad_total 82175
telemt_connections_current 1570
telemt_connections_me_current 1570
telemt_handshake_timeouts_total 64844
telemt_upstream_connect_attempt_total 20954
telemt_upstream_connect_success_total 20846
telemt_upstream_connect_fail_total 69
telemt_upstream_connect_attempts_per_request{bucket="1"} 20915
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7420
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13350
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 26
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 69
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 56
telemt_me_reconnect_attempts_total 1061
telemt_me_reconnect_success_total 460
telemt_me_reader_eof_total 454
telemt_me_idle_close_by_peer_total 454
telemt_me_route_drop_no_conn_total 998942
telemt_me_route_drop_channel_closed_total 383
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1255630
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_endpoint_quarantine_total 376
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 426
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
telemt_desync_total 5102
telemt_desync_full_logged_total 1787
telemt_desync_suppressed_total 3315
telemt_desync_frames_bucket_total{bucket="1_2"} 1073
telemt_desync_frames_bucket_total{bucket="3_10"} 1971
telemt_desync_frames_bucket_total{bucket="gt_10"} 2058
telemt_pool_swap_total 58
telemt_pool_force_close_total 1699
telemt_pool_stale_pick_total 12
telemt_me_writer_close_signal_drop_total 300
telemt_me_draining_writers_reap_progress_total 18712
telemt_me_writer_removed_unexpected_total 434
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1527
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17478
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1638
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 61
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17013
telemt_me_writer_teardown_success_total{mode="normal"} 19005
telemt_me_writer_teardown_noop_total 18716
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 33088
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 34048
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 34824
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 36140
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 37131
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 37557
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 37712
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 37720
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 37720
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 37721
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 37721
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 37721
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 37721
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 122.958739
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 37721
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 300
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 402
telemt_me_writer_restored_fallback_total 3
telemt_me_async_recovery_trigger_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 29
telemt_user_connections_total{user="hello"} 1254734
telemt_user_connections_current{user="hello"} 1570
telemt_user_octets_from_client{user="hello"} 17677468847 (16.46 GB)
telemt_user_octets_to_client{user="hello"} 343418854667 (319.83 GB)
telemt_user_msgs_from_client{user="hello"} 295
telemt_user_msgs_to_client{user="hello"} 249
telemt_user_unique_ips_current{user="hello"} 584
telemt_user_unique_ips_recent_window{user="hello"} 256
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 1461.6 (0h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 112809
telemt_connections_bad_total 5256
telemt_connections_current 1605
telemt_connections_me_current 1605
telemt_handshake_timeouts_total 3982
telemt_upstream_connect_attempt_total 522
telemt_upstream_connect_success_total 521
telemt_upstream_connect_attempts_per_request{bucket="1"} 521
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 231
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 286
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_reconnect_attempts_total 9
telemt_me_reconnect_success_total 9
telemt_me_reader_eof_total 11
telemt_me_idle_close_by_peer_total 11
telemt_me_route_drop_no_conn_total 75392
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 97384
telemt_me_endpoint_quarantine_total 11
telemt_me_single_endpoint_shadow_rotate_total 14
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
telemt_me_writers_active_current 45
telemt_desync_total 369
telemt_desync_full_logged_total 153
telemt_desync_suppressed_total 216
telemt_desync_frames_bucket_total{bucket="1_2"} 80
telemt_desync_frames_bucket_total{bucket="3_10"} 134
telemt_desync_frames_bucket_total{bucket="gt_10"} 155
telemt_pool_swap_total 1
telemt_pool_force_close_total 32
telemt_me_writer_close_signal_drop_total 4
telemt_me_draining_writers_reap_progress_total 386
telemt_me_writer_removed_unexpected_total 9
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 29
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 368
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 31
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 354
telemt_me_writer_teardown_success_total{mode="normal"} 397
telemt_me_writer_teardown_noop_total 386
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 763
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 778
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 778
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 783
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 783
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 783
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 783
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 783
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 783
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 783
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 783
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 783
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 783
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.150107
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 783
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 4
telemt_me_writer_restored_same_endpoint_total 9
telemt_user_connections_total{user="hello"} 97348
telemt_user_connections_current{user="hello"} 1605
telemt_user_octets_from_client{user="hello"} 1188453012 (1.11 GB)
telemt_user_octets_to_client{user="hello"} 23419089464 (21.81 GB)
telemt_user_unique_ips_current{user="hello"} 972
telemt_user_unique_ips_recent_window{user="hello"} 327
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 53568.1 (14h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3115066
telemt_connections_bad_total 337315
telemt_connections_current 3934
telemt_connections_me_current 3934
telemt_handshake_timeouts_total 113598
telemt_upstream_connect_attempt_total 20428
telemt_upstream_connect_success_total 20415
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 20416
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9248
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11107
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 60
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 694
telemt_me_reconnect_success_total 388
telemt_me_reader_eof_total 399
telemt_me_idle_close_by_peer_total 399
telemt_me_route_drop_no_conn_total 1346187
telemt_me_route_drop_channel_closed_total 25
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2478813
telemt_me_endpoint_quarantine_total 351
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 3
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 417
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
telemt_me_writers_active_current 46
telemt_desync_total 10860
telemt_desync_full_logged_total 3662
telemt_desync_suppressed_total 7198
telemt_desync_frames_bucket_total{bucket="1_2"} 2264
telemt_desync_frames_bucket_total{bucket="3_10"} 4256
telemt_desync_frames_bucket_total{bucket="gt_10"} 4340
telemt_pool_swap_total 58
telemt_pool_force_close_total 1771
telemt_pool_stale_pick_total 16
telemt_me_writer_close_signal_drop_total 247
telemt_me_draining_writers_reap_progress_total 18575
telemt_me_writer_removed_unexpected_total 376
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1531
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17280
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 13
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1678
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 93
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16804
telemt_me_writer_teardown_success_total{mode="normal"} 18811
telemt_me_writer_teardown_noop_total 18588
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 34823
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 35712
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 36193
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 36822
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 37185
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 37353
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 37399
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 37399
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 37399
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 37399
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 37399
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 37399
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 37399
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 47.778764
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 37399
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 247
telemt_me_refill_failed_total 15
telemt_me_writer_restored_same_endpoint_total 344
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 27
telemt_user_connections_total{user="hello"} 2475330
telemt_user_connections_current{user="hello"} 3934
telemt_user_octets_from_client{user="hello"} 40631560052 (37.84 GB)
telemt_user_octets_to_client{user="hello"} 904720428516 (842.59 GB)
telemt_user_unique_ips_current{user="hello"} 1540
telemt_user_unique_ips_recent_window{user="hello"} 609
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 53570.4 (14h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2582660
telemt_connections_bad_total 285622
telemt_connections_current 3528
telemt_connections_me_current 3528
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 106908
telemt_upstream_connect_attempt_total 25377
telemt_upstream_connect_success_total 25118
telemt_upstream_connect_fail_total 131
telemt_upstream_connect_attempts_per_request{bucket="1"} 25249
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13196
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11464
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 431
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 131
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 1070
telemt_me_reconnect_success_total 499
telemt_me_reader_eof_total 460
telemt_me_idle_close_by_peer_total 460
telemt_me_route_drop_no_conn_total 753216
telemt_me_route_drop_channel_closed_total 62
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1822427
telemt_me_endpoint_quarantine_total 361
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 415
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
telemt_me_writers_active_current 45
telemt_desync_total 8309
telemt_desync_full_logged_total 2854
telemt_desync_suppressed_total 5455
telemt_desync_frames_bucket_total{bucket="1_2"} 2074
telemt_desync_frames_bucket_total{bucket="3_10"} 3251
telemt_desync_frames_bucket_total{bucket="gt_10"} 2984
telemt_pool_swap_total 58
telemt_pool_force_close_total 1607
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 130
telemt_me_draining_writers_reap_progress_total 18350
telemt_me_writer_removed_unexpected_total 450
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1541
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17277
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1502
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 105
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16743
telemt_me_writer_teardown_success_total{mode="normal"} 18818
telemt_me_writer_teardown_noop_total 18351
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 36260
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 36790
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 36931
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 37070
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 37143
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 37167
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 37169
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 37169
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 37169
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 37169
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 37169
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 37169
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 37169
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 9.167432
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 37169
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 130
telemt_me_refill_failed_total 30
telemt_me_writer_restored_same_endpoint_total 418
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 26
telemt_user_connections_total{user="hello"} 1823924
telemt_user_connections_current{user="hello"} 3528
telemt_user_octets_from_client{user="hello"} 34862142413 (32.47 GB)
telemt_user_octets_to_client{user="hello"} 875446490695 (815.32 GB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1349
telemt_user_unique_ips_recent_window{user="hello"} 489
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 53533.3 (14h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2520024
telemt_connections_bad_total 285495
telemt_connections_current 3441
telemt_connections_me_current 3441
telemt_handshake_timeouts_total 74944
telemt_upstream_connect_attempt_total 21776
telemt_upstream_connect_success_total 21716
telemt_upstream_connect_attempts_per_request{bucket="1"} 21716
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9791
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11818
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 31
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 76
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 785
telemt_me_reconnect_success_total 532
telemt_me_reader_eof_total 473
telemt_me_idle_close_by_peer_total 473
telemt_me_route_drop_no_conn_total 731467
telemt_me_route_drop_channel_closed_total 25
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1814592
telemt_me_endpoint_quarantine_total 411
telemt_me_single_endpoint_outage_enter_total 4
telemt_me_single_endpoint_outage_exit_total 4
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 3
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 409
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
telemt_me_writers_active_current 44
telemt_desync_total 8518
telemt_desync_full_logged_total 2885
telemt_desync_suppressed_total 5633
telemt_desync_frames_bucket_total{bucket="1_2"} 2249
telemt_desync_frames_bucket_total{bucket="3_10"} 3253
telemt_desync_frames_bucket_total{bucket="gt_10"} 3016
telemt_pool_swap_total 57
telemt_pool_force_close_total 1584
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 160
telemt_me_draining_writers_reap_progress_total 19503
telemt_me_writer_removed_unexpected_total 449
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1554
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18430
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1467
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 117
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17919
telemt_me_writer_teardown_success_total{mode="normal"} 19984
telemt_me_writer_teardown_noop_total 19506
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 38703
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 39216
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 39339
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 39461
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 39490
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 39490
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 39490
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 39490
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 39490
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 39490
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 39490
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 39490
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 39490
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.439893
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 39490
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 160
telemt_me_refill_failed_total 14
telemt_me_writer_restored_same_endpoint_total 458
telemt_me_writer_restored_fallback_total 3
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 33
telemt_user_connections_total{user="hello"} 1811776
telemt_user_connections_current{user="hello"} 3441
telemt_user_octets_from_client{user="hello"} 41262712524 (38.43 GB)
telemt_user_octets_to_client{user="hello"} 881869992660 (821.31 GB)
telemt_user_unique_ips_current{user="hello"} 1269
telemt_user_unique_ips_recent_window{user="hello"} 520
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 53572.5 (14h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8008144
telemt_connections_bad_total 541070
telemt_connections_current 5041
telemt_connections_me_current 5041
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 282610
telemt_upstream_connect_attempt_total 63743
telemt_upstream_connect_success_total 60037
telemt_upstream_connect_fail_total 2945
telemt_upstream_connect_attempts_per_request{bucket="1"} 62982
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 42121
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15552
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2364
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2945
telemt_me_keepalive_timeout_total 59
telemt_me_reconnect_attempts_total 3167
telemt_me_reconnect_success_total 1094
telemt_me_reader_eof_total 791
telemt_me_idle_close_by_peer_total 790
telemt_me_route_drop_no_conn_total 13901370
telemt_me_route_drop_channel_closed_total 54
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6667690
telemt_me_endpoint_quarantine_total 418
telemt_me_single_endpoint_outage_enter_total 58
telemt_me_single_endpoint_outage_exit_total 58
telemt_me_single_endpoint_outage_reconnect_attempt_total 121
telemt_me_single_endpoint_outage_reconnect_success_total 28
telemt_me_single_endpoint_quarantine_bypass_total 121
telemt_me_single_endpoint_shadow_rotate_total 421
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
telemt_me_writers_active_current 45
telemt_desync_total 12701
telemt_desync_full_logged_total 4092
telemt_desync_suppressed_total 8609
telemt_desync_frames_bucket_total{bucket="1_2"} 2759
telemt_desync_frames_bucket_total{bucket="3_10"} 5603
telemt_desync_frames_bucket_total{bucket="gt_10"} 4339
telemt_pool_swap_total 54
telemt_pool_force_close_total 1694
telemt_pool_stale_pick_total 5
telemt_me_writer_close_signal_drop_total 350
telemt_me_draining_writers_reap_progress_total 17885
telemt_me_writer_removed_unexpected_total 1057
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2300
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16538
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1446
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 248
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16191
telemt_me_writer_teardown_success_total{mode="normal"} 18838
telemt_me_writer_teardown_noop_total 17894
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 33749
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 34792
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 35448
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 36148
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 36569
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 36714
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 36730
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 36732
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 36732
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 36732
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 36732
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 36732
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 36732
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 46.431605
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 36732
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 350
telemt_me_refill_failed_total 78
telemt_me_writer_restored_same_endpoint_total 770
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 279
telemt_user_connections_total{user="hello"} 6703402
telemt_user_connections_current{user="hello"} 5041
telemt_user_octets_from_client{user="hello"} 55902166324 (52.06 GB)
telemt_user_octets_to_client{user="hello"} 642726117915 (598.59 GB)
telemt_user_msgs_from_client{user="hello"} 129175
telemt_user_msgs_to_client{user="hello"} 449473
telemt_user_unique_ips_current{user="hello"} 1848
telemt_user_unique_ips_recent_window{user="hello"} 991
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 53540.3 (14h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2533561
telemt_connections_bad_total 307578
telemt_connections_current 3699
telemt_connections_me_current 3699
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 55446
telemt_upstream_connect_attempt_total 23233
telemt_upstream_connect_success_total 22989
telemt_upstream_connect_fail_total 219
telemt_upstream_connect_attempts_per_request{bucket="1"} 23208
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11074
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11868
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 47
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 219
telemt_me_reconnect_attempts_total 2231
telemt_me_reconnect_success_total 753
telemt_me_reader_eof_total 749
telemt_me_idle_close_by_peer_total 749
telemt_me_route_drop_no_conn_total 867495
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 33
telemt_me_route_drop_queue_full_profile_total{profile="high"} 33
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1918042
telemt_me_endpoint_quarantine_total 342
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 412
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
telemt_me_writers_active_current 45
telemt_desync_total 8765
telemt_desync_full_logged_total 3163
telemt_desync_suppressed_total 5602
telemt_desync_frames_bucket_total{bucket="1_2"} 1684
telemt_desync_frames_bucket_total{bucket="3_10"} 3537
telemt_desync_frames_bucket_total{bucket="gt_10"} 3544
telemt_pool_swap_total 55
telemt_pool_force_close_total 1511
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 132
telemt_me_draining_writers_reap_progress_total 19327
telemt_me_writer_removed_unexpected_total 725
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1810
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18266
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1362
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 149
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17816
telemt_me_writer_teardown_success_total{mode="normal"} 20076
telemt_me_writer_teardown_noop_total 19327
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 39017
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 39254
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 39377
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 39403
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 39403
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 39403
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 39403
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 39403
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 39403
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 39403
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 39403
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 39403
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 39403
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.156297
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 39403
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 132
telemt_me_refill_failed_total 81
telemt_me_writer_restored_same_endpoint_total 632
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 85
telemt_user_connections_total{user="hello"} 1903384
telemt_user_connections_current{user="hello"} 3699
telemt_user_octets_from_client{user="hello"} 34614683652 (32.24 GB)
telemt_user_octets_to_client{user="hello"} 854923090602 (796.21 GB)
telemt_user_msgs_from_client{user="hello"} 7339
telemt_user_msgs_to_client{user="hello"} 11522
telemt_user_unique_ips_current{user="hello"} 1426
telemt_user_unique_ips_recent_window{user="hello"} 576
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 53534.7 (14h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3746646
telemt_connections_bad_total 196679
telemt_connections_current 3260
telemt_connections_me_current 3260
telemt_handshake_timeouts_total 1612912
telemt_upstream_connect_attempt_total 21798
telemt_upstream_connect_success_total 21764
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 21767
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9782
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11696
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 286
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 775
telemt_me_reconnect_success_total 391
telemt_me_reader_eof_total 390
telemt_me_idle_close_by_peer_total 390
telemt_me_route_drop_no_conn_total 718692
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1701812
telemt_me_endpoint_quarantine_total 411
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 422
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
telemt_desync_total 8323
telemt_desync_full_logged_total 2969
telemt_desync_suppressed_total 5354
telemt_desync_frames_bucket_total{bucket="1_2"} 1526
telemt_desync_frames_bucket_total{bucket="3_10"} 3313
telemt_desync_frames_bucket_total{bucket="gt_10"} 3484
telemt_pool_swap_total 58
telemt_pool_force_close_total 1458
telemt_me_writer_close_signal_drop_total 117
telemt_me_draining_writers_reap_progress_total 19495
telemt_me_writer_removed_unexpected_total 378
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1309
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18585
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1411
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 47
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18037
telemt_me_writer_teardown_success_total{mode="normal"} 19894
telemt_me_writer_teardown_noop_total 19495
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 39193
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 39340
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 39379
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 39389
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 39389
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 39389
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 39389
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 39389
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 39389
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 39389
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 39389
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 39389
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 39389
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.042504
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 39389
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 117
telemt_me_refill_failed_total 21
telemt_me_writer_restored_same_endpoint_total 343
telemt_me_writer_restored_fallback_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 33
telemt_user_connections_total{user="hello"} 1695803
telemt_user_connections_current{user="hello"} 3260
telemt_user_octets_from_client{user="hello"} 30121019740 (28.05 GB)
telemt_user_octets_to_client{user="hello"} 822814595800 (766.31 GB)
telemt_user_unique_ips_current{user="hello"} 1315
telemt_user_unique_ips_recent_window{user="hello"} 492
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 51526.0 (14h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 778624
telemt_connections_bad_total 46907
telemt_connections_current 656
telemt_connections_me_current 656
telemt_handshake_timeouts_total 284220
telemt_upstream_connect_attempt_total 24817
telemt_upstream_connect_success_total 24815
telemt_upstream_connect_attempts_per_request{bucket="1"} 24815
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10273
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14473
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 69
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 1077
telemt_me_reconnect_success_total 410
telemt_me_reader_eof_total 406
telemt_me_idle_close_by_peer_total 406
telemt_me_route_drop_no_conn_total 162742
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 386391
telemt_me_endpoint_quarantine_total 485
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 438
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 8
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
telemt_desync_total 2637
telemt_desync_full_logged_total 1015
telemt_desync_suppressed_total 1622
telemt_desync_frames_bucket_total{bucket="1_2"} 422
telemt_desync_frames_bucket_total{bucket="3_10"} 944
telemt_desync_frames_bucket_total{bucket="gt_10"} 1271
telemt_pool_swap_total 57
telemt_pool_force_close_total 1267
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 85
telemt_me_draining_writers_reap_progress_total 22217
telemt_me_writer_removed_unexpected_total 386
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1628
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20980
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1264
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20950
telemt_me_writer_teardown_success_total{mode="normal"} 22608
telemt_me_writer_teardown_noop_total 22217
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 44400
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 44729
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 44793
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 44818
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 44825
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 44825
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 44825
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 44825
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 44825
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 44825
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 44825
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 44825
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 44825
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.570607
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 44825
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 85
telemt_me_refill_failed_total 35
telemt_me_writer_restored_same_endpoint_total 331
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 50
telemt_user_connections_total{user="hello"} 386459
telemt_user_connections_current{user="hello"} 656
telemt_user_octets_from_client{user="hello"} 5741570955 (5.35 GB)
telemt_user_octets_to_client{user="hello"} 149080831849 (138.84 GB)
telemt_user_msgs_from_client{user="hello"} 804
telemt_user_msgs_to_client{user="hello"} 1943
telemt_user_unique_ips_current{user="hello"} 263
telemt_user_unique_ips_recent_window{user="hello"} 121
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 53544.5 (14h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2688875
telemt_connections_bad_total 252971
telemt_connections_current 3931
telemt_connections_me_current 3931
telemt_handshake_timeouts_total 67646
telemt_upstream_connect_attempt_total 22575
telemt_upstream_connect_success_total 22479
telemt_upstream_connect_fail_total 65
telemt_upstream_connect_attempts_per_request{bucket="1"} 22544
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11210
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11243
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 65
telemt_me_reconnect_attempts_total 922
telemt_me_reconnect_success_total 505
telemt_me_reader_eof_total 471
telemt_me_idle_close_by_peer_total 471
telemt_me_route_drop_no_conn_total 711014
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2125524
telemt_me_endpoint_quarantine_total 421
telemt_me_single_endpoint_outage_enter_total 6
telemt_me_single_endpoint_outage_exit_total 6
telemt_me_single_endpoint_outage_reconnect_attempt_total 6
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 6
telemt_me_single_endpoint_shadow_rotate_total 421
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
telemt_me_writers_active_current 45
telemt_desync_total 8490
telemt_desync_full_logged_total 2821
telemt_desync_suppressed_total 5669
telemt_desync_frames_bucket_total{bucket="1_2"} 2021
telemt_desync_frames_bucket_total{bucket="3_10"} 3176
telemt_desync_frames_bucket_total{bucket="gt_10"} 3293
telemt_pool_swap_total 59
telemt_pool_force_close_total 1479
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 156
telemt_me_draining_writers_reap_progress_total 20291
telemt_me_writer_removed_unexpected_total 463
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1544
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19226
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1452
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 27
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18812
telemt_me_writer_teardown_success_total{mode="normal"} 20770
telemt_me_writer_teardown_noop_total 20291
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 40585
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 40893
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 40954
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 41054
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 41061
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 41061
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 41061
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 41061
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 41061
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 41061
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 41061
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 41061
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 41061
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.485038
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 41061
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 156
telemt_me_refill_failed_total 21
telemt_me_writer_restored_same_endpoint_total 450
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 8
telemt_user_connections_total{user="hello"} 2119135
telemt_user_connections_current{user="hello"} 3931
telemt_user_octets_from_client{user="hello"} 44545275000 (41.49 GB)
telemt_user_octets_to_client{user="hello"} 991051409812 (922.99 GB)
telemt_user_unique_ips_current{user="hello"} 1461
telemt_user_unique_ips_recent_window{user="hello"} 582
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 53541.3 (14h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2463822
telemt_connections_bad_total 193159
telemt_connections_current 3847
telemt_connections_me_current 3847
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 64680
telemt_upstream_connect_attempt_total 38719
telemt_upstream_connect_success_total 38484
telemt_upstream_connect_fail_total 192
telemt_upstream_connect_attempts_per_request{bucket="1"} 38676
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24529
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12856
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 514
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 585
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 192
telemt_me_reconnect_attempts_total 3207
telemt_me_reconnect_success_total 665
telemt_me_reader_eof_total 581
telemt_me_idle_close_by_peer_total 581
telemt_me_seq_mismatch_total 28
telemt_me_route_drop_no_conn_total 716101
telemt_me_route_drop_channel_closed_total 50
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1987173
telemt_me_endpoint_quarantine_total 465
telemt_me_single_endpoint_outage_enter_total 14
telemt_me_single_endpoint_outage_exit_total 14
telemt_me_single_endpoint_outage_reconnect_attempt_total 14
telemt_me_single_endpoint_outage_reconnect_success_total 14
telemt_me_single_endpoint_quarantine_bypass_total 14
telemt_me_single_endpoint_shadow_rotate_total 418
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
telemt_desync_total 7443
telemt_desync_full_logged_total 2551
telemt_desync_suppressed_total 4892
telemt_desync_frames_bucket_total{bucket="1_2"} 1953
telemt_desync_frames_bucket_total{bucket="3_10"} 2765
telemt_desync_frames_bucket_total{bucket="gt_10"} 2725
telemt_pool_swap_total 58
telemt_pool_force_close_total 1435
telemt_me_writer_close_signal_drop_total 131
telemt_me_draining_writers_reap_progress_total 19447
telemt_me_writer_removed_unexpected_total 593
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1822
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18246
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1343
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 92
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18012
telemt_me_writer_teardown_success_total{mode="normal"} 20068
telemt_me_writer_teardown_noop_total 19448
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 38989
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 39282
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 39419
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 39510
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 39516
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 39516
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 39516
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 39516
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 39516
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 39516
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 39516
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 39516
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 39516
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.136455
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 39516
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 131
telemt_me_refill_failed_total 144
telemt_me_writer_restored_same_endpoint_total 505
telemt_me_writer_restored_fallback_total 37
telemt_me_async_recovery_trigger_total 45
telemt_me_writer_removed_unexpected_minus_restored_total 51
telemt_user_connections_total{user="hello"} 1998039
telemt_user_connections_current{user="hello"} 3847
telemt_user_octets_from_client{user="hello"} 35970690817 (33.50 GB)
telemt_user_octets_to_client{user="hello"} 878262342788 (817.95 GB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1385
telemt_user_unique_ips_recent_window{user="hello"} 557
```