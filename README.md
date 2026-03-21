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

# Server Metrics 2026-03-21 10:42:39 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 50806.9 (14h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1482081
telemt_connections_bad_total 76031
telemt_connections_current 1632
telemt_connections_me_current 1632
telemt_handshake_timeouts_total 59596
telemt_upstream_connect_attempt_total 19985
telemt_upstream_connect_success_total 19895
telemt_upstream_connect_fail_total 66
telemt_upstream_connect_attempts_per_request{bucket="1"} 19961
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7118
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12726
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 14
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 66
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 55
telemt_me_reconnect_attempts_total 955
telemt_me_reconnect_success_total 416
telemt_me_reader_eof_total 414
telemt_me_idle_close_by_peer_total 414
telemt_me_route_drop_no_conn_total 806221
telemt_me_route_drop_channel_closed_total 315
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1130157
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_endpoint_quarantine_total 356
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 3
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 407
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
telemt_desync_total 4751
telemt_desync_full_logged_total 1655
telemt_desync_suppressed_total 3096
telemt_desync_frames_bucket_total{bucket="1_2"} 984
telemt_desync_frames_bucket_total{bucket="3_10"} 1847
telemt_desync_frames_bucket_total{bucket="gt_10"} 1920
telemt_pool_swap_total 55
telemt_pool_force_close_total 1577
telemt_pool_stale_pick_total 12
telemt_me_writer_close_signal_drop_total 269
telemt_me_draining_writers_reap_progress_total 17883
telemt_me_writer_removed_unexpected_total 392
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1443
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16728
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1516
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 61
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16306
telemt_me_writer_teardown_success_total{mode="normal"} 18171
telemt_me_writer_teardown_noop_total 17885
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 32061
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 32925
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 33589
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 34732
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 35591
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 35927
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 36049
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 36056
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 36056
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 36056
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 36056
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 36056
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 36056
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 100.422575
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 36056
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 269
telemt_me_refill_failed_total 30
telemt_me_writer_restored_same_endpoint_total 366
telemt_me_writer_restored_fallback_total 3
telemt_me_async_recovery_trigger_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 23
telemt_user_connections_total{user="hello"} 1129261
telemt_user_connections_current{user="hello"} 1632
telemt_user_octets_from_client{user="hello"} 15794412459 (14.71 GB)
telemt_user_octets_to_client{user="hello"} 320246875535 (298.25 GB)
telemt_user_msgs_from_client{user="hello"} 295
telemt_user_msgs_to_client{user="hello"} 249
telemt_user_unique_ips_current{user="hello"} 580
telemt_user_unique_ips_recent_window{user="hello"} 229
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 50808.1 (14h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3820204
telemt_connections_bad_total 382707
telemt_connections_current 4970
telemt_connections_me_current 4970
telemt_handshake_timeouts_total 111324
telemt_upstream_connect_attempt_total 18092
telemt_upstream_connect_success_total 18007
telemt_upstream_connect_fail_total 58
telemt_upstream_connect_attempts_per_request{bucket="1"} 18065
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7513
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10436
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 58
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 58
telemt_me_reconnect_attempts_total 1106
telemt_me_reconnect_success_total 418
telemt_me_reader_eof_total 411
telemt_me_idle_close_by_peer_total 410
telemt_me_route_drop_no_conn_total 1780700
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2637201
telemt_me_endpoint_quarantine_total 321
telemt_me_single_endpoint_outage_enter_total 6
telemt_me_single_endpoint_outage_exit_total 6
telemt_me_single_endpoint_outage_reconnect_attempt_total 6
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 6
telemt_me_single_endpoint_shadow_rotate_total 393
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
telemt_desync_total 11256
telemt_desync_full_logged_total 3773
telemt_desync_suppressed_total 7483
telemt_desync_frames_bucket_total{bucket="1_2"} 2301
telemt_desync_frames_bucket_total{bucket="3_10"} 4451
telemt_desync_frames_bucket_total{bucket="gt_10"} 4504
telemt_pool_swap_total 55
telemt_pool_force_close_total 1687
telemt_me_writer_close_signal_drop_total 210
telemt_me_draining_writers_reap_progress_total 16183
telemt_me_writer_removed_unexpected_total 385
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1517
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15037
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1587
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 100
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14496
telemt_me_writer_teardown_success_total{mode="normal"} 16554
telemt_me_writer_teardown_noop_total 16183
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 31106
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 31767
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 32093
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 32557
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 32721
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 32737
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 32737
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 32737
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 32737
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 32737
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 32737
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 32737
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 32737
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 18.932196
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 32737
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 210
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 335
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 6
telemt_me_writer_removed_unexpected_minus_restored_total 44
telemt_user_connections_total{user="hello"} 2632437
telemt_user_connections_current{user="hello"} 4970
telemt_user_octets_from_client{user="hello"} 36317169952 (33.82 GB)
telemt_user_octets_to_client{user="hello"} 872371512268 (812.46 GB)
telemt_user_unique_ips_current{user="hello"} 1722
telemt_user_unique_ips_recent_window{user="hello"} 652
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 50804.6 (14h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2820938
telemt_connections_bad_total 320228
telemt_connections_current 4012
telemt_connections_me_current 4012
telemt_handshake_timeouts_total 104197
telemt_upstream_connect_attempt_total 19536
telemt_upstream_connect_success_total 19523
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 19524
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8848
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10620
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 55
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 632
telemt_me_reconnect_success_total 362
telemt_me_reader_eof_total 375
telemt_me_idle_close_by_peer_total 375
telemt_me_route_drop_no_conn_total 1163022
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2224726
telemt_me_endpoint_quarantine_total 334
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 396
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
telemt_desync_total 9639
telemt_desync_full_logged_total 3317
telemt_desync_suppressed_total 6322
telemt_desync_frames_bucket_total{bucket="1_2"} 1994
telemt_desync_frames_bucket_total{bucket="3_10"} 3823
telemt_desync_frames_bucket_total{bucket="gt_10"} 3822
telemt_pool_swap_total 55
telemt_pool_force_close_total 1681
telemt_pool_stale_pick_total 16
telemt_me_writer_close_signal_drop_total 232
telemt_me_draining_writers_reap_progress_total 17805
telemt_me_writer_removed_unexpected_total 354
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1458
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16559
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 13
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1591
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 90
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16124
telemt_me_writer_teardown_success_total{mode="normal"} 18017
telemt_me_writer_teardown_noop_total 17818
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 33421
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 34252
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 34715
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 35309
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 35651
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 35795
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 35835
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 35835
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 35835
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 35835
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 35835
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 35835
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 35835
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 43.351181
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 35835
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 232
telemt_me_refill_failed_total 13
telemt_me_writer_restored_same_endpoint_total 324
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 25
telemt_user_connections_total{user="hello"} 2221424
telemt_user_connections_current{user="hello"} 4012
telemt_user_octets_from_client{user="hello"} 36133280840 (33.65 GB)
telemt_user_octets_to_client{user="hello"} 831555506788 (774.45 GB)
telemt_user_unique_ips_current{user="hello"} 1495
telemt_user_unique_ips_recent_window{user="hello"} 588
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 50805.8 (14h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2333481
telemt_connections_bad_total 262297
telemt_connections_current 3422
telemt_connections_me_current 3422
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 98628
telemt_upstream_connect_attempt_total 24570
telemt_upstream_connect_success_total 24318
telemt_upstream_connect_fail_total 129
telemt_upstream_connect_attempts_per_request{bucket="1"} 24447
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12857
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11012
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 422
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 129
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 1040
telemt_me_reconnect_success_total 468
telemt_me_reader_eof_total 432
telemt_me_idle_close_by_peer_total 432
telemt_me_route_drop_no_conn_total 682170
telemt_me_route_drop_channel_closed_total 54
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1637839
telemt_me_endpoint_quarantine_total 349
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 397
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
telemt_desync_total 7511
telemt_desync_full_logged_total 2578
telemt_desync_suppressed_total 4933
telemt_desync_frames_bucket_total{bucket="1_2"} 1877
telemt_desync_frames_bucket_total{bucket="3_10"} 2946
telemt_desync_frames_bucket_total{bucket="gt_10"} 2688
telemt_pool_swap_total 55
telemt_pool_force_close_total 1514
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 106
telemt_me_draining_writers_reap_progress_total 17661
telemt_me_writer_removed_unexpected_total 426
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1448
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16653
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1423
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 91
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16147
telemt_me_writer_teardown_success_total{mode="normal"} 18101
telemt_me_writer_teardown_noop_total 17662
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 34994
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 35450
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 35564
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 35677
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 35737
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 35761
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 35763
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 35763
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 35763
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 35763
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 35763
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 35763
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 35763
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.913532
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 35763
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 106
telemt_me_refill_failed_total 30
telemt_me_writer_restored_same_endpoint_total 391
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 29
telemt_user_connections_total{user="hello"} 1639577
telemt_user_connections_current{user="hello"} 3422
telemt_user_octets_from_client{user="hello"} 32083791717 (29.88 GB)
telemt_user_octets_to_client{user="hello"} 786741049079 (732.71 GB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1311
telemt_user_unique_ips_recent_window{user="hello"} 483
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 50769.8 (14h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2277000
telemt_connections_bad_total 253341
telemt_connections_current 3419
telemt_connections_me_current 3419
telemt_handshake_timeouts_total 68769
telemt_upstream_connect_attempt_total 20931
telemt_upstream_connect_success_total 20879
telemt_upstream_connect_attempts_per_request{bucket="1"} 20879
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9406
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11380
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 24
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 69
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 746
telemt_me_reconnect_success_total 502
telemt_me_reader_eof_total 452
telemt_me_idle_close_by_peer_total 452
telemt_me_route_drop_no_conn_total 657722
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1636059
telemt_me_endpoint_quarantine_total 393
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 392
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
telemt_desync_total 7714
telemt_desync_full_logged_total 2630
telemt_desync_suppressed_total 5084
telemt_desync_frames_bucket_total{bucket="1_2"} 2051
telemt_desync_frames_bucket_total{bucket="3_10"} 2934
telemt_desync_frames_bucket_total{bucket="gt_10"} 2729
telemt_pool_swap_total 54
telemt_pool_force_close_total 1489
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 138
telemt_me_draining_writers_reap_progress_total 18753
telemt_me_writer_removed_unexpected_total 428
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1464
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17748
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1376
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 113
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17264
telemt_me_writer_teardown_success_total{mode="normal"} 19212
telemt_me_writer_teardown_noop_total 18756
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 37283
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 37728
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 37840
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 37939
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 37968
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 37968
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 37968
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 37968
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 37968
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 37968
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 37968
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 37968
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 37968
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.725668
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 37968
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 138
telemt_me_refill_failed_total 14
telemt_me_writer_restored_same_endpoint_total 438
telemt_me_writer_restored_fallback_total 3
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 33
telemt_user_connections_total{user="hello"} 1633485
telemt_user_connections_current{user="hello"} 3419
telemt_user_octets_from_client{user="hello"} 38319270844 (35.69 GB)
telemt_user_octets_to_client{user="hello"} 798316835696 (743.49 GB)
telemt_user_unique_ips_current{user="hello"} 1211
telemt_user_unique_ips_recent_window{user="hello"} 464
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 50809.1 (14h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7016578
telemt_connections_bad_total 434392
telemt_connections_current 5252
telemt_connections_me_current 5252
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 255960
telemt_upstream_connect_attempt_total 60073
telemt_upstream_connect_success_total 57401
telemt_upstream_connect_fail_total 1950
telemt_upstream_connect_attempts_per_request{bucket="1"} 59351
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40484
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14862
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2055
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1950
telemt_me_keepalive_timeout_total 59
telemt_me_reconnect_attempts_total 2979
telemt_me_reconnect_success_total 1047
telemt_me_reader_eof_total 752
telemt_me_idle_close_by_peer_total 751
telemt_me_route_drop_no_conn_total 11880918
telemt_me_route_drop_channel_closed_total 45
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5876508
telemt_me_endpoint_quarantine_total 392
telemt_me_single_endpoint_outage_enter_total 55
telemt_me_single_endpoint_outage_exit_total 55
telemt_me_single_endpoint_outage_reconnect_attempt_total 117
telemt_me_single_endpoint_outage_reconnect_success_total 25
telemt_me_single_endpoint_quarantine_bypass_total 117
telemt_me_single_endpoint_shadow_rotate_total 403
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
telemt_me_writers_active_current 79
telemt_desync_total 11453
telemt_desync_full_logged_total 3666
telemt_desync_suppressed_total 7787
telemt_desync_frames_bucket_total{bucket="1_2"} 2517
telemt_desync_frames_bucket_total{bucket="3_10"} 5005
telemt_desync_frames_bucket_total{bucket="gt_10"} 3931
telemt_pool_swap_total 51
telemt_pool_force_close_total 1607
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 320
telemt_me_draining_writers_reap_progress_total 16993
telemt_me_writer_removed_unexpected_total 1017
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2189
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15732
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1387
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 220
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15386
telemt_me_writer_teardown_success_total{mode="normal"} 17921
telemt_me_writer_teardown_noop_total 17002
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 32157
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 33126
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 33742
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 34390
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 34769
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 34907
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 34923
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 34923
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 34923
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 34923
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 34923
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 34923
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 34923
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 42.212008
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 34923
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 320
telemt_me_refill_failed_total 71
telemt_me_writer_restored_same_endpoint_total 737
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 272
telemt_user_connections_total{user="hello"} 5910875
telemt_user_connections_current{user="hello"} 5252
telemt_user_octets_from_client{user="hello"} 51727101448 (48.17 GB)
telemt_user_octets_to_client{user="hello"} 611632686783 (569.63 GB)
telemt_user_msgs_from_client{user="hello"} 126757
telemt_user_msgs_to_client{user="hello"} 447030
telemt_user_unique_ips_current{user="hello"} 1851
telemt_user_unique_ips_recent_window{user="hello"} 990
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 50776.4 (14h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2280264
telemt_connections_bad_total 273656
telemt_connections_current 3395
telemt_connections_me_current 3395
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 46347
telemt_upstream_connect_attempt_total 22366
telemt_upstream_connect_success_total 22136
telemt_upstream_connect_fail_total 208
telemt_upstream_connect_attempts_per_request{bucket="1"} 22344
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10674
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11416
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 208
telemt_me_reconnect_attempts_total 2115
telemt_me_reconnect_success_total 704
telemt_me_reader_eof_total 713
telemt_me_idle_close_by_peer_total 713
telemt_me_route_drop_no_conn_total 782286
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 33
telemt_me_route_drop_queue_full_profile_total{profile="high"} 33
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1726262
telemt_me_endpoint_quarantine_total 314
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 393
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
telemt_me_writers_active_current 46
telemt_desync_total 7942
telemt_desync_full_logged_total 2884
telemt_desync_suppressed_total 5058
telemt_desync_frames_bucket_total{bucket="1_2"} 1507
telemt_desync_frames_bucket_total{bucket="3_10"} 3228
telemt_desync_frames_bucket_total{bucket="gt_10"} 3207
telemt_pool_swap_total 52
telemt_pool_force_close_total 1420
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 118
telemt_me_draining_writers_reap_progress_total 18572
telemt_me_writer_removed_unexpected_total 690
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1724
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17561
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1276
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 144
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17152
telemt_me_writer_teardown_success_total{mode="normal"} 19285
telemt_me_writer_teardown_noop_total 18572
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 37523
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 37733
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 37845
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 37857
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 37857
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 37857
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 37857
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 37857
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 37857
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 37857
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 37857
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 37857
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 37857
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.773731
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 37857
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 118
telemt_me_refill_failed_total 77
telemt_me_writer_restored_same_endpoint_total 601
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 81
telemt_user_connections_total{user="hello"} 1712260
telemt_user_connections_current{user="hello"} 3395
telemt_user_octets_from_client{user="hello"} 31284143040 (29.14 GB)
telemt_user_octets_to_client{user="hello"} 781418025198 (727.75 GB)
telemt_user_msgs_from_client{user="hello"} 7339
telemt_user_msgs_to_client{user="hello"} 11522
telemt_user_unique_ips_current{user="hello"} 1362
telemt_user_unique_ips_recent_window{user="hello"} 522
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 50771.2 (14h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3320020
telemt_connections_bad_total 178195
telemt_connections_current 3570
telemt_connections_me_current 3570
telemt_handshake_timeouts_total 1403761
telemt_upstream_connect_attempt_total 20774
telemt_upstream_connect_success_total 20740
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 20743
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9313
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11144
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 283
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 613
telemt_me_reconnect_success_total 310
telemt_me_reader_eof_total 317
telemt_me_idle_close_by_peer_total 317
telemt_me_route_drop_no_conn_total 614571
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1536010
telemt_me_endpoint_quarantine_total 384
telemt_me_single_endpoint_shadow_rotate_total 402
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
telemt_me_writers_active_current 42
telemt_desync_total 7525
telemt_desync_full_logged_total 2671
telemt_desync_suppressed_total 4854
telemt_desync_frames_bucket_total{bucket="1_2"} 1344
telemt_desync_frames_bucket_total{bucket="3_10"} 3013
telemt_desync_frames_bucket_total{bucket="gt_10"} 3168
telemt_pool_swap_total 56
telemt_pool_force_close_total 1379
telemt_me_writer_close_signal_drop_total 106
telemt_me_draining_writers_reap_progress_total 18640
telemt_me_writer_removed_unexpected_total 305
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1187
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17779
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1361
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 18
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17261
telemt_me_writer_teardown_success_total{mode="normal"} 18966
telemt_me_writer_teardown_noop_total 18640
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 37415
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 37557
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 37596
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 37606
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 37606
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 37606
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 37606
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 37606
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 37606
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 37606
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 37606
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 37606
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 37606
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.016110
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 37606
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 106
telemt_me_refill_failed_total 16
telemt_me_writer_restored_same_endpoint_total 276
telemt_me_writer_restored_fallback_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 27
telemt_user_connections_total{user="hello"} 1531406
telemt_user_connections_current{user="hello"} 3570
telemt_user_octets_from_client{user="hello"} 27472913024 (25.59 GB)
telemt_user_octets_to_client{user="hello"} 747744851508 (696.39 GB)
telemt_user_unique_ips_current{user="hello"} 1331
telemt_user_unique_ips_recent_window{user="hello"} 525
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 48762.6 (13h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 678928
telemt_connections_bad_total 22487
telemt_connections_current 636
telemt_connections_me_current 636
telemt_handshake_timeouts_total 253484
telemt_upstream_connect_attempt_total 23659
telemt_upstream_connect_success_total 23657
telemt_upstream_connect_attempts_per_request{bucket="1"} 23657
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9806
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13789
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 62
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 1037
telemt_me_reconnect_success_total 383
telemt_me_reader_eof_total 384
telemt_me_idle_close_by_peer_total 384
telemt_me_route_drop_no_conn_total 145611
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 348850
telemt_me_endpoint_quarantine_total 463
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 414
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
telemt_desync_total 2278
telemt_desync_full_logged_total 899
telemt_desync_suppressed_total 1379
telemt_desync_frames_bucket_total{bucket="1_2"} 385
telemt_desync_frames_bucket_total{bucket="3_10"} 844
telemt_desync_frames_bucket_total{bucket="gt_10"} 1049
telemt_pool_swap_total 54
telemt_pool_force_close_total 1162
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 80
telemt_me_draining_writers_reap_progress_total 21140
telemt_me_writer_removed_unexpected_total 365
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1539
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19970
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1159
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19978
telemt_me_writer_teardown_success_total{mode="normal"} 21509
telemt_me_writer_teardown_noop_total 21140
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 42280
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 42568
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 42620
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 42643
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 42649
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 42649
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 42649
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 42649
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 42649
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 42649
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 42649
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 42649
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 42649
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.271449
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 42649
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 80
telemt_me_refill_failed_total 34
telemt_me_writer_restored_same_endpoint_total 313
telemt_me_writer_restored_fallback_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 48
telemt_user_connections_total{user="hello"} 348976
telemt_user_connections_current{user="hello"} 636
telemt_user_octets_from_client{user="hello"} 5182137739 (4.83 GB)
telemt_user_octets_to_client{user="hello"} 134340736929 (125.11 GB)
telemt_user_msgs_from_client{user="hello"} 804
telemt_user_msgs_to_client{user="hello"} 1943
telemt_user_unique_ips_current{user="hello"} 258
telemt_user_unique_ips_recent_window{user="hello"} 107
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 50781.0 (14h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2413644
telemt_connections_bad_total 222904
telemt_connections_current 4045
telemt_connections_me_current 4045
telemt_handshake_timeouts_total 58544
telemt_upstream_connect_attempt_total 21614
telemt_upstream_connect_success_total 21520
telemt_upstream_connect_fail_total 64
telemt_upstream_connect_attempts_per_request{bucket="1"} 21584
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10766
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10729
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 64
telemt_me_reconnect_attempts_total 855
telemt_me_reconnect_success_total 481
telemt_me_reader_eof_total 446
telemt_me_idle_close_by_peer_total 446
telemt_me_route_drop_no_conn_total 628955
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1905530
telemt_me_endpoint_quarantine_total 402
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 400
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
telemt_desync_total 7487
telemt_desync_full_logged_total 2512
telemt_desync_suppressed_total 4975
telemt_desync_frames_bucket_total{bucket="1_2"} 1818
telemt_desync_frames_bucket_total{bucket="3_10"} 2815
telemt_desync_frames_bucket_total{bucket="gt_10"} 2854
telemt_pool_swap_total 56
telemt_pool_force_close_total 1401
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 139
telemt_me_draining_writers_reap_progress_total 19446
telemt_me_writer_removed_unexpected_total 440
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1459
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18441
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1377
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 24
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18045
telemt_me_writer_teardown_success_total{mode="normal"} 19900
telemt_me_writer_teardown_noop_total 19446
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 38956
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 39191
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 39250
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 39339
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 39346
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 39346
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 39346
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 39346
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 39346
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 39346
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 39346
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 39346
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 39346
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.103127
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 39346
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 139
telemt_me_refill_failed_total 19
telemt_me_writer_restored_same_endpoint_total 430
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 1899439
telemt_user_connections_current{user="hello"} 4045
telemt_user_octets_from_client{user="hello"} 41190474484 (38.36 GB)
telemt_user_octets_to_client{user="hello"} 891618552016 (830.38 GB)
telemt_user_unique_ips_current{user="hello"} 1429
telemt_user_unique_ips_recent_window{user="hello"} 636
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 50777.7 (14h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2219644
telemt_connections_bad_total 176754
telemt_connections_current 3706
telemt_connections_me_current 3706
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 54651
telemt_upstream_connect_attempt_total 37831
telemt_upstream_connect_success_total 37607
telemt_upstream_connect_fail_total 181
telemt_upstream_connect_attempts_per_request{bucket="1"} 37788
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24103
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12410
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 514
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 580
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 181
telemt_me_reconnect_attempts_total 3093
telemt_me_reconnect_success_total 628
telemt_me_reader_eof_total 554
telemt_me_idle_close_by_peer_total 554
telemt_me_seq_mismatch_total 26
telemt_me_route_drop_no_conn_total 628964
telemt_me_route_drop_channel_closed_total 41
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1790838
telemt_me_endpoint_quarantine_total 443
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 399
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
telemt_desync_total 6744
telemt_desync_full_logged_total 2296
telemt_desync_suppressed_total 4448
telemt_desync_frames_bucket_total{bucket="1_2"} 1798
telemt_desync_frames_bucket_total{bucket="3_10"} 2501
telemt_desync_frames_bucket_total{bucket="gt_10"} 2445
telemt_pool_swap_total 55
telemt_pool_force_close_total 1350
telemt_me_writer_close_signal_drop_total 121
telemt_me_draining_writers_reap_progress_total 18655
telemt_me_writer_removed_unexpected_total 564
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1721
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17525
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1267
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 83
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17305
telemt_me_writer_teardown_success_total{mode="normal"} 19246
telemt_me_writer_teardown_noop_total 18656
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 37438
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 37693
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 37827
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 37896
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 37902
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 37902
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 37902
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 37902
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 37902
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 37902
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 37902
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 37902
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 37902
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.548918
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 37902
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 121
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 485
telemt_me_writer_restored_fallback_total 32
telemt_me_async_recovery_trigger_total 45
telemt_me_writer_removed_unexpected_minus_restored_total 47
telemt_user_connections_total{user="hello"} 1801994
telemt_user_connections_current{user="hello"} 3706
telemt_user_octets_from_client{user="hello"} 32840732457 (30.59 GB)
telemt_user_octets_to_client{user="hello"} 798148228612 (743.33 GB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1346
telemt_user_unique_ips_recent_window{user="hello"} 518
```